# Function: <code>bitmap_get_counter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bitmap_counter_t *bitmap_get_counter(struct bitmap_counts *bitmap, sector_t offset, sector_t *blocks, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff8169c820)
Location: drivers/md/bitmap.c:1314
Inline: False
Direct callers:
  - drivers/md/bitmap.c:bitmap_start_sync
  - drivers/md/bitmap.c:bitmap_end_sync
  - drivers/md/bitmap.c:bitmap_set_memory_bits
  - drivers/md/bitmap.c:bitmap_startwrite
  - drivers/md/bitmap.c:bitmap_endwrite
  - drivers/md/bitmap.c:bitmap_resize
  - drivers/md/bitmap.c:bitmap_resize
  - drivers/md/bitmap.c:bitmap_resize
  - drivers/md/bitmap.c:bitmap_daemon_work
```
**Symbols:**

```
ffffffff8169c820-ffffffff8169c9ff: bitmap_get_counter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bitmap_counter_t *bitmap_get_counter(struct bitmap_counts *bitmap, sector_t offset, sector_t *blocks, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff816fdb00)
Location: drivers/md/bitmap.c:1321
Inline: False
Direct callers:
  - drivers/md/bitmap.c:bitmap_resize
  - drivers/md/bitmap.c:bitmap_resize
  - drivers/md/bitmap.c:bitmap_resize
  - drivers/md/bitmap.c:bitmap_set_memory_bits
  - drivers/md/bitmap.c:bitmap_end_sync
  - drivers/md/bitmap.c:bitmap_start_sync
  - drivers/md/bitmap.c:bitmap_endwrite
  - drivers/md/bitmap.c:bitmap_startwrite
  - drivers/md/bitmap.c:bitmap_daemon_work
```
**Symbols:**

```
ffffffff816fdb00-ffffffff816fdbc8: bitmap_get_counter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bitmap_counter_t *bitmap_get_counter(struct bitmap_counts *bitmap, sector_t offset, sector_t *blocks, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff8172f760)
Location: drivers/md/bitmap.c:1349
Inline: False
Direct callers:
  - drivers/md/bitmap.c:bitmap_resize
  - drivers/md/bitmap.c:bitmap_resize
  - drivers/md/bitmap.c:bitmap_resize
  - drivers/md/bitmap.c:bitmap_set_memory_bits
  - drivers/md/bitmap.c:bitmap_end_sync
  - drivers/md/bitmap.c:bitmap_start_sync
  - drivers/md/bitmap.c:bitmap_endwrite
  - drivers/md/bitmap.c:bitmap_startwrite
  - drivers/md/bitmap.c:bitmap_daemon_work
```
**Symbols:**

```
ffffffff8172f760-ffffffff8172f828: bitmap_get_counter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bitmap_counter_t *bitmap_get_counter(struct bitmap_counts *bitmap, sector_t offset, sector_t *blocks, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff81748c30)
Location: drivers/md/bitmap.c:1351
Inline: False
Direct callers:
  - drivers/md/bitmap.c:bitmap_resize
  - drivers/md/bitmap.c:bitmap_resize
  - drivers/md/bitmap.c:bitmap_resize
  - drivers/md/bitmap.c:bitmap_set_memory_bits
  - drivers/md/bitmap.c:bitmap_start_sync
  - drivers/md/bitmap.c:bitmap_endwrite
  - drivers/md/bitmap.c:bitmap_startwrite
  - drivers/md/bitmap.c:bitmap_daemon_work
```
**Symbols:**

```
ffffffff81748c30-ffffffff81748cfa: bitmap_get_counter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bitmap_counter_t *bitmap_get_counter(struct bitmap_counts *bitmap, sector_t offset, sector_t *blocks, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff817baf10)
Location: drivers/md/md-bitmap.c:1355
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:bitmap_resize
  - drivers/md/md-bitmap.c:bitmap_resize
  - drivers/md/md-bitmap.c:bitmap_resize
  - drivers/md/md-bitmap.c:bitmap_set_memory_bits
  - drivers/md/md-bitmap.c:bitmap_start_sync
  - drivers/md/md-bitmap.c:bitmap_endwrite
  - drivers/md/md-bitmap.c:bitmap_startwrite
  - drivers/md/md-bitmap.c:bitmap_daemon_work
```
**Symbols:**

```
ffffffff817baf10-ffffffff817bafda: bitmap_get_counter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bitmap_counter_t *bitmap_get_counter(struct bitmap_counts *bitmap, sector_t offset, sector_t *blocks, int create);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff818030a0)
Location: drivers/md/md-bitmap.c:1355
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:bitmap_resize
  - drivers/md/md-bitmap.c:bitmap_resize
  - drivers/md/md-bitmap.c:bitmap_resize
  - drivers/md/md-bitmap.c:bitmap_set_memory_bits
  - drivers/md/md-bitmap.c:bitmap_start_sync
  - drivers/md/md-bitmap.c:bitmap_endwrite
  - drivers/md/md-bitmap.c:bitmap_startwrite
  - drivers/md/md-bitmap.c:bitmap_daemon_work
```
**Symbols:**

```
ffffffff818030a0-ffffffff81803178: bitmap_get_counter (STB_LOCAL)
```
</details>
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
