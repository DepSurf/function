# Function: <code>ext4_dio_write_iter</code>

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
ssize_t ext4_dio_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff813e9b60)
Location: fs/ext4/file.c:454
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_write_iter
```
**Symbols:**

```
ffffffff813e9b60-ffffffff813e9edf: ext4_dio_write_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t ext4_dio_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff813fbc80)
Location: fs/ext4/file.c:455
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_write_iter
```
**Symbols:**

```
ffffffff813fbc80-ffffffff813fc02a: ext4_dio_write_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t ext4_dio_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff81401f70)
Location: fs/ext4/file.c:471
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_write_iter
```
**Symbols:**

```
ffffffff81401f70-ffffffff8140246f: ext4_dio_write_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t ext4_dio_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/file.c (0)
Location: fs/ext4/file.c:471
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_write_iter
```
**Symbols:**

```
ffffffff814546f0-ffffffff81454b2f: ext4_dio_write_iter (STB_LOCAL)
ffffffff81cc9e46-ffffffff81cc9f56: ext4_dio_write_iter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t ext4_dio_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/file.c (0)
Location: fs/ext4/file.c:471
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_write_iter
```
**Symbols:**

```
ffffffff814d1e30-ffffffff814d22ab: ext4_dio_write_iter (STB_LOCAL)
ffffffff81e7cb3d-ffffffff81e7cc50: ext4_dio_write_iter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
ssize_t ext4_dio_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/file.c (0)
Location: fs/ext4/file.c:486
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_write_iter
```
**Symbols:**

```
ffffffff8156a930-ffffffff8156adde: ext4_dio_write_iter (STB_LOCAL)
ffffffff8206d169-ffffffff8206d246: ext4_dio_write_iter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
ssize_t ext4_dio_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/file.c (0)
Location: fs/ext4/file.c:532
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_write_iter
```
**Symbols:**

```
ffffffff815a28b0-ffffffff815a2c8e: ext4_dio_write_iter (STB_LOCAL)
ffffffff820ecf93-ffffffff820ed017: ext4_dio_write_iter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
ssize_t ext4_dio_write_iter(struct kiocb *iocb, struct iov_iter *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/file.c (0)
Location: fs/ext4/file.c:498
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_file_write_iter
```
**Symbols:**

```
ffffffff815db5e0-ffffffff815db9a7: ext4_dio_write_iter (STB_LOCAL)
ffffffff821ca0ee-ffffffff821ca15d: ext4_dio_write_iter.cold (STB_LOCAL)
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
