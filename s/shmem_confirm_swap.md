# Function: <code>shmem_confirm_swap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811a940b)
Location: mm/shmem.c:284
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811c0fca)
Location: mm/shmem.c:329
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811d15c9)
Location: mm/shmem.c:326
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
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
In mm/shmem.c (ffffffff811d9e22)
Location: mm/shmem.c:342
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
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
In mm/shmem.c (ffffffff811efb07)
Location: mm/shmem.c:356
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
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
In mm/shmem.c (ffffffff812112f4)
Location: mm/shmem.c:356
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
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
In mm/shmem.c (ffffffff81223236)
Location: mm/shmem.c:358
Inline: True
Inline callers:
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
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
In mm/shmem.c (ffffffff81233228)
Location: mm/shmem.c:363
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool shmem_confirm_swap(struct address_space *mapping, long unsigned int index, swp_entry_t swap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8123d960)
Location: mm/shmem.c:378
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
```
**Symbols:**

```
ffffffff8123d960-ffffffff8123d999: shmem_confirm_swap (STB_LOCAL)
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
In mm/shmem.c (ffffffff8126dcf4)
Location: mm/shmem.c:377
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
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
In mm/shmem.c (ffffffff812799f2)
Location: mm/shmem.c:436
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
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
In mm/shmem.c (ffffffff8127eb54)
Location: mm/shmem.c:436
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
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
In mm/shmem.c (ffffffff812bc6d2)
Location: mm/shmem.c:433
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
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
In mm/shmem.c (ffffffff813186a1)
Location: mm/shmem.c:431
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_swapin_folio
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
In mm/shmem.c (ffffffff8138c5b1)
Location: mm/shmem.c:428
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_swapin_folio
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
In mm/shmem.c (ffffffff813bebde)
Location: mm/shmem.c:429
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_swapin_folio
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
In mm/shmem.c (ffffffff813e9c19)
Location: mm/shmem.c:495
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_swapin_folio
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
bool shmem_confirm_swap(struct address_space *mapping, long unsigned int index, swp_entry_t swap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffff8000102cf348)
Location: mm/shmem.c:378
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
```
**Symbols:**

```
ffff8000102cf348-ffff8000102cf3c0: shmem_confirm_swap (STB_LOCAL)
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
In mm/shmem.c (c04fbaec)
Location: mm/shmem.c:378
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
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
In mm/shmem.c (c00000000039295c)
Location: mm/shmem.c:378
Inline: True
Inline callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool shmem_confirm_swap(struct address_space *mapping, long unsigned int index, swp_entry_t swap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffe0001ecc92)
Location: mm/shmem.c:378
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
```
**Symbols:**

```
ffffffe0001ecc92-ffffffe0001ecce0: shmem_confirm_swap (STB_LOCAL)
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
bool shmem_confirm_swap(struct address_space *mapping, long unsigned int index, swp_entry_t swap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81235fb0)
Location: mm/shmem.c:378
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
```
**Symbols:**

```
ffffffff81235fb0-ffffffff81235fe9: shmem_confirm_swap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool shmem_confirm_swap(struct address_space *mapping, long unsigned int index, swp_entry_t swap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81229010)
Location: mm/shmem.c:378
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
```
**Symbols:**

```
ffffffff81229010-ffffffff81229049: shmem_confirm_swap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool shmem_confirm_swap(struct address_space *mapping, long unsigned int index, swp_entry_t swap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81233d50)
Location: mm/shmem.c:378
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
```
**Symbols:**

```
ffffffff81233d50-ffffffff81233d89: shmem_confirm_swap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool shmem_confirm_swap(struct address_space *mapping, long unsigned int index, swp_entry_t swap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81243320)
Location: mm/shmem.c:378
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
  - mm/shmem.c:shmem_swapin_page
```
**Symbols:**

```
ffffffff81243320-ffffffff81243359: shmem_confirm_swap (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
