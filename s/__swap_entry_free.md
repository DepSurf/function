# Function: <code>__swap_entry_free</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned char __swap_entry_free(struct swap_info_struct *p, swp_entry_t entry, unsigned char usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8120d600)
Location: mm/swapfile.c:1075
Inline: False
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:swap_free
```
**Symbols:**

```
ffffffff8120d600-ffffffff8120d702: __swap_entry_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned char __swap_entry_free(struct swap_info_struct *p, swp_entry_t entry, unsigned char usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812275c0)
Location: mm/swapfile.c:1110
Inline: False
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:swap_free
```
**Symbols:**

```
ffffffff812275c0-ffffffff812276cb: __swap_entry_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned char __swap_entry_free(struct swap_info_struct *p, swp_entry_t entry, unsigned char usage);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81249b20)
Location: mm/swapfile.c:1110
Inline: False
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:put_swap_page
  - mm/swapfile.c:swap_free
```
**Symbols:**

```
ffffffff81249b20-ffffffff81249c2b: __swap_entry_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (ffffffff8125e1f0)
Location: mm/swapfile.c:1177
Inline: True
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:swap_free
```
**Symbols:**

```
ffffffff8125e1f0-ffffffff8125e283: __swap_entry_free.constprop.48 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (ffffffff81279320)
Location: mm/swapfile.c:1277
Inline: True
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:swap_free
```
**Symbols:**

```
ffffffff81279320-ffffffff812793bb: __swap_entry_free.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (ffffffff81288e00)
Location: mm/swapfile.c:1277
Inline: True
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:swap_free
```
**Symbols:**

```
ffffffff81288e00-ffffffff81288e9b: __swap_entry_free.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned char __swap_entry_free(struct swap_info_struct *p, swp_entry_t entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812bba90)
Location: mm/swapfile.c:1313
Inline: False
Direct callers:
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:free_swap_and_cache
```
**Symbols:**

```
ffffffff812bba90-ffffffff812bbb2b: __swap_entry_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned char __swap_entry_free(struct swap_info_struct *p, swp_entry_t entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812c7540)
Location: mm/swapfile.c:1331
Inline: False
Direct callers:
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:free_swap_and_cache
```
**Symbols:**

```
ffffffff812c7540-ffffffff812c75db: __swap_entry_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned char __swap_entry_free(struct swap_info_struct *p, swp_entry_t entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812cde80)
Location: mm/swapfile.c:1330
Inline: False
Direct callers:
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:free_swap_and_cache
```
**Symbols:**

```
ffffffff812cde80-ffffffff812cdf1b: __swap_entry_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned char __swap_entry_free(struct swap_info_struct *p, swp_entry_t entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81313300)
Location: mm/swapfile.c:1299
Inline: False
Direct callers:
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:free_swap_and_cache
```
**Symbols:**

```
ffffffff81313300-ffffffff8131339b: __swap_entry_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned char __swap_entry_free(struct swap_info_struct *p, swp_entry_t entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8137e690)
Location: mm/swapfile.c:1282
Inline: False
Direct callers:
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:free_swap_and_cache
```
**Symbols:**

```
ffffffff8137e690-ffffffff8137e735: __swap_entry_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned char __swap_entry_free(struct swap_info_struct *p, swp_entry_t entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff813fc2c0)
Location: mm/swapfile.c:1286
Inline: False
Direct callers:
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:free_swap_and_cache
```
**Symbols:**

```
ffffffff813fc2c0-ffffffff813fc365: __swap_entry_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned char __swap_entry_free(struct swap_info_struct *p, swp_entry_t entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8142f3d0)
Location: mm/swapfile.c:1292
Inline: False
Direct callers:
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:free_swap_and_cache
```
**Symbols:**

```
ffffffff8142f3d0-ffffffff8142f475: __swap_entry_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned char __swap_entry_free(struct swap_info_struct *p, swp_entry_t entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff814687a0)
Location: mm/swapfile.c:1292
Inline: False
Direct callers:
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:free_swap_and_cache
```
**Symbols:**

```
ffffffff814687a0-ffffffff81468845: __swap_entry_free (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (ffff800010323d88)
Location: mm/swapfile.c:1277
Inline: True
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:swap_free
```
**Symbols:**

```
ffff800010323d88-ffff800010323f48: __swap_entry_free.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (c053bc40)
Location: mm/swapfile.c:1277
Inline: True
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:swap_free
```
**Symbols:**

```
c053bc40-c053bd5c: __swap_entry_free.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (c0000000003f9ac0)
Location: mm/swapfile.c:1277
Inline: True
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:swap_free
```
**Symbols:**

```
c0000000003f9ac0-c0000000003f9cdc: __swap_entry_free.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (ffffffe0002245c0)
Location: mm/swapfile.c:1277
Inline: True
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:swap_free
```
**Symbols:**

```
ffffffe0002245c0-ffffffe00022470c: __swap_entry_free.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (ffffffff812813e0)
Location: mm/swapfile.c:1277
Inline: True
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:swap_free
```
**Symbols:**

```
ffffffff812813e0-ffffffff8128147b: __swap_entry_free.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (ffffffff81273250)
Location: mm/swapfile.c:1277
Inline: True
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:swap_free
```
**Symbols:**

```
ffffffff81273250-ffffffff812732eb: __swap_entry_free.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (ffffffff8127f1f0)
Location: mm/swapfile.c:1277
Inline: True
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:swap_free
```
**Symbols:**

```
ffffffff8127f1f0-ffffffff8127f28b: __swap_entry_free.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swapfile.c (ffffffff8128edc0)
Location: mm/swapfile.c:1277
Inline: True
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:swap_free
```
**Symbols:**

```
ffffffff8128edc0-ffffffff8128ee59: __swap_entry_free.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
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
