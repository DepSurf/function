# Function: <code>iommu_flush_write_buffer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void iommu_flush_write_buffer(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff81535ca0)
Location: drivers/iommu/intel-iommu.c:1330
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:intel_map_sg
  - drivers/iommu/intel-iommu.c:__intel_map_single
```
**Symbols:**

```
ffffffff81535ca0-ffffffff81535d3c: iommu_flush_write_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void iommu_flush_write_buffer(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff8158a360)
Location: drivers/iommu/intel-iommu.c:1337
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:intel_map_sg
  - drivers/iommu/intel-iommu.c:__intel_map_single
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
```
**Symbols:**

```
ffffffff8158a360-ffffffff8158a421: iommu_flush_write_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void iommu_flush_write_buffer(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815b79d0)
Location: drivers/iommu/intel-iommu.c:1351
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:intel_map_sg
  - drivers/iommu/intel-iommu.c:__intel_map_single
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
```
**Symbols:**

```
ffffffff815b79d0-ffffffff815b7a91: iommu_flush_write_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff815d1b19)
Location: drivers/iommu/intel-iommu.c:1356
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:__intel_map_single
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:__intel_map_single
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
```
**Symbols:**

```
ffffffff815cedb0-ffffffff815cee3c: iommu_flush_write_buffer.part.51 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (ffffffff816388e9)
Location: drivers/iommu/intel-iommu.c:1339
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:__intel_map_single
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:__intel_map_single
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
```
**Symbols:**

```
ffffffff81635b20-ffffffff81635bac: iommu_flush_write_buffer.part.53 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void iommu_flush_write_buffer(struct intel_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:1341
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
```
**Symbols:**

```
ffffffff8166fe60-ffffffff8166ff1e: iommu_flush_write_buffer (STB_LOCAL)
ffffffff816753bf-ffffffff816753cb: iommu_flush_write_buffer.cold.78 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void iommu_flush_write_buffer(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:1217
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
```
**Symbols:**

```
ffffffff81693b83-ffffffff81693b8f: iommu_flush_write_buffer.cold.97 (STB_LOCAL)
ffffffff81691530-ffffffff816915ee: iommu_flush_write_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void iommu_flush_write_buffer(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:1222
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
```
**Symbols:**

```
ffffffff816cc41b-ffffffff816cc427: iommu_flush_write_buffer.cold (STB_LOCAL)
ffffffff816c94f0-ffffffff816c9584: iommu_flush_write_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void iommu_flush_write_buffer(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:1233
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
```
**Symbols:**

```
ffffffff816efc9c-ffffffff816efca8: iommu_flush_write_buffer.cold (STB_LOCAL)
ffffffff816ec4c0-ffffffff816ec554: iommu_flush_write_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void iommu_flush_write_buffer(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:1249
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_iommu_hw
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
```
**Symbols:**

```
ffffffff817a736f-ffffffff817a737b: iommu_flush_write_buffer.cold (STB_LOCAL)
ffffffff817a45b0-ffffffff817a4647: iommu_flush_write_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void iommu_flush_write_buffer(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:1332
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_map
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_iommu_hw
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
```
**Symbols:**

```
ffffffff81c0cbb4-ffffffff81c0cbc0: iommu_flush_write_buffer.cold (STB_LOCAL)
ffffffff817b1a40-ffffffff817b1ad7: iommu_flush_write_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void iommu_flush_write_buffer(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:1356
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_iotlb_sync_map
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
```
**Symbols:**

```
ffffffff81bfe32e-ffffffff81bfe33a: iommu_flush_write_buffer.cold (STB_LOCAL)
ffffffff81794780-ffffffff8179481d: iommu_flush_write_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void iommu_flush_write_buffer(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:1360
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_iotlb_sync_map
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
```
**Symbols:**

```
ffffffff81d0015c-ffffffff81d00168: iommu_flush_write_buffer.cold (STB_LOCAL)
ffffffff8181c6b0-ffffffff8181c74d: iommu_flush_write_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void iommu_flush_write_buffer(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (0)
Location: drivers/iommu/intel/iommu.c:1290
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_iotlb_sync_map
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
```
**Symbols:**

```
ffffffff81ec8732-ffffffff81ec873e: iommu_flush_write_buffer.cold (STB_LOCAL)
ffffffff8195ccc0-ffffffff8195cd6b: iommu_flush_write_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void iommu_flush_write_buffer(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81ac48f0)
Location: drivers/iommu/intel/iommu.c:1245
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_iotlb_sync_map
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
```
**Symbols:**

```
ffffffff81ac48f0-ffffffff81ac49a2: iommu_flush_write_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void iommu_flush_write_buffer(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81b112d0)
Location: drivers/iommu/intel/iommu.c:1244
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_iotlb_sync_map
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
```
**Symbols:**

```
ffffffff81b112d0-ffffffff81b11383: iommu_flush_write_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void iommu_flush_write_buffer(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81b65690)
Location: drivers/iommu/intel/iommu.c:1104
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_iotlb_sync_map
  - drivers/iommu/intel/iommu.c:intel_iommu_add
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/iommu.c:init_dmars
  - drivers/iommu/intel/iommu.c:domain_context_mapping_one
```
**Symbols:**

```
ffffffff81b65690-ffffffff81b65743: iommu_flush_write_buffer (STB_GLOBAL)
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
void iommu_flush_write_buffer(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:1233
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
```
**Symbols:**

```
ffffffff816b5482-ffffffff816b548e: iommu_flush_write_buffer.cold (STB_LOCAL)
ffffffff816b1df0-ffffffff816b1e84: iommu_flush_write_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void iommu_flush_write_buffer(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:1233
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
```
**Symbols:**

```
ffffffff816930cc-ffffffff816930d8: iommu_flush_write_buffer.cold (STB_LOCAL)
ffffffff8168f8f0-ffffffff8168f984: iommu_flush_write_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void iommu_flush_write_buffer(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:1233
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
```
**Symbols:**

```
ffffffff816e395c-ffffffff816e3968: iommu_flush_write_buffer.cold (STB_LOCAL)
ffffffff816e0180-ffffffff816e0214: iommu_flush_write_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void iommu_flush_write_buffer(struct intel_iommu *iommu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel-iommu.c (0)
Location: drivers/iommu/intel-iommu.c:1233
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:dmar_iommu_hotplug
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:init_dmars
  - drivers/iommu/intel-iommu.c:domain_context_mapping_one
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_pass_through
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_second_level
  - drivers/iommu/intel-pasid.c:intel_pasid_setup_first_level
```
**Symbols:**

```
ffffffff816fdfec-ffffffff816fdff8: iommu_flush_write_buffer.cold (STB_LOCAL)
ffffffff816fa790-ffffffff816fa824: iommu_flush_write_buffer (STB_GLOBAL)
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
