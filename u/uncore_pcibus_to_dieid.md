# Function: <code>uncore_pcibus_to_dieid</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int uncore_pcibus_to_dieid(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8101ae61)
Location: arch/x86/events/intel/uncore.c:39
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_die_to_segment
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_init
  - arch/x86/events/intel/uncore.c:uncore_pci_bus_notify
  - arch/x86/events/intel/uncore.c:uncore_pci_sub_bus_notify
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore_snbep.c:__snr_uncore_mmio_init_box
```
**Symbols:**

```
ffffffff8101ab80-ffffffff8101abee: uncore_pcibus_to_dieid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int uncore_pcibus_to_dieid(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8101d761)
Location: arch/x86/events/intel/uncore.c:39
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_die_to_segment
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_init
  - arch/x86/events/intel/uncore.c:uncore_pci_bus_notify
  - arch/x86/events/intel/uncore.c:uncore_pci_sub_bus_notify
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_map
```
**Symbols:**

```
ffffffff8101d570-ffffffff8101d5de: uncore_pcibus_to_dieid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int uncore_pcibus_to_dieid(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8101ff28)
Location: arch/x86/events/intel/uncore.c:39
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_bus_notify
  - arch/x86/events/intel/uncore.c:uncore_pci_sub_bus_notify
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_die_to_segment
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_init
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_map
  - arch/x86/events/intel/uncore_snbep.c:sad_cfg_iio_topology
```
**Symbols:**

```
ffffffff81020090-ffffffff81020101: uncore_pcibus_to_dieid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int uncore_pcibus_to_dieid(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff83e69e15)
Location: arch/x86/events/intel/uncore.c:39
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_init
  - arch/x86/events/intel/uncore.c:uncore_pci_bus_notify
  - arch/x86/events/intel/uncore.c:uncore_pci_sub_bus_notify
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_die_to_segment
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_map
  - arch/x86/events/intel/uncore_snbep.c:sad_cfg_iio_topology
```
**Symbols:**

```
ffffffff81024920-ffffffff81024991: uncore_pcibus_to_dieid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int uncore_pcibus_to_dieid(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8368a7a5)
Location: arch/x86/events/intel/uncore.c:39
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_init
  - arch/x86/events/intel/uncore.c:uncore_pci_bus_notify
  - arch/x86/events/intel/uncore.c:uncore_pci_sub_bus_notify
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_die_to_segment
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_map
  - arch/x86/events/intel/uncore_snbep.c:sad_cfg_iio_topology
```
**Symbols:**

```
ffffffff81024680-ffffffff810246f3: uncore_pcibus_to_dieid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int uncore_pcibus_to_dieid(struct pci_bus *bus);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff838ba365)
Location: arch/x86/events/intel/uncore.c:39
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_init
  - arch/x86/events/intel/uncore.c:uncore_pci_bus_notify
  - arch/x86/events/intel/uncore.c:uncore_pci_sub_bus_notify
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_die_to_segment
Direct callers:
  - arch/x86/events/intel/uncore_snbep.c:snr_uncore_mmio_map
  - arch/x86/events/intel/uncore_snbep.c:sad_cfg_iio_topology
```
**Symbols:**

```
ffffffff8102a7b0-ffffffff8102a823: uncore_pcibus_to_dieid (STB_GLOBAL)
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
<b>Regular</b>
<ul>
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
