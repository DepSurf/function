# Function: <code>purge_fragmented_blocks</code>

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
In mm/vmalloc.c (ffffffff811cce3e)
Location: mm/vmalloc.c:891
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
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
In mm/vmalloc.c (ffffffff811e9eb2)
Location: mm/vmalloc.c:915
Inline: True
Inline callers:
  - mm/vmalloc.c:__purge_vmap_area_lazy
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
In mm/vmalloc.c (ffffffff811fb451)
Location: mm/vmalloc.c:886
Inline: True
Inline callers:
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
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
In mm/vmalloc.c (ffffffff81206191)
Location: mm/vmalloc.c:937
Inline: True
Inline callers:
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
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
In mm/vmalloc.c (ffffffff8121eeb1)
Location: mm/vmalloc.c:935
Inline: True
Inline callers:
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
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
In mm/vmalloc.c (ffffffff812417bd)
Location: mm/vmalloc.c:918
Inline: True
Inline callers:
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
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
In mm/vmalloc.c (ffffffff81255ebd)
Location: mm/vmalloc.c:918
Inline: True
Inline callers:
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
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
In mm/vmalloc.c (ffffffff81269024)
Location: mm/vmalloc.c:1521
Inline: True
Inline callers:
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
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
In mm/vmalloc.c (ffffffff81277f54)
Location: mm/vmalloc.c:1529
Inline: True
Inline callers:
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void purge_fragmented_blocks(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812a8de0)
Location: mm/vmalloc.c:1630
Inline: False
Direct callers:
  - mm/vmalloc.c:purge_vmap_area_lazy
```
**Symbols:**

```
ffffffff812a8de0-ffffffff812a8f8e: purge_fragmented_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void purge_fragmented_blocks(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812b4220)
Location: mm/vmalloc.c:1619
Inline: False
Direct callers:
  - mm/vmalloc.c:purge_vmap_area_lazy
```
**Symbols:**

```
ffffffff812b4220-ffffffff812b43d3: purge_fragmented_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void purge_fragmented_blocks(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812b9900)
Location: mm/vmalloc.c:1889
Inline: False
Direct callers:
  - mm/vmalloc.c:purge_vmap_area_lazy
```
**Symbols:**

```
ffffffff812b9900-ffffffff812b9ab3: purge_fragmented_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void purge_fragmented_blocks(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812fbea0)
Location: mm/vmalloc.c:1941
Inline: False
Direct callers:
  - mm/vmalloc.c:purge_vmap_area_lazy
```
**Symbols:**

```
ffffffff812fbea0-ffffffff812fc074: purge_fragmented_blocks (STB_LOCAL)
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
In mm/vmalloc.c (ffffffff81360f79)
Location: mm/vmalloc.c:1960
Inline: True
Inline callers:
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
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
In mm/vmalloc.c (ffffffff813dc96b)
Location: mm/vmalloc.c:2022
Inline: True
Inline callers:
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
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
In mm/vmalloc.c (ffffffff814137bd)
Location: mm/vmalloc.c:2130
Inline: True
Inline callers:
  - mm/vmalloc.c:reclaim_and_purge_vmap_areas
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
In mm/vmalloc.c (ffffffff8144022d)
Location: mm/vmalloc.c:2130
Inline: True
Inline callers:
  - mm/vmalloc.c:reclaim_and_purge_vmap_areas
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
In mm/vmalloc.c (ffff80001030e5a8)
Location: mm/vmalloc.c:1529
Inline: True
Inline callers:
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
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
In mm/vmalloc.c (c0529f94)
Location: mm/vmalloc.c:1529
Inline: True
Inline callers:
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
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
In mm/vmalloc.c (c0000000003df3a0)
Location: mm/vmalloc.c:1529
Inline: True
Inline callers:
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
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
In mm/vmalloc.c (ffffffe000216f84)
Location: mm/vmalloc.c:1529
Inline: True
Inline callers:
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
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
In mm/vmalloc.c (ffffffff812705a4)
Location: mm/vmalloc.c:1529
Inline: True
Inline callers:
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
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
In mm/vmalloc.c (ffffffff81262514)
Location: mm/vmalloc.c:1529
Inline: True
Inline callers:
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
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
In mm/vmalloc.c (ffffffff8126e344)
Location: mm/vmalloc.c:1529
Inline: True
Inline callers:
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
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
In mm/vmalloc.c (ffffffff8127dd04)
Location: mm/vmalloc.c:1529
Inline: True
Inline callers:
  - mm/vmalloc.c:purge_fragmented_blocks_allcpus
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
</ul>
