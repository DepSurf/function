# Function: <code>dmar_fault</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
irqreturn_t dmar_fault(int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff81532f50)
Location: drivers/iommu/dmar.c:1593
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:enable_drhd_fault_handling
```
**Symbols:**

```
ffffffff81532f50-ffffffff81533139: dmar_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
irqreturn_t dmar_fault(int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff81587df0)
Location: drivers/iommu/dmar.c:1602
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:enable_drhd_fault_handling
```
**Symbols:**

```
ffffffff81587df0-ffffffff81588032: dmar_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
irqreturn_t dmar_fault(int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff815b54b0)
Location: drivers/iommu/dmar.c:1603
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:enable_drhd_fault_handling
```
**Symbols:**

```
ffffffff815b54b0-ffffffff815b56f2: dmar_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
irqreturn_t dmar_fault(int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff815cb330)
Location: drivers/iommu/dmar.c:1612
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:enable_drhd_fault_handling
```
**Symbols:**

```
ffffffff815cb330-ffffffff815cb55b: dmar_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
irqreturn_t dmar_fault(int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff81632100)
Location: drivers/iommu/dmar.c:1615
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:enable_drhd_fault_handling
```
**Symbols:**

```
ffffffff81632100-ffffffff8163232b: dmar_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
irqreturn_t dmar_fault(int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:1615
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:enable_drhd_fault_handling
```
**Symbols:**

```
ffffffff8166f22f-ffffffff8166f2e0: dmar_fault.cold.22 (STB_LOCAL)
ffffffff8166d4c0-ffffffff8166d604: dmar_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
irqreturn_t dmar_fault(int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:1646
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:enable_drhd_fault_handling
```
**Symbols:**

```
ffffffff8168d78f-ffffffff8168d840: dmar_fault.cold.21 (STB_LOCAL)
ffffffff8168b8d0-ffffffff8168ba14: dmar_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
irqreturn_t dmar_fault(int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:1635
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:enable_drhd_fault_handling
```
**Symbols:**

```
ffffffff816c517f-ffffffff816c5232: dmar_fault.cold (STB_LOCAL)
ffffffff816c32c0-ffffffff816c3411: dmar_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
irqreturn_t dmar_fault(int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:1708
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:enable_drhd_fault_handling
```
**Symbols:**

```
ffffffff816e80af-ffffffff816e8192: dmar_fault.cold (STB_LOCAL)
ffffffff816e6200-ffffffff816e6368: dmar_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
irqreturn_t dmar_fault(int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:1824
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:enable_drhd_fault_handling
```
**Symbols:**

```
ffffffff8179ed7c-ffffffff8179ed97: dmar_fault.cold (STB_LOCAL)
ffffffff8179cd20-ffffffff8179cead: dmar_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
irqreturn_t dmar_fault(int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:1861
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:enable_drhd_fault_handling
```
**Symbols:**

```
ffffffff81c0c1a7-ffffffff81c0c1c2: dmar_fault.cold (STB_LOCAL)
ffffffff817aa9f0-ffffffff817aab7c: dmar_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
irqreturn_t dmar_fault(int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:1930
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:enable_drhd_fault_handling
```
**Symbols:**

```
ffffffff81bfd90d-ffffffff81bfd9f9: dmar_fault.cold (STB_LOCAL)
ffffffff8178d3e0-ffffffff8178d542: dmar_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
irqreturn_t dmar_fault(int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:1966
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:enable_drhd_fault_handling
```
**Symbols:**

```
ffffffff81cfee5e-ffffffff81cfefce: dmar_fault.cold (STB_LOCAL)
ffffffff81814bd0-ffffffff81814dc4: dmar_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
irqreturn_t dmar_fault(int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:1968
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:enable_drhd_fault_handling
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
```
**Symbols:**

```
ffffffff81ec7675-ffffffff81ec77c6: dmar_fault.cold (STB_LOCAL)
ffffffff81955e20-ffffffff81956088: dmar_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
irqreturn_t dmar_fault(int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff81abc9a0)
Location: drivers/iommu/intel/dmar.c:1957
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:enable_drhd_fault_handling
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
```
**Symbols:**

```
ffffffff81abc9a0-ffffffff81abcd82: dmar_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
irqreturn_t dmar_fault(int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff81b09290)
Location: drivers/iommu/intel/dmar.c:1980
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:enable_drhd_fault_handling
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
```
**Symbols:**

```
ffffffff81b09290-ffffffff81b096cd: dmar_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
irqreturn_t dmar_fault(int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff81b5d2b0)
Location: drivers/iommu/intel/dmar.c:1998
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:enable_drhd_fault_handling
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
```
**Symbols:**

```
ffffffff81b5d2b0-ffffffff81b5d6ed: dmar_fault (STB_GLOBAL)
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
irqreturn_t dmar_fault(int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:1708
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:enable_drhd_fault_handling
```
**Symbols:**

```
ffffffff816adb8f-ffffffff816adc72: dmar_fault.cold (STB_LOCAL)
ffffffff816abce0-ffffffff816abe48: dmar_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
irqreturn_t dmar_fault(int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:1708
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:enable_drhd_fault_handling
```
**Symbols:**

```
ffffffff8168b4ef-ffffffff8168b5d2: dmar_fault.cold (STB_LOCAL)
ffffffff81689640-ffffffff816897a8: dmar_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
irqreturn_t dmar_fault(int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:1708
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:enable_drhd_fault_handling
```
**Symbols:**

```
ffffffff816dbd6f-ffffffff816dbe52: dmar_fault.cold (STB_LOCAL)
ffffffff816d9ec0-ffffffff816da028: dmar_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
irqreturn_t dmar_fault(int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:1708
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:enable_drhd_fault_handling
```
**Symbols:**

```
ffffffff816f633f-ffffffff816f6422: dmar_fault.cold (STB_LOCAL)
ffffffff816f4470-ffffffff816f45d8: dmar_fault (STB_GLOBAL)
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
