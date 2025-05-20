# Function: <code>amd_iommu_int_thread</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
irqreturn_t amd_iommu_int_thread(int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81531f30)
Location: drivers/iommu/amd_iommu.c:614
Inline: False
```
**Symbols:**

```
ffffffff81531f30-ffffffff815323ac: amd_iommu_int_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
irqreturn_t amd_iommu_int_thread(int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81586720)
Location: drivers/iommu/amd_iommu.c:710
Inline: False
```
**Symbols:**

```
ffffffff81586720-ffffffff81586b78: amd_iommu_int_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
irqreturn_t amd_iommu_int_thread(int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815b3bf0)
Location: drivers/iommu/amd_iommu.c:773
Inline: False
```
**Symbols:**

```
ffffffff815b3bf0-ffffffff815b4136: amd_iommu_int_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
irqreturn_t amd_iommu_int_thread(int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815c9850)
Location: drivers/iommu/amd_iommu.c:830
Inline: False
```
**Symbols:**

```
ffffffff815c9850-ffffffff815c9eca: amd_iommu_int_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
irqreturn_t amd_iommu_int_thread(int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81630200)
Location: drivers/iommu/amd_iommu.c:769
Inline: False
```
**Symbols:**

```
ffffffff81630200-ffffffff81630892: amd_iommu_int_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
irqreturn_t amd_iommu_int_thread(int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (0)
Location: drivers/iommu/amd_iommu.c:775
Inline: False
```
**Symbols:**

```
ffffffff8166b86d-ffffffff8166b94e: amd_iommu_int_thread.cold.50 (STB_LOCAL)
ffffffff8166ace0-ffffffff8166b2ed: amd_iommu_int_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
irqreturn_t amd_iommu_int_thread(int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (0)
Location: drivers/iommu/amd_iommu.c:790
Inline: False
```
**Symbols:**

```
ffffffff81689faa-ffffffff8168a089: amd_iommu_int_thread.cold.51 (STB_LOCAL)
ffffffff816893e0-ffffffff816899fe: amd_iommu_int_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
irqreturn_t amd_iommu_int_thread(int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (0)
Location: drivers/iommu/amd_iommu.c:778
Inline: False
```
**Symbols:**

```
ffffffff816c1587-ffffffff816c18b7: amd_iommu_int_thread.cold (STB_LOCAL)
ffffffff816c0c10-ffffffff816c0fdc: amd_iommu_int_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
irqreturn_t amd_iommu_int_thread(int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (0)
Location: drivers/iommu/amd_iommu.c:785
Inline: False
```
**Symbols:**

```
ffffffff816e4491-ffffffff816e47d6: amd_iommu_int_thread.cold (STB_LOCAL)
ffffffff816e3c40-ffffffff816e4049: amd_iommu_int_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
irqreturn_t amd_iommu_int_thread(int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:728
Inline: False
```
**Symbols:**

```
ffffffff8179a8a7-ffffffff8179a8c9: amd_iommu_int_thread.cold (STB_LOCAL)
ffffffff81799fa0-ffffffff8179a266: amd_iommu_int_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
irqreturn_t amd_iommu_int_thread(int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:819
Inline: False
```
**Symbols:**

```
ffffffff81c0b771-ffffffff81c0b793: amd_iommu_int_thread.cold (STB_LOCAL)
ffffffff817a86d0-ffffffff817a897b: amd_iommu_int_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
irqreturn_t amd_iommu_int_thread(int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:743
Inline: False
```
**Symbols:**

```
ffffffff81bfd1e6-ffffffff81bfd208: amd_iommu_int_thread.cold (STB_LOCAL)
ffffffff81789340-ffffffff817895ed: amd_iommu_int_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
irqreturn_t amd_iommu_int_thread(int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:750
Inline: False
```
**Symbols:**

```
ffffffff81cfe29c-ffffffff81cfe2cf: amd_iommu_int_thread.cold (STB_LOCAL)
ffffffff81810500-ffffffff818107df: amd_iommu_int_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
irqreturn_t amd_iommu_int_thread(int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:772
Inline: False
```
**Symbols:**

```
ffffffff81ec6bfa-ffffffff81ec6c2d: amd_iommu_int_thread.cold (STB_LOCAL)
ffffffff81952210-ffffffff81952516: amd_iommu_int_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
irqreturn_t amd_iommu_int_thread(int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81ab73b0)
Location: drivers/iommu/amd/iommu.c:840
Inline: False
```
**Symbols:**

```
ffffffff81ab73b0-ffffffff81ab76e3: amd_iommu_int_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
irqreturn_t amd_iommu_int_thread(int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81b03700)
Location: drivers/iommu/amd/iommu.c:851
Inline: False
```
**Symbols:**

```
ffffffff81b03700-ffffffff81b03946: amd_iommu_int_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
irqreturn_t amd_iommu_int_thread(int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81b562e0)
Location: drivers/iommu/amd/iommu.c:1011
Inline: False
```
**Symbols:**

```
ffffffff81b562e0-ffffffff81b56462: amd_iommu_int_thread (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
irqreturn_t amd_iommu_int_thread(int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (0)
Location: drivers/iommu/amd_iommu.c:785
Inline: False
```
**Symbols:**

```
ffffffff816a9f71-ffffffff816aa2b6: amd_iommu_int_thread.cold (STB_LOCAL)
ffffffff816a9720-ffffffff816a9b29: amd_iommu_int_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
irqreturn_t amd_iommu_int_thread(int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (0)
Location: drivers/iommu/amd_iommu.c:785
Inline: False
```
**Symbols:**

```
ffffffff816878d1-ffffffff81687c16: amd_iommu_int_thread.cold (STB_LOCAL)
ffffffff81687080-ffffffff81687489: amd_iommu_int_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
irqreturn_t amd_iommu_int_thread(int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (0)
Location: drivers/iommu/amd_iommu.c:785
Inline: False
```
**Symbols:**

```
ffffffff816d8151-ffffffff816d8496: amd_iommu_int_thread.cold (STB_LOCAL)
ffffffff816d7900-ffffffff816d7d09: amd_iommu_int_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
irqreturn_t amd_iommu_int_thread(int irq, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (0)
Location: drivers/iommu/amd_iommu.c:785
Inline: False
```
**Symbols:**

```
ffffffff816f2701-ffffffff816f2a46: amd_iommu_int_thread.cold (STB_LOCAL)
ffffffff816f1eb0-ffffffff816f22b9: amd_iommu_int_thread (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
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
