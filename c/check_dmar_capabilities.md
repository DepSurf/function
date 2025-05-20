# Function: <code>check_dmar_capabilities</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void check_dmar_capabilities(struct intel_iommu *a, struct intel_iommu *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/cap_audit.c (0)
Location: drivers/iommu/intel/cap_audit.c:26
Inline: False
Direct callers:
  - drivers/iommu/intel/cap_audit.c:intel_cap_audit
```
**Symbols:**

```
ffffffff81797a80-ffffffff81797e3b: check_dmar_capabilities (STB_LOCAL)
ffffffff81bfe657-ffffffff81bfebb8: check_dmar_capabilities.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void check_dmar_capabilities(struct intel_iommu *a, struct intel_iommu *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/cap_audit.c (0)
Location: drivers/iommu/intel/cap_audit.c:26
Inline: False
Direct callers:
  - drivers/iommu/intel/cap_audit.c:intel_cap_audit
```
**Symbols:**

```
ffffffff818202c0-ffffffff8182067b: check_dmar_capabilities (STB_LOCAL)
ffffffff81d00523-ffffffff81d00a84: check_dmar_capabilities.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void check_dmar_capabilities(struct intel_iommu *a, struct intel_iommu *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/cap_audit.c (0)
Location: drivers/iommu/intel/cap_audit.c:26
Inline: False
Direct callers:
  - drivers/iommu/intel/cap_audit.c:intel_cap_audit
```
**Symbols:**

```
ffffffff819603a0-ffffffff8196076c: check_dmar_capabilities (STB_LOCAL)
ffffffff81ec8a23-ffffffff81ec8f84: check_dmar_capabilities.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void check_dmar_capabilities(struct intel_iommu *a, struct intel_iommu *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/cap_audit.c (ffffffff81ac8100)
Location: drivers/iommu/intel/cap_audit.c:26
Inline: False
Direct callers:
  - drivers/iommu/intel/cap_audit.c:intel_cap_audit
```
**Symbols:**

```
ffffffff81ac8100-ffffffff81ac8aa5: check_dmar_capabilities (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void check_dmar_capabilities(struct intel_iommu *a, struct intel_iommu *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/cap_audit.c (ffffffff81b14d30)
Location: drivers/iommu/intel/cap_audit.c:26
Inline: False
Direct callers:
  - drivers/iommu/intel/cap_audit.c:intel_cap_audit
```
**Symbols:**

```
ffffffff81b14d30-ffffffff81b15619: check_dmar_capabilities (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void check_dmar_capabilities(struct intel_iommu *a, struct intel_iommu *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/cap_audit.c (ffffffff81b6a670)
Location: drivers/iommu/intel/cap_audit.c:26
Inline: False
Direct callers:
  - drivers/iommu/intel/cap_audit.c:intel_cap_audit
```
**Symbols:**

```
ffffffff81b6a670-ffffffff81b6af59: check_dmar_capabilities (STB_LOCAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
