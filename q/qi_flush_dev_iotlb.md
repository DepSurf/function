# Function: <code>qi_flush_dev_iotlb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void qi_flush_dev_iotlb(struct intel_iommu *iommu, u16 sid, u16 qdep, u64 addr, unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff81534ea0)
Location: drivers/iommu/dmar.c:1316
Inline: False
Direct callers:
  - drivers/iommu/intel-iommu.c:iommu_flush_dev_iotlb
```
**Symbols:**

```
ffffffff81534ea0-ffffffff81534f59: qi_flush_dev_iotlb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void qi_flush_dev_iotlb(struct intel_iommu *iommu, u16 sid, u16 qdep, u64 addr, unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff815896f0)
Location: drivers/iommu/dmar.c:1329
Inline: False
```
**Symbols:**

```
ffffffff815896f0-ffffffff815897b1: qi_flush_dev_iotlb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void qi_flush_dev_iotlb(struct intel_iommu *iommu, u16 sid, u16 qdep, u64 addr, unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff815b6db0)
Location: drivers/iommu/dmar.c:1330
Inline: False
```
**Symbols:**

```
ffffffff815b6db0-ffffffff815b6e71: qi_flush_dev_iotlb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void qi_flush_dev_iotlb(struct intel_iommu *iommu, u16 sid, u16 qdep, u64 addr, unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff815ccc00)
Location: drivers/iommu/dmar.c:1339
Inline: False
```
**Symbols:**

```
ffffffff815ccc00-ffffffff815cccb8: qi_flush_dev_iotlb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void qi_flush_dev_iotlb(struct intel_iommu *iommu, u16 sid, u16 qdep, u64 addr, unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff816339f0)
Location: drivers/iommu/dmar.c:1342
Inline: False
```
**Symbols:**

```
ffffffff816339f0-ffffffff81633aa5: qi_flush_dev_iotlb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void qi_flush_dev_iotlb(struct intel_iommu *iommu, u16 sid, u16 pfsid, u16 qdep, u64 addr, unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff8166eb50)
Location: drivers/iommu/dmar.c:1342
Inline: False
```
**Symbols:**

```
ffffffff8166eb50-ffffffff8166ec27: qi_flush_dev_iotlb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void qi_flush_dev_iotlb(struct intel_iommu *iommu, u16 sid, u16 pfsid, u16 qdep, u64 addr, unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff8168d090)
Location: drivers/iommu/dmar.c:1359
Inline: False
Direct callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry
```
**Symbols:**

```
ffffffff8168d090-ffffffff8168d177: qi_flush_dev_iotlb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void qi_flush_dev_iotlb(struct intel_iommu *iommu, u16 sid, u16 pfsid, u16 qdep, u64 addr, unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff816c4ac0)
Location: drivers/iommu/dmar.c:1348
Inline: False
Direct callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry
```
**Symbols:**

```
ffffffff816c4ac0-ffffffff816c4bab: qi_flush_dev_iotlb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void qi_flush_dev_iotlb(struct intel_iommu *iommu, u16 sid, u16 pfsid, u16 qdep, u64 addr, unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff816e7a10)
Location: drivers/iommu/dmar.c:1358
Inline: False
Direct callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry
```
**Symbols:**

```
ffffffff816e7a10-ffffffff816e7adb: qi_flush_dev_iotlb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void qi_flush_dev_iotlb(struct intel_iommu *iommu, u16 sid, u16 pfsid, u16 qdep, u64 addr, unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff8179e290)
Location: drivers/iommu/intel/dmar.c:1377
Inline: False
Direct callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry
```
**Symbols:**

```
ffffffff8179e290-ffffffff8179e35d: qi_flush_dev_iotlb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void qi_flush_dev_iotlb(struct intel_iommu *iommu, u16 sid, u16 pfsid, u16 qdep, u64 addr, unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff817abff0)
Location: drivers/iommu/intel/dmar.c:1416
Inline: False
Direct callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry
```
**Symbols:**

```
ffffffff817abff0-ffffffff817ac0bd: qi_flush_dev_iotlb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void qi_flush_dev_iotlb(struct intel_iommu *iommu, u16 sid, u16 pfsid, u16 qdep, u64 addr, unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff8178eec0)
Location: drivers/iommu/intel/dmar.c:1485
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:domain_context_clear_one
  - drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry
```
**Symbols:**

```
ffffffff8178eec0-ffffffff8178ef83: qi_flush_dev_iotlb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void qi_flush_dev_iotlb(struct intel_iommu *iommu, u16 sid, u16 pfsid, u16 qdep, u64 addr, unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:1514
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:domain_context_clear_one
  - drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry
```
**Symbols:**

```
ffffffff81cff0f2-ffffffff81cff118: qi_flush_dev_iotlb.cold (STB_LOCAL)
ffffffff81816750-ffffffff81816836: qi_flush_dev_iotlb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void qi_flush_dev_iotlb(struct intel_iommu *iommu, u16 sid, u16 pfsid, u16 qdep, u64 addr, unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:1510
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:domain_context_clear_one
```
**Symbols:**

```
ffffffff81ec78be-ffffffff81ec78e4: qi_flush_dev_iotlb.cold (STB_LOCAL)
ffffffff819576d0-ffffffff819577ec: qi_flush_dev_iotlb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void qi_flush_dev_iotlb(struct intel_iommu *iommu, u16 sid, u16 pfsid, u16 qdep, u64 addr, unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:1499
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:domain_context_clear_one
  - drivers/iommu/intel/iommu.c:domain_context_clear_one
```
**Symbols:**

```
ffffffff8209735e-ffffffff82097384: qi_flush_dev_iotlb.cold (STB_LOCAL)
ffffffff81abe610-ffffffff81abe72c: qi_flush_dev_iotlb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void qi_flush_dev_iotlb(struct intel_iommu *iommu, u16 sid, u16 pfsid, u16 qdep, u64 addr, unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:1520
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:domain_context_clear_one
  - drivers/iommu/intel/iommu.c:domain_context_clear_one
```
**Symbols:**

```
ffffffff821183c4-ffffffff821183ea: qi_flush_dev_iotlb.cold (STB_LOCAL)
ffffffff81b0afa0-ffffffff81b0b0bc: qi_flush_dev_iotlb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void qi_flush_dev_iotlb(struct intel_iommu *iommu, u16 sid, u16 pfsid, u16 qdep, u64 addr, unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:1520
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:domain_context_clear_one
  - drivers/iommu/intel/iommu.c:domain_context_clear_one
  - drivers/iommu/intel/iommu.c:parent_domain_flush
  - drivers/iommu/intel/iommu.c:parent_domain_flush
  - drivers/iommu/intel/nested.c:intel_nested_cache_invalidate_user
```
**Symbols:**

```
ffffffff821f60d8-ffffffff821f60fe: qi_flush_dev_iotlb.cold (STB_LOCAL)
ffffffff81b5eff0-ffffffff81b5f120: qi_flush_dev_iotlb (STB_GLOBAL)
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
void qi_flush_dev_iotlb(struct intel_iommu *iommu, u16 sid, u16 pfsid, u16 qdep, u64 addr, unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff816ad4f0)
Location: drivers/iommu/dmar.c:1358
Inline: False
Direct callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry
```
**Symbols:**

```
ffffffff816ad4f0-ffffffff816ad5bb: qi_flush_dev_iotlb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void qi_flush_dev_iotlb(struct intel_iommu *iommu, u16 sid, u16 pfsid, u16 qdep, u64 addr, unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff8168ae50)
Location: drivers/iommu/dmar.c:1358
Inline: False
Direct callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry
```
**Symbols:**

```
ffffffff8168ae50-ffffffff8168af1b: qi_flush_dev_iotlb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void qi_flush_dev_iotlb(struct intel_iommu *iommu, u16 sid, u16 pfsid, u16 qdep, u64 addr, unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff816db6d0)
Location: drivers/iommu/dmar.c:1358
Inline: False
Direct callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry
```
**Symbols:**

```
ffffffff816db6d0-ffffffff816db79b: qi_flush_dev_iotlb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void qi_flush_dev_iotlb(struct intel_iommu *iommu, u16 sid, u16 pfsid, u16 qdep, u64 addr, unsigned int mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff816f5ca0)
Location: drivers/iommu/dmar.c:1358
Inline: False
Direct callers:
  - drivers/iommu/intel-pasid.c:intel_pasid_tear_down_entry
```
**Symbols:**

```
ffffffff816f5ca0-ffffffff816f5d6b: qi_flush_dev_iotlb (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u16 pfsid</code>
</li>
<li>
<b>Param reordered. </b>
<code>iommu, sid, qdep, addr, mask</code> ➡️ <code>iommu, sid, pfsid, qdep, addr, mask</code>
</li>
</ul>
</details>
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
