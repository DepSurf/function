# Function: <code>fuse_send_write_pages</code>

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
In fs/fuse/file.c (ffffffff813193db)
Location: fs/fuse/file.c:987
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
In fs/fuse/file.c (ffffffff8134dece)
Location: fs/fuse/file.c:1000
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
In fs/fuse/file.c (ffffffff813637ce)
Location: fs/fuse/file.c:1001
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
In fs/fuse/file.c (ffffffff8137807a)
Location: fs/fuse/file.c:996
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
In fs/fuse/file.c (ffffffff8139ce49)
Location: fs/fuse/file.c:1004
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
In fs/fuse/file.c (ffffffff813cc278)
Location: fs/fuse/file.c:1005
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
In fs/fuse/file.c (ffffffff813e55a5)
Location: fs/fuse/file.c:1010
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
In fs/fuse/file.c (ffffffff81411446)
Location: fs/fuse/file.c:1022
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
In fs/fuse/file.c (ffffffff8142b067)
Location: fs/fuse/file.c:1097
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
ssize_t fuse_send_write_pages(struct fuse_io_args *ia, struct kiocb *iocb, struct inode *inode, loff_t pos, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81476ec0)
Location: fs/fuse/file.c:1070
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff81476ec0-ffffffff81477127: fuse_send_write_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t fuse_send_write_pages(struct fuse_io_args *ia, struct kiocb *iocb, struct inode *inode, loff_t pos, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81491cd0)
Location: fs/fuse/file.c:1093
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff81491cd0-ffffffff81491f63: fuse_send_write_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t fuse_send_write_pages(struct fuse_io_args *ia, struct kiocb *iocb, struct inode *inode, loff_t pos, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81496e20)
Location: fs/fuse/file.c:1088
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff81496e20-ffffffff81497121: fuse_send_write_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t fuse_send_write_pages(struct fuse_io_args *ia, struct kiocb *iocb, struct inode *inode, loff_t pos, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (0)
Location: fs/fuse/file.c:1092
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff814ee700-ffffffff814eea17: fuse_send_write_pages (STB_LOCAL)
ffffffff81cd20a7-ffffffff81cd20ca: fuse_send_write_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t fuse_send_write_pages(struct fuse_io_args *ia, struct kiocb *iocb, struct inode *inode, loff_t pos, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (0)
Location: fs/fuse/file.c:1112
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff8157f420-ffffffff8157f804: fuse_send_write_pages (STB_LOCAL)
ffffffff81e8525d-ffffffff81e8528e: fuse_send_write_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
ssize_t fuse_send_write_pages(struct fuse_io_args *ia, struct kiocb *iocb, struct inode *inode, loff_t pos, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (0)
Location: fs/fuse/file.c:1112
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff81625110-ffffffff816254dd: fuse_send_write_pages (STB_LOCAL)
ffffffff8207276b-ffffffff8207279c: fuse_send_write_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
ssize_t fuse_send_write_pages(struct fuse_io_args *ia, struct kiocb *iocb, struct inode *inode, loff_t pos, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (0)
Location: fs/fuse/file.c:1113
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff8165d4a0-ffffffff8165d842: fuse_send_write_pages (STB_LOCAL)
ffffffff820f23e4-ffffffff820f2407: fuse_send_write_pages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
ssize_t fuse_send_write_pages(struct fuse_io_args *ia, struct kiocb *iocb, struct inode *inode, loff_t pos, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/file.c (0)
Location: fs/fuse/file.c:1114
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_perform_write
```
**Symbols:**

```
ffffffff816971f0-ffffffff81697586: fuse_send_write_pages (STB_LOCAL)
ffffffff821cf694-ffffffff821cf6b7: fuse_send_write_pages.cold (STB_LOCAL)
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
In fs/fuse/file.c (ffff80001050ef10)
Location: fs/fuse/file.c:1097
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
In fs/fuse/file.c (c06ca798)
Location: fs/fuse/file.c:1097
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
In fs/fuse/file.c (c0000000006562cc)
Location: fs/fuse/file.c:1097
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
In fs/fuse/file.c (ffffffe0003799b2)
Location: fs/fuse/file.c:1097
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
In fs/fuse/file.c (ffffffff81423647)
Location: fs/fuse/file.c:1097
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
In fs/fuse/file.c (ffffffff814140c7)
Location: fs/fuse/file.c:1097
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
In fs/fuse/file.c (ffffffff8141f7e7)
Location: fs/fuse/file.c:1097
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
In fs/fuse/file.c (ffffffff81436567)
Location: fs/fuse/file.c:1097
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
