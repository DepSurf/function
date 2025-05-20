# Function: <code>update_adapter_status</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8144cc47)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:94
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff8149998a)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:94
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff814bb57a)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:94
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int update_adapter_status(struct hotplug_slot *hotplug_slot, u8 value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff814c56c0)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:95
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
```
**Symbols:**

```
ffffffff814c56c0-ffffffff814c5708: update_adapter_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int update_adapter_status(struct hotplug_slot *hotplug_slot, u8 value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81505c50)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:95
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
```
**Symbols:**

```
ffffffff81505c50-ffffffff81505c98: update_adapter_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int update_adapter_status(struct hotplug_slot *hotplug_slot, u8 value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81536c10)
Location: drivers/pci/hotplug/cpci_hotplug_core.c:81
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:check_slots
  - drivers/pci/hotplug/cpci_hotplug_core.c:disable_slot
```
**Symbols:**

```
ffffffff81536c10-ffffffff81536c58: update_adapter_status (STB_LOCAL)
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
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
