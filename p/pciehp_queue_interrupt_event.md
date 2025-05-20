# Function: <code>pciehp_queue_interrupt_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pciehp_queue_interrupt_event(struct slot *p_slot, u32 event_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8144f7a0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:40
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_isr
```
**Symbols:**

```
ffffffff8144f7a0-ffffffff8144f830: pciehp_queue_interrupt_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pciehp_queue_interrupt_event(struct slot *p_slot, u32 event_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff8149bf40)
Location: drivers/pci/hotplug/pciehp_ctrl.c:40
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_isr
```
**Symbols:**

```
ffffffff8149bf40-ffffffff8149bfd0: pciehp_queue_interrupt_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pciehp_queue_interrupt_event(struct slot *p_slot, u32 event_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff814bdad0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:40
Inline: False
```
**Symbols:**

```
ffffffff814bdad0-ffffffff814bdb60: pciehp_queue_interrupt_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pciehp_queue_interrupt_event(struct slot *p_slot, u32 event_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff814c82b0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:40
Inline: False
```
**Symbols:**

```
ffffffff814c82b0-ffffffff814c8340: pciehp_queue_interrupt_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pciehp_queue_interrupt_event(struct slot *p_slot, u32 event_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff81508860)
Location: drivers/pci/hotplug/pciehp_ctrl.c:40
Inline: False
```
**Symbols:**

```
ffffffff81508860-ffffffff815088f0: pciehp_queue_interrupt_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pciehp_queue_interrupt_event(struct slot *p_slot, u32 event_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_ctrl.c (ffffffff815397a0)
Location: drivers/pci/hotplug/pciehp_ctrl.c:26
Inline: False
```
**Symbols:**

```
ffffffff815397a0-ffffffff81539830: pciehp_queue_interrupt_event (STB_GLOBAL)
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
