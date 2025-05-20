# Function: <code>__try_to_reclaim_swap</code>

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
In mm/swapfile.c (ffffffff811d4aa4)
Location: mm/swapfile.c:102
Inline: True
Inline callers:
  - mm/swapfile.c:scan_swap_map
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
In mm/swapfile.c (ffffffff811f298b)
Location: mm/swapfile.c:102
Inline: True
Inline callers:
  - mm/swapfile.c:scan_swap_map
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
In mm/swapfile.c (ffffffff812033fb)
Location: mm/swapfile.c:102
Inline: True
Inline callers:
  - mm/swapfile.c:scan_swap_map
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
In mm/swapfile.c (ffffffff8120ec1b)
Location: mm/swapfile.c:106
Inline: True
Inline callers:
  - mm/swapfile.c:scan_swap_map_slots
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
In mm/swapfile.c (ffffffff8122a3aa)
Location: mm/swapfile.c:108
Inline: True
Inline callers:
  - mm/swapfile.c:scan_swap_map_slots
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
In mm/swapfile.c (ffffffff8124b636)
Location: mm/swapfile.c:108
Inline: True
Inline callers:
  - mm/swapfile.c:scan_swap_map_slots
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
In mm/swapfile.c (ffffffff8125f890)
Location: mm/swapfile.c:117
Inline: True
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:scan_swap_map_slots
```
**Symbols:**

```
ffffffff8125f890-ffffffff8125f9ca: __try_to_reclaim_swap.isra.44 (STB_LOCAL)
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
In mm/swapfile.c (ffffffff8127a560)
Location: mm/swapfile.c:127
Inline: True
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:scan_swap_map_slots
```
**Symbols:**

```
ffffffff8127a560-ffffffff8127a685: __try_to_reclaim_swap.isra.0 (STB_LOCAL)
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
In mm/swapfile.c (ffffffff8128a040)
Location: mm/swapfile.c:127
Inline: True
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:scan_swap_map_slots
```
**Symbols:**

```
ffffffff8128a040-ffffffff8128a165: __try_to_reclaim_swap.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __try_to_reclaim_swap(struct swap_info_struct *si, long unsigned int offset, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812bccb0)
Location: mm/swapfile.c:126
Inline: False
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:scan_swap_map_slots
```
**Symbols:**

```
ffffffff812bccb0-ffffffff812bcdd3: __try_to_reclaim_swap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __try_to_reclaim_swap(struct swap_info_struct *si, long unsigned int offset, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812c87e0)
Location: mm/swapfile.c:126
Inline: False
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:scan_swap_map_slots
```
**Symbols:**

```
ffffffff812c87e0-ffffffff812c88fc: __try_to_reclaim_swap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __try_to_reclaim_swap(struct swap_info_struct *si, long unsigned int offset, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812cf220)
Location: mm/swapfile.c:125
Inline: False
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:scan_swap_map_slots
```
**Symbols:**

```
ffffffff812cf220-ffffffff812cf33f: __try_to_reclaim_swap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __try_to_reclaim_swap(struct swap_info_struct *si, long unsigned int offset, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff813147c0)
Location: mm/swapfile.c:125
Inline: False
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:scan_swap_map_slots
```
**Symbols:**

```
ffffffff813147c0-ffffffff813148d8: __try_to_reclaim_swap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __try_to_reclaim_swap(struct swap_info_struct *si, long unsigned int offset, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8137fcf0)
Location: mm/swapfile.c:127
Inline: False
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:scan_swap_map_slots
```
**Symbols:**

```
ffffffff8137fcf0-ffffffff8137fe82: __try_to_reclaim_swap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __try_to_reclaim_swap(struct swap_info_struct *si, long unsigned int offset, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff813fe6e0)
Location: mm/swapfile.c:131
Inline: False
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:scan_swap_map_slots
```
**Symbols:**

```
ffffffff813fe6e0-ffffffff813fe7c8: __try_to_reclaim_swap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __try_to_reclaim_swap(struct swap_info_struct *si, long unsigned int offset, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81431610)
Location: mm/swapfile.c:132
Inline: False
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:scan_swap_map_slots
```
**Symbols:**

```
ffffffff81431610-ffffffff81431718: __try_to_reclaim_swap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __try_to_reclaim_swap(struct swap_info_struct *si, long unsigned int offset, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8146aa00)
Location: mm/swapfile.c:134
Inline: False
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:scan_swap_map_slots
```
**Symbols:**

```
ffffffff8146aa00-ffffffff8146ab05: __try_to_reclaim_swap (STB_LOCAL)
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
In mm/swapfile.c (ffff800010324ec8)
Location: mm/swapfile.c:127
Inline: True
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:scan_swap_map_slots
```
**Symbols:**

```
ffff800010324ec8-ffff800010325040: __try_to_reclaim_swap.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __try_to_reclaim_swap(struct swap_info_struct *si, long unsigned int offset, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (c053c91c)
Location: mm/swapfile.c:127
Inline: False
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:scan_swap_map_slots
```
**Symbols:**

```
c053c91c-c053ca94: __try_to_reclaim_swap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __try_to_reclaim_swap(struct swap_info_struct *si, long unsigned int offset, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (c0000000003fb0e0)
Location: mm/swapfile.c:127
Inline: False
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:scan_swap_map_slots
```
**Symbols:**

```
c0000000003fb0e0-c0000000003fb2d8: __try_to_reclaim_swap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __try_to_reclaim_swap(struct swap_info_struct *si, long unsigned int offset, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffe000225556)
Location: mm/swapfile.c:127
Inline: False
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:scan_swap_map_slots
```
**Symbols:**

```
ffffffe000225556-ffffffe000225676: __try_to_reclaim_swap (STB_LOCAL)
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
In mm/swapfile.c (ffffffff81282620)
Location: mm/swapfile.c:127
Inline: True
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:scan_swap_map_slots
```
**Symbols:**

```
ffffffff81282620-ffffffff81282745: __try_to_reclaim_swap.isra.0 (STB_LOCAL)
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
In mm/swapfile.c (ffffffff81274140)
Location: mm/swapfile.c:127
Inline: True
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:scan_swap_map_slots
```
**Symbols:**

```
ffffffff81274140-ffffffff81274265: __try_to_reclaim_swap.isra.0 (STB_LOCAL)
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
In mm/swapfile.c (ffffffff81280430)
Location: mm/swapfile.c:127
Inline: True
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:scan_swap_map_slots
```
**Symbols:**

```
ffffffff81280430-ffffffff81280555: __try_to_reclaim_swap.isra.0 (STB_LOCAL)
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
In mm/swapfile.c (ffffffff81290150)
Location: mm/swapfile.c:127
Inline: True
Direct callers:
  - mm/swapfile.c:free_swap_and_cache
  - mm/swapfile.c:scan_swap_map_slots
```
**Symbols:**

```
ffffffff81290150-ffffffff81290275: __try_to_reclaim_swap.isra.0 (STB_LOCAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
