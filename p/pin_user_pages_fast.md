# Function: <code>pin_user_pages_fast</code>

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
int pin_user_pages_fast(long unsigned int start, int nr_pages, unsigned int gup_flags, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8128b590)
Location: mm/gup.c:2921
Inline: False
```
**Symbols:**

```
ffffffff8128b590-ffffffff8128b5b3: pin_user_pages_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pin_user_pages_fast(long unsigned int start, int nr_pages, unsigned int gup_flags, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81295400)
Location: mm/gup.c:2710
Inline: False
```
**Symbols:**

```
ffffffff81295400-ffffffff81295426: pin_user_pages_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pin_user_pages_fast(long unsigned int start, int nr_pages, unsigned int gup_flags, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8129ad70)
Location: mm/gup.c:2776
Inline: False
```
**Symbols:**

```
ffffffff8129ad70-ffffffff8129ad96: pin_user_pages_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pin_user_pages_fast(long unsigned int start, int nr_pages, unsigned int gup_flags, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812db740)
Location: mm/gup.c:2871
Inline: False
```
**Symbols:**

```
ffffffff812db740-ffffffff812db766: pin_user_pages_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pin_user_pages_fast(long unsigned int start, int nr_pages, unsigned int gup_flags, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8133b460)
Location: mm/gup.c:3021
Inline: False
```
**Symbols:**

```
ffffffff8133b460-ffffffff8133b4b7: pin_user_pages_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pin_user_pages_fast(long unsigned int start, int nr_pages, unsigned int gup_flags, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813b2fd0)
Location: mm/gup.c:3047
Inline: False
```
**Symbols:**

```
ffffffff813b2fd0-ffffffff813b3027: pin_user_pages_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pin_user_pages_fast(long unsigned int start, int nr_pages, unsigned int gup_flags, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813e7d10)
Location: mm/gup.c:3298
Inline: False
Direct callers:
  - io_uring/io_uring.c:__io_uaddr_map
  - lib/iov_iter.c:iov_iter_extract_pages
```
**Symbols:**

```
ffffffff813e7d10-ffffffff813e7dc2: pin_user_pages_fast (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pin_user_pages_fast(long unsigned int start, int nr_pages, unsigned int gup_flags, struct page **pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81412980)
Location: mm/gup.c:3316
Inline: False
Direct callers:
  - io_uring/io_uring.c:__io_uaddr_map
  - lib/iov_iter.c:iov_iter_extract_pages
  - drivers/iommu/iommufd/iova_bitmap.c:iova_bitmap_get
```
**Symbols:**

```
ffffffff81412980-ffffffff81412a32: pin_user_pages_fast (STB_GLOBAL)
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
