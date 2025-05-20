# Function: <code>disable_dmar_iommu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void disable_dmar_iommu(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815391d0)
Location: drivers/iommu/intel-iommu.c:1667
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff815391d0-ffffffff815392a3: disable_dmar_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void disable_dmar_iommu(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8158dcd0)
Location: drivers/iommu/intel-iommu.c:1706
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff8158dcd0-ffffffff8158dda0: disable_dmar_iommu (STB_LOCAL)
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
In drivers/iommu/intel-iommu.c (ffffffff815bbd2d)
Location: drivers/iommu/intel-iommu.c:1720
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff815bb910-ffffffff815bb9dd: disable_dmar_iommu.part.51 (STB_LOCAL)
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
In drivers/iommu/intel-iommu.c (ffffffff815d196d)
Location: drivers/iommu/intel-iommu.c:1725
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff815d1540-ffffffff815d160d: disable_dmar_iommu.part.56 (STB_LOCAL)
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
In drivers/iommu/intel-iommu.c (ffffffff8163873d)
Location: drivers/iommu/intel-iommu.c:1727
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81638310-ffffffff816383dd: disable_dmar_iommu.part.58 (STB_LOCAL)
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
In drivers/iommu/intel-iommu.c (ffffffff81673a3d)
Location: drivers/iommu/intel-iommu.c:1755
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81673630-ffffffff816736fd: disable_dmar_iommu.part.66 (STB_LOCAL)
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
In drivers/iommu/intel-iommu.c (ffffffff8169200f)
Location: drivers/iommu/intel-iommu.c:1642
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff8168ff90-ffffffff8169005d: disable_dmar_iommu.part.67 (STB_LOCAL)
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
In drivers/iommu/intel-iommu.c (ffffffff816c9f8f)
Location: drivers/iommu/intel-iommu.c:1650
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff816c7bc0-ffffffff816c7c5f: disable_dmar_iommu.part.0 (STB_LOCAL)
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
In drivers/iommu/intel-iommu.c (ffffffff816ecf5f)
Location: drivers/iommu/intel-iommu.c:1661
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff816eab70-ffffffff816eac0f: disable_dmar_iommu.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void disable_dmar_iommu(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817a524e)
Location: drivers/iommu/intel/iommu.c:1706
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel/iommu.c:intel_iommu_add
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff817a2340-ffffffff817a23df: disable_dmar_iommu.part.0 (STB_LOCAL)
ffffffff817a23e0-ffffffff817a23ff: disable_dmar_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void disable_dmar_iommu(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817b269e)
Location: drivers/iommu/intel/iommu.c:1804
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel/iommu.c:intel_iommu_add
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff817b0500-ffffffff817b059f: disable_dmar_iommu.part.0 (STB_LOCAL)
ffffffff817b05a0-ffffffff817b05bf: disable_dmar_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void disable_dmar_iommu(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8179558e)
Location: drivers/iommu/intel/iommu.c:1828
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel/iommu.c:intel_iommu_add
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff817922f0-ffffffff8179238f: disable_dmar_iommu.part.0 (STB_LOCAL)
ffffffff81792390-ffffffff817923af: disable_dmar_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void disable_dmar_iommu(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8181d3fe)
Location: drivers/iommu/intel/iommu.c:1829
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel/iommu.c:intel_iommu_add
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81819a90-ffffffff81819b2f: disable_dmar_iommu.part.0 (STB_LOCAL)
ffffffff81819b30-ffffffff81819b4f: disable_dmar_iommu (STB_LOCAL)
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
In drivers/iommu/intel/iommu.c (ffffffff8195e172)
Location: drivers/iommu/intel/iommu.c:1728
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff8195bed0-ffffffff8195bf8b: disable_dmar_iommu.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void disable_dmar_iommu(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81ac01d0)
Location: drivers/iommu/intel/iommu.c:1696
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81ac01d0-ffffffff81ac023a: disable_dmar_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void disable_dmar_iommu(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81b0ca80)
Location: drivers/iommu/intel/iommu.c:1667
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81b0ca80-ffffffff81b0caed: disable_dmar_iommu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void disable_dmar_iommu(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81b61230)
Location: drivers/iommu/intel/iommu.c:1617
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81b61230-ffffffff81b6129d: disable_dmar_iommu (STB_LOCAL)
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
In drivers/iommu/intel-iommu.c (ffffffff816b26cf)
Location: drivers/iommu/intel-iommu.c:1661
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff816b0650-ffffffff816b06ef: disable_dmar_iommu.part.0 (STB_LOCAL)
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
In drivers/iommu/intel-iommu.c (ffffffff8169038f)
Location: drivers/iommu/intel-iommu.c:1661
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff8168dfa0-ffffffff8168e03f: disable_dmar_iommu.part.0 (STB_LOCAL)
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
In drivers/iommu/intel-iommu.c (ffffffff816e0c1f)
Location: drivers/iommu/intel-iommu.c:1661
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff816de830-ffffffff816de8cf: disable_dmar_iommu.part.0 (STB_LOCAL)
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
In drivers/iommu/intel-iommu.c (ffffffff816fb22f)
Location: drivers/iommu/intel-iommu.c:1661
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff816f8f50-ffffffff816f8fef: disable_dmar_iommu.part.0 (STB_LOCAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
