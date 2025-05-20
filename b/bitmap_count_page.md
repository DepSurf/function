# Function: <code>bitmap_count_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void bitmap_count_page(struct bitmap_counts *bitmap, sector_t offset, int inc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff8169c150)
Location: drivers/md/bitmap.c:1165
Inline: False
Direct callers:
  - drivers/md/bitmap.c:bitmap_set_memory_bits
  - drivers/md/bitmap.c:bitmap_startwrite
  - drivers/md/bitmap.c:bitmap_resize
  - drivers/md/bitmap.c:bitmap_resize
  - drivers/md/bitmap.c:bitmap_daemon_work
```
**Symbols:**

```
ffffffff8169c150-ffffffff8169c1cd: bitmap_count_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void bitmap_count_page(struct bitmap_counts *bitmap, sector_t offset, int inc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff816fd290)
Location: drivers/md/bitmap.c:1172
Inline: False
Direct callers:
  - drivers/md/bitmap.c:bitmap_resize
  - drivers/md/bitmap.c:bitmap_resize
  - drivers/md/bitmap.c:bitmap_set_memory_bits
  - drivers/md/bitmap.c:bitmap_startwrite
  - drivers/md/bitmap.c:bitmap_daemon_work
```
**Symbols:**

```
ffffffff816fd290-ffffffff816fd30b: bitmap_count_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void bitmap_count_page(struct bitmap_counts *bitmap, sector_t offset, int inc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff8172ef10)
Location: drivers/md/bitmap.c:1195
Inline: False
Direct callers:
  - drivers/md/bitmap.c:bitmap_resize
  - drivers/md/bitmap.c:bitmap_resize
  - drivers/md/bitmap.c:bitmap_set_memory_bits
  - drivers/md/bitmap.c:bitmap_startwrite
  - drivers/md/bitmap.c:bitmap_daemon_work
```
**Symbols:**

```
ffffffff8172ef10-ffffffff8172ef8b: bitmap_count_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void bitmap_count_page(struct bitmap_counts *bitmap, sector_t offset, int inc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff817485a0)
Location: drivers/md/bitmap.c:1197
Inline: False
Direct callers:
  - drivers/md/bitmap.c:bitmap_resize
  - drivers/md/bitmap.c:bitmap_resize
  - drivers/md/bitmap.c:bitmap_set_memory_bits
  - drivers/md/bitmap.c:bitmap_startwrite
  - drivers/md/bitmap.c:bitmap_daemon_work
```
**Symbols:**

```
ffffffff817485a0-ffffffff8174861c: bitmap_count_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void bitmap_count_page(struct bitmap_counts *bitmap, sector_t offset, int inc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff817ba830)
Location: drivers/md/md-bitmap.c:1201
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:bitmap_resize
  - drivers/md/md-bitmap.c:bitmap_resize
  - drivers/md/md-bitmap.c:bitmap_set_memory_bits
  - drivers/md/md-bitmap.c:bitmap_startwrite
  - drivers/md/md-bitmap.c:bitmap_daemon_work
```
**Symbols:**

```
ffffffff817ba830-ffffffff817ba8ac: bitmap_count_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void bitmap_count_page(struct bitmap_counts *bitmap, sector_t offset, int inc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff818027d0)
Location: drivers/md/md-bitmap.c:1201
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:bitmap_resize
  - drivers/md/md-bitmap.c:bitmap_resize
  - drivers/md/md-bitmap.c:bitmap_set_memory_bits
  - drivers/md/md-bitmap.c:bitmap_startwrite
  - drivers/md/md-bitmap.c:bitmap_daemon_work
```
**Symbols:**

```
ffffffff818027d0-ffffffff8180284b: bitmap_count_page (STB_LOCAL)
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
