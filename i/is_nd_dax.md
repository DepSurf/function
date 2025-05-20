# Function: <code>is_nd_dax</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_dax(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dax_devs.c (ffffffff815f911d)
Location: drivers/nvdimm/dax_devs.c:39
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_release
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
```
**Symbols:**

```
ffffffff815f90e0-ffffffff815f90ff: is_nd_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_dax(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dax_devs.c (ffffffff8162739d)
Location: drivers/nvdimm/dax_devs.c:39
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_release
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
```
**Symbols:**

```
ffffffff81627360-ffffffff8162737f: is_nd_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_dax(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dax_devs.c (ffffffff8163c5ad)
Location: drivers/nvdimm/dax_devs.c:39
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
ffffffff8163c530-ffffffff8163c54d: is_nd_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_dax(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dax_devs.c (ffffffff816a523d)
Location: drivers/nvdimm/dax_devs.c:39
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
ffffffff816a51c0-ffffffff816a51dd: is_nd_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_dax(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dax_devs.c (ffffffff816e1440)
Location: drivers/nvdimm/dax_devs.c:39
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
```
**Symbols:**

```
ffffffff816e13c0-ffffffff816e13dd: is_nd_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_dax(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dax_devs.c (ffffffff81703a90)
Location: drivers/nvdimm/dax_devs.c:39
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
```
**Symbols:**

```
ffffffff81703a10-ffffffff81703a2d: is_nd_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_dax(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dax_devs.c (ffffffff8173d6c1)
Location: drivers/nvdimm/dax_devs.c:31
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
```
**Symbols:**

```
ffffffff8173d650-ffffffff8173d66d: is_nd_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_dax(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dax_devs.c (ffffffff817614f1)
Location: drivers/nvdimm/dax_devs.c:31
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
```
**Symbols:**

```
ffffffff81761470-ffffffff8176148d: is_nd_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_dax(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dax_devs.c (ffffffff81821361)
Location: drivers/nvdimm/dax_devs.c:41
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_detach_and_reset
  - drivers/nvdimm/claim.c:nd_detach_and_reset
  - drivers/nvdimm/pfn_devs.c:nd_pfn_init
```
**Symbols:**

```
ffffffff81821130-ffffffff8182114d: is_nd_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_dax(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dax_devs.c (ffffffff81830071)
Location: drivers/nvdimm/dax_devs.c:41
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_detach_and_reset
  - drivers/nvdimm/claim.c:nd_detach_and_reset
  - drivers/nvdimm/pfn_devs.c:nd_pfn_init
```
**Symbols:**

```
ffffffff8182fe40-ffffffff8182fe5d: is_nd_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_dax(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dax_devs.c (ffffffff81813301)
Location: drivers/nvdimm/dax_devs.c:41
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/pfn_devs.c:nd_pfn_init
```
**Symbols:**

```
ffffffff818130d0-ffffffff818130ed: is_nd_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_dax(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dax_devs.c (ffffffff8189d951)
Location: drivers/nvdimm/dax_devs.c:41
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/pfn_devs.c:nd_pfn_init
```
**Symbols:**

```
ffffffff8189d730-ffffffff8189d74d: is_nd_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_dax(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dax_devs.c (ffffffff819e7361)
Location: drivers/nvdimm/dax_devs.c:41
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/pfn_devs.c:nd_pfn_init
```
**Symbols:**

```
ffffffff819e70c0-ffffffff819e70e3: is_nd_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_dax(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dax_devs.c (ffffffff81b63561)
Location: drivers/nvdimm/dax_devs.c:41
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/pfn_devs.c:nd_pfn_init
```
**Symbols:**

```
ffffffff81b63280-ffffffff81b632a3: is_nd_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_dax(const struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dax_devs.c (ffffffff81bb6b61)
Location: drivers/nvdimm/dax_devs.c:41
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/pfn_devs.c:nd_pfn_init
```
**Symbols:**

```
ffffffff81bb6860-ffffffff81bb6883: is_nd_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_dax(const struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dax_devs.c (ffffffff81c0b1b1)
Location: drivers/nvdimm/dax_devs.c:41
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/pfn_devs.c:nd_pfn_init
```
**Symbols:**

```
ffffffff81c0ae80-ffffffff81c0aea3: is_nd_dax (STB_GLOBAL)
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
Location: drivers/nvdimm/nd.h:336
Inline: True
```
```
In drivers/nvdimm/region_devs.c (0)
Location: drivers/nvdimm/nd.h:336
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/nd.h:336
Inline: True
```
```
In drivers/nvdimm/claim.c (0)
Location: drivers/nvdimm/nd.h:336
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
bool is_nd_dax(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dax_devs.c (c000000000a16d5c)
Location: drivers/nvdimm/dax_devs.c:31
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:to_nd_dax
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
```
**Symbols:**

```
c000000000a16cf0-c000000000a16d38: is_nd_dax (STB_GLOBAL)
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
Location: drivers/nvdimm/nd.h:336
Inline: True
```
```
In drivers/nvdimm/region_devs.c (0)
Location: drivers/nvdimm/nd.h:336
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (0)
Location: drivers/nvdimm/nd.h:336
Inline: True
```
```
In drivers/nvdimm/claim.c (0)
Location: drivers/nvdimm/nd.h:336
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
bool is_nd_dax(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dax_devs.c (ffffffff81715be1)
Location: drivers/nvdimm/dax_devs.c:31
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
```
**Symbols:**

```
ffffffff81715b60-ffffffff81715b7d: is_nd_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_dax(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dax_devs.c (ffffffff816e9661)
Location: drivers/nvdimm/dax_devs.c:31
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
```
**Symbols:**

```
ffffffff816e95e0-ffffffff816e95fd: is_nd_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_dax(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dax_devs.c (ffffffff817549b1)
Location: drivers/nvdimm/dax_devs.c:31
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
```
**Symbols:**

```
ffffffff81754930-ffffffff8175494d: is_nd_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool is_nd_dax(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dax_devs.c (ffffffff8176fe21)
Location: drivers/nvdimm/dax_devs.c:31
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:mode_show
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/pfn_devs.c:nvdimm_setup_pfn
```
**Symbols:**

```
ffffffff8176fda0-ffffffff8176fdbd: is_nd_dax (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct device *dev</code> ➡️ <code>const struct device *dev</code>
</li>
</ul>
</details>
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
