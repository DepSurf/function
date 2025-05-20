# Function: <code>iommu_enable_ga</code>

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
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff815b4a65)
Location: drivers/iommu/amd_iommu_init.c:1987
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
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
In drivers/iommu/amd_iommu_init.c (ffffffff815ca71d)
Location: drivers/iommu/amd_iommu_init.c:2007
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void iommu_enable_ga(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff81630f10)
Location: drivers/iommu/amd_iommu_init.c:2143
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff81630f10-ffffffff81630f69: iommu_enable_ga (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void iommu_enable_ga(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff8166bdd0)
Location: drivers/iommu/amd_iommu_init.c:2144
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff8166bdd0-ffffffff8166be29: iommu_enable_ga (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void iommu_enable_ga(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff8168a650)
Location: drivers/iommu/amd_iommu_init.c:2177
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff8168a650-ffffffff8168a6af: iommu_enable_ga (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void iommu_enable_ga(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816c2080)
Location: drivers/iommu/amd_iommu_init.c:2253
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff816c2080-ffffffff816c20df: iommu_enable_ga (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void iommu_enable_ga(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816e4fa0)
Location: drivers/iommu/amd_iommu_init.c:2273
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff816e4fa0-ffffffff816e4fff: iommu_enable_ga (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void iommu_enable_ga(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff8179b050)
Location: drivers/iommu/amd/init.c:2243
Inline: True
Direct callers:
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff8179b050-ffffffff8179b0af: iommu_enable_ga (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void iommu_enable_ga(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff817a9580)
Location: drivers/iommu/amd/init.c:2447
Inline: True
Direct callers:
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff817a9580-ffffffff817a95df: iommu_enable_ga (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void iommu_enable_ga(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/init.c (ffffffff8178b100)
Location: drivers/iommu/amd/init.c:2400
Inline: True
Direct callers:
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff8178b100-ffffffff8178b162: iommu_enable_ga (STB_LOCAL)
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
In drivers/iommu/amd/init.c (ffffffff81812db6)
Location: drivers/iommu/amd/init.c:2424
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
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
In drivers/iommu/amd/init.c (ffffffff81953d6a)
Location: drivers/iommu/amd/init.c:2438
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
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
In drivers/iommu/amd/init.c (ffffffff81ab981e)
Location: drivers/iommu/amd/init.c:2663
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
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
In drivers/iommu/amd/init.c (ffffffff81b05c8e)
Location: drivers/iommu/amd/init.c:2701
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
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
In drivers/iommu/amd/init.c (ffffffff81b59a2e)
Location: drivers/iommu/amd/init.c:2721
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
  - drivers/iommu/amd/init.c:early_enable_iommus
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
void iommu_enable_ga(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816aaa80)
Location: drivers/iommu/amd_iommu_init.c:2273
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff816aaa80-ffffffff816aaadf: iommu_enable_ga (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void iommu_enable_ga(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816880d0)
Location: drivers/iommu/amd_iommu_init.c:2273
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff816880d0-ffffffff8168812f: iommu_enable_ga (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void iommu_enable_ga(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816d8c60)
Location: drivers/iommu/amd_iommu_init.c:2273
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff816d8c60-ffffffff816d8cbf: iommu_enable_ga (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void iommu_enable_ga(struct amd_iommu *iommu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu_init.c (ffffffff816f3210)
Location: drivers/iommu/amd_iommu_init.c:2273
Inline: True
Direct callers:
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
  - drivers/iommu/amd_iommu_init.c:early_enable_iommus
```
**Symbols:**

```
ffffffff816f3210-ffffffff816f326f: iommu_enable_ga (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
