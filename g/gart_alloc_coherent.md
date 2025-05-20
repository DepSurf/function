# Function: <code>gart_alloc_coherent</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *gart_alloc_coherent(struct device *dev, size_t size, dma_addr_t *dma_addr, gfp_t flag, struct dma_attrs *attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81066e60)
Location: arch/x86/kernel/amd_gart_64.c:479
Inline: True
```
**Symbols:**

```
ffffffff81066e60-ffffffff81066f31: gart_alloc_coherent.part.13 (STB_LOCAL)
ffffffff81066f40-ffffffff81066f66: gart_alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *gart_alloc_coherent(struct device *dev, size_t size, dma_addr_t *dma_addr, gfp_t flag, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81066c00)
Location: arch/x86/kernel/amd_gart_64.c:478
Inline: True
```
**Symbols:**

```
ffffffff81066c00-ffffffff81066cce: gart_alloc_coherent.part.13 (STB_LOCAL)
ffffffff81066cd0-ffffffff81066cf6: gart_alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *gart_alloc_coherent(struct device *dev, size_t size, dma_addr_t *dma_addr, gfp_t flag, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8106a840)
Location: arch/x86/kernel/amd_gart_64.c:478
Inline: True
```
**Symbols:**

```
ffffffff8106a840-ffffffff8106a916: gart_alloc_coherent.part.13 (STB_LOCAL)
ffffffff8106a920-ffffffff8106a946: gart_alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *gart_alloc_coherent(struct device *dev, size_t size, dma_addr_t *dma_addr, gfp_t flag, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81069b20)
Location: arch/x86/kernel/amd_gart_64.c:479
Inline: True
```
**Symbols:**

```
ffffffff81069b20-ffffffff81069bf6: gart_alloc_coherent.part.11 (STB_LOCAL)
ffffffff81069c00-ffffffff81069c26: gart_alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void *gart_alloc_coherent(struct device *dev, size_t size, dma_addr_t *dma_addr, gfp_t flag, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8106e3d0)
Location: arch/x86/kernel/amd_gart_64.c:479
Inline: True
```
**Symbols:**

```
ffffffff8106e3d0-ffffffff8106e4a6: gart_alloc_coherent.part.11 (STB_LOCAL)
ffffffff8106e4b0-ffffffff8106e4d6: gart_alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *gart_alloc_coherent(struct device *dev, size_t size, dma_addr_t *dma_addr, gfp_t flag, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81071130)
Location: arch/x86/kernel/amd_gart_64.c:480
Inline: False
```
**Symbols:**

```
ffffffff81071130-ffffffff810711fc: gart_alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *gart_alloc_coherent(struct device *dev, size_t size, dma_addr_t *dma_addr, gfp_t flag, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff810771a0)
Location: arch/x86/kernel/amd_gart_64.c:473
Inline: False
```
**Symbols:**

```
ffffffff810771a0-ffffffff8107726a: gart_alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *gart_alloc_coherent(struct device *dev, size_t size, dma_addr_t *dma_addr, gfp_t flag, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8107b130)
Location: arch/x86/kernel/amd_gart_64.c:467
Inline: False
```
**Symbols:**

```
ffffffff8107b130-ffffffff8107b1fa: gart_alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *gart_alloc_coherent(struct device *dev, size_t size, dma_addr_t *dma_addr, gfp_t flag, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8107c220)
Location: arch/x86/kernel/amd_gart_64.c:467
Inline: False
```
**Symbols:**

```
ffffffff8107c220-ffffffff8107c2ea: gart_alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *gart_alloc_coherent(struct device *dev, size_t size, dma_addr_t *dma_addr, gfp_t flag, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff810833c0)
Location: arch/x86/kernel/amd_gart_64.c:466
Inline: False
```
**Symbols:**

```
ffffffff810833c0-ffffffff810834c8: gart_alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *gart_alloc_coherent(struct device *dev, size_t size, dma_addr_t *dma_addr, gfp_t flag, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81084bb0)
Location: arch/x86/kernel/amd_gart_64.c:466
Inline: False
```
**Symbols:**

```
ffffffff81084bb0-ffffffff81084cc6: gart_alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *gart_alloc_coherent(struct device *dev, size_t size, dma_addr_t *dma_addr, gfp_t flag, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff810857a0)
Location: arch/x86/kernel/amd_gart_64.c:466
Inline: False
```
**Symbols:**

```
ffffffff810857a0-ffffffff810858b6: gart_alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void *gart_alloc_coherent(struct device *dev, size_t size, dma_addr_t *dma_addr, gfp_t flag, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (0)
Location: arch/x86/kernel/amd_gart_64.c:466
Inline: False
```
**Symbols:**

```
ffffffff81094900-ffffffff810949db: gart_alloc_coherent (STB_LOCAL)
ffffffff81c9f953-ffffffff81c9f972: gart_alloc_coherent.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void *gart_alloc_coherent(struct device *dev, size_t size, dma_addr_t *dma_addr, gfp_t flag, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (0)
Location: arch/x86/kernel/amd_gart_64.c:464
Inline: False
```
**Symbols:**

```
ffffffff810a6ba0-ffffffff810a6c90: gart_alloc_coherent (STB_LOCAL)
ffffffff81e4f19b-ffffffff81e4f1ba: gart_alloc_coherent.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void *gart_alloc_coherent(struct device *dev, size_t size, dma_addr_t *dma_addr, gfp_t flag, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (0)
Location: arch/x86/kernel/amd_gart_64.c:464
Inline: False
```
**Symbols:**

```
ffffffff810bfd20-ffffffff810bfe10: gart_alloc_coherent (STB_LOCAL)
ffffffff82054765-ffffffff82054784: gart_alloc_coherent.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void *gart_alloc_coherent(struct device *dev, size_t size, dma_addr_t *dma_addr, gfp_t flag, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (0)
Location: arch/x86/kernel/amd_gart_64.c:464
Inline: False
```
**Symbols:**

```
ffffffff810c3400-ffffffff810c34f0: gart_alloc_coherent (STB_LOCAL)
ffffffff820d2d73-ffffffff820d2d92: gart_alloc_coherent.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void *gart_alloc_coherent(struct device *dev, size_t size, dma_addr_t *dma_addr, gfp_t flag, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (0)
Location: arch/x86/kernel/amd_gart_64.c:464
Inline: False
```
**Symbols:**

```
ffffffff810cb840-ffffffff810cb930: gart_alloc_coherent (STB_LOCAL)
ffffffff821adbea-ffffffff821adc09: gart_alloc_coherent.cold (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void *gart_alloc_coherent(struct device *dev, size_t size, dma_addr_t *dma_addr, gfp_t flag, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8107b220)
Location: arch/x86/kernel/amd_gart_64.c:467
Inline: False
```
**Symbols:**

```
ffffffff8107b220-ffffffff8107b2ea: gart_alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *gart_alloc_coherent(struct device *dev, size_t size, dma_addr_t *dma_addr, gfp_t flag, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8106a950)
Location: arch/x86/kernel/amd_gart_64.c:467
Inline: False
```
**Symbols:**

```
ffffffff8106a950-ffffffff8106aa1a: gart_alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *gart_alloc_coherent(struct device *dev, size_t size, dma_addr_t *dma_addr, gfp_t flag, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8107b1d0)
Location: arch/x86/kernel/amd_gart_64.c:467
Inline: False
```
**Symbols:**

```
ffffffff8107b1d0-ffffffff8107b29a: gart_alloc_coherent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *gart_alloc_coherent(struct device *dev, size_t size, dma_addr_t *dma_addr, gfp_t flag, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8107d2d0)
Location: arch/x86/kernel/amd_gart_64.c:467
Inline: False
```
**Symbols:**

```
ffffffff8107d2d0-ffffffff8107d39a: gart_alloc_coherent (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct dma_attrs *attrs</code> ➡️ <code>long unsigned int attrs</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
<b>Arch</b>
<ul>
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
