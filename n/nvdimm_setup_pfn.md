# Function: <code>nvdimm_setup_pfn</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct vmem_altmap *nvdimm_setup_pfn(struct nd_pfn *nd_pfn, struct resource *res, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff815f8550)
Location: drivers/nvdimm/pfn_devs.c:673
Inline: False
```
**Symbols:**

```
ffffffff815f8550-ffffffff815f8b20: nvdimm_setup_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct vmem_altmap *nvdimm_setup_pfn(struct nd_pfn *nd_pfn, struct resource *res, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff816267c0)
Location: drivers/nvdimm/pfn_devs.c:670
Inline: False
```
**Symbols:**

```
ffffffff816267c0-ffffffff81626d97: nvdimm_setup_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct vmem_altmap *nvdimm_setup_pfn(struct nd_pfn *nd_pfn, struct resource *res, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff8163bc30)
Location: drivers/nvdimm/pfn_devs.c:680
Inline: True
```
**Symbols:**

```
ffffffff8163bc30-ffffffff8163c233: nvdimm_setup_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct vmem_altmap *nvdimm_setup_pfn(struct nd_pfn *nd_pfn, struct resource *res, struct vmem_altmap *altmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff816a4890)
Location: drivers/nvdimm/pfn_devs.c:711
Inline: True
```
**Symbols:**

```
ffffffff816a4890-ffffffff816a4ec5: nvdimm_setup_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int nvdimm_setup_pfn(struct nd_pfn *nd_pfn, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff816e08f0)
Location: drivers/nvdimm/pfn_devs.c:712
Inline: False
```
**Symbols:**

```
ffffffff816e08f0-ffffffff816e0f12: nvdimm_setup_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int nvdimm_setup_pfn(struct nd_pfn *nd_pfn, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff81702e70)
Location: drivers/nvdimm/pfn_devs.c:781
Inline: False
```
**Symbols:**

```
ffffffff81702e70-ffffffff8170356b: nvdimm_setup_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int nvdimm_setup_pfn(struct nd_pfn *nd_pfn, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (0)
Location: drivers/nvdimm/pfn_devs.c:740
Inline: False
```
**Symbols:**

```
ffffffff8173d588-ffffffff8173d5f3: nvdimm_setup_pfn.cold (STB_LOCAL)
ffffffff8173cc40-ffffffff8173d030: nvdimm_setup_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int nvdimm_setup_pfn(struct nd_pfn *nd_pfn, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (0)
Location: drivers/nvdimm/pfn_devs.c:806
Inline: False
```
**Symbols:**

```
ffffffff81761407-ffffffff81761470: nvdimm_setup_pfn.cold (STB_LOCAL)
ffffffff81760a30-ffffffff81760e49: nvdimm_setup_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int nvdimm_setup_pfn(struct nd_pfn *nd_pfn, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff81820a60)
Location: drivers/nvdimm/pfn_devs.c:834
Inline: False
```
**Symbols:**

```
ffffffff81820a60-ffffffff81820aab: nvdimm_setup_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int nvdimm_setup_pfn(struct nd_pfn *nd_pfn, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff8182f950)
Location: drivers/nvdimm/pfn_devs.c:835
Inline: False
```
**Symbols:**

```
ffffffff8182f950-ffffffff8182f99b: nvdimm_setup_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int nvdimm_setup_pfn(struct nd_pfn *nd_pfn, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (0)
Location: drivers/nvdimm/pfn_devs.c:835
Inline: False
```
**Symbols:**

```
ffffffff81c07dca-ffffffff81c07de5: nvdimm_setup_pfn.cold (STB_LOCAL)
ffffffff81812a70-ffffffff81812c23: nvdimm_setup_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int nvdimm_setup_pfn(struct nd_pfn *nd_pfn, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (0)
Location: drivers/nvdimm/pfn_devs.c:835
Inline: False
```
**Symbols:**

```
ffffffff81d0b785-ffffffff81d0b7a0: nvdimm_setup_pfn.cold (STB_LOCAL)
ffffffff8189d100-ffffffff8189d2b3: nvdimm_setup_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int nvdimm_setup_pfn(struct nd_pfn *nd_pfn, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (0)
Location: drivers/nvdimm/pfn_devs.c:837
Inline: False
```
**Symbols:**

```
ffffffff81ed45fe-ffffffff81ed4619: nvdimm_setup_pfn.cold (STB_LOCAL)
ffffffff819e6a00-ffffffff819e6bc2: nvdimm_setup_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int nvdimm_setup_pfn(struct nd_pfn *nd_pfn, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff81b62cb0)
Location: drivers/nvdimm/pfn_devs.c:849
Inline: False
```
**Symbols:**

```
ffffffff81b62cb0-ffffffff81b62d09: nvdimm_setup_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int nvdimm_setup_pfn(struct nd_pfn *nd_pfn, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff81bb6290)
Location: drivers/nvdimm/pfn_devs.c:849
Inline: False
```
**Symbols:**

```
ffffffff81bb6290-ffffffff81bb62e9: nvdimm_setup_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int nvdimm_setup_pfn(struct nd_pfn *nd_pfn, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (ffffffff81c0a880)
Location: drivers/nvdimm/pfn_devs.c:855
Inline: False
```
**Symbols:**

```
ffffffff81c0a880-ffffffff81c0a8d9: nvdimm_setup_pfn (STB_GLOBAL)
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
int nvdimm_setup_pfn(struct nd_pfn *nd_pfn, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (c000000000a16190)
Location: drivers/nvdimm/pfn_devs.c:806
Inline: False
```
**Symbols:**

```
c000000000a16190-c000000000a16660: nvdimm_setup_pfn (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int nvdimm_setup_pfn(struct nd_pfn *nd_pfn, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (0)
Location: drivers/nvdimm/pfn_devs.c:806
Inline: False
```
**Symbols:**

```
ffffffff81715af7-ffffffff81715b60: nvdimm_setup_pfn.cold (STB_LOCAL)
ffffffff81715120-ffffffff81715539: nvdimm_setup_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int nvdimm_setup_pfn(struct nd_pfn *nd_pfn, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (0)
Location: drivers/nvdimm/pfn_devs.c:806
Inline: False
Direct callers:
  - drivers/nvdimm/pmem.c:pmem_attach_disk
  - drivers/dax/pmem/core.c:__dax_pmem_probe
```
**Symbols:**

```
ffffffff816e9577-ffffffff816e95e0: nvdimm_setup_pfn.cold (STB_LOCAL)
ffffffff816e8ba0-ffffffff816e8fb9: nvdimm_setup_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int nvdimm_setup_pfn(struct nd_pfn *nd_pfn, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (0)
Location: drivers/nvdimm/pfn_devs.c:806
Inline: False
```
**Symbols:**

```
ffffffff817548c7-ffffffff81754930: nvdimm_setup_pfn.cold (STB_LOCAL)
ffffffff81753ef0-ffffffff81754309: nvdimm_setup_pfn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int nvdimm_setup_pfn(struct nd_pfn *nd_pfn, struct dev_pagemap *pgmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/pfn_devs.c (0)
Location: drivers/nvdimm/pfn_devs.c:806
Inline: False
```
**Symbols:**

```
ffffffff8176fd37-ffffffff8176fda0: nvdimm_setup_pfn.cold (STB_LOCAL)
ffffffff8176f360-ffffffff8176f779: nvdimm_setup_pfn (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct dev_pagemap *pgmap</code>
</li>
<li>
<b>Param removed. </b>
<code>struct resource *res</code>
</li>
<li>
<b>Param removed. </b>
<code>struct vmem_altmap *altmap</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct vmem_altmap *</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
