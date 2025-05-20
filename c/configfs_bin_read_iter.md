# Function: <code>configfs_bin_read_iter</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t configfs_bin_read_iter(struct kiocb *iocb, struct iov_iter *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/configfs/file.c (0)
Location: fs/configfs/file.c:106
Inline: False
```
**Symbols:**

```
ffffffff8143e040-ffffffff8143e260: configfs_bin_read_iter (STB_LOCAL)
ffffffff81cc870c-ffffffff81cc8751: configfs_bin_read_iter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t configfs_bin_read_iter(struct kiocb *iocb, struct iov_iter *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/configfs/file.c (0)
Location: fs/configfs/file.c:106
Inline: False
```
**Symbols:**

```
ffffffff814b97a0-ffffffff814b99d0: configfs_bin_read_iter (STB_LOCAL)
ffffffff81e7b44a-ffffffff81e7b489: configfs_bin_read_iter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
ssize_t configfs_bin_read_iter(struct kiocb *iocb, struct iov_iter *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/configfs/file.c (0)
Location: fs/configfs/file.c:106
Inline: False
```
**Symbols:**

```
ffffffff81550f50-ffffffff81551180: configfs_bin_read_iter (STB_LOCAL)
ffffffff8206bc74-ffffffff8206bcb3: configfs_bin_read_iter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
ssize_t configfs_bin_read_iter(struct kiocb *iocb, struct iov_iter *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/configfs/file.c (0)
Location: fs/configfs/file.c:106
Inline: False
```
**Symbols:**

```
ffffffff81588c30-ffffffff81588e63: configfs_bin_read_iter (STB_LOCAL)
ffffffff820ebb02-ffffffff820ebb41: configfs_bin_read_iter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
ssize_t configfs_bin_read_iter(struct kiocb *iocb, struct iov_iter *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/configfs/file.c (0)
Location: fs/configfs/file.c:106
Inline: False
```
**Symbols:**

```
ffffffff815c1800-ffffffff815c1a36: configfs_bin_read_iter (STB_LOCAL)
ffffffff821c8d66-ffffffff821c8da5: configfs_bin_read_iter.cold (STB_LOCAL)
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
