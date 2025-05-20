# Function: <code>bitmap_write_all</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void bitmap_write_all(struct bitmap *bitmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/bitmap.c (ffffffff8169c5d0)
Location: drivers/md/bitmap.c:1146
Inline: True
Inline callers:
  - drivers/md/bitmap.c:bitmap_copy_from_slot
Direct callers:
  - drivers/md/bitmap.c:bitmap_copy_from_slot
```
**Symbols:**

```
ffffffff8169c5d0-ffffffff8169c60a: bitmap_write_all.part.23 (STB_LOCAL)
ffffffff8169e840-ffffffff8169e864: bitmap_write_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void bitmap_write_all(struct bitmap *bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff816ffbf0)
Location: drivers/md/bitmap.c:1153
Inline: False
```
**Symbols:**

```
ffffffff816ffbf0-ffffffff816ffc42: bitmap_write_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void bitmap_write_all(struct bitmap *bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff817318f0)
Location: drivers/md/bitmap.c:1176
Inline: False
```
**Symbols:**

```
ffffffff817318f0-ffffffff81731942: bitmap_write_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void bitmap_write_all(struct bitmap *bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff8174a6e0)
Location: drivers/md/bitmap.c:1178
Inline: False
```
**Symbols:**

```
ffffffff8174a6e0-ffffffff8174a732: bitmap_write_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void bitmap_write_all(struct bitmap *bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff817bca20)
Location: drivers/md/md-bitmap.c:1182
Inline: False
```
**Symbols:**

```
ffffffff817bca20-ffffffff817bca7d: bitmap_write_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void bitmap_write_all(struct bitmap *bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81804b10)
Location: drivers/md/md-bitmap.c:1182
Inline: False
```
**Symbols:**

```
ffffffff81804b10-ffffffff81804b6c: bitmap_write_all (STB_GLOBAL)
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
