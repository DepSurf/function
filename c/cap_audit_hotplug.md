# Function: <code>cap_audit_hotplug</code>

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
int cap_audit_hotplug(struct intel_iommu *iommu, enum cap_audit_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/cap_audit.c (0)
Location: drivers/iommu/intel/cap_audit.c:75
Inline: False
Direct callers:
  - drivers/iommu/intel/cap_audit.c:intel_cap_audit
```
**Symbols:**

```
ffffffff81797e40-ffffffff817983df: cap_audit_hotplug (STB_LOCAL)
ffffffff81bfebb8-ffffffff81bff1db: cap_audit_hotplug.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int cap_audit_hotplug(struct intel_iommu *iommu, enum cap_audit_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/cap_audit.c (0)
Location: drivers/iommu/intel/cap_audit.c:75
Inline: False
Direct callers:
  - drivers/iommu/intel/cap_audit.c:intel_cap_audit
```
**Symbols:**

```
ffffffff81820680-ffffffff81820c1f: cap_audit_hotplug (STB_LOCAL)
ffffffff81d00a84-ffffffff81d010a7: cap_audit_hotplug.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int cap_audit_hotplug(struct intel_iommu *iommu, enum cap_audit_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/cap_audit.c (0)
Location: drivers/iommu/intel/cap_audit.c:75
Inline: False
Direct callers:
  - drivers/iommu/intel/cap_audit.c:intel_cap_audit
```
**Symbols:**

```
ffffffff81960770-ffffffff81960d1c: cap_audit_hotplug (STB_LOCAL)
ffffffff81ec8f84-ffffffff81ec95a5: cap_audit_hotplug.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cap_audit_hotplug(struct intel_iommu *iommu, enum cap_audit_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/cap_audit.c (ffffffff81ac8ac0)
Location: drivers/iommu/intel/cap_audit.c:75
Inline: False
Direct callers:
  - drivers/iommu/intel/cap_audit.c:intel_cap_audit
```
**Symbols:**

```
ffffffff81ac8ac0-ffffffff81ac97c5: cap_audit_hotplug (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cap_audit_hotplug(struct intel_iommu *iommu, enum cap_audit_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/cap_audit.c (ffffffff81b15630)
Location: drivers/iommu/intel/cap_audit.c:74
Inline: False
Direct callers:
  - drivers/iommu/intel/cap_audit.c:intel_cap_audit
```
**Symbols:**

```
ffffffff81b15630-ffffffff81b1634d: cap_audit_hotplug (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cap_audit_hotplug(struct intel_iommu *iommu, enum cap_audit_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/cap_audit.c (ffffffff81b6af70)
Location: drivers/iommu/intel/cap_audit.c:74
Inline: False
Direct callers:
  - drivers/iommu/intel/cap_audit.c:intel_cap_audit
```
**Symbols:**

```
ffffffff81b6af70-ffffffff81b6bc8d: cap_audit_hotplug (STB_LOCAL)
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
