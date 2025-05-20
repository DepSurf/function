# Function: <code>pci_resource_name</code>

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
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
const char *pci_resource_name(struct pci_dev *dev, unsigned int i);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81970b68)
Location: drivers/pci/pci.c:860
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_reassigndev_resource_alignment
  - drivers/pci/pci.c:pci_ea_read
Direct callers:
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/setup-res.c:pci_enable_resources
  - drivers/pci/setup-res.c:pci_release_resource
  - drivers/pci/setup-res.c:pci_reassign_resource
  - drivers/pci/setup-res.c:pci_assign_resource
  - drivers/pci/setup-res.c:pci_assign_resource
  - drivers/pci/setup-res.c:pci_claim_resource
  - drivers/pci/setup-res.c:pci_std_update_resource
  - drivers/pci/setup-bus.c:pci_reassign_bridge_resources
  - drivers/pci/setup-bus.c:pbus_size_mem
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/setup-bus.c:reassign_resources_sorted
  - drivers/pci/quirks.c:quirk_io
  - drivers/pci/quirks.c:quirk_extend_bar_to_page
  - drivers/pci/iov.c:sriov_init
```
**Symbols:**

```
ffffffff8196b9e0-ffffffff8196ba65: pci_resource_name (STB_GLOBAL)
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
</ul>
