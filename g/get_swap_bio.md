# Function: <code>get_swap_bio</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct bio *get_swap_bio(gfp_t gfp_flags, struct page *page, bio_end_io_t *end_io);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff811d1fc0)
Location: mm/page_io.c:27
Inline: True
Direct callers:
  - mm/page_io.c:__swap_writepage
  - mm/page_io.c:swap_readpage
```
**Symbols:**

```
ffffffff811d1fc0-ffffffff811d202c: get_swap_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct bio *get_swap_bio(gfp_t gfp_flags, struct page *page, bio_end_io_t *end_io);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff811efb20)
Location: mm/page_io.c:27
Inline: True
Direct callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
```
**Symbols:**

```
ffffffff811efb20-ffffffff811efb8c: get_swap_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct bio *get_swap_bio(gfp_t gfp_flags, struct page *page, bio_end_io_t *end_io);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff812004c0)
Location: mm/page_io.c:27
Inline: True
Direct callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
```
**Symbols:**

```
ffffffff812004c0-ffffffff8120052c: get_swap_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct bio *get_swap_bio(gfp_t gfp_flags, struct page *page, bio_end_io_t *end_io);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff8120b120)
Location: mm/page_io.c:28
Inline: True
Direct callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
```
**Symbols:**

```
ffffffff8120b120-ffffffff8120b18c: get_swap_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct bio *get_swap_bio(gfp_t gfp_flags, struct page *page, bio_end_io_t *end_io);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff812244a0)
Location: mm/page_io.c:29
Inline: False
Direct callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
```
**Symbols:**

```
ffffffff812244a0-ffffffff81224596: get_swap_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct bio *get_swap_bio(gfp_t gfp_flags, struct page *page, bio_end_io_t *end_io);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff812469a0)
Location: mm/page_io.c:29
Inline: False
Direct callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
```
**Symbols:**

```
ffffffff812469a0-ffffffff81246a96: get_swap_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct bio *get_swap_bio(gfp_t gfp_flags, struct page *page, bio_end_io_t *end_io);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff8125adc0)
Location: mm/page_io.c:29
Inline: False
Direct callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
```
**Symbols:**

```
ffffffff8125adc0-ffffffff8125aebb: get_swap_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct bio *get_swap_bio(gfp_t gfp_flags, struct page *page, bio_end_io_t *end_io);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff81275fb0)
Location: mm/page_io.c:29
Inline: False
Direct callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
```
**Symbols:**

```
ffffffff81275fb0-ffffffff8127608f: get_swap_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct bio *get_swap_bio(gfp_t gfp_flags, struct page *page, bio_end_io_t *end_io);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff81285a90)
Location: mm/page_io.c:29
Inline: False
Direct callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
```
**Symbols:**

```
ffffffff81285a90-ffffffff81285b6f: get_swap_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct bio *get_swap_bio(gfp_t gfp_flags, struct page *page, bio_end_io_t *end_io);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff812b7b80)
Location: mm/page_io.c:29
Inline: False
Direct callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
```
**Symbols:**

```
ffffffff812b7b80-ffffffff812b7c5f: get_swap_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct bio *get_swap_bio(gfp_t gfp_flags, struct page *page, bio_end_io_t *end_io);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff812c3240)
Location: mm/page_io.c:29
Inline: False
Direct callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
```
**Symbols:**

```
ffffffff812c3240-ffffffff812c3320: get_swap_bio (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct bio *get_swap_bio(gfp_t gfp_flags, struct page *page, bio_end_io_t *end_io);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffff80001031fda8)
Location: mm/page_io.c:29
Inline: False
Direct callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
```
**Symbols:**

```
ffff80001031fda8-ffff80001031fea0: get_swap_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct bio *get_swap_bio(gfp_t gfp_flags, struct page *page, bio_end_io_t *end_io);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (c053871c)
Location: mm/page_io.c:29
Inline: False
Direct callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
```
**Symbols:**

```
c053871c-c0538808: get_swap_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct bio *get_swap_bio(gfp_t gfp_flags, struct page *page, bio_end_io_t *end_io);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (c0000000003f4c80)
Location: mm/page_io.c:29
Inline: False
Direct callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
```
**Symbols:**

```
c0000000003f4c80-c0000000003f4dac: get_swap_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct bio *get_swap_bio(gfp_t gfp_flags, struct page *page, bio_end_io_t *end_io);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffe000221626)
Location: mm/page_io.c:29
Inline: False
Direct callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
```
**Symbols:**

```
ffffffe000221626-ffffffe0002216c4: get_swap_bio (STB_LOCAL)
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
struct bio *get_swap_bio(gfp_t gfp_flags, struct page *page, bio_end_io_t *end_io);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff8127e0e0)
Location: mm/page_io.c:29
Inline: False
Direct callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
```
**Symbols:**

```
ffffffff8127e0e0-ffffffff8127e1bf: get_swap_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct bio *get_swap_bio(gfp_t gfp_flags, struct page *page, bio_end_io_t *end_io);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff8126ff10)
Location: mm/page_io.c:29
Inline: False
Direct callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
```
**Symbols:**

```
ffffffff8126ff10-ffffffff8126ffef: get_swap_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct bio *get_swap_bio(gfp_t gfp_flags, struct page *page, bio_end_io_t *end_io);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff8127be80)
Location: mm/page_io.c:29
Inline: False
Direct callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
```
**Symbols:**

```
ffffffff8127be80-ffffffff8127bf5f: get_swap_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct bio *get_swap_bio(gfp_t gfp_flags, struct page *page, bio_end_io_t *end_io);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_io.c (ffffffff8128ba60)
Location: mm/page_io.c:29
Inline: False
Direct callers:
  - mm/page_io.c:swap_readpage
  - mm/page_io.c:__swap_writepage
```
**Symbols:**

```
ffffffff8128ba60-ffffffff8128bb3f: get_swap_bio (STB_LOCAL)
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
