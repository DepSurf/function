# Function: <code>fuse_fill_write_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81319289)
Location: fs/fuse/file.c:1022
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_perform_write
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8134dd01)
Location: fs/fuse/file.c:1035
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_perform_write
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81363601)
Location: fs/fuse/file.c:1036
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_perform_write
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81377f09)
Location: fs/fuse/file.c:1031
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_perform_write
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8139ccd2)
Location: fs/fuse/file.c:1039
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_perform_write
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813cc0d6)
Location: fs/fuse/file.c:1040
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_perform_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff813e5403)
Location: fs/fuse/file.c:1045
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_perform_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814112b4)
Location: fs/fuse/file.c:1057
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_perform_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8142aee8)
Location: fs/fuse/file.c:1139
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_perform_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t fuse_fill_write_pages(struct fuse_args_pages *ap, struct address_space *mapping, struct iov_iter *ii, loff_t pos, unsigned int max_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81476b00)
Location: fs/fuse/file.c:1112
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff81476b00-ffffffff81476d1e: fuse_fill_write_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t fuse_fill_write_pages(struct fuse_args_pages *ap, struct address_space *mapping, struct iov_iter *ii, loff_t pos, unsigned int max_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81491910)
Location: fs/fuse/file.c:1137
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff81491910-ffffffff81491b2e: fuse_fill_write_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t fuse_fill_write_pages(struct fuse_io_args *ia, struct address_space *mapping, struct iov_iter *ii, loff_t pos, unsigned int max_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81496a90)
Location: fs/fuse/file.c:1138
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff81496a90-ffffffff81496cf2: fuse_fill_write_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t fuse_fill_write_pages(struct fuse_io_args *ia, struct address_space *mapping, struct iov_iter *ii, loff_t pos, unsigned int max_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814ee3b0)
Location: fs/fuse/file.c:1142
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff814ee3b0-ffffffff814ee5db: fuse_fill_write_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t fuse_fill_write_pages(struct fuse_io_args *ia, struct address_space *mapping, struct iov_iter *ii, loff_t pos, unsigned int max_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8157e0f0)
Location: fs/fuse/file.c:1162
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff8157e0f0-ffffffff8157e39f: fuse_fill_write_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t fuse_fill_write_pages(struct fuse_io_args *ia, struct address_space *mapping, struct iov_iter *ii, loff_t pos, unsigned int max_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81623e60)
Location: fs/fuse/file.c:1162
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff81623e60-ffffffff8162410f: fuse_fill_write_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t fuse_fill_write_pages(struct fuse_io_args *ia, struct address_space *mapping, struct iov_iter *ii, loff_t pos, unsigned int max_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8165c240)
Location: fs/fuse/file.c:1163
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff8165c240-ffffffff8165c4ef: fuse_fill_write_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t fuse_fill_write_pages(struct fuse_io_args *ia, struct address_space *mapping, struct iov_iter *ii, loff_t pos, unsigned int max_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81695fa0)
Location: fs/fuse/file.c:1164
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff81695fa0-ffffffff8169624d: fuse_fill_write_pages (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffff80001050eddc)
Location: fs/fuse/file.c:1139
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_perform_write
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (c06ca63c)
Location: fs/fuse/file.c:1139
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_perform_write
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (c000000000656168)
Location: fs/fuse/file.c:1139
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_perform_write
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffe00037981c)
Location: fs/fuse/file.c:1139
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_perform_write
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814234c8)
Location: fs/fuse/file.c:1139
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_perform_write
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81413f48)
Location: fs/fuse/file.c:1139
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_perform_write
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8141f668)
Location: fs/fuse/file.c:1139
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_perform_write
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814363e8)
Location: fs/fuse/file.c:1139
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_perform_write
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fuse_io_args *ia</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fuse_args_pages *ap</code>
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
