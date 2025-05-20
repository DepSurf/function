# Function: <code>pcibios_resource_to_bus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pcibios_resource_to_bus(struct pci_bus *bus, struct pci_bus_region *region, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffff81432e80)
Location: drivers/pci/host-bridge.c:48
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/rom.c:pci_enable_rom
  - drivers/pci/setup-res.c:pci_update_resource
  - drivers/pci/setup-bus.c:iov_resources_unassigned
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_configure
```
**Symbols:**

```
ffffffff81432e80-ffffffff81432f21: pcibios_resource_to_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pcibios_resource_to_bus(struct pci_bus *bus, struct pci_bus_region *region, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffff8147e700)
Location: drivers/pci/host-bridge.c:49
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/rom.c:pci_enable_rom
  - drivers/pci/setup-res.c:pci_update_resource
  - drivers/pci/setup-bus.c:iov_resources_unassigned
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_configure
```
**Symbols:**

```
ffffffff8147e700-ffffffff8147e7a1: pcibios_resource_to_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pcibios_resource_to_bus(struct pci_bus *bus, struct pci_bus_region *region, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffff8149fda0)
Location: drivers/pci/host-bridge.c:49
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/rom.c:pci_enable_rom
  - drivers/pci/setup-res.c:pci_update_resource
  - drivers/pci/setup-bus.c:iov_resources_unassigned
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_configure
```
**Symbols:**

```
ffffffff8149fda0-ffffffff8149fe41: pcibios_resource_to_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pcibios_resource_to_bus(struct pci_bus *bus, struct pci_bus_region *region, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffff814a9bf0)
Location: drivers/pci/host-bridge.c:49
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/rom.c:pci_enable_rom
  - drivers/pci/setup-res.c:pci_update_resource
  - drivers/pci/setup-bus.c:iov_resources_unassigned
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_configure
```
**Symbols:**

```
ffffffff814a9bf0-ffffffff814a9c8a: pcibios_resource_to_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pcibios_resource_to_bus(struct pci_bus *bus, struct pci_bus_region *region, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffff814e8e50)
Location: drivers/pci/host-bridge.c:49
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/rom.c:pci_enable_rom
  - drivers/pci/setup-res.c:pci_update_resource
  - drivers/pci/setup-bus.c:iov_resources_unassigned
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_configure
```
**Symbols:**

```
ffffffff814e8e50-ffffffff814e8eea: pcibios_resource_to_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pcibios_resource_to_bus(struct pci_bus *bus, struct pci_bus_region *region, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffff815185e0)
Location: drivers/pci/host-bridge.c:50
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/rom.c:pci_enable_rom
  - drivers/pci/setup-bus.c:iov_resources_unassigned
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_configure
```
**Symbols:**

```
ffffffff815185e0-ffffffff8151867a: pcibios_resource_to_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pcibios_resource_to_bus(struct pci_bus *bus, struct pci_bus_region *region, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffff8152e060)
Location: drivers/pci/host-bridge.c:50
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/rom.c:pci_enable_rom
  - drivers/pci/setup-bus.c:iov_resources_unassigned
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-gtt.c:intel_gmch_probe
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_configure
```
**Symbols:**

```
ffffffff8152e060-ffffffff8152e0fa: pcibios_resource_to_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pcibios_resource_to_bus(struct pci_bus *bus, struct pci_bus_region *region, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffff8155d810)
Location: drivers/pci/host-bridge.c:50
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/rom.c:pci_enable_rom
  - drivers/pci/setup-bus.c:iov_resources_unassigned
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_configure
```
**Symbols:**

```
ffffffff8155d810-ffffffff8155d8a8: pcibios_resource_to_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pcibios_resource_to_bus(struct pci_bus *bus, struct pci_bus_region *region, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffff8157e880)
Location: drivers/pci/host-bridge.c:50
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/rom.c:pci_enable_rom
  - drivers/pci/setup-bus.c:iov_resources_unassigned
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_configure
```
**Symbols:**

```
ffffffff8157e880-ffffffff8157e918: pcibios_resource_to_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pcibios_resource_to_bus(struct pci_bus *bus, struct pci_bus_region *region, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffff81623da0)
Location: drivers/pci/host-bridge.c:50
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/rom.c:pci_enable_rom
  - drivers/pci/setup-res.c:pci_std_update_resource
  - drivers/pci/setup-bus.c:iov_resources_unassigned
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/amd64-agp.c:fix_northbridge
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_configure
```
**Symbols:**

```
ffffffff81623da0-ffffffff81623e40: pcibios_resource_to_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pcibios_resource_to_bus(struct pci_bus *bus, struct pci_bus_region *region, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffff81649960)
Location: drivers/pci/host-bridge.c:50
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/rom.c:pci_enable_rom
  - drivers/pci/setup-res.c:pci_std_update_resource
  - drivers/pci/setup-bus.c:iov_resources_unassigned
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/amd64-agp.c:fix_northbridge
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_configure
```
**Symbols:**

```
ffffffff81649960-ffffffff81649a00: pcibios_resource_to_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pcibios_resource_to_bus(struct pci_bus *bus, struct pci_bus_region *region, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffff8162c520)
Location: drivers/pci/host-bridge.c:50
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/rom.c:pci_enable_rom
  - drivers/pci/setup-res.c:pci_std_update_resource
  - drivers/pci/setup-bus.c:iov_resources_unassigned
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/amd64-agp.c:fix_northbridge
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_configure
```
**Symbols:**

```
ffffffff8162c520-ffffffff8162c5c0: pcibios_resource_to_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pcibios_resource_to_bus(struct pci_bus *bus, struct pci_bus_region *region, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffff8169ba10)
Location: drivers/pci/host-bridge.c:51
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/rom.c:pci_enable_rom
  - drivers/pci/setup-res.c:pci_std_update_resource
  - drivers/pci/setup-bus.c:iov_resources_unassigned
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/amd64-agp.c:fix_northbridge
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_configure
```
**Symbols:**

```
ffffffff8169ba10-ffffffff8169bab0: pcibios_resource_to_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pcibios_resource_to_bus(struct pci_bus *bus, struct pci_bus_region *region, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffff817bd260)
Location: drivers/pci/host-bridge.c:51
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/rom.c:pci_enable_rom
  - drivers/pci/setup-res.c:pci_std_update_resource
  - drivers/pci/setup-bus.c:iov_resources_unassigned
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/amd64-agp.c:fix_northbridge
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_configure
```
**Symbols:**

```
ffffffff817bd260-ffffffff817bd333: pcibios_resource_to_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pcibios_resource_to_bus(struct pci_bus *bus, struct pci_bus_region *region, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffff818d9320)
Location: drivers/pci/host-bridge.c:51
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/rom.c:pci_enable_rom
  - drivers/pci/setup-res.c:pci_std_update_resource
  - drivers/pci/setup-bus.c:iov_resources_unassigned
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/amd64-agp.c:fix_northbridge
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_configure
```
**Symbols:**

```
ffffffff818d9320-ffffffff818d93f3: pcibios_resource_to_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pcibios_resource_to_bus(struct pci_bus *bus, struct pci_bus_region *region, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffff8191c650)
Location: drivers/pci/host-bridge.c:51
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/rom.c:pci_enable_rom
  - drivers/pci/setup-res.c:pci_std_update_resource
  - drivers/pci/setup-bus.c:iov_resources_unassigned
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/amd64-agp.c:fix_northbridge
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_configure
```
**Symbols:**

```
ffffffff8191c650-ffffffff8191c723: pcibios_resource_to_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pcibios_resource_to_bus(struct pci_bus *bus, struct pci_bus_region *region, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffff81964a80)
Location: drivers/pci/host-bridge.c:51
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/rom.c:pci_enable_rom
  - drivers/pci/setup-res.c:pci_std_update_resource
  - drivers/pci/setup-bus.c:iov_resources_unassigned
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
  - drivers/pci/p2pdma.c:pci_p2pdma_add_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/amd64-agp.c:fix_northbridge
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_configure
```
**Symbols:**

```
ffffffff81964a80-ffffffff81964b53: pcibios_resource_to_bus (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void pcibios_resource_to_bus(struct pci_bus *bus, struct pci_bus_region *region, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffff8000106e1140)
Location: drivers/pci/host-bridge.c:50
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/rom.c:pci_enable_rom
  - drivers/pci/setup-bus.c:iov_resources_unassigned
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
```
**Symbols:**

```
ffff8000106e1140-ffff8000106e120c: pcibios_resource_to_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pcibios_resource_to_bus(struct pci_bus *bus, struct pci_bus_region *region, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (c087ce18)
Location: drivers/pci/host-bridge.c:50
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_resource
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/rom.c:pci_enable_rom
  - drivers/pci/setup-bus.c:iov_resources_unassigned
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
```
**Symbols:**

```
c087ce18-c087cec8: pcibios_resource_to_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pcibios_resource_to_bus(struct pci_bus *bus, struct pci_bus_region *region, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (c00000000085a360)
Location: drivers/pci/host-bridge.c:50
Inline: False
Direct callers:
  - arch/powerpc/kernel/pci-common.c:pcibios_setup_bus_self
  - arch/powerpc/kernel/pci-common.c:pci_resource_to_user
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/rom.c:pci_enable_rom
  - drivers/pci/setup-bus.c:iov_resources_unassigned
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/char/agp/generic.c:agp3_generic_configure
```
**Symbols:**

```
c00000000085a360-c00000000085a428: pcibios_resource_to_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pcibios_resource_to_bus(struct pci_bus *bus, struct pci_bus_region *region, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffe0004b8dc4)
Location: drivers/pci/host-bridge.c:50
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/rom.c:pci_enable_rom
  - drivers/pci/setup-bus.c:iov_resources_unassigned
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
```
**Symbols:**

```
ffffffe0004b8dc4-ffffffe0004b8e5e: pcibios_resource_to_bus (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void pcibios_resource_to_bus(struct pci_bus *bus, struct pci_bus_region *region, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffff81572da0)
Location: drivers/pci/host-bridge.c:50
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/rom.c:pci_enable_rom
  - drivers/pci/setup-bus.c:iov_resources_unassigned
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_configure
```
**Symbols:**

```
ffffffff81572da0-ffffffff81572e38: pcibios_resource_to_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pcibios_resource_to_bus(struct pci_bus *bus, struct pci_bus_region *region, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffff81561500)
Location: drivers/pci/host-bridge.c:50
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/rom.c:pci_enable_rom
  - drivers/pci/setup-bus.c:iov_resources_unassigned
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_configure
```
**Symbols:**

```
ffffffff81561500-ffffffff81561598: pcibios_resource_to_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pcibios_resource_to_bus(struct pci_bus *bus, struct pci_bus_region *region, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffff815725d0)
Location: drivers/pci/host-bridge.c:50
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/rom.c:pci_enable_rom
  - drivers/pci/setup-bus.c:iov_resources_unassigned
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_configure
```
**Symbols:**

```
ffffffff815725d0-ffffffff81572668: pcibios_resource_to_bus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pcibios_resource_to_bus(struct pci_bus *bus, struct pci_bus_region *region, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffff8158cab0)
Location: drivers/pci/host-bridge.c:50
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/rom.c:pci_enable_rom
  - drivers/pci/setup-bus.c:iov_resources_unassigned
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio_pref
  - drivers/pci/setup-bus.c:pci_setup_bridge_mmio
  - drivers/pci/setup-bus.c:pci_setup_bridge_io
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/setup-bus.c:pci_setup_cardbus
  - drivers/pci/iov.c:pci_iov_update_resource
  - drivers/tty/serial/8250/8250_pci.c:pci_ni8430_init
  - drivers/char/agp/generic.c:agp3_generic_configure
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/intel-agp.c:intel_7505_configure
  - drivers/char/agp/intel-agp.c:intel_830mp_configure
  - drivers/char/agp/intel-agp.c:intel_860_configure
  - drivers/char/agp/intel-agp.c:intel_850_configure
  - drivers/char/agp/intel-agp.c:intel_845_configure
  - drivers/char/agp/intel-agp.c:intel_840_configure
  - drivers/char/agp/intel-agp.c:intel_820_configure
  - drivers/char/agp/intel-agp.c:intel_815_configure
  - drivers/char/agp/intel-agp.c:intel_configure
  - drivers/char/agp/intel-gtt.c:intel_gtt_init
  - drivers/char/agp/via-agp.c:via_configure_agp3
  - drivers/char/agp/via-agp.c:via_configure
```
**Symbols:**

```
ffffffff8158cab0-ffffffff8158cb48: pcibios_resource_to_bus (STB_GLOBAL)
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
