# Function: <code>bitmap_create</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct bitmap *bitmap_create(struct mddev *mddev, int slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff8169ed40)
Location: drivers/md/bitmap.c:1731
Inline: False
Direct callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/bitmap.c:bitmap_copy_from_slot
  - drivers/md/bitmap.c:location_store
```
**Symbols:**

```
ffffffff8169ed40-ffffffff8169f6c8: bitmap_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct bitmap *bitmap_create(struct mddev *mddev, int slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff81700110)
Location: drivers/md/bitmap.c:1760
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_run
  - drivers/md/bitmap.c:bitmap_copy_from_slot
```
**Symbols:**

```
ffffffff81700110-ffffffff81700abb: bitmap_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct bitmap *bitmap_create(struct mddev *mddev, int slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff81731e40)
Location: drivers/md/bitmap.c:1788
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_run
  - drivers/md/bitmap.c:bitmap_copy_from_slot
```
**Symbols:**

```
ffffffff81731e40-ffffffff81732829: bitmap_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct bitmap *bitmap_create(struct mddev *mddev, int slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff8174ad00)
Location: drivers/md/bitmap.c:1807
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_run
  - drivers/md/bitmap.c:get_bitmap_from_slot
```
**Symbols:**

```
ffffffff8174ad00-ffffffff8174b601: bitmap_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct bitmap *bitmap_create(struct mddev *mddev, int slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff817bd050)
Location: drivers/md/md-bitmap.c:1811
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_run
  - drivers/md/md-bitmap.c:get_bitmap_from_slot
```
**Symbols:**

```
ffffffff817bd050-ffffffff817bd96b: bitmap_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct bitmap *bitmap_create(struct mddev *mddev, int slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:1811
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_run
  - drivers/md/md-bitmap.c:get_bitmap_from_slot
```
**Symbols:**

```
ffffffff818060d6-ffffffff818061e1: bitmap_create.cold.32 (STB_LOCAL)
ffffffff81805140-ffffffff81805963: bitmap_create (STB_GLOBAL)
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
