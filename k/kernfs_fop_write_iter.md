# Function: <code>kernfs_fop_write_iter</code>

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
ssize_t kernfs_fop_write_iter(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff813e2500)
Location: fs/kernfs/file.c:255
Inline: False
```
**Symbols:**

```
ffffffff813e2500-ffffffff813e26c2: kernfs_fop_write_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t kernfs_fop_write_iter(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff813e8d80)
Location: fs/kernfs/file.c:255
Inline: False
```
**Symbols:**

```
ffffffff813e8d80-ffffffff813e8f38: kernfs_fop_write_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t kernfs_fop_write_iter(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff8143aab0)
Location: fs/kernfs/file.c:255
Inline: False
```
**Symbols:**

```
ffffffff8143aab0-ffffffff8143ac68: kernfs_fop_write_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t kernfs_fop_write_iter(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff814b62b0)
Location: fs/kernfs/file.c:249
Inline: False
```
**Symbols:**

```
ffffffff814b62b0-ffffffff814b64aa: kernfs_fop_write_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t kernfs_fop_write_iter(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff8154d0c0)
Location: fs/kernfs/file.c:293
Inline: False
```
**Symbols:**

```
ffffffff8154d0c0-ffffffff8154d2c1: kernfs_fop_write_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t kernfs_fop_write_iter(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff81584ca0)
Location: fs/kernfs/file.c:293
Inline: False
```
**Symbols:**

```
ffffffff81584ca0-ffffffff81584e72: kernfs_fop_write_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t kernfs_fop_write_iter(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff815bd6f0)
Location: fs/kernfs/file.c:293
Inline: False
```
**Symbols:**

```
ffffffff815bd6f0-ffffffff815bd8c2: kernfs_fop_write_iter (STB_LOCAL)
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
