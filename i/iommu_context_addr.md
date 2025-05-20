# Function: <code>iommu_context_addr</code>

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
In drivers/iommu/intel-iommu.c (ffffffff8153754f)
Location: drivers/iommu/intel-iommu.c:836
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:domain_context_clear_one_cb
  - drivers/iommu/intel-iommu.c:device_context_mapped
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid
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
In drivers/iommu/intel-iommu.c (ffffffff8158fd8b)
Location: drivers/iommu/intel-iommu.c:843
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel-iommu.c:domain_context_clear_one_cb
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:device_context_mapped
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
In drivers/iommu/intel-iommu.c (ffffffff815bd5eb)
Location: drivers/iommu/intel-iommu.c:844
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel-iommu.c:domain_context_clear_one_cb
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:device_context_mapped
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
In drivers/iommu/intel-iommu.c (ffffffff815d31ec)
Location: drivers/iommu/intel-iommu.c:849
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel-iommu.c:domain_context_clear_one_cb
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:device_context_mapped
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
In drivers/iommu/intel-iommu.c (ffffffff81639eec)
Location: drivers/iommu/intel-iommu.c:822
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel-iommu.c:domain_context_clear_one_cb
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:device_context_mapped
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
In drivers/iommu/intel-iommu.c (ffffffff81675085)
Location: drivers/iommu/intel-iommu.c:824
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel-iommu.c:domain_context_clear_one_cb
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:device_context_mapped
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct context_entry *iommu_context_addr(struct intel_iommu *iommu, u8 bus, u8 devfn, int alloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81691100)
Location: drivers/iommu/intel-iommu.c:700
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel-iommu.c:domain_context_clear_one_cb
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:device_context_mapped
```
**Symbols:**

```
ffffffff81691100-ffffffff816911f7: iommu_context_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct context_entry *iommu_context_addr(struct intel_iommu *iommu, u8 bus, u8 devfn, int alloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816c90b0)
Location: drivers/iommu/intel-iommu.c:685
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel-iommu.c:domain_context_clear_one_cb
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:device_context_mapped
```
**Symbols:**

```
ffffffff816c90b0-ffffffff816c91a9: iommu_context_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct context_entry *iommu_context_addr(struct intel_iommu *iommu, u8 bus, u8 devfn, int alloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816ec080)
Location: drivers/iommu/intel-iommu.c:696
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel-iommu.c:domain_context_clear_one_cb
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:device_context_mapped
```
**Symbols:**

```
ffffffff816ec080-ffffffff816ec179: iommu_context_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct context_entry *iommu_context_addr(struct intel_iommu *iommu, u8 bus, u8 devfn, int alloc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817a1bde)
Location: drivers/iommu/intel/iommu.c:711
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:free_context_table
  - drivers/iommu/intel/iommu.c:free_context_table
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel/iommu.c:domain_context_clear_one_cb
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:device_context_mapped
```
**Symbols:**

```
ffffffff817a42c0-ffffffff817a43fb: iommu_context_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct context_entry *iommu_context_addr(struct intel_iommu *iommu, u8 bus, u8 devfn, int alloc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817af22e)
Location: drivers/iommu/intel/iommu.c:752
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:free_context_table
  - drivers/iommu/intel/iommu.c:free_context_table
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel/iommu.c:domain_context_clear_one_cb
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:device_context_mapped
```
**Symbols:**

```
ffffffff817b0c70-ffffffff817b0dab: iommu_context_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct context_entry *iommu_context_addr(struct intel_iommu *iommu, u8 bus, u8 devfn, int alloc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817924dc)
Location: drivers/iommu/intel/iommu.c:768
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:free_dmar_iommu
  - drivers/iommu/intel/iommu.c:free_dmar_iommu
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel/iommu.c:domain_context_clear_one
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:device_context_mapped
```
**Symbols:**

```
ffffffff81793700-ffffffff8179383b: iommu_context_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct context_entry *iommu_context_addr(struct intel_iommu *iommu, u8 bus, u8 devfn, int alloc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81819d9d)
Location: drivers/iommu/intel/iommu.c:774
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:free_dmar_iommu
  - drivers/iommu/intel/iommu.c:free_dmar_iommu
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel/iommu.c:domain_context_clear_one
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:device_context_mapped
```
**Symbols:**

```
ffffffff8181b560-ffffffff8181b69b: iommu_context_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct context_entry *iommu_context_addr(struct intel_iommu *iommu, u8 bus, u8 devfn, int alloc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8195a917)
Location: drivers/iommu/intel/iommu.c:626
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:free_dmar_iommu
  - drivers/iommu/intel/iommu.c:free_dmar_iommu
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel/iommu.c:domain_context_clear_one
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:device_context_mapped
```
**Symbols:**

```
ffffffff8195c2e0-ffffffff8195c434: iommu_context_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct context_entry *iommu_context_addr(struct intel_iommu *iommu, u8 bus, u8 devfn, int alloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81ac3cd0)
Location: drivers/iommu/intel/iommu.c:595
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:domain_context_clear_one
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
  - drivers/iommu/intel/iommu.c:free_dmar_iommu
  - drivers/iommu/intel/iommu.c:free_dmar_iommu
```
**Symbols:**

```
ffffffff81ac3cd0-ffffffff81ac3e5c: iommu_context_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct context_entry *iommu_context_addr(struct intel_iommu *iommu, u8 bus, u8 devfn, int alloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81b106c0)
Location: drivers/iommu/intel/iommu.c:595
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:domain_context_clear_one
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
```
**Symbols:**

```
ffffffff81b106c0-ffffffff81b1081e: iommu_context_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct context_entry *iommu_context_addr(struct intel_iommu *iommu, u8 bus, u8 devfn, int alloc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81b65160)
Location: drivers/iommu/intel/iommu.c:455
Inline: True
Direct callers:
  - drivers/iommu/intel/iommu.c:domain_context_clear_one
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
```
**Symbols:**

```
ffffffff81b65160-ffffffff81b652be: iommu_context_addr (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
struct context_entry *iommu_context_addr(struct intel_iommu *iommu, u8 bus, u8 devfn, int alloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816b19b0)
Location: drivers/iommu/intel-iommu.c:696
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel-iommu.c:domain_context_clear_one_cb
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:device_context_mapped
```
**Symbols:**

```
ffffffff816b19b0-ffffffff816b1aa9: iommu_context_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct context_entry *iommu_context_addr(struct intel_iommu *iommu, u8 bus, u8 devfn, int alloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8168f4b0)
Location: drivers/iommu/intel-iommu.c:696
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel-iommu.c:domain_context_clear_one_cb
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:device_context_mapped
```
**Symbols:**

```
ffffffff8168f4b0-ffffffff8168f5a9: iommu_context_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct context_entry *iommu_context_addr(struct intel_iommu *iommu, u8 bus, u8 devfn, int alloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816dfd40)
Location: drivers/iommu/intel-iommu.c:696
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel-iommu.c:domain_context_clear_one_cb
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:device_context_mapped
```
**Symbols:**

```
ffffffff816dfd40-ffffffff816dfe39: iommu_context_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct context_entry *iommu_context_addr(struct intel_iommu *iommu, u8 bus, u8 devfn, int alloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816fa350)
Location: drivers/iommu/intel-iommu.c:696
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:intel_iommu_enable_pasid
  - drivers/iommu/intel-iommu.c:domain_context_clear_one_cb
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:free_dmar_iommu
  - drivers/iommu/intel-iommu.c:device_context_mapped
```
**Symbols:**

```
ffffffff816fa350-ffffffff816fa449: iommu_context_addr (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
