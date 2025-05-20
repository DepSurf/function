# Function: <code>amd_iommu_get_resv_regions</code>

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
void amd_iommu_get_resv_regions(struct device *dev, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815b23a0)
Location: drivers/iommu/amd_iommu.c:3164
Inline: False
```
**Symbols:**

```
ffffffff815b23a0-ffffffff815b2614: amd_iommu_get_resv_regions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void amd_iommu_get_resv_regions(struct device *dev, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815c8180)
Location: drivers/iommu/amd_iommu.c:3304
Inline: False
```
**Symbols:**

```
ffffffff815c8180-ffffffff815c83b3: amd_iommu_get_resv_regions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void amd_iommu_get_resv_regions(struct device *dev, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8162eb30)
Location: drivers/iommu/amd_iommu.c:3087
Inline: False
```
**Symbols:**

```
ffffffff8162eb30-ffffffff8162ed50: amd_iommu_get_resv_regions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void amd_iommu_get_resv_regions(struct device *dev, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (0)
Location: drivers/iommu/amd_iommu.c:3095
Inline: False
```
**Symbols:**

```
ffffffff8166a310-ffffffff8166a515: amd_iommu_get_resv_regions (STB_LOCAL)
ffffffff8166b6a3-ffffffff8166b6c3: amd_iommu_get_resv_regions.cold.48 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void amd_iommu_get_resv_regions(struct device *dev, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (0)
Location: drivers/iommu/amd_iommu.c:3161
Inline: False
```
**Symbols:**

```
ffffffff81687f30-ffffffff81688110: amd_iommu_get_resv_regions (STB_LOCAL)
ffffffff81689d29-ffffffff81689d49: amd_iommu_get_resv_regions.cold.47 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void amd_iommu_get_resv_regions(struct device *dev, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (0)
Location: drivers/iommu/amd_iommu.c:3140
Inline: False
```
**Symbols:**

```
ffffffff816bf4b0-ffffffff816bf696: amd_iommu_get_resv_regions (STB_LOCAL)
ffffffff816c132f-ffffffff816c1343: amd_iommu_get_resv_regions.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void amd_iommu_get_resv_regions(struct device *dev, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (0)
Location: drivers/iommu/amd_iommu.c:3175
Inline: False
```
**Symbols:**

```
ffffffff816e2840-ffffffff816e2a26: amd_iommu_get_resv_regions (STB_LOCAL)
ffffffff816e4352-ffffffff816e4366: amd_iommu_get_resv_regions.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void amd_iommu_get_resv_regions(struct device *dev, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:2567
Inline: False
```
**Symbols:**

```
ffffffff81797150-ffffffff817972db: amd_iommu_get_resv_regions (STB_LOCAL)
ffffffff8179a81d-ffffffff8179a831: amd_iommu_get_resv_regions.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void amd_iommu_get_resv_regions(struct device *dev, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:2658
Inline: False
```
**Symbols:**

```
ffffffff817a55b0-ffffffff817a573e: amd_iommu_get_resv_regions (STB_LOCAL)
ffffffff81c0b6e7-ffffffff81c0b6fb: amd_iommu_get_resv_regions.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void amd_iommu_get_resv_regions(struct device *dev, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:2088
Inline: False
```
**Symbols:**

```
ffffffff817875b0-ffffffff8178773e: amd_iommu_get_resv_regions (STB_LOCAL)
ffffffff81bfd19c-ffffffff81bfd1b0: amd_iommu_get_resv_regions.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void amd_iommu_get_resv_regions(struct device *dev, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:2149
Inline: False
```
**Symbols:**

```
ffffffff8180e280-ffffffff8180e40e: amd_iommu_get_resv_regions (STB_LOCAL)
ffffffff81cfe03d-ffffffff81cfe051: amd_iommu_get_resv_regions.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void amd_iommu_get_resv_regions(struct device *dev, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:2167
Inline: False
```
**Symbols:**

```
ffffffff8194f420-ffffffff8194f5ca: amd_iommu_get_resv_regions (STB_LOCAL)
ffffffff81ec69cb-ffffffff81ec69df: amd_iommu_get_resv_regions.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void amd_iommu_get_resv_regions(struct device *dev, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81ab3a60)
Location: drivers/iommu/amd/iommu.c:2307
Inline: False
```
**Symbols:**

```
ffffffff81ab3a60-ffffffff81ab3c74: amd_iommu_get_resv_regions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void amd_iommu_get_resv_regions(struct device *dev, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81b00a50)
Location: drivers/iommu/amd/iommu.c:2328
Inline: False
```
**Symbols:**

```
ffffffff81b00a50-ffffffff81b00c64: amd_iommu_get_resv_regions (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void amd_iommu_get_resv_regions(struct device *dev, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81b549e0)
Location: drivers/iommu/amd/iommu.c:2498
Inline: False
```
**Symbols:**

```
ffffffff81b549e0-ffffffff81b54c6a: amd_iommu_get_resv_regions (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void amd_iommu_get_resv_regions(struct device *dev, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (0)
Location: drivers/iommu/amd_iommu.c:3175
Inline: False
```
**Symbols:**

```
ffffffff816a8290-ffffffff816a8476: amd_iommu_get_resv_regions (STB_LOCAL)
ffffffff816a9e32-ffffffff816a9e46: amd_iommu_get_resv_regions.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void amd_iommu_get_resv_regions(struct device *dev, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (0)
Location: drivers/iommu/amd_iommu.c:3175
Inline: False
```
**Symbols:**

```
ffffffff81685c80-ffffffff81685e66: amd_iommu_get_resv_regions (STB_LOCAL)
ffffffff81687792-ffffffff816877a6: amd_iommu_get_resv_regions.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void amd_iommu_get_resv_regions(struct device *dev, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (0)
Location: drivers/iommu/amd_iommu.c:3175
Inline: False
```
**Symbols:**

```
ffffffff816d6500-ffffffff816d66e6: amd_iommu_get_resv_regions (STB_LOCAL)
ffffffff816d8012-ffffffff816d8026: amd_iommu_get_resv_regions.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void amd_iommu_get_resv_regions(struct device *dev, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (0)
Location: drivers/iommu/amd_iommu.c:3175
Inline: False
```
**Symbols:**

```
ffffffff816f0ab0-ffffffff816f0c96: amd_iommu_get_resv_regions (STB_LOCAL)
ffffffff816f25c2-ffffffff816f25d6: amd_iommu_get_resv_regions.cold (STB_LOCAL)
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
