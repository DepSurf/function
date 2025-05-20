# Function: <code>generic_write_check_limits</code>

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
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int generic_write_check_limits(struct file *file, loff_t pos, loff_t *count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811fc580)
Location: mm/filemap.c:2915
Inline: True
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - mm/filemap.c:generic_remap_checks
```
**Symbols:**

```
ffffffff811fc580-ffffffff811fc605: generic_write_check_limits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/filemap.c (ffffffff81213cd0)
Location: mm/filemap.c:2951
Inline: True
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - mm/filemap.c:generic_copy_file_checks
  - mm/filemap.c:generic_remap_checks
```
**Symbols:**

```
ffffffff81213cd0-ffffffff81213d55: generic_write_check_limits.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/filemap.c (ffffffff812214d0)
Location: mm/filemap.c:2905
Inline: True
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - mm/filemap.c:generic_copy_file_checks
  - mm/filemap.c:generic_remap_checks
```
**Symbols:**

```
ffffffff812214d0-ffffffff81221555: generic_write_check_limits.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int generic_write_check_limits(struct file *file, loff_t pos, loff_t *count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8124e160)
Location: mm/filemap.c:2914
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - mm/filemap.c:generic_copy_file_checks
  - mm/filemap.c:generic_remap_checks
```
**Symbols:**

```
ffffffff8124e160-ffffffff8124e1e8: generic_write_check_limits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int generic_write_check_limits(struct file *file, loff_t pos, loff_t *count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81320580)
Location: fs/read_write.c:1605
Inline: False
Direct callers:
  - fs/read_write.c:generic_write_checks
```
**Symbols:**

```
ffffffff81320580-ffffffff81320608: generic_write_check_limits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int generic_write_check_limits(struct file *file, loff_t pos, loff_t *count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff813266b0)
Location: fs/read_write.c:1610
Inline: False
Direct callers:
  - fs/read_write.c:generic_write_checks
  - fs/read_write.c:vfs_copy_file_range
  - fs/remap_range.c:generic_remap_file_range_prep
```
**Symbols:**

```
ffffffff813266b0-ffffffff81326744: generic_write_check_limits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int generic_write_check_limits(struct file *file, loff_t pos, loff_t *count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81373c50)
Location: fs/read_write.c:1601
Inline: False
Direct callers:
  - fs/read_write.c:generic_write_checks
  - fs/read_write.c:vfs_copy_file_range
  - fs/remap_range.c:generic_remap_file_range_prep
```
**Symbols:**

```
ffffffff81373c50-ffffffff81373ce4: generic_write_check_limits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int generic_write_check_limits(struct file *file, loff_t pos, loff_t *count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff813f2a40)
Location: fs/read_write.c:1626
Inline: False
Direct callers:
  - fs/read_write.c:generic_write_checks
  - fs/read_write.c:vfs_copy_file_range
```
**Symbols:**

```
ffffffff813f2a40-ffffffff813f2b01: generic_write_check_limits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int generic_write_check_limits(struct file *file, loff_t pos, loff_t *count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8147b690)
Location: fs/read_write.c:1630
Inline: False
Direct callers:
  - fs/read_write.c:generic_write_checks
  - fs/read_write.c:vfs_copy_file_range
```
**Symbols:**

```
ffffffff8147b690-ffffffff8147b751: generic_write_check_limits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int generic_write_check_limits(struct file *file, loff_t pos, loff_t *count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814b0220)
Location: fs/read_write.c:1629
Inline: False
Direct callers:
  - fs/read_write.c:generic_write_checks
  - fs/read_write.c:vfs_copy_file_range
```
**Symbols:**

```
ffffffff814b0220-ffffffff814b02e1: generic_write_check_limits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int generic_write_check_limits(struct file *file, loff_t pos, loff_t *count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814e19e0)
Location: fs/read_write.c:1646
Inline: False
Direct callers:
  - fs/read_write.c:generic_write_checks
  - fs/read_write.c:vfs_copy_file_range
```
**Symbols:**

```
ffffffff814e19e0-ffffffff814e1aa1: generic_write_check_limits (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/filemap.c (ffff8000102ae038)
Location: mm/filemap.c:2905
Inline: True
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - mm/filemap.c:generic_copy_file_checks
  - mm/filemap.c:generic_copy_file_checks
  - mm/filemap.c:generic_remap_checks
```
**Symbols:**

```
ffff8000102ae038-ffff8000102ae0f8: generic_write_check_limits.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int generic_write_check_limits(struct file *file, loff_t pos, loff_t *count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c04db470)
Location: mm/filemap.c:2905
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - mm/filemap.c:generic_copy_file_checks
  - mm/filemap.c:generic_remap_checks
```
**Symbols:**

```
c04db470-c04db56c: generic_write_check_limits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int generic_write_check_limits(struct file *file, loff_t pos, loff_t *count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c000000000363490)
Location: mm/filemap.c:2905
Inline: True
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - mm/filemap.c:generic_copy_file_checks
  - mm/filemap.c:generic_copy_file_checks
  - mm/filemap.c:generic_remap_checks
```
**Symbols:**

```
c000000000363490-c00000000036357c: generic_write_check_limits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int generic_write_check_limits(struct file *file, loff_t pos, loff_t *count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffe0001d4cf8)
Location: mm/filemap.c:2905
Inline: True
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - mm/filemap.c:generic_copy_file_checks
  - mm/filemap.c:generic_remap_checks
```
**Symbols:**

```
ffffffe0001d4cf8-ffffffe0001d4d96: generic_write_check_limits (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/filemap.c (ffffffff81219b20)
Location: mm/filemap.c:2905
Inline: True
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - mm/filemap.c:generic_copy_file_checks
  - mm/filemap.c:generic_remap_checks
```
**Symbols:**

```
ffffffff81219b20-ffffffff81219ba5: generic_write_check_limits.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/filemap.c (ffffffff8120cd30)
Location: mm/filemap.c:2905
Inline: True
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - mm/filemap.c:generic_copy_file_checks
  - mm/filemap.c:generic_remap_checks
```
**Symbols:**

```
ffffffff8120cd30-ffffffff8120cdb5: generic_write_check_limits.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/filemap.c (ffffffff812178c0)
Location: mm/filemap.c:2905
Inline: True
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - mm/filemap.c:generic_copy_file_checks
  - mm/filemap.c:generic_remap_checks
```
**Symbols:**

```
ffffffff812178c0-ffffffff81217945: generic_write_check_limits.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/filemap.c (ffffffff81226980)
Location: mm/filemap.c:2905
Inline: True
Direct callers:
  - mm/filemap.c:generic_file_write_iter
  - mm/filemap.c:generic_copy_file_checks
  - mm/filemap.c:generic_remap_checks
```
**Symbols:**

```
ffffffff81226980-ffffffff81226a05: generic_write_check_limits.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
