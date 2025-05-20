# Function: <code>pagevec_lookup_range_nr_tag</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range_nr_tag(struct pagevec *pvec, struct address_space *mapping, long unsigned int *index, long unsigned int end, int tag, unsigned int max_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811df3a0)
Location: mm/swap.c:1002
Inline: False
```
**Symbols:**

```
ffffffff811df3a0-ffffffff811df3db: pagevec_lookup_range_nr_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range_nr_tag(struct pagevec *pvec, struct address_space *mapping, long unsigned int *index, long unsigned int end, int tag, unsigned int max_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81200b60)
Location: mm/swap.c:1013
Inline: False
```
**Symbols:**

```
ffffffff81200b60-ffffffff81200b9b: pagevec_lookup_range_nr_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range_nr_tag(struct pagevec *pvec, struct address_space *mapping, long unsigned int *index, long unsigned int end, xa_mark_t tag, unsigned int max_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff812134d0)
Location: mm/swap.c:1014
Inline: False
```
**Symbols:**

```
ffffffff812134d0-ffffffff8121350b: pagevec_lookup_range_nr_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range_nr_tag(struct pagevec *pvec, struct address_space *mapping, long unsigned int *index, long unsigned int end, xa_mark_t tag, unsigned int max_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81222f00)
Location: mm/swap.c:1020
Inline: False
```
**Symbols:**

```
ffffffff81222f00-ffffffff81222f3b: pagevec_lookup_range_nr_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range_nr_tag(struct pagevec *pvec, struct address_space *mapping, long unsigned int *index, long unsigned int end, xa_mark_t tag, unsigned int max_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff812309b0)
Location: mm/swap.c:1060
Inline: False
```
**Symbols:**

```
ffffffff812309b0-ffffffff812309eb: pagevec_lookup_range_nr_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range_nr_tag(struct pagevec *pvec, struct address_space *mapping, long unsigned int *index, long unsigned int end, xa_mark_t tag, unsigned int max_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8125db80)
Location: mm/swap.c:1126
Inline: False
```
**Symbols:**

```
ffffffff8125db80-ffffffff8125dbbe: pagevec_lookup_range_nr_tag (STB_GLOBAL)
```
</details>
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
unsigned int pagevec_lookup_range_nr_tag(struct pagevec *pvec, struct address_space *mapping, long unsigned int *index, long unsigned int end, xa_mark_t tag, unsigned int max_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffff8000102c0148)
Location: mm/swap.c:1060
Inline: False
```
**Symbols:**

```
ffff8000102c0148-ffff8000102c01bc: pagevec_lookup_range_nr_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range_nr_tag(struct pagevec *pvec, struct address_space *mapping, long unsigned int *index, long unsigned int end, xa_mark_t tag, unsigned int max_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (c04ebc94)
Location: mm/swap.c:1060
Inline: False
```
**Symbols:**

```
c04ebc94-c04ebcec: pagevec_lookup_range_nr_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range_nr_tag(struct pagevec *pvec, struct address_space *mapping, long unsigned int *index, long unsigned int end, xa_mark_t tag, unsigned int max_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (c0000000003796f0)
Location: mm/swap.c:1060
Inline: False
```
**Symbols:**

```
c0000000003796f0-c000000000379760: pagevec_lookup_range_nr_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range_nr_tag(struct pagevec *pvec, struct address_space *mapping, long unsigned int *index, long unsigned int end, xa_mark_t tag, unsigned int max_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffe0001e2178)
Location: mm/swap.c:1060
Inline: False
```
**Symbols:**

```
ffffffe0001e2178-ffffffe0001e21e0: pagevec_lookup_range_nr_tag (STB_GLOBAL)
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
unsigned int pagevec_lookup_range_nr_tag(struct pagevec *pvec, struct address_space *mapping, long unsigned int *index, long unsigned int end, xa_mark_t tag, unsigned int max_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81229000)
Location: mm/swap.c:1060
Inline: False
```
**Symbols:**

```
ffffffff81229000-ffffffff8122903b: pagevec_lookup_range_nr_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range_nr_tag(struct pagevec *pvec, struct address_space *mapping, long unsigned int *index, long unsigned int end, xa_mark_t tag, unsigned int max_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8121c140)
Location: mm/swap.c:1060
Inline: False
```
**Symbols:**

```
ffffffff8121c140-ffffffff8121c17b: pagevec_lookup_range_nr_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range_nr_tag(struct pagevec *pvec, struct address_space *mapping, long unsigned int *index, long unsigned int end, xa_mark_t tag, unsigned int max_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81226da0)
Location: mm/swap.c:1060
Inline: False
```
**Symbols:**

```
ffffffff81226da0-ffffffff81226ddb: pagevec_lookup_range_nr_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int pagevec_lookup_range_nr_tag(struct pagevec *pvec, struct address_space *mapping, long unsigned int *index, long unsigned int end, xa_mark_t tag, unsigned int max_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff812360d0)
Location: mm/swap.c:1060
Inline: False
```
**Symbols:**

```
ffffffff812360d0-ffffffff8123610b: pagevec_lookup_range_nr_tag (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int tag</code> ➡️ <code>xa_mark_t tag</code>
</li>
</ul>
</details>
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
