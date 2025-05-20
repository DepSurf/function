# Function: <code>bitmap_init_from_disk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int bitmap_init_from_disk(struct bitmap *bitmap, sector_t start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff8169d7e0)
Location: drivers/md/bitmap.c:1020
Inline: False
Direct callers:
  - drivers/md/bitmap.c:bitmap_load
  - drivers/md/bitmap.c:bitmap_copy_from_slot
```
**Symbols:**

```
ffffffff8169d7e0-ffffffff8169dd2d: bitmap_init_from_disk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int bitmap_init_from_disk(struct bitmap *bitmap, sector_t start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff816feac0)
Location: drivers/md/bitmap.c:1027
Inline: False
Direct callers:
  - drivers/md/bitmap.c:bitmap_copy_from_slot
  - drivers/md/bitmap.c:bitmap_load
```
**Symbols:**

```
ffffffff816feac0-ffffffff816fefad: bitmap_init_from_disk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int bitmap_init_from_disk(struct bitmap *bitmap, sector_t start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff81730720)
Location: drivers/md/bitmap.c:1052
Inline: False
Direct callers:
  - drivers/md/bitmap.c:bitmap_copy_from_slot
  - drivers/md/bitmap.c:bitmap_load
```
**Symbols:**

```
ffffffff81730720-ffffffff81730c4b: bitmap_init_from_disk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int bitmap_init_from_disk(struct bitmap *bitmap, sector_t start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff817492e0)
Location: drivers/md/bitmap.c:1054
Inline: False
Direct callers:
  - drivers/md/bitmap.c:get_bitmap_from_slot
  - drivers/md/bitmap.c:bitmap_load
```
**Symbols:**

```
ffffffff817492e0-ffffffff8174976f: bitmap_init_from_disk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int bitmap_init_from_disk(struct bitmap *bitmap, sector_t start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff817bb5c0)
Location: drivers/md/md-bitmap.c:1058
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:get_bitmap_from_slot
  - drivers/md/md-bitmap.c:bitmap_load
```
**Symbols:**

```
ffffffff817bb5c0-ffffffff817bba42: bitmap_init_from_disk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int bitmap_init_from_disk(struct bitmap *bitmap, sector_t start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:1058
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:get_bitmap_from_slot
  - drivers/md/md-bitmap.c:bitmap_load
```
**Symbols:**

```
ffffffff81803b70-ffffffff81803f15: bitmap_init_from_disk (STB_LOCAL)
ffffffff81805fef-ffffffff818060d6: bitmap_init_from_disk.cold.31 (STB_LOCAL)
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
