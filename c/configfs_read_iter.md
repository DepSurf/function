# Function: <code>configfs_read_iter</code>

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
ssize_t configfs_read_iter(struct kiocb *iocb, struct iov_iter *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/configfs/file.c (0)
Location: fs/configfs/file.c:80
Inline: False
```
**Symbols:**

```
ffffffff8143e5c0-ffffffff8143e79a: configfs_read_iter (STB_LOCAL)
ffffffff81cc8781-ffffffff81cc879e: configfs_read_iter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t configfs_read_iter(struct kiocb *iocb, struct iov_iter *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/configfs/file.c (0)
Location: fs/configfs/file.c:80
Inline: False
```
**Symbols:**

```
ffffffff814b9ef0-ffffffff814ba0c9: configfs_read_iter (STB_LOCAL)
ffffffff81e7b4ce-ffffffff81e7b4e9: configfs_read_iter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
ssize_t configfs_read_iter(struct kiocb *iocb, struct iov_iter *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/configfs/file.c (0)
Location: fs/configfs/file.c:80
Inline: False
```
**Symbols:**

```
ffffffff81551700-ffffffff815518d9: configfs_read_iter (STB_LOCAL)
ffffffff8206bcf8-ffffffff8206bd13: configfs_read_iter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
ssize_t configfs_read_iter(struct kiocb *iocb, struct iov_iter *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/configfs/file.c (0)
Location: fs/configfs/file.c:80
Inline: False
```
**Symbols:**

```
ffffffff81589420-ffffffff815895fc: configfs_read_iter (STB_LOCAL)
ffffffff820ebb86-ffffffff820ebba1: configfs_read_iter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
ssize_t configfs_read_iter(struct kiocb *iocb, struct iov_iter *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/configfs/file.c (0)
Location: fs/configfs/file.c:80
Inline: False
```
**Symbols:**

```
ffffffff815c2030-ffffffff815c220f: configfs_read_iter (STB_LOCAL)
ffffffff821c8dea-ffffffff821c8e05: configfs_read_iter.cold (STB_LOCAL)
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
