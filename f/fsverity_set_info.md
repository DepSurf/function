# Function: <code>fsverity_set_info</code>

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
<summary>In <code>5.4</code>: ✅</summary>

```c
void fsverity_set_info(struct inode *inode, struct fsverity_info *vi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (ffffffff81350d60)
Location: fs/verity/open.c:220
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
```
**Symbols:**

```
ffffffff81350d60-ffffffff81350d89: fsverity_set_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fsverity_set_info(struct inode *inode, struct fsverity_info *vi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (ffffffff81397780)
Location: fs/verity/open.c:221
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/open.c:ensure_verity_info
```
**Symbols:**

```
ffffffff81397780-ffffffff813977c2: fsverity_set_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fsverity_set_info(struct inode *inode, struct fsverity_info *vi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (ffffffff813a91f0)
Location: fs/verity/open.c:221
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/open.c:ensure_verity_info
```
**Symbols:**

```
ffffffff813a91f0-ffffffff813a923c: fsverity_set_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fsverity_set_info(struct inode *inode, struct fsverity_info *vi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (ffffffff813b0200)
Location: fs/verity/open.c:194
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
```
**Symbols:**

```
ffffffff813b0200-ffffffff813b024c: fsverity_set_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void fsverity_set_info(struct inode *inode, struct fsverity_info *vi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (ffffffff813ffdf0)
Location: fs/verity/open.c:194
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
```
**Symbols:**

```
ffffffff813ffdf0-ffffffff813ffe3c: fsverity_set_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void fsverity_set_info(struct inode *inode, struct fsverity_info *vi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (ffffffff81473bd0)
Location: fs/verity/open.c:193
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
```
**Symbols:**

```
ffffffff81473bd0-ffffffff81473c30: fsverity_set_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fsverity_set_info(struct inode *inode, struct fsverity_info *vi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (ffffffff81505c80)
Location: fs/verity/open.c:193
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
```
**Symbols:**

```
ffffffff81505c80-ffffffff81505ce0: fsverity_set_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fsverity_set_info(struct inode *inode, struct fsverity_info *vi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (ffffffff8153cf90)
Location: fs/verity/open.c:252
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/open.c:__fsverity_file_open
```
**Symbols:**

```
ffffffff8153cf90-ffffffff8153cffd: fsverity_set_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fsverity_set_info(struct inode *inode, struct fsverity_info *vi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (ffffffff815723f0)
Location: fs/verity/open.c:252
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
  - fs/verity/open.c:__fsverity_file_open
```
**Symbols:**

```
ffffffff815723f0-ffffffff8157245d: fsverity_set_info (STB_GLOBAL)
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
void fsverity_set_info(struct inode *inode, struct fsverity_info *vi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (ffff800010412e80)
Location: fs/verity/open.c:220
Inline: True
Direct callers:
  - fs/verity/enable.c:enable_verity
```
**Symbols:**

```
ffff800010412e80-ffff800010412eec: fsverity_set_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void fsverity_set_info(struct inode *inode, struct fsverity_info *vi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (c05df238)
Location: fs/verity/open.c:220
Inline: True
Direct callers:
  - fs/verity/enable.c:enable_verity
```
**Symbols:**

```
c05df238-c05df28c: fsverity_set_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void fsverity_set_info(struct inode *inode, struct fsverity_info *vi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (c000000000520ba0)
Location: fs/verity/open.c:220
Inline: True
Direct callers:
  - fs/verity/enable.c:enable_verity
```
**Symbols:**

```
c000000000520ba0-c000000000520bec: fsverity_set_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fsverity_set_info(struct inode *inode, struct fsverity_info *vi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (ffffffe0002baa8e)
Location: fs/verity/open.c:220
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
```
**Symbols:**

```
ffffffe0002baa8e-ffffffe0002baad6: fsverity_set_info (STB_GLOBAL)
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
void fsverity_set_info(struct inode *inode, struct fsverity_info *vi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (ffffffff81349340)
Location: fs/verity/open.c:220
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
```
**Symbols:**

```
ffffffff81349340-ffffffff81349369: fsverity_set_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void fsverity_set_info(struct inode *inode, struct fsverity_info *vi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (ffffffff8133a020)
Location: fs/verity/open.c:220
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
```
**Symbols:**

```
ffffffff8133a020-ffffffff8133a049: fsverity_set_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void fsverity_set_info(struct inode *inode, struct fsverity_info *vi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (ffffffff81346e10)
Location: fs/verity/open.c:220
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
```
**Symbols:**

```
ffffffff81346e10-ffffffff81346e39: fsverity_set_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void fsverity_set_info(struct inode *inode, struct fsverity_info *vi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/verity/open.c (ffffffff8135a0f0)
Location: fs/verity/open.c:220
Inline: False
Direct callers:
  - fs/verity/enable.c:enable_verity
```
**Symbols:**

```
ffffffff8135a0f0-ffffffff8135a119: fsverity_set_info (STB_GLOBAL)
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
