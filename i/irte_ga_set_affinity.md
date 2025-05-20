# Function: <code>irte_ga_set_affinity</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void irte_ga_set_affinity(void *entry, u16 devid, u16 index, u8 vector, u32 dest_apicid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815afc60)
Location: drivers/iommu/amd_iommu.c:3932
Inline: False
```
**Symbols:**

```
ffffffff815afc60-ffffffff815afcbd: irte_ga_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void irte_ga_set_affinity(void *entry, u16 devid, u16 index, u8 vector, u32 dest_apicid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815c5e80)
Location: drivers/iommu/amd_iommu.c:4070
Inline: False
```
**Symbols:**

```
ffffffff815c5e80-ffffffff815c5eea: irte_ga_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void irte_ga_set_affinity(void *entry, u16 devid, u16 index, u8 vector, u32 dest_apicid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8162c950)
Location: drivers/iommu/amd_iommu.c:3863
Inline: False
```
**Symbols:**

```
ffffffff8162c950-ffffffff8162c9ba: irte_ga_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void irte_ga_set_affinity(void *entry, u16 devid, u16 index, u8 vector, u32 dest_apicid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81666e60)
Location: drivers/iommu/amd_iommu.c:3923
Inline: False
```
**Symbols:**

```
ffffffff81666e60-ffffffff81666e8e: irte_ga_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void irte_ga_set_affinity(void *entry, u16 devid, u16 index, u8 vector, u32 dest_apicid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816854f0)
Location: drivers/iommu/amd_iommu.c:3989
Inline: True
```
**Symbols:**

```
ffffffff816854f0-ffffffff8168552f: irte_ga_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void irte_ga_set_affinity(void *entry, u16 devid, u16 index, u8 vector, u32 dest_apicid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816bca20)
Location: drivers/iommu/amd_iommu.c:3970
Inline: True
```
**Symbols:**

```
ffffffff816bca20-ffffffff816bca61: irte_ga_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void irte_ga_set_affinity(void *entry, u16 devid, u16 index, u8 vector, u32 dest_apicid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816df980)
Location: drivers/iommu/amd_iommu.c:4025
Inline: True
```
**Symbols:**

```
ffffffff816df980-ffffffff816df9c1: irte_ga_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void irte_ga_set_affinity(void *entry, u16 devid, u16 index, u8 vector, u32 dest_apicid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81797690)
Location: drivers/iommu/amd/iommu.c:3450
Inline: True
```
**Symbols:**

```
ffffffff81797690-ffffffff817976d1: irte_ga_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void irte_ga_set_affinity(void *entry, u16 devid, u16 index, u8 vector, u32 dest_apicid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817a5e00)
Location: drivers/iommu/amd/iommu.c:3541
Inline: True
```
**Symbols:**

```
ffffffff817a5e00-ffffffff817a5e41: irte_ga_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void irte_ga_set_affinity(void *entry, u16 devid, u16 index, u8 vector, u32 dest_apicid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81787a00)
Location: drivers/iommu/amd/iommu.c:2907
Inline: True
```
**Symbols:**

```
ffffffff81787a00-ffffffff81787a41: irte_ga_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void irte_ga_set_affinity(void *entry, u16 devid, u16 index, u8 vector, u32 dest_apicid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff8180f2e0)
Location: drivers/iommu/amd/iommu.c:2975
Inline: True
```
**Symbols:**

```
ffffffff8180f2e0-ffffffff8180f321: irte_ga_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void irte_ga_set_affinity(void *entry, u16 devid, u16 index, u8 vector, u32 dest_apicid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff8194fe70)
Location: drivers/iommu/amd/iommu.c:3001
Inline: True
```
**Symbols:**

```
ffffffff8194fe70-ffffffff8194fed0: irte_ga_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void irte_ga_set_affinity(struct amd_iommu *iommu, void *entry, u16 devid, u16 index, u8 vector, u32 dest_apicid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81ab4e40)
Location: drivers/iommu/amd/iommu.c:3156
Inline: True
```
**Symbols:**

```
ffffffff81ab4e40-ffffffff81ab4eaa: irte_ga_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void irte_ga_set_affinity(struct amd_iommu *iommu, void *entry, u16 devid, u16 index, u8 vector, u32 dest_apicid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81afee10)
Location: drivers/iommu/amd/iommu.c:3194
Inline: True
```
**Symbols:**

```
ffffffff81afee10-ffffffff81afee77: irte_ga_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void irte_ga_set_affinity(struct amd_iommu *iommu, void *entry, u16 devid, u16 index, u8 vector, u32 dest_apicid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81b53770)
Location: drivers/iommu/amd/iommu.c:3245
Inline: True
```
**Symbols:**

```
ffffffff81b53770-ffffffff81b537f3: irte_ga_set_affinity (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void irte_ga_set_affinity(void *entry, u16 devid, u16 index, u8 vector, u32 dest_apicid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816a53d0)
Location: drivers/iommu/amd_iommu.c:4025
Inline: True
```
**Symbols:**

```
ffffffff816a53d0-ffffffff816a5411: irte_ga_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void irte_ga_set_affinity(void *entry, u16 devid, u16 index, u8 vector, u32 dest_apicid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81682dc0)
Location: drivers/iommu/amd_iommu.c:4025
Inline: True
```
**Symbols:**

```
ffffffff81682dc0-ffffffff81682e01: irte_ga_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void irte_ga_set_affinity(void *entry, u16 devid, u16 index, u8 vector, u32 dest_apicid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816d3640)
Location: drivers/iommu/amd_iommu.c:4025
Inline: True
```
**Symbols:**

```
ffffffff816d3640-ffffffff816d3681: irte_ga_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void irte_ga_set_affinity(void *entry, u16 devid, u16 index, u8 vector, u32 dest_apicid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816edd40)
Location: drivers/iommu/amd_iommu.c:4025
Inline: True
```
**Symbols:**

```
ffffffff816edd40-ffffffff816edd81: irte_ga_set_affinity (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct amd_iommu *iommu</code>
</li>
<li>
<b>Param reordered. </b>
<code>entry, devid, index, vector, dest_apicid</code> ➡️ <code>iommu, entry, devid, index, vector, dest_apicid</code>
</li>
</ul>
</details>
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
