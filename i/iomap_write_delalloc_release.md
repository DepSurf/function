# Function: <code>iomap_write_delalloc_release</code>

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
<summary>In <code>6.2</code>: ✅</summary>

```c
int iomap_write_delalloc_release(struct inode *inode, loff_t start_byte, loff_t end_byte, int (*punch)(struct inode *, loff_t, loff_t));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8151bf70)
Location: fs/iomap/buffered-io.c:954
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_file_buffered_write_punch_delalloc
```
**Symbols:**

```
ffffffff8151bf70-ffffffff8151c1b8: iomap_write_delalloc_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int iomap_write_delalloc_release(struct inode *inode, loff_t start_byte, loff_t end_byte, int (*punch)(struct inode *, loff_t, loff_t));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff815541b0)
Location: fs/iomap/buffered-io.c:974
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_file_buffered_write_punch_delalloc
```
**Symbols:**

```
ffffffff815541b0-ffffffff815543ef: iomap_write_delalloc_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int iomap_write_delalloc_release(struct inode *inode, loff_t start_byte, loff_t end_byte, iomap_punch_t punch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:1140
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_file_buffered_write_punch_delalloc
```
**Symbols:**

```
ffffffff8158a190-ffffffff8158a5cf: iomap_write_delalloc_release (STB_LOCAL)
ffffffff821c7972-ffffffff821c7b3b: iomap_write_delalloc_release.cold (STB_LOCAL)
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
