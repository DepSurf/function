# Function: <code>pci_stop_and_remove_bus_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void pci_stop_and_remove_bus_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/remove.c (ffffffff814332a0)
Location: drivers/pci/remove.c:111
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/acpiphp_glue.c:disable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/iov.c:pci_enable_sriov
```
**Symbols:**

```
ffffffff814332a0-ffffffff814332bd: pci_stop_and_remove_bus_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void pci_stop_and_remove_bus_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/remove.c (ffffffff8147eb42)
Location: drivers/pci/remove.c:115
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked
Direct callers:
  - drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/hotplug/acpiphp_glue.c:disable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff8147eb10-ffffffff8147eb2d: pci_stop_and_remove_bus_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void pci_stop_and_remove_bus_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/remove.c (ffffffff814a01e2)
Location: drivers/pci/remove.c:115
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked
Direct callers:
  - drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/hotplug/acpiphp_glue.c:disable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff814a01b0-ffffffff814a01cd: pci_stop_and_remove_bus_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void pci_stop_and_remove_bus_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/remove.c (ffffffff814aa012)
Location: drivers/pci/remove.c:115
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked
Direct callers:
  - drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/hotplug/acpiphp_glue.c:disable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff814a9fe0-ffffffff814a9ffd: pci_stop_and_remove_bus_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void pci_stop_and_remove_bus_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/remove.c (ffffffff814e9272)
Location: drivers/pci/remove.c:115
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked
Direct callers:
  - drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/hotplug/acpiphp_glue.c:disable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff814e9240-ffffffff814e925d: pci_stop_and_remove_bus_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void pci_stop_and_remove_bus_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/remove.c (ffffffff81518a02)
Location: drivers/pci/remove.c:117
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked
Direct callers:
  - drivers/pci/pcie/err.c:pcie_do_fatal_recovery
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/hotplug/acpiphp_glue.c:disable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff815189d0-ffffffff815189ed: pci_stop_and_remove_bus_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void pci_stop_and_remove_bus_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/remove.c (ffffffff8152e472)
Location: drivers/pci/remove.c:114
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/hotplug/acpiphp_glue.c:disable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff8152e440-ffffffff8152e45d: pci_stop_and_remove_bus_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void pci_stop_and_remove_bus_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/remove.c (ffffffff8155dc23)
Location: drivers/pci/remove.c:114
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/hotplug/acpiphp_glue.c:disable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff8155dbf0-ffffffff8155dc0f: pci_stop_and_remove_bus_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void pci_stop_and_remove_bus_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/remove.c (ffffffff8157ec93)
Location: drivers/pci/remove.c:114
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/hotplug/acpiphp_glue.c:disable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff8157ec60-ffffffff8157ec7f: pci_stop_and_remove_bus_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void pci_stop_and_remove_bus_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/remove.c (ffffffff81624293)
Location: drivers/pci/remove.c:114
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/hotplug/acpiphp_glue.c:disable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff81624250-ffffffff81624271: pci_stop_and_remove_bus_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void pci_stop_and_remove_bus_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/remove.c (ffffffff81649e53)
Location: drivers/pci/remove.c:114
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/hotplug/acpiphp_glue.c:disable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff81649e10-ffffffff81649e31: pci_stop_and_remove_bus_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void pci_stop_and_remove_bus_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/remove.c (ffffffff8162ca03)
Location: drivers/pci/remove.c:116
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/hotplug/acpiphp_glue.c:disable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff8162c9c0-ffffffff8162c9e1: pci_stop_and_remove_bus_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void pci_stop_and_remove_bus_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/remove.c (ffffffff8169bed3)
Location: drivers/pci/remove.c:115
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/hotplug/acpiphp_glue.c:disable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff8169be90-ffffffff8169beb1: pci_stop_and_remove_bus_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void pci_stop_and_remove_bus_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/remove.c (ffffffff817bd7f2)
Location: drivers/pci/remove.c:115
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/hotplug/acpiphp_glue.c:disable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff817bd7b0-ffffffff817bd7d6: pci_stop_and_remove_bus_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void pci_stop_and_remove_bus_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/remove.c (ffffffff818d9952)
Location: drivers/pci/remove.c:115
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/hotplug/acpiphp_glue.c:disable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/platform/x86/p2sb.c:p2sb_bar
  - drivers/platform/x86/p2sb.c:p2sb_bar
  - drivers/platform/x86/p2sb.c:p2sb_bar
  - drivers/platform/x86/p2sb.c:p2sb_bar
```
**Symbols:**

```
ffffffff818d9900-ffffffff818d9926: pci_stop_and_remove_bus_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void pci_stop_and_remove_bus_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/remove.c (ffffffff8191cca2)
Location: drivers/pci/remove.c:115
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/hotplug/acpiphp_glue.c:disable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/platform/x86/p2sb.c:p2sb_bar
  - drivers/platform/x86/p2sb.c:p2sb_bar
  - drivers/platform/x86/p2sb.c:p2sb_bar
  - drivers/platform/x86/p2sb.c:p2sb_bar
```
**Symbols:**

```
ffffffff8191cc50-ffffffff8191cc76: pci_stop_and_remove_bus_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void pci_stop_and_remove_bus_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/remove.c (ffffffff819650d2)
Location: drivers/pci/remove.c:116
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/hotplug/acpiphp_glue.c:disable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
  - drivers/platform/x86/p2sb.c:p2sb_scan_and_cache_devfn
```
**Symbols:**

```
ffffffff81965080-ffffffff819650a6: pci_stop_and_remove_bus_device (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void pci_stop_and_remove_bus_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/remove.c (ffff8000106e174c)
Location: drivers/pci/remove.c:114
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/hotplug/acpiphp_glue.c:disable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffff8000106e16f8-ffff8000106e172c: pci_stop_and_remove_bus_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void pci_stop_and_remove_bus_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/remove.c (c087d25c)
Location: drivers/pci/remove.c:114
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked
Direct callers:
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
c087d218-c087d240: pci_stop_and_remove_bus_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void pci_stop_and_remove_bus_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/remove.c (c00000000085a9b8)
Location: drivers/pci/remove.c:114
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked
Direct callers:
  - arch/powerpc/kernel/eeh_driver.c:eeh_rmv_device
  - arch/powerpc/kernel/pci-hotplug.c:pci_hp_remove_devices
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
c00000000085a950-c00000000085a990: pci_stop_and_remove_bus_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void pci_stop_and_remove_bus_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/remove.c (ffffffe0004b91fa)
Location: drivers/pci/remove.c:114
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffe0004b91a8-ffffffe0004b91dc: pci_stop_and_remove_bus_device (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void pci_stop_and_remove_bus_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/remove.c (ffffffff815731b3)
Location: drivers/pci/remove.c:114
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/hotplug/acpiphp_glue.c:disable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff81573180-ffffffff8157319f: pci_stop_and_remove_bus_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void pci_stop_and_remove_bus_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/remove.c (ffffffff81561913)
Location: drivers/pci/remove.c:114
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/hotplug/acpiphp_glue.c:disable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff815618e0-ffffffff815618ff: pci_stop_and_remove_bus_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void pci_stop_and_remove_bus_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/remove.c (ffffffff815729e3)
Location: drivers/pci/remove.c:114
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/hotplug/acpiphp_glue.c:disable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff815729b0-ffffffff815729cf: pci_stop_and_remove_bus_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void pci_stop_and_remove_bus_device(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/remove.c (ffffffff8158cec3)
Location: drivers/pci/remove.c:114
Inline: True
Inline callers:
  - drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
  - drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/hotplug/acpiphp_glue.c:disable_slot
  - drivers/pci/hotplug/acpiphp_glue.c:enable_slot
  - drivers/pci/iov.c:pci_iov_remove_virtfn
  - drivers/pci/iov.c:pci_iov_add_virtfn
```
**Symbols:**

```
ffffffff8158ce90-ffffffff8158ceaf: pci_stop_and_remove_bus_device (STB_GLOBAL)
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
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
