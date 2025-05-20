# Function: <code>iommu_get_group_resv_regions</code>

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
int iommu_get_group_resv_regions(struct iommu_group *group, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff815ab3b0)
Location: drivers/iommu/iommu.c:218
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_group_show_resv_regions
```
**Symbols:**

```
ffffffff815ab3b0-ffffffff815ab50b: iommu_get_group_resv_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int iommu_get_group_resv_regions(struct iommu_group *group, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff815c0fa0)
Location: drivers/iommu/iommu.c:251
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_group_show_resv_regions
```
**Symbols:**

```
ffffffff815c0fa0-ffffffff815c10e8: iommu_get_group_resv_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int iommu_get_group_resv_regions(struct iommu_group *group, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81627730)
Location: drivers/iommu/iommu.c:251
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_group_show_resv_regions
```
**Symbols:**

```
ffffffff81627730-ffffffff8162788a: iommu_get_group_resv_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int iommu_get_group_resv_regions(struct iommu_group *group, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816621a0)
Location: drivers/iommu/iommu.c:253
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_group_show_resv_regions
```
**Symbols:**

```
ffffffff816621a0-ffffffff816622fa: iommu_get_group_resv_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int iommu_get_group_resv_regions(struct iommu_group *group, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81680d60)
Location: drivers/iommu/iommu.c:287
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_group_show_resv_regions
```
**Symbols:**

```
ffffffff81680d60-ffffffff81680eba: iommu_get_group_resv_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int iommu_get_group_resv_regions(struct iommu_group *group, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816b8580)
Location: drivers/iommu/iommu.c:304
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_group_show_resv_regions
```
**Symbols:**

```
ffffffff816b8580-ffffffff816b86c2: iommu_get_group_resv_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int iommu_get_group_resv_regions(struct iommu_group *group, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816db3a0)
Location: drivers/iommu/iommu.c:359
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_group_show_resv_regions
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
```
**Symbols:**

```
ffffffff816db3a0-ffffffff816db4e2: iommu_get_group_resv_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int iommu_get_group_resv_regions(struct iommu_group *group, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8178f670)
Location: drivers/iommu/iommu.c:453
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_group_show_resv_regions
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_resv_refresh
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
```
**Symbols:**

```
ffffffff8178f670-ffffffff8178f7dc: iommu_get_group_resv_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int iommu_get_group_resv_regions(struct iommu_group *group, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff817ba200)
Location: drivers/iommu/iommu.c:459
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_group_show_resv_regions
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_resv_refresh
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
```
**Symbols:**

```
ffffffff817ba200-ffffffff817ba36c: iommu_get_group_resv_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int iommu_get_group_resv_regions(struct iommu_group *group, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8179da60)
Location: drivers/iommu/iommu.c:485
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_group_show_resv_regions
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
```
**Symbols:**

```
ffffffff8179da60-ffffffff8179dbcc: iommu_get_group_resv_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int iommu_get_group_resv_regions(struct iommu_group *group, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81826a60)
Location: drivers/iommu/iommu.c:497
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_group_show_resv_regions
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
```
**Symbols:**

```
ffffffff81826a60-ffffffff81826bcc: iommu_get_group_resv_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int iommu_get_group_resv_regions(struct iommu_group *group, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81965ff0)
Location: drivers/iommu/iommu.c:504
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_group_show_resv_regions
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
```
**Symbols:**

```
ffffffff81965ff0-ffffffff81966140: iommu_get_group_resv_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int iommu_get_group_resv_regions(struct iommu_group *group, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81acf9d0)
Location: drivers/iommu/iommu.c:631
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_group_show_resv_regions
```
**Symbols:**

```
ffffffff81acf9d0-ffffffff81acfb57: iommu_get_group_resv_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int iommu_get_group_resv_regions(struct iommu_group *group, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b1f230)
Location: drivers/iommu/iommu.c:701
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_group_show_resv_regions
```
**Symbols:**

```
ffffffff81b1f230-ffffffff81b1f3b7: iommu_get_group_resv_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int iommu_get_group_resv_regions(struct iommu_group *group, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff81b75670)
Location: drivers/iommu/iommu.c:831
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_group_show_resv_regions
```
**Symbols:**

```
ffffffff81b75670-ffffffff81b75800: iommu_get_group_resv_regions (STB_GLOBAL)
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
int iommu_get_group_resv_regions(struct iommu_group *group, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffff8000108c7370)
Location: drivers/iommu/iommu.c:359
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_group_show_resv_regions
```
**Symbols:**

```
ffff8000108c7370-ffff8000108c74b0: iommu_get_group_resv_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int iommu_get_group_resv_regions(struct iommu_group *group, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c09be310)
Location: drivers/iommu/iommu.c:359
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_group_show_resv_regions
```
**Symbols:**

```
c09be310-c09be454: iommu_get_group_resv_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int iommu_get_group_resv_regions(struct iommu_group *group, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (c00000000096db10)
Location: drivers/iommu/iommu.c:359
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_group_show_resv_regions
```
**Symbols:**

```
c00000000096db10-c00000000096dcdc: iommu_get_group_resv_regions (STB_GLOBAL)
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
int iommu_get_group_resv_regions(struct iommu_group *group, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816a0df0)
Location: drivers/iommu/iommu.c:359
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_group_show_resv_regions
```
**Symbols:**

```
ffffffff816a0df0-ffffffff816a0f32: iommu_get_group_resv_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int iommu_get_group_resv_regions(struct iommu_group *group, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff8167e7e0)
Location: drivers/iommu/iommu.c:359
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_group_show_resv_regions
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
```
**Symbols:**

```
ffffffff8167e7e0-ffffffff8167e922: iommu_get_group_resv_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int iommu_get_group_resv_regions(struct iommu_group *group, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816cf060)
Location: drivers/iommu/iommu.c:359
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_group_show_resv_regions
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
```
**Symbols:**

```
ffffffff816cf060-ffffffff816cf1a2: iommu_get_group_resv_regions (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int iommu_get_group_resv_regions(struct iommu_group *group, struct list_head *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/iommu.c (ffffffff816e95d0)
Location: drivers/iommu/iommu.c:359
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:iommu_group_show_resv_regions
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_detach_group
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_attach_group
```
**Symbols:**

```
ffffffff816e95d0-ffffffff816e9712: iommu_get_group_resv_regions (STB_GLOBAL)
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
