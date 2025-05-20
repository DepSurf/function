# Function: <code>add_to_free_area_random</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void add_to_free_area_random(struct page *page, struct free_area *area, int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shuffle.c (ffffffff812744b0)
Location: mm/shuffle.c:186
Inline: False
Direct callers:
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
```
**Symbols:**

```
ffffffff812744b0-ffffffff81274552: add_to_free_area_random (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void add_to_free_area_random(struct page *page, struct free_area *area, int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shuffle.c (ffffffff812832c0)
Location: mm/shuffle.c:186
Inline: False
Direct callers:
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
```
**Symbols:**

```
ffffffff812832c0-ffffffff81283362: add_to_free_area_random (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void add_to_free_area_random(struct page *page, struct free_area *area, int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shuffle.c (ffff80001031b1f8)
Location: mm/shuffle.c:186
Inline: False
Direct callers:
  - mm/page_alloc.c:__free_one_page
```
**Symbols:**

```
ffff80001031b1f8-ffff80001031b2d0: add_to_free_area_random (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void add_to_free_area_random(struct page *page, struct free_area *area, int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shuffle.c (c05352a8)
Location: mm/shuffle.c:186
Inline: False
Direct callers:
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
```
**Symbols:**

```
c05352a8-c053535c: add_to_free_area_random (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void add_to_free_area_random(struct page *page, struct free_area *area, int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shuffle.c (c0000000003eead0)
Location: mm/shuffle.c:186
Inline: False
Direct callers:
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
```
**Symbols:**

```
c0000000003eead0-c0000000003eec0c: add_to_free_area_random (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void add_to_free_area_random(struct page *page, struct free_area *area, int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shuffle.c (ffffffe00022034e)
Location: mm/shuffle.c:186
Inline: False
Direct callers:
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
```
**Symbols:**

```
ffffffe00022034e-ffffffe000220402: add_to_free_area_random (STB_GLOBAL)
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
void add_to_free_area_random(struct page *page, struct free_area *area, int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shuffle.c (ffffffff8127b910)
Location: mm/shuffle.c:186
Inline: False
Direct callers:
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
```
**Symbols:**

```
ffffffff8127b910-ffffffff8127b9b2: add_to_free_area_random (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void add_to_free_area_random(struct page *page, struct free_area *area, int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shuffle.c (ffffffff8126d7f0)
Location: mm/shuffle.c:186
Inline: False
Direct callers:
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
```
**Symbols:**

```
ffffffff8126d7f0-ffffffff8126d892: add_to_free_area_random (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void add_to_free_area_random(struct page *page, struct free_area *area, int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shuffle.c (ffffffff812796b0)
Location: mm/shuffle.c:186
Inline: False
Direct callers:
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
```
**Symbols:**

```
ffffffff812796b0-ffffffff81279752: add_to_free_area_random (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void add_to_free_area_random(struct page *page, struct free_area *area, int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shuffle.c (ffffffff812892a0)
Location: mm/shuffle.c:186
Inline: False
Direct callers:
  - mm/page_alloc.c:free_one_page
  - mm/page_alloc.c:free_pcppages_bulk
```
**Symbols:**

```
ffffffff812892a0-ffffffff81289342: add_to_free_area_random (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
