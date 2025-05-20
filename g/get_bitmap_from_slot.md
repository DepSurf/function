# Function: <code>get_bitmap_from_slot</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct bitmap *get_bitmap_from_slot(struct mddev *mddev, int slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff8174b610)
Location: drivers/md/bitmap.c:1942
Inline: False
Direct callers:
  - drivers/md/bitmap.c:bitmap_copy_from_slot
```
**Symbols:**

```
ffffffff8174b610-ffffffff8174b662: get_bitmap_from_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct bitmap *get_bitmap_from_slot(struct mddev *mddev, int slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff817bd970)
Location: drivers/md/md-bitmap.c:1952
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:bitmap_copy_from_slot
```
**Symbols:**

```
ffffffff817bd970-ffffffff817bd9c2: get_bitmap_from_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct bitmap *get_bitmap_from_slot(struct mddev *mddev, int slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81805970)
Location: drivers/md/md-bitmap.c:1952
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:bitmap_copy_from_slot
```
**Symbols:**

```
ffffffff81805970-ffffffff818059ba: get_bitmap_from_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct bitmap *get_bitmap_from_slot(struct mddev *mddev, int slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81831b70)
Location: drivers/md/md-bitmap.c:1950
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
```
**Symbols:**

```
ffffffff81831b70-ffffffff81831bba: get_bitmap_from_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct bitmap *get_bitmap_from_slot(struct mddev *mddev, int slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff818742f0)
Location: drivers/md/md-bitmap.c:1957
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
```
**Symbols:**

```
ffffffff818742f0-ffffffff81874342: get_bitmap_from_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct bitmap *get_bitmap_from_slot(struct mddev *mddev, int slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff818a6100)
Location: drivers/md/md-bitmap.c:1957
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
```
**Symbols:**

```
ffffffff818a6100-ffffffff818a6152: get_bitmap_from_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct bitmap *get_bitmap_from_slot(struct mddev *mddev, int slot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff819761d5)
Location: drivers/md/md-bitmap.c:1952
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
```
**Symbols:**

```
ffffffff81975e80-ffffffff81975ed2: get_bitmap_from_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct bitmap *get_bitmap_from_slot(struct mddev *mddev, int slot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff8197b1d8)
Location: drivers/md/md-bitmap.c:1954
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
```
**Symbols:**

```
ffffffff8197ae70-ffffffff8197aec2: get_bitmap_from_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct bitmap *get_bitmap_from_slot(struct mddev *mddev, int slot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff8195f3f8)
Location: drivers/md/md-bitmap.c:1956
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
```
**Symbols:**

```
ffffffff8195f0a0-ffffffff8195f0f2: get_bitmap_from_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct bitmap *get_bitmap_from_slot(struct mddev *mddev, int slot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81a04d38)
Location: drivers/md/md-bitmap.c:1956
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
```
**Symbols:**

```
ffffffff81a049e0-ffffffff81a04a32: get_bitmap_from_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct bitmap *get_bitmap_from_slot(struct mddev *mddev, int slot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81b6ca28)
Location: drivers/md/md-bitmap.c:1957
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
```
**Symbols:**

```
ffffffff81b6c6b0-ffffffff81b6c71b: get_bitmap_from_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct bitmap *get_bitmap_from_slot(struct mddev *mddev, int slot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81d08b38)
Location: drivers/md/md-bitmap.c:1957
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
```
**Symbols:**

```
ffffffff81d08790-ffffffff81d087fb: get_bitmap_from_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct bitmap *get_bitmap_from_slot(struct mddev *mddev, int slot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81d71ca8)
Location: drivers/md/md-bitmap.c:2023
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
```
**Symbols:**

```
ffffffff81d71920-ffffffff81d71978: get_bitmap_from_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct bitmap *get_bitmap_from_slot(struct mddev *mddev, int slot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81e28d78)
Location: drivers/md/md-bitmap.c:2027
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
```
**Symbols:**

```
ffffffff81e28a00-ffffffff81e28a58: get_bitmap_from_slot (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct bitmap *get_bitmap_from_slot(struct mddev *mddev, int slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffff800010afafe8)
Location: drivers/md/md-bitmap.c:1957
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
```
**Symbols:**

```
ffff800010afafe8-ffff800010afb06c: get_bitmap_from_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct bitmap *get_bitmap_from_slot(struct mddev *mddev, int slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (c0bdba88)
Location: drivers/md/md-bitmap.c:1957
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
```
**Symbols:**

```
c0bdba88-c0bdbadc: get_bitmap_from_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct bitmap *get_bitmap_from_slot(struct mddev *mddev, int slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (c000000000be9130)
Location: drivers/md/md-bitmap.c:1957
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
```
**Symbols:**

```
c000000000be9130-c000000000be91dc: get_bitmap_from_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct bitmap *get_bitmap_from_slot(struct mddev *mddev, int slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffe0006ec832)
Location: drivers/md/md-bitmap.c:1957
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
```
**Symbols:**

```
ffffffe0006ec832-ffffffe0006ec8a8: get_bitmap_from_slot (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct bitmap *get_bitmap_from_slot(struct mddev *mddev, int slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff8184bf80)
Location: drivers/md/md-bitmap.c:1957
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
```
**Symbols:**

```
ffffffff8184bf80-ffffffff8184bfd2: get_bitmap_from_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct bitmap *get_bitmap_from_slot(struct mddev *mddev, int slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff818135a0)
Location: drivers/md/md-bitmap.c:1957
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
```
**Symbols:**

```
ffffffff818135a0-ffffffff818135f2: get_bitmap_from_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct bitmap *get_bitmap_from_slot(struct mddev *mddev, int slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff8189b5b0)
Location: drivers/md/md-bitmap.c:1957
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
```
**Symbols:**

```
ffffffff8189b5b0-ffffffff8189b602: get_bitmap_from_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct bitmap *get_bitmap_from_slot(struct mddev *mddev, int slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff818b7740)
Location: drivers/md/md-bitmap.c:1957
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
```
**Symbols:**

```
ffffffff818b7740-ffffffff818b7792: get_bitmap_from_slot (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
