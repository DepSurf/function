# Function: <code>bitmap_set_memory_bits</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void bitmap_set_memory_bits(struct bitmap *bitmap, sector_t offset, int needed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff8169cdc0)
Location: drivers/md/bitmap.c:1603
Inline: False
Direct callers:
  - drivers/md/bitmap.c:bitmap_init_from_disk
  - drivers/md/bitmap.c:bitmap_init_from_disk
  - drivers/md/bitmap.c:bitmap_dirty_bits
  - drivers/md/bitmap.c:bitmap_copy_from_slot
```
**Symbols:**

```
ffffffff8169cdc0-ffffffff8169ce9f: bitmap_set_memory_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void bitmap_set_memory_bits(struct bitmap *bitmap, sector_t offset, int needed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff816fe0a0)
Location: drivers/md/bitmap.c:1631
Inline: False
Direct callers:
  - drivers/md/bitmap.c:bitmap_copy_from_slot
  - drivers/md/bitmap.c:bitmap_dirty_bits
  - drivers/md/bitmap.c:bitmap_init_from_disk
  - drivers/md/bitmap.c:bitmap_init_from_disk
```
**Symbols:**

```
ffffffff816fe0a0-ffffffff816fe17f: bitmap_set_memory_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void bitmap_set_memory_bits(struct bitmap *bitmap, sector_t offset, int needed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff8172fd00)
Location: drivers/md/bitmap.c:1659
Inline: False
Direct callers:
  - drivers/md/bitmap.c:bitmap_copy_from_slot
  - drivers/md/bitmap.c:bitmap_dirty_bits
  - drivers/md/bitmap.c:bitmap_init_from_disk
  - drivers/md/bitmap.c:bitmap_init_from_disk
```
**Symbols:**

```
ffffffff8172fd00-ffffffff8172fddf: bitmap_set_memory_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void bitmap_set_memory_bits(struct bitmap *bitmap, sector_t offset, int needed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff81749200)
Location: drivers/md/bitmap.c:1661
Inline: False
Direct callers:
  - drivers/md/bitmap.c:bitmap_copy_from_slot
  - drivers/md/bitmap.c:bitmap_dirty_bits
  - drivers/md/bitmap.c:bitmap_init_from_disk
  - drivers/md/bitmap.c:bitmap_init_from_disk
```
**Symbols:**

```
ffffffff81749200-ffffffff817492df: bitmap_set_memory_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void bitmap_set_memory_bits(struct bitmap *bitmap, sector_t offset, int needed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff817bb4e0)
Location: drivers/md/md-bitmap.c:1665
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:bitmap_dirty_bits
  - drivers/md/md-bitmap.c:bitmap_init_from_disk
  - drivers/md/md-bitmap.c:bitmap_init_from_disk
```
**Symbols:**

```
ffffffff817bb4e0-ffffffff817bb5bf: bitmap_set_memory_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void bitmap_set_memory_bits(struct bitmap *bitmap, sector_t offset, int needed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81803a90)
Location: drivers/md/md-bitmap.c:1665
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:bitmap_dirty_bits
  - drivers/md/md-bitmap.c:bitmap_init_from_disk
  - drivers/md/md-bitmap.c:bitmap_init_from_disk
```
**Symbols:**

```
ffffffff81803a90-ffffffff81803b6f: bitmap_set_memory_bits (STB_LOCAL)
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
