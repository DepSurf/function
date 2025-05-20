# Function: <code>iomap_file_buffered_write_punch_delalloc</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int iomap_file_buffered_write_punch_delalloc(struct inode *inode, struct iomap *iomap, loff_t pos, loff_t length, ssize_t written, int (*punch)(struct inode *, loff_t, loff_t));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:1047
Inline: False
```
**Symbols:**

```
ffffffff8206ac62-ffffffff8206ac94: iomap_file_buffered_write_punch_delalloc.cold (STB_LOCAL)
ffffffff8151c1d0-ffffffff8151c290: iomap_file_buffered_write_punch_delalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int iomap_file_buffered_write_punch_delalloc(struct inode *inode, struct iomap *iomap, loff_t pos, loff_t length, ssize_t written, int (*punch)(struct inode *, loff_t, loff_t));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:1067
Inline: False
```
**Symbols:**

```
ffffffff820eabfd-ffffffff820eac2f: iomap_file_buffered_write_punch_delalloc.cold (STB_LOCAL)
ffffffff81554400-ffffffff815544bf: iomap_file_buffered_write_punch_delalloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int iomap_file_buffered_write_punch_delalloc(struct inode *inode, struct iomap *iomap, loff_t pos, loff_t length, ssize_t written, iomap_punch_t punch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:1232
Inline: False
```
**Symbols:**

```
ffffffff821c7b3b-ffffffff821c7b6d: iomap_file_buffered_write_punch_delalloc.cold (STB_LOCAL)
ffffffff8158a5e0-ffffffff8158a69f: iomap_file_buffered_write_punch_delalloc (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int (*punch)(struct inode *, loff_t, loff_t)</code> ➡️ <code>iomap_punch_t punch</code>
</li>
</ul>
</details>
</li>
</ul>
