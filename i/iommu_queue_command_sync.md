# Function: <code>iommu_queue_command_sync</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int iommu_queue_command_sync(struct amd_iommu *iommu, struct iommu_cmd *cmd, bool sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8152d980)
Location: drivers/iommu/amd_iommu.c:847
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:iommu_flush_dte
  - drivers/iommu/amd_iommu.c:iommu_flush_irt
  - drivers/iommu/amd_iommu.c:amd_iommu_complete_ppr
  - drivers/iommu/amd_iommu.c:iommu_completion_wait
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
**Symbols:**

```
ffffffff8152d980-ffffffff8152dab3: iommu_queue_command_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int iommu_queue_command_sync(struct amd_iommu *iommu, struct iommu_cmd *cmd, bool sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815814e0)
Location: drivers/iommu/amd_iommu.c:943
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_complete_ppr
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:__flush_pasid
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
  - drivers/iommu/amd_iommu.c:__domain_flush_pages
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_irt
  - drivers/iommu/amd_iommu.c:iommu_flush_dte
  - drivers/iommu/amd_iommu.c:iommu_completion_wait
```
**Symbols:**

```
ffffffff815814e0-ffffffff81581613: iommu_queue_command_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815af1c0)
Location: drivers/iommu/amd_iommu.c:1049
Inline: True
Direct callers:
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
**Symbols:**

```
ffffffff815af1c0-ffffffff815af20f: iommu_queue_command_sync.constprop.34 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815c4f80)
Location: drivers/iommu/amd_iommu.c:1108
Inline: True
Direct callers:
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
**Symbols:**

```
ffffffff815c4f80-ffffffff815c4fcf: iommu_queue_command_sync.constprop.43 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8162bcd0)
Location: drivers/iommu/amd_iommu.c:1049
Inline: True
Direct callers:
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
**Symbols:**

```
ffffffff8162bcd0-ffffffff8162bd1f: iommu_queue_command_sync.constprop.40 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81666a70)
Location: drivers/iommu/amd_iommu.c:1055
Inline: True
Direct callers:
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
**Symbols:**

```
ffffffff81666a70-ffffffff81666abf: iommu_queue_command_sync.constprop.43 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816850f0)
Location: drivers/iommu/amd_iommu.c:1070
Inline: True
Direct callers:
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
**Symbols:**

```
ffffffff816850f0-ffffffff8168513f: iommu_queue_command_sync.constprop.43 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816bc600)
Location: drivers/iommu/amd_iommu.c:1058
Inline: True
Direct callers:
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
**Symbols:**

```
ffffffff816bc600-ffffffff816bc651: iommu_queue_command_sync.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816df560)
Location: drivers/iommu/amd_iommu.c:1065
Inline: True
Direct callers:
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
**Symbols:**

```
ffffffff816df560-ffffffff816df5b1: iommu_queue_command_sync.constprop.0 (STB_LOCAL)
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
Location: drivers/iommu/amd/iommu.c:1009
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
Location: drivers/iommu/amd/iommu.c:1100
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
Location: drivers/iommu/amd/iommu.c:1032
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
Location: drivers/iommu/amd/iommu.c:1044
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
Location: drivers/iommu/amd/iommu.c:1066
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
Location: drivers/iommu/amd/iommu.c:1135
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
Location: drivers/iommu/amd/iommu.c:1152
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
Location: drivers/iommu/amd/iommu.c:1241
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816a4fb0)
Location: drivers/iommu/amd_iommu.c:1065
Inline: True
Direct callers:
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
**Symbols:**

```
ffffffff816a4fb0-ffffffff816a5001: iommu_queue_command_sync.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816829a0)
Location: drivers/iommu/amd_iommu.c:1065
Inline: True
Direct callers:
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
**Symbols:**

```
ffffffff816829a0-ffffffff816829f1: iommu_queue_command_sync.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816d3220)
Location: drivers/iommu/amd_iommu.c:1065
Inline: True
Direct callers:
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
**Symbols:**

```
ffffffff816d3220-ffffffff816d3271: iommu_queue_command_sync.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816ed920)
Location: drivers/iommu/amd_iommu.c:1065
Inline: True
Direct callers:
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
**Symbols:**

```
ffffffff816ed920-ffffffff816ed971: iommu_queue_command_sync.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
</ul>
