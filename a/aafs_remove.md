# Function: <code>aafs_remove</code>

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

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff813dc09e)
Location: security/apparmor/apparmorfs.c:347
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:remove_rawdata_dents
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:remove_rawdata_dents
```
**Symbols:**

```
ffffffff813d90f0-ffffffff813d9176: aafs_remove.part.20 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81402b45)
Location: security/apparmor/apparmorfs.c:348
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:remove_rawdata_dents
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:remove_rawdata_dents
```
**Symbols:**

```
ffffffff813ff160-ffffffff813ff1e6: aafs_remove.part.20 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81433abc)
Location: security/apparmor/apparmorfs.c:345
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:remove_rawdata_dents
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:remove_rawdata_dents
```
**Symbols:**

```
ffffffff814300f0-ffffffff81430176: aafs_remove.part.26 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff814507bc)
Location: security/apparmor/apparmorfs.c:345
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:remove_rawdata_dents
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:remove_rawdata_dents
```
**Symbols:**

```
ffffffff8144cc40-ffffffff8144ccce: aafs_remove.part.26 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void aafs_remove(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8147a400)
Location: security/apparmor/apparmorfs.c:350
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:remove_rawdata_dents
```
**Symbols:**

```
ffffffff8147a400-ffffffff8147a4a7: aafs_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void aafs_remove(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81494100)
Location: security/apparmor/apparmorfs.c:318
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:remove_rawdata_dents
```
**Symbols:**

```
ffffffff81494100-ffffffff814941a7: aafs_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void aafs_remove(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff814eb560)
Location: security/apparmor/apparmorfs.c:348
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
```
**Symbols:**

```
ffffffff814eb560-ffffffff814eb607: aafs_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void aafs_remove(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81508940)
Location: security/apparmor/apparmorfs.c:348
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
```
**Symbols:**

```
ffffffff81508940-ffffffff815089e7: aafs_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void aafs_remove(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8150f4b0)
Location: security/apparmor/apparmorfs.c:348
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
```
**Symbols:**

```
ffffffff8150f4b0-ffffffff8150f557: aafs_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void aafs_remove(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8156d010)
Location: security/apparmor/apparmorfs.c:348
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
```
**Symbols:**

```
ffffffff8156d010-ffffffff8156d0b7: aafs_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void aafs_remove(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81609600)
Location: security/apparmor/apparmorfs.c:351
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
```
**Symbols:**

```
ffffffff81609600-ffffffff816096af: aafs_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void aafs_remove(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff816bb100)
Location: security/apparmor/apparmorfs.c:352
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
```
**Symbols:**

```
ffffffff816bb100-ffffffff816bb1af: aafs_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void aafs_remove(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff816f37f0)
Location: security/apparmor/apparmorfs.c:353
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
```
**Symbols:**

```
ffffffff816f37f0-ffffffff816f389f: aafs_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void aafs_remove(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81730580)
Location: security/apparmor/apparmorfs.c:353
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
```
**Symbols:**

```
ffffffff81730580-ffffffff8173062f: aafs_remove (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void aafs_remove(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffff800010589750)
Location: security/apparmor/apparmorfs.c:318
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:remove_rawdata_dents
```
**Symbols:**

```
ffff800010589750-ffff800010589800: aafs_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void aafs_remove(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (c073a96c)
Location: security/apparmor/apparmorfs.c:318
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:remove_rawdata_dents
```
**Symbols:**

```
c073a96c-c073aa14: aafs_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void aafs_remove(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (c0000000006fa780)
Location: security/apparmor/apparmorfs.c:318
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:remove_rawdata_dents
```
**Symbols:**

```
c0000000006fa780-c0000000006fa884: aafs_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void aafs_remove(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffe0003d8646)
Location: security/apparmor/apparmorfs.c:318
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:remove_rawdata_dents
```
**Symbols:**

```
ffffffe0003d8646-ffffffe0003d86f2: aafs_remove (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void aafs_remove(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8148c6e0)
Location: security/apparmor/apparmorfs.c:318
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:remove_rawdata_dents
```
**Symbols:**

```
ffffffff8148c6e0-ffffffff8148c787: aafs_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void aafs_remove(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8147d100)
Location: security/apparmor/apparmorfs.c:318
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:remove_rawdata_dents
```
**Symbols:**

```
ffffffff8147d100-ffffffff8147d1a7: aafs_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void aafs_remove(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81488780)
Location: security/apparmor/apparmorfs.c:318
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:remove_rawdata_dents
```
**Symbols:**

```
ffffffff81488780-ffffffff81488827: aafs_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void aafs_remove(struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff814a02c0)
Location: security/apparmor/apparmorfs.c:318
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:remove_rawdata_dents
```
**Symbols:**

```
ffffffff814a02c0-ffffffff814a0367: aafs_remove (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
