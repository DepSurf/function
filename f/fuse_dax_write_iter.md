# Function: <code>fuse_dax_write_iter</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t fuse_dax_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff8149de80)
Location: fs/fuse/dax.c:744
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff8149de80-ffffffff8149e011: fuse_dax_write_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t fuse_dax_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff814a3e50)
Location: fs/fuse/dax.c:744
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff814a3e50-ffffffff814a3fe1: fuse_dax_write_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t fuse_dax_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/dax.c (0)
Location: fs/fuse/dax.c:743
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff81cd2407-ffffffff81cd241c: fuse_dax_write_iter.cold (STB_LOCAL)
ffffffff814fbed0-ffffffff814fc083: fuse_dax_write_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t fuse_dax_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/dax.c (0)
Location: fs/fuse/dax.c:740
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff81e8553a-ffffffff81e8554e: fuse_dax_write_iter.cold (STB_LOCAL)
ffffffff8158c430-ffffffff8158c60b: fuse_dax_write_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
ssize_t fuse_dax_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/dax.c (0)
Location: fs/fuse/dax.c:740
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff820729b2-ffffffff820729c6: fuse_dax_write_iter.cold (STB_LOCAL)
ffffffff81632ca0-ffffffff81632ea5: fuse_dax_write_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
ssize_t fuse_dax_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/dax.c (0)
Location: fs/fuse/dax.c:740
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff820f2616-ffffffff820f262a: fuse_dax_write_iter.cold (STB_LOCAL)
ffffffff8166af50-ffffffff8166b161: fuse_dax_write_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
ssize_t fuse_dax_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/dax.c (0)
Location: fs/fuse/dax.c:740
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff821cf8b1-ffffffff821cf8c5: fuse_dax_write_iter.cold (STB_LOCAL)
ffffffff816a5290-ffffffff816a54a1: fuse_dax_write_iter (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
