# Function: <code>__aa_fs_remove_rawdata</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __aa_fs_remove_rawdata(struct aa_loaddata *rawdata);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff813dbf4e)
Location: security/apparmor/apparmorfs.c:1336
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
**Symbols:**

```
ffffffff813d9ba0-ffffffff813d9c0a: __aa_fs_remove_rawdata.part.27 (STB_LOCAL)
ffffffff813db830-ffffffff813db849: __aa_fs_remove_rawdata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __aa_fs_remove_rawdata(struct aa_loaddata *rawdata);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff814029ce)
Location: security/apparmor/apparmorfs.c:1335
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
**Symbols:**

```
ffffffff813ff730-ffffffff813ff795: __aa_fs_remove_rawdata.part.29 (STB_LOCAL)
ffffffff81402320-ffffffff81402339: __aa_fs_remove_rawdata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __aa_fs_remove_rawdata(struct aa_loaddata *rawdata);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8143394e)
Location: security/apparmor/apparmorfs.c:1332
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
**Symbols:**

```
ffffffff814305d0-ffffffff81430640: __aa_fs_remove_rawdata.part.34 (STB_LOCAL)
ffffffff81433280-ffffffff81433298: __aa_fs_remove_rawdata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __aa_fs_remove_rawdata(struct aa_loaddata *rawdata);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8145064e)
Location: security/apparmor/apparmorfs.c:1330
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
**Symbols:**

```
ffffffff8144d630-ffffffff8144d6a0: __aa_fs_remove_rawdata.part.34 (STB_LOCAL)
ffffffff8144ff80-ffffffff8144ff98: __aa_fs_remove_rawdata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __aa_fs_remove_rawdata(struct aa_loaddata *rawdata);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8147e133)
Location: security/apparmor/apparmorfs.c:1335
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
**Symbols:**

```
ffffffff8147b300-ffffffff8147b370: __aa_fs_remove_rawdata.part.0 (STB_LOCAL)
ffffffff8147da90-ffffffff8147daa8: __aa_fs_remove_rawdata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __aa_fs_remove_rawdata(struct aa_loaddata *rawdata);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81497e33)
Location: security/apparmor/apparmorfs.c:1303
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
**Symbols:**

```
ffffffff81494fd0-ffffffff81495040: __aa_fs_remove_rawdata.part.0 (STB_LOCAL)
ffffffff81497770-ffffffff81497788: __aa_fs_remove_rawdata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __aa_fs_remove_rawdata(struct aa_loaddata *rawdata);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff814effbf)
Location: security/apparmor/apparmorfs.c:1415
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
Direct callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
**Symbols:**

```
ffffffff814ef6d0-ffffffff814ef78e: __aa_fs_remove_rawdata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __aa_fs_remove_rawdata(struct aa_loaddata *rawdata);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8150d43f)
Location: security/apparmor/apparmorfs.c:1415
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
Direct callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
**Symbols:**

```
ffffffff8150cb50-ffffffff8150cc0e: __aa_fs_remove_rawdata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __aa_fs_remove_rawdata(struct aa_loaddata *rawdata);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81513e4f)
Location: security/apparmor/apparmorfs.c:1415
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
Direct callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
**Symbols:**

```
ffffffff81513570-ffffffff8151362e: __aa_fs_remove_rawdata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __aa_fs_remove_rawdata(struct aa_loaddata *rawdata);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81571c43)
Location: security/apparmor/apparmorfs.c:1415
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
Direct callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
**Symbols:**

```
ffffffff81571170-ffffffff81571291: __aa_fs_remove_rawdata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __aa_fs_remove_rawdata(struct aa_loaddata *rawdata);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8160ea81)
Location: security/apparmor/apparmorfs.c:1429
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
Direct callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
**Symbols:**

```
ffffffff8160def0-ffffffff8160e026: __aa_fs_remove_rawdata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __aa_fs_remove_rawdata(struct aa_loaddata *rawdata);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff816c0d41)
Location: security/apparmor/apparmorfs.c:1610
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
Direct callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
**Symbols:**

```
ffffffff816c0130-ffffffff816c0266: __aa_fs_remove_rawdata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __aa_fs_remove_rawdata(struct aa_loaddata *rawdata);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff816f9840)
Location: security/apparmor/apparmorfs.c:1658
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
Direct callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
**Symbols:**

```
ffffffff816f8c30-ffffffff816f8d66: __aa_fs_remove_rawdata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __aa_fs_remove_rawdata(struct aa_loaddata *rawdata);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff817365e0)
Location: security/apparmor/apparmorfs.c:1657
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
Direct callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
**Symbols:**

```
ffffffff817359f0-ffffffff81735b26: __aa_fs_remove_rawdata (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __aa_fs_remove_rawdata(struct aa_loaddata *rawdata);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/apparmorfs.c (ffff80001058d9a8)
Location: security/apparmor/apparmorfs.c:1303
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
**Symbols:**

```
ffff80001058aff8-ffff80001058b070: __aa_fs_remove_rawdata.part.0 (STB_LOCAL)
ffff80001058d308-ffff80001058d33c: __aa_fs_remove_rawdata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __aa_fs_remove_rawdata(struct aa_loaddata *rawdata);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/apparmorfs.c (c073e830)
Location: security/apparmor/apparmorfs.c:1303
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
**Symbols:**

```
c073bb8c-c073bc08: __aa_fs_remove_rawdata.part.0 (STB_LOCAL)
c073e13c-c073e164: __aa_fs_remove_rawdata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __aa_fs_remove_rawdata(struct aa_loaddata *rawdata);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/apparmorfs.c (c0000000007001f0)
Location: security/apparmor/apparmorfs.c:1303
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
**Symbols:**

```
c0000000006fc3f0-c0000000006fc4b4: __aa_fs_remove_rawdata.part.0 (STB_LOCAL)
c0000000006ff930-c0000000006ff950: __aa_fs_remove_rawdata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __aa_fs_remove_rawdata(struct aa_loaddata *rawdata);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffe0003dbae4)
Location: security/apparmor/apparmorfs.c:1303
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
Direct callers:
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
**Symbols:**

```
ffffffe0003db4ac-ffffffe0003db512: __aa_fs_remove_rawdata (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __aa_fs_remove_rawdata(struct aa_loaddata *rawdata);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81490413)
Location: security/apparmor/apparmorfs.c:1303
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
**Symbols:**

```
ffffffff8148d5b0-ffffffff8148d620: __aa_fs_remove_rawdata.part.0 (STB_LOCAL)
ffffffff8148fd50-ffffffff8148fd68: __aa_fs_remove_rawdata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __aa_fs_remove_rawdata(struct aa_loaddata *rawdata);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81480e33)
Location: security/apparmor/apparmorfs.c:1303
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
**Symbols:**

```
ffffffff8147dfd0-ffffffff8147e040: __aa_fs_remove_rawdata.part.0 (STB_LOCAL)
ffffffff81480770-ffffffff81480788: __aa_fs_remove_rawdata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __aa_fs_remove_rawdata(struct aa_loaddata *rawdata);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8148c4b3)
Location: security/apparmor/apparmorfs.c:1303
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
**Symbols:**

```
ffffffff81489650-ffffffff814896c0: __aa_fs_remove_rawdata.part.0 (STB_LOCAL)
ffffffff8148bdf0-ffffffff8148be08: __aa_fs_remove_rawdata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __aa_fs_remove_rawdata(struct aa_loaddata *rawdata);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff814a42f3)
Location: security/apparmor/apparmorfs.c:1303
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/policy_unpack.c:do_loaddata_free
```
**Symbols:**

```
ffffffff814a12b0-ffffffff814a1320: __aa_fs_remove_rawdata.part.0 (STB_LOCAL)
ffffffff814a3c30-ffffffff814a3c48: __aa_fs_remove_rawdata (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
