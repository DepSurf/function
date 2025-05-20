# Function: <code>md_bitmap_create</code>

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
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct bitmap *md_bitmap_create(struct mddev *mddev, int slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:1809
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_run
  - drivers/md/md-bitmap.c:get_bitmap_from_slot
```
**Symbols:**

```
ffffffff81832266-ffffffff81832371: md_bitmap_create.cold.32 (STB_LOCAL)
ffffffff81831340-ffffffff81831b63: md_bitmap_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct bitmap *md_bitmap_create(struct mddev *mddev, int slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:1812
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_run
  - drivers/md/md-bitmap.c:get_bitmap_from_slot
```
**Symbols:**

```
ffffffff81874b36-ffffffff81874b64: md_bitmap_create.cold (STB_LOCAL)
ffffffff81873ef0-ffffffff818742ea: md_bitmap_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct bitmap *md_bitmap_create(struct mddev *mddev, int slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:1812
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_run
  - drivers/md/md-bitmap.c:get_bitmap_from_slot
```
**Symbols:**

```
ffffffff818a6946-ffffffff818a6974: md_bitmap_create.cold (STB_LOCAL)
ffffffff818a5d00-ffffffff818a60fa: md_bitmap_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct bitmap *md_bitmap_create(struct mddev *mddev, int slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:1807
Inline: False
Direct callers:
  - drivers/md/md.c:update_array_info
  - drivers/md/md.c:set_bitmap_file
  - drivers/md/md.c:md_run
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
```
**Symbols:**

```
ffffffff819767a4-ffffffff819767d2: md_bitmap_create.cold (STB_LOCAL)
ffffffff81975c30-ffffffff81975e7f: md_bitmap_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct bitmap *md_bitmap_create(struct mddev *mddev, int slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:1808
Inline: False
Direct callers:
  - drivers/md/md.c:update_array_info
  - drivers/md/md.c:set_bitmap_file
  - drivers/md/md.c:md_run
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
```
**Symbols:**

```
ffffffff81c27eb4-ffffffff81c27ee2: md_bitmap_create.cold (STB_LOCAL)
ffffffff8197ac20-ffffffff8197ae6f: md_bitmap_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct bitmap *md_bitmap_create(struct mddev *mddev, int slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:1810
Inline: False
Direct callers:
  - drivers/md/md.c:update_array_info
  - drivers/md/md.c:set_bitmap_file
  - drivers/md/md.c:md_run
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
```
**Symbols:**

```
ffffffff81c1a079-ffffffff81c1a0a7: md_bitmap_create.cold (STB_LOCAL)
ffffffff8195ee50-ffffffff8195f09f: md_bitmap_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct bitmap *md_bitmap_create(struct mddev *mddev, int slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:1810
Inline: False
Direct callers:
  - drivers/md/md.c:update_array_info
  - drivers/md/md.c:set_bitmap_file
  - drivers/md/md.c:md_run
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
```
**Symbols:**

```
ffffffff81d29b7e-ffffffff81d29bac: md_bitmap_create.cold (STB_LOCAL)
ffffffff81a04790-ffffffff81a049dc: md_bitmap_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct bitmap *md_bitmap_create(struct mddev *mddev, int slot);
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
  - drivers/md/md.c:update_array_info
  - drivers/md/md.c:set_bitmap_file
  - drivers/md/md.c:md_run
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
```
**Symbols:**

```
ffffffff81ef5ee5-ffffffff81ef5f14: md_bitmap_create.cold (STB_LOCAL)
ffffffff81b6c460-ffffffff81b6c6a8: md_bitmap_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct bitmap *md_bitmap_create(struct mddev *mddev, int slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81d084f0)
Location: drivers/md/md-bitmap.c:1811
Inline: False
Direct callers:
  - drivers/md/md.c:update_array_info
  - drivers/md/md.c:set_bitmap_file
  - drivers/md/md.c:md_run
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
```
**Symbols:**

```
ffffffff81d084f0-ffffffff81d0877b: md_bitmap_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct bitmap *md_bitmap_create(struct mddev *mddev, int slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81d71680)
Location: drivers/md/md-bitmap.c:1877
Inline: False
Direct callers:
  - drivers/md/md.c:update_array_info
  - drivers/md/md.c:set_bitmap_file
  - drivers/md/md.c:md_run
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
```
**Symbols:**

```
ffffffff81d71680-ffffffff81d7190b: md_bitmap_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct bitmap *md_bitmap_create(struct mddev *mddev, int slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81e28730)
Location: drivers/md/md-bitmap.c:1881
Inline: False
Direct callers:
  - drivers/md/md.c:update_array_info
  - drivers/md/md.c:set_bitmap_file
  - drivers/md/md.c:md_run
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
```
**Symbols:**

```
ffffffff81e28730-ffffffff81e289ed: md_bitmap_create (STB_GLOBAL)
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
struct bitmap *md_bitmap_create(struct mddev *mddev, int slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffff800010afab98)
Location: drivers/md/md-bitmap.c:1812
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_run
  - drivers/md/md-bitmap.c:get_bitmap_from_slot
```
**Symbols:**

```
ffff800010afab98-ffff800010afafe4: md_bitmap_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct bitmap *md_bitmap_create(struct mddev *mddev, int slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (c0bdb680)
Location: drivers/md/md-bitmap.c:1812
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_run
  - drivers/md/md-bitmap.c:get_bitmap_from_slot
```
**Symbols:**

```
c0bdb680-c0bdba88: md_bitmap_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct bitmap *md_bitmap_create(struct mddev *mddev, int slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (c000000000be8c10)
Location: drivers/md/md-bitmap.c:1812
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_run
  - drivers/md/md-bitmap.c:get_bitmap_from_slot
```
**Symbols:**

```
c000000000be8c10-c000000000be9130: md_bitmap_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct bitmap *md_bitmap_create(struct mddev *mddev, int slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffe0006ec4ba)
Location: drivers/md/md-bitmap.c:1812
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_run
  - drivers/md/md-bitmap.c:get_bitmap_from_slot
```
**Symbols:**

```
ffffffe0006ec4ba-ffffffe0006ec832: md_bitmap_create (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
struct bitmap *md_bitmap_create(struct mddev *mddev, int slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:1812
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_run
  - drivers/md/md-bitmap.c:get_bitmap_from_slot
```
**Symbols:**

```
ffffffff8184c7c6-ffffffff8184c7f4: md_bitmap_create.cold (STB_LOCAL)
ffffffff8184bb80-ffffffff8184bf7a: md_bitmap_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct bitmap *md_bitmap_create(struct mddev *mddev, int slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:1812
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_run
  - drivers/md/md-bitmap.c:get_bitmap_from_slot
```
**Symbols:**

```
ffffffff81813de6-ffffffff81813e14: md_bitmap_create.cold (STB_LOCAL)
ffffffff818131a0-ffffffff8181359a: md_bitmap_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct bitmap *md_bitmap_create(struct mddev *mddev, int slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:1812
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_run
  - drivers/md/md-bitmap.c:get_bitmap_from_slot
```
**Symbols:**

```
ffffffff8189bdf6-ffffffff8189be24: md_bitmap_create.cold (STB_LOCAL)
ffffffff8189b1b0-ffffffff8189b5aa: md_bitmap_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct bitmap *md_bitmap_create(struct mddev *mddev, int slot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (0)
Location: drivers/md/md-bitmap.c:1812
Inline: False
Direct callers:
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_ioctl
  - drivers/md/md.c:md_run
  - drivers/md/md-bitmap.c:get_bitmap_from_slot
```
**Symbols:**

```
ffffffff818b7f9e-ffffffff818b7fe4: md_bitmap_create.cold (STB_LOCAL)
ffffffff818b7310-ffffffff818b7737: md_bitmap_create (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
