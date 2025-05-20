# Function: <code>set_iommu_domain</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void set_iommu_domain(struct intel_iommu *iommu, u16 did, struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81538de0)
Location: drivers/iommu/intel-iommu.c:627
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff81538de0-ffffffff81538e72: set_iommu_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void set_iommu_domain(struct intel_iommu *iommu, u16 did, struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8158d8a0)
Location: drivers/iommu/intel-iommu.c:634
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff8158d8a0-ffffffff8158d932: set_iommu_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void set_iommu_domain(struct intel_iommu *iommu, u16 did, struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815bb040)
Location: drivers/iommu/intel-iommu.c:635
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff815bb040-ffffffff815bb0d2: set_iommu_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void set_iommu_domain(struct intel_iommu *iommu, u16 did, struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815d0cd0)
Location: drivers/iommu/intel-iommu.c:640
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff815d0cd0-ffffffff815d0d53: set_iommu_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void set_iommu_domain(struct intel_iommu *iommu, u16 did, struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81637ad0)
Location: drivers/iommu/intel-iommu.c:613
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff81637ad0-ffffffff81637b53: set_iommu_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void set_iommu_domain(struct intel_iommu *iommu, u16 did, struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81672e50)
Location: drivers/iommu/intel-iommu.c:615
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff81672e50-ffffffff81672ebc: set_iommu_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void set_iommu_domain(struct intel_iommu *iommu, u16 did, struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8168faf0)
Location: drivers/iommu/intel-iommu.c:491
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info
  - drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info
```
**Symbols:**

```
ffffffff8168faf0-ffffffff8168fb68: set_iommu_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void set_iommu_domain(struct intel_iommu *iommu, u16 did, struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:485
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:domain_detach_iommu
  - drivers/iommu/intel-iommu.c:domain_attach_iommu
```
**Symbols:**

```
ffffffff816c7690-ffffffff816c76ff: set_iommu_domain (STB_LOCAL)
ffffffff816cbe1b-ffffffff816cbe2e: set_iommu_domain.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void set_iommu_domain(struct intel_iommu *iommu, u16 did, struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816ea5f0)
Location: drivers/iommu/intel-iommu.c:496
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:domain_detach_iommu
```
**Symbols:**

```
ffffffff816ea5f0-ffffffff816ea666: set_iommu_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void set_iommu_domain(struct intel_iommu *iommu, u16 did, struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817a1de0)
Location: drivers/iommu/intel/iommu.c:493
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:domain_attach_iommu
```
**Symbols:**

```
ffffffff817a1de0-ffffffff817a1e56: set_iommu_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void set_iommu_domain(struct intel_iommu *iommu, u16 did, struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817affa0)
Location: drivers/iommu/intel/iommu.c:483
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:domain_attach_iommu
```
**Symbols:**

```
ffffffff817affa0-ffffffff817b0016: set_iommu_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void set_iommu_domain(struct intel_iommu *iommu, u16 did, struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81791da0)
Location: drivers/iommu/intel/iommu.c:492
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:domain_attach_iommu
```
**Symbols:**

```
ffffffff81791da0-ffffffff81791e1d: set_iommu_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void set_iommu_domain(struct intel_iommu *iommu, u16 did, struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff818196d0)
Location: drivers/iommu/intel/iommu.c:481
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:domain_detach_iommu
```
**Symbols:**

```
ffffffff818196d0-ffffffff8181974d: set_iommu_domain (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void set_iommu_domain(struct intel_iommu *iommu, u16 did, struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816b00d0)
Location: drivers/iommu/intel-iommu.c:496
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:domain_detach_iommu
```
**Symbols:**

```
ffffffff816b00d0-ffffffff816b0146: set_iommu_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void set_iommu_domain(struct intel_iommu *iommu, u16 did, struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8168da20)
Location: drivers/iommu/intel-iommu.c:496
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:domain_detach_iommu
```
**Symbols:**

```
ffffffff8168da20-ffffffff8168da96: set_iommu_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void set_iommu_domain(struct intel_iommu *iommu, u16 did, struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816de2b0)
Location: drivers/iommu/intel-iommu.c:496
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:domain_detach_iommu
```
**Symbols:**

```
ffffffff816de2b0-ffffffff816de326: set_iommu_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void set_iommu_domain(struct intel_iommu *iommu, u16 did, struct dmar_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816f88c0)
Location: drivers/iommu/intel-iommu.c:496
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:domain_detach_iommu
```
**Symbols:**

```
ffffffff816f88c0-ffffffff816f8936: set_iommu_domain (STB_LOCAL)
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
