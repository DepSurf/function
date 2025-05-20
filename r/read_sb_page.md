# Function: <code>read_sb_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int read_sb_page(struct mddev *mddev, loff_t offset, struct page *page, long unsigned int index, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff8169bb20)
Location: drivers/md/bitmap.c:145
Inline: False
Direct callers:
  - drivers/md/bitmap.c:bitmap_init_from_disk
  - drivers/md/bitmap.c:bitmap_create
```
**Symbols:**

```
ffffffff8169bb20-ffffffff8169bbf3: read_sb_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int read_sb_page(struct mddev *mddev, loff_t offset, struct page *page, long unsigned int index, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff816fcc50)
Location: drivers/md/bitmap.c:147
Inline: False
Direct callers:
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_init_from_disk
```
**Symbols:**

```
ffffffff816fcc50-ffffffff816fcd2e: read_sb_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int read_sb_page(struct mddev *mddev, loff_t offset, struct page *page, long unsigned int index, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff8172e820)
Location: drivers/md/bitmap.c:148
Inline: False
Direct callers:
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_init_from_disk
```
**Symbols:**

```
ffffffff8172e820-ffffffff8172e8fe: read_sb_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int read_sb_page(struct mddev *mddev, loff_t offset, struct page *page, long unsigned int index, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/bitmap.c (ffffffff81747760)
Location: drivers/md/bitmap.c:148
Inline: False
Direct callers:
  - drivers/md/bitmap.c:bitmap_create
  - drivers/md/bitmap.c:bitmap_init_from_disk
```
**Symbols:**

```
ffffffff81747760-ffffffff81747849: read_sb_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int read_sb_page(struct mddev *mddev, loff_t offset, struct page *page, long unsigned int index, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff817b99f0)
Location: drivers/md/md-bitmap.c:148
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:bitmap_create
  - drivers/md/md-bitmap.c:bitmap_init_from_disk
```
**Symbols:**

```
ffffffff817b99f0-ffffffff817b9ad9: read_sb_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int read_sb_page(struct mddev *mddev, loff_t offset, struct page *page, long unsigned int index, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81801b80)
Location: drivers/md/md-bitmap.c:148
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:bitmap_create
  - drivers/md/md-bitmap.c:bitmap_init_from_disk
```
**Symbols:**

```
ffffffff81801b80-ffffffff81801c58: read_sb_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int read_sb_page(struct mddev *mddev, loff_t offset, struct page *page, long unsigned int index, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff8182dd90)
Location: drivers/md/md-bitmap.c:148
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
```
**Symbols:**

```
ffffffff8182dd90-ffffffff8182de68: read_sb_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int read_sb_page(struct mddev *mddev, loff_t offset, struct page *page, long unsigned int index, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81870400)
Location: drivers/md/md-bitmap.c:149
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
**Symbols:**

```
ffffffff81870400-ffffffff818704e1: read_sb_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int read_sb_page(struct mddev *mddev, loff_t offset, struct page *page, long unsigned int index, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff818a2200)
Location: drivers/md/md-bitmap.c:149
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
**Symbols:**

```
ffffffff818a2200-ffffffff818a22dc: read_sb_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int read_sb_page(struct mddev *mddev, loff_t offset, struct page *page, long unsigned int index, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81971c60)
Location: drivers/md/md-bitmap.c:149
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
**Symbols:**

```
ffffffff81971c60-ffffffff81971d3c: read_sb_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int read_sb_page(struct mddev *mddev, loff_t offset, struct page *page, long unsigned int index, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81976b70)
Location: drivers/md/md-bitmap.c:149
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
**Symbols:**

```
ffffffff81976b70-ffffffff81976c49: read_sb_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int read_sb_page(struct mddev *mddev, loff_t offset, struct page *page, long unsigned int index, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff8195adb0)
Location: drivers/md/md-bitmap.c:149
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
**Symbols:**

```
ffffffff8195adb0-ffffffff8195ae89: read_sb_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int read_sb_page(struct mddev *mddev, loff_t offset, struct page *page, long unsigned int index, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81a005a0)
Location: drivers/md/md-bitmap.c:149
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
**Symbols:**

```
ffffffff81a005a0-ffffffff81a00679: read_sb_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int read_sb_page(struct mddev *mddev, loff_t offset, struct page *page, long unsigned int index, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81b67d60)
Location: drivers/md/md-bitmap.c:149
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
**Symbols:**

```
ffffffff81b67d60-ffffffff81b67e5a: read_sb_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int read_sb_page(struct mddev *mddev, loff_t offset, struct page *page, long unsigned int index, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81d03740)
Location: drivers/md/md-bitmap.c:149
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
**Symbols:**

```
ffffffff81d03740-ffffffff81d0383a: read_sb_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int read_sb_page(struct mddev *mddev, loff_t offset, struct page *page, long unsigned int index, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81d6c5f0)
Location: drivers/md/md-bitmap.c:142
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
**Symbols:**

```
ffffffff81d6c5f0-ffffffff81d6c6e7: read_sb_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int read_sb_page(struct mddev *mddev, loff_t offset, struct page *page, long unsigned int index, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81e23820)
Location: drivers/md/md-bitmap.c:144
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
**Symbols:**

```
ffffffff81e23820-ffffffff81e23916: read_sb_page (STB_LOCAL)
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
int read_sb_page(struct mddev *mddev, loff_t offset, struct page *page, long unsigned int index, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffff800010af6150)
Location: drivers/md/md-bitmap.c:149
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
**Symbols:**

```
ffff800010af6150-ffff800010af6254: read_sb_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int read_sb_page(struct mddev *mddev, loff_t offset, struct page *page, long unsigned int index, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (c0bd7b20)
Location: drivers/md/md-bitmap.c:149
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
**Symbols:**

```
c0bd7b20-c0bd7c2c: read_sb_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int read_sb_page(struct mddev *mddev, loff_t offset, struct page *page, long unsigned int index, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (c000000000be3390)
Location: drivers/md/md-bitmap.c:149
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
**Symbols:**

```
c000000000be3390-c000000000be34f4: read_sb_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int read_sb_page(struct mddev *mddev, loff_t offset, struct page *page, long unsigned int index, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffe0006e8e74)
Location: drivers/md/md-bitmap.c:149
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
**Symbols:**

```
ffffffe0006e8e74-ffffffe0006e8f36: read_sb_page (STB_LOCAL)
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
int read_sb_page(struct mddev *mddev, loff_t offset, struct page *page, long unsigned int index, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81848080)
Location: drivers/md/md-bitmap.c:149
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
**Symbols:**

```
ffffffff81848080-ffffffff8184815c: read_sb_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int read_sb_page(struct mddev *mddev, loff_t offset, struct page *page, long unsigned int index, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff8180f6e0)
Location: drivers/md/md-bitmap.c:149
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
**Symbols:**

```
ffffffff8180f6e0-ffffffff8180f7bc: read_sb_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int read_sb_page(struct mddev *mddev, loff_t offset, struct page *page, long unsigned int index, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff818976b0)
Location: drivers/md/md-bitmap.c:149
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
**Symbols:**

```
ffffffff818976b0-ffffffff8189778c: read_sb_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int read_sb_page(struct mddev *mddev, loff_t offset, struct page *page, long unsigned int index, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff818b3790)
Location: drivers/md/md-bitmap.c:149
Inline: False
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_init_from_disk
  - drivers/md/md-bitmap.c:md_bitmap_read_sb
```
**Symbols:**

```
ffffffff818b3790-ffffffff818b386c: read_sb_page (STB_LOCAL)
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
