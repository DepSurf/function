# Function: <code>pcibios_bus_to_resource</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pcibios_bus_to_resource(struct pci_bus *bus, struct resource *res, struct pci_bus_region *region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffff81432f30)
Location: drivers/pci/host-bridge.c:73
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/quirks.c:quirk_io
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pnp/quirks.c:quirk_intel_mch
```
**Symbols:**

```
ffffffff81432f30-ffffffff81432fd3: pcibios_bus_to_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pcibios_bus_to_resource(struct pci_bus *bus, struct resource *res, struct pci_bus_region *region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffff8147e7b0)
Location: drivers/pci/host-bridge.c:74
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/quirks.c:quirk_io
  - drivers/pnp/quirks.c:quirk_intel_mch
```
**Symbols:**

```
ffffffff8147e7b0-ffffffff8147e853: pcibios_bus_to_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pcibios_bus_to_resource(struct pci_bus *bus, struct resource *res, struct pci_bus_region *region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffff8149fe50)
Location: drivers/pci/host-bridge.c:74
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/quirks.c:quirk_io
  - drivers/pnp/quirks.c:quirk_intel_mch
```
**Symbols:**

```
ffffffff8149fe50-ffffffff8149fef3: pcibios_bus_to_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pcibios_bus_to_resource(struct pci_bus *bus, struct resource *res, struct pci_bus_region *region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffff814a9c90)
Location: drivers/pci/host-bridge.c:74
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/quirks.c:quirk_io
  - drivers/pnp/quirks.c:quirk_intel_mch
```
**Symbols:**

```
ffffffff814a9c90-ffffffff814a9d26: pcibios_bus_to_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pcibios_bus_to_resource(struct pci_bus *bus, struct resource *res, struct pci_bus_region *region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffff814e8ef0)
Location: drivers/pci/host-bridge.c:74
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/quirks.c:quirk_io
  - drivers/pnp/quirks.c:quirk_intel_mch
```
**Symbols:**

```
ffffffff814e8ef0-ffffffff814e8f86: pcibios_bus_to_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pcibios_bus_to_resource(struct pci_bus *bus, struct resource *res, struct pci_bus_region *region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffff81518680)
Location: drivers/pci/host-bridge.c:75
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/quirks.c:quirk_io
  - drivers/pnp/quirks.c:quirk_intel_mch
```
**Symbols:**

```
ffffffff81518680-ffffffff81518719: pcibios_bus_to_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pcibios_bus_to_resource(struct pci_bus *bus, struct resource *res, struct pci_bus_region *region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffff8152e100)
Location: drivers/pci/host-bridge.c:75
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/quirks.c:quirk_io
  - drivers/pnp/quirks.c:quirk_intel_mch
```
**Symbols:**

```
ffffffff8152e100-ffffffff8152e199: pcibios_bus_to_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pcibios_bus_to_resource(struct pci_bus *bus, struct resource *res, struct pci_bus_region *region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffff8155d8b0)
Location: drivers/pci/host-bridge.c:75
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/quirks.c:quirk_io
  - drivers/pnp/quirks.c:quirk_intel_mch
```
**Symbols:**

```
ffffffff8155d8b0-ffffffff8155d947: pcibios_bus_to_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pcibios_bus_to_resource(struct pci_bus *bus, struct resource *res, struct pci_bus_region *region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffff8157e920)
Location: drivers/pci/host-bridge.c:75
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/quirks.c:quirk_io
  - drivers/pnp/quirks.c:quirk_intel_mch
```
**Symbols:**

```
ffffffff8157e920-ffffffff8157e9b7: pcibios_bus_to_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pcibios_bus_to_resource(struct pci_bus *bus, struct resource *res, struct pci_bus_region *region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffff81623e40)
Location: drivers/pci/host-bridge.c:75
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_mmio_pref
  - drivers/pci/probe.c:pci_read_bridge_io
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/quirks.c:quirk_io
  - drivers/pnp/quirks.c:quirk_intel_mch
```
**Symbols:**

```
ffffffff81623e40-ffffffff81623edc: pcibios_bus_to_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pcibios_bus_to_resource(struct pci_bus *bus, struct resource *res, struct pci_bus_region *region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffff81649a00)
Location: drivers/pci/host-bridge.c:75
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_mmio_pref
  - drivers/pci/probe.c:pci_read_bridge_io
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/quirks.c:quirk_io
  - drivers/pnp/quirks.c:quirk_intel_mch
```
**Symbols:**

```
ffffffff81649a00-ffffffff81649a9c: pcibios_bus_to_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pcibios_bus_to_resource(struct pci_bus *bus, struct resource *res, struct pci_bus_region *region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffff8162c5c0)
Location: drivers/pci/host-bridge.c:75
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/quirks.c:quirk_io
  - drivers/pnp/quirks.c:quirk_intel_mch
```
**Symbols:**

```
ffffffff8162c5c0-ffffffff8162c64f: pcibios_bus_to_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pcibios_bus_to_resource(struct pci_bus *bus, struct resource *res, struct pci_bus_region *region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffff8169bab0)
Location: drivers/pci/host-bridge.c:76
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/quirks.c:quirk_io
  - drivers/pnp/quirks.c:quirk_intel_mch
```
**Symbols:**

```
ffffffff8169bab0-ffffffff8169bb3f: pcibios_bus_to_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pcibios_bus_to_resource(struct pci_bus *bus, struct resource *res, struct pci_bus_region *region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffff817bd340)
Location: drivers/pci/host-bridge.c:76
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/quirks.c:quirk_io
  - drivers/pnp/quirks.c:quirk_intel_mch
```
**Symbols:**

```
ffffffff817bd340-ffffffff817bd403: pcibios_bus_to_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pcibios_bus_to_resource(struct pci_bus *bus, struct resource *res, struct pci_bus_region *region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffff818d9410)
Location: drivers/pci/host-bridge.c:76
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/quirks.c:quirk_io
  - drivers/pnp/quirks.c:quirk_intel_mch
```
**Symbols:**

```
ffffffff818d9410-ffffffff818d94d3: pcibios_bus_to_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pcibios_bus_to_resource(struct pci_bus *bus, struct resource *res, struct pci_bus_region *region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffff8191c740)
Location: drivers/pci/host-bridge.c:76
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/quirks.c:quirk_io
  - drivers/pnp/quirks.c:quirk_intel_mch
```
**Symbols:**

```
ffffffff8191c740-ffffffff8191c803: pcibios_bus_to_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pcibios_bus_to_resource(struct pci_bus *bus, struct resource *res, struct pci_bus_region *region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffff81964b70)
Location: drivers/pci/host-bridge.c:76
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_read_bridge_mmio_pref
  - drivers/pci/probe.c:pci_read_bridge_mmio
  - drivers/pci/probe.c:pci_read_bridge_io
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/quirks.c:quirk_io
  - drivers/pnp/quirks.c:quirk_intel_mch
```
**Symbols:**

```
ffffffff81964b70-ffffffff81964c33: pcibios_bus_to_resource (STB_GLOBAL)
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
void pcibios_bus_to_resource(struct pci_bus *bus, struct resource *res, struct pci_bus_region *region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffff8000106e1210)
Location: drivers/pci/host-bridge.c:75
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/quirks.c:quirk_io
  - drivers/pnp/quirks.c:quirk_intel_mch
```
**Symbols:**

```
ffff8000106e1210-ffff8000106e12dc: pcibios_bus_to_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pcibios_bus_to_resource(struct pci_bus *bus, struct resource *res, struct pci_bus_region *region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (c087cec8)
Location: drivers/pci/host-bridge.c:75
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_resource
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/quirks.c:quirk_io
```
**Symbols:**

```
c087cec8-c087cf70: pcibios_bus_to_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pcibios_bus_to_resource(struct pci_bus *bus, struct resource *res, struct pci_bus_region *region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (c00000000085a430)
Location: drivers/pci/host-bridge.c:75
Inline: False
Direct callers:
  - arch/powerpc/kernel/pci_of_scan.c:of_scan_pci_bridge
  - arch/powerpc/kernel/pci_of_scan.c:of_create_pci_dev
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/quirks.c:quirk_io
```
**Symbols:**

```
c00000000085a430-c00000000085a4e4: pcibios_bus_to_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pcibios_bus_to_resource(struct pci_bus *bus, struct resource *res, struct pci_bus_region *region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffe0004b8e5e)
Location: drivers/pci/host-bridge.c:75
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/quirks.c:quirk_io
```
**Symbols:**

```
ffffffe0004b8e5e-ffffffe0004b8eee: pcibios_bus_to_resource (STB_GLOBAL)
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
void pcibios_bus_to_resource(struct pci_bus *bus, struct resource *res, struct pci_bus_region *region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffff81572e40)
Location: drivers/pci/host-bridge.c:75
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/quirks.c:quirk_io
  - drivers/pnp/quirks.c:quirk_intel_mch
```
**Symbols:**

```
ffffffff81572e40-ffffffff81572ed7: pcibios_bus_to_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pcibios_bus_to_resource(struct pci_bus *bus, struct resource *res, struct pci_bus_region *region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffff815615a0)
Location: drivers/pci/host-bridge.c:75
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/quirks.c:quirk_io
  - drivers/pnp/quirks.c:quirk_intel_mch
```
**Symbols:**

```
ffffffff815615a0-ffffffff81561637: pcibios_bus_to_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pcibios_bus_to_resource(struct pci_bus *bus, struct resource *res, struct pci_bus_region *region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffff81572670)
Location: drivers/pci/host-bridge.c:75
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/quirks.c:quirk_io
  - drivers/pnp/quirks.c:quirk_intel_mch
```
**Symbols:**

```
ffffffff81572670-ffffffff81572707: pcibios_bus_to_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pcibios_bus_to_resource(struct pci_bus *bus, struct resource *res, struct pci_bus_region *region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/host-bridge.c (ffffffff8158cb50)
Location: drivers/pci/host-bridge.c:75
Inline: False
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_setup_device
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/probe.c:__pci_read_base
  - drivers/pci/quirks.c:quirk_io_region
  - drivers/pci/quirks.c:quirk_io
  - drivers/pnp/quirks.c:quirk_intel_mch
```
**Symbols:**

```
ffffffff8158cb50-ffffffff8158cbe7: pcibios_bus_to_resource (STB_GLOBAL)
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
