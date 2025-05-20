# Function: <code>__cmpxchg_double_slab</code>

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
In mm/slub.c (ffffffff811e9e20)
Location: mm/slub.c:365
Inline: True
Direct callers:
  - mm/slub.c:deactivate_slab
  - mm/slub.c:deactivate_slab
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff811e9e20-ffffffff811e9ed4: __cmpxchg_double_slab.isra.44 (STB_LOCAL)
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
In mm/slub.c (ffffffff81209480)
Location: mm/slub.c:342
Inline: True
Direct callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:deactivate_slab
  - mm/slub.c:deactivate_slab
```
**Symbols:**

```
ffffffff81209480-ffffffff81209527: __cmpxchg_double_slab.isra.47 (STB_LOCAL)
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
In mm/slub.c (ffffffff8121b4f0)
Location: mm/slub.c:338
Inline: True
Direct callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:deactivate_slab
  - mm/slub.c:deactivate_slab
```
**Symbols:**

```
ffffffff8121b4f0-ffffffff8121b597: __cmpxchg_double_slab.isra.49 (STB_LOCAL)
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
In mm/slub.c (ffffffff81226f20)
Location: mm/slub.c:340
Inline: True
Direct callers:
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff81226f20-ffffffff81226fd7: __cmpxchg_double_slab.isra.50 (STB_LOCAL)
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
In mm/slub.c (ffffffff81241f50)
Location: mm/slub.c:375
Inline: True
Direct callers:
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff81241f50-ffffffff81242007: __cmpxchg_double_slab.isra.51 (STB_LOCAL)
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
In mm/slub.c (ffffffff812662a4)
Location: mm/slub.c:360
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
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
In mm/slub.c (ffffffff8127afe4)
Location: mm/slub.c:364
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
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
In mm/slub.c (ffffffff81296958)
Location: mm/slub.c:365
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
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
In mm/slub.c (ffffffff812a65ff)
Location: mm/slub.c:365
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
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
In mm/slub.c (ffffffff812db59d)
Location: mm/slub.c:363
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:unfreeze_partials
  - mm/slub.c:deactivate_slab
  - mm/slub.c:deactivate_slab
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
In mm/slub.c (ffffffff812e7adf)
Location: mm/slub.c:359
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:unfreeze_partials
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
In mm/slub.c (ffffffff812ef277)
Location: mm/slub.c:370
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:unfreeze_partials
  - mm/slub.c:deactivate_slab
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
In mm/slub.c (ffffffff81337577)
Location: mm/slub.c:451
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:__unfreeze_partials
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
In mm/slub.c (ffffffff813a8e67)
Location: mm/slub.c:480
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:__unfreeze_partials
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
In mm/slub.c (ffffffff81429f67)
Location: mm/slub.c:522
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:__unfreeze_partials
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
In mm/slub.c (ffff800010347890)
Location: mm/slub.c:365
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
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
In mm/slub.c (c054b9d8)
Location: mm/slub.c:365
Inline: True
Inline callers:
  - mm/slub.c:unfreeze_partials
  - mm/slub.c:unfreeze_partials
  - mm/slub.c:deactivate_slab
  - mm/slub.c:deactivate_slab
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
In mm/slub.c (c000000000425b34)
Location: mm/slub.c:365
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
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
In mm/slub.c (ffffffe000239660)
Location: mm/slub.c:365
Inline: True
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
In mm/slub.c (ffffffff8129ebdf)
Location: mm/slub.c:365
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
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
In mm/slub.c (ffffffff8129071f)
Location: mm/slub.c:365
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
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
In mm/slub.c (ffffffff8129c9ef)
Location: mm/slub.c:365
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
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
In mm/slub.c (ffffffff812aca22)
Location: mm/slub.c:365
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
</details>
</li>
</ul>

## Differences
