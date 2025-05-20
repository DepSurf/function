# Function: <code>is_nd_blk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_blk(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff8159a12b)
Location: drivers/nvdimm/region_devs.c:64
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:to_nd_blk_region
  - drivers/nvdimm/region_devs.c:nd_region_notify_driver_action
  - drivers/nvdimm/region_devs.c:nd_region_notify_driver_action
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:nd_blk_region_init
Direct callers:
  - drivers/nvdimm/bus.c:to_bus_provider
  - drivers/nvdimm/bus.c:nvdimm_bus_uevent
  - drivers/nvdimm/namespace_devs.c:is_namespace_uuid_busy
  - drivers/nvdimm/namespace_devs.c:nd_region_create_blk_seed
```
**Symbols:**

```
ffffffff8159a9a0-ffffffff8159a9bf: is_nd_blk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_blk(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff815f0ba4)
Location: drivers/nvdimm/region_devs.c:152
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_blk_region_init
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:to_nd_blk_region
Direct callers:
  - drivers/nvdimm/bus.c:to_bus_provider
  - drivers/nvdimm/bus.c:nvdimm_bus_uevent
  - drivers/nvdimm/namespace_devs.c:nd_region_create_blk_seed
  - drivers/nvdimm/namespace_devs.c:is_namespace_uuid_busy
```
**Symbols:**

```
ffffffff815f0980-ffffffff815f099f: is_nd_blk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_blk(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff8161df64)
Location: drivers/nvdimm/region_devs.c:167
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_blk_region_init
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:to_nd_blk_region
Direct callers:
  - drivers/nvdimm/bus.c:to_bus_provider
  - drivers/nvdimm/bus.c:nvdimm_bus_uevent
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:is_namespace_uuid_busy
```
**Symbols:**

```
ffffffff8161d940-ffffffff8161d95f: is_nd_blk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_blk(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81632419)
Location: drivers/nvdimm/region_devs.c:166
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_blk_region_init
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:to_nd_blk_region
Direct callers:
  - drivers/nvdimm/bus.c:to_bus_provider
  - drivers/nvdimm/bus.c:nvdimm_bus_uevent
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
```
**Symbols:**

```
ffffffff81631dc0-ffffffff81631ddd: is_nd_blk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_blk(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff8169ad79)
Location: drivers/nvdimm/region_devs.c:166
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_blk_region_init
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:to_nd_blk_region
Direct callers:
  - drivers/nvdimm/bus.c:to_bus_provider
  - drivers/nvdimm/bus.c:nvdimm_bus_uevent
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
```
**Symbols:**

```
ffffffff8169a720-ffffffff8169a73d: is_nd_blk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_blk(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff816d7157)
Location: drivers/nvdimm/region_devs.c:166
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_blk_region_init
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:to_nd_blk_region
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_uevent
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
```
**Symbols:**

```
ffffffff816d69d0-ffffffff816d69ed: is_nd_blk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_blk(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff816f8fb7)
Location: drivers/nvdimm/region_devs.c:171
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_blk_region_init
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:to_nd_blk_region
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
```
**Symbols:**

```
ffffffff816f87b0-ffffffff816f87cd: is_nd_blk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_blk(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81732688)
Location: drivers/nvdimm/region_devs.c:163
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_blk_region_init
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:to_nd_blk_region
Direct callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
```
**Symbols:**

```
ffffffff81731e70-ffffffff81731e8d: is_nd_blk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_blk(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81756538)
Location: drivers/nvdimm/region_devs.c:163
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_blk_region_init
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:to_nd_blk_region
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
```
**Symbols:**

```
ffffffff81755fe0-ffffffff81755ffd: is_nd_blk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_blk(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81813a1d)
Location: drivers/nvdimm/region_devs.c:847
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_blk_region_init
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:to_nd_blk_region
  - drivers/nvdimm/region_devs.c:nd_region_release
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_dev_to_target_node
  - drivers/nvdimm/bus.c:nvdimm_dev_to_target_node
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
```
**Symbols:**

```
ffffffff818158f0-ffffffff8181590d: is_nd_blk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_blk(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81822c0d)
Location: drivers/nvdimm/region_devs.c:847
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_blk_region_init
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:to_nd_blk_region
  - drivers/nvdimm/region_devs.c:nd_region_release
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_dev_to_target_node
  - drivers/nvdimm/bus.c:nvdimm_dev_to_target_node
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
```
**Symbols:**

```
ffffffff81824ae0-ffffffff81824afd: is_nd_blk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_blk(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81805bbd)
Location: drivers/nvdimm/region_devs.c:854
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_blk_region_init
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:to_nd_blk_region
  - drivers/nvdimm/region_devs.c:nd_region_release
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_dev_to_target_node
  - drivers/nvdimm/bus.c:nvdimm_dev_to_target_node
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
```
**Symbols:**

```
ffffffff81807e70-ffffffff81807e8d: is_nd_blk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_blk(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81890c7f)
Location: drivers/nvdimm/region_devs.c:854
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_region_create
  - drivers/nvdimm/region_devs.c:nd_blk_region_init
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:nd_region_release
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_dev_to_target_node
  - drivers/nvdimm/bus.c:nvdimm_dev_to_target_node
  - drivers/nvdimm/bus.c:nvdimm_bus_remove
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
```
**Symbols:**

```
ffffffff81892610-ffffffff8189262d: is_nd_blk (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_blk(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffff80001095797c)
Location: drivers/nvdimm/region_devs.c:163
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_blk_region_init
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:to_nd_blk_region
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
```
**Symbols:**

```
ffff800010957338-ffff80001095737c: is_nd_blk (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_blk(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (c000000000a05ba0)
Location: drivers/nvdimm/region_devs.c:163
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_blk_region_init
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:to_nd_blk_region
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
```
**Symbols:**

```
c000000000a052c0-c000000000a05308: is_nd_blk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_blk(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffe0005c68cc)
Location: drivers/nvdimm/region_devs.c:163
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_blk_region_init
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:to_nd_blk_region
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
```
**Symbols:**

```
ffffffe0005c63ce-ffffffe0005c6402: is_nd_blk (STB_GLOBAL)
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
bool is_nd_blk(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff8170ac28)
Location: drivers/nvdimm/region_devs.c:163
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_blk_region_init
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:to_nd_blk_region
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
```
**Symbols:**

```
ffffffff8170a6d0-ffffffff8170a6ed: is_nd_blk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_blk(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff816de6a8)
Location: drivers/nvdimm/region_devs.c:163
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_blk_region_init
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:to_nd_blk_region
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
```
**Symbols:**

```
ffffffff816de150-ffffffff816de16d: is_nd_blk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_blk(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff817499f8)
Location: drivers/nvdimm/region_devs.c:163
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_blk_region_init
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:to_nd_blk_region
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
```
**Symbols:**

```
ffffffff817494a0-ffffffff817494bd: is_nd_blk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_blk(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81764e78)
Location: drivers/nvdimm/region_devs.c:163
Inline: True
Inline callers:
  - drivers/nvdimm/region_devs.c:nd_blk_region_init
  - drivers/nvdimm/region_devs.c:nd_region_allocatable_dpa
  - drivers/nvdimm/region_devs.c:nd_region_available_dpa
  - drivers/nvdimm/region_devs.c:to_nd_blk_region
Direct callers:
  - drivers/nvdimm/bus.c:nvdimm_bus_probe
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
```
**Symbols:**

```
ffffffff81764920-ffffffff8176493d: is_nd_blk (STB_GLOBAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
