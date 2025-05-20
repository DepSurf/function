# Function: <code>seq_read_iter</code>

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
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
ssize_t seq_read_iter(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/seq_file.c (0)
Location: fs/seq_file.c:168
Inline: False
Direct callers:
  - fs/seq_file.c:seq_read
  - fs/kernfs/file.c:kernfs_fop_read_iter
```
**Symbols:**

```
ffffffff81bea7e7-ffffffff81bea810: seq_read_iter.cold (STB_LOCAL)
ffffffff8134da10-ffffffff8134df2b: seq_read_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
ssize_t seq_read_iter(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/seq_file.c (0)
Location: fs/seq_file.c:171
Inline: False
Direct callers:
  - fs/seq_file.c:seq_read
  - fs/kernfs/file.c:kernfs_fop_read_iter
```
**Symbols:**

```
ffffffff81bdc846-ffffffff81bdc86f: seq_read_iter.cold (STB_LOCAL)
ffffffff81354db0-ffffffff81355256: seq_read_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t seq_read_iter(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/seq_file.c (0)
Location: fs/seq_file.c:171
Inline: False
Direct callers:
  - fs/seq_file.c:seq_read
  - fs/kernfs/file.c:kernfs_fop_read_iter
```
**Symbols:**

```
ffffffff81cc4047-ffffffff81cc4070: seq_read_iter.cold (STB_LOCAL)
ffffffff813a31c0-ffffffff813a3666: seq_read_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t seq_read_iter(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/seq_file.c (0)
Location: fs/seq_file.c:171
Inline: False
Direct callers:
  - fs/seq_file.c:seq_read
  - fs/kernfs/file.c:kernfs_fop_read_iter
```
**Symbols:**

```
ffffffff81e7692c-ffffffff81e76955: seq_read_iter.cold (STB_LOCAL)
ffffffff81426f70-ffffffff814273ed: seq_read_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t seq_read_iter(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff814b3a30)
Location: fs/seq_file.c:171
Inline: False
Direct callers:
  - fs/seq_file.c:seq_read
  - fs/kernfs/file.c:kernfs_fop_read_iter
```
**Symbols:**

```
ffffffff814b3a30-ffffffff814b3ece: seq_read_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t seq_read_iter(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff814e8ab0)
Location: fs/seq_file.c:171
Inline: False
Direct callers:
  - fs/seq_file.c:seq_read
  - fs/kernfs/file.c:kernfs_fop_read_iter
```
**Symbols:**

```
ffffffff814e8ab0-ffffffff814e8f5a: seq_read_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t seq_read_iter(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8151c940)
Location: fs/seq_file.c:171
Inline: False
Direct callers:
  - fs/seq_file.c:seq_read
  - fs/kernfs/file.c:kernfs_fop_read_iter
```
**Symbols:**

```
ffffffff8151c940-ffffffff8151cdea: seq_read_iter (STB_GLOBAL)
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
