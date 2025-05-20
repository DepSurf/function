# Function: <code>build_inv_irt</code>

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
In drivers/iommu/amd_iommu.c (ffffffff8152db26)
Location: drivers/iommu/amd_iommu.c:836
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_flush_irt
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
In drivers/iommu/amd_iommu.c (ffffffff81581686)
Location: drivers/iommu/amd_iommu.c:932
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_flush_irt
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
In drivers/iommu/amd_iommu.c (ffffffff815af6a6)
Location: drivers/iommu/amd_iommu.c:1002
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_flush_irt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void build_inv_irt(struct iommu_cmd *cmd, u16 devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815c3fd0)
Location: drivers/iommu/amd_iommu.c:1060
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
ffffffff815c3fd0-ffffffff815c3ff6: build_inv_irt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void build_inv_irt(struct iommu_cmd *cmd, u16 devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8162ad20)
Location: drivers/iommu/amd_iommu.c:1001
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
ffffffff8162ad20-ffffffff8162ad46: build_inv_irt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void build_inv_irt(struct iommu_cmd *cmd, u16 devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81665940)
Location: drivers/iommu/amd_iommu.c:1007
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
ffffffff81665940-ffffffff81665966: build_inv_irt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void build_inv_irt(struct iommu_cmd *cmd, u16 devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816843b0)
Location: drivers/iommu/amd_iommu.c:1022
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
ffffffff816843b0-ffffffff816843d6: build_inv_irt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void build_inv_irt(struct iommu_cmd *cmd, u16 devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816bb910)
Location: drivers/iommu/amd_iommu.c:1010
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
ffffffff816bb910-ffffffff816bb92f: build_inv_irt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void build_inv_irt(struct iommu_cmd *cmd, u16 devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816de7a0)
Location: drivers/iommu/amd_iommu.c:1017
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
ffffffff816de7a0-ffffffff816de7bf: build_inv_irt (STB_LOCAL)
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
Location: drivers/iommu/amd/iommu.c:961
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
Location: drivers/iommu/amd/iommu.c:1052
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
Location: drivers/iommu/amd/iommu.c:984
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
Location: drivers/iommu/amd/iommu.c:996
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
Location: drivers/iommu/amd/iommu.c:1018
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
Location: drivers/iommu/amd/iommu.c:1087
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
<summary>In <code>6.5</code>: ✅</summary>

```c
void build_inv_irt(struct iommu_cmd *cmd, u16 devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81afdc50)
Location: drivers/iommu/amd/iommu.c:1104
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:iommu_flush_irt_and_complete
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
```
**Symbols:**

```
ffffffff81afdc50-ffffffff81afdc77: build_inv_irt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void build_inv_irt(struct iommu_cmd *cmd, u16 devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81b511d0)
Location: drivers/iommu/amd/iommu.c:1193
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:iommu_flush_irt_and_complete
  - drivers/iommu/amd/iommu.c:amd_iommu_flush_all_caches
```
**Symbols:**

```
ffffffff81b511d0-ffffffff81b511f7: build_inv_irt (STB_LOCAL)
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
void build_inv_irt(struct iommu_cmd *cmd, u16 devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816a41f0)
Location: drivers/iommu/amd_iommu.c:1017
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
ffffffff816a41f0-ffffffff816a420f: build_inv_irt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void build_inv_irt(struct iommu_cmd *cmd, u16 devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81681be0)
Location: drivers/iommu/amd_iommu.c:1017
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
ffffffff81681be0-ffffffff81681bff: build_inv_irt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void build_inv_irt(struct iommu_cmd *cmd, u16 devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816d2460)
Location: drivers/iommu/amd_iommu.c:1017
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
ffffffff816d2460-ffffffff816d247f: build_inv_irt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void build_inv_irt(struct iommu_cmd *cmd, u16 devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816ecaa0)
Location: drivers/iommu/amd_iommu.c:1017
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
ffffffff816ecaa0-ffffffff816ecabf: build_inv_irt (STB_LOCAL)
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
