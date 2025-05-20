# Function: <code>remove_rawdata_dents</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
void remove_rawdata_dents(struct aa_loaddata *rawdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff813d9180)
Location: security/apparmor/apparmorfs.c:1323
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
```
**Symbols:**

```
ffffffff813d9180-ffffffff813d91bf: remove_rawdata_dents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void remove_rawdata_dents(struct aa_loaddata *rawdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff813ff1f0)
Location: security/apparmor/apparmorfs.c:1322
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
```
**Symbols:**

```
ffffffff813ff1f0-ffffffff813ff22f: remove_rawdata_dents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void remove_rawdata_dents(struct aa_loaddata *rawdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81430180)
Location: security/apparmor/apparmorfs.c:1319
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
```
**Symbols:**

```
ffffffff81430180-ffffffff814301bf: remove_rawdata_dents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void remove_rawdata_dents(struct aa_loaddata *rawdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8144ccd0)
Location: security/apparmor/apparmorfs.c:1317
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
```
**Symbols:**

```
ffffffff8144ccd0-ffffffff8144cd0f: remove_rawdata_dents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void remove_rawdata_dents(struct aa_loaddata *rawdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8147a4b0)
Location: security/apparmor/apparmorfs.c:1322
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
```
**Symbols:**

```
ffffffff8147a4b0-ffffffff8147a4ef: remove_rawdata_dents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void remove_rawdata_dents(struct aa_loaddata *rawdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff814941b0)
Location: security/apparmor/apparmorfs.c:1290
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
```
**Symbols:**

```
ffffffff814941b0-ffffffff814941ef: remove_rawdata_dents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff814effd2)
Location: security/apparmor/apparmorfs.c:1402
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8150d452)
Location: security/apparmor/apparmorfs.c:1402
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81513e62)
Location: security/apparmor/apparmorfs.c:1402
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff815714a6)
Location: security/apparmor/apparmorfs.c:1402
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8160e243)
Location: security/apparmor/apparmorfs.c:1416
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff816c0493)
Location: security/apparmor/apparmorfs.c:1597
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff816f8f93)
Location: security/apparmor/apparmorfs.c:1645
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81735d53)
Location: security/apparmor/apparmorfs.c:1644
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
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
void remove_rawdata_dents(struct aa_loaddata *rawdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffff800010589800)
Location: security/apparmor/apparmorfs.c:1290
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
```
**Symbols:**

```
ffff800010589800-ffff800010589850: remove_rawdata_dents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void remove_rawdata_dents(struct aa_loaddata *rawdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (c073aa14)
Location: security/apparmor/apparmorfs.c:1290
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
```
**Symbols:**

```
c073aa14-c073aa60: remove_rawdata_dents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void remove_rawdata_dents(struct aa_loaddata *rawdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (c0000000006fa890)
Location: security/apparmor/apparmorfs.c:1290
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
```
**Symbols:**

```
c0000000006fa890-c0000000006fa910: remove_rawdata_dents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void remove_rawdata_dents(struct aa_loaddata *rawdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffe0003d86f2)
Location: security/apparmor/apparmorfs.c:1290
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aafs_ns_rmdir
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
```
**Symbols:**

```
ffffffe0003d86f2-ffffffe0003d8740: remove_rawdata_dents (STB_LOCAL)
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
void remove_rawdata_dents(struct aa_loaddata *rawdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8148c790)
Location: security/apparmor/apparmorfs.c:1290
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
```
**Symbols:**

```
ffffffff8148c790-ffffffff8148c7cf: remove_rawdata_dents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void remove_rawdata_dents(struct aa_loaddata *rawdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8147d1b0)
Location: security/apparmor/apparmorfs.c:1290
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
```
**Symbols:**

```
ffffffff8147d1b0-ffffffff8147d1ef: remove_rawdata_dents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void remove_rawdata_dents(struct aa_loaddata *rawdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81488830)
Location: security/apparmor/apparmorfs.c:1290
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
```
**Symbols:**

```
ffffffff81488830-ffffffff8148886f: remove_rawdata_dents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void remove_rawdata_dents(struct aa_loaddata *rawdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff814a0370)
Location: security/apparmor/apparmorfs.c:1290
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:__aa_fs_create_rawdata
```
**Symbols:**

```
ffffffff814a0370-ffffffff814a03af: remove_rawdata_dents (STB_LOCAL)
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
