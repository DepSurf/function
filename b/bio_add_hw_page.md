# Function: <code>bio_add_hw_page</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bio_add_hw_page(struct request_queue *q, struct bio *bio, struct page *page, unsigned int len, unsigned int offset, unsigned int max_sectors, bool *same_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8153f4a0)
Location: block/bio.c:790
Inline: False
Direct callers:
  - block/bio.c:__bio_iov_append_get_pages
  - block/bio.c:bio_add_pc_page
  - block/blk-map.c:bio_map_user_iov
```
**Symbols:**

```
ffffffff8153f4a0-ffffffff8153f624: bio_add_hw_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bio_add_hw_page(struct request_queue *q, struct bio *bio, struct page *page, unsigned int len, unsigned int offset, unsigned int max_sectors, bool *same_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8155bcb0)
Location: block/bio.c:790
Inline: False
Direct callers:
  - block/bio.c:__bio_iov_append_get_pages
  - block/bio.c:bio_add_pc_page
  - block/blk-map.c:bio_map_user_iov
```
**Symbols:**

```
ffffffff8155bcb0-ffffffff8155be34: bio_add_hw_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bio_add_hw_page(struct request_queue *q, struct bio *bio, struct page *page, unsigned int len, unsigned int offset, unsigned int max_sectors, bool *same_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81564310)
Location: block/bio.c:746
Inline: False
Direct callers:
  - block/bio.c:bio_add_zone_append_page
  - block/bio.c:bio_add_pc_page
  - block/blk-map.c:bio_map_user_iov
```
**Symbols:**

```
ffffffff81564310-ffffffff81564490: bio_add_hw_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int bio_add_hw_page(struct request_queue *q, struct bio *bio, struct page *page, unsigned int len, unsigned int offset, unsigned int max_sectors, bool *same_page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff815c87a0)
Location: block/bio.c:829
Inline: True
Direct callers:
  - block/bio.c:__bio_iov_append_get_pages
  - block/bio.c:bio_add_zone_append_page
  - block/bio.c:bio_add_pc_page
  - block/blk-map.c:bio_map_user_iov
```
**Symbols:**

```
ffffffff815c87a0-ffffffff815c8920: bio_add_hw_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bio_add_hw_page(struct request_queue *q, struct bio *bio, struct page *page, unsigned int len, unsigned int offset, unsigned int max_sectors, bool *same_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81673620)
Location: block/bio.c:947
Inline: False
Direct callers:
  - block/bio.c:bio_iov_iter_get_pages
  - block/bio.c:bio_add_zone_append_page
  - block/bio.c:bio_add_pc_page
  - block/blk-map.c:bio_map_user_iov
```
**Symbols:**

```
ffffffff81673620-ffffffff816737d9: bio_add_hw_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bio_add_hw_page(struct request_queue *q, struct bio *bio, struct page *page, unsigned int len, unsigned int offset, unsigned int max_sectors, bool *same_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8172f1e0)
Location: block/bio.c:1002
Inline: False
Direct callers:
  - block/bio.c:__bio_iov_iter_get_pages
  - block/bio.c:bio_add_zone_append_page
  - block/bio.c:bio_add_pc_page
  - block/blk-map.c:bio_map_user_iov
```
**Symbols:**

```
ffffffff8172f1e0-ffffffff8172f399: bio_add_hw_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bio_add_hw_page(struct request_queue *q, struct bio *bio, struct page *page, unsigned int len, unsigned int offset, unsigned int max_sectors, bool *same_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8176b510)
Location: block/bio.c:965
Inline: False
Direct callers:
  - block/bio.c:__bio_iov_iter_get_pages
  - block/bio.c:bio_add_zone_append_page
  - block/bio.c:bio_add_pc_page
  - block/blk-map.c:bio_map_user_iov
```
**Symbols:**

```
ffffffff8176b510-ffffffff8176b642: bio_add_hw_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bio_add_hw_page(struct request_queue *q, struct bio *bio, struct page *page, unsigned int len, unsigned int offset, unsigned int max_sectors, bool *same_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff817ad9a0)
Location: block/bio.c:965
Inline: False
Direct callers:
  - block/bio.c:__bio_iov_iter_get_pages
  - block/bio.c:bio_add_zone_append_page
  - block/bio.c:bio_add_pc_page
  - block/blk-map.c:bio_map_user_iov
```
**Symbols:**

```
ffffffff817ad9a0-ffffffff817adae3: bio_add_hw_page (STB_GLOBAL)
```
</details>
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
