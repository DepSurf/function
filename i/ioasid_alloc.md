# Function: <code>ioasid_alloc</code>

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
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
ioasid_t ioasid_alloc(struct ioasid_set *set, ioasid_t min, ioasid_t max, void *private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/ioasid.c (0)
Location: drivers/iommu/ioasid.c:304
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:aux_domain_add_dev
```
**Symbols:**

```
ffffffff81793444-ffffffff817934a2: ioasid_alloc.cold (STB_LOCAL)
ffffffff817930f0-ffffffff81793227: ioasid_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
ioasid_t ioasid_alloc(struct ioasid_set *set, ioasid_t min, ioasid_t max, void *private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/ioasid.c (0)
Location: drivers/iommu/ioasid.c:305
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:aux_domain_add_dev
```
**Symbols:**

```
ffffffff81c0d7ad-ffffffff81c0d80b: ioasid_alloc.cold (STB_LOCAL)
ffffffff817bfb30-ffffffff817bfc6e: ioasid_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
ioasid_t ioasid_alloc(struct ioasid_set *set, ioasid_t min, ioasid_t max, void *private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/ioasid.c (0)
Location: drivers/iommu/ioasid.c:305
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:aux_domain_add_dev
```
**Symbols:**

```
ffffffff81bffb16-ffffffff81bffb74: ioasid_alloc.cold (STB_LOCAL)
ffffffff817a2d50-ffffffff817a2e8e: ioasid_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ioasid_t ioasid_alloc(struct ioasid_set *set, ioasid_t min, ioasid_t max, void *private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/ioasid.c (0)
Location: drivers/iommu/ioasid.c:305
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:aux_domain_add_dev
  - drivers/iommu/iommu-sva-lib.c:iommu_sva_alloc_pasid
```
**Symbols:**

```
ffffffff81d01ff1-ffffffff81d0204f: ioasid_alloc.cold (STB_LOCAL)
ffffffff8182c090-ffffffff8182c1ce: ioasid_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ioasid_t ioasid_alloc(struct ioasid_set *set, ioasid_t min, ioasid_t max, void *private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/ioasid.c (0)
Location: drivers/iommu/ioasid.c:304
Inline: False
Direct callers:
  - drivers/iommu/iommu-sva-lib.c:iommu_sva_alloc_pasid
```
**Symbols:**

```
ffffffff81eca4c3-ffffffff81eca521: ioasid_alloc.cold (STB_LOCAL)
ffffffff8196d270-ffffffff8196d3b2: ioasid_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ioasid_t ioasid_alloc(struct ioasid_set *set, ioasid_t min, ioasid_t max, void *private);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/ioasid.c (ffffffff81ad7a50)
Location: drivers/iommu/ioasid.c:304
Inline: False
Direct callers:
  - drivers/iommu/iommu-sva.c:iommu_sva_alloc_pasid
```
**Symbols:**

```
ffffffff81ad7a50-ffffffff81ad7beb: ioasid_alloc (STB_GLOBAL)
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
