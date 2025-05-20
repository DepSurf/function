# Function: <code>iommu_insert_resv_region</code>

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
int iommu_insert_resv_region(struct iommu_resv_region *new, struct list_head *regions);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff815ab210)
Location: drivers/iommu/iommu.c:154
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_get_group_resv_regions
  - drivers/iommu/iommu.c:iommu_insert_resv_region
```
**Symbols:**

```
ffffffff815ab210-ffffffff815ab3a4: iommu_insert_resv_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int iommu_insert_resv_region(struct iommu_resv_region *new, struct list_head *regions);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff815c0e20)
Location: drivers/iommu/iommu.c:187
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_get_group_resv_regions
  - drivers/iommu/iommu.c:iommu_insert_resv_region
```
**Symbols:**

```
ffffffff815c0e20-ffffffff815c0f9c: iommu_insert_resv_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int iommu_insert_resv_region(struct iommu_resv_region *new, struct list_head *regions);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816275b0)
Location: drivers/iommu/iommu.c:187
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_get_group_resv_regions
  - drivers/iommu/iommu.c:iommu_insert_resv_region
```
**Symbols:**

```
ffffffff816275b0-ffffffff8162772c: iommu_insert_resv_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int iommu_insert_resv_region(struct iommu_resv_region *new, struct list_head *regions);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81662010)
Location: drivers/iommu/iommu.c:189
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_get_group_resv_regions
  - drivers/iommu/iommu.c:iommu_insert_resv_region
```
**Symbols:**

```
ffffffff81662010-ffffffff8166219a: iommu_insert_resv_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int iommu_insert_resv_region(struct iommu_resv_region *new, struct list_head *regions);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81680c10)
Location: drivers/iommu/iommu.c:223
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_get_group_resv_regions
  - drivers/iommu/iommu.c:iommu_insert_resv_region
```
**Symbols:**

```
ffffffff81680c10-ffffffff81680d59: iommu_insert_resv_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int iommu_insert_resv_region(struct iommu_resv_region *new, struct list_head *regions);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816b8460)
Location: drivers/iommu/iommu.c:238
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_get_group_resv_regions
  - drivers/iommu/iommu.c:iommu_insert_resv_region
```
**Symbols:**

```
ffffffff816b8460-ffffffff816b8571: iommu_insert_resv_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int iommu_insert_resv_region(struct iommu_resv_region *new, struct list_head *regions);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816db1c0)
Location: drivers/iommu/iommu.c:292
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_get_group_resv_regions
```
**Symbols:**

```
ffffffff816db1c0-ffffffff816db39b: iommu_insert_resv_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int iommu_insert_resv_region(struct iommu_resv_region *new, struct list_head *regions);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8178f460)
Location: drivers/iommu/iommu.c:386
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_get_group_resv_regions
```
**Symbols:**

```
ffffffff8178f460-ffffffff8178f66b: iommu_insert_resv_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int iommu_insert_resv_region(struct iommu_resv_region *new, struct list_head *regions);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff817b9ff0)
Location: drivers/iommu/iommu.c:392
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_get_group_resv_regions
```
**Symbols:**

```
ffffffff817b9ff0-ffffffff817ba1fb: iommu_insert_resv_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int iommu_insert_resv_region(struct iommu_resv_region *new, struct list_head *regions);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8179d850)
Location: drivers/iommu/iommu.c:418
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_get_group_resv_regions
```
**Symbols:**

```
ffffffff8179d850-ffffffff8179da59: iommu_insert_resv_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int iommu_insert_resv_region(struct iommu_resv_region *new, struct list_head *regions);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81826850)
Location: drivers/iommu/iommu.c:430
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_get_group_resv_regions
```
**Symbols:**

```
ffffffff81826850-ffffffff81826a59: iommu_insert_resv_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int iommu_insert_resv_region(struct iommu_resv_region *new, struct list_head *regions);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81965df0)
Location: drivers/iommu/iommu.c:437
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_get_group_resv_regions
```
**Symbols:**

```
ffffffff81965df0-ffffffff81965fe7: iommu_insert_resv_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int iommu_insert_resv_region(struct iommu_resv_region *new, struct list_head *regions);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81acf580)
Location: drivers/iommu/iommu.c:564
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_get_group_resv_regions
```
**Symbols:**

```
ffffffff81acf580-ffffffff81acf777: iommu_insert_resv_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int iommu_insert_resv_region(struct iommu_resv_region *new, struct list_head *regions);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b1eb50)
Location: drivers/iommu/iommu.c:634
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_get_group_resv_regions
```
**Symbols:**

```
ffffffff81b1eb50-ffffffff81b1ed47: iommu_insert_resv_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int iommu_insert_resv_region(struct iommu_resv_region *new, struct list_head *regions);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b75160)
Location: drivers/iommu/iommu.c:764
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_get_group_resv_regions
```
**Symbols:**

```
ffffffff81b75160-ffffffff81b75386: iommu_insert_resv_region (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int iommu_insert_resv_region(struct iommu_resv_region *new, struct list_head *regions);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffff8000108c7150)
Location: drivers/iommu/iommu.c:292
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_get_group_resv_regions
```
**Symbols:**

```
ffff8000108c7150-ffff8000108c736c: iommu_insert_resv_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int iommu_insert_resv_region(struct iommu_resv_region *new, struct list_head *regions);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c09be114)
Location: drivers/iommu/iommu.c:292
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_get_group_resv_regions
```
**Symbols:**

```
c09be114-c09be310: iommu_insert_resv_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int iommu_insert_resv_region(struct iommu_resv_region *new, struct list_head *regions);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c00000000096d860)
Location: drivers/iommu/iommu.c:292
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_get_group_resv_regions
```
**Symbols:**

```
c00000000096d860-c00000000096db0c: iommu_insert_resv_region (STB_GLOBAL)
```
</details>
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
int iommu_insert_resv_region(struct iommu_resv_region *new, struct list_head *regions);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816a0c10)
Location: drivers/iommu/iommu.c:292
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_get_group_resv_regions
```
**Symbols:**

```
ffffffff816a0c10-ffffffff816a0deb: iommu_insert_resv_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int iommu_insert_resv_region(struct iommu_resv_region *new, struct list_head *regions);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8167e600)
Location: drivers/iommu/iommu.c:292
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_get_group_resv_regions
```
**Symbols:**

```
ffffffff8167e600-ffffffff8167e7db: iommu_insert_resv_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int iommu_insert_resv_region(struct iommu_resv_region *new, struct list_head *regions);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816cee80)
Location: drivers/iommu/iommu.c:292
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_get_group_resv_regions
```
**Symbols:**

```
ffffffff816cee80-ffffffff816cf05b: iommu_insert_resv_region (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int iommu_insert_resv_region(struct iommu_resv_region *new, struct list_head *regions);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816e93f0)
Location: drivers/iommu/iommu.c:292
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_get_group_resv_regions
```
**Symbols:**

```
ffffffff816e93f0-ffffffff816e95cb: iommu_insert_resv_region (STB_GLOBAL)
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
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
