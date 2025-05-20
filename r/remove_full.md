# Function: <code>remove_full</code>

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
In mm/slub.c (ffffffff811ea190)
Location: mm/slub.c:976
Inline: True
Inline callers:
  - mm/slub.c:deactivate_slab
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
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
In mm/slub.c (ffffffff8120ad10)
Location: mm/slub.c:1000
Inline: True
Inline callers:
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:deactivate_slab
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
In mm/slub.c (ffffffff8121cd60)
Location: mm/slub.c:999
Inline: True
Inline callers:
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:deactivate_slab
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
In mm/slub.c (ffffffff8122889f)
Location: mm/slub.c:1001
Inline: True
Inline callers:
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
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
In mm/slub.c (ffffffff812427e0)
Location: mm/slub.c:1036
Inline: True
Inline callers:
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
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
In mm/slub.c (ffffffff81267d9f)
Location: mm/slub.c:1024
Inline: True
Inline callers:
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
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
In mm/slub.c (ffffffff8127cc5f)
Location: mm/slub.c:1029
Inline: True
Inline callers:
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
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
In mm/slub.c (ffffffff81298806)
Location: mm/slub.c:1021
Inline: True
Inline callers:
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
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
In mm/slub.c (ffffffff812a8666)
Location: mm/slub.c:1021
Inline: True
Inline callers:
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff812dda02)
Location: mm/slub.c:1066
Inline: True
Inline callers:
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:deactivate_slab
  - mm/slub.c:deactivate_slab
Direct callers:
  - mm/slub.c:__slab_free
```
**Symbols:**

```
ffffffff812d7de0-ffffffff812d7e10: remove_full.part.0 (STB_LOCAL)
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
In mm/slub.c (ffffffff812e67a5)
Location: mm/slub.c:1061
Inline: True
Inline callers:
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:deactivate_slab
  - mm/slub.c:deactivate_slab
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
In mm/slub.c (ffffffff812edf63)
Location: mm/slub.c:1073
Inline: True
Inline callers:
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:deactivate_slab
  - mm/slub.c:deactivate_slab
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff8133635c)
Location: mm/slub.c:1197
Inline: True
Inline callers:
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:deactivate_slab
  - mm/slub.c:deactivate_slab
Direct callers:
  - mm/slub.c:__slab_free
```
**Symbols:**

```
ffffffff81333070-ffffffff813330a0: remove_full.part.0 (STB_LOCAL)
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
In mm/slub.c (ffffffff813a7bbd)
Location: mm/slub.c:1243
Inline: True
Inline callers:
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
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
In mm/slub.c (ffffffff8142bdb9)
Location: mm/slub.c:1338
Inline: True
Inline callers:
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:free_to_partial_list
  - mm/slub.c:free_to_partial_list
Direct callers:
  - mm/slub.c:__slab_free
```
**Symbols:**

```
ffffffff814248d0-ffffffff8142490a: remove_full.part.0 (STB_LOCAL)
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
In mm/slub.c (ffffffff8146133d)
Location: mm/slub.c:1359
Inline: True
Inline callers:
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:free_to_partial_list
  - mm/slub.c:free_to_partial_list
Direct callers:
  - mm/slub.c:__slab_free
```
**Symbols:**

```
ffffffff81459b70-ffffffff81459baa: remove_full.part.0 (STB_LOCAL)
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
In mm/slub.c (ffffffff81459309)
Location: mm/slub.c:1483
Inline: True
Inline callers:
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:free_to_partial_list
  - mm/slub.c:free_to_partial_list
Direct callers:
  - mm/slub.c:__slab_free
```
**Symbols:**

```
ffffffff81454af0-ffffffff81454b2a: remove_full.part.0 (STB_LOCAL)
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
In mm/slub.c (ffff80001034a040)
Location: mm/slub.c:1021
Inline: True
Inline callers:
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
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
In mm/slub.c (c054e054)
Location: mm/slub.c:1021
Inline: True
Inline callers:
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:deactivate_slab
  - mm/slub.c:deactivate_slab
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
In mm/slub.c (c000000000428edc)
Location: mm/slub.c:1021
Inline: True
Inline callers:
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
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
In mm/slub.c (ffffffe00023b9d8)
Location: mm/slub.c:1021
Inline: True
Inline callers:
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
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
In mm/slub.c (ffffffff812a0c46)
Location: mm/slub.c:1021
Inline: True
Inline callers:
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
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
In mm/slub.c (ffffffff8129272d)
Location: mm/slub.c:1021
Inline: True
Inline callers:
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
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
In mm/slub.c (ffffffff8129ea56)
Location: mm/slub.c:1021
Inline: True
Inline callers:
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
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
In mm/slub.c (ffffffff812aeb39)
Location: mm/slub.c:1021
Inline: True
Inline callers:
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
```
</details>
</li>
</ul>

## Differences
