# Function: <code>uncore_pci_get_dev_die_info</code>

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
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81019b09)
Location: arch/x86/events/intel/uncore.c:999
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_bus_notify
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_sub_driver_init
```
**Symbols:**

```
ffffffff810198d0-ffffffff8101991e: uncore_pci_get_dev_die_info.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff831bf5b2)
Location: arch/x86/events/intel/uncore.c:1038
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_init
  - arch/x86/events/intel/uncore.c:uncore_pci_bus_notify
  - arch/x86/events/intel/uncore.c:uncore_pci_sub_bus_notify
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8329fa22)
Location: arch/x86/events/intel/uncore.c:1045
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_init
  - arch/x86/events/intel/uncore.c:uncore_pci_bus_notify
  - arch/x86/events/intel/uncore.c:uncore_pci_sub_bus_notify
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8344e832)
Location: arch/x86/events/intel/uncore.c:1045
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_init
  - arch/x86/events/intel/uncore.c:uncore_pci_bus_notify
  - arch/x86/events/intel/uncore.c:uncore_pci_sub_bus_notify
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff83e69e06)
Location: arch/x86/events/intel/uncore.c:1045
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_init
  - arch/x86/events/intel/uncore.c:uncore_pci_bus_notify
  - arch/x86/events/intel/uncore.c:uncore_pci_sub_bus_notify
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8368a796)
Location: arch/x86/events/intel/uncore.c:1066
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_init
  - arch/x86/events/intel/uncore.c:uncore_pci_bus_notify
  - arch/x86/events/intel/uncore.c:uncore_pci_sub_bus_notify
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff838ba356)
Location: arch/x86/events/intel/uncore.c:1066
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_init
  - arch/x86/events/intel/uncore.c:uncore_pci_bus_notify
  - arch/x86/events/intel/uncore.c:uncore_pci_sub_bus_notify
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
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
