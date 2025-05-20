# Function: <code>amd_iommu_apply_erratum_63</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void amd_iommu_apply_erratum_63(u16 devid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff81fa8b47)
Location: drivers/iommu/amd_iommu_init.c:646
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:set_dev_entry_from_acpi
Direct callers:
  - drivers/iommu/amd_iommu.c:clear_dte_entry
```
**Symbols:**

```
ffffffff81532e90-ffffffff81532ed6: amd_iommu_apply_erratum_63 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void amd_iommu_apply_erratum_63(u16 devid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff81fd5444)
Location: drivers/iommu/amd_iommu_init.c:700
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:clear_dte_entry
```
**Symbols:**

```
ffffffff815876b0-ffffffff815876f6: amd_iommu_apply_erratum_63 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void amd_iommu_apply_erratum_63(u16 devid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff8201371c)
Location: drivers/iommu/amd_iommu_init.c:802
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:clear_dte_entry
```
**Symbols:**

```
ffffffff815b4db0-ffffffff815b4df6: amd_iommu_apply_erratum_63 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void amd_iommu_apply_erratum_63(u16 devid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff820f4ae9)
Location: drivers/iommu/amd_iommu_init.c:811
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:clear_dte_entry
```
**Symbols:**

```
ffffffff815cabf0-ffffffff815cac36: amd_iommu_apply_erratum_63 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void amd_iommu_apply_erratum_63(u16 devid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff826fe1a9)
Location: drivers/iommu/amd_iommu_init.c:946
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:clear_dte_entry
```
**Symbols:**

```
ffffffff816319b0-ffffffff816319f6: amd_iommu_apply_erratum_63 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void amd_iommu_apply_erratum_63(u16 devid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff82728471)
Location: drivers/iommu/amd_iommu_init.c:946
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:clear_dte_entry
```
**Symbols:**

```
ffffffff8166c530-ffffffff8166c56e: amd_iommu_apply_erratum_63 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void amd_iommu_apply_erratum_63(u16 devid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff828e079e)
Location: drivers/iommu/amd_iommu_init.c:973
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:clear_dte_entry
```
**Symbols:**

```
ffffffff8168ae40-ffffffff8168ae7e: amd_iommu_apply_erratum_63 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void amd_iommu_apply_erratum_63(u16 devid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff828fb176)
Location: drivers/iommu/amd_iommu_init.c:961
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:clear_dte_entry
```
**Symbols:**

```
ffffffff816c2890-ffffffff816c28ce: amd_iommu_apply_erratum_63 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void amd_iommu_apply_erratum_63(u16 devid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff82903fff)
Location: drivers/iommu/amd_iommu_init.c:962
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:do_detach
```
**Symbols:**

```
ffffffff816e57b0-ffffffff816e57ee: amd_iommu_apply_erratum_63 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void amd_iommu_apply_erratum_63(u16 devid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff8179b950)
Location: drivers/iommu/amd/init.c:962
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:do_detach
```
**Symbols:**

```
ffffffff8179b950-ffffffff8179b98e: amd_iommu_apply_erratum_63 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void amd_iommu_apply_erratum_63(u16 devid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff817a9d90)
Location: drivers/iommu/amd/init.c:1025
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:do_detach
```
**Symbols:**

```
ffffffff817a9d90-ffffffff817a9dce: amd_iommu_apply_erratum_63 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void amd_iommu_apply_erratum_63(u16 devid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff8178bad0)
Location: drivers/iommu/amd/init.c:1021
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:do_detach
```
**Symbols:**

```
ffffffff8178bad0-ffffffff8178bb0e: amd_iommu_apply_erratum_63 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void amd_iommu_apply_erratum_63(u16 devid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff818130c0)
Location: drivers/iommu/amd/init.c:1032
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:do_detach
```
**Symbols:**

```
ffffffff818130c0-ffffffff818130fe: amd_iommu_apply_erratum_63 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void amd_iommu_apply_erratum_63(u16 devid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81954020)
Location: drivers/iommu/amd/init.c:1038
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:do_detach
```
**Symbols:**

```
ffffffff81954020-ffffffff81954072: amd_iommu_apply_erratum_63 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void amd_iommu_apply_erratum_63(struct amd_iommu *iommu, u16 devid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81ab9c90)
Location: drivers/iommu/amd/init.c:1142
Inline: False
Direct callers:
  - drivers/iommu/amd/iommu.c:do_detach
```
**Symbols:**

```
ffffffff81ab9c90-ffffffff81ab9d0c: amd_iommu_apply_erratum_63 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void amd_iommu_apply_erratum_63(struct amd_iommu *iommu, u16 devid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81b06230)
Location: drivers/iommu/amd/init.c:1177
Inline: True
Direct callers:
  - drivers/iommu/amd/iommu.c:do_detach
```
**Symbols:**

```
ffffffff81b06230-ffffffff81b062ac: amd_iommu_apply_erratum_63 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void amd_iommu_apply_erratum_63(struct amd_iommu *iommu, u16 devid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff81b59fd0)
Location: drivers/iommu/amd/init.c:1192
Inline: True
Direct callers:
  - drivers/iommu/amd/iommu.c:do_detach
```
**Symbols:**

```
ffffffff81b59fd0-ffffffff81b5a04c: amd_iommu_apply_erratum_63 (STB_GLOBAL)
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
void amd_iommu_apply_erratum_63(u16 devid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff828eb7e6)
Location: drivers/iommu/amd_iommu_init.c:962
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:do_detach
```
**Symbols:**

```
ffffffff816ab290-ffffffff816ab2ce: amd_iommu_apply_erratum_63 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void amd_iommu_apply_erratum_63(u16 devid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff828e2c73)
Location: drivers/iommu/amd_iommu_init.c:962
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:do_detach
```
**Symbols:**

```
ffffffff81688bf0-ffffffff81688c2e: amd_iommu_apply_erratum_63 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void amd_iommu_apply_erratum_63(u16 devid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff828ff322)
Location: drivers/iommu/amd_iommu_init.c:962
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:do_detach
```
**Symbols:**

```
ffffffff816d9470-ffffffff816d94ae: amd_iommu_apply_erratum_63 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void amd_iommu_apply_erratum_63(u16 devid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff82905061)
Location: drivers/iommu/amd_iommu_init.c:962
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu.c:do_detach
```
**Symbols:**

```
ffffffff816f3a20-ffffffff816f3a5e: amd_iommu_apply_erratum_63 (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct amd_iommu *iommu</code>
</li>
<li>
<b>Param reordered. </b>
<code>devid</code> ➡️ <code>iommu, devid</code>
</li>
</ul>
</details>
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
