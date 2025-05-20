# Function: <code>iommu_completion_wait</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int iommu_completion_wait(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8152dc30)
Location: drivers/iommu/amd_iommu.c:897
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:domain_flush_complete
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/amd_iommu.c:modify_irte
  - drivers/iommu/amd_iommu.c:free_irte
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
**Symbols:**

```
ffffffff8152dc30-ffffffff8152dcb0: iommu_completion_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int iommu_completion_wait(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81581780)
Location: drivers/iommu/amd_iommu.c:993
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:free_irte
  - drivers/iommu/amd_iommu.c:modify_irte
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:__queue_flush
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
**Symbols:**

```
ffffffff81581780-ffffffff81581800: iommu_completion_wait (STB_LOCAL)
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
In drivers/iommu/amd_iommu.c (ffffffff815b008c)
Location: drivers/iommu/amd_iommu.c:1072
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd_iommu.c:free_irte
  - drivers/iommu/amd_iommu.c:modify_irte
  - drivers/iommu/amd_iommu.c:modify_irte_ga
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:domain_flush_complete
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd_iommu.c:free_irte
  - drivers/iommu/amd_iommu.c:modify_irte
  - drivers/iommu/amd_iommu.c:modify_irte_ga
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:domain_flush_complete
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
**Symbols:**

```
ffffffff815aee20-ffffffff815aeec5: iommu_completion_wait.part.14 (STB_LOCAL)
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
In drivers/iommu/amd_iommu.c (ffffffff815c6335)
Location: drivers/iommu/amd_iommu.c:1131
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd_iommu.c:free_irte
  - drivers/iommu/amd_iommu.c:modify_irte
  - drivers/iommu/amd_iommu.c:modify_irte_ga
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:domain_flush_complete
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd_iommu.c:free_irte
  - drivers/iommu/amd_iommu.c:modify_irte
  - drivers/iommu/amd_iommu.c:modify_irte_ga
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:domain_flush_complete
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
**Symbols:**

```
ffffffff815c4ac0-ffffffff815c4c14: iommu_completion_wait.part.22 (STB_LOCAL)
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
In drivers/iommu/amd_iommu.c (ffffffff8162ce05)
Location: drivers/iommu/amd_iommu.c:1072
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd_iommu.c:free_irte
  - drivers/iommu/amd_iommu.c:modify_irte
  - drivers/iommu/amd_iommu.c:modify_irte_ga
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:domain_flush_complete
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd_iommu.c:free_irte
  - drivers/iommu/amd_iommu.c:modify_irte
  - drivers/iommu/amd_iommu.c:modify_irte_ga
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:domain_flush_complete
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
**Symbols:**

```
ffffffff8162b920-ffffffff8162ba7c: iommu_completion_wait.part.20 (STB_LOCAL)
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
In drivers/iommu/amd_iommu.c (ffffffff81666b83)
Location: drivers/iommu/amd_iommu.c:1078
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd_iommu.c:free_irte
  - drivers/iommu/amd_iommu.c:modify_irte
  - drivers/iommu/amd_iommu.c:modify_irte_ga
  - drivers/iommu/amd_iommu.c:alloc_irq_table
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:domain_flush_complete
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd_iommu.c:free_irte
  - drivers/iommu/amd_iommu.c:modify_irte
  - drivers/iommu/amd_iommu.c:modify_irte_ga
  - drivers/iommu/amd_iommu.c:alloc_irq_table
  - drivers/iommu/amd_iommu.c:alloc_irq_table
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:domain_flush_complete
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
**Symbols:**

```
ffffffff81666590-ffffffff816666dc: iommu_completion_wait.part.23 (STB_LOCAL)
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
In drivers/iommu/amd_iommu.c (ffffffff81685203)
Location: drivers/iommu/amd_iommu.c:1093
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd_iommu.c:free_irte
  - drivers/iommu/amd_iommu.c:modify_irte
  - drivers/iommu/amd_iommu.c:modify_irte_ga
  - drivers/iommu/amd_iommu.c:alloc_irq_table
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:domain_flush_complete
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd_iommu.c:free_irte
  - drivers/iommu/amd_iommu.c:modify_irte
  - drivers/iommu/amd_iommu.c:modify_irte_ga
  - drivers/iommu/amd_iommu.c:alloc_irq_table
  - drivers/iommu/amd_iommu.c:alloc_irq_table
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:domain_flush_complete
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
**Symbols:**

```
ffffffff81684e60-ffffffff81684fac: iommu_completion_wait.part.24 (STB_LOCAL)
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
In drivers/iommu/amd_iommu.c (ffffffff816bc728)
Location: drivers/iommu/amd_iommu.c:1081
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd_iommu.c:free_irte
  - drivers/iommu/amd_iommu.c:modify_irte
  - drivers/iommu/amd_iommu.c:modify_irte_ga
  - drivers/iommu/amd_iommu.c:alloc_irq_table
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:domain_flush_complete
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd_iommu.c:free_irte
  - drivers/iommu/amd_iommu.c:modify_irte
  - drivers/iommu/amd_iommu.c:modify_irte_ga
  - drivers/iommu/amd_iommu.c:alloc_irq_table
  - drivers/iommu/amd_iommu.c:alloc_irq_table
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:domain_flush_complete
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
**Symbols:**

```
ffffffff816bc370-ffffffff816bc4b5: iommu_completion_wait.part.0 (STB_LOCAL)
ffffffff816c1201-ffffffff816c1214: iommu_completion_wait.part.0.cold (STB_LOCAL)
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
In drivers/iommu/amd_iommu.c (ffffffff816df688)
Location: drivers/iommu/amd_iommu.c:1088
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd_iommu.c:free_irte
  - drivers/iommu/amd_iommu.c:modify_irte
  - drivers/iommu/amd_iommu.c:modify_irte_ga
  - drivers/iommu/amd_iommu.c:alloc_irq_table
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:domain_flush_complete
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd_iommu.c:free_irte
  - drivers/iommu/amd_iommu.c:modify_irte
  - drivers/iommu/amd_iommu.c:modify_irte_ga
  - drivers/iommu/amd_iommu.c:alloc_irq_table
  - drivers/iommu/amd_iommu.c:alloc_irq_table
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:domain_flush_complete
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
**Symbols:**

```
ffffffff816df2d0-ffffffff816df41c: iommu_completion_wait.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81799735)
Location: drivers/iommu/amd/iommu.c:1032
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd/iommu.c:free_irte
  - drivers/iommu/amd/iommu.c:modify_irte_ga
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd/iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd/iommu.c:amd_iommu_release_device
  - drivers/iommu/amd/iommu.c:set_dte_entry
  - drivers/iommu/amd/iommu.c:domain_flush_complete
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd/iommu.c:free_irte
  - drivers/iommu/amd/iommu.c:modify_irte_ga
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd/iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd/iommu.c:amd_iommu_release_device
  - drivers/iommu/amd/iommu.c:set_dte_entry
  - drivers/iommu/amd/iommu.c:domain_flush_complete
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
```
**Symbols:**

```
ffffffff81795950-ffffffff81795a84: iommu_completion_wait.part.0.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817a7215)
Location: drivers/iommu/amd/iommu.c:1123
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd/iommu.c:free_irte
  - drivers/iommu/amd/iommu.c:modify_irte_ga
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd/iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd/iommu.c:amd_iommu_release_device
  - drivers/iommu/amd/iommu.c:set_dte_entry
  - drivers/iommu/amd/iommu.c:domain_flush_complete
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd/iommu.c:free_irte
  - drivers/iommu/amd/iommu.c:modify_irte_ga
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd/iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd/iommu.c:amd_iommu_release_device
  - drivers/iommu/amd/iommu.c:set_dte_entry
  - drivers/iommu/amd/iommu.c:domain_flush_complete
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
```
**Symbols:**

```
ffffffff817a3ed0-ffffffff817a3ffb: iommu_completion_wait.part.0.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817882d3)
Location: drivers/iommu/amd/iommu.c:1055
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd/iommu.c:free_irte
  - drivers/iommu/amd/iommu.c:modify_irte_ga
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd/iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd/iommu.c:amd_iommu_release_device
  - drivers/iommu/amd/iommu.c:set_dte_entry
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_flush_complete
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd/iommu.c:free_irte
  - drivers/iommu/amd/iommu.c:modify_irte_ga
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd/iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd/iommu.c:amd_iommu_release_device
  - drivers/iommu/amd/iommu.c:set_dte_entry
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_flush_complete
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
```
**Symbols:**

```
ffffffff81786760-ffffffff81786893: iommu_completion_wait.part.0.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff8180fbb7)
Location: drivers/iommu/amd/iommu.c:1067
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd/iommu.c:free_irte
  - drivers/iommu/amd/iommu.c:modify_irte_ga
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd/iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd/iommu.c:amd_iommu_release_device
  - drivers/iommu/amd/iommu.c:set_dte_entry
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_flush_complete
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd/iommu.c:free_irte
  - drivers/iommu/amd/iommu.c:modify_irte_ga
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd/iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd/iommu.c:amd_iommu_release_device
  - drivers/iommu/amd/iommu.c:set_dte_entry
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_flush_complete
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
```
**Symbols:**

```
ffffffff8180d830-ffffffff8180d963: iommu_completion_wait.part.0.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:1089
Inline: True
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd/iommu.c:free_irte
  - drivers/iommu/amd/iommu.c:modify_irte_ga
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:__flush_pasid
  - drivers/iommu/amd/iommu.c:__flush_pasid
  - drivers/iommu/amd/iommu.c:amd_iommu_iotlb_sync
  - drivers/iommu/amd/iommu.c:amd_iommu_flush_iotlb_all
  - drivers/iommu/amd/iommu.c:amd_iommu_iotlb_sync_map
  - drivers/iommu/amd/iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd/iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_update
  - drivers/iommu/amd/iommu.c:amd_iommu_release_device
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:do_detach
  - drivers/iommu/amd/iommu.c:set_dte_entry
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
```
**Symbols:**

```
ffffffff8194e170-ffffffff8194e2de: iommu_completion_wait.isra.0 (STB_LOCAL)
ffffffff81ec65e9-ffffffff81ec65fd: iommu_completion_wait.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:1158
Inline: True
Direct callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd/iommu.c:free_irte
  - drivers/iommu/amd/iommu.c:modify_irte_ga
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:__flush_pasid
  - drivers/iommu/amd/iommu.c:__flush_pasid
  - drivers/iommu/amd/iommu.c:amd_iommu_iotlb_sync
  - drivers/iommu/amd/iommu.c:amd_iommu_flush_iotlb_all
  - drivers/iommu/amd/iommu.c:amd_iommu_iotlb_sync_map
  - drivers/iommu/amd/iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd/iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_update
  - drivers/iommu/amd/iommu.c:amd_iommu_probe_device
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:do_detach
  - drivers/iommu/amd/iommu.c:set_dte_entry
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
```
**Symbols:**

```
ffffffff81ab2930-ffffffff81ab2a96: iommu_completion_wait.isra.0 (STB_LOCAL)
ffffffff82096d58-ffffffff82096d6c: iommu_completion_wait.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:1175
Inline: True
Direct callers:
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:__flush_pasid
  - drivers/iommu/amd/iommu.c:__flush_pasid
  - drivers/iommu/amd/iommu.c:amd_iommu_iotlb_sync
  - drivers/iommu/amd/iommu.c:amd_iommu_flush_iotlb_all
  - drivers/iommu/amd/iommu.c:amd_iommu_iotlb_sync_map
  - drivers/iommu/amd/iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd/iommu.c:amd_iommu_domain_update
  - drivers/iommu/amd/iommu.c:amd_iommu_probe_device
  - drivers/iommu/amd/iommu.c:attach_device
  - drivers/iommu/amd/iommu.c:do_detach
  - drivers/iommu/amd/iommu.c:set_dte_entry
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
```
**Symbols:**

```
ffffffff81afff40-ffffffff81b00069: iommu_completion_wait.isra.0 (STB_LOCAL)
ffffffff82117c8b-ffffffff82117c9f: iommu_completion_wait.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/iommu/amd/iommu.c (0)
Location: drivers/iommu/amd/iommu.c:1264
Inline: True
Direct callers:
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:__flush_pasid
  - drivers/iommu/amd/iommu.c:__flush_pasid
  - drivers/iommu/amd/iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd/iommu.c:amd_iommu_probe_device
  - drivers/iommu/amd/iommu.c:set_dte_entry
  - drivers/iommu/amd/iommu.c:amd_iommu_flush_all_caches
  - drivers/iommu/amd/iommu.c:amd_iommu_flush_all_caches
  - drivers/iommu/amd/iommu.c:amd_iommu_flush_all_caches
  - drivers/iommu/amd/iommu.c:amd_iommu_flush_all_caches
```
**Symbols:**

```
ffffffff81b531a0-ffffffff81b532c9: iommu_completion_wait.isra.0 (STB_LOCAL)
ffffffff821f5992-ffffffff821f59a6: iommu_completion_wait.isra.0.cold (STB_LOCAL)
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
In drivers/iommu/amd_iommu.c (ffffffff816a50d8)
Location: drivers/iommu/amd_iommu.c:1088
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd_iommu.c:free_irte
  - drivers/iommu/amd_iommu.c:modify_irte
  - drivers/iommu/amd_iommu.c:modify_irte_ga
  - drivers/iommu/amd_iommu.c:alloc_irq_table
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:domain_flush_complete
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd_iommu.c:free_irte
  - drivers/iommu/amd_iommu.c:modify_irte
  - drivers/iommu/amd_iommu.c:modify_irte_ga
  - drivers/iommu/amd_iommu.c:alloc_irq_table
  - drivers/iommu/amd_iommu.c:alloc_irq_table
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:domain_flush_complete
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
**Symbols:**

```
ffffffff816a4d20-ffffffff816a4e6c: iommu_completion_wait.part.0 (STB_LOCAL)
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
In drivers/iommu/amd_iommu.c (ffffffff81682ac8)
Location: drivers/iommu/amd_iommu.c:1088
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd_iommu.c:free_irte
  - drivers/iommu/amd_iommu.c:modify_irte
  - drivers/iommu/amd_iommu.c:modify_irte_ga
  - drivers/iommu/amd_iommu.c:alloc_irq_table
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:domain_flush_complete
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd_iommu.c:free_irte
  - drivers/iommu/amd_iommu.c:modify_irte
  - drivers/iommu/amd_iommu.c:modify_irte_ga
  - drivers/iommu/amd_iommu.c:alloc_irq_table
  - drivers/iommu/amd_iommu.c:alloc_irq_table
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:domain_flush_complete
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
**Symbols:**

```
ffffffff81682710-ffffffff8168285c: iommu_completion_wait.part.0 (STB_LOCAL)
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
In drivers/iommu/amd_iommu.c (ffffffff816d3348)
Location: drivers/iommu/amd_iommu.c:1088
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd_iommu.c:free_irte
  - drivers/iommu/amd_iommu.c:modify_irte
  - drivers/iommu/amd_iommu.c:modify_irte_ga
  - drivers/iommu/amd_iommu.c:alloc_irq_table
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:domain_flush_complete
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd_iommu.c:free_irte
  - drivers/iommu/amd_iommu.c:modify_irte
  - drivers/iommu/amd_iommu.c:modify_irte_ga
  - drivers/iommu/amd_iommu.c:alloc_irq_table
  - drivers/iommu/amd_iommu.c:alloc_irq_table
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:domain_flush_complete
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
**Symbols:**

```
ffffffff816d2f90-ffffffff816d30dc: iommu_completion_wait.part.0 (STB_LOCAL)
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
In drivers/iommu/amd_iommu.c (ffffffff816eda48)
Location: drivers/iommu/amd_iommu.c:1088
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd_iommu.c:free_irte
  - drivers/iommu/amd_iommu.c:modify_irte
  - drivers/iommu/amd_iommu.c:modify_irte_ga
  - drivers/iommu/amd_iommu.c:alloc_irq_table
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:domain_flush_complete
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd_iommu.c:free_irte
  - drivers/iommu/amd_iommu.c:modify_irte
  - drivers/iommu/amd_iommu.c:modify_irte_ga
  - drivers/iommu/amd_iommu.c:alloc_irq_table
  - drivers/iommu/amd_iommu.c:alloc_irq_table
  - drivers/iommu/amd_iommu.c:amd_iommu_attach_device
  - drivers/iommu/amd_iommu.c:amd_iommu_detach_device
  - drivers/iommu/amd_iommu.c:set_dte_entry
  - drivers/iommu/amd_iommu.c:domain_flush_complete
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
**Symbols:**

```
ffffffff816ed630-ffffffff816ed77c: iommu_completion_wait.part.0 (STB_LOCAL)
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
