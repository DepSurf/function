# Function: <code>fsverity_create_info</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct fsverity_info *fsverity_create_info(const struct inode *inode, void *_desc, size_t desc_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/open.c (0)
Location: fs/verity/open.c:147
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
```
**Symbols:**

```
ffffffff81350f6d-ffffffff81351060: fsverity_create_info.cold (STB_LOCAL)
ffffffff81350be0-ffffffff81350d55: fsverity_create_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct fsverity_info *fsverity_create_info(const struct inode *inode, void *_desc, size_t desc_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/open.c (0)
Location: fs/verity/open.c:148
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/open.c:ensure_verity_info
```
**Symbols:**

```
ffffffff813979d9-ffffffff81397acc: fsverity_create_info.cold (STB_LOCAL)
ffffffff813975f0-ffffffff81397775: fsverity_create_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct fsverity_info *fsverity_create_info(const struct inode *inode, void *_desc, size_t desc_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/open.c (0)
Location: fs/verity/open.c:148
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/open.c:ensure_verity_info
```
**Symbols:**

```
ffffffff81beb642-ffffffff81beb735: fsverity_create_info.cold (STB_LOCAL)
ffffffff813a9060-ffffffff813a91e5: fsverity_create_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct fsverity_info *fsverity_create_info(const struct inode *inode, struct fsverity_descriptor *desc, size_t desc_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/open.c (0)
Location: fs/verity/open.c:149
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
```
**Symbols:**

```
ffffffff81bdd696-ffffffff81bdd6dc: fsverity_create_info.cold (STB_LOCAL)
ffffffff813b00d0-ffffffff813b01fb: fsverity_create_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct fsverity_info *fsverity_create_info(const struct inode *inode, struct fsverity_descriptor *desc, size_t desc_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/open.c (0)
Location: fs/verity/open.c:149
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
```
**Symbols:**

```
ffffffff81cc6fe6-ffffffff81cc702c: fsverity_create_info.cold (STB_LOCAL)
ffffffff813ffcc0-ffffffff813ffde8: fsverity_create_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct fsverity_info *fsverity_create_info(const struct inode *inode, struct fsverity_descriptor *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/open.c (0)
Location: fs/verity/open.c:149
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
```
**Symbols:**

```
ffffffff81e7954e-ffffffff81e79594: fsverity_create_info.cold (STB_LOCAL)
ffffffff81473a90-ffffffff81473bca: fsverity_create_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct fsverity_info *fsverity_create_info(const struct inode *inode, struct fsverity_descriptor *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/open.c (0)
Location: fs/verity/open.c:149
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
```
**Symbols:**

```
ffffffff8206aa46-ffffffff8206aa69: fsverity_create_info.cold (STB_LOCAL)
ffffffff81505a90-ffffffff81505c66: fsverity_create_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct fsverity_info *fsverity_create_info(const struct inode *inode, struct fsverity_descriptor *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/open.c (0)
Location: fs/verity/open.c:180
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/open.c:__fsverity_file_open
```
**Symbols:**

```
ffffffff820ea8c3-ffffffff820ea904: fsverity_create_info.cold (STB_LOCAL)
ffffffff8153cd60-ffffffff8153cf74: fsverity_create_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct fsverity_info *fsverity_create_info(const struct inode *inode, struct fsverity_descriptor *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/open.c (0)
Location: fs/verity/open.c:180
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/open.c:__fsverity_file_open
```
**Symbols:**

```
ffffffff821c7571-ffffffff821c75b2: fsverity_create_info.cold (STB_LOCAL)
ffffffff815721c0-ffffffff815723d4: fsverity_create_info (STB_GLOBAL)
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
struct fsverity_info *fsverity_create_info(const struct inode *inode, void *_desc, size_t desc_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (ffff800010412c18)
Location: fs/verity/open.c:147
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
```
**Symbols:**

```
ffff800010412c18-ffff800010412e80: fsverity_create_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct fsverity_info *fsverity_create_info(const struct inode *inode, void *_desc, size_t desc_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (c05defe8)
Location: fs/verity/open.c:147
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
```
**Symbols:**

```
c05defe8-c05df238: fsverity_create_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct fsverity_info *fsverity_create_info(const struct inode *inode, void *_desc, size_t desc_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (c000000000520880)
Location: fs/verity/open.c:147
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
```
**Symbols:**

```
c000000000520880-c000000000520b9c: fsverity_create_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct fsverity_info *fsverity_create_info(const struct inode *inode, void *_desc, size_t desc_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (ffffffe0002ba86c)
Location: fs/verity/open.c:147
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
```
**Symbols:**

```
ffffffe0002ba86c-ffffffe0002baa8e: fsverity_create_info (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
struct fsverity_info *fsverity_create_info(const struct inode *inode, void *_desc, size_t desc_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/open.c (0)
Location: fs/verity/open.c:147
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
```
**Symbols:**

```
ffffffff8134954d-ffffffff81349640: fsverity_create_info.cold (STB_LOCAL)
ffffffff813491c0-ffffffff81349335: fsverity_create_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct fsverity_info *fsverity_create_info(const struct inode *inode, void *_desc, size_t desc_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/open.c (0)
Location: fs/verity/open.c:147
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
```
**Symbols:**

```
ffffffff8133a22d-ffffffff8133a320: fsverity_create_info.cold (STB_LOCAL)
ffffffff81339ea0-ffffffff8133a015: fsverity_create_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct fsverity_info *fsverity_create_info(const struct inode *inode, void *_desc, size_t desc_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/open.c (0)
Location: fs/verity/open.c:147
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
```
**Symbols:**

```
ffffffff8134701d-ffffffff81347110: fsverity_create_info.cold (STB_LOCAL)
ffffffff81346c90-ffffffff81346e05: fsverity_create_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct fsverity_info *fsverity_create_info(const struct inode *inode, void *_desc, size_t desc_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/verity/open.c (0)
Location: fs/verity/open.c:147
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
```
**Symbols:**

```
ffffffff8135a2fd-ffffffff8135a3f0: fsverity_create_info.cold (STB_LOCAL)
ffffffff81359f70-ffffffff8135a0e5: fsverity_create_info (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<code>struct fsverity_descriptor *desc</code>
</li>
<li>
<b>Param removed. </b>
<code>void *_desc</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>size_t desc_size</code>
</li>
</ul>
</details>
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
