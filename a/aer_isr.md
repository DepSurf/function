# Function: <code>aer_isr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void aer_isr(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff8144a830)
Location: drivers/pci/pcie/aer/aerdrv_core.c:804
Inline: False
```
**Symbols:**

```
ffffffff8144a830-ffffffff8144ac15: aer_isr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void aer_isr(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff81496af0)
Location: drivers/pci/pcie/aer/aerdrv_core.c:804
Inline: False
```
**Symbols:**

```
ffffffff81496af0-ffffffff81496ea1: aer_isr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void aer_isr(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff814b84c0)
Location: drivers/pci/pcie/aer/aerdrv_core.c:797
Inline: False
```
**Symbols:**

```
ffffffff814b84c0-ffffffff814b8860: aer_isr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void aer_isr(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff814c2d20)
Location: drivers/pci/pcie/aer/aerdrv_core.c:797
Inline: False
```
**Symbols:**

```
ffffffff814c2d20-ffffffff814c30c6: aer_isr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void aer_isr(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer/aerdrv_core.c (ffffffff81502f70)
Location: drivers/pci/pcie/aer/aerdrv_core.c:805
Inline: False
```
**Symbols:**

```
ffffffff81502f70-ffffffff81503316: aer_isr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void aer_isr(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff81533d00)
Location: drivers/pci/pcie/aer.c:1044
Inline: False
```
**Symbols:**

```
ffffffff81533d00-ffffffff815345f0: aer_isr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
irqreturn_t aer_isr(int irq, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff8154bc40)
Location: drivers/pci/pcie/aer.c:1211
Inline: False
```
**Symbols:**

```
ffffffff8154bc40-ffffffff8154c0d4: aer_isr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
irqreturn_t aer_isr(int irq, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aer.c (0)
Location: drivers/pci/pcie/aer.c:1211
Inline: False
```
**Symbols:**

```
ffffffff8157b5d0-ffffffff8157b6ba: aer_isr (STB_LOCAL)
ffffffff8157be5a-ffffffff8157befb: aer_isr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
irqreturn_t aer_isr(int irq, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aer.c (0)
Location: drivers/pci/pcie/aer.c:1211
Inline: False
```
**Symbols:**

```
ffffffff8159d030-ffffffff8159d11a: aer_isr (STB_LOCAL)
ffffffff8159d8ba-ffffffff8159d95b: aer_isr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
irqreturn_t aer_isr(int irq, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff8163cd60)
Location: drivers/pci/pcie/aer.c:1137
Inline: False
```
**Symbols:**

```
ffffffff8163cd60-ffffffff8163cddb: aer_isr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
irqreturn_t aer_isr(int irq, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff81663cc0)
Location: drivers/pci/pcie/aer.c:1167
Inline: False
```
**Symbols:**

```
ffffffff81663cc0-ffffffff81663d3b: aer_isr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
irqreturn_t aer_isr(int irq, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aer.c (0)
Location: drivers/pci/pcie/aer.c:1167
Inline: False
```
**Symbols:**

```
ffffffff816460c0-ffffffff816461aa: aer_isr (STB_LOCAL)
ffffffff81beb7c5-ffffffff81beb866: aer_isr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
irqreturn_t aer_isr(int irq, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff816b7440)
Location: drivers/pci/pcie/aer.c:1169
Inline: False
```
**Symbols:**

```
ffffffff816b7440-ffffffff816b7a23: aer_isr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
irqreturn_t aer_isr(int irq, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff817db150)
Location: drivers/pci/pcie/aer.c:1174
Inline: False
```
**Symbols:**

```
ffffffff817db150-ffffffff817db7a0: aer_isr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
irqreturn_t aer_isr(int irq, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff818fd290)
Location: drivers/pci/pcie/aer.c:1185
Inline: False
```
**Symbols:**

```
ffffffff818fd290-ffffffff818fd466: aer_isr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
irqreturn_t aer_isr(int irq, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff81940710)
Location: drivers/pci/pcie/aer.c:1188
Inline: False
```
**Symbols:**

```
ffffffff81940710-ffffffff819408f9: aer_isr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
irqreturn_t aer_isr(int irq, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffff81989970)
Location: drivers/pci/pcie/aer.c:1336
Inline: False
```
**Symbols:**

```
ffffffff81989970-ffffffff81989b59: aer_isr (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
irqreturn_t aer_isr(int irq, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffff800010705010)
Location: drivers/pci/pcie/aer.c:1211
Inline: False
```
**Symbols:**

```
ffff800010705010-ffff8000107051d8: aer_isr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
irqreturn_t aer_isr(int irq, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (c089c31c)
Location: drivers/pci/pcie/aer.c:1211
Inline: False
```
**Symbols:**

```
c089c31c-c089c4f4: aer_isr (STB_LOCAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
irqreturn_t aer_isr(int irq, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/aer.c (ffffffe0004d3124)
Location: drivers/pci/pcie/aer.c:1211
Inline: False
```
**Symbols:**

```
ffffffe0004d3124-ffffffe0004d32f6: aer_isr (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
irqreturn_t aer_isr(int irq, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aer.c (0)
Location: drivers/pci/pcie/aer.c:1211
Inline: False
```
**Symbols:**

```
ffffffff81590b00-ffffffff81590bea: aer_isr (STB_LOCAL)
ffffffff815910b9-ffffffff8159115a: aer_isr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
irqreturn_t aer_isr(int irq, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aer.c (0)
Location: drivers/pci/pcie/aer.c:1211
Inline: False
```
**Symbols:**

```
ffffffff8157fa00-ffffffff8157faea: aer_isr (STB_LOCAL)
ffffffff8158028a-ffffffff8158032b: aer_isr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
irqreturn_t aer_isr(int irq, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aer.c (0)
Location: drivers/pci/pcie/aer.c:1211
Inline: False
```
**Symbols:**

```
ffffffff81590d80-ffffffff81590e6a: aer_isr (STB_LOCAL)
ffffffff8159160a-ffffffff815916ab: aer_isr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
irqreturn_t aer_isr(int irq, void *context);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pcie/aer.c (0)
Location: drivers/pci/pcie/aer.c:1211
Inline: False
```
**Symbols:**

```
ffffffff815ab230-ffffffff815ab31a: aer_isr (STB_LOCAL)
ffffffff815abacf-ffffffff815abb70: aer_isr.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int irq</code>
</li>
<li>
<b>Param added. </b>
<code>void *context</code>
</li>
<li>
<b>Param removed. </b>
<code>struct work_struct *work</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>irqreturn_t</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
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
