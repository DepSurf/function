# Function: <code>dmar_free_dev_scope</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void dmar_free_dev_scope(struct dmar_dev_scope **devices, int *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff81533da0)
Location: drivers/iommu/dmar.c:113
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/intel-iommu.c:dmar_release_one_atsr
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
```
**Symbols:**

```
ffffffff81533da0-ffffffff81533e31: dmar_free_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void dmar_free_dev_scope(struct dmar_dev_scope **devices, int *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff81588640)
Location: drivers/iommu/dmar.c:113
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:dmar_release_one_atsr
```
**Symbols:**

```
ffffffff81588640-ffffffff815886ab: dmar_free_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dmar_free_dev_scope(struct dmar_dev_scope **devices, int *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff815b5d00)
Location: drivers/iommu/dmar.c:112
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:dmar_release_one_atsr
```
**Symbols:**

```
ffffffff815b5d00-ffffffff815b5d6b: dmar_free_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dmar_free_dev_scope(struct dmar_dev_scope **devices, int *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff815cbb40)
Location: drivers/iommu/dmar.c:114
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:dmar_release_one_atsr
```
**Symbols:**

```
ffffffff815cbb40-ffffffff815cbbad: dmar_free_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dmar_free_dev_scope(struct dmar_dev_scope **devices, int *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff81632910)
Location: drivers/iommu/dmar.c:114
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:dmar_release_one_atsr
```
**Symbols:**

```
ffffffff81632910-ffffffff8163297d: dmar_free_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dmar_free_dev_scope(struct dmar_dev_scope **devices, int *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff8166dba0)
Location: drivers/iommu/dmar.c:114
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:dmar_release_one_atsr
```
**Symbols:**

```
ffffffff8166dba0-ffffffff8166dc0e: dmar_free_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dmar_free_dev_scope(struct dmar_dev_scope **devices, int *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff8168bfd0)
Location: drivers/iommu/dmar.c:114
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:dmar_release_one_atsr
```
**Symbols:**

```
ffffffff8168bfd0-ffffffff8168c03e: dmar_free_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dmar_free_dev_scope(struct dmar_dev_scope **devices, int *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff816c3d80)
Location: drivers/iommu/dmar.c:103
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:dmar_release_one_atsr
```
**Symbols:**

```
ffffffff816c3d80-ffffffff816c3dee: dmar_free_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dmar_free_dev_scope(struct dmar_dev_scope **devices, int *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff816e6cd0)
Location: drivers/iommu/dmar.c:104
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:dmar_release_one_atsr
```
**Symbols:**

```
ffffffff816e6cd0-ffffffff816e6d3e: dmar_free_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dmar_free_dev_scope(struct dmar_dev_scope **devices, int *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff8179d570)
Location: drivers/iommu/intel/dmar.c:104
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_hp_release_drhd
  - drivers/iommu/intel/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel/iommu.c:intel_iommu_free_dmars
  - drivers/iommu/intel/iommu.c:intel_iommu_free_dmars
  - drivers/iommu/intel/iommu.c:dmar_release_one_atsr
```
**Symbols:**

```
ffffffff8179d570-ffffffff8179d5de: dmar_free_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dmar_free_dev_scope(struct dmar_dev_scope **devices, int *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff817ab290)
Location: drivers/iommu/intel/dmar.c:104
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_hp_release_drhd
  - drivers/iommu/intel/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel/iommu.c:intel_iommu_free_dmars
  - drivers/iommu/intel/iommu.c:intel_iommu_free_dmars
  - drivers/iommu/intel/iommu.c:dmar_release_one_atsr
```
**Symbols:**

```
ffffffff817ab290-ffffffff817ab2fe: dmar_free_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dmar_free_dev_scope(struct dmar_dev_scope **devices, int *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff8178e030)
Location: drivers/iommu/intel/dmar.c:105
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_free_drhd
  - drivers/iommu/intel/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:dmar_release_one_atsr
```
**Symbols:**

```
ffffffff8178e030-ffffffff8178e09e: dmar_free_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dmar_free_dev_scope(struct dmar_dev_scope **devices, int *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff818158c0)
Location: drivers/iommu/intel/dmar.c:106
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_free_drhd
  - drivers/iommu/intel/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:dmar_release_one_atsr
```
**Symbols:**

```
ffffffff818158c0-ffffffff8181592e: dmar_free_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dmar_free_dev_scope(struct dmar_dev_scope **devices, int *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff81956710)
Location: drivers/iommu/intel/dmar.c:103
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_free_drhd
  - drivers/iommu/intel/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:dmar_release_one_atsr
```
**Symbols:**

```
ffffffff81956710-ffffffff81956783: dmar_free_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dmar_free_dev_scope(struct dmar_dev_scope **devices, int *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff81abd540)
Location: drivers/iommu/intel/dmar.c:103
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_free_drhd
  - drivers/iommu/intel/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:dmar_release_one_atsr
```
**Symbols:**

```
ffffffff81abd540-ffffffff81abd5b3: dmar_free_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dmar_free_dev_scope(struct dmar_dev_scope **devices, int *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff81b09e70)
Location: drivers/iommu/intel/dmar.c:104
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_free_drhd
  - drivers/iommu/intel/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:dmar_release_one_atsr
```
**Symbols:**

```
ffffffff81b09e70-ffffffff81b09ee4: dmar_free_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dmar_free_dev_scope(struct dmar_dev_scope **devices, int *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff81b5dec0)
Location: drivers/iommu/intel/dmar.c:104
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_free_drhd
  - drivers/iommu/intel/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:intel_iommu_init
  - drivers/iommu/intel/iommu.c:dmar_release_one_atsr
```
**Symbols:**

```
ffffffff81b5dec0-ffffffff81b5df34: dmar_free_dev_scope (STB_GLOBAL)
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
void dmar_free_dev_scope(struct dmar_dev_scope **devices, int *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff816ac7b0)
Location: drivers/iommu/dmar.c:104
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:dmar_release_one_atsr
```
**Symbols:**

```
ffffffff816ac7b0-ffffffff816ac81e: dmar_free_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dmar_free_dev_scope(struct dmar_dev_scope **devices, int *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff8168a110)
Location: drivers/iommu/dmar.c:104
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:dmar_release_one_atsr
```
**Symbols:**

```
ffffffff8168a110-ffffffff8168a17e: dmar_free_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dmar_free_dev_scope(struct dmar_dev_scope **devices, int *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff816da990)
Location: drivers/iommu/dmar.c:104
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:dmar_release_one_atsr
```
**Symbols:**

```
ffffffff816da990-ffffffff816da9fe: dmar_free_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dmar_free_dev_scope(struct dmar_dev_scope **devices, int *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff816f4f40)
Location: drivers/iommu/dmar.c:104
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_free_drhd
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:intel_iommu_init
  - drivers/iommu/intel-iommu.c:dmar_release_one_atsr
```
**Symbols:**

```
ffffffff816f4f40-ffffffff816f4fae: dmar_free_dev_scope (STB_GLOBAL)
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
