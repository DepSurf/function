# Function: <code>dmar_remove_dev_scope</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dmar_remove_dev_scope(struct dmar_pci_notify_info *info, u16 segment, struct dmar_dev_scope *devices, int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff815336c0)
Location: drivers/iommu/dmar.c:265
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_pci_bus_notifier
Direct callers:
  - drivers/iommu/dmar.c:dmar_pci_bus_notifier
  - drivers/iommu/intel-iommu.c:dmar_iommu_notify_scope_dev
  - drivers/iommu/intel-iommu.c:dmar_iommu_notify_scope_dev
```
**Symbols:**

```
ffffffff815336c0-ffffffff81533733: dmar_remove_dev_scope.part.10 (STB_LOCAL)
ffffffff81534890-ffffffff815348ae: dmar_remove_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dmar_remove_dev_scope(struct dmar_pci_notify_info *info, u16 segment, struct dmar_dev_scope *devices, int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff81589133)
Location: drivers/iommu/dmar.c:277
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_pci_bus_notifier
Direct callers:
  - drivers/iommu/dmar.c:dmar_pci_bus_notifier
  - drivers/iommu/intel-iommu.c:dmar_iommu_notify_scope_dev
  - drivers/iommu/intel-iommu.c:dmar_iommu_notify_scope_dev
```
**Symbols:**

```
ffffffff81587d10-ffffffff81587d78: dmar_remove_dev_scope.part.11 (STB_LOCAL)
ffffffff81589160-ffffffff8158917e: dmar_remove_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dmar_remove_dev_scope(struct dmar_pci_notify_info *info, u16 segment, struct dmar_dev_scope *devices, int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff815b67f3)
Location: drivers/iommu/dmar.c:276
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_pci_bus_notifier
Direct callers:
  - drivers/iommu/dmar.c:dmar_pci_bus_notifier
  - drivers/iommu/intel-iommu.c:dmar_iommu_notify_scope_dev
  - drivers/iommu/intel-iommu.c:dmar_iommu_notify_scope_dev
```
**Symbols:**

```
ffffffff815b53d0-ffffffff815b5438: dmar_remove_dev_scope.part.13 (STB_LOCAL)
ffffffff815b6820-ffffffff815b683e: dmar_remove_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dmar_remove_dev_scope(struct dmar_pci_notify_info *info, u16 segment, struct dmar_dev_scope *devices, int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff815cc633)
Location: drivers/iommu/dmar.c:278
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_pci_bus_notifier
Direct callers:
  - drivers/iommu/dmar.c:dmar_pci_bus_notifier
  - drivers/iommu/intel-iommu.c:dmar_iommu_notify_scope_dev
  - drivers/iommu/intel-iommu.c:dmar_iommu_notify_scope_dev
```
**Symbols:**

```
ffffffff815cb250-ffffffff815cb2b8: dmar_remove_dev_scope.part.15 (STB_LOCAL)
ffffffff815cc660-ffffffff815cc67e: dmar_remove_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dmar_remove_dev_scope(struct dmar_pci_notify_info *info, u16 segment, struct dmar_dev_scope *devices, int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff81633403)
Location: drivers/iommu/dmar.c:278
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_pci_bus_notifier
Direct callers:
  - drivers/iommu/dmar.c:dmar_pci_bus_notifier
  - drivers/iommu/intel-iommu.c:dmar_iommu_notify_scope_dev
  - drivers/iommu/intel-iommu.c:dmar_iommu_notify_scope_dev
```
**Symbols:**

```
ffffffff81632020-ffffffff81632088: dmar_remove_dev_scope.part.14 (STB_LOCAL)
ffffffff81633430-ffffffff8163344e: dmar_remove_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dmar_remove_dev_scope(struct dmar_pci_notify_info *info, u16 segment, struct dmar_dev_scope *devices, int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff8166e5d5)
Location: drivers/iommu/dmar.c:278
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_pci_bus_notifier
Direct callers:
  - drivers/iommu/dmar.c:dmar_pci_bus_notifier
  - drivers/iommu/intel-iommu.c:dmar_iommu_notify_scope_dev
  - drivers/iommu/intel-iommu.c:dmar_iommu_notify_scope_dev
```
**Symbols:**

```
ffffffff8166d3f0-ffffffff8166d458: dmar_remove_dev_scope.part.14 (STB_LOCAL)
ffffffff8166e610-ffffffff8166e62e: dmar_remove_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dmar_remove_dev_scope(struct dmar_pci_notify_info *info, u16 segment, struct dmar_dev_scope *devices, int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff8168ca05)
Location: drivers/iommu/dmar.c:278
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_pci_bus_notifier
Direct callers:
  - drivers/iommu/dmar.c:dmar_pci_bus_notifier
  - drivers/iommu/intel-iommu.c:dmar_iommu_notify_scope_dev
  - drivers/iommu/intel-iommu.c:dmar_iommu_notify_scope_dev
```
**Symbols:**

```
ffffffff8168b800-ffffffff8168b868: dmar_remove_dev_scope.part.13 (STB_LOCAL)
ffffffff8168ca40-ffffffff8168ca5e: dmar_remove_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dmar_remove_dev_scope(struct dmar_pci_notify_info *info, u16 segment, struct dmar_dev_scope *devices, int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff816c4452)
Location: drivers/iommu/dmar.c:267
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_pci_bus_notifier
Direct callers:
  - drivers/iommu/dmar.c:dmar_pci_bus_notifier
  - drivers/iommu/intel-iommu.c:dmar_iommu_notify_scope_dev
  - drivers/iommu/intel-iommu.c:dmar_iommu_notify_scope_dev
```
**Symbols:**

```
ffffffff816c31f0-ffffffff816c325b: dmar_remove_dev_scope.part.0 (STB_LOCAL)
ffffffff816c4490-ffffffff816c44ae: dmar_remove_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dmar_remove_dev_scope(struct dmar_pci_notify_info *info, u16 segment, struct dmar_dev_scope *devices, int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff816e73a2)
Location: drivers/iommu/dmar.c:275
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_pci_bus_notifier
Direct callers:
  - drivers/iommu/dmar.c:dmar_pci_bus_notifier
  - drivers/iommu/intel-iommu.c:dmar_iommu_notify_scope_dev
  - drivers/iommu/intel-iommu.c:dmar_iommu_notify_scope_dev
```
**Symbols:**

```
ffffffff816e6130-ffffffff816e619b: dmar_remove_dev_scope.part.0 (STB_LOCAL)
ffffffff816e73e0-ffffffff816e73fe: dmar_remove_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int dmar_remove_dev_scope(struct dmar_pci_notify_info *info, u16 segment, struct dmar_dev_scope *devices, int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff8179db5a)
Location: drivers/iommu/intel/dmar.c:275
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_pci_bus_notifier
  - drivers/iommu/intel/dmar.c:dmar_pci_bus_notifier
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_iommu_notify_scope_dev
  - drivers/iommu/intel/iommu.c:dmar_iommu_notify_scope_dev
```
**Symbols:**

```
ffffffff8179dbe0-ffffffff8179dc5a: dmar_remove_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int dmar_remove_dev_scope(struct dmar_pci_notify_info *info, u16 segment, struct dmar_dev_scope *devices, int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff817ab8a6)
Location: drivers/iommu/intel/dmar.c:275
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_pci_bus_notifier
  - drivers/iommu/intel/dmar.c:dmar_pci_bus_notifier
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_iommu_notify_scope_dev
  - drivers/iommu/intel/iommu.c:dmar_iommu_notify_scope_dev
```
**Symbols:**

```
ffffffff817ab920-ffffffff817ab99a: dmar_remove_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int dmar_remove_dev_scope(struct dmar_pci_notify_info *info, u16 segment, struct dmar_dev_scope *devices, int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff8178e699)
Location: drivers/iommu/intel/dmar.c:276
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_pci_bus_notifier
  - drivers/iommu/intel/dmar.c:dmar_pci_bus_notifier
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_iommu_notify_scope_dev
  - drivers/iommu/intel/iommu.c:dmar_iommu_notify_scope_dev
  - drivers/iommu/intel/iommu.c:dmar_iommu_notify_scope_dev
```
**Symbols:**

```
ffffffff8178e780-ffffffff8178e7f5: dmar_remove_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int dmar_remove_dev_scope(struct dmar_pci_notify_info *info, u16 segment, struct dmar_dev_scope *devices, int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff81815f29)
Location: drivers/iommu/intel/dmar.c:275
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_pci_bus_notifier
  - drivers/iommu/intel/dmar.c:dmar_pci_bus_notifier
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_iommu_notify_scope_dev
  - drivers/iommu/intel/iommu.c:dmar_iommu_notify_scope_dev
  - drivers/iommu/intel/iommu.c:dmar_iommu_notify_scope_dev
```
**Symbols:**

```
ffffffff81816010-ffffffff81816085: dmar_remove_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int dmar_remove_dev_scope(struct dmar_pci_notify_info *info, u16 segment, struct dmar_dev_scope *devices, int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff81956dec)
Location: drivers/iommu/intel/dmar.c:272
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_pci_bus_notifier
  - drivers/iommu/intel/dmar.c:dmar_pci_bus_notifier
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_iommu_notify_scope_dev
  - drivers/iommu/intel/iommu.c:dmar_iommu_notify_scope_dev
  - drivers/iommu/intel/iommu.c:dmar_iommu_notify_scope_dev
```
**Symbols:**

```
ffffffff81956ec0-ffffffff81956f4b: dmar_remove_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int dmar_remove_dev_scope(struct dmar_pci_notify_info *info, u16 segment, struct dmar_dev_scope *devices, int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff81abdcbc)
Location: drivers/iommu/intel/dmar.c:272
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_pci_bus_notifier
  - drivers/iommu/intel/dmar.c:dmar_pci_bus_notifier
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_iommu_notify_scope_dev
  - drivers/iommu/intel/iommu.c:dmar_iommu_notify_scope_dev
  - drivers/iommu/intel/iommu.c:dmar_iommu_notify_scope_dev
```
**Symbols:**

```
ffffffff81abdda0-ffffffff81abde2b: dmar_remove_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int dmar_remove_dev_scope(struct dmar_pci_notify_info *info, u16 segment, struct dmar_dev_scope *devices, int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff81b0a647)
Location: drivers/iommu/intel/dmar.c:272
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_pci_bus_notifier
  - drivers/iommu/intel/dmar.c:dmar_pci_bus_notifier
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_iommu_notify_scope_dev
  - drivers/iommu/intel/iommu.c:dmar_iommu_notify_scope_dev
  - drivers/iommu/intel/iommu.c:dmar_iommu_notify_scope_dev
```
**Symbols:**

```
ffffffff81b0a730-ffffffff81b0a7bb: dmar_remove_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int dmar_remove_dev_scope(struct dmar_pci_notify_info *info, u16 segment, struct dmar_dev_scope *devices, int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff81b5e697)
Location: drivers/iommu/intel/dmar.c:272
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_pci_bus_notifier
  - drivers/iommu/intel/dmar.c:dmar_pci_bus_notifier
Direct callers:
  - drivers/iommu/intel/iommu.c:dmar_iommu_notify_scope_dev
  - drivers/iommu/intel/iommu.c:dmar_iommu_notify_scope_dev
  - drivers/iommu/intel/iommu.c:dmar_iommu_notify_scope_dev
```
**Symbols:**

```
ffffffff81b5e780-ffffffff81b5e80b: dmar_remove_dev_scope (STB_GLOBAL)
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
int dmar_remove_dev_scope(struct dmar_pci_notify_info *info, u16 segment, struct dmar_dev_scope *devices, int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff816ace82)
Location: drivers/iommu/dmar.c:275
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_pci_bus_notifier
Direct callers:
  - drivers/iommu/dmar.c:dmar_pci_bus_notifier
  - drivers/iommu/intel-iommu.c:dmar_iommu_notify_scope_dev
  - drivers/iommu/intel-iommu.c:dmar_iommu_notify_scope_dev
```
**Symbols:**

```
ffffffff816abc10-ffffffff816abc7b: dmar_remove_dev_scope.part.0 (STB_LOCAL)
ffffffff816acec0-ffffffff816acede: dmar_remove_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dmar_remove_dev_scope(struct dmar_pci_notify_info *info, u16 segment, struct dmar_dev_scope *devices, int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff8168a7e2)
Location: drivers/iommu/dmar.c:275
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_pci_bus_notifier
Direct callers:
  - drivers/iommu/dmar.c:dmar_pci_bus_notifier
  - drivers/iommu/intel-iommu.c:dmar_iommu_notify_scope_dev
  - drivers/iommu/intel-iommu.c:dmar_iommu_notify_scope_dev
```
**Symbols:**

```
ffffffff81689570-ffffffff816895db: dmar_remove_dev_scope.part.0 (STB_LOCAL)
ffffffff8168a820-ffffffff8168a83e: dmar_remove_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dmar_remove_dev_scope(struct dmar_pci_notify_info *info, u16 segment, struct dmar_dev_scope *devices, int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff816db062)
Location: drivers/iommu/dmar.c:275
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_pci_bus_notifier
Direct callers:
  - drivers/iommu/dmar.c:dmar_pci_bus_notifier
  - drivers/iommu/intel-iommu.c:dmar_iommu_notify_scope_dev
  - drivers/iommu/intel-iommu.c:dmar_iommu_notify_scope_dev
```
**Symbols:**

```
ffffffff816d9df0-ffffffff816d9e5b: dmar_remove_dev_scope.part.0 (STB_LOCAL)
ffffffff816db0a0-ffffffff816db0be: dmar_remove_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dmar_remove_dev_scope(struct dmar_pci_notify_info *info, u16 segment, struct dmar_dev_scope *devices, int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff816f5612)
Location: drivers/iommu/dmar.c:275
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_pci_bus_notifier
Direct callers:
  - drivers/iommu/dmar.c:dmar_pci_bus_notifier
  - drivers/iommu/intel-iommu.c:dmar_iommu_notify_scope_dev
  - drivers/iommu/intel-iommu.c:dmar_iommu_notify_scope_dev
```
**Symbols:**

```
ffffffff816f43a0-ffffffff816f440b: dmar_remove_dev_scope.part.0 (STB_LOCAL)
ffffffff816f5650-ffffffff816f566e: dmar_remove_dev_scope (STB_GLOBAL)
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
