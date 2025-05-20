# Function: <code>amd_iommu_get_num_iommus</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int amd_iommu_get_num_iommus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff815ca670)
Location: drivers/iommu/amd_iommu_init.c:275
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:domain_flush_complete
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
```
**Symbols:**

```
ffffffff815ca670-ffffffff815ca681: amd_iommu_get_num_iommus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int amd_iommu_get_num_iommus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816311a0)
Location: drivers/iommu/amd_iommu_init.c:304
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:domain_flush_complete
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
```
**Symbols:**

```
ffffffff816311a0-ffffffff816311b1: amd_iommu_get_num_iommus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int amd_iommu_get_num_iommus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff8166c060)
Location: drivers/iommu/amd_iommu_init.c:304
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:domain_flush_complete
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
```
**Symbols:**

```
ffffffff8166c060-ffffffff8166c071: amd_iommu_get_num_iommus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int amd_iommu_get_num_iommus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff8168a880)
Location: drivers/iommu/amd_iommu_init.c:307
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:domain_flush_complete
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
```
**Symbols:**

```
ffffffff8168a880-ffffffff8168a891: amd_iommu_get_num_iommus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int amd_iommu_get_num_iommus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816c22b0)
Location: drivers/iommu/amd_iommu_init.c:292
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:domain_flush_complete
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
```
**Symbols:**

```
ffffffff816c22b0-ffffffff816c22c1: amd_iommu_get_num_iommus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int amd_iommu_get_num_iommus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816e51d0)
Location: drivers/iommu/amd_iommu_init.c:293
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:domain_flush_complete
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
```
**Symbols:**

```
ffffffff816e51d0-ffffffff816e51e1: amd_iommu_get_num_iommus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int amd_iommu_get_num_iommus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff8179b640)
Location: drivers/iommu/amd/init.c:293
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
  - drivers/iommu/amd/iommu.c:__flush_pasid
  - drivers/iommu/amd/iommu.c:domain_flush_complete
  - drivers/iommu/amd/iommu.c:__domain_flush_pages
```
**Symbols:**

```
ffffffff8179b640-ffffffff8179b651: amd_iommu_get_num_iommus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int amd_iommu_get_num_iommus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff817a9a80)
Location: drivers/iommu/amd/init.c:299
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
  - drivers/iommu/amd/iommu.c:__flush_pasid
  - drivers/iommu/amd/iommu.c:domain_flush_complete
  - drivers/iommu/amd/iommu.c:__domain_flush_pages
```
**Symbols:**

```
ffffffff817a9a80-ffffffff817a9a91: amd_iommu_get_num_iommus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int amd_iommu_get_num_iommus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff8178b7a0)
Location: drivers/iommu/amd/init.c:295
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
  - drivers/iommu/amd/iommu.c:__flush_pasid
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_flush_complete
  - drivers/iommu/amd/iommu.c:__domain_flush_pages
```
**Symbols:**

```
ffffffff8178b7a0-ffffffff8178b7b1: amd_iommu_get_num_iommus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int amd_iommu_get_num_iommus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81813000)
Location: drivers/iommu/amd/init.c:296
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
  - drivers/iommu/amd/iommu.c:__flush_pasid
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_flush_complete
```
**Symbols:**

```
ffffffff81813000-ffffffff81813011: amd_iommu_get_num_iommus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int amd_iommu_get_num_iommus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81953fb0)
Location: drivers/iommu/amd/init.c:298
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
  - drivers/iommu/amd/iommu.c:__flush_pasid
  - drivers/iommu/amd/iommu.c:__flush_pasid
  - drivers/iommu/amd/iommu.c:__flush_pasid
  - drivers/iommu/amd/iommu.c:amd_iommu_iotlb_sync
  - drivers/iommu/amd/iommu.c:amd_iommu_flush_iotlb_all
  - drivers/iommu/amd/iommu.c:amd_iommu_iotlb_sync_map
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_update
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:do_detach
```
**Symbols:**

```
ffffffff81953fb0-ffffffff81953fc5: amd_iommu_get_num_iommus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int amd_iommu_get_num_iommus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81ab9c00)
Location: drivers/iommu/amd/init.c:263
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
  - drivers/iommu/amd/iommu.c:__flush_pasid
  - drivers/iommu/amd/iommu.c:__flush_pasid
  - drivers/iommu/amd/iommu.c:__flush_pasid
  - drivers/iommu/amd/iommu.c:amd_iommu_iotlb_sync
  - drivers/iommu/amd/iommu.c:amd_iommu_flush_iotlb_all
  - drivers/iommu/amd/iommu.c:amd_iommu_iotlb_sync_map
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_update
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:do_detach
```
**Symbols:**

```
ffffffff81ab9c00-ffffffff81ab9c15: amd_iommu_get_num_iommus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int amd_iommu_get_num_iommus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81b060b0)
Location: drivers/iommu/amd/init.c:266
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
  - drivers/iommu/amd/iommu.c:__flush_pasid
  - drivers/iommu/amd/iommu.c:__flush_pasid
  - drivers/iommu/amd/iommu.c:__flush_pasid
  - drivers/iommu/amd/iommu.c:__flush_pasid
  - drivers/iommu/amd/iommu.c:__flush_pasid
  - drivers/iommu/amd/iommu.c:amd_iommu_iotlb_sync
  - drivers/iommu/amd/iommu.c:amd_iommu_iotlb_sync
  - drivers/iommu/amd/iommu.c:amd_iommu_flush_iotlb_all
  - drivers/iommu/amd/iommu.c:amd_iommu_flush_iotlb_all
  - drivers/iommu/amd/iommu.c:amd_iommu_iotlb_sync_map
  - drivers/iommu/amd/iommu.c:amd_iommu_iotlb_sync_map
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_update
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_update
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:do_detach
  - drivers/iommu/amd/iommu.c:do_detach
```
**Symbols:**

```
ffffffff81b060b0-ffffffff81b060c5: amd_iommu_get_num_iommus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int amd_iommu_get_num_iommus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81b59e50)
Location: drivers/iommu/amd/init.c:261
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
  - drivers/iommu/amd/iommu.c:__flush_pasid
  - drivers/iommu/amd/iommu.c:__flush_pasid
  - drivers/iommu/amd/iommu.c:__flush_pasid
  - drivers/iommu/amd/iommu.c:__flush_pasid
  - drivers/iommu/amd/iommu.c:__flush_pasid
  - drivers/iommu/amd/iommu.c:__domain_flush_pages
```
**Symbols:**

```
ffffffff81b59e50-ffffffff81b59e65: amd_iommu_get_num_iommus (STB_GLOBAL)
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
int amd_iommu_get_num_iommus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816aacb0)
Location: drivers/iommu/amd_iommu_init.c:293
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:domain_flush_complete
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
```
**Symbols:**

```
ffffffff816aacb0-ffffffff816aacc1: amd_iommu_get_num_iommus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int amd_iommu_get_num_iommus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff81688610)
Location: drivers/iommu/amd_iommu_init.c:293
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:domain_flush_complete
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
```
**Symbols:**

```
ffffffff81688610-ffffffff81688621: amd_iommu_get_num_iommus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int amd_iommu_get_num_iommus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816d8e90)
Location: drivers/iommu/amd_iommu_init.c:293
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:domain_flush_complete
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
```
**Symbols:**

```
ffffffff816d8e90-ffffffff816d8ea1: amd_iommu_get_num_iommus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int amd_iommu_get_num_iommus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816f3440)
Location: drivers/iommu/amd_iommu_init.c:293
Inline: False
Direct callers:
  - arch/x86/events/amd/iommu.c:amd_iommu_pc_init
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:domain_flush_complete
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
```
**Symbols:**

```
ffffffff816f3440-ffffffff816f3451: amd_iommu_get_num_iommus (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
