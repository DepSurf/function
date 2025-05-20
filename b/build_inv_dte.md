# Function: <code>build_inv_dte</code>

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
In drivers/iommu/amd_iommu.c (ffffffff8152dac6)
Location: drivers/iommu/amd_iommu.c:707
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_flush_dte
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
In drivers/iommu/amd_iommu.c (ffffffff81581626)
Location: drivers/iommu/amd_iommu.c:803
Inline: True
Inline callers:
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
In drivers/iommu/amd_iommu.c (ffffffff815af706)
Location: drivers/iommu/amd_iommu.c:873
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:iommu_flush_dte
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void build_inv_dte(struct iommu_cmd *cmd, u16 devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815c3f30)
Location: drivers/iommu/amd_iommu.c:931
Inline: False
```
**Symbols:**

```
ffffffff815c3f30-ffffffff815c3f56: build_inv_dte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void build_inv_dte(struct iommu_cmd *cmd, u16 devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8162ac80)
Location: drivers/iommu/amd_iommu.c:872
Inline: False
```
**Symbols:**

```
ffffffff8162ac80-ffffffff8162aca6: build_inv_dte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void build_inv_dte(struct iommu_cmd *cmd, u16 devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816658a0)
Location: drivers/iommu/amd_iommu.c:878
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:set_remap_table_entry
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
**Symbols:**

```
ffffffff816658a0-ffffffff816658c6: build_inv_dte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void build_inv_dte(struct iommu_cmd *cmd, u16 devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81684310)
Location: drivers/iommu/amd_iommu.c:893
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:set_remap_table_entry
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
**Symbols:**

```
ffffffff81684310-ffffffff81684336: build_inv_dte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void build_inv_dte(struct iommu_cmd *cmd, u16 devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816bb880)
Location: drivers/iommu/amd_iommu.c:881
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:set_remap_table_entry
  - drivers/iommu/amd_iommu.c:iommu_flush_all_caches
```
**Symbols:**

```
ffffffff816bb880-ffffffff816bb89f: build_inv_dte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void build_inv_dte(struct iommu_cmd *cmd, u16 devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816de710)
Location: drivers/iommu/amd_iommu.c:888
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:device_flush_dte
  - drivers/iommu/amd_iommu.c:device_flush_dte
  - drivers/iommu/amd_iommu.c:device_flush_dte_alias
```
**Symbols:**

```
ffffffff816de710-ffffffff816de72f: build_inv_dte (STB_LOCAL)
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
In drivers/iommu/amd/iommu.c (ffffffff8179680e)
Location: drivers/iommu/amd/iommu.c:832
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
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817a4f2e)
Location: drivers/iommu/amd/iommu.c:923
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
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff817870f3)
Location: drivers/iommu/amd/iommu.c:847
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
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff8180e213)
Location: drivers/iommu/amd/iommu.c:859
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
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff8194f3b1)
Location: drivers/iommu/amd/iommu.c:881
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
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81ab450b)
Location: drivers/iommu/amd/iommu.c:950
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
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81b00cb3)
Location: drivers/iommu/amd/iommu.c:967
Inline: True
Inline callers:
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
In drivers/iommu/amd/iommu.c (ffffffff81b53bb3)
Location: drivers/iommu/amd/iommu.c:1080
Inline: True
Inline callers:
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
<summary>In <code>aws</code>: ✅</summary>

```c
void build_inv_dte(struct iommu_cmd *cmd, u16 devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816a4160)
Location: drivers/iommu/amd_iommu.c:888
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:device_flush_dte
  - drivers/iommu/amd_iommu.c:device_flush_dte
  - drivers/iommu/amd_iommu.c:device_flush_dte_alias
```
**Symbols:**

```
ffffffff816a4160-ffffffff816a417f: build_inv_dte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void build_inv_dte(struct iommu_cmd *cmd, u16 devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81681b50)
Location: drivers/iommu/amd_iommu.c:888
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:device_flush_dte
  - drivers/iommu/amd_iommu.c:device_flush_dte
  - drivers/iommu/amd_iommu.c:device_flush_dte_alias
```
**Symbols:**

```
ffffffff81681b50-ffffffff81681b6f: build_inv_dte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void build_inv_dte(struct iommu_cmd *cmd, u16 devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816d23d0)
Location: drivers/iommu/amd_iommu.c:888
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:device_flush_dte
  - drivers/iommu/amd_iommu.c:device_flush_dte
  - drivers/iommu/amd_iommu.c:device_flush_dte_alias
```
**Symbols:**

```
ffffffff816d23d0-ffffffff816d23ef: build_inv_dte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void build_inv_dte(struct iommu_cmd *cmd, u16 devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816eca10)
Location: drivers/iommu/amd_iommu.c:888
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:device_flush_dte
  - drivers/iommu/amd_iommu.c:device_flush_dte
  - drivers/iommu/amd_iommu.c:device_flush_dte_alias
```
**Symbols:**

```
ffffffff816eca10-ffffffff816eca2f: build_inv_dte (STB_LOCAL)
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
