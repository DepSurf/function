# Function: <code>pciehp_card_present_or_link_active</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool pciehp_card_present_or_link_active(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815520a0)
Location: drivers/pci/hotplug/pciehp_hpc.c:392
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff815520a0-ffffffff81552105: pciehp_card_present_or_link_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool pciehp_card_present_or_link_active(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81581ff0)
Location: drivers/pci/hotplug/pciehp_hpc.c:394
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff81581ff0-ffffffff81582057: pciehp_card_present_or_link_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pciehp_card_present_or_link_active(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815a3a90)
Location: drivers/pci/hotplug/pciehp_hpc.c:425
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff815a3a90-ffffffff815a3ab3: pciehp_card_present_or_link_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pciehp_card_present_or_link_active(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8164c670)
Location: drivers/pci/hotplug/pciehp_hpc.c:461
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff8164c670-ffffffff8164c6e8: pciehp_card_present_or_link_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pciehp_card_present_or_link_active(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff816709c0)
Location: drivers/pci/hotplug/pciehp_hpc.c:464
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff816709c0-ffffffff81670a38: pciehp_card_present_or_link_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pciehp_card_present_or_link_active(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81652e80)
Location: drivers/pci/hotplug/pciehp_hpc.c:464
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff81652e80-ffffffff81652ef8: pciehp_card_present_or_link_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pciehp_card_present_or_link_active(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff816c4bf0)
Location: drivers/pci/hotplug/pciehp_hpc.c:464
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff816c4bf0-ffffffff816c4c68: pciehp_card_present_or_link_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pciehp_card_present_or_link_active(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff817ea8a0)
Location: drivers/pci/hotplug/pciehp_hpc.c:466
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff817ea8a0-ffffffff817ea927: pciehp_card_present_or_link_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pciehp_card_present_or_link_active(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81910a90)
Location: drivers/pci/hotplug/pciehp_hpc.c:466
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff81910a90-ffffffff81910b17: pciehp_card_present_or_link_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pciehp_card_present_or_link_active(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff819541b0)
Location: drivers/pci/hotplug/pciehp_hpc.c:460
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff819541b0-ffffffff81954237: pciehp_card_present_or_link_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pciehp_card_present_or_link_active(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8199d640)
Location: drivers/pci/hotplug/pciehp_hpc.c:461
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff8199d640-ffffffff8199d6c7: pciehp_card_present_or_link_active (STB_GLOBAL)
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
int pciehp_card_present_or_link_active(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffff80001070c5b8)
Location: drivers/pci/hotplug/pciehp_hpc.c:425
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffff80001070c5b8-ffff80001070c5f0: pciehp_card_present_or_link_active (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pciehp_card_present_or_link_active(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffe0004d8eae)
Location: drivers/pci/hotplug/pciehp_hpc.c:425
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffe0004d8eae-ffffffe0004d8ee4: pciehp_card_present_or_link_active (STB_GLOBAL)
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
int pciehp_card_present_or_link_active(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815972a0)
Location: drivers/pci/hotplug/pciehp_hpc.c:425
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff815972a0-ffffffff815972c3: pciehp_card_present_or_link_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pciehp_card_present_or_link_active(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81586430)
Location: drivers/pci/hotplug/pciehp_hpc.c:425
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff81586430-ffffffff81586453: pciehp_card_present_or_link_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pciehp_card_present_or_link_active(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815977e0)
Location: drivers/pci/hotplug/pciehp_hpc.c:425
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff815977e0-ffffffff81597803: pciehp_card_present_or_link_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pciehp_card_present_or_link_active(struct controller *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815b1c20)
Location: drivers/pci/hotplug/pciehp_hpc.c:425
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_check_presence
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff815b1c20-ffffffff815b1c43: pciehp_card_present_or_link_active (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
