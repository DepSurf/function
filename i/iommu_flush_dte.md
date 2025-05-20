# Function: <code>iommu_flush_dte</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int iommu_flush_dte(struct amd_iommu *iommu, u16 devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8152dac0)
Location: drivers/iommu/amd_iommu.c:915
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
**Symbols:**

```
ffffffff8152dac0-ffffffff8152db1c: iommu_flush_dte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int iommu_flush_dte(struct amd_iommu *iommu, u16 devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81581620)
Location: drivers/iommu/amd_iommu.c:1011
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
**Symbols:**

```
ffffffff81581620-ffffffff8158167c: iommu_flush_dte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int iommu_flush_dte(struct amd_iommu *iommu, u16 devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815af700)
Location: drivers/iommu/amd_iommu.c:1100
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
**Symbols:**

```
ffffffff815af700-ffffffff815af757: iommu_flush_dte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int iommu_flush_dte(struct amd_iommu *iommu, u16 devid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815c5880)
Location: drivers/iommu/amd_iommu.c:1159
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
**Symbols:**

```
ffffffff815c5880-ffffffff815c58e8: iommu_flush_dte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int iommu_flush_dte(struct amd_iommu *iommu, u16 devid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8162c460)
Location: drivers/iommu/amd_iommu.c:1100
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/amd_iommu.c:get_irq_table
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
**Symbols:**

```
ffffffff8162c460-ffffffff8162c4c8: iommu_flush_dte (STB_LOCAL)
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
In drivers/iommu/amd_iommu.c (ffffffff81667992)
Location: drivers/iommu/amd_iommu.c:1106
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:set_remap_table_entry
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
In drivers/iommu/amd_iommu.c (ffffffff81685eb2)
Location: drivers/iommu/amd_iommu.c:1121
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:set_remap_table_entry
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
In drivers/iommu/amd_iommu.c (ffffffff816bd610)
Location: drivers/iommu/amd_iommu.c:1109
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:set_remap_table_entry
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int iommu_flush_dte(struct amd_iommu *iommu, u16 devid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816e0500)
Location: drivers/iommu/amd_iommu.c:1116
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:device_flush_dte
  - drivers/iommu/amd_iommu.c:device_flush_dte
  - drivers/iommu/amd_iommu.c:device_flush_dte_alias
Direct callers:
  - drivers/iommu/amd_iommu.c:set_remap_table_entry_alias
  - drivers/iommu/amd_iommu.c:set_remap_table_entry
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
**Symbols:**

```
ffffffff816e05e0-ffffffff816e0637: iommu_flush_dte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int iommu_flush_dte(struct amd_iommu *iommu, u16 devid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff8179680e)
Location: drivers/iommu/amd/iommu.c:1060
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:set_remap_table_entry_alias
  - drivers/iommu/amd/iommu.c:set_remap_table_entry
  - drivers/iommu/amd/iommu.c:device_flush_dte_alias
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
```
**Symbols:**

```
ffffffff81796080-ffffffff8179610b: iommu_flush_dte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int iommu_flush_dte(struct amd_iommu *iommu, u16 devid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817a4f2e)
Location: drivers/iommu/amd/iommu.c:1150
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:set_remap_table_entry_alias
  - drivers/iommu/amd/iommu.c:set_remap_table_entry
  - drivers/iommu/amd/iommu.c:device_flush_dte_alias
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
```
**Symbols:**

```
ffffffff817a4860-ffffffff817a48eb: iommu_flush_dte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int iommu_flush_dte(struct amd_iommu *iommu, u16 devid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817870f3)
Location: drivers/iommu/amd/iommu.c:1082
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:set_remap_table_entry_alias
  - drivers/iommu/amd/iommu.c:set_remap_table_entry
  - drivers/iommu/amd/iommu.c:device_flush_dte_alias
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
```
**Symbols:**

```
ffffffff81786f50-ffffffff81786fe2: iommu_flush_dte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int iommu_flush_dte(struct amd_iommu *iommu, u16 devid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff8180e213)
Location: drivers/iommu/amd/iommu.c:1094
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:set_remap_table_entry_alias
  - drivers/iommu/amd/iommu.c:set_remap_table_entry
  - drivers/iommu/amd/iommu.c:device_flush_dte_alias
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
```
**Symbols:**

```
ffffffff8180e070-ffffffff8180e102: iommu_flush_dte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int iommu_flush_dte(struct amd_iommu *iommu, u16 devid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff8194f3b1)
Location: drivers/iommu/amd/iommu.c:1116
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:set_remap_table_entry_alias
  - drivers/iommu/amd/iommu.c:set_remap_table_entry
  - drivers/iommu/amd/iommu.c:device_flush_dte_alias
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
```
**Symbols:**

```
ffffffff8194ec50-ffffffff8194ece8: iommu_flush_dte (STB_LOCAL)
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
In drivers/iommu/amd/iommu.c (ffffffff81ab450b)
Location: drivers/iommu/amd/iommu.c:1185
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:set_remap_table_entry_alias
  - drivers/iommu/amd/iommu.c:set_remap_table_entry
  - drivers/iommu/amd/iommu.c:device_flush_dte_alias
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int iommu_flush_dte(struct amd_iommu *iommu, u16 devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81b00c80)
Location: drivers/iommu/amd/iommu.c:1202
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:set_remap_table_entry_alias
  - drivers/iommu/amd/iommu.c:device_flush_dte_alias
  - drivers/iommu/amd/iommu.c:iommu_flush_all_caches
```
**Symbols:**

```
ffffffff81b00c80-ffffffff81b00d18: iommu_flush_dte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int iommu_flush_dte(struct amd_iommu *iommu, u16 devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81b53b80)
Location: drivers/iommu/amd/iommu.c:1291
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:alloc_irq_table
  - drivers/iommu/amd/iommu.c:set_remap_table_entry_alias
  - drivers/iommu/amd/iommu.c:device_flush_dte_alias
  - drivers/iommu/amd/iommu.c:amd_iommu_flush_all_caches
```
**Symbols:**

```
ffffffff81b53b80-ffffffff81b53c18: iommu_flush_dte (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int iommu_flush_dte(struct amd_iommu *iommu, u16 devid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816a5f50)
Location: drivers/iommu/amd_iommu.c:1116
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:device_flush_dte
  - drivers/iommu/amd_iommu.c:device_flush_dte
  - drivers/iommu/amd_iommu.c:device_flush_dte_alias
Direct callers:
  - drivers/iommu/amd_iommu.c:set_remap_table_entry_alias
  - drivers/iommu/amd_iommu.c:set_remap_table_entry
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
**Symbols:**

```
ffffffff816a6030-ffffffff816a6087: iommu_flush_dte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int iommu_flush_dte(struct amd_iommu *iommu, u16 devid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81683940)
Location: drivers/iommu/amd_iommu.c:1116
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:device_flush_dte
  - drivers/iommu/amd_iommu.c:device_flush_dte
  - drivers/iommu/amd_iommu.c:device_flush_dte_alias
Direct callers:
  - drivers/iommu/amd_iommu.c:set_remap_table_entry_alias
  - drivers/iommu/amd_iommu.c:set_remap_table_entry
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
**Symbols:**

```
ffffffff81683a20-ffffffff81683a77: iommu_flush_dte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int iommu_flush_dte(struct amd_iommu *iommu, u16 devid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816d41c0)
Location: drivers/iommu/amd_iommu.c:1116
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:device_flush_dte
  - drivers/iommu/amd_iommu.c:device_flush_dte
  - drivers/iommu/amd_iommu.c:device_flush_dte_alias
Direct callers:
  - drivers/iommu/amd_iommu.c:set_remap_table_entry_alias
  - drivers/iommu/amd_iommu.c:set_remap_table_entry
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
**Symbols:**

```
ffffffff816d42a0-ffffffff816d42f7: iommu_flush_dte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int iommu_flush_dte(struct amd_iommu *iommu, u16 devid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816ee8c0)
Location: drivers/iommu/amd_iommu.c:1116
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:device_flush_dte
  - drivers/iommu/amd_iommu.c:device_flush_dte
  - drivers/iommu/amd_iommu.c:device_flush_dte_alias
Direct callers:
  - drivers/iommu/amd_iommu.c:set_remap_table_entry_alias
  - drivers/iommu/amd_iommu.c:set_remap_table_entry
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
**Symbols:**

```
ffffffff816ee9a0-ffffffff816ee9f7: iommu_flush_dte (STB_LOCAL)
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
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
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
