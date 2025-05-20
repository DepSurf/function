# Function: <code>ext4_handle_inode_extension</code>

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
ssize_t ext4_handle_inode_extension(struct inode *inode, loff_t offset, ssize_t written, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff813e8e40)
Location: fs/ext4/file.c:283
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
```
**Symbols:**

```
ffffffff813e8e40-ffffffff813e9103: ext4_handle_inode_extension (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t ext4_handle_inode_extension(struct inode *inode, loff_t offset, ssize_t written, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff813faca0)
Location: fs/ext4/file.c:284
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
```
**Symbols:**

```
ffffffff813faca0-ffffffff813faf69: ext4_handle_inode_extension (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t ext4_handle_inode_extension(struct inode *inode, loff_t offset, ssize_t written, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff81401110)
Location: fs/ext4/file.c:283
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
```
**Symbols:**

```
ffffffff81401110-ffffffff81401405: ext4_handle_inode_extension (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t ext4_handle_inode_extension(struct inode *inode, loff_t offset, ssize_t written, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/file.c (0)
Location: fs/ext4/file.c:283
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
```
**Symbols:**

```
ffffffff81453680-ffffffff81453985: ext4_handle_inode_extension (STB_LOCAL)
ffffffff81cc9c75-ffffffff81cc9ce6: ext4_handle_inode_extension.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t ext4_handle_inode_extension(struct inode *inode, loff_t offset, ssize_t written, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/file.c (0)
Location: fs/ext4/file.c:283
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
```
**Symbols:**

```
ffffffff814d1200-ffffffff814d14e3: ext4_handle_inode_extension (STB_LOCAL)
ffffffff81e7c95f-ffffffff81e7c9d2: ext4_handle_inode_extension.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
ssize_t ext4_handle_inode_extension(struct inode *inode, loff_t offset, ssize_t written, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/file.c (0)
Location: fs/ext4/file.c:298
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
```
**Symbols:**

```
ffffffff81569d20-ffffffff8156a00b: ext4_handle_inode_extension (STB_LOCAL)
ffffffff8206cf8b-ffffffff8206cffe: ext4_handle_inode_extension.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
ssize_t ext4_handle_inode_extension(struct inode *inode, loff_t offset, ssize_t written, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/file.c (0)
Location: fs/ext4/file.c:308
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dio_write_iter
```
**Symbols:**

```
ffffffff815a1b20-ffffffff815a1e02: ext4_handle_inode_extension (STB_LOCAL)
ffffffff820ecd21-ffffffff820ecd7e: ext4_handle_inode_extension.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t ext4_handle_inode_extension(struct inode *inode, loff_t offset, ssize_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff815da800)
Location: fs/ext4/file.c:308
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dax_write_iter
  - fs/ext4/file.c:ext4_dio_write_end_io
```
**Symbols:**

```
ffffffff815da800-ffffffff815da937: ext4_handle_inode_extension (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>ssize_t written</code>
</li>
<li>
<b>Param reordered. </b>
<code>inode, offset, written, count</code> ➡️ <code>inode, offset, count</code>
</li>
<li>
<b>Param type changed. </b>
<code>size_t count</code> ➡️ <code>ssize_t count</code>
</li>
</ul>
</details>
</li>
</ul>
