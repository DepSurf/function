# Function: <code>ioasid_find</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
void *ioasid_find(struct ioasid_set *set, ioasid_t ioasid, bool (*getter)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/ioasid.c (ffffffff81792d50)
Location: drivers/iommu/ioasid.c:389
Inline: False
Direct callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:intel_svm_unbind_gpasid
  - drivers/iommu/intel/svm.c:intel_svm_bind_gpasid
```
**Symbols:**

```
ffffffff81792d50-ffffffff81792dce: ioasid_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *ioasid_find(struct ioasid_set *set, ioasid_t ioasid, bool (*getter)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/ioasid.c (ffffffff817bf6d0)
Location: drivers/iommu/ioasid.c:419
Inline: False
Direct callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:pasid_to_svm_sdev
```
**Symbols:**

```
ffffffff817bf6d0-ffffffff817bf75d: ioasid_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *ioasid_find(struct ioasid_set *set, ioasid_t ioasid, bool (*getter)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/ioasid.c (ffffffff817a28f0)
Location: drivers/iommu/ioasid.c:419
Inline: False
Direct callers:
  - drivers/iommu/intel/svm.c:prq_event_thread
  - drivers/iommu/intel/svm.c:pasid_to_svm_sdev
```
**Symbols:**

```
ffffffff817a28f0-ffffffff817a297d: ioasid_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *ioasid_find(struct ioasid_set *set, ioasid_t ioasid, bool (*getter)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/ioasid.c (ffffffff8182bc30)
Location: drivers/iommu/ioasid.c:419
Inline: False
Direct callers:
  - drivers/iommu/iommu-sva-lib.c:iommu_sva_find
```
**Symbols:**

```
ffffffff8182bc30-ffffffff8182bcbd: ioasid_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *ioasid_find(struct ioasid_set *set, ioasid_t ioasid, bool (*getter)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/ioasid.c (ffffffff8196d1b0)
Location: drivers/iommu/ioasid.c:389
Inline: False
Direct callers:
  - drivers/iommu/iommu-sva-lib.c:iommu_sva_find
```
**Symbols:**

```
ffffffff8196d1b0-ffffffff8196d263: ioasid_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *ioasid_find(struct ioasid_set *set, ioasid_t ioasid, bool (*getter)(void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/ioasid.c (ffffffff81ad7980)
Location: drivers/iommu/ioasid.c:389
Inline: False
Direct callers:
  - drivers/iommu/iommu-sva.c:iommu_sva_find
```
**Symbols:**

```
ffffffff81ad7980-ffffffff81ad7a33: ioasid_find (STB_GLOBAL)
```
</details>
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
</ul>
