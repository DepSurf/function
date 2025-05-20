# Function: <code>to_nd_pfn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nd_pfn *to_nd_pfn(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff815a1b60)
Location: drivers/nvdimm/pfn_devs.c:47
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
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/claim.c:nd_namespace_store
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/pfn_devs.c:uuid_store
  - drivers/nvdimm/pfn_devs.c:namespace_store
  - drivers/nvdimm/pfn_devs.c:namespace_show
  - drivers/nvdimm/pfn_devs.c:mode_store
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
```
**Symbols:**

```
ffffffff815a1b60-ffffffff815a1b7c: to_nd_pfn.part.3 (STB_LOCAL)
ffffffff815a1b80-ffffffff815a1ba8: to_nd_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct nd_pfn *to_nd_pfn(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff815f8fb7)
Location: drivers/nvdimm/pfn_devs.c:48
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
```
**Symbols:**

```
ffffffff815f8da0-ffffffff815f8dd4: to_nd_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct nd_pfn *to_nd_pfn(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff81627237)
Location: drivers/nvdimm/pfn_devs.c:48
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
```
**Symbols:**

```
ffffffff81627020-ffffffff81627054: to_nd_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nd_pfn *to_nd_pfn(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff8163c404)
Location: drivers/nvdimm/pfn_devs.c:48
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
```
**Symbols:**

```
ffffffff8163b970-ffffffff8163b97d: to_nd_pfn.part.2 (STB_LOCAL)
ffffffff8163b980-ffffffff8163b9a8: to_nd_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nd_pfn *to_nd_pfn(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff816a5094)
Location: drivers/nvdimm/pfn_devs.c:48
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
```
**Symbols:**

```
ffffffff816a4710-ffffffff816a471d: to_nd_pfn.part.3 (STB_LOCAL)
ffffffff816a4720-ffffffff816a4748: to_nd_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nd_pfn *to_nd_pfn(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff816e127e)
Location: drivers/nvdimm/pfn_devs.c:48
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
```
**Symbols:**

```
ffffffff816e0f20-ffffffff816e0f2d: to_nd_pfn.part.3 (STB_LOCAL)
ffffffff816e0f30-ffffffff816e0f60: to_nd_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nd_pfn *to_nd_pfn(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff817038ce)
Location: drivers/nvdimm/pfn_devs.c:48
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
```
**Symbols:**

```
ffffffff81703570-ffffffff8170357d: to_nd_pfn.part.3 (STB_LOCAL)
ffffffff81703580-ffffffff817035b0: to_nd_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nd_pfn *to_nd_pfn(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff8173d38e)
Location: drivers/nvdimm/pfn_devs.c:40
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
```
**Symbols:**

```
ffffffff8173d5f3-ffffffff8173d60c: to_nd_pfn.part.0 (STB_LOCAL)
ffffffff8173d60c-ffffffff8173d61e: to_nd_pfn.cold (STB_LOCAL)
ffffffff8173d030-ffffffff8173d05a: to_nd_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nd_pfn *to_nd_pfn(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff817611de)
Location: drivers/nvdimm/pfn_devs.c:40
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
```
**Symbols:**

```
ffffffff81760e50-ffffffff81760e5d: to_nd_pfn.part.0 (STB_LOCAL)
ffffffff81760e60-ffffffff81760e90: to_nd_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct nd_pfn *to_nd_pfn(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff81820e0a)
Location: drivers/nvdimm/pfn_devs.c:29
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
```
**Symbols:**

```
ffffffff81820ab0-ffffffff81820ad0: to_nd_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct nd_pfn *to_nd_pfn(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff8182fcfa)
Location: drivers/nvdimm/pfn_devs.c:29
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
```
**Symbols:**

```
ffffffff8182f9a0-ffffffff8182f9c0: to_nd_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct nd_pfn *to_nd_pfn(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff81812f8a)
Location: drivers/nvdimm/pfn_devs.c:29
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
```
**Symbols:**

```
ffffffff81812c30-ffffffff81812c50: to_nd_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct nd_pfn *to_nd_pfn(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff8189d5ea)
Location: drivers/nvdimm/pfn_devs.c:29
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
ffffffff8189c120-ffffffff8189c140: to_nd_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct nd_pfn *to_nd_pfn(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff819e6f44)
Location: drivers/nvdimm/pfn_devs.c:28
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
ffffffff819e5990-ffffffff819e59b6: to_nd_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct nd_pfn *to_nd_pfn(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff81b630e4)
Location: drivers/nvdimm/pfn_devs.c:30
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
ffffffff81b61880-ffffffff81b618a6: to_nd_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct nd_pfn *to_nd_pfn(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff81bb66c4)
Location: drivers/nvdimm/pfn_devs.c:30
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
ffffffff81bb4e80-ffffffff81bb4ea6: to_nd_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct nd_pfn *to_nd_pfn(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff81c0ace4)
Location: drivers/nvdimm/pfn_devs.c:30
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
ffffffff81c09400-ffffffff81c09426: to_nd_pfn (STB_GLOBAL)
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
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct nd_pfn *to_nd_pfn(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (c000000000a14e50)
Location: drivers/nvdimm/pfn_devs.c:40
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
```
**Symbols:**

```
c000000000a14e50-c000000000a14e8c: to_nd_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nd_pfn *to_nd_pfn(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff817158ce)
Location: drivers/nvdimm/pfn_devs.c:40
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
```
**Symbols:**

```
ffffffff81715540-ffffffff8171554d: to_nd_pfn.part.0 (STB_LOCAL)
ffffffff81715550-ffffffff81715580: to_nd_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nd_pfn *to_nd_pfn(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff816e934e)
Location: drivers/nvdimm/pfn_devs.c:40
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
  - drivers/nvdimm/pmem.c:pmem_attach_disk
```
**Symbols:**

```
ffffffff816e8fc0-ffffffff816e8fcd: to_nd_pfn.part.0 (STB_LOCAL)
ffffffff816e8fd0-ffffffff816e9000: to_nd_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nd_pfn *to_nd_pfn(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff8175469e)
Location: drivers/nvdimm/pfn_devs.c:40
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
```
**Symbols:**

```
ffffffff81754310-ffffffff8175431d: to_nd_pfn.part.0 (STB_LOCAL)
ffffffff81754320-ffffffff81754350: to_nd_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nd_pfn *to_nd_pfn(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff8176fb0e)
Location: drivers/nvdimm/pfn_devs.c:40
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:is_uuid_busy
  - drivers/nvdimm/pfn_devs.c:nd_pfn_probe
  - drivers/nvdimm/pfn_devs.c:nd_pfn_release
```
**Symbols:**

```
ffffffff8176f780-ffffffff8176f78d: to_nd_pfn.part.0 (STB_LOCAL)
ffffffff8176f790-ffffffff8176f7c0: to_nd_pfn (STB_GLOBAL)
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
