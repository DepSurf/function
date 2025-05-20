# Function: <code>page_cache_alloc</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811cf1d6)
Location: include/linux/pagemap.h:232
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_read_iter
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
In mm/filemap.c (ffffffff811ee80d)
Location: include/linux/pagemap.h:232
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read
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
In mm/filemap.c (ffffffff81200029)
Location: include/linux/pagemap.h:232
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read
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
In mm/filemap.c (ffffffff8121707c)
Location: include/linux/pagemap.h:219
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read
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
In mm/filemap.c (ffffffff8122498c)
Location: include/linux/pagemap.h:219
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81252635)
Location: include/linux/pagemap.h:257
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125bea1)
Location: include/linux/pagemap.h:293
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read_get_pages
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
In mm/filemap.c (ffffffff812620db)
Location: include/linux/pagemap.h:308
Inline: True
Inline callers:
  - mm/filemap.c:filemap_get_pages
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
In mm/filemap.c (ffffffff8129e6b6)
Location: include/linux/pagemap.h:308
Inline: True
Inline callers:
  - mm/filemap.c:filemap_get_pages
```
</details>
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffff8000102b1f34)
Location: include/linux/pagemap.h:219
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read
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
In mm/filemap.c (c04decc0)
Location: include/linux/pagemap.h:219
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read
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
In mm/filemap.c (c000000000367d98)
Location: include/linux/pagemap.h:219
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read
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
In mm/filemap.c (ffffffe0001d77f4)
Location: include/linux/pagemap.h:219
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read
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
In mm/filemap.c (ffffffff8121cfdc)
Location: include/linux/pagemap.h:219
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read
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
In mm/filemap.c (ffffffff812101b2)
Location: include/linux/pagemap.h:219
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read
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
In mm/filemap.c (ffffffff8121ad7c)
Location: include/linux/pagemap.h:219
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read
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
In mm/filemap.c (ffffffff81229ebb)
Location: include/linux/pagemap.h:219
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_buffered_read
```
</details>
</li>
</ul>

## Differences
