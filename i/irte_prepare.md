# Function: <code>irte_prepare</code>

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
void irte_prepare(void *entry, u32 delivery_mode, u32 dest_mode, u8 vector, u32 dest_apicid, int devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815ae000)
Location: drivers/iommu/amd_iommu.c:3859
Inline: False
```
**Symbols:**

```
ffffffff815ae000-ffffffff815ae02c: irte_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void irte_prepare(void *entry, u32 delivery_mode, u32 dest_mode, u8 vector, u32 dest_apicid, int devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815c3cb0)
Location: drivers/iommu/amd_iommu.c:3999
Inline: False
```
**Symbols:**

```
ffffffff815c3cb0-ffffffff815c3cdc: irte_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void irte_prepare(void *entry, u32 delivery_mode, u32 dest_mode, u8 vector, u32 dest_apicid, int devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8162aa40)
Location: drivers/iommu/amd_iommu.c:3792
Inline: False
```
**Symbols:**

```
ffffffff8162aa40-ffffffff8162aa6c: irte_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void irte_prepare(void *entry, u32 delivery_mode, u32 dest_mode, u8 vector, u32 dest_apicid, int devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81665670)
Location: drivers/iommu/amd_iommu.c:3852
Inline: False
```
**Symbols:**

```
ffffffff81665670-ffffffff8166569c: irte_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void irte_prepare(void *entry, u32 delivery_mode, u32 dest_mode, u8 vector, u32 dest_apicid, int devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81683f30)
Location: drivers/iommu/amd_iommu.c:3917
Inline: False
```
**Symbols:**

```
ffffffff81683f30-ffffffff81683f5c: irte_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void irte_prepare(void *entry, u32 delivery_mode, u32 dest_mode, u8 vector, u32 dest_apicid, int devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816bb4c0)
Location: drivers/iommu/amd_iommu.c:3898
Inline: False
```
**Symbols:**

```
ffffffff816bb4c0-ffffffff816bb4ed: irte_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void irte_prepare(void *entry, u32 delivery_mode, u32 dest_mode, u8 vector, u32 dest_apicid, int devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816de320)
Location: drivers/iommu/amd_iommu.c:3953
Inline: False
```
**Symbols:**

```
ffffffff816de320-ffffffff816de34d: irte_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void irte_prepare(void *entry, u32 delivery_mode, u32 dest_mode, u8 vector, u32 dest_apicid, int devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81794cc0)
Location: drivers/iommu/amd/iommu.c:3378
Inline: False
```
**Symbols:**

```
ffffffff81794cc0-ffffffff81794ced: irte_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void irte_prepare(void *entry, u32 delivery_mode, bool dest_mode, u8 vector, u32 dest_apicid, int devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817a3180)
Location: drivers/iommu/amd/iommu.c:3469
Inline: False
```
**Symbols:**

```
ffffffff817a3180-ffffffff817a31ad: irte_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void irte_prepare(void *entry, u32 delivery_mode, bool dest_mode, u8 vector, u32 dest_apicid, int devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81785f00)
Location: drivers/iommu/amd/iommu.c:2835
Inline: False
```
**Symbols:**

```
ffffffff81785f00-ffffffff81785f2d: irte_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void irte_prepare(void *entry, u32 delivery_mode, bool dest_mode, u8 vector, u32 dest_apicid, int devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff8180cd40)
Location: drivers/iommu/amd/iommu.c:2903
Inline: False
```
**Symbols:**

```
ffffffff8180cd40-ffffffff8180cd6d: irte_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void irte_prepare(void *entry, u32 delivery_mode, bool dest_mode, u8 vector, u32 dest_apicid, int devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff8194d3d0)
Location: drivers/iommu/amd/iommu.c:2929
Inline: False
```
**Symbols:**

```
ffffffff8194d3d0-ffffffff8194d40c: irte_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void irte_prepare(void *entry, u32 delivery_mode, bool dest_mode, u8 vector, u32 dest_apicid, int devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81ab1910)
Location: drivers/iommu/amd/iommu.c:3084
Inline: False
```
**Symbols:**

```
ffffffff81ab1910-ffffffff81ab194c: irte_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void irte_prepare(void *entry, u32 delivery_mode, bool dest_mode, u8 vector, u32 dest_apicid, int devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81afd980)
Location: drivers/iommu/amd/iommu.c:3122
Inline: False
```
**Symbols:**

```
ffffffff81afd980-ffffffff81afd9bc: irte_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void irte_prepare(void *entry, u32 delivery_mode, bool dest_mode, u8 vector, u32 dest_apicid, int devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81b50f60)
Location: drivers/iommu/amd/iommu.c:3173
Inline: False
```
**Symbols:**

```
ffffffff81b50f60-ffffffff81b50f9c: irte_prepare (STB_LOCAL)
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
void irte_prepare(void *entry, u32 delivery_mode, u32 dest_mode, u8 vector, u32 dest_apicid, int devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816a3d70)
Location: drivers/iommu/amd_iommu.c:3953
Inline: False
```
**Symbols:**

```
ffffffff816a3d70-ffffffff816a3d9d: irte_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void irte_prepare(void *entry, u32 delivery_mode, u32 dest_mode, u8 vector, u32 dest_apicid, int devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81681760)
Location: drivers/iommu/amd_iommu.c:3953
Inline: False
```
**Symbols:**

```
ffffffff81681760-ffffffff8168178d: irte_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void irte_prepare(void *entry, u32 delivery_mode, u32 dest_mode, u8 vector, u32 dest_apicid, int devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816d1fe0)
Location: drivers/iommu/amd_iommu.c:3953
Inline: False
```
**Symbols:**

```
ffffffff816d1fe0-ffffffff816d200d: irte_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void irte_prepare(void *entry, u32 delivery_mode, u32 dest_mode, u8 vector, u32 dest_apicid, int devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816ec5e0)
Location: drivers/iommu/amd_iommu.c:3953
Inline: False
```
**Symbols:**

```
ffffffff816ec5e0-ffffffff816ec60d: irte_prepare (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>u32 dest_mode</code> ➡️ <code>bool dest_mode</code>
</li>
</ul>
</details>
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
