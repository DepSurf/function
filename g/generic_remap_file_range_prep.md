# Function: <code>generic_remap_file_range_prep</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int generic_remap_file_range_prep(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t *len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812ad030)
Location: fs/read_write.c:1876
Inline: False
```
**Symbols:**

```
ffffffff812ad030-ffffffff812ad549: generic_remap_file_range_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int generic_remap_file_range_prep(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t *len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812c99d0)
Location: fs/read_write.c:1972
Inline: False
```
**Symbols:**

```
ffffffff812c99d0-ffffffff812c9fc2: generic_remap_file_range_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int generic_remap_file_range_prep(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t *len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812db3e0)
Location: fs/read_write.c:1970
Inline: False
```
**Symbols:**

```
ffffffff812db3e0-ffffffff812db9eb: generic_remap_file_range_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int generic_remap_file_range_prep(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t *len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81311980)
Location: fs/read_write.c:2054
Inline: False
```
**Symbols:**

```
ffffffff81311980-ffffffff81311bc4: generic_remap_file_range_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int generic_remap_file_range_prep(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t *len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/remap_range.c (ffffffff81366d00)
Location: fs/remap_range.c:292
Inline: False
```
**Symbols:**

```
ffffffff81366d00-ffffffff81366f4b: generic_remap_file_range_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int generic_remap_file_range_prep(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t *len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/remap_range.c (ffffffff8136d5b0)
Location: fs/remap_range.c:292
Inline: False
```
**Symbols:**

```
ffffffff8136d5b0-ffffffff8136d939: generic_remap_file_range_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int generic_remap_file_range_prep(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t *len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/remap_range.c (0)
Location: fs/remap_range.c:280
Inline: False
```
**Symbols:**

```
ffffffff81cc430f-ffffffff81cc4355: generic_remap_file_range_prep.cold (STB_LOCAL)
ffffffff813bc290-ffffffff813bc5f5: generic_remap_file_range_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int generic_remap_file_range_prep(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t *len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/remap_range.c (0)
Location: fs/remap_range.c:275
Inline: False
```
**Symbols:**

```
ffffffff81e76c76-ffffffff81e76cab: generic_remap_file_range_prep.cold (STB_LOCAL)
ffffffff81442100-ffffffff81442350: generic_remap_file_range_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int generic_remap_file_range_prep(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t *len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/remap_range.c (ffffffff814d1680)
Location: fs/remap_range.c:358
Inline: False
```
**Symbols:**

```
ffffffff814d1680-ffffffff814d16a4: generic_remap_file_range_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int generic_remap_file_range_prep(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t *len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/remap_range.c (ffffffff81507e00)
Location: fs/remap_range.c:361
Inline: False
```
**Symbols:**

```
ffffffff81507e00-ffffffff81507e24: generic_remap_file_range_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int generic_remap_file_range_prep(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t *len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/remap_range.c (ffffffff8153cc40)
Location: fs/remap_range.c:367
Inline: False
```
**Symbols:**

```
ffffffff8153cc40-ffffffff8153cc64: generic_remap_file_range_prep (STB_GLOBAL)
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
int generic_remap_file_range_prep(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t *len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffff800010380900)
Location: fs/read_write.c:1970
Inline: False
```
**Symbols:**

```
ffff800010380900-ffff800010380b54: generic_remap_file_range_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int generic_remap_file_range_prep(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t *len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c056b204)
Location: fs/read_write.c:1970
Inline: False
```
**Symbols:**

```
c056b204-c056ba18: generic_remap_file_range_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int generic_remap_file_range_prep(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t *len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (c000000000476d30)
Location: fs/read_write.c:1970
Inline: False
```
**Symbols:**

```
c000000000476d30-c000000000477634: generic_remap_file_range_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int generic_remap_file_range_prep(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t *len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffe000255982)
Location: fs/read_write.c:1970
Inline: False
```
**Symbols:**

```
ffffffe000255982-ffffffe000255e5a: generic_remap_file_range_prep (STB_GLOBAL)
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
int generic_remap_file_range_prep(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t *len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d39c0)
Location: fs/read_write.c:1970
Inline: False
```
**Symbols:**

```
ffffffff812d39c0-ffffffff812d3fcb: generic_remap_file_range_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int generic_remap_file_range_prep(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t *len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812c4640)
Location: fs/read_write.c:1970
Inline: False
```
**Symbols:**

```
ffffffff812c4640-ffffffff812c4c4b: generic_remap_file_range_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int generic_remap_file_range_prep(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t *len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812d17d0)
Location: fs/read_write.c:1970
Inline: False
```
**Symbols:**

```
ffffffff812d17d0-ffffffff812d1ddb: generic_remap_file_range_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int generic_remap_file_range_prep(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t *len, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff812e2600)
Location: fs/read_write.c:1970
Inline: False
```
**Symbols:**

```
ffffffff812e2600-ffffffff812e2c3d: generic_remap_file_range_prep (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
