# Function: <code>__drain_swap_slots_cache</code>

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
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swap_slots.c (ffffffff811ec6d0)
Location: mm/swap_slots.c:196
Inline: True
Direct callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:disable_swap_slots_cache_lock
```
**Symbols:**

```
ffffffff811ec6d0-ffffffff811ec716: __drain_swap_slots_cache.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swap_slots.c (ffffffff81202a50)
Location: mm/swap_slots.c:204
Inline: True
Direct callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:disable_swap_slots_cache_lock
```
**Symbols:**

```
ffffffff81202a50-ffffffff81202a8c: __drain_swap_slots_cache.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swap_slots.c (ffffffff8124e9b0)
Location: mm/swap_slots.c:202
Inline: True
Direct callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:disable_swap_slots_cache_lock
```
**Symbols:**

```
ffffffff8124e9b0-ffffffff8124e9ec: __drain_swap_slots_cache.constprop.1 (STB_LOCAL)
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
In mm/swap_slots.c (ffffffff81262e90)
Location: mm/swap_slots.c:202
Inline: True
Direct callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:disable_swap_slots_cache_lock
```
**Symbols:**

```
ffffffff81262e90-ffffffff81262ecc: __drain_swap_slots_cache.constprop.1 (STB_LOCAL)
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
In mm/swap_slots.c (ffffffff8127de00)
Location: mm/swap_slots.c:202
Inline: True
Direct callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:disable_swap_slots_cache_lock
```
**Symbols:**

```
ffffffff8127de00-ffffffff8127de3b: __drain_swap_slots_cache.constprop.0 (STB_LOCAL)
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
In mm/swap_slots.c (ffffffff8128d850)
Location: mm/swap_slots.c:202
Inline: True
Direct callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:disable_swap_slots_cache_lock
```
**Symbols:**

```
ffffffff8128d850-ffffffff8128d88b: __drain_swap_slots_cache.constprop.0 (STB_LOCAL)
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
In mm/swap_slots.c (ffffffff812c0777)
Location: mm/swap_slots.c:202
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:disable_swap_slots_cache_lock
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
In mm/swap_slots.c (ffffffff812cc161)
Location: mm/swap_slots.c:201
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:disable_swap_slots_cache_lock
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
In mm/swap_slots.c (ffffffff812d2d11)
Location: mm/swap_slots.c:200
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:disable_swap_slots_cache_lock
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
In mm/swap_slots.c (ffffffff81318744)
Location: mm/swap_slots.c:198
Inline: True
Inline callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:disable_swap_slots_cache_lock
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
In mm/swap_slots.c (ffffffff81383e05)
Location: mm/swap_slots.c:199
Inline: True
Inline callers:
  - mm/swap_slots.c:folio_alloc_swap
  - mm/swap_slots.c:disable_swap_slots_cache_lock
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swap_slots.c (ffffffff814013a0)
Location: mm/swap_slots.c:199
Inline: True
Direct callers:
  - mm/swap_slots.c:folio_alloc_swap
  - mm/swap_slots.c:disable_swap_slots_cache_lock
```
**Symbols:**

```
ffffffff814013a0-ffffffff814013e9: __drain_swap_slots_cache.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swap_slots.c (ffffffff81434280)
Location: mm/swap_slots.c:199
Inline: True
Direct callers:
  - mm/swap_slots.c:folio_alloc_swap
  - mm/swap_slots.c:disable_swap_slots_cache_lock
```
**Symbols:**

```
ffffffff81434280-ffffffff814342c9: __drain_swap_slots_cache.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/swap_slots.c (ffffffff8146d680)
Location: mm/swap_slots.c:199
Inline: True
Direct callers:
  - mm/swap_slots.c:folio_alloc_swap
  - mm/swap_slots.c:disable_swap_slots_cache_lock
```
**Symbols:**

```
ffffffff8146d680-ffffffff8146d6c9: __drain_swap_slots_cache.constprop.0 (STB_LOCAL)
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
In mm/swap_slots.c (ffff800010329a50)
Location: mm/swap_slots.c:202
Inline: True
Direct callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:disable_swap_slots_cache_lock
```
**Symbols:**

```
ffff800010329a50-ffff800010329ab4: __drain_swap_slots_cache.constprop.0 (STB_LOCAL)
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
In mm/swap_slots.c (c0540350)
Location: mm/swap_slots.c:202
Inline: True
Direct callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:disable_swap_slots_cache_lock
```
**Symbols:**

```
c0540350-c05403a0: __drain_swap_slots_cache.constprop.0 (STB_LOCAL)
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
In mm/swap_slots.c (c000000000400570)
Location: mm/swap_slots.c:202
Inline: True
Direct callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:disable_swap_slots_cache_lock
```
**Symbols:**

```
c000000000400570-c000000000400604: __drain_swap_slots_cache.constprop.0 (STB_LOCAL)
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
In mm/swap_slots.c (ffffffe000228dae)
Location: mm/swap_slots.c:202
Inline: True
Direct callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:disable_swap_slots_cache_lock
```
**Symbols:**

```
ffffffe000228dae-ffffffe000228e0c: __drain_swap_slots_cache.constprop.0 (STB_LOCAL)
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
In mm/swap_slots.c (ffffffff81285e30)
Location: mm/swap_slots.c:202
Inline: True
Direct callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:disable_swap_slots_cache_lock
```
**Symbols:**

```
ffffffff81285e30-ffffffff81285e6b: __drain_swap_slots_cache.constprop.0 (STB_LOCAL)
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
In mm/swap_slots.c (ffffffff81277ca0)
Location: mm/swap_slots.c:202
Inline: True
Direct callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:disable_swap_slots_cache_lock
```
**Symbols:**

```
ffffffff81277ca0-ffffffff81277cdb: __drain_swap_slots_cache.constprop.0 (STB_LOCAL)
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
In mm/swap_slots.c (ffffffff81283c40)
Location: mm/swap_slots.c:202
Inline: True
Direct callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:disable_swap_slots_cache_lock
```
**Symbols:**

```
ffffffff81283c40-ffffffff81283c7b: __drain_swap_slots_cache.constprop.0 (STB_LOCAL)
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
In mm/swap_slots.c (ffffffff81293930)
Location: mm/swap_slots.c:202
Inline: True
Direct callers:
  - mm/swap_slots.c:get_swap_page
  - mm/swap_slots.c:disable_swap_slots_cache_lock
```
**Symbols:**

```
ffffffff81293930-ffffffff8129396b: __drain_swap_slots_cache.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
