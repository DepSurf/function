# Function: <code>write_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision ⚠️</summary>

```c
int write_page(void *buf, sector_t offset, struct hib_bio_batch *hb);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff810d2ad0)
Location: kernel/power/swap.c:350
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
```
```
In drivers/md/bitmap.c (ffffffff8169d4d0)
Location: drivers/md/bitmap.c:285
Inline: False
Direct callers:
  - drivers/md/bitmap.c:bitmap_init_from_disk
  - drivers/md/bitmap.c:bitmap_daemon_work
```
**Symbols:**

```
ffffffff810d2ad0-ffffffff810d2b81: write_page (STB_LOCAL)
ffffffff8169d4d0-ffffffff8169d7e0: write_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision ⚠️</summary>

```c
int write_page(void *buf, sector_t offset, struct hib_bio_batch *hb);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff810d7880)
Location: kernel/power/swap.c:369
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
```
```
In drivers/md/bitmap.c (ffffffff816fe7a0)
Location: drivers/md/bitmap.c:283
Inline: False
Direct callers:
  - drivers/md/bitmap.c:bitmap_daemon_work
  - drivers/md/bitmap.c:bitmap_init_from_disk
```
**Symbols:**

```
ffffffff810d7880-ffffffff810d793a: write_page (STB_LOCAL)
ffffffff816fe7a0-ffffffff816feabc: write_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision ⚠️</summary>

```c
int write_page(void *buf, sector_t offset, struct hib_bio_batch *hb);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff810de3a0)
Location: kernel/power/swap.c:369
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
```
```
In drivers/md/bitmap.c (ffffffff81730400)
Location: drivers/md/bitmap.c:286
Inline: False
Direct callers:
  - drivers/md/bitmap.c:bitmap_daemon_work
  - drivers/md/bitmap.c:bitmap_init_from_disk
```
**Symbols:**

```
ffffffff810de3a0-ffffffff810de45a: write_page (STB_LOCAL)
ffffffff81730400-ffffffff8173071c: write_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision ⚠️</summary>

```c
int write_page(void *buf, sector_t offset, struct hib_bio_batch *hb);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff810dd490)
Location: kernel/power/swap.c:369
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
```
```
In drivers/md/bitmap.c (ffffffff81748280)
Location: drivers/md/bitmap.c:287
Inline: False
Direct callers:
  - drivers/md/bitmap.c:bitmap_daemon_work
  - drivers/md/bitmap.c:bitmap_init_from_disk
```
**Symbols:**

```
ffffffff810dd490-ffffffff810dd546: write_page (STB_LOCAL)
ffffffff81748280-ffffffff81748594: write_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision ⚠️</summary>

```c
int write_page(void *buf, sector_t offset, struct hib_bio_batch *hb);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff810e5700)
Location: kernel/power/swap.c:370
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
```
```
In drivers/md/md-bitmap.c (ffffffff817ba510)
Location: drivers/md/md-bitmap.c:287
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:bitmap_daemon_work
  - drivers/md/md-bitmap.c:bitmap_init_from_disk
```
**Symbols:**

```
ffffffff810e5700-ffffffff810e57b6: write_page (STB_LOCAL)
ffffffff817ba510-ffffffff817ba824: write_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision ⚠️</summary>

```c
int write_page(void *buf, sector_t offset, struct hib_bio_batch *hb);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff810edc10)
Location: kernel/power/swap.c:370
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
```
```
In drivers/md/md-bitmap.c (ffffffff81802490)
Location: drivers/md/md-bitmap.c:287
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:bitmap_daemon_work
  - drivers/md/md-bitmap.c:bitmap_init_from_disk
```
**Symbols:**

```
ffffffff810edc10-ffffffff810edca9: write_page (STB_LOCAL)
ffffffff81802490-ffffffff818027c7: write_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision ⚠️</summary>

```c
int write_page(void *buf, sector_t offset, struct hib_bio_batch *hb);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff810f9280)
Location: kernel/power/swap.c:370
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
```
```
In drivers/md/md-bitmap.c (ffffffff8182e780)
Location: drivers/md/md-bitmap.c:287
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
```
**Symbols:**

```
ffffffff810f9280-ffffffff810f9319: write_page (STB_LOCAL)
ffffffff8182e780-ffffffff8182eab0: write_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision ⚠️</summary>

```c
int write_page(void *buf, sector_t offset, struct hib_bio_batch *hb);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff81101970)
Location: kernel/power/swap.c:368
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
```
```
In drivers/md/md-bitmap.c (ffffffff81870c80)
Location: drivers/md/md-bitmap.c:288
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
```
**Symbols:**

```
ffffffff81101970-ffffffff81101a09: write_page (STB_LOCAL)
ffffffff81870c80-ffffffff81870fb3: write_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision ⚠️</summary>

```c
int write_page(void *buf, sector_t offset, struct hib_bio_batch *hb);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff8110dda0)
Location: kernel/power/swap.c:368
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
```
```
In drivers/md/md-bitmap.c (ffffffff818a2a70)
Location: drivers/md/md-bitmap.c:288
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
```
**Symbols:**

```
ffffffff8110dda0-ffffffff8110de39: write_page (STB_LOCAL)
ffffffff818a2a70-ffffffff818a2da7: write_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline ⚠️</summary>

```c
int write_page(void *buf, sector_t offset, struct hib_bio_batch *hb);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff8111a7c1)
Location: kernel/power/swap.c:368
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_write
Direct callers:
  - kernel/power/swap.c:swap_write_page
  - kernel/power/swap.c:swap_write_page
```
```
In drivers/md/md-bitmap.c (ffffffff81973d00)
Location: drivers/md/md-bitmap.c:288
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
```
**Symbols:**

```
ffffffff81118dc0-ffffffff81118e59: write_page (STB_LOCAL)
ffffffff81973d00-ffffffff81973e4d: write_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision ⚠️</summary>

```c
int write_page(void *buf, sector_t offset, struct hib_bio_batch *hb);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff81114890)
Location: kernel/power/swap.c:376
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:swap_write_page
  - kernel/power/swap.c:swap_write_page
```
```
In drivers/md/md-bitmap.c (ffffffff81978c00)
Location: drivers/md/md-bitmap.c:288
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
```
**Symbols:**

```
ffffffff81114890-ffffffff81114929: write_page (STB_LOCAL)
ffffffff81978c00-ffffffff81978d4d: write_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision ⚠️</summary>

```c
int write_page(void *buf, sector_t offset, struct hib_bio_batch *hb);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff81115040)
Location: kernel/power/swap.c:376
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:swap_write_page
  - kernel/power/swap.c:swap_write_page
```
```
In drivers/md/md-bitmap.c (ffffffff8195c0f0)
Location: drivers/md/md-bitmap.c:288
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
```
**Symbols:**

```
ffffffff81115040-ffffffff811150d9: write_page (STB_LOCAL)
ffffffff8195c0f0-ffffffff8195c23d: write_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision ⚠️</summary>

```c
int write_page(void *buf, sector_t offset, struct hib_bio_batch *hb);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff811350e0)
Location: kernel/power/swap.c:376
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:swap_write_page
  - kernel/power/swap.c:swap_write_page
```
```
In drivers/md/md-bitmap.c (ffffffff81a01900)
Location: drivers/md/md-bitmap.c:288
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
```
**Symbols:**

```
ffffffff811350e0-ffffffff81135176: write_page (STB_LOCAL)
ffffffff81a01900-ffffffff81a01a4d: write_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision ⚠️</summary>

```c
int write_page(void *buf, sector_t offset, struct hib_bio_batch *hb);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff811573c0)
Location: kernel/power/swap.c:380
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
  - kernel/power/swap.c:swap_write_page
  - kernel/power/swap.c:swap_write_page
```
```
In drivers/md/md-bitmap.c (ffffffff81b697f0)
Location: drivers/md/md-bitmap.c:288
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
```
**Symbols:**

```
ffffffff811573c0-ffffffff81157474: write_page (STB_LOCAL)
ffffffff81b697f0-ffffffff81b69973: write_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline ⚠️</summary>

```c
int write_page(void *buf, sector_t offset, struct hib_bio_batch *hb);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff8118b21a)
Location: kernel/power/swap.c:378
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_write
Direct callers:
  - kernel/power/swap.c:swap_write_page
  - kernel/power/swap.c:swap_write_page
```
```
In drivers/md/md-bitmap.c (ffffffff81d056b0)
Location: drivers/md/md-bitmap.c:288
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_unplug
```
**Symbols:**

```
ffffffff81188140-ffffffff811881e9: write_page (STB_LOCAL)
ffffffff81d056b0-ffffffff81d05820: write_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline ⚠️</summary>

```c
int write_page(void *buf, sector_t offset, struct hib_bio_batch *hb);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff8119c963)
Location: kernel/power/swap.c:378
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_write
Direct callers:
  - kernel/power/swap.c:swap_write_page
  - kernel/power/swap.c:swap_write_page
```
```
In drivers/md/md-bitmap.c (ffffffff81d6e790)
Location: drivers/md/md-bitmap.c:304
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
```
**Symbols:**

```
ffffffff811992d0-ffffffff81199379: write_page (STB_LOCAL)
ffffffff81d6e790-ffffffff81d6e9c7: write_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int write_page(void *buf, sector_t offset, struct hib_bio_batch *hb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff811abab1)
Location: kernel/power/swap.c:379
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_write
Direct callers:
  - kernel/power/swap.c:swap_write_page
  - kernel/power/swap.c:swap_write_page
```
**Symbols:**

```
ffffffff811a8330-ffffffff811a83d9: write_page (STB_LOCAL)
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
void write_page(struct bitmap *bitmap, struct page *page, int wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffff800010af84c8)
Location: drivers/md/md-bitmap.c:288
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
```
**Symbols:**

```
ffff800010af84c8-ffff800010af88d8: write_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
int write_page(void *buf, sector_t offset, struct hib_bio_batch *hb);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (c03c0db4)
Location: kernel/power/swap.c:368
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
```
```
In drivers/md/md-bitmap.c (c0bd8568)
Location: drivers/md/md-bitmap.c:288
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
```
**Symbols:**

```
c03c0db4-c03c0e98: write_page (STB_LOCAL)
c0bd8568-c0bd8a0c: write_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void write_page(struct bitmap *bitmap, struct page *page, int wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (c000000000be4420)
Location: drivers/md/md-bitmap.c:288
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
```
**Symbols:**

```
c000000000be4420-c000000000be48cc: write_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void write_page(struct bitmap *bitmap, struct page *page, int wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffe0006e95d8)
Location: drivers/md/md-bitmap.c:288
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
```
**Symbols:**

```
ffffffe0006e95d8-ffffffe0006e9882: write_page (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Transformation ⚠️</summary>

```c
int write_page(void *buf, sector_t offset, struct hib_bio_batch *hb);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:432
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
```
```
In drivers/md/md-bitmap.c (ffffffff818488f0)
Location: drivers/md/md-bitmap.c:288
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
```
**Symbols:**

```
ffffffff81106020-ffffffff81106225: write_page (STB_LOCAL)
ffffffff81107ba8-ffffffff81107bd4: write_page.cold (STB_LOCAL)
ffffffff818488f0-ffffffff81848c27: write_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision ⚠️</summary>

```c
int write_page(void *buf, sector_t offset, struct hib_bio_batch *hb);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff810f7260)
Location: kernel/power/swap.c:368
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
```
```
In drivers/md/md-bitmap.c (ffffffff8180ff50)
Location: drivers/md/md-bitmap.c:288
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
```
**Symbols:**

```
ffffffff810f7260-ffffffff810f72f9: write_page (STB_LOCAL)
ffffffff8180ff50-ffffffff81810287: write_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision ⚠️</summary>

```c
int write_page(void *buf, sector_t offset, struct hib_bio_batch *hb);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff81104270)
Location: kernel/power/swap.c:368
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
```
```
In drivers/md/md-bitmap.c (ffffffff81897f20)
Location: drivers/md/md-bitmap.c:288
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
```
**Symbols:**

```
ffffffff81104270-ffffffff81104309: write_page (STB_LOCAL)
ffffffff81897f20-ffffffff81898257: write_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision ⚠️</summary>

```c
int write_page(void *buf, sector_t offset, struct hib_bio_batch *hb);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff8110f660)
Location: kernel/power/swap.c:368
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
```
```
In drivers/md/md-bitmap.c (ffffffff818b4110)
Location: drivers/md/md-bitmap.c:288
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_daemon_work
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
```
**Symbols:**

```
ffffffff8110f660-ffffffff8110f6f9: write_page (STB_LOCAL)
ffffffff818b4110-ffffffff818b4471: write_page (STB_LOCAL)
```
</details>
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
<details>
<summary>Changed between <code>amd64</code> and <code>arm64</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bitmap *bitmap</code>
</li>
<li>
<b>Param added. </b>
<code>struct page *page</code>
</li>
<li>
<b>Param added. </b>
<code>int wait</code>
</li>
<li>
<b>Param removed. </b>
<code>void *buf</code>
</li>
<li>
<b>Param removed. </b>
<code>sector_t offset</code>
</li>
<li>
<b>Param removed. </b>
<code>struct hib_bio_batch *hb</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>ppc64el</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bitmap *bitmap</code>
</li>
<li>
<b>Param added. </b>
<code>struct page *page</code>
</li>
<li>
<b>Param added. </b>
<code>int wait</code>
</li>
<li>
<b>Param removed. </b>
<code>void *buf</code>
</li>
<li>
<b>Param removed. </b>
<code>sector_t offset</code>
</li>
<li>
<b>Param removed. </b>
<code>struct hib_bio_batch *hb</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>riscv64</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bitmap *bitmap</code>
</li>
<li>
<b>Param added. </b>
<code>struct page *page</code>
</li>
<li>
<b>Param added. </b>
<code>int wait</code>
</li>
<li>
<b>Param removed. </b>
<code>void *buf</code>
</li>
<li>
<b>Param removed. </b>
<code>sector_t offset</code>
</li>
<li>
<b>Param removed. </b>
<code>struct hib_bio_batch *hb</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
