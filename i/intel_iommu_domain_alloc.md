# Function: <code>intel_iommu_domain_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct iommu_domain *intel_iommu_domain_alloc(unsigned int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81539340)
Location: drivers/iommu/intel-iommu.c:4751
Inline: True
```
**Symbols:**

```
ffffffff81539340-ffffffff815393d3: intel_iommu_domain_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct iommu_domain *intel_iommu_domain_alloc(unsigned int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8158de40)
Location: drivers/iommu/intel-iommu.c:4889
Inline: True
```
**Symbols:**

```
ffffffff8158de40-ffffffff8158ded3: intel_iommu_domain_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct iommu_domain *intel_iommu_domain_alloc(unsigned int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815bb500)
Location: drivers/iommu/intel-iommu.c:4982
Inline: True
```
**Symbols:**

```
ffffffff815bb500-ffffffff815bb593: intel_iommu_domain_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct iommu_domain *intel_iommu_domain_alloc(unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815d1160)
Location: drivers/iommu/intel-iommu.c:5016
Inline: False
```
**Symbols:**

```
ffffffff815d1160-ffffffff815d11f3: intel_iommu_domain_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct iommu_domain *intel_iommu_domain_alloc(unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81637f10)
Location: drivers/iommu/intel-iommu.c:4930
Inline: False
```
**Symbols:**

```
ffffffff81637f10-ffffffff81637fa3: intel_iommu_domain_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct iommu_domain *intel_iommu_domain_alloc(unsigned int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:4972
Inline: True
```
**Symbols:**

```
ffffffff81673270-ffffffff816732e7: intel_iommu_domain_alloc (STB_LOCAL)
ffffffff816756cf-ffffffff816756f9: intel_iommu_domain_alloc.cold.92 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct iommu_domain *intel_iommu_domain_alloc(unsigned int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81690ce4)
Location: drivers/iommu/intel-iommu.c:5027
Inline: True
```
**Symbols:**

```
ffffffff81690cd0-ffffffff81690d47: intel_iommu_domain_alloc (STB_LOCAL)
ffffffff81693b59-ffffffff81693b83: intel_iommu_domain_alloc.cold.96 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct iommu_domain *intel_iommu_domain_alloc(unsigned int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816c8eb4)
Location: drivers/iommu/intel-iommu.c:4889
Inline: True
```
**Symbols:**

```
ffffffff816c8e90-ffffffff816c8f59: intel_iommu_domain_alloc (STB_LOCAL)
ffffffff816cc3bd-ffffffff816cc406: intel_iommu_domain_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct iommu_domain *intel_iommu_domain_alloc(unsigned int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816ebe74)
Location: drivers/iommu/intel-iommu.c:5173
Inline: True
```
**Symbols:**

```
ffffffff816ebe50-ffffffff816ebf19: intel_iommu_domain_alloc (STB_LOCAL)
ffffffff816efc53-ffffffff816efc9c: intel_iommu_domain_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct iommu_domain *intel_iommu_domain_alloc(unsigned int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817a380c)
Location: drivers/iommu/intel/iommu.c:5062
Inline: True
```
**Symbols:**

```
ffffffff817a37e0-ffffffff817a399d: intel_iommu_domain_alloc (STB_LOCAL)
ffffffff817a6ef1-ffffffff817a6f15: intel_iommu_domain_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct iommu_domain *intel_iommu_domain_alloc(unsigned int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817b0790)
Location: drivers/iommu/intel/iommu.c:4441
Inline: True
```
**Symbols:**

```
ffffffff817b0760-ffffffff817b08cf: intel_iommu_domain_alloc (STB_LOCAL)
ffffffff81c0c667-ffffffff81c0c67b: intel_iommu_domain_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct iommu_domain *intel_iommu_domain_alloc(unsigned int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81793230)
Location: drivers/iommu/intel/iommu.c:4539
Inline: True
```
**Symbols:**

```
ffffffff81793200-ffffffff8179336f: intel_iommu_domain_alloc (STB_LOCAL)
ffffffff81bfde55-ffffffff81bfde69: intel_iommu_domain_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct iommu_domain *intel_iommu_domain_alloc(unsigned int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8181a50a)
Location: drivers/iommu/intel/iommu.c:4527
Inline: True
```
**Symbols:**

```
ffffffff8181a4e0-ffffffff8181a57f: intel_iommu_domain_alloc (STB_LOCAL)
ffffffff81cff86a-ffffffff81cff8bf: intel_iommu_domain_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct iommu_domain *intel_iommu_domain_alloc(unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:4262
Inline: False
```
**Symbols:**

```
ffffffff8195bd00-ffffffff8195be68: intel_iommu_domain_alloc (STB_LOCAL)
ffffffff81ec8248-ffffffff81ec8282: intel_iommu_domain_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct iommu_domain *intel_iommu_domain_alloc(unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:4176
Inline: False
```
**Symbols:**

```
ffffffff81ac34f0-ffffffff81ac366e: intel_iommu_domain_alloc (STB_LOCAL)
ffffffff82097a48-ffffffff82097a6f: intel_iommu_domain_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct iommu_domain *intel_iommu_domain_alloc(unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:4066
Inline: False
```
**Symbols:**

```
ffffffff81b10520-ffffffff81b10620: intel_iommu_domain_alloc (STB_LOCAL)
ffffffff821189b5-ffffffff821189dc: intel_iommu_domain_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct iommu_domain *intel_iommu_domain_alloc(unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:3908
Inline: False
```
**Symbols:**

```
ffffffff81b64fc0-ffffffff81b650b3: intel_iommu_domain_alloc (STB_LOCAL)
ffffffff821f66e9-ffffffff821f6710: intel_iommu_domain_alloc.cold (STB_LOCAL)
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
In <code>ppc64el</code>: Absent ⚠️
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
struct iommu_domain *intel_iommu_domain_alloc(unsigned int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816b17a4)
Location: drivers/iommu/intel-iommu.c:5173
Inline: True
```
**Symbols:**

```
ffffffff816b1780-ffffffff816b1849: intel_iommu_domain_alloc (STB_LOCAL)
ffffffff816b5439-ffffffff816b5482: intel_iommu_domain_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct iommu_domain *intel_iommu_domain_alloc(unsigned int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8168f2a4)
Location: drivers/iommu/intel-iommu.c:5173
Inline: True
```
**Symbols:**

```
ffffffff8168f280-ffffffff8168f349: intel_iommu_domain_alloc (STB_LOCAL)
ffffffff81693083-ffffffff816930cc: intel_iommu_domain_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct iommu_domain *intel_iommu_domain_alloc(unsigned int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816dfb34)
Location: drivers/iommu/intel-iommu.c:5173
Inline: True
```
**Symbols:**

```
ffffffff816dfb10-ffffffff816dfbd9: intel_iommu_domain_alloc (STB_LOCAL)
ffffffff816e3913-ffffffff816e395c: intel_iommu_domain_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct iommu_domain *intel_iommu_domain_alloc(unsigned int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816fa144)
Location: drivers/iommu/intel-iommu.c:5173
Inline: True
```
**Symbols:**

```
ffffffff816fa120-ffffffff816fa1e9: intel_iommu_domain_alloc (STB_LOCAL)
ffffffff816fdfa3-ffffffff816fdfec: intel_iommu_domain_alloc.cold (STB_LOCAL)
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
