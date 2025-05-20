# Function: <code>dmar_insert_dev_scope</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int dmar_insert_dev_scope(struct dmar_pci_notify_info *info, void *start, void *end, u16 segment, struct dmar_dev_scope *devices, int devices_cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff815344e0)
Location: drivers/iommu/dmar.c:220
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_pci_bus_add_dev
  - drivers/iommu/intel-iommu.c:dmar_iommu_notify_scope_dev
  - drivers/iommu/intel-iommu.c:dmar_iommu_notify_scope_dev
```
**Symbols:**

```
ffffffff815344e0-ffffffff8153471c: dmar_insert_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int dmar_insert_dev_scope(struct dmar_pci_notify_info *info, void *start, void *end, u16 segment, struct dmar_dev_scope *devices, int devices_cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff81588d80)
Location: drivers/iommu/dmar.c:220
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_pci_bus_add_dev
  - drivers/iommu/intel-iommu.c:dmar_iommu_notify_scope_dev
  - drivers/iommu/intel-iommu.c:dmar_iommu_notify_scope_dev
```
**Symbols:**

```
ffffffff81588d80-ffffffff81588feb: dmar_insert_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dmar_insert_dev_scope(struct dmar_pci_notify_info *info, void *start, void *end, u16 segment, struct dmar_dev_scope *devices, int devices_cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff815b6440)
Location: drivers/iommu/dmar.c:219
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_pci_bus_add_dev
  - drivers/iommu/intel-iommu.c:dmar_iommu_notify_scope_dev
  - drivers/iommu/intel-iommu.c:dmar_iommu_notify_scope_dev
```
**Symbols:**

```
ffffffff815b6440-ffffffff815b66ab: dmar_insert_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dmar_insert_dev_scope(struct dmar_pci_notify_info *info, void *start, void *end, u16 segment, struct dmar_dev_scope *devices, int devices_cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff815cc2c0)
Location: drivers/iommu/dmar.c:221
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_pci_bus_add_dev
  - drivers/iommu/intel-iommu.c:dmar_iommu_notify_scope_dev
  - drivers/iommu/intel-iommu.c:dmar_iommu_notify_scope_dev
```
**Symbols:**

```
ffffffff815cc2c0-ffffffff815cc4ff: dmar_insert_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dmar_insert_dev_scope(struct dmar_pci_notify_info *info, void *start, void *end, u16 segment, struct dmar_dev_scope *devices, int devices_cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff81633090)
Location: drivers/iommu/dmar.c:221
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_pci_bus_add_dev
  - drivers/iommu/intel-iommu.c:dmar_iommu_notify_scope_dev
  - drivers/iommu/intel-iommu.c:dmar_iommu_notify_scope_dev
```
**Symbols:**

```
ffffffff81633090-ffffffff816332cf: dmar_insert_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int dmar_insert_dev_scope(struct dmar_pci_notify_info *info, void *start, void *end, u16 segment, struct dmar_dev_scope *devices, int devices_cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:221
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_pci_bus_add_dev
  - drivers/iommu/intel-iommu.c:dmar_iommu_notify_scope_dev
  - drivers/iommu/intel-iommu.c:dmar_iommu_notify_scope_dev
```
**Symbols:**

```
ffffffff8166f423-ffffffff8166f471: dmar_insert_dev_scope.cold.27 (STB_LOCAL)
ffffffff8166e2b0-ffffffff8166e4a3: dmar_insert_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int dmar_insert_dev_scope(struct dmar_pci_notify_info *info, void *start, void *end, u16 segment, struct dmar_dev_scope *devices, int devices_cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:221
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_pci_bus_add_dev
  - drivers/iommu/intel-iommu.c:dmar_iommu_notify_scope_dev
  - drivers/iommu/intel-iommu.c:dmar_iommu_notify_scope_dev
```
**Symbols:**

```
ffffffff8168d983-ffffffff8168d9d1: dmar_insert_dev_scope.cold.26 (STB_LOCAL)
ffffffff8168c6e0-ffffffff8168c8d3: dmar_insert_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int dmar_insert_dev_scope(struct dmar_pci_notify_info *info, void *start, void *end, u16 segment, struct dmar_dev_scope *devices, int devices_cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:210
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_pci_bus_add_dev
  - drivers/iommu/intel-iommu.c:dmar_iommu_notify_scope_dev
  - drivers/iommu/intel-iommu.c:dmar_iommu_notify_scope_dev
```
**Symbols:**

```
ffffffff816c53aa-ffffffff816c5401: dmar_insert_dev_scope.cold (STB_LOCAL)
ffffffff816c4170-ffffffff816c4320: dmar_insert_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int dmar_insert_dev_scope(struct dmar_pci_notify_info *info, void *start, void *end, u16 segment, struct dmar_dev_scope *devices, int devices_cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:218
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_pci_bus_add_dev
  - drivers/iommu/intel-iommu.c:dmar_iommu_notify_scope_dev
  - drivers/iommu/intel-iommu.c:dmar_iommu_notify_scope_dev
```
**Symbols:**

```
ffffffff816e82e1-ffffffff816e8338: dmar_insert_dev_scope.cold (STB_LOCAL)
ffffffff816e70c0-ffffffff816e7270: dmar_insert_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int dmar_insert_dev_scope(struct dmar_pci_notify_info *info, void *start, void *end, u16 segment, struct dmar_dev_scope *devices, int devices_cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:218
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_iommu_notify_scope_dev
  - drivers/iommu/intel/iommu.c:dmar_iommu_notify_scope_dev
```
**Symbols:**

```
ffffffff8179ee59-ffffffff8179eeab: dmar_insert_dev_scope.cold (STB_LOCAL)
ffffffff8179d870-ffffffff8179da1a: dmar_insert_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int dmar_insert_dev_scope(struct dmar_pci_notify_info *info, void *start, void *end, u16 segment, struct dmar_dev_scope *devices, int devices_cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:218
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_iommu_notify_scope_dev
  - drivers/iommu/intel/iommu.c:dmar_iommu_notify_scope_dev
```
**Symbols:**

```
ffffffff81c0c2a1-ffffffff81c0c2f3: dmar_insert_dev_scope.cold (STB_LOCAL)
ffffffff817ab590-ffffffff817ab73a: dmar_insert_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int dmar_insert_dev_scope(struct dmar_pci_notify_info *info, void *start, void *end, u16 segment, struct dmar_dev_scope *devices, int devices_cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:219
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_iommu_notify_scope_dev
  - drivers/iommu/intel/iommu.c:dmar_iommu_notify_scope_dev
  - drivers/iommu/intel/iommu.c:dmar_iommu_notify_scope_dev
```
**Symbols:**

```
ffffffff81bfdb0b-ffffffff81bfdb5d: dmar_insert_dev_scope.cold (STB_LOCAL)
ffffffff8178e3e0-ffffffff8178e58b: dmar_insert_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dmar_insert_dev_scope(struct dmar_pci_notify_info *info, void *start, void *end, u16 segment, struct dmar_dev_scope *devices, int devices_cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:218
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_iommu_notify_scope_dev
  - drivers/iommu/intel/iommu.c:dmar_iommu_notify_scope_dev
  - drivers/iommu/intel/iommu.c:dmar_iommu_notify_scope_dev
```
**Symbols:**

```
ffffffff81cff0a0-ffffffff81cff0f2: dmar_insert_dev_scope.cold (STB_LOCAL)
ffffffff81815c70-ffffffff81815e1b: dmar_insert_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dmar_insert_dev_scope(struct dmar_pci_notify_info *info, void *start, void *end, u16 segment, struct dmar_dev_scope *devices, int devices_cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:215
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_iommu_notify_scope_dev
  - drivers/iommu/intel/iommu.c:dmar_iommu_notify_scope_dev
  - drivers/iommu/intel/iommu.c:dmar_iommu_notify_scope_dev
```
**Symbols:**

```
ffffffff81ec7873-ffffffff81ec78be: dmar_insert_dev_scope.cold (STB_LOCAL)
ffffffff81956af0-ffffffff81956cbe: dmar_insert_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dmar_insert_dev_scope(struct dmar_pci_notify_info *info, void *start, void *end, u16 segment, struct dmar_dev_scope *devices, int devices_cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff81abd960)
Location: drivers/iommu/intel/dmar.c:215
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_iommu_notify_scope_dev
  - drivers/iommu/intel/iommu.c:dmar_iommu_notify_scope_dev
  - drivers/iommu/intel/iommu.c:dmar_iommu_notify_scope_dev
```
**Symbols:**

```
ffffffff81abd960-ffffffff81abdb65: dmar_insert_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dmar_insert_dev_scope(struct dmar_pci_notify_info *info, void *start, void *end, u16 segment, struct dmar_dev_scope *devices, int devices_cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff81b0a2d0)
Location: drivers/iommu/intel/dmar.c:214
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_iommu_notify_scope_dev
  - drivers/iommu/intel/iommu.c:dmar_iommu_notify_scope_dev
  - drivers/iommu/intel/iommu.c:dmar_iommu_notify_scope_dev
```
**Symbols:**

```
ffffffff81b0a2d0-ffffffff81b0a4f7: dmar_insert_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dmar_insert_dev_scope(struct dmar_pci_notify_info *info, void *start, void *end, u16 segment, struct dmar_dev_scope *devices, int devices_cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff81b5e320)
Location: drivers/iommu/intel/dmar.c:214
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_iommu_notify_scope_dev
  - drivers/iommu/intel/iommu.c:dmar_iommu_notify_scope_dev
  - drivers/iommu/intel/iommu.c:dmar_iommu_notify_scope_dev
```
**Symbols:**

```
ffffffff81b5e320-ffffffff81b5e547: dmar_insert_dev_scope (STB_GLOBAL)
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
int dmar_insert_dev_scope(struct dmar_pci_notify_info *info, void *start, void *end, u16 segment, struct dmar_dev_scope *devices, int devices_cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:218
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_pci_bus_add_dev
  - drivers/iommu/intel-iommu.c:dmar_iommu_notify_scope_dev
  - drivers/iommu/intel-iommu.c:dmar_iommu_notify_scope_dev
```
**Symbols:**

```
ffffffff816addc1-ffffffff816ade18: dmar_insert_dev_scope.cold (STB_LOCAL)
ffffffff816acba0-ffffffff816acd50: dmar_insert_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int dmar_insert_dev_scope(struct dmar_pci_notify_info *info, void *start, void *end, u16 segment, struct dmar_dev_scope *devices, int devices_cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:218
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_pci_bus_add_dev
  - drivers/iommu/intel-iommu.c:dmar_iommu_notify_scope_dev
  - drivers/iommu/intel-iommu.c:dmar_iommu_notify_scope_dev
```
**Symbols:**

```
ffffffff8168b721-ffffffff8168b778: dmar_insert_dev_scope.cold (STB_LOCAL)
ffffffff8168a500-ffffffff8168a6b0: dmar_insert_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int dmar_insert_dev_scope(struct dmar_pci_notify_info *info, void *start, void *end, u16 segment, struct dmar_dev_scope *devices, int devices_cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:218
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_pci_bus_add_dev
  - drivers/iommu/intel-iommu.c:dmar_iommu_notify_scope_dev
  - drivers/iommu/intel-iommu.c:dmar_iommu_notify_scope_dev
```
**Symbols:**

```
ffffffff816dbfa1-ffffffff816dbff8: dmar_insert_dev_scope.cold (STB_LOCAL)
ffffffff816dad80-ffffffff816daf30: dmar_insert_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int dmar_insert_dev_scope(struct dmar_pci_notify_info *info, void *start, void *end, u16 segment, struct dmar_dev_scope *devices, int devices_cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:218
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_pci_bus_add_dev
  - drivers/iommu/intel-iommu.c:dmar_iommu_notify_scope_dev
  - drivers/iommu/intel-iommu.c:dmar_iommu_notify_scope_dev
```
**Symbols:**

```
ffffffff816f6571-ffffffff816f65c8: dmar_insert_dev_scope.cold (STB_LOCAL)
ffffffff816f5330-ffffffff816f54e0: dmar_insert_dev_scope (STB_GLOBAL)
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
