# Function: <code>intel_vcmd_ioasid_free</code>

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
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void intel_vcmd_ioasid_free(ioasid_t ioasid, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817a0bba)
Location: drivers/iommu/intel/iommu.c:3092
Inline: True
```
**Symbols:**

```
ffffffff817a0ba0-ffffffff817a0bde: intel_vcmd_ioasid_free (STB_LOCAL)
ffffffff817a6c22-ffffffff817a6c36: intel_vcmd_ioasid_free.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void intel_vcmd_ioasid_free(ioasid_t ioasid, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff817ae12a)
Location: drivers/iommu/intel/iommu.c:3106
Inline: True
```
**Symbols:**

```
ffffffff817ae110-ffffffff817ae14e: intel_vcmd_ioasid_free (STB_LOCAL)
ffffffff81c0c438-ffffffff81c0c44c: intel_vcmd_ioasid_free.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void intel_vcmd_ioasid_free(ioasid_t ioasid, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81790b8a)
Location: drivers/iommu/intel/iommu.c:3146
Inline: True
```
**Symbols:**

```
ffffffff81790b70-ffffffff81790bae: intel_vcmd_ioasid_free (STB_LOCAL)
ffffffff81bfdc8b-ffffffff81bfdc9f: intel_vcmd_ioasid_free.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void intel_vcmd_ioasid_free(ioasid_t ioasid, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8181848a)
Location: drivers/iommu/intel/iommu.c:3139
Inline: True
```
**Symbols:**

```
ffffffff81818470-ffffffff818184ae: intel_vcmd_ioasid_free (STB_LOCAL)
ffffffff81cff362-ffffffff81cff376: intel_vcmd_ioasid_free.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void intel_vcmd_ioasid_free(ioasid_t ioasid, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81ec7b37)
Location: drivers/iommu/intel/iommu.c:2919
Inline: True
```
**Symbols:**

```
ffffffff81959410-ffffffff81959464: intel_vcmd_ioasid_free (STB_LOCAL)
ffffffff81ec7b37-ffffffff81ec7b4b: intel_vcmd_ioasid_free.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void intel_vcmd_ioasid_free(ioasid_t ioasid, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff81ac07d0)
Location: drivers/iommu/intel/iommu.c:2830
Inline: True
```
**Symbols:**

```
ffffffff81ac07d0-ffffffff81ac083b: intel_vcmd_ioasid_free (STB_LOCAL)
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
