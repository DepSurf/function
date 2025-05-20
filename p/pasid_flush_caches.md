# Function: <code>pasid_flush_caches</code>

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
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void pasid_flush_caches(struct intel_iommu *iommu, struct pasid_entry *pte, int pasid, u16 did);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/pasid.c (ffffffff817a7510)
Location: drivers/iommu/intel/pasid.c:516
Inline: True
Direct callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
```
**Symbols:**

```
ffffffff817a7510-ffffffff817a7608: pasid_flush_caches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void pasid_flush_caches(struct intel_iommu *iommu, struct pasid_entry *pte, u32 pasid, u16 did);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/pasid.c (ffffffff817b33b0)
Location: drivers/iommu/intel/pasid.c:524
Inline: True
Direct callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
```
**Symbols:**

```
ffffffff817b33b0-ffffffff817b34a3: pasid_flush_caches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void pasid_flush_caches(struct intel_iommu *iommu, struct pasid_entry *pte, u32 pasid, u16 did);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/pasid.c (ffffffff81796510)
Location: drivers/iommu/intel/pasid.c:543
Inline: True
Direct callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
```
**Symbols:**

```
ffffffff81796510-ffffffff817965e4: pasid_flush_caches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void pasid_flush_caches(struct intel_iommu *iommu, struct pasid_entry *pte, u32 pasid, u16 did);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/pasid.c (ffffffff8181e4a0)
Location: drivers/iommu/intel/pasid.c:547
Inline: True
Direct callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
```
**Symbols:**

```
ffffffff8181e4a0-ffffffff8181e574: pasid_flush_caches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void pasid_flush_caches(struct intel_iommu *iommu, struct pasid_entry *pte, u32 pasid, u16 did);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/pasid.c (ffffffff8195e850)
Location: drivers/iommu/intel/pasid.c:484
Inline: True
Direct callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
```
**Symbols:**

```
ffffffff8195e850-ffffffff8195e93d: pasid_flush_caches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void pasid_flush_caches(struct intel_iommu *iommu, struct pasid_entry *pte, u32 pasid, u16 did);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/pasid.c (ffffffff81ac6260)
Location: drivers/iommu/intel/pasid.c:493
Inline: True
Direct callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
```
**Symbols:**

```
ffffffff81ac6260-ffffffff81ac634d: pasid_flush_caches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void pasid_flush_caches(struct intel_iommu *iommu, struct pasid_entry *pte, u32 pasid, u16 did);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/pasid.c (ffffffff81b12e30)
Location: drivers/iommu/intel/pasid.c:484
Inline: True
Direct callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
```
**Symbols:**

```
ffffffff81b12e30-ffffffff81b12f1d: pasid_flush_caches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void pasid_flush_caches(struct intel_iommu *iommu, struct pasid_entry *pte, u32 pasid, u16 did);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/pasid.c (ffffffff81b67c70)
Location: drivers/iommu/intel/pasid.c:270
Inline: True
Direct callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_nested
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel/pasid.c:intel_pasid_setup_first_level
```
**Symbols:**

```
ffffffff81b67c70-ffffffff81b67d5d: pasid_flush_caches (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int pasid</code> ➡️ <code>u32 pasid</code>
</li>
</ul>
</details>
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
