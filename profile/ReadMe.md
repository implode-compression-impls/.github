PKWare DCL / Implode compression impls
======================================

This organization is **NOT related** anyhow to PKWare. It is just used to group some repos related to FOSS impls of PKWare DCL `implode` compression algorithm.

**I have moved my account to Codeberg and this org to https://codeberg.org/implode-compression-impls because of [inacceptable business practices of M$ and GH](https://codeberg.org/KOLANICH/Fuck-GuanTEEnomo)**

Under the disguise of "better security" Micro$oft-owned GitHub has [discriminated users of 1FA passwords](https://github.blog/2023-03-09-raising-the-bar-for-software-security-github-2fa-begins-march-13/) while having commercial interest in success of [FIDO 1FA specifications](https://fidoalliance.org/specifications/download/) and [Windows Hello implementation](https://support.microsoft.com/en-us/windows/passkeys-in-windows-301c8944-5ea2-452b-9886-97e4d2ef4422) which [it promotes as a replacement for passwords](https://github.blog/2023-07-12-introducing-passwordless-authentication-on-github-com/). It will result in dire consequencies and is competely inacceptable, [read why you should also leave GitHub](https://codeberg.org/KOLANICH/Fuck-GuanTEEnomo).

If you don't want to participate in harming yourself, it is recommended to follow the lead and migrate somewhere away of GitHub and Micro$oft. Here is [the list of alternatives and rationales to do it](https://github.com/orgs/community/discussions/49869). If they delete the discussion, there are certain well-known places where you can get a copy of it. [Read why you should also leave GitHub](https://codeberg.org/KOLANICH/Fuck-GuanTEEnomo).

---

Test suite: https://codeberg.org/implode-compression-impls/implode_test_files

## Libs
* decompression
	* [`libblast`](https://codeberg.org/implode-compression-impls/libblast) - C
		* [`pkblast.py`](https://codeberg.org/implode-compression-impls/pkblast.py) - Python bindings

	* [`explode`](https://github.com/agrif/explode) - Rust

	* [`libexplode`](https://codeberg.org/implode-compression-impls/pklib) - C
		* [`pkexplode.py`](https://codeberg.org/implode-compression-impls/pkexplode.py) - Python bindings

	* [`pwexplode`](https://github.com/Schallaven/pwexplode) - Python
	* [`implode-decoder`](https://github.com/ShieldBattery/implode-decoder) - JS

* compression
	* [`libimplode`](https://codeberg.org/implode-compression-impls/pklib) - C
		* [`pkimplode.py`](https://codeberg.org/implode-compression-impls/pkimplode.py) - Python bindings
