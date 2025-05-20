# Function: <code>rmqueue_pcplist</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811c1ce3)
Location: mm/page_alloc.c:2787
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
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
In mm/page_alloc.c (ffffffff811d625e)
Location: mm/page_alloc.c:2845
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
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
In mm/page_alloc.c (ffffffff811f7662)
Location: mm/page_alloc.c:2949
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
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
In mm/page_alloc.c (ffffffff81209ad8)
Location: mm/page_alloc.c:3049
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
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
In mm/page_alloc.c (ffffffff8126f101)
Location: mm/page_alloc.c:3225
Inline: True
Inline callers:
  - mm/page_alloc.c:rmqueue
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
In mm/page_alloc.c (ffffffff8127df41)
Location: mm/page_alloc.c:3216
Inline: True
Inline callers:
  - mm/page_alloc.c:rmqueue
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
In mm/page_alloc.c (ffffffff812b06f0)
Location: mm/page_alloc.c:3327
Inline: True
Direct callers:
  - mm/page_alloc.c:rmqueue
```
**Symbols:**

```
ffffffff812b06f0-ffffffff812b083d: rmqueue_pcplist.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (ffffffff812bc330)
Location: mm/page_alloc.c:3429
Inline: True
Direct callers:
  - mm/page_alloc.c:rmqueue
```
**Symbols:**

```
ffffffff812bc330-ffffffff812bc47d: rmqueue_pcplist.constprop.0 (STB_LOCAL)
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
In mm/page_alloc.c (ffffffff812c12ae)
Location: mm/page_alloc.c:3479
Inline: True
Inline callers:
  - mm/page_alloc.c:rmqueue
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
In mm/page_alloc.c (ffffffff813049e8)
Location: mm/page_alloc.c:3642
Inline: True
Inline callers:
  - mm/page_alloc.c:rmqueue
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
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:3678
Inline: True
Direct callers:
  - mm/page_alloc.c:rmqueue
```
**Symbols:**

```
ffffffff8136c770-ffffffff8136c952: rmqueue_pcplist.constprop.0 (STB_LOCAL)
ffffffff81e6f5fe-ffffffff81e6f67d: rmqueue_pcplist.constprop.0.cold (STB_LOCAL)
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
In mm/page_alloc.c (ffffffff813e8df0)
Location: mm/page_alloc.c:3771
Inline: True
Inline callers:
  - mm/page_alloc.c:rmqueue
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
In mm/page_alloc.c (ffffffff8141e478)
Location: mm/page_alloc.c:2760
Inline: True
Inline callers:
  - mm/page_alloc.c:rmqueue
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
In mm/page_alloc.c (ffffffff8144b068)
Location: mm/page_alloc.c:2838
Inline: True
Inline callers:
  - mm/page_alloc.c:rmqueue
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
In mm/page_alloc.c (ffff800010315980)
Location: mm/page_alloc.c:3216
Inline: True
Inline callers:
  - mm/page_alloc.c:rmqueue
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
In mm/page_alloc.c (c0530780)
Location: mm/page_alloc.c:3216
Inline: True
Inline callers:
  - mm/page_alloc.c:rmqueue
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
In mm/page_alloc.c (c0000000003e79ac)
Location: mm/page_alloc.c:3216
Inline: True
Inline callers:
  - mm/page_alloc.c:rmqueue
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
In mm/page_alloc.c (ffffffe00021c6ee)
Location: mm/page_alloc.c:3216
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
In mm/page_alloc.c (ffffffff81276591)
Location: mm/page_alloc.c:3216
Inline: True
Inline callers:
  - mm/page_alloc.c:rmqueue
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
In mm/page_alloc.c (ffffffff812684e0)
Location: mm/page_alloc.c:3216
Inline: True
Inline callers:
  - mm/page_alloc.c:rmqueue
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
In mm/page_alloc.c (ffffffff81274331)
Location: mm/page_alloc.c:3216
Inline: True
Inline callers:
  - mm/page_alloc.c:rmqueue
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
In mm/page_alloc.c (ffffffff81284400)
Location: mm/page_alloc.c:3216
Inline: True
Inline callers:
  - mm/page_alloc.c:rmqueue
```
</details>
</li>
</ul>

## Differences
