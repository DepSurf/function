# Function: <code>intel_vcmd_ioasid_alloc</code>

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
ioasid_t intel_vcmd_ioasid_alloc(ioasid_t min, ioasid_t max, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817a0be0)
Location: drivers/iommu/intel/iommu.c:3071
Inline: True
```
**Symbols:**

```
ffffffff817a0be0-ffffffff817a0c45: intel_vcmd_ioasid_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
ioasid_t intel_vcmd_ioasid_alloc(ioasid_t min, ioasid_t max, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817ae150)
Location: drivers/iommu/intel/iommu.c:3085
Inline: True
```
**Symbols:**

```
ffffffff817ae150-ffffffff817ae1b5: intel_vcmd_ioasid_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
ioasid_t intel_vcmd_ioasid_alloc(ioasid_t min, ioasid_t max, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81790bb0)
Location: drivers/iommu/intel/iommu.c:3125
Inline: True
```
**Symbols:**

```
ffffffff81790bb0-ffffffff81790c17: intel_vcmd_ioasid_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
ioasid_t intel_vcmd_ioasid_alloc(ioasid_t min, ioasid_t max, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff818184b0)
Location: drivers/iommu/intel/iommu.c:3118
Inline: True
```
**Symbols:**

```
ffffffff818184b0-ffffffff81818517: intel_vcmd_ioasid_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ioasid_t intel_vcmd_ioasid_alloc(ioasid_t min, ioasid_t max, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81959180)
Location: drivers/iommu/intel/iommu.c:2898
Inline: False
```
**Symbols:**

```
ffffffff81959180-ffffffff819591f0: intel_vcmd_ioasid_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ioasid_t intel_vcmd_ioasid_alloc(ioasid_t min, ioasid_t max, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81ac0470)
Location: drivers/iommu/intel/iommu.c:2809
Inline: False
```
**Symbols:**

```
ffffffff81ac0470-ffffffff81ac04e0: intel_vcmd_ioasid_alloc (STB_LOCAL)
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
