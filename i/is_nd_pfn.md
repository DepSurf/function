# Function: <code>is_nd_pfn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_pfn(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff815a1960)
Location: drivers/nvdimm/pfn_devs.c:41
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/pfn_devs.c:uuid_store
  - drivers/nvdimm/pfn_devs.c:namespace_store
  - drivers/nvdimm/pfn_devs.c:namespace_show
  - drivers/nvdimm/pfn_devs.c:mode_store
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
Direct callers:
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_disk_name
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
ffffffff815a1960-ffffffff815a197f: is_nd_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_pfn(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff815f8fb7)
Location: drivers/nvdimm/pfn_devs.c:42
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
ffffffff815f7cf0-ffffffff815f7d0f: is_nd_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_pfn(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff81627237)
Location: drivers/nvdimm/pfn_devs.c:42
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
ffffffff81625f60-ffffffff81625f7f: is_nd_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_pfn(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff8163c404)
Location: drivers/nvdimm/pfn_devs.c:42
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
ffffffff8163b120-ffffffff8163b13d: is_nd_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_pfn(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff816a5094)
Location: drivers/nvdimm/pfn_devs.c:42
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
ffffffff816a3d30-ffffffff816a3d4d: is_nd_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_pfn(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff816e1282)
Location: drivers/nvdimm/pfn_devs.c:42
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
ffffffff816dfe80-ffffffff816dfe9d: is_nd_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_pfn(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff817038d2)
Location: drivers/nvdimm/pfn_devs.c:42
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
ffffffff81702240-ffffffff8170225d: is_nd_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_pfn(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff8173d393)
Location: drivers/nvdimm/pfn_devs.c:34
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
ffffffff8173c160-ffffffff8173c17d: is_nd_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_pfn(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff817611e3)
Location: drivers/nvdimm/pfn_devs.c:34
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
ffffffff8175fde0-ffffffff8175fdfd: is_nd_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_pfn(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff81820e0f)
Location: drivers/nvdimm/pfn_devs.c:289
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_detach_and_reset
  - drivers/nvdimm/claim.c:nd_detach_and_reset
```
**Symbols:**

```
ffffffff8181f8f0-ffffffff8181f90d: is_nd_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_pfn(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff8182fcff)
Location: drivers/nvdimm/pfn_devs.c:289
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_detach_and_reset
  - drivers/nvdimm/claim.c:nd_detach_and_reset
```
**Symbols:**

```
ffffffff8182e820-ffffffff8182e83d: is_nd_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_pfn(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff81812f8f)
Location: drivers/nvdimm/pfn_devs.c:289
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
ffffffff81811af0-ffffffff81811b0d: is_nd_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_pfn(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff8189d5ef)
Location: drivers/nvdimm/pfn_devs.c:289
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
ffffffff8189c100-ffffffff8189c11d: is_nd_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_pfn(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff819e6f48)
Location: drivers/nvdimm/pfn_devs.c:288
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:pmem_should_map_pages
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
ffffffff819e5960-ffffffff819e5983: is_nd_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_pfn(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff81b630e8)
Location: drivers/nvdimm/pfn_devs.c:290
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:pmem_should_map_pages
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
ffffffff81b61840-ffffffff81b61863: is_nd_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_pfn(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff81bb66c8)
Location: drivers/nvdimm/pfn_devs.c:290
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:pmem_should_map_pages
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
ffffffff81bb4e40-ffffffff81bb4e63: is_nd_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_pfn(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff81c0ace8)
Location: drivers/nvdimm/pfn_devs.c:290
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:pmem_should_map_pages
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
ffffffff81c093c0-ffffffff81c093e3: is_nd_pfn (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (0)
Location: drivers/nvdimm/nd.h:308
Inline: True
```
```
In drivers/nvdimm/region_devs.c (0)
Location: drivers/nvdimm/nd.h:308
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/nd.h:308
Inline: True
```
```
In drivers/nvdimm/claim.c (0)
Location: drivers/nvdimm/nd.h:308
Inline: True
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
bool is_nd_pfn(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (c000000000a14e6c)
Location: drivers/nvdimm/pfn_devs.c:34
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:to_nd_pfn
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
c000000000a14dc0-c000000000a14e08: is_nd_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (0)
Location: drivers/nvdimm/nd.h:308
Inline: True
```
```
In drivers/nvdimm/region_devs.c (0)
Location: drivers/nvdimm/nd.h:308
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/nd.h:308
Inline: True
```
```
In drivers/nvdimm/claim.c (0)
Location: drivers/nvdimm/nd.h:308
Inline: True
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
bool is_nd_pfn(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff817158d3)
Location: drivers/nvdimm/pfn_devs.c:34
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
ffffffff817144d0-ffffffff817144ed: is_nd_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_pfn(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff816e9353)
Location: drivers/nvdimm/pfn_devs.c:34
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/pmem.c:nd_pmem_probe
  - drivers/nvdimm/pmem.c:pmem_attach_disk
  - drivers/nvdimm/pmem.c:pmem_attach_disk
```
**Symbols:**

```
ffffffff816e7f50-ffffffff816e7f6d: is_nd_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_pfn(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff817546a3)
Location: drivers/nvdimm/pfn_devs.c:34
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
ffffffff817532a0-ffffffff817532bd: is_nd_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_pfn(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff8176fb13)
Location: drivers/nvdimm/pfn_devs.c:34
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
ffffffff8176e710-ffffffff8176e72d: is_nd_pfn (STB_GLOBAL)
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
