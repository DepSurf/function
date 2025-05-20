# Function: <code>pciehp_is_native</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool pciehp_is_native(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff814c69b0)
Location: drivers/pci/pci-acpi.c:380
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffffffff814c69b0-ffffffff814c6a13: pciehp_is_native (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool pciehp_is_native(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff814d0920)
Location: drivers/pci/pci-acpi.c:379
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffffffff814d0920-ffffffff814d0983: pciehp_is_native (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool pciehp_is_native(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff81510b50)
Location: drivers/pci/pci-acpi.c:379
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffffffff81510b50-ffffffff81510bad: pciehp_is_native (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool pciehp_is_native(struct pci_dev *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff81545c20)
Location: drivers/pci/pci-acpi.c:378
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffffffff81545c20-ffffffff81545c97: pciehp_is_native (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool pciehp_is_native(struct pci_dev *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff81541e40)
Location: drivers/pci/pci-acpi.c:378
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffffffff81541e40-ffffffff81541eb4: pciehp_is_native (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool pciehp_is_native(struct pci_dev *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff81571990)
Location: drivers/pci/pci-acpi.c:445
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffffffff81571990-ffffffff81571a04: pciehp_is_native (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool pciehp_is_native(struct pci_dev *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff81592f10)
Location: drivers/pci/pci-acpi.c:791
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffffffff81592f10-ffffffff81592f84: pciehp_is_native (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool pciehp_is_native(struct pci_dev *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff816413a0)
Location: drivers/pci/pci-acpi.c:791
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffffffff816413a0-ffffffff81641413: pciehp_is_native (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool pciehp_is_native(struct pci_dev *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff81667890)
Location: drivers/pci/pci-acpi.c:791
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffffffff81667890-ffffffff81667903: pciehp_is_native (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool pciehp_is_native(struct pci_dev *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff81649da0)
Location: drivers/pci/pci-acpi.c:791
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffffffff81649da0-ffffffff81649e13: pciehp_is_native (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool pciehp_is_native(struct pci_dev *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-acpi.c (0)
Location: drivers/pci/pci-acpi.c:792
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffffffff81ce6b12-ffffffff81ce6b2d: pciehp_is_native.cold (STB_LOCAL)
ffffffff816bb870-ffffffff816bb8ec: pciehp_is_native (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool pciehp_is_native(struct pci_dev *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-acpi.c (0)
Location: drivers/pci/pci-acpi.c:792
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bridge_d3_possible
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffffffff81eada17-ffffffff81eada32: pciehp_is_native.cold (STB_LOCAL)
ffffffff817dfb60-ffffffff817dfbed: pciehp_is_native (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool pciehp_is_native(struct pci_dev *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-acpi.c (0)
Location: drivers/pci/pci-acpi.c:793
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bridge_d3_possible
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffffffff8208f69a-ffffffff8208f6b5: pciehp_is_native.cold (STB_LOCAL)
ffffffff819029e0-ffffffff81902a6d: pciehp_is_native (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool pciehp_is_native(struct pci_dev *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-acpi.c (0)
Location: drivers/pci/pci-acpi.c:793
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bridge_d3_possible
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffffffff8210f9fb-ffffffff8210fa16: pciehp_is_native.cold (STB_LOCAL)
ffffffff81946070-ffffffff819460fd: pciehp_is_native (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool pciehp_is_native(struct pci_dev *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-acpi.c (0)
Location: drivers/pci/pci-acpi.c:793
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_bridge_d3_possible
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffffffff821ed723-ffffffff821ed73e: pciehp_is_native.cold (STB_LOCAL)
ffffffff8198f3a0-ffffffff8198f42d: pciehp_is_native (STB_GLOBAL)
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
bool pciehp_is_native(struct pci_dev *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffff8000106f8f70)
Location: drivers/pci/pci-acpi.c:791
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffff8000106f8f70-ffff8000106f8ff8: pciehp_is_native (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (0)
Location: include/linux/pci_hotplug.h:101
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (0)
Location: include/linux/pci_hotplug.h:101
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (0)
Location: include/linux/pci_hotplug.h:101
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
bool pciehp_is_native(struct pci_dev *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff81586da0)
Location: drivers/pci/pci-acpi.c:791
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffffffff81586da0-ffffffff81586e14: pciehp_is_native (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool pciehp_is_native(struct pci_dev *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff81575b70)
Location: drivers/pci/pci-acpi.c:791
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffffffff81575b70-ffffffff81575be4: pciehp_is_native (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool pciehp_is_native(struct pci_dev *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff81586c60)
Location: drivers/pci/pci-acpi.c:791
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffffffff81586c60-ffffffff81586cd4: pciehp_is_native (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool pciehp_is_native(struct pci_dev *bridge);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-acpi.c (ffffffff815a1110)
Location: drivers/pci/pci-acpi.c:791
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffffffff815a1110-ffffffff815a1184: pciehp_is_native (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct pci_dev *bridge</code>
</li>
<li>
<b>Param removed. </b>
<code>struct pci_dev *pdev</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
