# Function: <code>pci_bus_read_dev_vendor_id</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool pci_bus_read_dev_vendor_id(struct pci_bus *bus, int devfn, u32 *l, int crs_timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8142fa50)
Location: drivers/pci/probe.c:1547
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_device_is_present
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffffffff8142fa50-ffffffff8142fb2a: pci_bus_read_dev_vendor_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool pci_bus_read_dev_vendor_id(struct pci_bus *bus, int devfn, u32 *l, int crs_timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8147b1b0)
Location: drivers/pci/probe.c:1569
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_device_is_present
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffffffff8147b1b0-ffffffff8147b282: pci_bus_read_dev_vendor_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool pci_bus_read_dev_vendor_id(struct pci_bus *bus, int devfn, u32 *l, int crs_timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8149c630)
Location: drivers/pci/probe.c:1716
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffffffff8149c630-ffffffff8149c702: pci_bus_read_dev_vendor_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool pci_bus_read_dev_vendor_id(struct pci_bus *bus, int devfn, u32 *l, int crs_timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814a6500)
Location: drivers/pci/probe.c:1870
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffffffff814a6500-ffffffff814a65c9: pci_bus_read_dev_vendor_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool pci_bus_read_dev_vendor_id(struct pci_bus *bus, int devfn, u32 *l, int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814e54a0)
Location: drivers/pci/probe.c:2023
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffffffff814e54a0-ffffffff814e5603: pci_bus_read_dev_vendor_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool pci_bus_read_dev_vendor_id(struct pci_bus *bus, int devfn, u32 *l, int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:2171
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/acpiphp_glue.c:get_slot_status
  - drivers/pci/hotplug/acpiphp_glue.c:get_slot_status
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffffffff8151850c-ffffffff815185a4: pci_bus_read_dev_vendor_id.cold.44 (STB_LOCAL)
ffffffff815149b0-ffffffff81514a94: pci_bus_read_dev_vendor_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool pci_bus_read_dev_vendor_id(struct pci_bus *bus, int devfn, u32 *l, int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8152c130)
Location: drivers/pci/probe.c:2275
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/acpiphp_glue.c:get_slot_status
  - drivers/pci/hotplug/acpiphp_glue.c:get_slot_status
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffffffff8152c130-ffffffff8152c15e: pci_bus_read_dev_vendor_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool pci_bus_read_dev_vendor_id(struct pci_bus *bus, int devfn, u32 *l, int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8155aad0)
Location: drivers/pci/probe.c:2501
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/acpiphp_glue.c:get_slot_status
  - drivers/pci/hotplug/acpiphp_glue.c:get_slot_status
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffffffff8155aad0-ffffffff8155aafe: pci_bus_read_dev_vendor_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool pci_bus_read_dev_vendor_id(struct pci_bus *bus, int devfn, u32 *l, int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8157bb60)
Location: drivers/pci/probe.c:2239
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/acpiphp_glue.c:get_slot_status
  - drivers/pci/hotplug/acpiphp_glue.c:get_slot_status
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffffffff8157bb60-ffffffff8157bb8e: pci_bus_read_dev_vendor_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool pci_bus_read_dev_vendor_id(struct pci_bus *bus, int devfn, u32 *l, int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff816212e0)
Location: drivers/pci/probe.c:2307
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_update_current_state
  - drivers/pci/hotplug/acpiphp_glue.c:get_slot_status
  - drivers/pci/hotplug/acpiphp_glue.c:get_slot_status
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffffffff816212e0-ffffffff8162130e: pci_bus_read_dev_vendor_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool pci_bus_read_dev_vendor_id(struct pci_bus *bus, int devfn, u32 *l, int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81647e50)
Location: drivers/pci/probe.c:2314
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_update_current_state
  - drivers/pci/hotplug/acpiphp_glue.c:get_slot_status
  - drivers/pci/hotplug/acpiphp_glue.c:get_slot_status
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffffffff81647e50-ffffffff81647e7e: pci_bus_read_dev_vendor_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool pci_bus_read_dev_vendor_id(struct pci_bus *bus, int devfn, u32 *l, int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8162aa90)
Location: drivers/pci/probe.c:2357
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_update_current_state
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/acpiphp_glue.c:get_slot_status
  - drivers/pci/hotplug/acpiphp_glue.c:get_slot_status
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffffffff8162aa90-ffffffff8162aabe: pci_bus_read_dev_vendor_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool pci_bus_read_dev_vendor_id(struct pci_bus *bus, int devfn, u32 *l, int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81699f70)
Location: drivers/pci/probe.c:2404
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_update_current_state
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/acpiphp_glue.c:get_slot_status
  - drivers/pci/hotplug/acpiphp_glue.c:get_slot_status
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffffffff81699f70-ffffffff81699f9e: pci_bus_read_dev_vendor_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool pci_bus_read_dev_vendor_id(struct pci_bus *bus, int devfn, u32 *l, int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff817bb570)
Location: drivers/pci/probe.c:2379
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/acpiphp_glue.c:get_slot_status
  - drivers/pci/hotplug/acpiphp_glue.c:get_slot_status
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffffffff817bb570-ffffffff817bb5b6: pci_bus_read_dev_vendor_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool pci_bus_read_dev_vendor_id(struct pci_bus *bus, int devfn, u32 *l, int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff818d7050)
Location: drivers/pci/probe.c:2391
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_device_is_present
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/acpiphp_glue.c:get_slot_status
  - drivers/pci/hotplug/acpiphp_glue.c:get_slot_status
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffffffff818d7050-ffffffff818d7096: pci_bus_read_dev_vendor_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool pci_bus_read_dev_vendor_id(struct pci_bus *bus, int devfn, u32 *l, int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8191a2d0)
Location: drivers/pci/probe.c:2402
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_device_is_present
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/acpiphp_glue.c:get_slot_status
  - drivers/pci/hotplug/acpiphp_glue.c:get_slot_status
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffffffff8191a2d0-ffffffff8191a316: pci_bus_read_dev_vendor_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool pci_bus_read_dev_vendor_id(struct pci_bus *bus, int devfn, u32 *l, int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff819626d0)
Location: drivers/pci/probe.c:2451
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_device_is_present
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/acpiphp_glue.c:get_slot_status
  - drivers/pci/hotplug/acpiphp_glue.c:get_slot_status
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffffffff819626d0-ffffffff81962716: pci_bus_read_dev_vendor_id (STB_GLOBAL)
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
bool pci_bus_read_dev_vendor_id(struct pci_bus *bus, int devfn, u32 *l, int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffff8000106df0b8)
Location: drivers/pci/probe.c:2239
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/acpiphp_glue.c:get_slot_status
  - drivers/pci/hotplug/acpiphp_glue.c:get_slot_status
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffff8000106df0b8-ffff8000106df13c: pci_bus_read_dev_vendor_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool pci_bus_read_dev_vendor_id(struct pci_bus *bus, int devfn, u32 *l, int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c087ad78)
Location: drivers/pci/probe.c:2239
Inline: True
```
**Symbols:**

```
c087ad78-c087ade4: pci_bus_read_dev_vendor_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool pci_bus_read_dev_vendor_id(struct pci_bus *bus, int devfn, u32 *l, int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c000000000857680)
Location: drivers/pci/probe.c:2239
Inline: True
```
**Symbols:**

```
c000000000857680-c000000000857710: pci_bus_read_dev_vendor_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool pci_bus_read_dev_vendor_id(struct pci_bus *bus, int devfn, u32 *l, int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffe0004b7164)
Location: drivers/pci/probe.c:2239
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
```
**Symbols:**

```
ffffffe0004b7164-ffffffe0004b71cc: pci_bus_read_dev_vendor_id (STB_GLOBAL)
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
bool pci_bus_read_dev_vendor_id(struct pci_bus *bus, int devfn, u32 *l, int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81570080)
Location: drivers/pci/probe.c:2239
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/acpiphp_glue.c:get_slot_status
  - drivers/pci/hotplug/acpiphp_glue.c:get_slot_status
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffffffff81570080-ffffffff815700ae: pci_bus_read_dev_vendor_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool pci_bus_read_dev_vendor_id(struct pci_bus *bus, int devfn, u32 *l, int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8155e7e0)
Location: drivers/pci/probe.c:2239
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/acpiphp_glue.c:get_slot_status
  - drivers/pci/hotplug/acpiphp_glue.c:get_slot_status
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffffffff8155e7e0-ffffffff8155e80e: pci_bus_read_dev_vendor_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool pci_bus_read_dev_vendor_id(struct pci_bus *bus, int devfn, u32 *l, int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8156f8b0)
Location: drivers/pci/probe.c:2239
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/acpiphp_glue.c:get_slot_status
  - drivers/pci/hotplug/acpiphp_glue.c:get_slot_status
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffffffff8156f8b0-ffffffff8156f8de: pci_bus_read_dev_vendor_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool pci_bus_read_dev_vendor_id(struct pci_bus *bus, int devfn, u32 *l, int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81589d90)
Location: drivers/pci/probe.c:2239
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status
  - drivers/pci/hotplug/acpiphp_glue.c:get_slot_status
  - drivers/pci/hotplug/acpiphp_glue.c:get_slot_status
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffffffff81589d90-ffffffff81589dbe: pci_bus_read_dev_vendor_id (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int timeout</code>
</li>
<li>
<b>Param removed. </b>
<code>int crs_timeout</code>
</li>
</ul>
</details>
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
