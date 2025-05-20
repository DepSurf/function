# Function: <code>blk_queue_free_zone_bitmaps</code>

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
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_free_zone_bitmaps(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff814cc281)
Location: block/blk-zoned.c:393
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
Direct callers:
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
ffffffff814cc220-ffffffff814cc25e: blk_queue_free_zone_bitmaps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_free_zone_bitmaps(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff814fa6c4)
Location: block/blk-zoned.c:397
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
Direct callers:
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
ffffffff814faac0-ffffffff814faafe: blk_queue_free_zone_bitmaps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_free_zone_bitmaps(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81518608)
Location: block/blk-zoned.c:436
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
Direct callers:
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
ffffffff81518a40-ffffffff81518a7e: blk_queue_free_zone_bitmaps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_queue_free_zone_bitmaps(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81578ee0)
Location: block/blk-zoned.c:379
Inline: False
Direct callers:
  - block/blk-sysfs.c:__blk_release_queue
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
**Symbols:**

```
ffffffff81578ee0-ffffffff81578f21: blk_queue_free_zone_bitmaps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_queue_free_zone_bitmaps(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81595990)
Location: block/blk-zoned.c:414
Inline: False
Direct callers:
  - block/blk-sysfs.c:blk_release_queue
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
**Symbols:**

```
ffffffff81595990-ffffffff815959d1: blk_queue_free_zone_bitmaps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_free_zone_bitmaps(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff8159c963)
Location: block/blk-zoned.c:406
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_queue_clear_zone_settings
Direct callers:
  - block/blk-sysfs.c:blk_release_queue
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
**Symbols:**

```
ffffffff8159c730-ffffffff8159c771: blk_queue_free_zone_bitmaps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_free_zone_bitmaps(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81605013)
Location: block/blk-zoned.c:460
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_queue_clear_zone_settings
Direct callers:
  - block/blk-sysfs.c:blk_release_queue
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
**Symbols:**

```
ffffffff81604de0-ffffffff81604e21: blk_queue_free_zone_bitmaps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_free_zone_bitmaps(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff816b8802)
Location: block/blk-zoned.c:453
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_queue_clear_zone_settings
Direct callers:
  - block/blk-sysfs.c:blk_release_queue
  - block/blk-zoned.c:blk_revalidate_disk_zones
```
**Symbols:**

```
ffffffff816b85b0-ffffffff816b85f7: blk_queue_free_zone_bitmaps (STB_GLOBAL)
```
</details>
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_free_zone_bitmaps(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffff80001061ff8c)
Location: block/blk-zoned.c:436
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
Direct callers:
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
ffff8000106204b0-ffff8000106204ec: blk_queue_free_zone_bitmaps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_free_zone_bitmaps(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (c07c7b00)
Location: block/blk-zoned.c:436
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
Direct callers:
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
c07c7fb4-c07c7fec: blk_queue_free_zone_bitmaps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_free_zone_bitmaps(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (c0000000007bf65c)
Location: block/blk-zoned.c:436
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
Direct callers:
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
c0000000007bfc90-c0000000007bfcf4: blk_queue_free_zone_bitmaps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_free_zone_bitmaps(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffe000452702)
Location: block/blk-zoned.c:436
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
Direct callers:
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
ffffffe000452b76-ffffffe000452bb6: blk_queue_free_zone_bitmaps (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_free_zone_bitmaps(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81510be8)
Location: block/blk-zoned.c:436
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
Direct callers:
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
ffffffff81511020-ffffffff8151105e: blk_queue_free_zone_bitmaps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_free_zone_bitmaps(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81500f08)
Location: block/blk-zoned.c:436
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
Direct callers:
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
ffffffff81501340-ffffffff8150137e: blk_queue_free_zone_bitmaps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_free_zone_bitmaps(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff8150cc78)
Location: block/blk-zoned.c:436
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
Direct callers:
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
ffffffff8150d0b0-ffffffff8150d0ee: blk_queue_free_zone_bitmaps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_free_zone_bitmaps(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81526358)
Location: block/blk-zoned.c:436
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
Direct callers:
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
ffffffff81526790-ffffffff815267ce: blk_queue_free_zone_bitmaps (STB_GLOBAL)
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
