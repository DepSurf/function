# Function: <code>pciehp_get_adapter_status</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void pciehp_get_adapter_status(struct slot *slot, u8 *status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff814507c0)
Location: drivers/pci/hotplug/pciehp_hpc.c:416
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_isr
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_core.c:pciehp_resume
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
  - drivers/pci/hotplug/pciehp_ctrl.c:handle_surprise_event
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
```
**Symbols:**

```
ffffffff81450d70-ffffffff81450dd2: pciehp_get_adapter_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void pciehp_get_adapter_status(struct slot *slot, u8 *status);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8149cfc0)
Location: drivers/pci/hotplug/pciehp_hpc.c:416
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_isr
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_resume
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:handle_surprise_event
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
```
**Symbols:**

```
ffffffff8149d580-ffffffff8149d5e2: pciehp_get_adapter_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pciehp_get_adapter_status(struct slot *slot, u8 *status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff814bf170)
Location: drivers/pci/hotplug/pciehp_hpc.c:428
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_resume
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
```
**Symbols:**

```
ffffffff814bf170-ffffffff814bf1d2: pciehp_get_adapter_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pciehp_get_adapter_status(struct slot *slot, u8 *status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff814c98f0)
Location: drivers/pci/hotplug/pciehp_hpc.c:428
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_resume
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
```
**Symbols:**

```
ffffffff814c98f0-ffffffff814c9952: pciehp_get_adapter_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pciehp_get_adapter_status(struct slot *slot, u8 *status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81509ea0)
Location: drivers/pci/hotplug/pciehp_hpc.c:425
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_resume
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
```
**Symbols:**

```
ffffffff81509ea0-ffffffff81509f02: pciehp_get_adapter_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pciehp_get_adapter_status(struct slot *slot, u8 *status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8153ae00)
Location: drivers/pci/hotplug/pciehp_hpc.c:405
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_resume
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
  - drivers/pci/hotplug/pciehp_core.c:get_adapter_status
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
```
**Symbols:**

```
ffffffff8153ae00-ffffffff8153ae62: pciehp_get_adapter_status (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
</ul>
