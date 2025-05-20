# Function: <code>pci_scan_root_bus_msi</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct pci_bus *pci_scan_root_bus_msi(struct device *parent, int bus, struct pci_ops *ops, void *sysdata, struct list_head *resources, struct msi_controller *msi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81432d60)
Location: drivers/pci/probe.c:2261
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus
```
**Symbols:**

```
ffffffff81432d60-ffffffff81432e18: pci_scan_root_bus_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct pci_bus *pci_scan_root_bus_msi(struct device *parent, int bus, struct pci_ops *ops, void *sysdata, struct list_head *resources, struct msi_controller *msi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8147e5c0)
Location: drivers/pci/probe.c:2301
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus
```
**Symbols:**

```
ffffffff8147e5c0-ffffffff8147e672: pci_scan_root_bus_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct pci_bus *pci_scan_root_bus_msi(struct device *parent, int bus, struct pci_ops *ops, void *sysdata, struct list_head *resources, struct msi_controller *msi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8149fc80)
Location: drivers/pci/probe.c:2381
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_scan_root_bus
```
**Symbols:**

```
ffffffff8149fc80-ffffffff8149fd1b: pci_scan_root_bus_msi (STB_GLOBAL)
```
</details>
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
</ul>
