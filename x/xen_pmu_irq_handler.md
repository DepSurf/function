# Function: <code>xen_pmu_irq_handler</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
irqreturn_t xen_pmu_irq_handler(int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff810263d0)
Location: arch/x86/xen/pmu.c:477
Inline: False
```
**Symbols:**

```
ffffffff810263d0-ffffffff8102651b: xen_pmu_irq_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
irqreturn_t xen_pmu_irq_handler(int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff81025870)
Location: arch/x86/xen/pmu.c:477
Inline: False
```
**Symbols:**

```
ffffffff81025870-ffffffff810259bf: xen_pmu_irq_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
irqreturn_t xen_pmu_irq_handler(int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff81025f90)
Location: arch/x86/xen/pmu.c:477
Inline: False
```
**Symbols:**

```
ffffffff81025f90-ffffffff810260df: xen_pmu_irq_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
irqreturn_t xen_pmu_irq_handler(int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff8101c8f0)
Location: arch/x86/xen/pmu.c:477
Inline: False
```
**Symbols:**

```
ffffffff8101c8f0-ffffffff8101ca3b: xen_pmu_irq_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
irqreturn_t xen_pmu_irq_handler(int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/pmu.c (ffffffff8101d590)
Location: arch/x86/xen/pmu.c:478
Inline: False
```
**Symbols:**

```
ffffffff8101d590-ffffffff8101d6e1: xen_pmu_irq_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
irqreturn_t xen_pmu_irq_handler(int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/pmu.c (0)
Location: arch/x86/xen/pmu.c:478
Inline: False
```
**Symbols:**

```
ffffffff8101e428-ffffffff8101e46c: xen_pmu_irq_handler.cold.8 (STB_LOCAL)
ffffffff8101df40-ffffffff8101e074: xen_pmu_irq_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
irqreturn_t xen_pmu_irq_handler(int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/pmu.c (0)
Location: arch/x86/xen/pmu.c:485
Inline: False
```
**Symbols:**

```
ffffffff8101dcb8-ffffffff8101dcfc: xen_pmu_irq_handler.cold.8 (STB_LOCAL)
ffffffff8101d7c0-ffffffff8101d8f4: xen_pmu_irq_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
irqreturn_t xen_pmu_irq_handler(int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/pmu.c (0)
Location: arch/x86/xen/pmu.c:485
Inline: False
```
**Symbols:**

```
ffffffff8101f85a-ffffffff8101f8a0: xen_pmu_irq_handler.cold (STB_LOCAL)
ffffffff8101f350-ffffffff8101f49c: xen_pmu_irq_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
irqreturn_t xen_pmu_irq_handler(int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/pmu.c (0)
Location: arch/x86/xen/pmu.c:485
Inline: False
```
**Symbols:**

```
ffffffff810201ba-ffffffff81020200: xen_pmu_irq_handler.cold (STB_LOCAL)
ffffffff8101fcb0-ffffffff8101fdfc: xen_pmu_irq_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
irqreturn_t xen_pmu_irq_handler(int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/pmu.c (0)
Location: arch/x86/xen/pmu.c:485
Inline: False
```
**Symbols:**

```
ffffffff8102280b-ffffffff81022851: xen_pmu_irq_handler.cold (STB_LOCAL)
ffffffff810223d0-ffffffff81022518: xen_pmu_irq_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
irqreturn_t xen_pmu_irq_handler(int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/pmu.c (0)
Location: arch/x86/xen/pmu.c:485
Inline: False
```
**Symbols:**

```
ffffffff81bd2abb-ffffffff81bd2b01: xen_pmu_irq_handler.cold (STB_LOCAL)
ffffffff81022ab0-ffffffff81022bf8: xen_pmu_irq_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
irqreturn_t xen_pmu_irq_handler(int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/pmu.c (0)
Location: arch/x86/xen/pmu.c:485
Inline: False
```
**Symbols:**

```
ffffffff81bc4c5b-ffffffff81bc4c9f: xen_pmu_irq_handler.cold (STB_LOCAL)
ffffffff81024d10-ffffffff81024e4d: xen_pmu_irq_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
irqreturn_t xen_pmu_irq_handler(int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/pmu.c (0)
Location: arch/x86/xen/pmu.c:485
Inline: False
```
**Symbols:**

```
ffffffff81c973b5-ffffffff81c97424: xen_pmu_irq_handler.cold (STB_LOCAL)
ffffffff81029160-ffffffff810292ba: xen_pmu_irq_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
irqreturn_t xen_pmu_irq_handler(int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/pmu.c (0)
Location: arch/x86/xen/pmu.c:479
Inline: False
```
**Symbols:**

```
ffffffff81e46810-ffffffff81e46857: xen_pmu_irq_handler.cold (STB_LOCAL)
ffffffff8102da60-ffffffff8102dbdf: xen_pmu_irq_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
irqreturn_t xen_pmu_irq_handler(int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/pmu.c (0)
Location: arch/x86/xen/pmu.c:492
Inline: False
```
**Symbols:**

```
ffffffff820519be-ffffffff820519e6: xen_pmu_irq_handler.cold (STB_LOCAL)
ffffffff81034df0-ffffffff81034f8c: xen_pmu_irq_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
irqreturn_t xen_pmu_irq_handler(int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/pmu.c (0)
Location: arch/x86/xen/pmu.c:492
Inline: False
```
**Symbols:**

```
ffffffff820cfeaa-ffffffff820cfed2: xen_pmu_irq_handler.cold (STB_LOCAL)
ffffffff81034d70-ffffffff81034f0c: xen_pmu_irq_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
irqreturn_t xen_pmu_irq_handler(int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/pmu.c (0)
Location: arch/x86/xen/pmu.c:492
Inline: False
```
**Symbols:**

```
ffffffff821aa817-ffffffff821aa83f: xen_pmu_irq_handler.cold (STB_LOCAL)
ffffffff8103af70-ffffffff8103b10c: xen_pmu_irq_handler (STB_GLOBAL)
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
irqreturn_t xen_pmu_irq_handler(int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/pmu.c (0)
Location: arch/x86/xen/pmu.c:485
Inline: False
```
**Symbols:**

```
ffffffff8102031a-ffffffff81020360: xen_pmu_irq_handler.cold (STB_LOCAL)
ffffffff8101fe10-ffffffff8101ff5c: xen_pmu_irq_handler (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
irqreturn_t xen_pmu_irq_handler(int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/pmu.c (0)
Location: arch/x86/xen/pmu.c:485
Inline: False
```
**Symbols:**

```
ffffffff8102017a-ffffffff810201c0: xen_pmu_irq_handler.cold (STB_LOCAL)
ffffffff8101fc70-ffffffff8101fdbc: xen_pmu_irq_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
irqreturn_t xen_pmu_irq_handler(int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/pmu.c (0)
Location: arch/x86/xen/pmu.c:485
Inline: False
```
**Symbols:**

```
ffffffff810203ca-ffffffff81020410: xen_pmu_irq_handler.cold (STB_LOCAL)
ffffffff8101fec0-ffffffff8102000c: xen_pmu_irq_handler (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
