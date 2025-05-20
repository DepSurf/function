# Function: <code>irte_set_affinity</code>

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
void irte_set_affinity(void *entry, u16 devid, u16 index, u8 vector, u32 dest_apicid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815afb00)
Location: drivers/iommu/amd_iommu.c:3922
Inline: False
```
**Symbols:**

```
ffffffff815afb00-ffffffff815afb26: irte_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void irte_set_affinity(void *entry, u16 devid, u16 index, u8 vector, u32 dest_apicid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815c5ce0)
Location: drivers/iommu/amd_iommu.c:4060
Inline: False
```
**Symbols:**

```
ffffffff815c5ce0-ffffffff815c5d06: irte_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void irte_set_affinity(void *entry, u16 devid, u16 index, u8 vector, u32 dest_apicid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8162c7b0)
Location: drivers/iommu/amd_iommu.c:3853
Inline: False
```
**Symbols:**

```
ffffffff8162c7b0-ffffffff8162c7d6: irte_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void irte_set_affinity(void *entry, u16 devid, u16 index, u8 vector, u32 dest_apicid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81667190)
Location: drivers/iommu/amd_iommu.c:3913
Inline: False
```
**Symbols:**

```
ffffffff81667190-ffffffff816671b6: irte_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void irte_set_affinity(void *entry, u16 devid, u16 index, u8 vector, u32 dest_apicid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81685840)
Location: drivers/iommu/amd_iommu.c:3979
Inline: False
```
**Symbols:**

```
ffffffff81685840-ffffffff81685866: irte_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void irte_set_affinity(void *entry, u16 devid, u16 index, u8 vector, u32 dest_apicid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816bcd80)
Location: drivers/iommu/amd_iommu.c:3960
Inline: False
```
**Symbols:**

```
ffffffff816bcd80-ffffffff816bcda7: irte_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void irte_set_affinity(void *entry, u16 devid, u16 index, u8 vector, u32 dest_apicid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816dfd50)
Location: drivers/iommu/amd_iommu.c:4015
Inline: False
```
**Symbols:**

```
ffffffff816dfd50-ffffffff816dfd77: irte_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void irte_set_affinity(void *entry, u16 devid, u16 index, u8 vector, u32 dest_apicid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81797430)
Location: drivers/iommu/amd/iommu.c:3440
Inline: False
```
**Symbols:**

```
ffffffff81797430-ffffffff81797457: irte_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void irte_set_affinity(void *entry, u16 devid, u16 index, u8 vector, u32 dest_apicid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817a5b70)
Location: drivers/iommu/amd/iommu.c:3531
Inline: False
```
**Symbols:**

```
ffffffff817a5b70-ffffffff817a5b97: irte_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void irte_set_affinity(void *entry, u16 devid, u16 index, u8 vector, u32 dest_apicid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81787890)
Location: drivers/iommu/amd/iommu.c:2897
Inline: False
```
**Symbols:**

```
ffffffff81787890-ffffffff817878b7: irte_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void irte_set_affinity(void *entry, u16 devid, u16 index, u8 vector, u32 dest_apicid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff8180f010)
Location: drivers/iommu/amd/iommu.c:2965
Inline: False
```
**Symbols:**

```
ffffffff8180f010-ffffffff8180f037: irte_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void irte_set_affinity(void *entry, u16 devid, u16 index, u8 vector, u32 dest_apicid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff8194fcf0)
Location: drivers/iommu/amd/iommu.c:2991
Inline: False
```
**Symbols:**

```
ffffffff8194fcf0-ffffffff8194fd25: irte_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void irte_set_affinity(struct amd_iommu *iommu, void *entry, u16 devid, u16 index, u8 vector, u32 dest_apicid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81ab4870)
Location: drivers/iommu/amd/iommu.c:3146
Inline: False
```
**Symbols:**

```
ffffffff81ab4870-ffffffff81ab48ab: irte_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void irte_set_affinity(struct amd_iommu *iommu, void *entry, u16 devid, u16 index, u8 vector, u32 dest_apicid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81aff410)
Location: drivers/iommu/amd/iommu.c:3184
Inline: False
```
**Symbols:**

```
ffffffff81aff410-ffffffff81aff44b: irte_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void irte_set_affinity(struct amd_iommu *iommu, void *entry, u16 devid, u16 index, u8 vector, u32 dest_apicid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81b52800)
Location: drivers/iommu/amd/iommu.c:3235
Inline: False
```
**Symbols:**

```
ffffffff81b52800-ffffffff81b5283b: irte_set_affinity (STB_LOCAL)
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
void irte_set_affinity(void *entry, u16 devid, u16 index, u8 vector, u32 dest_apicid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816a57a0)
Location: drivers/iommu/amd_iommu.c:4015
Inline: False
```
**Symbols:**

```
ffffffff816a57a0-ffffffff816a57c7: irte_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void irte_set_affinity(void *entry, u16 devid, u16 index, u8 vector, u32 dest_apicid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81683190)
Location: drivers/iommu/amd_iommu.c:4015
Inline: False
```
**Symbols:**

```
ffffffff81683190-ffffffff816831b7: irte_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void irte_set_affinity(void *entry, u16 devid, u16 index, u8 vector, u32 dest_apicid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816d3a10)
Location: drivers/iommu/amd_iommu.c:4015
Inline: False
```
**Symbols:**

```
ffffffff816d3a10-ffffffff816d3a37: irte_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void irte_set_affinity(void *entry, u16 devid, u16 index, u8 vector, u32 dest_apicid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816ee110)
Location: drivers/iommu/amd_iommu.c:4015
Inline: False
```
**Symbols:**

```
ffffffff816ee110-ffffffff816ee137: irte_set_affinity (STB_LOCAL)
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
