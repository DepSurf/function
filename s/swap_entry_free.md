# Function: <code>swap_entry_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
unsigned char swap_entry_free(struct swap_info_struct *p, swp_entry_t entry, unsigned char usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff811d3cc0)
Location: mm/swapfile.c:767
Inline: False
Direct callers:
  - mm/swapfile.c:swap_free
  - mm/swapfile.c:swapcache_free
  - mm/swapfile.c:free_swap_and_cache
```
**Symbols:**

```
ffffffff811d3cc0-ffffffff811d3fef: swap_entry_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned char swap_entry_free(struct swap_info_struct *p, swp_entry_t entry, unsigned char usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff811f1ae0)
Location: mm/swapfile.c:764
Inline: False
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:swapcache_free
  - mm/swapfile.c:swap_free
```
**Symbols:**

```
ffffffff811f1ae0-ffffffff811f1e19: swap_entry_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned char swap_entry_free(struct swap_info_struct *p, swp_entry_t entry, unsigned char usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812024d0)
Location: mm/swapfile.c:770
Inline: False
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:swapcache_free
  - mm/swapfile.c:swap_free
```
**Symbols:**

```
ffffffff812024d0-ffffffff81202809: swap_entry_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8120e26c)
Location: mm/swapfile.c:1117
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_free_entries
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812296fc)
Location: mm/swapfile.c:1152
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_free_entries
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8124a9cc)
Location: mm/swapfile.c:1152
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_free_entries
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8125f07c)
Location: mm/swapfile.c:1192
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_free_entries
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81279d2b)
Location: mm/swapfile.c:1292
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_free_entries
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8128980b)
Location: mm/swapfile.c:1292
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_free_entries
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812bc33b)
Location: mm/swapfile.c:1329
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_free_entries
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812c7e5b)
Location: mm/swapfile.c:1347
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_free_entries
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812ce8ef)
Location: mm/swapfile.c:1346
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_free_entries
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81313e7f)
Location: mm/swapfile.c:1315
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_free_entries
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8137f547)
Location: mm/swapfile.c:1298
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_free_entries
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff813fe087)
Location: mm/swapfile.c:1302
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_free_entries
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81431067)
Location: mm/swapfile.c:1308
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_free_entries
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8146a487)
Location: mm/swapfile.c:1308
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_free_entries
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffff8000103244a4)
Location: mm/swapfile.c:1292
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_free_entries
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (c053c158)
Location: mm/swapfile.c:1292
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_free_entries
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (c0000000003fa400)
Location: mm/swapfile.c:1292
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_free_entries
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffe000224bc8)
Location: mm/swapfile.c:1292
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_free_entries
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81281deb)
Location: mm/swapfile.c:1292
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_free_entries
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8127390b)
Location: mm/swapfile.c:1292
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_free_entries
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8127fbfb)
Location: mm/swapfile.c:1292
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_free_entries
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8128f8c9)
Location: mm/swapfile.c:1292
Inline: True
Inline callers:
  - mm/swapfile.c:swapcache_free_entries
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
</ul>
