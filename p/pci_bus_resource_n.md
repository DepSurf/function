# Function: <code>pci_bus_resource_n</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct resource *pci_bus_resource_n(const struct pci_bus *bus, int n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/bus.c (ffffffff8142f290)
Location: drivers/pci/bus.c:64
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/bus.c:pci_bus_clip_resource
Direct callers:
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/setup-bus.c:find_free_bus_resource
  - drivers/pci/setup-bus.c:find_free_bus_resource
  - drivers/pci/setup-bus.c:pci_bus_dump_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
```
**Symbols:**

```
ffffffff8142f290-ffffffff8142f2d1: pci_bus_resource_n.part.1 (STB_LOCAL)
ffffffff8142f2e0-ffffffff8142f2fe: pci_bus_resource_n (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct resource *pci_bus_resource_n(const struct pci_bus *bus, int n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/bus.c (ffffffff8147adab)
Location: drivers/pci/bus.c:64
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_alloc_from_region
Direct callers:
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/setup-bus.c:pci_bus_dump_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/setup-bus.c:find_free_bus_resource
  - drivers/pci/setup-bus.c:find_free_bus_resource
```
**Symbols:**

```
ffffffff8147a900-ffffffff8147a941: pci_bus_resource_n.part.1 (STB_LOCAL)
ffffffff8147a950-ffffffff8147a96e: pci_bus_resource_n (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct resource *pci_bus_resource_n(const struct pci_bus *bus, int n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/bus.c (ffffffff8149c22d)
Location: drivers/pci/bus.c:64
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_alloc_from_region
Direct callers:
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/setup-bus.c:pci_bus_dump_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/setup-bus.c:find_free_bus_resource
  - drivers/pci/setup-bus.c:find_free_bus_resource
```
**Symbols:**

```
ffffffff8149bd80-ffffffff8149bdc1: pci_bus_resource_n.part.3 (STB_LOCAL)
ffffffff8149bdd0-ffffffff8149bdee: pci_bus_resource_n (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct resource *pci_bus_resource_n(const struct pci_bus *bus, int n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/bus.c (ffffffff814a5fdb)
Location: drivers/pci/bus.c:64
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_alloc_from_region
Direct callers:
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/setup-bus.c:pci_bus_dump_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/setup-bus.c:find_free_bus_resource
  - drivers/pci/setup-bus.c:find_free_bus_resource
```
**Symbols:**

```
ffffffff814a5b60-ffffffff814a5ba1: pci_bus_resource_n.part.3 (STB_LOCAL)
ffffffff814a5bb0-ffffffff814a5bce: pci_bus_resource_n (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct resource *pci_bus_resource_n(const struct pci_bus *bus, int n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/bus.c (ffffffff814e4e16)
Location: drivers/pci/bus.c:64
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_alloc_from_region
Direct callers:
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/setup-bus.c:pci_bus_dump_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/setup-bus.c:find_free_bus_resource
  - drivers/pci/setup-bus.c:find_free_bus_resource
```
**Symbols:**

```
ffffffff814e49a0-ffffffff814e49e1: pci_bus_resource_n.part.3 (STB_LOCAL)
ffffffff814e49f0-ffffffff814e4a0e: pci_bus_resource_n (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct resource *pci_bus_resource_n(const struct pci_bus *bus, int n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/bus.c (ffffffff815142e8)
Location: drivers/pci/bus.c:63
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_alloc_from_region
Direct callers:
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/setup-bus.c:pci_bus_dump_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/setup-bus.c:find_free_bus_resource
  - drivers/pci/setup-bus.c:find_free_bus_resource
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
```
**Symbols:**

```
ffffffff81513e80-ffffffff81513ec0: pci_bus_resource_n.part.4 (STB_LOCAL)
ffffffff81513ec0-ffffffff81513ede: pci_bus_resource_n (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct resource *pci_bus_resource_n(const struct pci_bus *bus, int n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/bus.c (ffffffff81529a4e)
Location: drivers/pci/bus.c:63
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_alloc_from_region
Direct callers:
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/setup-bus.c:pci_bus_dump_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/setup-bus.c:find_free_bus_resource
  - drivers/pci/setup-bus.c:find_free_bus_resource
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
```
**Symbols:**

```
ffffffff815295e0-ffffffff81529620: pci_bus_resource_n.part.4 (STB_LOCAL)
ffffffff81529620-ffffffff8152963e: pci_bus_resource_n (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct resource *pci_bus_resource_n(const struct pci_bus *bus, int n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/bus.c (ffffffff81558cbb)
Location: drivers/pci/bus.c:63
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_alloc_from_region
Direct callers:
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/setup-bus.c:pci_bus_dump_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/setup-bus.c:find_free_bus_resource
  - drivers/pci/setup-bus.c:find_free_bus_resource
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
```
**Symbols:**

```
ffffffff81558860-ffffffff815588a0: pci_bus_resource_n.part.0 (STB_LOCAL)
ffffffff815588a0-ffffffff815588be: pci_bus_resource_n (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct resource *pci_bus_resource_n(const struct pci_bus *bus, int n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/bus.c (ffffffff8157a24d)
Location: drivers/pci/bus.c:63
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_alloc_from_region
Direct callers:
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/setup-bus.c:pci_bus_dump_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/setup-bus.c:find_free_bus_resource
  - drivers/pci/setup-bus.c:find_free_bus_resource
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
```
**Symbols:**

```
ffffffff81579df0-ffffffff81579e30: pci_bus_resource_n.part.0 (STB_LOCAL)
ffffffff81579e30-ffffffff81579e4e: pci_bus_resource_n (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct resource *pci_bus_resource_n(const struct pci_bus *bus, int n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff8161f32e)
Location: drivers/pci/bus.c:63
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/bus.c:pci_bus_alloc_from_region
Direct callers:
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/setup-bus.c:pci_bus_dump_resources
  - drivers/pci/setup-bus.c:assign_fixed_resource_on_bus
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:find_bus_resource_of_type
  - drivers/pci/setup-bus.c:find_bus_resource_of_type
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/eisa/pci_eisa.c:pci_eisa_init
```
**Symbols:**

```
ffffffff8161ee40-ffffffff8161ee8c: pci_bus_resource_n (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct resource *pci_bus_resource_n(const struct pci_bus *bus, int n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff81645b1e)
Location: drivers/pci/bus.c:63
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/bus.c:pci_bus_alloc_from_region
Direct callers:
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/setup-bus.c:pci_bus_dump_resources
  - drivers/pci/setup-bus.c:assign_fixed_resource_on_bus
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:find_bus_resource_of_type
  - drivers/pci/setup-bus.c:find_bus_resource_of_type
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/eisa/pci_eisa.c:pci_eisa_init
```
**Symbols:**

```
ffffffff81645630-ffffffff8164567c: pci_bus_resource_n (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct resource *pci_bus_resource_n(const struct pci_bus *bus, int n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff81628861)
Location: drivers/pci/bus.c:63
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/bus.c:pci_bus_alloc_from_region
Direct callers:
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/setup-bus.c:pci_bus_dump_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:find_bus_resource_of_type
  - drivers/pci/setup-bus.c:find_bus_resource_of_type
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
```
**Symbols:**

```
ffffffff81628370-ffffffff816283bc: pci_bus_resource_n (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct resource *pci_bus_resource_n(const struct pci_bus *bus, int n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff816981aa)
Location: drivers/pci/bus.c:63
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/bus.c:pci_bus_alloc_from_region
Direct callers:
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/setup-bus.c:pci_bus_dump_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:find_bus_resource_of_type
  - drivers/pci/setup-bus.c:find_bus_resource_of_type
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
```
**Symbols:**

```
ffffffff81697c70-ffffffff81697cec: pci_bus_resource_n (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct resource *pci_bus_resource_n(const struct pci_bus *bus, int n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff817b946a)
Location: drivers/pci/bus.c:63
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/bus.c:pci_bus_alloc_from_region
Direct callers:
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/setup-bus.c:pci_bus_dump_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:find_bus_resource_of_type
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
```
**Symbols:**

```
ffffffff817b8e50-ffffffff817b8ef0: pci_bus_resource_n (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct resource *pci_bus_resource_n(const struct pci_bus *bus, int n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff818d3feb)
Location: drivers/pci/bus.c:63
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/bus.c:pci_bus_alloc_from_region
Direct callers:
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/setup-bus.c:pci_bus_dump_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:find_bus_resource_of_type
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
```
**Symbols:**

```
ffffffff818d3920-ffffffff818d39c0: pci_bus_resource_n (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct resource *pci_bus_resource_n(const struct pci_bus *bus, int n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff8191722b)
Location: drivers/pci/bus.c:64
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/bus.c:pci_bus_alloc_from_region
Direct callers:
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/setup-bus.c:pci_bus_dump_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:find_bus_resource_of_type
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
```
**Symbols:**

```
ffffffff81916a50-ffffffff81916af0: pci_bus_resource_n (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct resource *pci_bus_resource_n(const struct pci_bus *bus, int n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/bus.c (ffffffff8195f330)
Location: drivers/pci/bus.c:64
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/bus.c:pci_bus_alloc_from_region
Direct callers:
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/setup-bus.c:pci_bus_dump_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_size_bridges
  - drivers/pci/setup-bus.c:find_bus_resource_of_type
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
```
**Symbols:**

```
ffffffff8195eb20-ffffffff8195ebc0: pci_bus_resource_n (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct resource *pci_bus_resource_n(const struct pci_bus *bus, int n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/bus.c (ffff8000106dcb1c)
Location: drivers/pci/bus.c:63
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_alloc_from_region
Direct callers:
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/setup-bus.c:pci_bus_dump_resources
  - drivers/pci/setup-bus.c:pci_bus_dump_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/setup-bus.c:find_free_bus_resource
  - drivers/pci/setup-bus.c:find_free_bus_resource
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
```
**Symbols:**

```
ffff8000106dc5e8-ffff8000106dc664: pci_bus_resource_n.part.0 (STB_LOCAL)
ffff8000106dc668-ffff8000106dc6b8: pci_bus_resource_n (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct resource *pci_bus_resource_n(const struct pci_bus *bus, int n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/bus.c (c087870c)
Location: drivers/pci/bus.c:63
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_alloc_resource
Direct callers:
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_alloc_resource
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/setup-bus.c:pci_bus_dump_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/setup-bus.c:find_free_bus_resource
  - drivers/pci/setup-bus.c:find_free_bus_resource
```
**Symbols:**

```
c0878390-c08783ec: pci_bus_resource_n.part.0 (STB_LOCAL)
c08783ec-c087841c: pci_bus_resource_n (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct resource *pci_bus_resource_n(const struct pci_bus *bus, int n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/bus.c (c000000000854bdc)
Location: drivers/pci/bus.c:63
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_alloc_from_region
Direct callers:
  - arch/powerpc/kernel/pci-common.c:pcibios_allocate_bus_resources
  - arch/powerpc/kernel/pci-common.c:pcibios_setup_bus_self
  - arch/powerpc/kernel/pci-common.c:pcibios_setup_bus_self
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/setup-bus.c:pci_bus_dump_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/setup-bus.c:find_free_bus_resource
```
**Symbols:**

```
c0000000008545e0-c000000000854648: pci_bus_resource_n.part.0 (STB_LOCAL)
c000000000854650-c000000000854680: pci_bus_resource_n (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct resource *pci_bus_resource_n(const struct pci_bus *bus, int n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/bus.c (ffffffe0004b4fc6)
Location: drivers/pci/bus.c:63
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_alloc_from_region
Direct callers:
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/setup-bus.c:pci_bus_dump_resources
  - drivers/pci/setup-bus.c:pci_bus_dump_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/setup-bus.c:find_free_bus_resource
  - drivers/pci/setup-bus.c:find_free_bus_resource
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
```
**Symbols:**

```
ffffffe0004b4ba4-ffffffe0004b4c08: pci_bus_resource_n.part.0 (STB_LOCAL)
ffffffe0004b4c08-ffffffe0004b4c54: pci_bus_resource_n (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct resource *pci_bus_resource_n(const struct pci_bus *bus, int n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/bus.c (ffffffff8156e76b)
Location: drivers/pci/bus.c:63
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_alloc_from_region
Direct callers:
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/setup-bus.c:pci_bus_dump_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/setup-bus.c:find_free_bus_resource
  - drivers/pci/setup-bus.c:find_free_bus_resource
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
```
**Symbols:**

```
ffffffff8156e310-ffffffff8156e350: pci_bus_resource_n.part.0 (STB_LOCAL)
ffffffff8156e350-ffffffff8156e36e: pci_bus_resource_n (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct resource *pci_bus_resource_n(const struct pci_bus *bus, int n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/bus.c (ffffffff8155cecd)
Location: drivers/pci/bus.c:63
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_alloc_from_region
Direct callers:
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/setup-bus.c:pci_bus_dump_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/setup-bus.c:find_free_bus_resource
  - drivers/pci/setup-bus.c:find_free_bus_resource
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
```
**Symbols:**

```
ffffffff8155ca70-ffffffff8155cab0: pci_bus_resource_n.part.0 (STB_LOCAL)
ffffffff8155cab0-ffffffff8155cace: pci_bus_resource_n (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct resource *pci_bus_resource_n(const struct pci_bus *bus, int n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/bus.c (ffffffff8156df9d)
Location: drivers/pci/bus.c:63
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_alloc_from_region
Direct callers:
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/setup-bus.c:pci_bus_dump_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/setup-bus.c:find_free_bus_resource
  - drivers/pci/setup-bus.c:find_free_bus_resource
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
```
**Symbols:**

```
ffffffff8156db40-ffffffff8156db80: pci_bus_resource_n.part.0 (STB_LOCAL)
ffffffff8156db80-ffffffff8156db9e: pci_bus_resource_n (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct resource *pci_bus_resource_n(const struct pci_bus *bus, int n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/bus.c (ffffffff8158847d)
Location: drivers/pci/bus.c:63
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_alloc_from_region
Direct callers:
  - drivers/pci/bus.c:pci_bus_clip_resource
  - drivers/pci/bus.c:pci_bus_alloc_from_region
  - drivers/pci/probe.c:pci_read_bridge_bases
  - drivers/pci/pci.c:pci_find_parent_resource
  - drivers/pci/setup-bus.c:pci_bus_dump_resources
  - drivers/pci/setup-bus.c:__pci_bus_assign_resources
  - drivers/pci/setup-bus.c:find_free_bus_resource
  - drivers/pci/setup-bus.c:find_free_bus_resource
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl
  - drivers/eisa/pci_eisa.c:pci_eisa_init_early
```
**Symbols:**

```
ffffffff81588020-ffffffff81588060: pci_bus_resource_n.part.0 (STB_LOCAL)
ffffffff81588060-ffffffff8158807e: pci_bus_resource_n (STB_GLOBAL)
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
