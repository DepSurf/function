# Function: <code>ext4_direct_IO_write</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812cbafe)
Location: fs/ext4/inode.c:3359
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812e19fa)
Location: fs/ext4/inode.c:3492
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81305e68)
Location: fs/ext4/inode.c:3615
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8132a9be)
Location: fs/ext4/inode.c:3656
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81358c72)
Location: fs/ext4/inode.c:3661
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81370fa1)
Location: fs/ext4/inode.c:3694
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t ext4_direct_IO_write(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8139a390)
Location: fs/ext4/inode.c:3707
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_direct_IO
```
**Symbols:**

```
ffffffff8139a390-ffffffff8139a7c9: ext4_direct_IO_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t ext4_direct_IO_write(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813b2e50)
Location: fs/ext4/inode.c:3676
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_direct_IO
```
**Symbols:**

```
ffffffff813b2e50-ffffffff813b3289: ext4_direct_IO_write (STB_LOCAL)
```
</details>
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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
ssize_t ext4_direct_IO_write(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffff800010487670)
Location: fs/ext4/inode.c:3676
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_direct_IO
```
**Symbols:**

```
ffff800010487670-ffff800010487ad8: ext4_direct_IO_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t ext4_direct_IO_write(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0649798)
Location: fs/ext4/inode.c:3676
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_direct_IO
```
**Symbols:**

```
c0649798-c0649c88: ext4_direct_IO_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t ext4_direct_IO_write(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0000000005adb20)
Location: fs/ext4/inode.c:3676
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_direct_IO
```
**Symbols:**

```
c0000000005adb20-c0000000005ae118: ext4_direct_IO_write (STB_LOCAL)
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
In fs/ext4/inode.c (ffffffe00030f5e8)
Location: fs/ext4/inode.c:3676
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
ssize_t ext4_direct_IO_write(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813ab430)
Location: fs/ext4/inode.c:3676
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_direct_IO
```
**Symbols:**

```
ffffffff813ab430-ffffffff813ab869: ext4_direct_IO_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t ext4_direct_IO_write(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8139bec0)
Location: fs/ext4/inode.c:3676
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_direct_IO
```
**Symbols:**

```
ffffffff8139bec0-ffffffff8139c2f9: ext4_direct_IO_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t ext4_direct_IO_write(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a8c90)
Location: fs/ext4/inode.c:3676
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_direct_IO
```
**Symbols:**

```
ffffffff813a8c90-ffffffff813a90c9: ext4_direct_IO_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t ext4_direct_IO_write(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813bd540)
Location: fs/ext4/inode.c:3676
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_direct_IO
```
**Symbols:**

```
ffffffff813bd540-ffffffff813bd979: ext4_direct_IO_write (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
