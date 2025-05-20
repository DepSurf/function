# Function: <code>iommu_queue_command</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8152dac9)
Location: drivers/iommu/amd_iommu.c:888
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_flush_dte
  - drivers/iommu/amd_iommu.c:iommu_flush_irt
  - drivers/iommu/amd_iommu.c:amd_iommu_complete_ppr
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8158174c)
Location: drivers/iommu/amd_iommu.c:984
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_complete_ppr
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_irt
  - drivers/iommu/amd_iommu.c:iommu_flush_dte
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815af66c)
Location: drivers/iommu/amd_iommu.c:1063
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_complete_ppr
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_irt
  - drivers/iommu/amd_iommu.c:iommu_flush_dte
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815c6329)
Location: drivers/iommu/amd_iommu.c:1122
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd_iommu.c:free_irte
  - drivers/iommu/amd_iommu.c:modify_irte
  - drivers/iommu/amd_iommu.c:modify_irte_ga
  - drivers/iommu/amd_iommu.c:amd_iommu_complete_ppr
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8162cdf9)
Location: drivers/iommu/amd_iommu.c:1063
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd_iommu.c:free_irte
  - drivers/iommu/amd_iommu.c:modify_irte
  - drivers/iommu/amd_iommu.c:modify_irte_ga
  - drivers/iommu/amd_iommu.c:amd_iommu_complete_ppr
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81666b76)
Location: drivers/iommu/amd_iommu.c:1069
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd_iommu.c:free_irte
  - drivers/iommu/amd_iommu.c:modify_irte
  - drivers/iommu/amd_iommu.c:modify_irte_ga
  - drivers/iommu/amd_iommu.c:set_remap_table_entry
  - drivers/iommu/amd_iommu.c:amd_iommu_complete_ppr
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816851f6)
Location: drivers/iommu/amd_iommu.c:1084
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd_iommu.c:free_irte
  - drivers/iommu/amd_iommu.c:modify_irte
  - drivers/iommu/amd_iommu.c:modify_irte_ga
  - drivers/iommu/amd_iommu.c:set_remap_table_entry
  - drivers/iommu/amd_iommu.c:amd_iommu_complete_ppr
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816bc71b)
Location: drivers/iommu/amd_iommu.c:1072
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd_iommu.c:free_irte
  - drivers/iommu/amd_iommu.c:modify_irte
  - drivers/iommu/amd_iommu.c:modify_irte_ga
  - drivers/iommu/amd_iommu.c:set_remap_table_entry
  - drivers/iommu/amd_iommu.c:amd_iommu_complete_ppr
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816df67b)
Location: drivers/iommu/amd_iommu.c:1079
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd_iommu.c:free_irte
  - drivers/iommu/amd_iommu.c:modify_irte
  - drivers/iommu/amd_iommu.c:modify_irte_ga
  - drivers/iommu/amd_iommu.c:amd_iommu_complete_ppr
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
  - drivers/iommu/amd_iommu.c:device_flush_dte
  - drivers/iommu/amd_iommu.c:device_flush_dte
  - drivers/iommu/amd_iommu.c:device_flush_dte
  - drivers/iommu/amd_iommu.c:device_flush_dte_alias
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81799711)
Location: drivers/iommu/amd/iommu.c:1023
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd/iommu.c:free_irte
  - drivers/iommu/amd/iommu.c:modify_irte_ga
  - drivers/iommu/amd/iommu.c:set_remap_table_entry_alias
  - drivers/iommu/amd/iommu.c:set_remap_table_entry
  - drivers/iommu/amd/iommu.c:amd_iommu_complete_ppr
  - drivers/iommu/amd/iommu.c:__flush_pasid
  - drivers/iommu/amd/iommu.c:__flush_pasid
  - drivers/iommu/amd/iommu.c:set_dte_entry
  - drivers/iommu/amd/iommu.c:__domain_flush_pages
  - drivers/iommu/amd/iommu.c:device_flush_dte_alias
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817a71f1)
Location: drivers/iommu/amd/iommu.c:1114
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd/iommu.c:free_irte
  - drivers/iommu/amd/iommu.c:modify_irte_ga
  - drivers/iommu/amd/iommu.c:set_remap_table_entry_alias
  - drivers/iommu/amd/iommu.c:set_remap_table_entry
  - drivers/iommu/amd/iommu.c:amd_iommu_complete_ppr
  - drivers/iommu/amd/iommu.c:__flush_pasid
  - drivers/iommu/amd/iommu.c:__flush_pasid
  - drivers/iommu/amd/iommu.c:set_dte_entry
  - drivers/iommu/amd/iommu.c:__domain_flush_pages
  - drivers/iommu/amd/iommu.c:device_flush_dte_alias
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817882ae)
Location: drivers/iommu/amd/iommu.c:1046
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd/iommu.c:free_irte
  - drivers/iommu/amd/iommu.c:modify_irte_ga
  - drivers/iommu/amd/iommu.c:set_remap_table_entry_alias
  - drivers/iommu/amd/iommu.c:set_remap_table_entry
  - drivers/iommu/amd/iommu.c:amd_iommu_complete_ppr
  - drivers/iommu/amd/iommu.c:__flush_pasid
  - drivers/iommu/amd/iommu.c:__flush_pasid
  - drivers/iommu/amd/iommu.c:set_dte_entry
  - drivers/iommu/amd/iommu.c:__domain_flush_pages
  - drivers/iommu/amd/iommu.c:device_flush_dte_alias
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff8180fb92)
Location: drivers/iommu/amd/iommu.c:1058
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd/iommu.c:free_irte
  - drivers/iommu/amd/iommu.c:modify_irte_ga
  - drivers/iommu/amd/iommu.c:set_remap_table_entry_alias
  - drivers/iommu/amd/iommu.c:set_remap_table_entry
  - drivers/iommu/amd/iommu.c:amd_iommu_complete_ppr
  - drivers/iommu/amd/iommu.c:__flush_pasid
  - drivers/iommu/amd/iommu.c:__flush_pasid
  - drivers/iommu/amd/iommu.c:set_dte_entry
  - drivers/iommu/amd/iommu.c:device_flush_dte_alias
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81951159)
Location: drivers/iommu/amd/iommu.c:1080
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd/iommu.c:free_irte
  - drivers/iommu/amd/iommu.c:modify_irte_ga
  - drivers/iommu/amd/iommu.c:set_remap_table_entry_alias
  - drivers/iommu/amd/iommu.c:set_remap_table_entry
  - drivers/iommu/amd/iommu.c:amd_iommu_complete_ppr
  - drivers/iommu/amd/iommu.c:__flush_pasid
  - drivers/iommu/amd/iommu.c:__flush_pasid
  - drivers/iommu/amd/iommu.c:set_dte_entry
  - drivers/iommu/amd/iommu.c:device_flush_dte_alias
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81ab62c5)
Location: drivers/iommu/amd/iommu.c:1149
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd/iommu.c:free_irte
  - drivers/iommu/amd/iommu.c:modify_irte_ga
  - drivers/iommu/amd/iommu.c:set_remap_table_entry_alias
  - drivers/iommu/amd/iommu.c:set_remap_table_entry
  - drivers/iommu/amd/iommu.c:amd_iommu_complete_ppr
  - drivers/iommu/amd/iommu.c:__flush_pasid
  - drivers/iommu/amd/iommu.c:__flush_pasid
  - drivers/iommu/amd/iommu.c:set_dte_entry
  - drivers/iommu/amd/iommu.c:device_flush_dte_alias
  - drivers/iommu/amd/iommu.c:device_flush_iotlb
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81b00ea2)
Location: drivers/iommu/amd/iommu.c:1166
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_complete_ppr
  - drivers/iommu/amd/iommu.c:__flush_pasid
  - drivers/iommu/amd/iommu.c:__flush_pasid
  - drivers/iommu/amd/iommu.c:set_dte_entry
  - drivers/iommu/amd/iommu.c:device_flush_iotlb
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd/iommu.c:iommu_flush_dte
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81b57d26)
Location: drivers/iommu/amd/iommu.c:1255
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_complete_ppr
  - drivers/iommu/amd/iommu.c:__flush_pasid
  - drivers/iommu/amd/iommu.c:__flush_pasid
  - drivers/iommu/amd/iommu.c:set_dte_entry
  - drivers/iommu/amd/iommu.c:__domain_flush_pages
  - drivers/iommu/amd/iommu.c:__domain_flush_pages
  - drivers/iommu/amd/iommu.c:amd_iommu_flush_all_caches
  - drivers/iommu/amd/iommu.c:amd_iommu_flush_all_caches
  - drivers/iommu/amd/iommu.c:amd_iommu_flush_all_caches
  - drivers/iommu/amd/iommu.c:iommu_flush_dte
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816a50cb)
Location: drivers/iommu/amd_iommu.c:1079
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd_iommu.c:free_irte
  - drivers/iommu/amd_iommu.c:modify_irte
  - drivers/iommu/amd_iommu.c:modify_irte_ga
  - drivers/iommu/amd_iommu.c:amd_iommu_complete_ppr
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
  - drivers/iommu/amd_iommu.c:device_flush_dte
  - drivers/iommu/amd_iommu.c:device_flush_dte
  - drivers/iommu/amd_iommu.c:device_flush_dte
  - drivers/iommu/amd_iommu.c:device_flush_dte_alias
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81682abb)
Location: drivers/iommu/amd_iommu.c:1079
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd_iommu.c:free_irte
  - drivers/iommu/amd_iommu.c:modify_irte
  - drivers/iommu/amd_iommu.c:modify_irte_ga
  - drivers/iommu/amd_iommu.c:amd_iommu_complete_ppr
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
  - drivers/iommu/amd_iommu.c:device_flush_dte
  - drivers/iommu/amd_iommu.c:device_flush_dte
  - drivers/iommu/amd_iommu.c:device_flush_dte
  - drivers/iommu/amd_iommu.c:device_flush_dte_alias
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816d333b)
Location: drivers/iommu/amd_iommu.c:1079
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd_iommu.c:free_irte
  - drivers/iommu/amd_iommu.c:modify_irte
  - drivers/iommu/amd_iommu.c:modify_irte_ga
  - drivers/iommu/amd_iommu.c:amd_iommu_complete_ppr
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
  - drivers/iommu/amd_iommu.c:device_flush_dte
  - drivers/iommu/amd_iommu.c:device_flush_dte
  - drivers/iommu/amd_iommu.c:device_flush_dte
  - drivers/iommu/amd_iommu.c:device_flush_dte_alias
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816eda3b)
Location: drivers/iommu/amd_iommu.c:1079
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd_iommu.c:free_irte
  - drivers/iommu/amd_iommu.c:modify_irte
  - drivers/iommu/amd_iommu.c:modify_irte_ga
  - drivers/iommu/amd_iommu.c:amd_iommu_complete_ppr
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
  - drivers/iommu/amd_iommu.c:device_flush_dte
  - drivers/iommu/amd_iommu.c:device_flush_dte
  - drivers/iommu/amd_iommu.c:device_flush_dte
  - drivers/iommu/amd_iommu.c:device_flush_dte_alias
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
</details>
</li>
</ul>

## Differences
