# Function: <code>iomap_inline_data</code>

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
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff81414247)
Location: include/linux/iomap.h:102
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
```
In fs/iomap/direct-io.c (ffffffff81415464)
Location: include/linux/iomap.h:102
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_inline_iter
  - fs/iomap/direct-io.c:iomap_dio_inline_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8148a3cb)
Location: include/linux/iomap.h:102
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
```
In fs/iomap/direct-io.c (ffffffff8148cc47)
Location: include/linux/iomap.h:102
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_inline_iter
  - fs/iomap/direct-io.c:iomap_dio_inline_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8151ddb8)
Location: include/linux/iomap.h:112
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
```
In fs/iomap/direct-io.c (ffffffff8152016a)
Location: include/linux/iomap.h:112
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_inline_iter
  - fs/iomap/direct-io.c:iomap_dio_inline_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff81555f54)
Location: include/linux/iomap.h:112
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
```
In fs/iomap/direct-io.c (ffffffff815581da)
Location: include/linux/iomap.h:112
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_inline_iter
  - fs/iomap/direct-io.c:iomap_dio_inline_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/iomap/buffered-io.c (ffffffff8158c448)
Location: include/linux/iomap.h:116
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_end
```
```
In fs/iomap/direct-io.c (ffffffff8158e80a)
Location: include/linux/iomap.h:116
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_inline_iter
  - fs/iomap/direct-io.c:iomap_dio_inline_iter
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
