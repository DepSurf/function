# Function: <code>pciehp_get_power_status</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pciehp_get_power_status(struct slot *slot, u8 *status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81450c40)
Location: drivers/pci/hotplug/pciehp_hpc.c:384
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
  - drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
```
**Symbols:**

```
ffffffff81450c40-ffffffff81450cf6: pciehp_get_power_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pciehp_get_power_status(struct slot *slot, u8 *status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8149d450)
Location: drivers/pci/hotplug/pciehp_hpc.c:384
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler
```
**Symbols:**

```
ffffffff8149d450-ffffffff8149d506: pciehp_get_power_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pciehp_get_power_status(struct slot *slot, u8 *status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff814bf040)
Location: drivers/pci/hotplug/pciehp_hpc.c:396
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler
```
**Symbols:**

```
ffffffff814bf040-ffffffff814bf0f6: pciehp_get_power_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pciehp_get_power_status(struct slot *slot, u8 *status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff814c97c0)
Location: drivers/pci/hotplug/pciehp_hpc.c:396
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler
```
**Symbols:**

```
ffffffff814c97c0-ffffffff814c9876: pciehp_get_power_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pciehp_get_power_status(struct slot *slot, u8 *status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81509d70)
Location: drivers/pci/hotplug/pciehp_hpc.c:393
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler
```
**Symbols:**

```
ffffffff81509d70-ffffffff81509e26: pciehp_get_power_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pciehp_get_power_status(struct slot *slot, u8 *status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8153acd0)
Location: drivers/pci/hotplug/pciehp_hpc.c:373
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler
```
**Symbols:**

```
ffffffff8153acd0-ffffffff8153ad84: pciehp_get_power_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pciehp_get_power_status(struct controller *ctrl, u8 *status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81551f30)
Location: drivers/pci/hotplug/pciehp_hpc.c:343
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff81551f30-ffffffff81551fe0: pciehp_get_power_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pciehp_get_power_status(struct controller *ctrl, u8 *status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81581e90)
Location: drivers/pci/hotplug/pciehp_hpc.c:345
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff81581e90-ffffffff81581f2c: pciehp_get_power_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pciehp_get_power_status(struct controller *ctrl, u8 *status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815a3920)
Location: drivers/pci/hotplug/pciehp_hpc.c:357
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff815a3920-ffffffff815a39bc: pciehp_get_power_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pciehp_get_power_status(struct controller *ctrl, u8 *status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8164c500)
Location: drivers/pci/hotplug/pciehp_hpc.c:393
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff8164c500-ffffffff8164c59a: pciehp_get_power_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pciehp_get_power_status(struct controller *ctrl, u8 *status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81670850)
Location: drivers/pci/hotplug/pciehp_hpc.c:396
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff81670850-ffffffff816708ea: pciehp_get_power_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pciehp_get_power_status(struct controller *ctrl, u8 *status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81652d10)
Location: drivers/pci/hotplug/pciehp_hpc.c:396
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff81652d10-ffffffff81652daa: pciehp_get_power_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pciehp_get_power_status(struct controller *ctrl, u8 *status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff816c4a80)
Location: drivers/pci/hotplug/pciehp_hpc.c:396
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff816c4a80-ffffffff816c4b17: pciehp_get_power_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pciehp_get_power_status(struct controller *ctrl, u8 *status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff817ea6f0)
Location: drivers/pci/hotplug/pciehp_hpc.c:398
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff817ea6f0-ffffffff817ea7a1: pciehp_get_power_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pciehp_get_power_status(struct controller *ctrl, u8 *status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff819108b0)
Location: drivers/pci/hotplug/pciehp_hpc.c:398
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff819108b0-ffffffff81910961: pciehp_get_power_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pciehp_get_power_status(struct controller *ctrl, u8 *status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81953fd0)
Location: drivers/pci/hotplug/pciehp_hpc.c:392
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff81953fd0-ffffffff8195408a: pciehp_get_power_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pciehp_get_power_status(struct controller *ctrl, u8 *status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8199d460)
Location: drivers/pci/hotplug/pciehp_hpc.c:393
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff8199d460-ffffffff8199d51a: pciehp_get_power_status (STB_GLOBAL)
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
void pciehp_get_power_status(struct controller *ctrl, u8 *status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffff80001070c3f8)
Location: drivers/pci/hotplug/pciehp_hpc.c:357
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffff80001070c3f8-ffff80001070c4b8: pciehp_get_power_status (STB_GLOBAL)
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
void pciehp_get_power_status(struct controller *ctrl, u8 *status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffe0004d8d7a)
Location: drivers/pci/hotplug/pciehp_hpc.c:357
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffe0004d8d7a-ffffffe0004d8e16: pciehp_get_power_status (STB_GLOBAL)
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
void pciehp_get_power_status(struct controller *ctrl, u8 *status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81597130)
Location: drivers/pci/hotplug/pciehp_hpc.c:357
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff81597130-ffffffff815971cc: pciehp_get_power_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pciehp_get_power_status(struct controller *ctrl, u8 *status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815862c0)
Location: drivers/pci/hotplug/pciehp_hpc.c:357
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff815862c0-ffffffff8158635c: pciehp_get_power_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pciehp_get_power_status(struct controller *ctrl, u8 *status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81597670)
Location: drivers/pci/hotplug/pciehp_hpc.c:357
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff81597670-ffffffff8159770c: pciehp_get_power_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pciehp_get_power_status(struct controller *ctrl, u8 *status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815b1ab0)
Location: drivers/pci/hotplug/pciehp_hpc.c:357
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:get_power_status
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
**Symbols:**

```
ffffffff815b1ab0-ffffffff815b1b4c: pciehp_get_power_status (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct controller *ctrl</code>
</li>
<li>
<b>Param removed. </b>
<code>struct slot *slot</code>
</li>
</ul>
</details>
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
