# Function: <code>__dma_map_cont</code>

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
In arch/x86/kernel/amd_gart_64.c (ffffffff81066950)
Location: arch/x86/kernel/amd_gart_64.c:334
Inline: True
```
**Symbols:**

```
ffffffff81066950-ffffffff81066a7d: __dma_map_cont.isra.8 (STB_LOCAL)
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
In arch/x86/kernel/amd_gart_64.c (ffffffff810666e0)
Location: arch/x86/kernel/amd_gart_64.c:333
Inline: True
```
**Symbols:**

```
ffffffff810666e0-ffffffff8106680b: __dma_map_cont.isra.8 (STB_LOCAL)
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
In arch/x86/kernel/amd_gart_64.c (ffffffff8106a360)
Location: arch/x86/kernel/amd_gart_64.c:333
Inline: True
```
**Symbols:**

```
ffffffff8106a360-ffffffff8106a48b: __dma_map_cont.isra.8 (STB_LOCAL)
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
In arch/x86/kernel/amd_gart_64.c (ffffffff810696c0)
Location: arch/x86/kernel/amd_gart_64.c:334
Inline: True
```
**Symbols:**

```
ffffffff810696c0-ffffffff81069806: __dma_map_cont.isra.6 (STB_LOCAL)
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
In arch/x86/kernel/amd_gart_64.c (ffffffff8106df70)
Location: arch/x86/kernel/amd_gart_64.c:334
Inline: True
```
**Symbols:**

```
ffffffff8106df70-ffffffff8106e0b6: __dma_map_cont.isra.6 (STB_LOCAL)
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
In arch/x86/kernel/amd_gart_64.c (ffffffff81070e60)
Location: arch/x86/kernel/amd_gart_64.c:335
Inline: True
```
**Symbols:**

```
ffffffff81070e60-ffffffff81070fa5: __dma_map_cont.isra.6 (STB_LOCAL)
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
In arch/x86/kernel/amd_gart_64.c (ffffffff81076e60)
Location: arch/x86/kernel/amd_gart_64.c:328
Inline: True
```
**Symbols:**

```
ffffffff81076e60-ffffffff81076fa5: __dma_map_cont.isra.6 (STB_LOCAL)
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
In arch/x86/kernel/amd_gart_64.c (ffffffff8107a9f0)
Location: arch/x86/kernel/amd_gart_64.c:325
Inline: True
```
**Symbols:**

```
ffffffff8107a9f0-ffffffff8107ab30: __dma_map_cont.isra.0 (STB_LOCAL)
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
In arch/x86/kernel/amd_gart_64.c (ffffffff8107bae0)
Location: arch/x86/kernel/amd_gart_64.c:325
Inline: True
```
**Symbols:**

```
ffffffff8107bae0-ffffffff8107bc20: __dma_map_cont.isra.0 (STB_LOCAL)
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
In arch/x86/kernel/amd_gart_64.c (ffffffff81082f20)
Location: arch/x86/kernel/amd_gart_64.c:324
Inline: True
```
**Symbols:**

```
ffffffff81082f20-ffffffff81083054: __dma_map_cont.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __dma_map_cont(struct device *dev, struct scatterlist *start, int nelems, struct scatterlist *sout, long unsigned int pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81084480)
Location: arch/x86/kernel/amd_gart_64.c:324
Inline: False
```
**Symbols:**

```
ffffffff81084480-ffffffff810845b4: __dma_map_cont (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __dma_map_cont(struct device *dev, struct scatterlist *start, int nelems, struct scatterlist *sout, long unsigned int pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff810851e0)
Location: arch/x86/kernel/amd_gart_64.c:324
Inline: False
```
**Symbols:**

```
ffffffff810851e0-ffffffff81085314: __dma_map_cont (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __dma_map_cont(struct device *dev, struct scatterlist *start, int nelems, struct scatterlist *sout, long unsigned int pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81094690)
Location: arch/x86/kernel/amd_gart_64.c:324
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
```
**Symbols:**

```
ffffffff81094690-ffffffff810947c4: __dma_map_cont (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __dma_map_cont(struct device *dev, struct scatterlist *start, int nelems, struct scatterlist *sout, long unsigned int pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff810a6900)
Location: arch/x86/kernel/amd_gart_64.c:322
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
```
**Symbols:**

```
ffffffff810a6900-ffffffff810a6a4c: __dma_map_cont (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __dma_map_cont(struct device *dev, struct scatterlist *start, int nelems, struct scatterlist *sout, long unsigned int pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff810bfa20)
Location: arch/x86/kernel/amd_gart_64.c:322
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
```
**Symbols:**

```
ffffffff810bfa20-ffffffff810bfb6c: __dma_map_cont (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __dma_map_cont(struct device *dev, struct scatterlist *start, int nelems, struct scatterlist *sout, long unsigned int pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff810c3100)
Location: arch/x86/kernel/amd_gart_64.c:322
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
```
**Symbols:**

```
ffffffff810c3100-ffffffff810c324c: __dma_map_cont (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __dma_map_cont(struct device *dev, struct scatterlist *start, int nelems, struct scatterlist *sout, long unsigned int pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff810cb540)
Location: arch/x86/kernel/amd_gart_64.c:322
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
  - arch/x86/kernel/amd_gart_64.c:gart_map_sg
```
**Symbols:**

```
ffffffff810cb540-ffffffff810cb68c: __dma_map_cont (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In arch/x86/kernel/amd_gart_64.c (ffffffff8107aae0)
Location: arch/x86/kernel/amd_gart_64.c:325
Inline: True
```
**Symbols:**

```
ffffffff8107aae0-ffffffff8107ac20: __dma_map_cont.isra.0 (STB_LOCAL)
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
In arch/x86/kernel/amd_gart_64.c (ffffffff8106a210)
Location: arch/x86/kernel/amd_gart_64.c:325
Inline: True
```
**Symbols:**

```
ffffffff8106a210-ffffffff8106a350: __dma_map_cont.isra.0 (STB_LOCAL)
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
In arch/x86/kernel/amd_gart_64.c (ffffffff8107aa90)
Location: arch/x86/kernel/amd_gart_64.c:325
Inline: True
```
**Symbols:**

```
ffffffff8107aa90-ffffffff8107abd0: __dma_map_cont.isra.0 (STB_LOCAL)
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
In arch/x86/kernel/amd_gart_64.c (ffffffff8107cb90)
Location: arch/x86/kernel/amd_gart_64.c:325
Inline: True
```
**Symbols:**

```
ffffffff8107cb90-ffffffff8107ccd0: __dma_map_cont.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
