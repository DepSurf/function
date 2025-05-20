# Function: <code>fuse_cache_write_iter</code>

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
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81411881)
Location: fs/fuse/file.c:1185
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_write_iter
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
In fs/fuse/file.c (ffffffff8142b571)
Location: fs/fuse/file.c:1268
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_write_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t fuse_cache_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8147b1e0)
Location: fs/fuse/file.c:1241
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff8147b1e0-ffffffff8147b487: fuse_cache_write_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t fuse_cache_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81495f10)
Location: fs/fuse/file.c:1266
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff81495f10-ffffffff8149621a: fuse_cache_write_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t fuse_cache_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8149afa0)
Location: fs/fuse/file.c:1278
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff8149afa0-ffffffff8149b2aa: fuse_cache_write_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t fuse_cache_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814f29e0)
Location: fs/fuse/file.c:1280
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff814f29e0-ffffffff814f2cf1: fuse_cache_write_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t fuse_cache_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff815823d0)
Location: fs/fuse/file.c:1297
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff815823d0-ffffffff81582756: fuse_cache_write_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t fuse_cache_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81628230)
Location: fs/fuse/file.c:1297
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff81628230-ffffffff816285b2: fuse_cache_write_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t fuse_cache_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81660630)
Location: fs/fuse/file.c:1301
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff81660630-ffffffff816607e7: fuse_cache_write_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t fuse_cache_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8169a490)
Location: fs/fuse/file.c:1302
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_write_iter
```
**Symbols:**

```
ffffffff8169a490-ffffffff8169a647: fuse_cache_write_iter (STB_LOCAL)
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
In fs/fuse/file.c (ffff80001050f420)
Location: fs/fuse/file.c:1268
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_write_iter
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
In fs/fuse/file.c (c06cac60)
Location: fs/fuse/file.c:1268
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_write_iter
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
In fs/fuse/file.c (c000000000656960)
Location: fs/fuse/file.c:1268
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_write_iter
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
In fs/fuse/file.c (ffffffe000379dd8)
Location: fs/fuse/file.c:1268
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_write_iter
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
In fs/fuse/file.c (ffffffff81423b51)
Location: fs/fuse/file.c:1268
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_write_iter
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
In fs/fuse/file.c (ffffffff814145d1)
Location: fs/fuse/file.c:1268
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_write_iter
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
In fs/fuse/file.c (ffffffff8141fcf1)
Location: fs/fuse/file.c:1268
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_write_iter
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
In fs/fuse/file.c (ffffffff81436a71)
Location: fs/fuse/file.c:1268
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_file_write_iter
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
