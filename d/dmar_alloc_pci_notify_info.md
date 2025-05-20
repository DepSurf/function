# Function: <code>dmar_alloc_pci_notify_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dmar_pci_notify_info *dmar_alloc_pci_notify_info(struct pci_dev *dev, long unsigned int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff81533b60)
Location: drivers/iommu/dmar.c:132
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_pci_bus_notifier
  - drivers/iommu/dmar.c:dmar_dev_scope_init
```
**Symbols:**

```
ffffffff81533b60-ffffffff81533ce5: dmar_alloc_pci_notify_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dmar_pci_notify_info *dmar_alloc_pci_notify_info(struct pci_dev *dev, long unsigned int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff815883f0)
Location: drivers/iommu/dmar.c:132
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/iommu/dmar.c:dmar_pci_bus_notifier
```
**Symbols:**

```
ffffffff815883f0-ffffffff81588575: dmar_alloc_pci_notify_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dmar_pci_notify_info *dmar_alloc_pci_notify_info(struct pci_dev *dev, long unsigned int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff815b5ab0)
Location: drivers/iommu/dmar.c:131
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/iommu/dmar.c:dmar_pci_bus_notifier
```
**Symbols:**

```
ffffffff815b5ab0-ffffffff815b5c35: dmar_alloc_pci_notify_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dmar_pci_notify_info *dmar_alloc_pci_notify_info(struct pci_dev *dev, long unsigned int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff815cb900)
Location: drivers/iommu/dmar.c:133
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/iommu/dmar.c:dmar_pci_bus_notifier
```
**Symbols:**

```
ffffffff815cb900-ffffffff815cba87: dmar_alloc_pci_notify_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dmar_pci_notify_info *dmar_alloc_pci_notify_info(struct pci_dev *dev, long unsigned int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff816326d0)
Location: drivers/iommu/dmar.c:133
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/iommu/dmar.c:dmar_pci_bus_notifier
```
**Symbols:**

```
ffffffff816326d0-ffffffff81632857: dmar_alloc_pci_notify_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct dmar_pci_notify_info *dmar_alloc_pci_notify_info(struct pci_dev *dev, long unsigned int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:133
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/iommu/dmar.c:dmar_pci_bus_notifier
```
**Symbols:**

```
ffffffff8166d980-ffffffff8166daf1: dmar_alloc_pci_notify_info (STB_LOCAL)
ffffffff8166f307-ffffffff8166f344: dmar_alloc_pci_notify_info.cold.24 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct dmar_pci_notify_info *dmar_alloc_pci_notify_info(struct pci_dev *dev, long unsigned int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:133
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/iommu/dmar.c:dmar_pci_bus_notifier
```
**Symbols:**

```
ffffffff8168bd90-ffffffff8168bf2a: dmar_alloc_pci_notify_info (STB_LOCAL)
ffffffff8168d867-ffffffff8168d8a4: dmar_alloc_pci_notify_info.cold.23 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct dmar_pci_notify_info *dmar_alloc_pci_notify_info(struct pci_dev *dev, long unsigned int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:122
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/iommu/dmar.c:dmar_pci_bus_notifier
```
**Symbols:**

```
ffffffff816c3b50-ffffffff816c3ce1: dmar_alloc_pci_notify_info (STB_LOCAL)
ffffffff816c534c-ffffffff816c5389: dmar_alloc_pci_notify_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct dmar_pci_notify_info *dmar_alloc_pci_notify_info(struct pci_dev *dev, long unsigned int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:123
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/iommu/dmar.c:dmar_pci_bus_notifier
```
**Symbols:**

```
ffffffff816e6a90-ffffffff816e6c3d: dmar_alloc_pci_notify_info (STB_LOCAL)
ffffffff816e8283-ffffffff816e82c0: dmar_alloc_pci_notify_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct dmar_pci_notify_info *dmar_alloc_pci_notify_info(struct pci_dev *dev, long unsigned int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:123
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_dev_scope_init
  - drivers/iommu/intel/dmar.c:dmar_pci_bus_notifier
```
**Symbols:**

```
ffffffff8179d320-ffffffff8179d4d6: dmar_alloc_pci_notify_info (STB_LOCAL)
ffffffff8179ee03-ffffffff8179ee40: dmar_alloc_pci_notify_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct dmar_pci_notify_info *dmar_alloc_pci_notify_info(struct pci_dev *dev, long unsigned int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:123
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_dev_scope_init
  - drivers/iommu/intel/dmar.c:dmar_pci_bus_notifier
```
**Symbols:**

```
ffffffff817ab050-ffffffff817ab1fd: dmar_alloc_pci_notify_info (STB_LOCAL)
ffffffff81c0c24b-ffffffff81c0c288: dmar_alloc_pci_notify_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct dmar_pci_notify_info *dmar_alloc_pci_notify_info(struct pci_dev *dev, long unsigned int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:124
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_dev_scope_init
  - drivers/iommu/intel/dmar.c:dmar_pci_bus_notifier
```
**Symbols:**

```
ffffffff8178d9c0-ffffffff8178db7e: dmar_alloc_pci_notify_info (STB_LOCAL)
ffffffff81bfda82-ffffffff81bfdac2: dmar_alloc_pci_notify_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dmar_pci_notify_info *dmar_alloc_pci_notify_info(struct pci_dev *dev, long unsigned int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff81815240)
Location: drivers/iommu/intel/dmar.c:125
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_dev_scope_init
  - drivers/iommu/intel/dmar.c:dmar_pci_bus_notifier
```
**Symbols:**

```
ffffffff81815240-ffffffff8181540b: dmar_alloc_pci_notify_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dmar_pci_notify_info *dmar_alloc_pci_notify_info(struct pci_dev *dev, long unsigned int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff81956490)
Location: drivers/iommu/intel/dmar.c:122
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_dev_scope_init
  - drivers/iommu/intel/dmar.c:dmar_pci_bus_notifier
```
**Symbols:**

```
ffffffff81956490-ffffffff8195665c: dmar_alloc_pci_notify_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dmar_pci_notify_info *dmar_alloc_pci_notify_info(struct pci_dev *dev, long unsigned int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff81abd290)
Location: drivers/iommu/intel/dmar.c:122
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_dev_scope_init
  - drivers/iommu/intel/dmar.c:dmar_pci_bus_notifier
```
**Symbols:**

```
ffffffff81abd290-ffffffff81abd45c: dmar_alloc_pci_notify_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dmar_pci_notify_info *dmar_alloc_pci_notify_info(struct pci_dev *dev, long unsigned int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff81b09c20)
Location: drivers/iommu/intel/dmar.c:123
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_dev_scope_init
  - drivers/iommu/intel/dmar.c:dmar_pci_bus_notifier
```
**Symbols:**

```
ffffffff81b09c20-ffffffff81b09d8d: dmar_alloc_pci_notify_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dmar_pci_notify_info *dmar_alloc_pci_notify_info(struct pci_dev *dev, long unsigned int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff81b5dc70)
Location: drivers/iommu/intel/dmar.c:123
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_dev_scope_init
  - drivers/iommu/intel/dmar.c:dmar_pci_bus_notifier
```
**Symbols:**

```
ffffffff81b5dc70-ffffffff81b5dddd: dmar_alloc_pci_notify_info (STB_LOCAL)
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
struct dmar_pci_notify_info *dmar_alloc_pci_notify_info(struct pci_dev *dev, long unsigned int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:123
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/iommu/dmar.c:dmar_pci_bus_notifier
```
**Symbols:**

```
ffffffff816ac570-ffffffff816ac71d: dmar_alloc_pci_notify_info (STB_LOCAL)
ffffffff816add63-ffffffff816adda0: dmar_alloc_pci_notify_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct dmar_pci_notify_info *dmar_alloc_pci_notify_info(struct pci_dev *dev, long unsigned int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:123
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/iommu/dmar.c:dmar_pci_bus_notifier
```
**Symbols:**

```
ffffffff81689ed0-ffffffff8168a07d: dmar_alloc_pci_notify_info (STB_LOCAL)
ffffffff8168b6c3-ffffffff8168b700: dmar_alloc_pci_notify_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct dmar_pci_notify_info *dmar_alloc_pci_notify_info(struct pci_dev *dev, long unsigned int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:123
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/iommu/dmar.c:dmar_pci_bus_notifier
```
**Symbols:**

```
ffffffff816da750-ffffffff816da8fd: dmar_alloc_pci_notify_info (STB_LOCAL)
ffffffff816dbf43-ffffffff816dbf80: dmar_alloc_pci_notify_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct dmar_pci_notify_info *dmar_alloc_pci_notify_info(struct pci_dev *dev, long unsigned int event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:123
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_dev_scope_init
  - drivers/iommu/dmar.c:dmar_pci_bus_notifier
```
**Symbols:**

```
ffffffff816f4d00-ffffffff816f4ead: dmar_alloc_pci_notify_info (STB_LOCAL)
ffffffff816f6513-ffffffff816f6550: dmar_alloc_pci_notify_info.cold (STB_LOCAL)
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
