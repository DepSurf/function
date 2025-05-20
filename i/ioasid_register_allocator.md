# Function: <code>ioasid_register_allocator</code>

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
int ioasid_register_allocator(struct ioasid_allocator_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/ioasid.c (0)
Location: drivers/iommu/ioasid.c:138
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff817934a2-ffffffff817934d0: ioasid_register_allocator.cold (STB_LOCAL)
ffffffff81793230-ffffffff817933dc: ioasid_register_allocator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ioasid_register_allocator(struct ioasid_allocator_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/ioasid.c (0)
Location: drivers/iommu/ioasid.c:139
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81c0d80b-ffffffff81c0d839: ioasid_register_allocator.cold (STB_LOCAL)
ffffffff817bfc70-ffffffff817bfe1c: ioasid_register_allocator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ioasid_register_allocator(struct ioasid_allocator_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/ioasid.c (0)
Location: drivers/iommu/ioasid.c:139
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81bffb74-ffffffff81bffba2: ioasid_register_allocator.cold (STB_LOCAL)
ffffffff817a2e90-ffffffff817a303c: ioasid_register_allocator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ioasid_register_allocator(struct ioasid_allocator_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/ioasid.c (0)
Location: drivers/iommu/ioasid.c:139
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81d0204f-ffffffff81d0207d: ioasid_register_allocator.cold (STB_LOCAL)
ffffffff8182c1d0-ffffffff8182c37c: ioasid_register_allocator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ioasid_register_allocator(struct ioasid_allocator_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/ioasid.c (0)
Location: drivers/iommu/ioasid.c:138
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81eca521-ffffffff81eca54d: ioasid_register_allocator.cold (STB_LOCAL)
ffffffff8196d3c0-ffffffff8196d57b: ioasid_register_allocator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ioasid_register_allocator(struct ioasid_allocator_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/ioasid.c (ffffffff81ad7c00)
Location: drivers/iommu/ioasid.c:138
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff81ad7c00-ffffffff81ad7deb: ioasid_register_allocator (STB_GLOBAL)
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
