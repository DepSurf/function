# Function: <code>dmar_alloc_dev_scope</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *dmar_alloc_dev_scope(void *start, void *end, int *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff81533cf0)
Location: drivers/iommu/dmar.c:90
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel-iommu.c:dmar_parse_one_rmrr
  - drivers/iommu/intel-iommu.c:dmar_parse_one_atsr
```
**Symbols:**

```
ffffffff81533cf0-ffffffff81533d94: dmar_alloc_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *dmar_alloc_dev_scope(void *start, void *end, int *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff81588580)
Location: drivers/iommu/dmar.c:90
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel-iommu.c:dmar_parse_one_atsr
  - drivers/iommu/intel-iommu.c:dmar_parse_one_rmrr
```
**Symbols:**

```
ffffffff81588580-ffffffff81588631: dmar_alloc_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *dmar_alloc_dev_scope(void *start, void *end, int *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff815b5c40)
Location: drivers/iommu/dmar.c:89
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel-iommu.c:dmar_parse_one_atsr
  - drivers/iommu/intel-iommu.c:dmar_parse_one_rmrr
```
**Symbols:**

```
ffffffff815b5c40-ffffffff815b5cf1: dmar_alloc_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *dmar_alloc_dev_scope(void *start, void *end, int *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff815cba90)
Location: drivers/iommu/dmar.c:91
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel-iommu.c:dmar_parse_one_atsr
  - drivers/iommu/intel-iommu.c:dmar_parse_one_rmrr
```
**Symbols:**

```
ffffffff815cba90-ffffffff815cbb3b: dmar_alloc_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *dmar_alloc_dev_scope(void *start, void *end, int *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff81632860)
Location: drivers/iommu/dmar.c:91
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel-iommu.c:dmar_parse_one_atsr
  - drivers/iommu/intel-iommu.c:dmar_parse_one_rmrr
```
**Symbols:**

```
ffffffff81632860-ffffffff8163290b: dmar_alloc_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void *dmar_alloc_dev_scope(void *start, void *end, int *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:91
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel-iommu.c:dmar_parse_one_atsr
  - drivers/iommu/intel-iommu.c:dmar_parse_one_rmrr
```
**Symbols:**

```
ffffffff8166f344-ffffffff8166f361: dmar_alloc_dev_scope.cold.25 (STB_LOCAL)
ffffffff8166db00-ffffffff8166db91: dmar_alloc_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void *dmar_alloc_dev_scope(void *start, void *end, int *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:91
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel-iommu.c:dmar_parse_one_atsr
  - drivers/iommu/intel-iommu.c:dmar_parse_one_rmrr
```
**Symbols:**

```
ffffffff8168d8a4-ffffffff8168d8c1: dmar_alloc_dev_scope.cold.24 (STB_LOCAL)
ffffffff8168bf30-ffffffff8168bfc1: dmar_alloc_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void *dmar_alloc_dev_scope(void *start, void *end, int *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:80
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel-iommu.c:dmar_parse_one_atsr
  - drivers/iommu/intel-iommu.c:dmar_parse_one_rmrr
```
**Symbols:**

```
ffffffff816c5389-ffffffff816c53aa: dmar_alloc_dev_scope.cold (STB_LOCAL)
ffffffff816c3cf0-ffffffff816c3d74: dmar_alloc_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void *dmar_alloc_dev_scope(void *start, void *end, int *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:81
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel-iommu.c:dmar_parse_one_atsr
  - drivers/iommu/intel-iommu.c:dmar_parse_one_rmrr
```
**Symbols:**

```
ffffffff816e82c0-ffffffff816e82e1: dmar_alloc_dev_scope.cold (STB_LOCAL)
ffffffff816e6c40-ffffffff816e6cc4: dmar_alloc_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void *dmar_alloc_dev_scope(void *start, void *end, int *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:81
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel/iommu.c:dmar_parse_one_atsr
  - drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr
```
**Symbols:**

```
ffffffff8179ee40-ffffffff8179ee59: dmar_alloc_dev_scope.cold (STB_LOCAL)
ffffffff8179d4e0-ffffffff8179d570: dmar_alloc_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void *dmar_alloc_dev_scope(void *start, void *end, int *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:81
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel/iommu.c:dmar_parse_one_atsr
  - drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr
```
**Symbols:**

```
ffffffff81c0c288-ffffffff81c0c2a1: dmar_alloc_dev_scope.cold (STB_LOCAL)
ffffffff817ab200-ffffffff817ab290: dmar_alloc_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void *dmar_alloc_dev_scope(void *start, void *end, int *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:82
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel/iommu.c:dmar_parse_one_satc
  - drivers/iommu/intel/iommu.c:dmar_parse_one_atsr
  - drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr
```
**Symbols:**

```
ffffffff81bfdaea-ffffffff81bfdb0b: dmar_alloc_dev_scope.cold (STB_LOCAL)
ffffffff8178dfa0-ffffffff8178e022: dmar_alloc_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void *dmar_alloc_dev_scope(void *start, void *end, int *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:83
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel/iommu.c:dmar_parse_one_satc
  - drivers/iommu/intel/iommu.c:dmar_parse_one_atsr
  - drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr
```
**Symbols:**

```
ffffffff81cff07f-ffffffff81cff0a0: dmar_alloc_dev_scope.cold (STB_LOCAL)
ffffffff81815830-ffffffff818158b2: dmar_alloc_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void *dmar_alloc_dev_scope(void *start, void *end, int *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/intel/dmar.c (0)
Location: drivers/iommu/intel/dmar.c:80
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel/iommu.c:dmar_parse_one_satc
  - drivers/iommu/intel/iommu.c:dmar_parse_one_atsr
  - drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr
```
**Symbols:**

```
ffffffff81ec7852-ffffffff81ec7873: dmar_alloc_dev_scope.cold (STB_LOCAL)
ffffffff81956660-ffffffff8195670a: dmar_alloc_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *dmar_alloc_dev_scope(void *start, void *end, int *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff81abd470)
Location: drivers/iommu/intel/dmar.c:80
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel/iommu.c:dmar_parse_one_satc
  - drivers/iommu/intel/iommu.c:dmar_parse_one_atsr
  - drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr
```
**Symbols:**

```
ffffffff81abd470-ffffffff81abd52d: dmar_alloc_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *dmar_alloc_dev_scope(void *start, void *end, int *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff81b09da0)
Location: drivers/iommu/intel/dmar.c:81
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel/iommu.c:dmar_parse_one_satc
  - drivers/iommu/intel/iommu.c:dmar_parse_one_atsr
  - drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr
```
**Symbols:**

```
ffffffff81b09da0-ffffffff81b09e5d: dmar_alloc_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *dmar_alloc_dev_scope(void *start, void *end, int *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff81b5ddf0)
Location: drivers/iommu/intel/dmar.c:81
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel/iommu.c:dmar_parse_one_satc
  - drivers/iommu/intel/iommu.c:dmar_parse_one_atsr
  - drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr
```
**Symbols:**

```
ffffffff81b5ddf0-ffffffff81b5dead: dmar_alloc_dev_scope (STB_GLOBAL)
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
void *dmar_alloc_dev_scope(void *start, void *end, int *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:81
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel-iommu.c:dmar_parse_one_atsr
  - drivers/iommu/intel-iommu.c:dmar_parse_one_rmrr
```
**Symbols:**

```
ffffffff816adda0-ffffffff816addc1: dmar_alloc_dev_scope.cold (STB_LOCAL)
ffffffff816ac720-ffffffff816ac7a4: dmar_alloc_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void *dmar_alloc_dev_scope(void *start, void *end, int *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:81
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel-iommu.c:dmar_parse_one_atsr
  - drivers/iommu/intel-iommu.c:dmar_parse_one_rmrr
```
**Symbols:**

```
ffffffff8168b700-ffffffff8168b721: dmar_alloc_dev_scope.cold (STB_LOCAL)
ffffffff8168a080-ffffffff8168a104: dmar_alloc_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void *dmar_alloc_dev_scope(void *start, void *end, int *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:81
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel-iommu.c:dmar_parse_one_atsr
  - drivers/iommu/intel-iommu.c:dmar_parse_one_rmrr
```
**Symbols:**

```
ffffffff816dbf80-ffffffff816dbfa1: dmar_alloc_dev_scope.cold (STB_LOCAL)
ffffffff816da900-ffffffff816da984: dmar_alloc_dev_scope (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void *dmar_alloc_dev_scope(void *start, void *end, int *cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/dmar.c (0)
Location: drivers/iommu/dmar.c:81
Inline: False
Direct callers:
  - drivers/iommu/dmar.c:dmar_parse_one_drhd
  - drivers/iommu/intel-iommu.c:dmar_parse_one_atsr
  - drivers/iommu/intel-iommu.c:dmar_parse_one_rmrr
```
**Symbols:**

```
ffffffff816f6550-ffffffff816f6571: dmar_alloc_dev_scope.cold (STB_LOCAL)
ffffffff816f4eb0-ffffffff816f4f34: dmar_alloc_dev_scope (STB_GLOBAL)
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
