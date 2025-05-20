# Function: <code>ext4_dio_supported</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool ext4_dio_supported(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff813e96b0)
Location: fs/ext4/file.c:39
Inline: True
Direct callers:
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
**Symbols:**

```
ffffffff813e96b0-ffffffff813e9704: ext4_dio_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool ext4_dio_supported(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff813fb360)
Location: fs/ext4/file.c:39
Inline: True
Direct callers:
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
**Symbols:**

```
ffffffff813fb360-ffffffff813fb3b4: ext4_dio_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool ext4_dio_supported(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff81401830)
Location: fs/ext4/file.c:39
Inline: True
Direct callers:
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
**Symbols:**

```
ffffffff81401830-ffffffff81401884: ext4_dio_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool ext4_dio_supported(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff81453dc0)
Location: fs/ext4/file.c:39
Inline: True
Direct callers:
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
**Symbols:**

```
ffffffff81453dc0-ffffffff81453e14: ext4_dio_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool ext4_dio_supported(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff814d1740)
Location: fs/ext4/file.c:39
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
  - fs/ext4/file.c:ext4_file_read_iter
```
**Symbols:**

```
ffffffff814d1740-ffffffff814d17a6: ext4_dio_supported (STB_LOCAL)
```
</details>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct kiocb *iocb</code>
</li>
<li>
<b>Param added. </b>
<code>struct iov_iter *iter</code>
</li>
<li>
<b>Param removed. </b>
<code>struct inode *inode</code>
</li>
</ul>
</details>
</li>
</ul>
