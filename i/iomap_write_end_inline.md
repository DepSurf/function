# Function: <code>iomap_write_end_inline</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff8132439c)
Location: fs/iomap.c:750
Inline: True
Inline callers:
  - fs/iomap.c:iomap_write_end
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8134c4e0)
Location: fs/iomap/buffered-io.c:682
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813647b0)
Location: fs/iomap/buffered-io.c:682
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int iomap_write_end_inline(struct inode *inode, struct page *page, struct iomap *iomap, loff_t pos, unsigned int copied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813aa7f0)
Location: fs/iomap/buffered-io.c:713
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
**Symbols:**

```
ffffffff813aa7f0-ffffffff813aa894: iomap_write_end_inline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t iomap_write_end_inline(struct inode *inode, struct page *page, struct iomap *iomap, loff_t pos, size_t copied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813bc9f0)
Location: fs/iomap/buffered-io.c:691
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
**Symbols:**

```
ffffffff813bc9f0-ffffffff813bca91: iomap_write_end_inline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff813c4a61)
Location: fs/iomap/buffered-io.c:691
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff81414215)
Location: fs/iomap/buffered-io.c:676
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8148a3a5)
Location: fs/iomap/buffered-io.c:679
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8151dd8f)
Location: fs/iomap/buffered-io.c:693
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff81555f2d)
Location: fs/iomap/buffered-io.c:715
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8158c425)
Location: fs/iomap/buffered-io.c:818
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffff80001042b2d0)
Location: fs/iomap/buffered-io.c:682
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (c05f45fc)
Location: fs/iomap/buffered-io.c:682
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (c00000000053bbf0)
Location: fs/iomap/buffered-io.c:682
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
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
In fs/iomap/buffered-io.c (ffffffe0002c895c)
Location: fs/iomap/buffered-io.c:682
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8135cd90)
Location: fs/iomap/buffered-io.c:682
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8134da30)
Location: fs/iomap/buffered-io.c:682
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8135a860)
Location: fs/iomap/buffered-io.c:682
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8136dfb0)
Location: fs/iomap/buffered-io.c:682
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned int copied</code> ➡️ <code>size_t copied</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>size_t</code>
</li>
</ul>
</details>
</li>
</ul>
