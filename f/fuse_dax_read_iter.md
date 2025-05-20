# Function: <code>fuse_dax_read_iter</code>

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
ssize_t fuse_dax_read_iter(struct kiocb *iocb, struct iov_iter *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff8149de10)
Location: fs/fuse/dax.c:701
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_read_iter
```
**Symbols:**

```
ffffffff8149de10-ffffffff8149de7d: fuse_dax_read_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t fuse_dax_read_iter(struct kiocb *iocb, struct iov_iter *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff814a3de0)
Location: fs/fuse/dax.c:701
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_read_iter
```
**Symbols:**

```
ffffffff814a3de0-ffffffff814a3e4d: fuse_dax_read_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t fuse_dax_read_iter(struct kiocb *iocb, struct iov_iter *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff814fbe60)
Location: fs/fuse/dax.c:700
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_read_iter
```
**Symbols:**

```
ffffffff814fbe60-ffffffff814fbecd: fuse_dax_read_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t fuse_dax_read_iter(struct kiocb *iocb, struct iov_iter *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff8158c3b0)
Location: fs/fuse/dax.c:700
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_read_iter
```
**Symbols:**

```
ffffffff8158c3b0-ffffffff8158c425: fuse_dax_read_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t fuse_dax_read_iter(struct kiocb *iocb, struct iov_iter *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff81632c10)
Location: fs/fuse/dax.c:700
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_read_iter
```
**Symbols:**

```
ffffffff81632c10-ffffffff81632c85: fuse_dax_read_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t fuse_dax_read_iter(struct kiocb *iocb, struct iov_iter *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff8166aec0)
Location: fs/fuse/dax.c:700
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_read_iter
```
**Symbols:**

```
ffffffff8166aec0-ffffffff8166af38: fuse_dax_read_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t fuse_dax_read_iter(struct kiocb *iocb, struct iov_iter *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff816a5200)
Location: fs/fuse/dax.c:700
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_file_read_iter
```
**Symbols:**

```
ffffffff816a5200-ffffffff816a5278: fuse_dax_read_iter (STB_GLOBAL)
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
