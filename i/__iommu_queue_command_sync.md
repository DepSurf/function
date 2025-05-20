# Function: <code>__iommu_queue_command_sync</code>

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
int __iommu_queue_command_sync(struct amd_iommu *iommu, struct iommu_cmd *cmd, bool sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815ae340)
Location: drivers/iommu/amd_iommu.c:1013
Inline: False
```
**Symbols:**

```
ffffffff815ae340-ffffffff815ae476: __iommu_queue_command_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __iommu_queue_command_sync(struct amd_iommu *iommu, struct iommu_cmd *cmd, bool sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815c4060)
Location: drivers/iommu/amd_iommu.c:1071
Inline: False
```
**Symbols:**

```
ffffffff815c4060-ffffffff815c4149: __iommu_queue_command_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __iommu_queue_command_sync(struct amd_iommu *iommu, struct iommu_cmd *cmd, bool sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8162adb0)
Location: drivers/iommu/amd_iommu.c:1012
Inline: False
```
**Symbols:**

```
ffffffff8162adb0-ffffffff8162ae99: __iommu_queue_command_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int __iommu_queue_command_sync(struct amd_iommu *iommu, struct iommu_cmd *cmd, bool sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (0)
Location: drivers/iommu/amd_iommu.c:1018
Inline: False
```
**Symbols:**

```
ffffffff816659d0-ffffffff81665a97: __iommu_queue_command_sync (STB_LOCAL)
ffffffff8166b4fb-ffffffff8166b511: __iommu_queue_command_sync.cold.44 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int __iommu_queue_command_sync(struct amd_iommu *iommu, struct iommu_cmd *cmd, bool sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (0)
Location: drivers/iommu/amd_iommu.c:1033
Inline: False
```
**Symbols:**

```
ffffffff81684440-ffffffff81684507: __iommu_queue_command_sync (STB_LOCAL)
ffffffff81689c0b-ffffffff81689c21: __iommu_queue_command_sync.cold.44 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __iommu_queue_command_sync(struct amd_iommu *iommu, struct iommu_cmd *cmd, bool sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (0)
Location: drivers/iommu/amd_iommu.c:1021
Inline: False
```
**Symbols:**

```
ffffffff816bb9a0-ffffffff816bba66: __iommu_queue_command_sync (STB_LOCAL)
ffffffff816c11eb-ffffffff816c1201: __iommu_queue_command_sync.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int __iommu_queue_command_sync(struct amd_iommu *iommu, struct iommu_cmd *cmd, bool sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (0)
Location: drivers/iommu/amd_iommu.c:1028
Inline: False
```
**Symbols:**

```
ffffffff816de830-ffffffff816de8f6: __iommu_queue_command_sync (STB_LOCAL)
ffffffff816e424b-ffffffff816e4261: __iommu_queue_command_sync.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int __iommu_queue_command_sync(struct amd_iommu *iommu, struct iommu_cmd *cmd, bool sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:972
Inline: False
Direct callers:
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
**Symbols:**

```
ffffffff81794f80-ffffffff81795046: __iommu_queue_command_sync (STB_LOCAL)
ffffffff8179a4fb-ffffffff8179a511: __iommu_queue_command_sync.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int __iommu_queue_command_sync(struct amd_iommu *iommu, struct iommu_cmd *cmd, bool sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:1063
Inline: False
Direct callers:
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
**Symbols:**

```
ffffffff817a3440-ffffffff817a3506: __iommu_queue_command_sync (STB_LOCAL)
ffffffff81c0b367-ffffffff81c0b37d: __iommu_queue_command_sync.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __iommu_queue_command_sync(struct amd_iommu *iommu, struct iommu_cmd *cmd, bool sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:995
Inline: False
Direct callers:
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
**Symbols:**

```
ffffffff81786150-ffffffff81786218: __iommu_queue_command_sync (STB_LOCAL)
ffffffff81bfcdea-ffffffff81bfce00: __iommu_queue_command_sync.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __iommu_queue_command_sync(struct amd_iommu *iommu, struct iommu_cmd *cmd, bool sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:1007
Inline: False
Direct callers:
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
**Symbols:**

```
ffffffff8180cfc0-ffffffff8180d088: __iommu_queue_command_sync (STB_LOCAL)
ffffffff81cfdba8-ffffffff81cfdbbe: __iommu_queue_command_sync.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __iommu_queue_command_sync(struct amd_iommu *iommu, struct iommu_cmd *cmd, bool sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:1029
Inline: False
Direct callers:
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
**Symbols:**

```
ffffffff8194d6b0-ffffffff8194d773: __iommu_queue_command_sync (STB_LOCAL)
ffffffff81ec64ae-ffffffff81ec64c4: __iommu_queue_command_sync.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __iommu_queue_command_sync(struct amd_iommu *iommu, struct iommu_cmd *cmd, bool sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81ab24c0)
Location: drivers/iommu/amd/iommu.c:1098
Inline: False
Direct callers:
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
**Symbols:**

```
ffffffff81ab24c0-ffffffff81ab2585: __iommu_queue_command_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __iommu_queue_command_sync(struct amd_iommu *iommu, struct iommu_cmd *cmd, bool sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81afe570)
Location: drivers/iommu/amd/iommu.c:1115
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:iommu_flush_irt_and_complete
  - drivers/iommu/amd/iommu.c:iommu_flush_irt_and_complete
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
**Symbols:**

```
ffffffff81afe570-ffffffff81afe635: __iommu_queue_command_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __iommu_queue_command_sync(struct amd_iommu *iommu, struct iommu_cmd *cmd, bool sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81b51cc0)
Location: drivers/iommu/amd/iommu.c:1204
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:iommu_flush_irt_and_complete
  - drivers/iommu/amd/iommu.c:iommu_flush_irt_and_complete
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
**Symbols:**

```
ffffffff81b51cc0-ffffffff81b51d85: __iommu_queue_command_sync (STB_LOCAL)
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
int __iommu_queue_command_sync(struct amd_iommu *iommu, struct iommu_cmd *cmd, bool sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (0)
Location: drivers/iommu/amd_iommu.c:1028
Inline: False
```
**Symbols:**

```
ffffffff816a4280-ffffffff816a4346: __iommu_queue_command_sync (STB_LOCAL)
ffffffff816a9d2b-ffffffff816a9d41: __iommu_queue_command_sync.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int __iommu_queue_command_sync(struct amd_iommu *iommu, struct iommu_cmd *cmd, bool sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (0)
Location: drivers/iommu/amd_iommu.c:1028
Inline: False
```
**Symbols:**

```
ffffffff81681c70-ffffffff81681d36: __iommu_queue_command_sync (STB_LOCAL)
ffffffff8168768b-ffffffff816876a1: __iommu_queue_command_sync.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int __iommu_queue_command_sync(struct amd_iommu *iommu, struct iommu_cmd *cmd, bool sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (0)
Location: drivers/iommu/amd_iommu.c:1028
Inline: False
```
**Symbols:**

```
ffffffff816d24f0-ffffffff816d25b6: __iommu_queue_command_sync (STB_LOCAL)
ffffffff816d7f0b-ffffffff816d7f21: __iommu_queue_command_sync.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int __iommu_queue_command_sync(struct amd_iommu *iommu, struct iommu_cmd *cmd, bool sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd_iommu.c (0)
Location: drivers/iommu/amd_iommu.c:1028
Inline: False
```
**Symbols:**

```
ffffffff816ecb30-ffffffff816ecbf6: __iommu_queue_command_sync (STB_LOCAL)
ffffffff816f24bb-ffffffff816f24d1: __iommu_queue_command_sync.cold (STB_LOCAL)
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
