# Function: <code>intel_cap_nest_sanity</code>

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
<summary>In <code>5.13</code>: ✅</summary>

```c
bool intel_cap_nest_sanity();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/cap_audit.c (ffffffff81798520)
Location: drivers/iommu/intel/cap_audit.c:197
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_enable_nesting
```
**Symbols:**

```
ffffffff81798520-ffffffff81798539: intel_cap_nest_sanity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool intel_cap_nest_sanity();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/cap_audit.c (ffffffff81820d60)
Location: drivers/iommu/intel/cap_audit.c:197
Inline: False
```
**Symbols:**

```
ffffffff81820d60-ffffffff81820d79: intel_cap_nest_sanity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool intel_cap_nest_sanity();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/cap_audit.c (ffffffff81960e90)
Location: drivers/iommu/intel/cap_audit.c:206
Inline: False
```
**Symbols:**

```
ffffffff81960e90-ffffffff81960ead: intel_cap_nest_sanity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool intel_cap_nest_sanity();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/cap_audit.c (ffffffff81ac99c0)
Location: drivers/iommu/intel/cap_audit.c:206
Inline: False
```
**Symbols:**

```
ffffffff81ac99c0-ffffffff81ac99dd: intel_cap_nest_sanity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool intel_cap_nest_sanity();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/cap_audit.c (ffffffff81b16550)
Location: drivers/iommu/intel/cap_audit.c:204
Inline: False
```
**Symbols:**

```
ffffffff81b16550-ffffffff81b1656d: intel_cap_nest_sanity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool intel_cap_nest_sanity();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/cap_audit.c (ffffffff81b6be90)
Location: drivers/iommu/intel/cap_audit.c:204
Inline: False
```
**Symbols:**

```
ffffffff81b6be90-ffffffff81b6bead: intel_cap_nest_sanity (STB_GLOBAL)
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
