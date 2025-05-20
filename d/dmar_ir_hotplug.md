# Function: <code>dmar_ir_hotplug</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int dmar_ir_hotplug(struct dmar_drhd_unit *dmaru, bool insert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff8153dc70)
Location: drivers/iommu/intel_irq_remapping.c:1445
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_hp_remove_drhd
  - drivers/iommu/dmar.c:dmar_hp_add_drhd
```
**Symbols:**

```
ffffffff8153dc70-ffffffff8153ded4: dmar_ir_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int dmar_ir_hotplug(struct dmar_drhd_unit *dmaru, bool insert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff81592c40)
Location: drivers/iommu/intel_irq_remapping.c:1445
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_hp_remove_drhd
  - drivers/iommu/dmar.c:dmar_hp_add_drhd
```
**Symbols:**

```
ffffffff81592c40-ffffffff81592eb0: dmar_ir_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dmar_ir_hotplug(struct dmar_drhd_unit *dmaru, bool insert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff815c0500)
Location: drivers/iommu/intel_irq_remapping.c:1445
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_hp_remove_drhd
  - drivers/iommu/dmar.c:dmar_hp_add_drhd
```
**Symbols:**

```
ffffffff815c0500-ffffffff815c0770: dmar_ir_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dmar_ir_hotplug(struct dmar_drhd_unit *dmaru, bool insert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff815d6040)
Location: drivers/iommu/intel_irq_remapping.c:1453
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_hp_remove_drhd
  - drivers/iommu/dmar.c:dmar_hp_add_drhd
```
**Symbols:**

```
ffffffff815d6040-ffffffff815d62a6: dmar_ir_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dmar_ir_hotplug(struct dmar_drhd_unit *dmaru, bool insert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (ffffffff8163cdf0)
Location: drivers/iommu/intel_irq_remapping.c:1459
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_hp_remove_drhd
  - drivers/iommu/dmar.c:dmar_hp_add_drhd
```
**Symbols:**

```
ffffffff8163cdf0-ffffffff8163d056: dmar_ir_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int dmar_ir_hotplug(struct dmar_drhd_unit *dmaru, bool insert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (0)
Location: drivers/iommu/intel_irq_remapping.c:1459
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_hp_remove_drhd
  - drivers/iommu/dmar.c:dmar_hp_add_drhd
```
**Symbols:**

```
ffffffff8167860a-ffffffff816786a6: dmar_ir_hotplug.cold.22 (STB_LOCAL)
ffffffff816781a0-ffffffff8167836c: dmar_ir_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int dmar_ir_hotplug(struct dmar_drhd_unit *dmaru, bool insert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (0)
Location: drivers/iommu/intel_irq_remapping.c:1461
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_hp_remove_drhd
  - drivers/iommu/dmar.c:dmar_hp_add_drhd
```
**Symbols:**

```
ffffffff816976ea-ffffffff81697786: dmar_ir_hotplug.cold.22 (STB_LOCAL)
ffffffff81697280-ffffffff8169744c: dmar_ir_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int dmar_ir_hotplug(struct dmar_drhd_unit *dmaru, bool insert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (0)
Location: drivers/iommu/intel_irq_remapping.c:1486
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_hp_remove_drhd
  - drivers/iommu/dmar.c:dmar_hp_add_drhd
```
**Symbols:**

```
ffffffff816d009c-ffffffff816d013b: dmar_ir_hotplug.cold (STB_LOCAL)
ffffffff816cfbe0-ffffffff816cfdab: dmar_ir_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int dmar_ir_hotplug(struct dmar_drhd_unit *dmaru, bool insert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (0)
Location: drivers/iommu/intel_irq_remapping.c:1486
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_hp_remove_drhd
  - drivers/iommu/dmar.c:dmar_hp_add_drhd
```
**Symbols:**

```
ffffffff816f3ec1-ffffffff816f3f60: dmar_ir_hotplug.cold (STB_LOCAL)
ffffffff816f3a20-ffffffff816f3beb: dmar_ir_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dmar_ir_hotplug(struct dmar_drhd_unit *dmaru, bool insert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (ffffffff817ac210)
Location: drivers/iommu/intel/irq_remapping.c:1500
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_hp_remove_drhd
  - drivers/iommu/intel/dmar.c:dmar_hp_add_drhd
```
**Symbols:**

```
ffffffff817ac210-ffffffff817ac2cb: dmar_ir_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dmar_ir_hotplug(struct dmar_drhd_unit *dmaru, bool insert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (ffffffff817b8720)
Location: drivers/iommu/intel/irq_remapping.c:1470
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_hp_remove_drhd
  - drivers/iommu/intel/dmar.c:dmar_hp_add_drhd
```
**Symbols:**

```
ffffffff817b8720-ffffffff817b87db: dmar_ir_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int dmar_ir_hotplug(struct dmar_drhd_unit *dmaru, bool insert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (0)
Location: drivers/iommu/intel/irq_remapping.c:1479
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_hp_remove_drhd
  - drivers/iommu/intel/dmar.c:dmar_hp_add_drhd
```
**Symbols:**

```
ffffffff81bff705-ffffffff81bff766: dmar_ir_hotplug.cold (STB_LOCAL)
ffffffff8179b870-ffffffff8179ba17: dmar_ir_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dmar_ir_hotplug(struct dmar_drhd_unit *dmaru, bool insert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (0)
Location: drivers/iommu/intel/irq_remapping.c:1486
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_hp_remove_drhd
  - drivers/iommu/intel/dmar.c:dmar_hp_add_drhd
```
**Symbols:**

```
ffffffff81d01720-ffffffff81d01781: dmar_ir_hotplug.cold (STB_LOCAL)
ffffffff81824480-ffffffff81824627: dmar_ir_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dmar_ir_hotplug(struct dmar_drhd_unit *dmaru, bool insert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (0)
Location: drivers/iommu/intel/irq_remapping.c:1486
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_hp_remove_drhd
  - drivers/iommu/intel/dmar.c:dmar_hp_add_drhd
```
**Symbols:**

```
ffffffff81ec9c12-ffffffff81ec9c64: dmar_ir_hotplug.cold (STB_LOCAL)
ffffffff81964220-ffffffff819643d1: dmar_ir_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dmar_ir_hotplug(struct dmar_drhd_unit *dmaru, bool insert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (ffffffff81acd2b0)
Location: drivers/iommu/intel/irq_remapping.c:1487
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_hp_remove_drhd
  - drivers/iommu/intel/dmar.c:dmar_hp_add_drhd
```
**Symbols:**

```
ffffffff81acd2b0-ffffffff81acd4b0: dmar_ir_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dmar_ir_hotplug(struct dmar_drhd_unit *dmaru, bool insert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b19e20)
Location: drivers/iommu/intel/irq_remapping.c:1478
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_hp_remove_drhd
  - drivers/iommu/intel/dmar.c:dmar_hp_add_drhd
```
**Symbols:**

```
ffffffff81b19e20-ffffffff81b1a020: dmar_ir_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dmar_ir_hotplug(struct dmar_drhd_unit *dmaru, bool insert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b6fa80)
Location: drivers/iommu/intel/irq_remapping.c:1478
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_hp_remove_drhd
  - drivers/iommu/intel/dmar.c:dmar_hp_add_drhd
```
**Symbols:**

```
ffffffff81b6fa80-ffffffff81b6fb46: dmar_ir_hotplug (STB_GLOBAL)
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
int dmar_ir_hotplug(struct dmar_drhd_unit *dmaru, bool insert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (0)
Location: drivers/iommu/intel_irq_remapping.c:1486
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_hp_remove_drhd
  - drivers/iommu/dmar.c:dmar_hp_add_drhd
```
**Symbols:**

```
ffffffff816b96b1-ffffffff816b9750: dmar_ir_hotplug.cold (STB_LOCAL)
ffffffff816b9210-ffffffff816b93db: dmar_ir_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int dmar_ir_hotplug(struct dmar_drhd_unit *dmaru, bool insert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (0)
Location: drivers/iommu/intel_irq_remapping.c:1486
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_hp_remove_drhd
  - drivers/iommu/dmar.c:dmar_hp_add_drhd
```
**Symbols:**

```
ffffffff816972e6-ffffffff81697381: dmar_ir_hotplug.cold (STB_LOCAL)
ffffffff81696e50-ffffffff81697010: dmar_ir_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int dmar_ir_hotplug(struct dmar_drhd_unit *dmaru, bool insert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (0)
Location: drivers/iommu/intel_irq_remapping.c:1486
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_hp_remove_drhd
  - drivers/iommu/dmar.c:dmar_hp_add_drhd
```
**Symbols:**

```
ffffffff816e7b81-ffffffff816e7c20: dmar_ir_hotplug.cold (STB_LOCAL)
ffffffff816e76e0-ffffffff816e78ab: dmar_ir_hotplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int dmar_ir_hotplug(struct dmar_drhd_unit *dmaru, bool insert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel_irq_remapping.c (0)
Location: drivers/iommu/intel_irq_remapping.c:1486
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_hp_remove_drhd
  - drivers/iommu/dmar.c:dmar_hp_add_drhd
```
**Symbols:**

```
ffffffff81702281-ffffffff81702320: dmar_ir_hotplug.cold (STB_LOCAL)
ffffffff81701de0-ffffffff81701fab: dmar_ir_hotplug (STB_GLOBAL)
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
