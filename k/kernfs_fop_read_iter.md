# Function: <code>kernfs_fop_read_iter</code>

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
ssize_t kernfs_fop_read_iter(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff813e1fb0)
Location: fs/kernfs/file.c:238
Inline: False
```
**Symbols:**

```
ffffffff813e1fb0-ffffffff813e1fde: kernfs_fop_read_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t kernfs_fop_read_iter(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff813e8be0)
Location: fs/kernfs/file.c:238
Inline: False
```
**Symbols:**

```
ffffffff813e8be0-ffffffff813e8c0e: kernfs_fop_read_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t kernfs_fop_read_iter(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff8143a910)
Location: fs/kernfs/file.c:238
Inline: False
```
**Symbols:**

```
ffffffff8143a910-ffffffff8143a93e: kernfs_fop_read_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t kernfs_fop_read_iter(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff814b5af0)
Location: fs/kernfs/file.c:232
Inline: False
```
**Symbols:**

```
ffffffff814b5af0-ffffffff814b5b2e: kernfs_fop_read_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t kernfs_fop_read_iter(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff8154cc70)
Location: fs/kernfs/file.c:276
Inline: False
```
**Symbols:**

```
ffffffff8154cc70-ffffffff8154ccae: kernfs_fop_read_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t kernfs_fop_read_iter(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff81584940)
Location: fs/kernfs/file.c:276
Inline: False
```
**Symbols:**

```
ffffffff81584940-ffffffff8158497e: kernfs_fop_read_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t kernfs_fop_read_iter(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff815bd2d0)
Location: fs/kernfs/file.c:276
Inline: False
```
**Symbols:**

```
ffffffff815bd2d0-ffffffff815bd30e: kernfs_fop_read_iter (STB_LOCAL)
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
