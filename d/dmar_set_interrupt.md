# Function: <code>dmar_set_interrupt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dmar_set_interrupt(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff81533740)
Location: drivers/iommu/dmar.c:1656
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:enable_drhd_fault_handling
Direct callers:
  - drivers/iommu/dmar.c:enable_drhd_fault_handling
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81533740-ffffffff815337ad: dmar_set_interrupt.part.11 (STB_LOCAL)
ffffffff815353f0-ffffffff8153540a: dmar_set_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dmar_set_interrupt(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff81fd77f6)
Location: drivers/iommu/dmar.c:1676
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:enable_drhd_fault_handling
Direct callers:
  - drivers/iommu/dmar.c:enable_drhd_fault_handling
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81587d80-ffffffff81587ded: dmar_set_interrupt.part.12 (STB_LOCAL)
ffffffff81589ca0-ffffffff81589cba: dmar_set_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dmar_set_interrupt(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff8201541e)
Location: drivers/iommu/dmar.c:1677
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:enable_drhd_fault_handling
Direct callers:
  - drivers/iommu/dmar.c:enable_drhd_fault_handling
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff815b5440-ffffffff815b54ad: dmar_set_interrupt.part.14 (STB_LOCAL)
ffffffff815b7350-ffffffff815b736a: dmar_set_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dmar_set_interrupt(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff820f7089)
Location: drivers/iommu/dmar.c:1686
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:enable_drhd_fault_handling
Direct callers:
  - drivers/iommu/dmar.c:enable_drhd_fault_handling
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff815cb2c0-ffffffff815cb32d: dmar_set_interrupt.part.16 (STB_LOCAL)
ffffffff815cd130-ffffffff815cd14a: dmar_set_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dmar_set_interrupt(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff827007f4)
Location: drivers/iommu/dmar.c:1690
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:enable_drhd_fault_handling
Direct callers:
  - drivers/iommu/dmar.c:enable_drhd_fault_handling
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81632090-ffffffff816320fd: dmar_set_interrupt.part.15 (STB_LOCAL)
ffffffff81633f30-ffffffff81633f4a: dmar_set_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dmar_set_interrupt(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff8272a519)
Location: drivers/iommu/dmar.c:1688
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:enable_drhd_fault_handling
Direct callers:
  - drivers/iommu/dmar.c:enable_drhd_fault_handling
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff8166d460-ffffffff8166d4b5: dmar_set_interrupt.part.15 (STB_LOCAL)
ffffffff8166f208-ffffffff8166f22f: dmar_set_interrupt.part.15.cold.21 (STB_LOCAL)
ffffffff8166f0d0-ffffffff8166f0ea: dmar_set_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dmar_set_interrupt(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff828e2dd7)
Location: drivers/iommu/dmar.c:1719
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:enable_drhd_fault_handling
Direct callers:
  - drivers/iommu/dmar.c:enable_drhd_fault_handling
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff8168b870-ffffffff8168b8c5: dmar_set_interrupt.part.14 (STB_LOCAL)
ffffffff8168d768-ffffffff8168d78f: dmar_set_interrupt.part.14.cold.20 (STB_LOCAL)
ffffffff8168d630-ffffffff8168d64a: dmar_set_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dmar_set_interrupt(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff828fd896)
Location: drivers/iommu/dmar.c:1708
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:enable_drhd_fault_handling
Direct callers:
  - drivers/iommu/dmar.c:enable_drhd_fault_handling
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff816c3260-ffffffff816c32bb: dmar_set_interrupt.part.0 (STB_LOCAL)
ffffffff816c5157-ffffffff816c517f: dmar_set_interrupt.part.0.cold (STB_LOCAL)
ffffffff816c5030-ffffffff816c504a: dmar_set_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dmar_set_interrupt(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff829068cb)
Location: drivers/iommu/dmar.c:1786
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:enable_drhd_fault_handling
Direct callers:
  - drivers/iommu/dmar.c:enable_drhd_fault_handling
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff816e61a0-ffffffff816e61fb: dmar_set_interrupt.part.0 (STB_LOCAL)
ffffffff816e8087-ffffffff816e80af: dmar_set_interrupt.part.0.cold (STB_LOCAL)
ffffffff816e7f60-ffffffff816e7f7a: dmar_set_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dmar_set_interrupt(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff82d1d139)
Location: drivers/iommu/intel/dmar.c:1902
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:enable_drhd_fault_handling
Direct callers:
  - drivers/iommu/intel/dmar.c:enable_drhd_fault_handling
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff8179c810-ffffffff8179c86b: dmar_set_interrupt.part.0 (STB_LOCAL)
ffffffff8179ec65-ffffffff8179ec8d: dmar_set_interrupt.part.0.cold (STB_LOCAL)
ffffffff8179eaa0-ffffffff8179eaba: dmar_set_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dmar_set_interrupt(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff8300aeb8)
Location: drivers/iommu/intel/dmar.c:1940
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:enable_drhd_fault_handling
Direct callers:
  - drivers/iommu/intel/dmar.c:enable_drhd_fault_handling
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff817aa4e0-ffffffff817aa53b: dmar_set_interrupt.part.0 (STB_LOCAL)
ffffffff81c0c090-ffffffff81c0c0b8: dmar_set_interrupt.part.0.cold (STB_LOCAL)
ffffffff817ac7f0-ffffffff817ac80a: dmar_set_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dmar_set_interrupt(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff83215b1c)
Location: drivers/iommu/intel/dmar.c:2009
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:enable_drhd_fault_handling
Direct callers:
  - drivers/iommu/intel/dmar.c:enable_drhd_fault_handling
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff8178d280-ffffffff8178d2db: dmar_set_interrupt.part.0 (STB_LOCAL)
ffffffff81bfd8cc-ffffffff81bfd8f4: dmar_set_interrupt.part.0.cold (STB_LOCAL)
ffffffff8178f6c0-ffffffff8178f6da: dmar_set_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dmar_set_interrupt(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff832ff375)
Location: drivers/iommu/intel/dmar.c:2045
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:enable_drhd_fault_handling
Direct callers:
  - drivers/iommu/intel/dmar.c:enable_drhd_fault_handling
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff818149d0-ffffffff81814a2b: dmar_set_interrupt.part.0 (STB_LOCAL)
ffffffff81cfee1d-ffffffff81cfee45: dmar_set_interrupt.part.0.cold (STB_LOCAL)
ffffffff81816fd0-ffffffff81816fea: dmar_set_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dmar_set_interrupt(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff834b8046)
Location: drivers/iommu/intel/dmar.c:2047
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:enable_drhd_fault_handling
Direct callers:
  - drivers/iommu/intel/dmar.c:enable_drhd_fault_handling
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81955870-ffffffff819558da: dmar_set_interrupt.part.0 (STB_LOCAL)
ffffffff81ec7604-ffffffff81ec762b: dmar_set_interrupt.part.0.cold (STB_LOCAL)
ffffffff81958010-ffffffff81958036: dmar_set_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dmar_set_interrupt(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff83ef4cb1)
Location: drivers/iommu/intel/dmar.c:2036
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:enable_drhd_fault_handling
Direct callers:
  - drivers/iommu/intel/dmar.c:enable_drhd_fault_handling
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81abc340-ffffffff81abc3da: dmar_set_interrupt.part.0 (STB_LOCAL)
ffffffff81abf020-ffffffff81abf046: dmar_set_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dmar_set_interrupt(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff8371a871)
Location: drivers/iommu/intel/dmar.c:2059
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:enable_drhd_fault_handling
Direct callers:
  - drivers/iommu/intel/dmar.c:enable_drhd_fault_handling
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81b08c30-ffffffff81b08cca: dmar_set_interrupt.part.0 (STB_LOCAL)
ffffffff81b0ba10-ffffffff81b0ba36: dmar_set_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dmar_set_interrupt(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff8394e351)
Location: drivers/iommu/intel/dmar.c:2077
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:enable_drhd_fault_handling
Direct callers:
  - drivers/iommu/intel/dmar.c:enable_drhd_fault_handling
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81b5cc50-ffffffff81b5ccea: dmar_set_interrupt.part.0 (STB_LOCAL)
ffffffff81b5faf0-ffffffff81b5fb16: dmar_set_interrupt (STB_GLOBAL)
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
int dmar_set_interrupt(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff828ee0b2)
Location: drivers/iommu/dmar.c:1786
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:enable_drhd_fault_handling
Direct callers:
  - drivers/iommu/dmar.c:enable_drhd_fault_handling
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff816abc80-ffffffff816abcdb: dmar_set_interrupt.part.0 (STB_LOCAL)
ffffffff816adb67-ffffffff816adb8f: dmar_set_interrupt.part.0.cold (STB_LOCAL)
ffffffff816ada40-ffffffff816ada5a: dmar_set_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dmar_set_interrupt(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff828e553f)
Location: drivers/iommu/dmar.c:1786
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:enable_drhd_fault_handling
Direct callers:
  - drivers/iommu/dmar.c:enable_drhd_fault_handling
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff816895e0-ffffffff8168963b: dmar_set_interrupt.part.0 (STB_LOCAL)
ffffffff8168b4c7-ffffffff8168b4ef: dmar_set_interrupt.part.0.cold (STB_LOCAL)
ffffffff8168b3a0-ffffffff8168b3ba: dmar_set_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dmar_set_interrupt(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff82901bee)
Location: drivers/iommu/dmar.c:1786
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:enable_drhd_fault_handling
Direct callers:
  - drivers/iommu/dmar.c:enable_drhd_fault_handling
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff816d9e60-ffffffff816d9ebb: dmar_set_interrupt.part.0 (STB_LOCAL)
ffffffff816dbd47-ffffffff816dbd6f: dmar_set_interrupt.part.0.cold (STB_LOCAL)
ffffffff816dbc20-ffffffff816dbc3a: dmar_set_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dmar_set_interrupt(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff8290792d)
Location: drivers/iommu/dmar.c:1786
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:enable_drhd_fault_handling
Direct callers:
  - drivers/iommu/dmar.c:enable_drhd_fault_handling
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff816f4410-ffffffff816f446b: dmar_set_interrupt.part.0 (STB_LOCAL)
ffffffff816f6317-ffffffff816f633f: dmar_set_interrupt.part.0.cold (STB_LOCAL)
ffffffff816f61f0-ffffffff816f620a: dmar_set_interrupt (STB_GLOBAL)
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
