# Function: <code>nd_region_create</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct nd_region *nd_region_create(struct nvdimm_bus *nvdimm_bus, struct nd_region_desc *ndr_desc, struct device_type *dev_type, const char *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff8159a5b0)
Location: drivers/nvdimm/region_devs.c:627
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nvdimm_pmem_region_create
  - drivers/nvdimm/region_devs.c:nvdimm_volatile_region_create
```
**Symbols:**

```
ffffffff8159a5b0-ffffffff8159a8d5: nd_region_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct nd_region *nd_region_create(struct nvdimm_bus *nvdimm_bus, struct nd_region_desc *ndr_desc, struct device_type *dev_type, const char *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff815f02f0)
Location: drivers/nvdimm/region_devs.c:751
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nvdimm_volatile_region_create
  - drivers/nvdimm/region_devs.c:nvdimm_pmem_region_create
```
**Symbols:**

```
ffffffff815f02f0-ffffffff815f0601: nd_region_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct nd_region *nd_region_create(struct nvdimm_bus *nvdimm_bus, struct nd_region_desc *ndr_desc, struct device_type *dev_type, const char *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff8161d200)
Location: drivers/nvdimm/region_devs.c:795
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nvdimm_volatile_region_create
  - drivers/nvdimm/region_devs.c:nvdimm_pmem_region_create
```
**Symbols:**

```
ffffffff8161d200-ffffffff8161d53c: nd_region_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct nd_region *nd_region_create(struct nvdimm_bus *nvdimm_bus, struct nd_region_desc *ndr_desc, struct device_type *dev_type, const char *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81631650)
Location: drivers/nvdimm/region_devs.c:896
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nvdimm_volatile_region_create
  - drivers/nvdimm/region_devs.c:nvdimm_blk_region_create
  - drivers/nvdimm/region_devs.c:nvdimm_pmem_region_create
```
**Symbols:**

```
ffffffff81631650-ffffffff816319c3: nd_region_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct nd_region *nd_region_create(struct nvdimm_bus *nvdimm_bus, struct nd_region_desc *ndr_desc, struct device_type *dev_type, const char *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81699f80)
Location: drivers/nvdimm/region_devs.c:916
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nvdimm_volatile_region_create
  - drivers/nvdimm/region_devs.c:nvdimm_blk_region_create
  - drivers/nvdimm/region_devs.c:nvdimm_pmem_region_create
```
**Symbols:**

```
ffffffff81699f80-ffffffff8169a322: nd_region_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct nd_region *nd_region_create(struct nvdimm_bus *nvdimm_bus, struct nd_region_desc *ndr_desc, struct device_type *dev_type, const char *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff816d6260)
Location: drivers/nvdimm/region_devs.c:955
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nvdimm_volatile_region_create
  - drivers/nvdimm/region_devs.c:nvdimm_pmem_region_create
```
**Symbols:**

```
ffffffff816d6260-ffffffff816d65f5: nd_region_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct nd_region *nd_region_create(struct nvdimm_bus *nvdimm_bus, struct nd_region_desc *ndr_desc, struct device_type *dev_type, const char *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff816f8010)
Location: drivers/nvdimm/region_devs.c:983
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nvdimm_volatile_region_create
  - drivers/nvdimm/region_devs.c:nvdimm_pmem_region_create
```
**Symbols:**

```
ffffffff816f8010-ffffffff816f83a8: nd_region_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct nd_region *nd_region_create(struct nvdimm_bus *nvdimm_bus, struct nd_region_desc *ndr_desc, struct device_type *dev_type, const char *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/region_devs.c (0)
Location: drivers/nvdimm/region_devs.c:981
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nvdimm_volatile_region_create
  - drivers/nvdimm/region_devs.c:nvdimm_pmem_region_create
```
**Symbols:**

```
ffffffff81731700-ffffffff81731a79: nd_region_create (STB_LOCAL)
ffffffff81732a5e-ffffffff81732ab4: nd_region_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct nd_region *nd_region_create(struct nvdimm_bus *nvdimm_bus, struct nd_region_desc *ndr_desc, struct device_type *dev_type, const char *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/region_devs.c (0)
Location: drivers/nvdimm/region_devs.c:933
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nvdimm_volatile_region_create
  - drivers/nvdimm/region_devs.c:nvdimm_pmem_region_create
```
**Symbols:**

```
ffffffff81755870-ffffffff81755be7: nd_region_create (STB_LOCAL)
ffffffff8175679e-ffffffff817567fa: nd_region_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct nd_region *nd_region_create(struct nvdimm_bus *nvdimm_bus, struct nd_region_desc *ndr_desc, const struct device_type *dev_type, const char *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/region_devs.c (0)
Location: drivers/nvdimm/region_devs.c:1029
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nvdimm_volatile_region_create
  - drivers/nvdimm/region_devs.c:nvdimm_pmem_region_create
```
**Symbols:**

```
ffffffff81813740-ffffffff81813b21: nd_region_create (STB_LOCAL)
ffffffff81815d8e-ffffffff81815df0: nd_region_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct nd_region *nd_region_create(struct nvdimm_bus *nvdimm_bus, struct nd_region_desc *ndr_desc, const struct device_type *dev_type, const char *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/region_devs.c (0)
Location: drivers/nvdimm/region_devs.c:1029
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nvdimm_volatile_region_create
  - drivers/nvdimm/region_devs.c:nvdimm_pmem_region_create
```
**Symbols:**

```
ffffffff81822930-ffffffff81822d11: nd_region_create (STB_LOCAL)
ffffffff81c15b49-ffffffff81c15bab: nd_region_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct nd_region *nd_region_create(struct nvdimm_bus *nvdimm_bus, struct nd_region_desc *ndr_desc, const struct device_type *dev_type, const char *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/region_devs.c (0)
Location: drivers/nvdimm/region_devs.c:1036
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nvdimm_volatile_region_create
  - drivers/nvdimm/region_devs.c:nvdimm_pmem_region_create
```
**Symbols:**

```
ffffffff818058e0-ffffffff81805cc1: nd_region_create (STB_LOCAL)
ffffffff81c078a1-ffffffff81c07903: nd_region_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct nd_region *nd_region_create(struct nvdimm_bus *nvdimm_bus, struct nd_region_desc *ndr_desc, const struct device_type *dev_type, const char *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/region_devs.c (0)
Location: drivers/nvdimm/region_devs.c:1036
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nvdimm_volatile_region_create
  - drivers/nvdimm/region_devs.c:nvdimm_pmem_region_create
```
**Symbols:**

```
ffffffff81890990-ffffffff81890d9f: nd_region_create (STB_LOCAL)
ffffffff81d0aff2-ffffffff81d0b054: nd_region_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/region_devs.c (0)
Location: drivers/nvdimm/region_devs.c:954
Inline: True
Direct callers:
  - drivers/nvdimm/region_devs.c:nvdimm_volatile_region_create
  - drivers/nvdimm/region_devs.c:nvdimm_pmem_region_create
```
**Symbols:**

```
ffffffff819da6b0-ffffffff819daa41: nd_region_create.constprop.0 (STB_LOCAL)
ffffffff81ed342b-ffffffff81ed345f: nd_region_create.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81b55a30)
Location: drivers/nvdimm/region_devs.c:999
Inline: True
Direct callers:
  - drivers/nvdimm/region_devs.c:nvdimm_volatile_region_create
  - drivers/nvdimm/region_devs.c:nvdimm_pmem_region_create
```
**Symbols:**

```
ffffffff81b55a30-ffffffff81b55e24: nd_region_create.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81ba8f80)
Location: drivers/nvdimm/region_devs.c:999
Inline: True
Direct callers:
  - drivers/nvdimm/region_devs.c:nvdimm_volatile_region_create
  - drivers/nvdimm/region_devs.c:nvdimm_pmem_region_create
```
**Symbols:**

```
ffffffff81ba8f80-ffffffff81ba9374: nd_region_create.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffff81bfd2c0)
Location: drivers/nvdimm/region_devs.c:1000
Inline: True
Direct callers:
  - drivers/nvdimm/region_devs.c:nvdimm_volatile_region_create
  - drivers/nvdimm/region_devs.c:nvdimm_pmem_region_create
```
**Symbols:**

```
ffffffff81bfd2c0-ffffffff81bfd6b5: nd_region_create.constprop.0 (STB_LOCAL)
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
struct nd_region *nd_region_create(struct nvdimm_bus *nvdimm_bus, struct nd_region_desc *ndr_desc, struct device_type *dev_type, const char *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffff800010956af0)
Location: drivers/nvdimm/region_devs.c:933
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nvdimm_volatile_region_create
  - drivers/nvdimm/region_devs.c:nvdimm_pmem_region_create
```
**Symbols:**

```
ffff800010956af0-ffff800010956e90: nd_region_create (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct nd_region *nd_region_create(struct nvdimm_bus *nvdimm_bus, struct nd_region_desc *ndr_desc, struct device_type *dev_type, const char *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (c000000000a04800)
Location: drivers/nvdimm/region_devs.c:933
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nvdimm_volatile_region_create
  - drivers/nvdimm/region_devs.c:nvdimm_pmem_region_create
```
**Symbols:**

```
c000000000a04800-c000000000a04cb8: nd_region_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct nd_region *nd_region_create(struct nvdimm_bus *nvdimm_bus, struct nd_region_desc *ndr_desc, struct device_type *dev_type, const char *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/region_devs.c (ffffffe0005c5c9c)
Location: drivers/nvdimm/region_devs.c:933
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nvdimm_volatile_region_create
  - drivers/nvdimm/region_devs.c:nvdimm_pmem_region_create
```
**Symbols:**

```
ffffffe0005c5c9c-ffffffe0005c5fb0: nd_region_create (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
struct nd_region *nd_region_create(struct nvdimm_bus *nvdimm_bus, struct nd_region_desc *ndr_desc, struct device_type *dev_type, const char *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/region_devs.c (0)
Location: drivers/nvdimm/region_devs.c:933
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nvdimm_volatile_region_create
  - drivers/nvdimm/region_devs.c:nvdimm_pmem_region_create
```
**Symbols:**

```
ffffffff81709f60-ffffffff8170a2d7: nd_region_create (STB_LOCAL)
ffffffff8170ae8e-ffffffff8170aeea: nd_region_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct nd_region *nd_region_create(struct nvdimm_bus *nvdimm_bus, struct nd_region_desc *ndr_desc, struct device_type *dev_type, const char *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/region_devs.c (0)
Location: drivers/nvdimm/region_devs.c:933
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nvdimm_volatile_region_create
  - drivers/nvdimm/region_devs.c:nvdimm_pmem_region_create
```
**Symbols:**

```
ffffffff816dd9e0-ffffffff816ddd57: nd_region_create (STB_LOCAL)
ffffffff816de90e-ffffffff816de96a: nd_region_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct nd_region *nd_region_create(struct nvdimm_bus *nvdimm_bus, struct nd_region_desc *ndr_desc, struct device_type *dev_type, const char *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/region_devs.c (0)
Location: drivers/nvdimm/region_devs.c:933
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nvdimm_volatile_region_create
  - drivers/nvdimm/region_devs.c:nvdimm_pmem_region_create
```
**Symbols:**

```
ffffffff81748d30-ffffffff817490a7: nd_region_create (STB_LOCAL)
ffffffff81749c5e-ffffffff81749cba: nd_region_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct nd_region *nd_region_create(struct nvdimm_bus *nvdimm_bus, struct nd_region_desc *ndr_desc, struct device_type *dev_type, const char *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/region_devs.c (0)
Location: drivers/nvdimm/region_devs.c:933
Inline: False
Direct callers:
  - drivers/nvdimm/region_devs.c:nvdimm_volatile_region_create
  - drivers/nvdimm/region_devs.c:nvdimm_pmem_region_create
```
**Symbols:**

```
ffffffff817641b0-ffffffff81764527: nd_region_create (STB_LOCAL)
ffffffff817650de-ffffffff8176513a: nd_region_create.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct device_type *dev_type</code> ➡️ <code>const struct device_type *dev_type</code>
</li>
</ul>
</details>
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
