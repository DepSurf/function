# Function: <code>dmar_device_hotplug</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int dmar_device_hotplug(acpi_handle handle, bool insert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff815338a0)
Location: drivers/iommu/dmar.c:1970
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_device_add
  - drivers/iommu/dmar.c:dmar_device_remove
```
**Symbols:**

```
ffffffff815338a0-ffffffff81533b57: dmar_device_hotplug (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int dmar_device_hotplug(acpi_handle handle, bool insert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff81588130)
Location: drivers/iommu/dmar.c:1991
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_device_remove
  - drivers/iommu/dmar.c:dmar_device_add
```
**Symbols:**

```
ffffffff81588130-ffffffff815883eb: dmar_device_hotplug (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dmar_device_hotplug(acpi_handle handle, bool insert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff815b57f0)
Location: drivers/iommu/dmar.c:1992
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_device_remove
  - drivers/iommu/dmar.c:dmar_device_add
```
**Symbols:**

```
ffffffff815b57f0-ffffffff815b5aab: dmar_device_hotplug (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dmar_device_hotplug(acpi_handle handle, bool insert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff815cb650)
Location: drivers/iommu/dmar.c:2000
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_device_remove
  - drivers/iommu/dmar.c:dmar_device_add
```
**Symbols:**

```
ffffffff815cb650-ffffffff815cb8fa: dmar_device_hotplug (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dmar_device_hotplug(acpi_handle handle, bool insert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff81632420)
Location: drivers/iommu/dmar.c:2004
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_device_remove
  - drivers/iommu/dmar.c:dmar_device_add
```
**Symbols:**

```
ffffffff81632420-ffffffff816326ca: dmar_device_hotplug (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int dmar_device_hotplug(acpi_handle handle, bool insert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:2002
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_device_remove
  - drivers/iommu/dmar.c:dmar_device_add
```
**Symbols:**

```
ffffffff8166d710-ffffffff8166d97e: dmar_device_hotplug (STB_LOCAL)
ffffffff8166f2e0-ffffffff8166f307: dmar_device_hotplug.cold.23 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int dmar_device_hotplug(acpi_handle handle, bool insert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:2033
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_device_remove
  - drivers/iommu/dmar.c:dmar_device_add
```
**Symbols:**

```
ffffffff8168bb20-ffffffff8168bd8e: dmar_device_hotplug (STB_LOCAL)
ffffffff8168d840-ffffffff8168d867: dmar_device_hotplug.cold.22 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int dmar_device_hotplug(acpi_handle handle, bool insert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:2022
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_device_remove
  - drivers/iommu/dmar.c:dmar_device_add
```
**Symbols:**

```
ffffffff816c3510-ffffffff816c3788: dmar_device_hotplug (STB_LOCAL)
ffffffff816c5232-ffffffff816c5283: dmar_device_hotplug.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int dmar_device_hotplug(acpi_handle handle, bool insert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:2100
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_device_remove
  - drivers/iommu/dmar.c:dmar_device_add
```
**Symbols:**

```
ffffffff816e6460-ffffffff816e66dd: dmar_device_hotplug (STB_LOCAL)
ffffffff816e8192-ffffffff816e81ba: dmar_device_hotplug.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int dmar_device_hotplug(acpi_handle handle, bool insert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:2216
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_device_remove
  - drivers/iommu/intel/dmar.c:dmar_device_add
```
**Symbols:**

```
ffffffff8179cb40-ffffffff8179cc27: dmar_device_hotplug (STB_LOCAL)
ffffffff8179ec9e-ffffffff8179ecb5: dmar_device_hotplug.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int dmar_device_hotplug(acpi_handle handle, bool insert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:2254
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_device_remove
  - drivers/iommu/intel/dmar.c:dmar_device_add
```
**Symbols:**

```
ffffffff817aa810-ffffffff817aa8f7: dmar_device_hotplug (STB_LOCAL)
ffffffff81c0c0c9-ffffffff81c0c0e0: dmar_device_hotplug.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int dmar_device_hotplug(acpi_handle handle, bool insert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:2325
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_device_remove
  - drivers/iommu/intel/dmar.c:dmar_device_add
```
**Symbols:**

```
ffffffff8178db80-ffffffff8178df98: dmar_device_hotplug (STB_LOCAL)
ffffffff81bfdac2-ffffffff81bfdaea: dmar_device_hotplug.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dmar_device_hotplug(acpi_handle handle, bool insert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:2361
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_device_remove
  - drivers/iommu/intel/dmar.c:dmar_device_add
```
**Symbols:**

```
ffffffff81815410-ffffffff81815828: dmar_device_hotplug (STB_LOCAL)
ffffffff81cff057-ffffffff81cff07f: dmar_device_hotplug.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dmar_device_hotplug(acpi_handle handle, bool insert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:2362
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_device_remove
  - drivers/iommu/intel/dmar.c:dmar_device_add
```
**Symbols:**

```
ffffffff81955ac0-ffffffff81955d50: dmar_device_hotplug (STB_LOCAL)
ffffffff81ec764e-ffffffff81ec7675: dmar_device_hotplug.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dmar_device_hotplug(acpi_handle handle, bool insert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff81abc5e0)
Location: drivers/iommu/intel/dmar.c:2351
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_device_remove
  - drivers/iommu/intel/dmar.c:dmar_device_add
```
**Symbols:**

```
ffffffff81abc5e0-ffffffff81abc897: dmar_device_hotplug (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dmar_device_hotplug(acpi_handle handle, bool insert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff81b08ed0)
Location: drivers/iommu/intel/dmar.c:2374
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_device_remove
  - drivers/iommu/intel/dmar.c:dmar_device_add
```
**Symbols:**

```
ffffffff81b08ed0-ffffffff81b09187: dmar_device_hotplug (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dmar_device_hotplug(acpi_handle handle, bool insert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff81b5cef0)
Location: drivers/iommu/intel/dmar.c:2392
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_device_remove
  - drivers/iommu/intel/dmar.c:dmar_device_add
```
**Symbols:**

```
ffffffff81b5cef0-ffffffff81b5d1a7: dmar_device_hotplug (STB_LOCAL)
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
int dmar_device_hotplug(acpi_handle handle, bool insert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:2100
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_device_remove
  - drivers/iommu/dmar.c:dmar_device_add
```
**Symbols:**

```
ffffffff816abf40-ffffffff816ac1bd: dmar_device_hotplug (STB_LOCAL)
ffffffff816adc72-ffffffff816adc9a: dmar_device_hotplug.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int dmar_device_hotplug(acpi_handle handle, bool insert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:2100
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_device_remove
  - drivers/iommu/dmar.c:dmar_device_add
```
**Symbols:**

```
ffffffff816898a0-ffffffff81689b1d: dmar_device_hotplug (STB_LOCAL)
ffffffff8168b5d2-ffffffff8168b5fa: dmar_device_hotplug.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int dmar_device_hotplug(acpi_handle handle, bool insert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:2100
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_device_remove
  - drivers/iommu/dmar.c:dmar_device_add
```
**Symbols:**

```
ffffffff816da120-ffffffff816da39d: dmar_device_hotplug (STB_LOCAL)
ffffffff816dbe52-ffffffff816dbe7a: dmar_device_hotplug.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int dmar_device_hotplug(acpi_handle handle, bool insert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:2100
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_device_remove
  - drivers/iommu/dmar.c:dmar_device_add
```
**Symbols:**

```
ffffffff816f46d0-ffffffff816f494d: dmar_device_hotplug (STB_LOCAL)
ffffffff816f6422-ffffffff816f644a: dmar_device_hotplug.cold (STB_LOCAL)
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
