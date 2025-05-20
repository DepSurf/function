# Function: <code>proc_reg_read_iter</code>

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
ssize_t proc_reg_read_iter(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/inode.c (ffffffff813cb2e0)
Location: fs/proc/inode.c:300
Inline: False
```
**Symbols:**

```
ffffffff813cb2e0-ffffffff813cb35e: proc_reg_read_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t proc_reg_read_iter(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/inode.c (ffffffff813d2180)
Location: fs/proc/inode.c:290
Inline: False
```
**Symbols:**

```
ffffffff813d2180-ffffffff813d21fe: proc_reg_read_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t proc_reg_read_iter(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/inode.c (ffffffff814236b0)
Location: fs/proc/inode.c:290
Inline: False
```
**Symbols:**

```
ffffffff814236b0-ffffffff8142372e: proc_reg_read_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t proc_reg_read_iter(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/inode.c (ffffffff8149c330)
Location: fs/proc/inode.c:290
Inline: False
```
**Symbols:**

```
ffffffff8149c330-ffffffff8149c3b8: proc_reg_read_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t proc_reg_read_iter(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/inode.c (ffffffff81530c80)
Location: fs/proc/inode.c:295
Inline: False
```
**Symbols:**

```
ffffffff81530c80-ffffffff81530d08: proc_reg_read_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t proc_reg_read_iter(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/inode.c (ffffffff81568e00)
Location: fs/proc/inode.c:295
Inline: False
```
**Symbols:**

```
ffffffff81568e00-ffffffff81568e8b: proc_reg_read_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t proc_reg_read_iter(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/inode.c (ffffffff815a1420)
Location: fs/proc/inode.c:289
Inline: False
```
**Symbols:**

```
ffffffff815a1420-ffffffff815a14ab: proc_reg_read_iter (STB_LOCAL)
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
