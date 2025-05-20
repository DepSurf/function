# Function: <code>generic_copy_file_checks</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
int generic_copy_file_checks(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t *req_count, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81219d80)
Location: mm/filemap.c:3119
Inline: False
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
```
**Symbols:**

```
ffffffff81219d80-ffffffff81219e9e: generic_copy_file_checks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int generic_copy_file_checks(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t *req_count, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812276f0)
Location: mm/filemap.c:3076
Inline: False
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
```
**Symbols:**

```
ffffffff812276f0-ffffffff8122780e: generic_copy_file_checks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int generic_copy_file_checks(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t *req_count, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81253f90)
Location: mm/filemap.c:3085
Inline: False
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
```
**Symbols:**

```
ffffffff81253f90-ffffffff812540a7: generic_copy_file_checks (STB_GLOBAL)
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
In fs/read_write.c (ffffffff81320750)
Location: fs/read_write.c:1422
Inline: True
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
```
**Symbols:**

```
ffffffff81320750-ffffffff81320867: generic_copy_file_checks.constprop.0 (STB_LOCAL)
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
In fs/read_write.c (ffffffff813268e2)
Location: fs/read_write.c:1427
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
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
In fs/read_write.c (ffffffff81373e82)
Location: fs/read_write.c:1418
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
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
In fs/read_write.c (ffffffff813f2d5e)
Location: fs/read_write.c:1410
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
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
In fs/read_write.c (ffffffff8147ba13)
Location: fs/read_write.c:1405
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
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
In fs/read_write.c (ffffffff814b0596)
Location: fs/read_write.c:1404
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
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
In fs/read_write.c (ffffffff814e1d75)
Location: fs/read_write.c:1412
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
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
int generic_copy_file_checks(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t *req_count, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffff8000102b4538)
Location: mm/filemap.c:3076
Inline: False
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
```
**Symbols:**

```
ffff8000102b4538-ffff8000102b4690: generic_copy_file_checks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int generic_copy_file_checks(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t *req_count, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c04e1f48)
Location: mm/filemap.c:3076
Inline: False
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
```
**Symbols:**

```
c04e1f48-c04e2174: generic_copy_file_checks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int generic_copy_file_checks(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t *req_count, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c00000000036bf30)
Location: mm/filemap.c:3076
Inline: False
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
```
**Symbols:**

```
c00000000036bf30-c00000000036c0c8: generic_copy_file_checks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int generic_copy_file_checks(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t *req_count, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffe0001d9d36)
Location: mm/filemap.c:3076
Inline: False
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
```
**Symbols:**

```
ffffffe0001d9d36-ffffffe0001d9e1a: generic_copy_file_checks (STB_GLOBAL)
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
int generic_copy_file_checks(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t *req_count, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121fd40)
Location: mm/filemap.c:3076
Inline: False
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
```
**Symbols:**

```
ffffffff8121fd40-ffffffff8121fe5e: generic_copy_file_checks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int generic_copy_file_checks(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t *req_count, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81212ef0)
Location: mm/filemap.c:3076
Inline: False
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
```
**Symbols:**

```
ffffffff81212ef0-ffffffff8121300e: generic_copy_file_checks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int generic_copy_file_checks(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t *req_count, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121dae0)
Location: mm/filemap.c:3076
Inline: False
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
```
**Symbols:**

```
ffffffff8121dae0-ffffffff8121dbfe: generic_copy_file_checks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int generic_copy_file_checks(struct file *file_in, loff_t pos_in, struct file *file_out, loff_t pos_out, size_t *req_count, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8122cb50)
Location: mm/filemap.c:3076
Inline: False
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
```
**Symbols:**

```
ffffffff8122cb50-ffffffff8122cc6e: generic_copy_file_checks (STB_GLOBAL)
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
