# Function: <code>pciehp_set_attention_status</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pciehp_set_attention_status(struct slot *slot, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81450e40)
Location: drivers/pci/hotplug/pciehp_hpc.c:434
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
  - drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler
  - drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler
  - drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
```
**Symbols:**

```
ffffffff81450e40-ffffffff81450ecb: pciehp_set_attention_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pciehp_set_attention_status(struct slot *slot, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8149d650)
Location: drivers/pci/hotplug/pciehp_hpc.c:434
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler
  - drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler
  - drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler
```
**Symbols:**

```
ffffffff8149d650-ffffffff8149d6db: pciehp_set_attention_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pciehp_set_attention_status(struct slot *slot, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff814bf270)
Location: drivers/pci/hotplug/pciehp_hpc.c:457
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler
  - drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler
  - drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler
```
**Symbols:**

```
ffffffff814bf270-ffffffff814bf2fb: pciehp_set_attention_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pciehp_set_attention_status(struct slot *slot, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff814c99f0)
Location: drivers/pci/hotplug/pciehp_hpc.c:457
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler
  - drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler
  - drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler
```
**Symbols:**

```
ffffffff814c99f0-ffffffff814c9a7b: pciehp_set_attention_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pciehp_set_attention_status(struct slot *slot, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81509fa0)
Location: drivers/pci/hotplug/pciehp_hpc.c:454
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler
  - drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler
  - drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler
```
**Symbols:**

```
ffffffff81509fa0-ffffffff8150a02b: pciehp_set_attention_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pciehp_set_attention_status(struct slot *slot, u8 value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8153af00)
Location: drivers/pci/hotplug/pciehp_hpc.c:434
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler
  - drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler
  - drivers/pci/hotplug/pciehp_ctrl.c:interrupt_event_handler
```
**Symbols:**

```
ffffffff8153af00-ffffffff8153af7c: pciehp_set_attention_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pciehp_set_attention_status(struct controller *ctrl, u8 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81552459)
Location: drivers/pci/hotplug/pciehp_hpc.c:419
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff81551b20-ffffffff81551b95: pciehp_set_attention_status.part.11 (STB_LOCAL)
ffffffff815521d0-ffffffff815521eb: pciehp_set_attention_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pciehp_set_attention_status(struct controller *ctrl, u8 value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81582e4b)
Location: drivers/pci/hotplug/pciehp_hpc.c:421
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
Direct callers:
  - drivers/pci/hotplug/pciehp_core.c:set_attention_status
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_presence_or_link_change
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_handle_button_press
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff81581a60-ffffffff81581ad4: pciehp_set_attention_status.part.0 (STB_LOCAL)
ffffffff81582120-ffffffff8158213b: pciehp_set_attention_status (STB_GLOBAL)
```
</details>
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
</ul>
