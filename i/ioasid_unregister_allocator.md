# Function: <code>ioasid_unregister_allocator</code>

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
void ioasid_unregister_allocator(struct ioasid_allocator_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/ioasid.c (0)
Location: drivers/iommu/ioasid.c:206
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:free_dmar_iommu
```
**Symbols:**

```
ffffffff81793417-ffffffff81793444: ioasid_unregister_allocator.cold (STB_LOCAL)
ffffffff81792f80-ffffffff817930e1: ioasid_unregister_allocator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void ioasid_unregister_allocator(struct ioasid_allocator_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/ioasid.c (0)
Location: drivers/iommu/ioasid.c:207
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:free_dmar_iommu
```
**Symbols:**

```
ffffffff81c0d780-ffffffff81c0d7ad: ioasid_unregister_allocator.cold (STB_LOCAL)
ffffffff817bf9c0-ffffffff817bfb21: ioasid_unregister_allocator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void ioasid_unregister_allocator(struct ioasid_allocator_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/ioasid.c (0)
Location: drivers/iommu/ioasid.c:207
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:free_dmar_iommu
```
**Symbols:**

```
ffffffff81bffae9-ffffffff81bffb16: ioasid_unregister_allocator.cold (STB_LOCAL)
ffffffff817a2be0-ffffffff817a2d41: ioasid_unregister_allocator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ioasid_unregister_allocator(struct ioasid_allocator_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/ioasid.c (0)
Location: drivers/iommu/ioasid.c:207
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:free_dmar_iommu
```
**Symbols:**

```
ffffffff81d01fc4-ffffffff81d01ff1: ioasid_unregister_allocator.cold (STB_LOCAL)
ffffffff8182bf20-ffffffff8182c081: ioasid_unregister_allocator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ioasid_unregister_allocator(struct ioasid_allocator_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/ioasid.c (0)
Location: drivers/iommu/ioasid.c:206
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:free_dmar_iommu
```
**Symbols:**

```
ffffffff81eca482-ffffffff81eca4af: ioasid_unregister_allocator.cold (STB_LOCAL)
ffffffff8196cf30-ffffffff8196d09d: ioasid_unregister_allocator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ioasid_unregister_allocator(struct ioasid_allocator_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/ioasid.c (ffffffff81ad7690)
Location: drivers/iommu/ioasid.c:206
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:free_dmar_iommu
```
**Symbols:**

```
ffffffff81ad7690-ffffffff81ad7826: ioasid_unregister_allocator (STB_GLOBAL)
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
