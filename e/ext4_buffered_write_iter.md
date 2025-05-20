# Function: <code>ext4_buffered_write_iter</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t ext4_buffered_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff813e9a00)
Location: fs/ext4/file.c:255
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
```
**Symbols:**

```
ffffffff813e9a00-ffffffff813e9b52: ext4_buffered_write_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t ext4_buffered_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff813fbb10)
Location: fs/ext4/file.c:254
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
```
**Symbols:**

```
ffffffff813fbb10-ffffffff813fbc7a: ext4_buffered_write_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t ext4_buffered_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff81401e00)
Location: fs/ext4/file.c:253
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
```
**Symbols:**

```
ffffffff81401e00-ffffffff81401f6a: ext4_buffered_write_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t ext4_buffered_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff81454570)
Location: fs/ext4/file.c:253
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
```
**Symbols:**

```
ffffffff81454570-ffffffff814546e4: ext4_buffered_write_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t ext4_buffered_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff814d1d00)
Location: fs/ext4/file.c:255
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
```
**Symbols:**

```
ffffffff814d1d00-ffffffff814d1e2e: ext4_buffered_write_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t ext4_buffered_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff8156a7c0)
Location: fs/ext4/file.c:270
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
```
**Symbols:**

```
ffffffff8156a7c0-ffffffff8156a91a: ext4_buffered_write_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t ext4_buffered_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff815a2770)
Location: fs/ext4/file.c:285
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
```
**Symbols:**

```
ffffffff815a2770-ffffffff815a2891: ext4_buffered_write_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t ext4_buffered_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff815db4a0)
Location: fs/ext4/file.c:285
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
```
**Symbols:**

```
ffffffff815db4a0-ffffffff815db5c1: ext4_buffered_write_iter (STB_LOCAL)
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
