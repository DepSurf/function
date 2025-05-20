# Function: <code>generic_remap_checks</code>

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
int generic_remap_checks(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t *req_count, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812028c0)
Location: mm/filemap.c:2972
Inline: False
Direct callers:
  - fs/read_write.c:generic_remap_file_range_prep
```
**Symbols:**

```
ffffffff812028c0-ffffffff81202a6e: generic_remap_checks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int generic_remap_checks(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t *req_count, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81219b80)
Location: mm/filemap.c:3018
Inline: False
Direct callers:
  - fs/read_write.c:generic_remap_file_range_prep
```
**Symbols:**

```
ffffffff81219b80-ffffffff81219cf5: generic_remap_checks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int generic_remap_checks(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t *req_count, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812274f0)
Location: mm/filemap.c:2975
Inline: False
Direct callers:
  - fs/read_write.c:generic_remap_file_range_prep
```
**Symbols:**

```
ffffffff812274f0-ffffffff81227665: generic_remap_checks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int generic_remap_checks(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t *req_count, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81253d90)
Location: mm/filemap.c:2984
Inline: False
Direct callers:
  - fs/read_write.c:generic_remap_file_range_prep
```
**Symbols:**

```
ffffffff81253d90-ffffffff81253f09: generic_remap_checks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/remap_range.c (ffffffff813663e0)
Location: fs/remap_range.c:29
Inline: True
Direct callers:
  - fs/remap_range.c:generic_remap_file_range_prep
```
**Symbols:**

```
ffffffff813663e0-ffffffff81366554: generic_remap_checks.isra.0 (STB_LOCAL)
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
In fs/remap_range.c (ffffffff8136d66b)
Location: fs/remap_range.c:29
Inline: True
Inline callers:
  - fs/remap_range.c:generic_remap_file_range_prep
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
In fs/remap_range.c (ffffffff813bc34b)
Location: fs/remap_range.c:29
Inline: True
Inline callers:
  - fs/remap_range.c:generic_remap_file_range_prep
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/remap_range.c (ffffffff81441710)
Location: fs/remap_range.c:29
Inline: True
Direct callers:
  - fs/remap_range.c:generic_remap_file_range_prep
```
**Symbols:**

```
ffffffff81441710-ffffffff814418d4: generic_remap_checks.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/remap_range.c (ffffffff814d06c0)
Location: fs/remap_range.c:30
Inline: True
Direct callers:
  - fs/remap_range.c:__generic_remap_file_range_prep
```
**Symbols:**

```
ffffffff814d06c0-ffffffff814d0884: generic_remap_checks.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/remap_range.c (ffffffff81506dc0)
Location: fs/remap_range.c:31
Inline: True
Direct callers:
  - fs/remap_range.c:__generic_remap_file_range_prep
```
**Symbols:**

```
ffffffff81506dc0-ffffffff81506f84: generic_remap_checks.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/remap_range.c (ffffffff8153bba0)
Location: fs/remap_range.c:31
Inline: True
Direct callers:
  - fs/remap_range.c:__generic_remap_file_range_prep
```
**Symbols:**

```
ffffffff8153bba0-ffffffff8153bd64: generic_remap_checks.isra.0 (STB_LOCAL)
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
int generic_remap_checks(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t *req_count, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffff8000102b4300)
Location: mm/filemap.c:2975
Inline: False
Direct callers:
  - fs/read_write.c:generic_remap_file_range_prep
```
**Symbols:**

```
ffff8000102b4300-ffff8000102b4498: generic_remap_checks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int generic_remap_checks(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t *req_count, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c04e1ae8)
Location: mm/filemap.c:2975
Inline: False
Direct callers:
  - fs/read_write.c:generic_remap_file_range_prep
```
**Symbols:**

```
c04e1ae8-c04e1eb4: generic_remap_checks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int generic_remap_checks(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t *req_count, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c00000000036bc50)
Location: mm/filemap.c:2975
Inline: False
Direct callers:
  - fs/read_write.c:generic_remap_file_range_prep
```
**Symbols:**

```
c00000000036bc50-c00000000036be7c: generic_remap_checks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int generic_remap_checks(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t *req_count, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffe0001d9b92)
Location: mm/filemap.c:2975
Inline: False
Direct callers:
  - fs/read_write.c:generic_remap_file_range_prep
```
**Symbols:**

```
ffffffe0001d9b92-ffffffe0001d9cc2: generic_remap_checks (STB_GLOBAL)
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
int generic_remap_checks(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t *req_count, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121fb40)
Location: mm/filemap.c:2975
Inline: False
Direct callers:
  - fs/read_write.c:generic_remap_file_range_prep
```
**Symbols:**

```
ffffffff8121fb40-ffffffff8121fcb5: generic_remap_checks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int generic_remap_checks(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t *req_count, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81212cf0)
Location: mm/filemap.c:2975
Inline: False
Direct callers:
  - fs/read_write.c:generic_remap_file_range_prep
```
**Symbols:**

```
ffffffff81212cf0-ffffffff81212e65: generic_remap_checks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int generic_remap_checks(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t *req_count, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121d8e0)
Location: mm/filemap.c:2975
Inline: False
Direct callers:
  - fs/read_write.c:generic_remap_file_range_prep
```
**Symbols:**

```
ffffffff8121d8e0-ffffffff8121da55: generic_remap_checks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int generic_remap_checks(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, loff_t *req_count, unsigned int remap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8122c950)
Location: mm/filemap.c:2975
Inline: False
Direct callers:
  - fs/read_write.c:generic_remap_file_range_prep
```
**Symbols:**

```
ffffffff8122c950-ffffffff8122cac5: generic_remap_checks (STB_GLOBAL)
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
