# Function: <code>generic_file_rw_checks</code>

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
int generic_file_rw_checks(struct file *file_in, struct file *file_out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81219d00)
Location: mm/filemap.c:3093
Inline: False
Direct callers:
  - mm/filemap.c:generic_copy_file_checks
  - fs/read_write.c:do_clone_file_range
```
**Symbols:**

```
ffffffff81219d00-ffffffff81219d7c: generic_file_rw_checks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int generic_file_rw_checks(struct file *file_in, struct file *file_out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81227670)
Location: mm/filemap.c:3050
Inline: False
Direct callers:
  - mm/filemap.c:generic_copy_file_checks
```
**Symbols:**

```
ffffffff81227670-ffffffff812276ec: generic_file_rw_checks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int generic_file_rw_checks(struct file *file_in, struct file *file_out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81253f10)
Location: mm/filemap.c:3059
Inline: False
Direct callers:
  - mm/filemap.c:generic_copy_file_checks
  - fs/read_write.c:do_clone_file_range
```
**Symbols:**

```
ffffffff81253f10-ffffffff81253f8c: generic_file_rw_checks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int generic_file_rw_checks(struct file *file_in, struct file *file_out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff813206d0)
Location: fs/read_write.c:1671
Inline: False
Direct callers:
  - fs/remap_range.c:do_clone_file_range
```
**Symbols:**

```
ffffffff813206d0-ffffffff8132074c: generic_file_rw_checks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int generic_file_rw_checks(struct file *file_in, struct file *file_out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81326810)
Location: fs/read_write.c:1676
Inline: False
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/remap_range.c:do_clone_file_range
```
**Symbols:**

```
ffffffff81326810-ffffffff8132688c: generic_file_rw_checks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int generic_file_rw_checks(struct file *file_in, struct file *file_out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81373db0)
Location: fs/read_write.c:1667
Inline: False
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/remap_range.c:do_clone_file_range
```
**Symbols:**

```
ffffffff81373db0-ffffffff81373e2c: generic_file_rw_checks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int generic_file_rw_checks(struct file *file_in, struct file *file_out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff813f2c60)
Location: fs/read_write.c:1698
Inline: False
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/remap_range.c:do_clone_file_range
```
**Symbols:**

```
ffffffff813f2c60-ffffffff813f2d04: generic_file_rw_checks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int generic_file_rw_checks(struct file *file_in, struct file *file_out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8147b900)
Location: fs/read_write.c:1704
Inline: False
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/remap_range.c:do_clone_file_range
```
**Symbols:**

```
ffffffff8147b900-ffffffff8147b9a4: generic_file_rw_checks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int generic_file_rw_checks(struct file *file_in, struct file *file_out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814b0490)
Location: fs/read_write.c:1703
Inline: False
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/remap_range.c:do_clone_file_range
```
**Symbols:**

```
ffffffff814b0490-ffffffff814b052a: generic_file_rw_checks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int generic_file_rw_checks(struct file *file_in, struct file *file_out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff814e1c50)
Location: fs/read_write.c:1720
Inline: False
Direct callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/remap_range.c:vfs_clone_file_range
```
**Symbols:**

```
ffffffff814e1c50-ffffffff814e1cea: generic_file_rw_checks (STB_GLOBAL)
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
int generic_file_rw_checks(struct file *file_in, struct file *file_out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffff8000102b4498)
Location: mm/filemap.c:3050
Inline: False
Direct callers:
  - mm/filemap.c:generic_copy_file_checks
```
**Symbols:**

```
ffff8000102b4498-ffff8000102b4534: generic_file_rw_checks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int generic_file_rw_checks(struct file *file_in, struct file *file_out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c04e1eb4)
Location: mm/filemap.c:3050
Inline: False
Direct callers:
  - mm/filemap.c:generic_copy_file_checks
  - fs/read_write.c:do_clone_file_range
```
**Symbols:**

```
c04e1eb4-c04e1f48: generic_file_rw_checks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int generic_file_rw_checks(struct file *file_in, struct file *file_out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c00000000036be80)
Location: mm/filemap.c:3050
Inline: False
Direct callers:
  - mm/filemap.c:generic_copy_file_checks
```
**Symbols:**

```
c00000000036be80-c00000000036bf28: generic_file_rw_checks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int generic_file_rw_checks(struct file *file_in, struct file *file_out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffe0001d9cc2)
Location: mm/filemap.c:3050
Inline: False
Direct callers:
  - mm/filemap.c:generic_copy_file_checks
```
**Symbols:**

```
ffffffe0001d9cc2-ffffffe0001d9d36: generic_file_rw_checks (STB_GLOBAL)
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
int generic_file_rw_checks(struct file *file_in, struct file *file_out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121fcc0)
Location: mm/filemap.c:3050
Inline: False
Direct callers:
  - mm/filemap.c:generic_copy_file_checks
```
**Symbols:**

```
ffffffff8121fcc0-ffffffff8121fd3c: generic_file_rw_checks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int generic_file_rw_checks(struct file *file_in, struct file *file_out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81212e70)
Location: mm/filemap.c:3050
Inline: False
Direct callers:
  - mm/filemap.c:generic_copy_file_checks
```
**Symbols:**

```
ffffffff81212e70-ffffffff81212eec: generic_file_rw_checks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int generic_file_rw_checks(struct file *file_in, struct file *file_out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121da60)
Location: mm/filemap.c:3050
Inline: False
Direct callers:
  - mm/filemap.c:generic_copy_file_checks
```
**Symbols:**

```
ffffffff8121da60-ffffffff8121dadc: generic_file_rw_checks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int generic_file_rw_checks(struct file *file_in, struct file *file_out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8122cad0)
Location: mm/filemap.c:3050
Inline: False
Direct callers:
  - mm/filemap.c:generic_copy_file_checks
```
**Symbols:**

```
ffffffff8122cad0-ffffffff8122cb4c: generic_file_rw_checks (STB_GLOBAL)
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
