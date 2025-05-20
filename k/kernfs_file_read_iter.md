# Function: <code>kernfs_file_read_iter</code>

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
ssize_t kernfs_file_read_iter(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff813e1e20)
Location: fs/kernfs/file.c:184
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_fop_read_iter
```
**Symbols:**

```
ffffffff813e1e20-ffffffff813e1fad: kernfs_file_read_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t kernfs_file_read_iter(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff813e8a50)
Location: fs/kernfs/file.c:184
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_fop_read_iter
```
**Symbols:**

```
ffffffff813e8a50-ffffffff813e8bd4: kernfs_file_read_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t kernfs_file_read_iter(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff8143a780)
Location: fs/kernfs/file.c:184
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_fop_read_iter
```
**Symbols:**

```
ffffffff8143a780-ffffffff8143a904: kernfs_file_read_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t kernfs_file_read_iter(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff814b5970)
Location: fs/kernfs/file.c:178
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_fop_read_iter
```
**Symbols:**

```
ffffffff814b5970-ffffffff814b5af0: kernfs_file_read_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t kernfs_file_read_iter(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff8154cad0)
Location: fs/kernfs/file.c:221
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_fop_read_iter
```
**Symbols:**

```
ffffffff8154cad0-ffffffff8154cc51: kernfs_file_read_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t kernfs_file_read_iter(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff815847a0)
Location: fs/kernfs/file.c:221
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_fop_read_iter
```
**Symbols:**

```
ffffffff815847a0-ffffffff81584921: kernfs_file_read_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t kernfs_file_read_iter(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff815bd130)
Location: fs/kernfs/file.c:221
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_fop_read_iter
```
**Symbols:**

```
ffffffff815bd130-ffffffff815bd2b1: kernfs_file_read_iter (STB_LOCAL)
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
