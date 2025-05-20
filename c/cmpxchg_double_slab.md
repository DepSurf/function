# Function: <code>cmpxchg_double_slab</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff811eb7d0)
Location: mm/slub.c:402
Inline: True
Direct callers:
  - mm/slub.c:__slab_free
```
**Symbols:**

```
ffffffff811eb7d0-ffffffff811eb8aa: cmpxchg_double_slab.isra.54 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff8120a9f0)
Location: mm/slub.c:379
Inline: True
Direct callers:
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
```
**Symbols:**

```
ffffffff8120a9f0-ffffffff8120aabb: cmpxchg_double_slab.isra.60 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff8121ca40)
Location: mm/slub.c:375
Inline: True
Direct callers:
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
```
**Symbols:**

```
ffffffff8121ca40-ffffffff8121cb0b: cmpxchg_double_slab.isra.62 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff81228620)
Location: mm/slub.c:377
Inline: True
Direct callers:
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
```
**Symbols:**

```
ffffffff81228620-ffffffff81228702: cmpxchg_double_slab.isra.61 (STB_LOCAL)
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
In mm/slub.c (ffffffff812424c0)
Location: mm/slub.c:412
Inline: True
Direct callers:
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
```
**Symbols:**

```
ffffffff812424c0-ffffffff812425a2: cmpxchg_double_slab.isra.61 (STB_LOCAL)
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
In mm/slub.c (ffffffff81267bfb)
Location: mm/slub.c:397
Inline: True
Inline callers:
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
In mm/slub.c (ffffffff8127cab3)
Location: mm/slub.c:401
Inline: True
Inline callers:
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
In mm/slub.c (ffffffff81298673)
Location: mm/slub.c:402
Inline: True
Inline callers:
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
In mm/slub.c (ffffffff812a84d3)
Location: mm/slub.c:402
Inline: True
Inline callers:
  - mm/slub.c:__slab_free
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
In mm/slub.c (ffffffff812dd869)
Location: mm/slub.c:400
Inline: True
Inline callers:
  - mm/slub.c:__slab_free
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
In mm/slub.c (ffffffff812e65e5)
Location: mm/slub.c:396
Inline: True
Inline callers:
  - mm/slub.c:__slab_free
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
In mm/slub.c (ffffffff812edd88)
Location: mm/slub.c:407
Inline: True
Inline callers:
  - mm/slub.c:__slab_free
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
In mm/slub.c (ffffffff81336173)
Location: mm/slub.c:492
Inline: True
Inline callers:
  - mm/slub.c:__slab_free
  - mm/slub.c:deactivate_slab
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slub.c (ffffffff813a69c0)
Location: mm/slub.c:521
Inline: True
Direct callers:
  - mm/slub.c:__slab_free
  - mm/slub.c:deactivate_slab
  - mm/slub.c:deactivate_slab
```
**Symbols:**

```
ffffffff813a69c0-ffffffff813a6aac: cmpxchg_double_slab.constprop.0.isra.0 (STB_LOCAL)
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
In mm/slub.c (ffffffff81425570)
Location: mm/slub.c:560
Inline: True
Direct callers:
  - mm/slub.c:__slab_free
  - mm/slub.c:deactivate_slab
  - mm/slub.c:deactivate_slab
```
**Symbols:**

```
ffffffff81425570-ffffffff81425662: cmpxchg_double_slab.constprop.0.isra.0 (STB_LOCAL)
```
</details>
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffff800010349db0)
Location: mm/slub.c:402
Inline: True
Inline callers:
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
In mm/slub.c (c054de24)
Location: mm/slub.c:402
Inline: True
Inline callers:
  - mm/slub.c:__slab_free
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
In mm/slub.c (c000000000428b90)
Location: mm/slub.c:402
Inline: True
Inline callers:
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
In mm/slub.c (ffffffe00023b7fc)
Location: mm/slub.c:402
Inline: True
Inline callers:
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
In mm/slub.c (ffffffff812a0ab3)
Location: mm/slub.c:402
Inline: True
Inline callers:
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
In mm/slub.c (ffffffff812925bf)
Location: mm/slub.c:402
Inline: True
Inline callers:
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
In mm/slub.c (ffffffff8129e8c3)
Location: mm/slub.c:402
Inline: True
Inline callers:
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
In mm/slub.c (ffffffff812ae953)
Location: mm/slub.c:402
Inline: True
Inline callers:
  - mm/slub.c:__slab_free
```
</details>
</li>
</ul>

## Differences
