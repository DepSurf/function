# Function: <code>iommu_flush_irt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void iommu_flush_irt(struct amd_iommu *iommu, u16 devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8152db20)
Location: drivers/iommu/amd_iommu.c:962
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:modify_irte
  - drivers/iommu/amd_iommu.c:free_irte
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
**Symbols:**

```
ffffffff8152db20-ffffffff8152db7c: iommu_flush_irt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void iommu_flush_irt(struct amd_iommu *iommu, u16 devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81581680)
Location: drivers/iommu/amd_iommu.c:1058
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:free_irte
  - drivers/iommu/amd_iommu.c:modify_irte
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
**Symbols:**

```
ffffffff81581680-ffffffff815816dc: iommu_flush_irt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void iommu_flush_irt(struct amd_iommu *iommu, u16 devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815af6a0)
Location: drivers/iommu/amd_iommu.c:1147
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd_iommu.c:free_irte
  - drivers/iommu/amd_iommu.c:modify_irte
  - drivers/iommu/amd_iommu.c:modify_irte_ga
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
**Symbols:**

```
ffffffff815af6a0-ffffffff815af6f7: iommu_flush_irt (STB_LOCAL)
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
In drivers/iommu/amd_iommu.c (ffffffff815c631d)
Location: drivers/iommu/amd_iommu.c:1206
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd_iommu.c:free_irte
  - drivers/iommu/amd_iommu.c:modify_irte
  - drivers/iommu/amd_iommu.c:modify_irte_ga
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
In drivers/iommu/amd_iommu.c (ffffffff8162cded)
Location: drivers/iommu/amd_iommu.c:1147
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd_iommu.c:free_irte
  - drivers/iommu/amd_iommu.c:modify_irte
  - drivers/iommu/amd_iommu.c:modify_irte_ga
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
In drivers/iommu/amd_iommu.c (ffffffff81666b69)
Location: drivers/iommu/amd_iommu.c:1153
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd_iommu.c:free_irte
  - drivers/iommu/amd_iommu.c:modify_irte
  - drivers/iommu/amd_iommu.c:modify_irte_ga
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
In drivers/iommu/amd_iommu.c (ffffffff816851e9)
Location: drivers/iommu/amd_iommu.c:1168
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd_iommu.c:free_irte
  - drivers/iommu/amd_iommu.c:modify_irte
  - drivers/iommu/amd_iommu.c:modify_irte_ga
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
In drivers/iommu/amd_iommu.c (ffffffff816bc70e)
Location: drivers/iommu/amd_iommu.c:1167
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd_iommu.c:free_irte
  - drivers/iommu/amd_iommu.c:modify_irte
  - drivers/iommu/amd_iommu.c:modify_irte_ga
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
In drivers/iommu/amd_iommu.c (ffffffff816df66e)
Location: drivers/iommu/amd_iommu.c:1174
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd_iommu.c:free_irte
  - drivers/iommu/amd_iommu.c:modify_irte
  - drivers/iommu/amd_iommu.c:modify_irte_ga
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
In drivers/iommu/amd/iommu.c (ffffffff817996f7)
Location: drivers/iommu/amd/iommu.c:1118
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd/iommu.c:free_irte
  - drivers/iommu/amd/iommu.c:modify_irte_ga
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
In drivers/iommu/amd/iommu.c (ffffffff817a71d7)
Location: drivers/iommu/amd/iommu.c:1208
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd/iommu.c:free_irte
  - drivers/iommu/amd/iommu.c:modify_irte_ga
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
In drivers/iommu/amd/iommu.c (ffffffff81788291)
Location: drivers/iommu/amd/iommu.c:1140
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd/iommu.c:free_irte
  - drivers/iommu/amd/iommu.c:modify_irte_ga
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
In drivers/iommu/amd/iommu.c (ffffffff8180fb75)
Location: drivers/iommu/amd/iommu.c:1152
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd/iommu.c:free_irte
  - drivers/iommu/amd/iommu.c:modify_irte_ga
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
In drivers/iommu/amd/iommu.c (ffffffff81951140)
Location: drivers/iommu/amd/iommu.c:1174
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd/iommu.c:free_irte
  - drivers/iommu/amd/iommu.c:modify_irte_ga
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
In drivers/iommu/amd/iommu.c (ffffffff81ab62ac)
Location: drivers/iommu/amd/iommu.c:1245
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd/iommu.c:free_irte
  - drivers/iommu/amd/iommu.c:modify_irte_ga
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
In drivers/iommu/amd/iommu.c (ffffffff81b03aa7)
Location: drivers/iommu/amd/iommu.c:1262
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
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
In drivers/iommu/amd/iommu.c (ffffffff81b565d4)
Location: drivers/iommu/amd/iommu.c:1351
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:amd_iommu_flush_all_caches
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
In drivers/iommu/amd_iommu.c (ffffffff816a50be)
Location: drivers/iommu/amd_iommu.c:1174
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd_iommu.c:free_irte
  - drivers/iommu/amd_iommu.c:modify_irte
  - drivers/iommu/amd_iommu.c:modify_irte_ga
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
In drivers/iommu/amd_iommu.c (ffffffff81682aae)
Location: drivers/iommu/amd_iommu.c:1174
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd_iommu.c:free_irte
  - drivers/iommu/amd_iommu.c:modify_irte
  - drivers/iommu/amd_iommu.c:modify_irte_ga
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
In drivers/iommu/amd_iommu.c (ffffffff816d332e)
Location: drivers/iommu/amd_iommu.c:1174
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd_iommu.c:free_irte
  - drivers/iommu/amd_iommu.c:modify_irte
  - drivers/iommu/amd_iommu.c:modify_irte_ga
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
In drivers/iommu/amd_iommu.c (ffffffff816eda2e)
Location: drivers/iommu/amd_iommu.c:1174
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:amd_iommu_update_ga
  - drivers/iommu/amd_iommu.c:free_irte
  - drivers/iommu/amd_iommu.c:modify_irte
  - drivers/iommu/amd_iommu.c:modify_irte_ga
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
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
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
