# Function: <code>gart_map_sg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int gart_map_sg(struct device *dev, struct scatterlist *sg, int nents, enum dma_data_direction dir, struct dma_attrs *attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81066f70)
Location: arch/x86/kernel/amd_gart_64.c:389
Inline: True
```
**Symbols:**

```
ffffffff81066f70-ffffffff810673ab: gart_map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int gart_map_sg(struct device *dev, struct scatterlist *sg, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81066d00)
Location: arch/x86/kernel/amd_gart_64.c:388
Inline: True
```
**Symbols:**

```
ffffffff81066d00-ffffffff81067122: gart_map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int gart_map_sg(struct device *dev, struct scatterlist *sg, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8106a950)
Location: arch/x86/kernel/amd_gart_64.c:388
Inline: True
```
**Symbols:**

```
ffffffff8106a950-ffffffff8106ad78: gart_map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int gart_map_sg(struct device *dev, struct scatterlist *sg, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81069ca0)
Location: arch/x86/kernel/amd_gart_64.c:389
Inline: True
```
**Symbols:**

```
ffffffff81069ca0-ffffffff8106a0b6: gart_map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int gart_map_sg(struct device *dev, struct scatterlist *sg, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8106e550)
Location: arch/x86/kernel/amd_gart_64.c:389
Inline: True
```
**Symbols:**

```
ffffffff8106e550-ffffffff8106e966: gart_map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int gart_map_sg(struct device *dev, struct scatterlist *sg, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (0)
Location: arch/x86/kernel/amd_gart_64.c:390
Inline: True
```
**Symbols:**

```
ffffffff81071270-ffffffff81071685: gart_map_sg (STB_LOCAL)
ffffffff81071844-ffffffff81071853: gart_map_sg.cold.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int gart_map_sg(struct device *dev, struct scatterlist *sg, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff810772a4)
Location: arch/x86/kernel/amd_gart_64.c:383
Inline: True
```
**Symbols:**

```
ffffffff81077270-ffffffff810776cb: gart_map_sg (STB_LOCAL)
ffffffff8107786c-ffffffff8107787c: gart_map_sg.cold.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int gart_map_sg(struct device *dev, struct scatterlist *sg, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8107b080)
Location: arch/x86/kernel/amd_gart_64.c:380
Inline: True
```
**Symbols:**

```
ffffffff8107ac90-ffffffff8107b080: gart_map_sg.part.0 (STB_LOCAL)
ffffffff8107b3bd-ffffffff8107b405: gart_map_sg.part.0.cold (STB_LOCAL)
ffffffff8107b080-ffffffff8107b097: gart_map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int gart_map_sg(struct device *dev, struct scatterlist *sg, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8107c170)
Location: arch/x86/kernel/amd_gart_64.c:380
Inline: True
```
**Symbols:**

```
ffffffff8107bd80-ffffffff8107c16e: gart_map_sg.part.0 (STB_LOCAL)
ffffffff8107c4ad-ffffffff8107c4f5: gart_map_sg.part.0.cold (STB_LOCAL)
ffffffff8107c170-ffffffff8107c187: gart_map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int gart_map_sg(struct device *dev, struct scatterlist *sg, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff810838c0)
Location: arch/x86/kernel/amd_gart_64.c:379
Inline: True
```
**Symbols:**

```
ffffffff810834d0-ffffffff810838b7: gart_map_sg.part.0 (STB_LOCAL)
ffffffff81083aa1-ffffffff81083af5: gart_map_sg.part.0.cold (STB_LOCAL)
ffffffff810838c0-ffffffff810838d7: gart_map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int gart_map_sg(struct device *dev, struct scatterlist *sg, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff810850b0)
Location: arch/x86/kernel/amd_gart_64.c:379
Inline: True
```
**Symbols:**

```
ffffffff81084cd0-ffffffff810850b0: gart_map_sg.part.0 (STB_LOCAL)
ffffffff81bd864d-ffffffff81bd86a1: gart_map_sg.part.0.cold (STB_LOCAL)
ffffffff810850b0-ffffffff810850c7: gart_map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int gart_map_sg(struct device *dev, struct scatterlist *sg, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff81085de0)
Location: arch/x86/kernel/amd_gart_64.c:379
Inline: True
```
**Symbols:**

```
ffffffff810858c0-ffffffff81085ddb: gart_map_sg.part.0 (STB_LOCAL)
ffffffff81bca4e6-ffffffff81bca542: gart_map_sg.part.0.cold (STB_LOCAL)
ffffffff81085de0-ffffffff81085df7: gart_map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int gart_map_sg(struct device *dev, struct scatterlist *sg, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (0)
Location: arch/x86/kernel/amd_gart_64.c:379
Inline: False
```
**Symbols:**

```
ffffffff81094a70-ffffffff81094ee7: gart_map_sg (STB_LOCAL)
ffffffff81c9f972-ffffffff81c9f9a1: gart_map_sg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int gart_map_sg(struct device *dev, struct scatterlist *sg, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (0)
Location: arch/x86/kernel/amd_gart_64.c:377
Inline: False
```
**Symbols:**

```
ffffffff810a6d30-ffffffff810a71de: gart_map_sg (STB_LOCAL)
ffffffff81e4f1ba-ffffffff81e4f1ea: gart_map_sg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int gart_map_sg(struct device *dev, struct scatterlist *sg, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff810bffa0)
Location: arch/x86/kernel/amd_gart_64.c:377
Inline: False
```
**Symbols:**

```
ffffffff810bffa0-ffffffff810c0491: gart_map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int gart_map_sg(struct device *dev, struct scatterlist *sg, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff810c3680)
Location: arch/x86/kernel/amd_gart_64.c:377
Inline: False
```
**Symbols:**

```
ffffffff810c3680-ffffffff810c3b72: gart_map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int gart_map_sg(struct device *dev, struct scatterlist *sg, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff810cbac0)
Location: arch/x86/kernel/amd_gart_64.c:377
Inline: False
```
**Symbols:**

```
ffffffff810cbac0-ffffffff810cbfb2: gart_map_sg (STB_LOCAL)
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

```c
int gart_map_sg(struct device *dev, struct scatterlist *sg, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8107b170)
Location: arch/x86/kernel/amd_gart_64.c:380
Inline: True
```
**Symbols:**

```
ffffffff8107ad80-ffffffff8107b16e: gart_map_sg.part.0 (STB_LOCAL)
ffffffff8107b4ad-ffffffff8107b4f5: gart_map_sg.part.0.cold (STB_LOCAL)
ffffffff8107b170-ffffffff8107b187: gart_map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int gart_map_sg(struct device *dev, struct scatterlist *sg, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8106a8a0)
Location: arch/x86/kernel/amd_gart_64.c:380
Inline: True
```
**Symbols:**

```
ffffffff8106a4b0-ffffffff8106a89e: gart_map_sg.part.0 (STB_LOCAL)
ffffffff8106abdd-ffffffff8106ac25: gart_map_sg.part.0.cold (STB_LOCAL)
ffffffff8106a8a0-ffffffff8106a8b7: gart_map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int gart_map_sg(struct device *dev, struct scatterlist *sg, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8107b120)
Location: arch/x86/kernel/amd_gart_64.c:380
Inline: True
```
**Symbols:**

```
ffffffff8107ad30-ffffffff8107b11e: gart_map_sg.part.0 (STB_LOCAL)
ffffffff8107b45d-ffffffff8107b4a5: gart_map_sg.part.0.cold (STB_LOCAL)
ffffffff8107b120-ffffffff8107b137: gart_map_sg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int gart_map_sg(struct device *dev, struct scatterlist *sg, int nents, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/amd_gart_64.c (ffffffff8107d220)
Location: arch/x86/kernel/amd_gart_64.c:380
Inline: True
```
**Symbols:**

```
ffffffff8107ce30-ffffffff8107d21e: gart_map_sg.part.0 (STB_LOCAL)
ffffffff8107d55d-ffffffff8107d5a5: gart_map_sg.part.0.cold (STB_LOCAL)
ffffffff8107d220-ffffffff8107d237: gart_map_sg (STB_LOCAL)
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
