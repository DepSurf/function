# Function: <code>to_nd_dax</code>

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
struct nd_dax *to_nd_dax(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dax_devs.c (ffffffff815f9114)
Location: drivers/nvdimm/dax_devs.c:45
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_release
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
```
**Symbols:**

```
ffffffff815f9360-ffffffff815f9394: to_nd_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct nd_dax *to_nd_dax(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dax_devs.c (ffffffff81627394)
Location: drivers/nvdimm/dax_devs.c:45
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_release
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
```
**Symbols:**

```
ffffffff816275e0-ffffffff81627614: to_nd_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nd_dax *to_nd_dax(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dax_devs.c (ffffffff8163c5a4)
Location: drivers/nvdimm/dax_devs.c:45
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_release
```
**Symbols:**

```
ffffffff8163c550-ffffffff8163c55d: to_nd_dax.part.1 (STB_LOCAL)
ffffffff8163c560-ffffffff8163c588: to_nd_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nd_dax *to_nd_dax(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dax_devs.c (ffffffff816a5234)
Location: drivers/nvdimm/dax_devs.c:45
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_release
```
**Symbols:**

```
ffffffff816a51e0-ffffffff816a51ed: to_nd_dax.part.1 (STB_LOCAL)
ffffffff816a51f0-ffffffff816a5218: to_nd_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nd_dax *to_nd_dax(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dax_devs.c (ffffffff816e1440)
Location: drivers/nvdimm/dax_devs.c:45
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_release
```
**Symbols:**

```
ffffffff816e13e0-ffffffff816e13ed: to_nd_dax.part.1 (STB_LOCAL)
ffffffff816e13f0-ffffffff816e1420: to_nd_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nd_dax *to_nd_dax(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dax_devs.c (ffffffff81703a90)
Location: drivers/nvdimm/dax_devs.c:45
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/dax_devs.c:nd_dax_release
```
**Symbols:**

```
ffffffff81703a30-ffffffff81703a3d: to_nd_dax.part.1 (STB_LOCAL)
ffffffff81703a40-ffffffff81703a70: to_nd_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nd_dax *to_nd_dax(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dax_devs.c (ffffffff8173d6c1)
Location: drivers/nvdimm/dax_devs.c:37
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/claim.c:to_nd_pfn_safe
  - drivers/nvdimm/dax_devs.c:nd_dax_release
```
**Symbols:**

```
ffffffff8173d969-ffffffff8173d982: to_nd_dax.part.0 (STB_LOCAL)
ffffffff8173d982-ffffffff8173d994: to_nd_dax.cold (STB_LOCAL)
ffffffff8173d670-ffffffff8173d69a: to_nd_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nd_dax *to_nd_dax(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dax_devs.c (ffffffff817614f1)
Location: drivers/nvdimm/dax_devs.c:37
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/claim.c:to_nd_pfn_safe
  - drivers/nvdimm/dax_devs.c:nd_dax_release
```
**Symbols:**

```
ffffffff81761490-ffffffff8176149d: to_nd_dax.part.0 (STB_LOCAL)
ffffffff817614a0-ffffffff817614d0: to_nd_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct nd_dax *to_nd_dax(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dax_devs.c (ffffffff81821361)
Location: drivers/nvdimm/dax_devs.c:26
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_release
  - drivers/nvdimm/dax_devs.c:nd_dax_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/claim.c:to_nd_pfn_safe
```
**Symbols:**

```
ffffffff81821150-ffffffff81821170: to_nd_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct nd_dax *to_nd_dax(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dax_devs.c (ffffffff81830071)
Location: drivers/nvdimm/dax_devs.c:26
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_release
  - drivers/nvdimm/dax_devs.c:nd_dax_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/claim.c:to_nd_pfn_safe
```
**Symbols:**

```
ffffffff8182fe60-ffffffff8182fe80: to_nd_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct nd_dax *to_nd_dax(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dax_devs.c (ffffffff81813301)
Location: drivers/nvdimm/dax_devs.c:26
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_release
  - drivers/nvdimm/dax_devs.c:nd_dax_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/claim.c:to_nd_pfn_safe
```
**Symbols:**

```
ffffffff818130f0-ffffffff81813110: to_nd_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct nd_dax *to_nd_dax(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dax_devs.c (ffffffff8189d951)
Location: drivers/nvdimm/dax_devs.c:26
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
ffffffff8189d750-ffffffff8189d770: to_nd_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct nd_dax *to_nd_dax(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dax_devs.c (ffffffff819e7361)
Location: drivers/nvdimm/dax_devs.c:26
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
ffffffff819e70f0-ffffffff819e7116: to_nd_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct nd_dax *to_nd_dax(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dax_devs.c (ffffffff81b63561)
Location: drivers/nvdimm/dax_devs.c:26
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
ffffffff81b632c0-ffffffff81b632e6: to_nd_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct nd_dax *to_nd_dax(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dax_devs.c (ffffffff81bb6b61)
Location: drivers/nvdimm/dax_devs.c:26
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
ffffffff81bb68a0-ffffffff81bb68c6: to_nd_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct nd_dax *to_nd_dax(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dax_devs.c (ffffffff81c0b1b1)
Location: drivers/nvdimm/dax_devs.c:26
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/claim.c:nd_namespace_store
```
**Symbols:**

```
ffffffff81c0aec0-ffffffff81c0aee6: to_nd_dax (STB_GLOBAL)
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
struct nd_dax *to_nd_dax(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dax_devs.c (c000000000a16d40)
Location: drivers/nvdimm/dax_devs.c:37
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/claim.c:to_nd_pfn_safe
  - drivers/nvdimm/dax_devs.c:nd_dax_release
```
**Symbols:**

```
c000000000a16d40-c000000000a16d7c: to_nd_dax (STB_GLOBAL)
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
struct nd_dax *to_nd_dax(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dax_devs.c (ffffffff81715be1)
Location: drivers/nvdimm/dax_devs.c:37
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/claim.c:to_nd_pfn_safe
  - drivers/nvdimm/dax_devs.c:nd_dax_release
```
**Symbols:**

```
ffffffff81715b80-ffffffff81715b8d: to_nd_dax.part.0 (STB_LOCAL)
ffffffff81715b90-ffffffff81715bc0: to_nd_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nd_dax *to_nd_dax(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dax_devs.c (ffffffff816e9661)
Location: drivers/nvdimm/dax_devs.c:37
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/claim.c:to_nd_pfn_safe
  - drivers/nvdimm/dax_devs.c:nd_dax_release
  - drivers/dax/pmem/core.c:__dax_pmem_probe
```
**Symbols:**

```
ffffffff816e9600-ffffffff816e960d: to_nd_dax.part.0 (STB_LOCAL)
ffffffff816e9610-ffffffff816e9640: to_nd_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nd_dax *to_nd_dax(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dax_devs.c (ffffffff817549b1)
Location: drivers/nvdimm/dax_devs.c:37
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/claim.c:to_nd_pfn_safe
  - drivers/nvdimm/dax_devs.c:nd_dax_release
```
**Symbols:**

```
ffffffff81754950-ffffffff8175495d: to_nd_dax.part.0 (STB_LOCAL)
ffffffff81754960-ffffffff81754990: to_nd_dax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nd_dax *to_nd_dax(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dax_devs.c (ffffffff8176fe21)
Location: drivers/nvdimm/dax_devs.c:37
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_release
Direct callers:
  - drivers/nvdimm/bus.c:nd_pmem_forget_poison_check
  - drivers/nvdimm/region_devs.c:nd_region_advance_seeds
  - drivers/nvdimm/namespace_devs.c:nvdimm_namespace_common_probe
  - drivers/nvdimm/claim.c:to_nd_pfn_safe
  - drivers/nvdimm/dax_devs.c:nd_dax_release
```
**Symbols:**

```
ffffffff8176fdc0-ffffffff8176fdcd: to_nd_dax.part.0 (STB_LOCAL)
ffffffff8176fdd0-ffffffff8176fe00: to_nd_dax (STB_GLOBAL)
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
