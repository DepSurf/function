# Function: <code>update_device_table</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8152fc1e)
Location: drivers/iommu/amd_iommu.c:2256
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8158345e)
Location: drivers/iommu/amd_iommu.c:2238
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815b076e)
Location: drivers/iommu/amd_iommu.c:2331
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815c6780)
Location: drivers/iommu/amd_iommu.c:2492
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8162d520)
Location: drivers/iommu/amd_iommu.c:2273
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81667fd5)
Location: drivers/iommu/amd_iommu.c:2281
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81686235)
Location: drivers/iommu/amd_iommu.c:2357
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816bdaf5)
Location: drivers/iommu/amd_iommu.c:2338
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816e0ce5)
Location: drivers/iommu/amd_iommu.c:2372
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:update_domain
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void update_device_table(struct protection_domain *domain, struct domain_pgtable *pgtable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81798c30)
Location: drivers/iommu/amd/iommu.c:2216
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:update_domain
  - drivers/iommu/amd/iommu.c:increase_address_space
```
**Symbols:**

```
ffffffff81798c30-ffffffff81798cca: update_device_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void update_device_table(struct protection_domain *domain, struct domain_pgtable *pgtable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817a74b0)
Location: drivers/iommu/amd/iommu.c:2308
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:update_domain
  - drivers/iommu/amd/iommu.c:increase_address_space
```
**Symbols:**

```
ffffffff817a74b0-ffffffff817a754a: update_device_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void update_device_table(struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81788e40)
Location: drivers/iommu/amd/iommu.c:1748
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_update
```
**Symbols:**

```
ffffffff81788e40-ffffffff81788ecb: update_device_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void update_device_table(struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:1792
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_update
```
**Symbols:**

```
ffffffff8180fa10-ffffffff8180fabf: update_device_table (STB_LOCAL)
ffffffff81cfe1c6-ffffffff81cfe202: update_device_table.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void update_device_table(struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:1814
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_update
```
**Symbols:**

```
ffffffff8194eb80-ffffffff8194ec4b: update_device_table (STB_LOCAL)
ffffffff81ec6971-ffffffff81ec69ad: update_device_table.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void update_device_table(struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:1934
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_update
```
**Symbols:**

```
ffffffff81ab3e80-ffffffff81ab3f4a: update_device_table (STB_LOCAL)
ffffffff82096db0-ffffffff82096df1: update_device_table.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void update_device_table(struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:1959
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_update
```
**Symbols:**

```
ffffffff81b00970-ffffffff81b00a3a: update_device_table (STB_LOCAL)
ffffffff82117ce3-ffffffff82117d24: update_device_table.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void update_device_table(struct protection_domain *domain);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81b546d0)
Location: drivers/iommu/amd/iommu.c:2007
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:protection_domain_alloc
```
**Symbols:**

```
ffffffff81b546d0-ffffffff81b54781: update_device_table (STB_LOCAL)
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816a6735)
Location: drivers/iommu/amd_iommu.c:2372
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:update_domain
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81684125)
Location: drivers/iommu/amd_iommu.c:2372
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:update_domain
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816d49a5)
Location: drivers/iommu/amd_iommu.c:2372
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:update_domain
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816ef0a5)
Location: drivers/iommu/amd_iommu.c:2372
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:update_domain
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct domain_pgtable *pgtable</code>
</li>
</ul>
</details>
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
