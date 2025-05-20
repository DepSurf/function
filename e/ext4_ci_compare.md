# Function: <code>ext4_ci_compare</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int ext4_ci_compare(const struct inode *parent, const struct qstr *name, const struct qstr *entry, bool quick);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813ac760)
Location: fs/ext4/namei.c:1282
Inline: True
Direct callers:
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
  - fs/ext4/namei.c:ext4_search_dir
```
**Symbols:**

```
ffffffff813ac760-ffffffff813ac7e0: ext4_ci_compare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int ext4_ci_compare(const struct inode *parent, const struct qstr *name, const struct qstr *entry, bool quick);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813c5690)
Location: fs/ext4/namei.c:1282
Inline: True
Direct callers:
  - fs/ext4/dir.c:ext4_d_compare
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
  - fs/ext4/namei.c:ext4_search_dir
```
**Symbols:**

```
ffffffff813c5690-ffffffff813c5710: ext4_ci_compare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_ci_compare(const struct inode *parent, const struct qstr *name, const struct qstr *entry, bool quick);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81411b00)
Location: fs/ext4/namei.c:1286
Inline: False
Direct callers:
  - fs/ext4/dir.c:ext4_d_compare
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
  - fs/ext4/namei.c:ext4_search_dir
```
**Symbols:**

```
ffffffff81411b00-ffffffff81411b80: ext4_ci_compare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_ci_compare(const struct inode *parent, const struct qstr *name, const struct qstr *entry, bool quick);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81424fb0)
Location: fs/ext4/namei.c:1275
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
  - fs/ext4/namei.c:ext4_search_dir
```
**Symbols:**

```
ffffffff81424fb0-ffffffff81425029: ext4_ci_compare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_ci_compare(const struct inode *parent, const struct qstr *name, u8 *de_name, size_t de_name_len, bool quick);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81429700)
Location: fs/ext4/namei.c:1328
Inline: False
```
**Symbols:**

```
ffffffff81429700-ffffffff81429838: ext4_ci_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_ci_compare(const struct inode *parent, const struct qstr *name, u8 *de_name, size_t de_name_len, bool quick);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8147d4f0)
Location: fs/ext4/namei.c:1329
Inline: False
```
**Symbols:**

```
ffffffff8147d4f0-ffffffff8147d628: ext4_ci_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_ci_compare(const struct inode *parent, const struct qstr *name, u8 *de_name, size_t de_name_len, bool quick);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff814ffdc0)
Location: fs/ext4/namei.c:1375
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_match
  - fs/ext4/namei.c:ext4_match
```
**Symbols:**

```
ffffffff814ffdc0-ffffffff814fff0d: ext4_ci_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_ci_compare(const struct inode *parent, const struct qstr *name, u8 *de_name, size_t de_name_len, bool quick);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8159a5a0)
Location: fs/ext4/namei.c:1380
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_match
  - fs/ext4/namei.c:ext4_match
```
**Symbols:**

```
ffffffff8159a5a0-ffffffff8159a6ed: ext4_ci_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_ci_compare(const struct inode *parent, const struct qstr *name, u8 *de_name, size_t de_name_len, bool quick);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff815d0e40)
Location: fs/ext4/namei.c:1397
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_match
  - fs/ext4/namei.c:ext4_match
```
**Symbols:**

```
ffffffff815d0e40-ffffffff815d0f8d: ext4_ci_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_ci_compare(const struct inode *parent, const struct qstr *name, u8 *de_name, size_t de_name_len, bool quick);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81609600)
Location: fs/ext4/namei.c:1401
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_match
  - fs/ext4/namei.c:ext4_match
```
**Symbols:**

```
ffffffff81609600-ffffffff8160974d: ext4_ci_compare (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int ext4_ci_compare(const struct inode *parent, const struct qstr *name, const struct qstr *entry, bool quick);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffff80001049d198)
Location: fs/ext4/namei.c:1282
Inline: True
Direct callers:
  - fs/ext4/dir.c:ext4_d_compare
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
  - fs/ext4/namei.c:ext4_search_dir
```
**Symbols:**

```
ffff80001049d198-ffff80001049d244: ext4_ci_compare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int ext4_ci_compare(const struct inode *parent, const struct qstr *name, const struct qstr *entry, bool quick);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (c065efd0)
Location: fs/ext4/namei.c:1282
Inline: True
Direct callers:
  - fs/ext4/dir.c:ext4_d_compare
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
  - fs/ext4/namei.c:ext4_search_dir
```
**Symbols:**

```
c065efd0-c065f064: ext4_ci_compare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int ext4_ci_compare(const struct inode *parent, const struct qstr *name, const struct qstr *entry, bool quick);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (c0000000005c8520)
Location: fs/ext4/namei.c:1282
Inline: True
Direct callers:
  - fs/ext4/dir.c:ext4_d_compare
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
  - fs/ext4/namei.c:ext4_search_dir
```
**Symbols:**

```
c0000000005c8520-c0000000005c8600: ext4_ci_compare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int ext4_ci_compare(const struct inode *parent, const struct qstr *name, const struct qstr *entry, bool quick);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffe00031ffd4)
Location: fs/ext4/namei.c:1282
Inline: True
Direct callers:
  - fs/ext4/dir.c:ext4_d_compare
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
  - fs/ext4/namei.c:ext4_search_dir
```
**Symbols:**

```
ffffffe00031ffd4-ffffffe000320070: ext4_ci_compare (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int ext4_ci_compare(const struct inode *parent, const struct qstr *name, const struct qstr *entry, bool quick);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813bdc70)
Location: fs/ext4/namei.c:1282
Inline: True
Direct callers:
  - fs/ext4/dir.c:ext4_d_compare
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
  - fs/ext4/namei.c:ext4_search_dir
```
**Symbols:**

```
ffffffff813bdc70-ffffffff813bdcf0: ext4_ci_compare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int ext4_ci_compare(const struct inode *parent, const struct qstr *name, const struct qstr *entry, bool quick);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813ae700)
Location: fs/ext4/namei.c:1282
Inline: True
Direct callers:
  - fs/ext4/dir.c:ext4_d_compare
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
  - fs/ext4/namei.c:ext4_search_dir
```
**Symbols:**

```
ffffffff813ae700-ffffffff813ae780: ext4_ci_compare (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int ext4_ci_compare(const struct inode *parent, const struct qstr *name, const struct qstr *entry, bool quick);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813d0200)
Location: fs/ext4/namei.c:1282
Inline: True
Direct callers:
  - fs/ext4/dir.c:ext4_d_compare
  - fs/ext4/namei.c:ext4_find_dest_de
  - fs/ext4/namei.c:ext4_search_dir
  - fs/ext4/namei.c:ext4_search_dir
```
**Symbols:**

```
ffffffff813d0200-ffffffff813d0280: ext4_ci_compare (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u8 *de_name</code>
</li>
<li>
<b>Param added. </b>
<code>size_t de_name_len</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct qstr *entry</code>
</li>
<li>
<b>Param reordered. </b>
<code>parent, name, entry, quick</code> ➡️ <code>parent, name, de_name, de_name_len, quick</code>
</li>
</ul>
</details>
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
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
