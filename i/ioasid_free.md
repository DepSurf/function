# Function: <code>ioasid_free</code>

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
void ioasid_free(ioasid_t ioasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/ioasid.c (0)
Location: drivers/iommu/ioasid.c:352
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:aux_domain_add_dev
  - drivers/iommu/intel/iommu.c:auxiliary_unlink_device
```
**Symbols:**

```
ffffffff81793403-ffffffff81793417: ioasid_free.cold (STB_LOCAL)
ffffffff81792ee0-ffffffff81792f74: ioasid_free (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ioasid_free(ioasid_t ioasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/ioasid.c (0)
Location: drivers/iommu/ioasid.c:352
Inline: False
Direct callers:
  - kernel/fork.c:__mmdrop
```
**Symbols:**

```
ffffffff81eca4af-ffffffff81eca4c3: ioasid_free.cold (STB_LOCAL)
ffffffff8196d0a0-ffffffff8196d13a: ioasid_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ioasid_free(ioasid_t ioasid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/ioasid.c (ffffffff81ad7840)
Location: drivers/iommu/ioasid.c:352
Inline: False
Direct callers:
  - kernel/fork.c:__mmdrop
```
**Symbols:**

```
ffffffff81ad7840-ffffffff81ad78e7: ioasid_free (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
</ul>
