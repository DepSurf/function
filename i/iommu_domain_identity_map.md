# Function: <code>iommu_domain_identity_map</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int iommu_domain_identity_map(struct dmar_domain *domain, long long unsigned int start, long long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81537ce0)
Location: drivers/iommu/intel-iommu.c:2485
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81537ce0-ffffffff81537d8e: iommu_domain_identity_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int iommu_domain_identity_map(struct dmar_domain *domain, long long unsigned int start, long long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8158c7d0)
Location: drivers/iommu/intel-iommu.c:2529
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff8158c7d0-ffffffff8158c87a: iommu_domain_identity_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int iommu_domain_identity_map(struct dmar_domain *domain, long long unsigned int start, long long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815b9f10)
Location: drivers/iommu/intel-iommu.c:2606
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff815b9f10-ffffffff815b9fba: iommu_domain_identity_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int iommu_domain_identity_map(struct dmar_domain *domain, long long unsigned int start, long long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815cfed0)
Location: drivers/iommu/intel-iommu.c:2614
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff815cfed0-ffffffff815cff7a: iommu_domain_identity_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int iommu_domain_identity_map(struct dmar_domain *domain, long long unsigned int start, long long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81636c70)
Location: drivers/iommu/intel-iommu.c:2638
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81636c70-ffffffff81636d1a: iommu_domain_identity_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int iommu_domain_identity_map(struct dmar_domain *domain, long long unsigned int start, long long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:2694
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_prepare_identity_map
```
**Symbols:**

```
ffffffff81672240-ffffffff816722db: iommu_domain_identity_map (STB_LOCAL)
ffffffff8167553b-ffffffff81675551: iommu_domain_identity_map.cold.90 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int iommu_domain_identity_map(struct dmar_domain *domain, long long unsigned int start, long long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:2691
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_prepare_identity_map
```
**Symbols:**

```
ffffffff816909f0-ffffffff81690a8b: iommu_domain_identity_map (STB_LOCAL)
ffffffff816939c5-ffffffff816939db: iommu_domain_identity_map.cold.94 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int iommu_domain_identity_map(struct dmar_domain *domain, long long unsigned int start, long long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:2657
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff816c8ba0-ffffffff816c8c3a: iommu_domain_identity_map (STB_LOCAL)
ffffffff816cc36f-ffffffff816cc385: iommu_domain_identity_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int iommu_domain_identity_map(struct dmar_domain *domain, long long unsigned int start, long long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:2668
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff816ebb60-ffffffff816ebbfa: iommu_domain_identity_map (STB_LOCAL)
ffffffff816efc05-ffffffff816efc1b: iommu_domain_identity_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int iommu_domain_identity_map(struct dmar_domain *domain, long unsigned int first_vpfn, long unsigned int last_vpfn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817a2d68)
Location: drivers/iommu/intel/iommu.c:2647
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier
Direct callers:
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/iommu/intel/iommu.c:si_domain_init
```
**Symbols:**

```
ffffffff817a2ce0-ffffffff817a2d20: iommu_domain_identity_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int iommu_domain_identity_map(struct dmar_domain *domain, long unsigned int first_vpfn, long unsigned int last_vpfn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817afea8)
Location: drivers/iommu/intel/iommu.c:2668
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier
Direct callers:
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/iommu/intel/iommu.c:si_domain_init
```
**Symbols:**

```
ffffffff817afe20-ffffffff817afe5e: iommu_domain_identity_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int iommu_domain_identity_map(struct dmar_domain *domain, long unsigned int first_vpfn, long unsigned int last_vpfn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81793108)
Location: drivers/iommu/intel/iommu.c:2708
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier
Direct callers:
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/iommu/intel/iommu.c:si_domain_init
```
**Symbols:**

```
ffffffff81793080-ffffffff817930be: iommu_domain_identity_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int iommu_domain_identity_map(struct dmar_domain *domain, long unsigned int first_vpfn, long unsigned int last_vpfn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8181b098)
Location: drivers/iommu/intel/iommu.c:2698
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier
Direct callers:
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/iommu/intel/iommu.c:si_domain_init
```
**Symbols:**

```
ffffffff8181aef0-ffffffff8181af2e: iommu_domain_identity_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int iommu_domain_identity_map(struct dmar_domain *domain, long unsigned int first_vpfn, long unsigned int last_vpfn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8195b7c4)
Location: drivers/iommu/intel/iommu.c:2433
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier
Direct callers:
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/iommu/intel/iommu.c:si_domain_init
```
**Symbols:**

```
ffffffff8195b5c0-ffffffff8195b60d: iommu_domain_identity_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81ac329c)
Location: drivers/iommu/intel/iommu.c:2368
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier
  - drivers/iommu/intel/iommu.c:si_domain_init
  - drivers/iommu/intel/iommu.c:si_domain_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int iommu_domain_identity_map(struct dmar_domain *domain, long unsigned int first_vpfn, long unsigned int last_vpfn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8371ae4e)
Location: drivers/iommu/intel/iommu.c:2332
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:si_domain_init
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier
  - drivers/iommu/intel/iommu.c:si_domain_init
```
**Symbols:**

```
ffffffff81b10280-ffffffff81b10316: iommu_domain_identity_map (STB_LOCAL)
ffffffff8211899e-ffffffff821189b5: iommu_domain_identity_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int iommu_domain_identity_map(struct dmar_domain *domain, long unsigned int first_vpfn, long unsigned int last_vpfn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8394e92e)
Location: drivers/iommu/intel/iommu.c:2253
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:si_domain_init
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_memory_notifier
  - drivers/iommu/intel/iommu.c:si_domain_init
```
**Symbols:**

```
ffffffff81b64d20-ffffffff81b64db6: iommu_domain_identity_map (STB_LOCAL)
ffffffff821f66d2-ffffffff821f66e9: iommu_domain_identity_map.cold (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int iommu_domain_identity_map(struct dmar_domain *domain, long long unsigned int start, long long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:2668
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff816b1490-ffffffff816b152a: iommu_domain_identity_map (STB_LOCAL)
ffffffff816b53eb-ffffffff816b5401: iommu_domain_identity_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int iommu_domain_identity_map(struct dmar_domain *domain, long long unsigned int start, long long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:2668
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff8168ef90-ffffffff8168f02a: iommu_domain_identity_map (STB_LOCAL)
ffffffff81693035-ffffffff8169304b: iommu_domain_identity_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int iommu_domain_identity_map(struct dmar_domain *domain, long long unsigned int start, long long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:2668
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff816df820-ffffffff816df8ba: iommu_domain_identity_map (STB_LOCAL)
ffffffff816e38c5-ffffffff816e38db: iommu_domain_identity_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int iommu_domain_identity_map(struct dmar_domain *domain, long long unsigned int start, long long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:2668
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
```
**Symbols:**

```
ffffffff816f9e30-ffffffff816f9eca: iommu_domain_identity_map (STB_LOCAL)
ffffffff816fdf55-ffffffff816fdf6b: iommu_domain_identity_map.cold (STB_LOCAL)
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
<b>Param added. </b>
<code>long unsigned int first_vpfn</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int last_vpfn</code>
</li>
<li>
<b>Param removed. </b>
<code>long long unsigned int start</code>
</li>
<li>
<b>Param removed. </b>
<code>long long unsigned int end</code>
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
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
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
