# Function: <code>pci_hp_change_slot_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pci_hp_change_slot_info(struct hotplug_slot *slot, struct hotplug_slot_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff8144bf10)
Location: drivers/pci/hotplug/pci_hotplug_core.c:517
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
```
**Symbols:**

```
ffffffff8144bf10-ffffffff8144bf36: pci_hp_change_slot_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pci_hp_change_slot_info(struct hotplug_slot *slot, struct hotplug_slot_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff81498620)
Location: drivers/pci/hotplug/pci_hotplug_core.c:515
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
```
**Symbols:**

```
ffffffff81498620-ffffffff81498646: pci_hp_change_slot_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pci_hp_change_slot_info(struct hotplug_slot *slot, struct hotplug_slot_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff814ba210)
Location: drivers/pci/hotplug/pci_hotplug_core.c:512
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
```
**Symbols:**

```
ffffffff814ba210-ffffffff814ba236: pci_hp_change_slot_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pci_hp_change_slot_info(struct hotplug_slot *slot, struct hotplug_slot_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff814c5560)
Location: drivers/pci/hotplug/pci_hotplug_core.c:512
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:update_adapter_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:update_latch_status
```
**Symbols:**

```
ffffffff814c5560-ffffffff814c5586: pci_hp_change_slot_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pci_hp_change_slot_info(struct hotplug_slot *slot, struct hotplug_slot_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff81505af0)
Location: drivers/pci/hotplug/pci_hotplug_core.c:512
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:update_adapter_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:update_latch_status
```
**Symbols:**

```
ffffffff81505af0-ffffffff81505b16: pci_hp_change_slot_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_hp_change_slot_info(struct hotplug_slot *slot, struct hotplug_slot_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pci_hotplug_core.c (ffffffff81536a00)
Location: drivers/pci/hotplug/pci_hotplug_core.c:507
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:update_adapter_status
  - drivers/pci/hotplug/cpci_hotplug_core.c:update_latch_status
  - drivers/pci/hotplug/shpchp_ctrl.c:update_slot_info
```
**Symbols:**

```
ffffffff81536a00-ffffffff81536a26: pci_hp_change_slot_info (STB_GLOBAL)
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
