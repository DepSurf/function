# Function: <code>amd_nb_num</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff810632b3)
Location: arch/x86/include/asm/amd_nb.h:69
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
```
```
In arch/x86/kernel/amd_gart_64.c (0)
Location: arch/x86/include/asm/amd_nb.h:69
Inline: True
```
```
In drivers/char/agp/amd64-agp.c (0)
Location: arch/x86/include/asm/amd_nb.h:69
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff81f9cbef)
Location: arch/x86/include/asm/amd_nb.h:77
Inline: True
Inline callers:
  - arch/x86/kernel/amd_nb.c:init_amd_nbs
```
```
In arch/x86/kernel/amd_gart_64.c (0)
Location: arch/x86/include/asm/amd_nb.h:77
Inline: True
```
```
In drivers/char/agp/amd64-agp.c (0)
Location: arch/x86/include/asm/amd_nb.h:77
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u16 amd_nb_num();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff81065e30)
Location: arch/x86/kernel/amd_nb.c:63
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
**Symbols:**

```
ffffffff81065e30-ffffffff81065e42: amd_nb_num (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u16 amd_nb_num();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff810651c0)
Location: arch/x86/kernel/amd_nb.c:63
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
**Symbols:**

```
ffffffff810651c0-ffffffff810651d2: amd_nb_num (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u16 amd_nb_num();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff81069360)
Location: arch/x86/kernel/amd_nb.c:67
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
**Symbols:**

```
ffffffff81069360-ffffffff81069372: amd_nb_num (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u16 amd_nb_num();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff8106bfb0)
Location: arch/x86/kernel/amd_nb.c:73
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
**Symbols:**

```
ffffffff8106bfb0-ffffffff8106bfc2: amd_nb_num (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u16 amd_nb_num();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff81071d40)
Location: arch/x86/kernel/amd_nb.c:93
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
**Symbols:**

```
ffffffff81071d40-ffffffff81071d52: amd_nb_num (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u16 amd_nb_num();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff81075880)
Location: arch/x86/kernel/amd_nb.c:94
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
**Symbols:**

```
ffffffff81075880-ffffffff81075892: amd_nb_num (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u16 amd_nb_num();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff81076850)
Location: arch/x86/kernel/amd_nb.c:100
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
**Symbols:**

```
ffffffff81076850-ffffffff81076862: amd_nb_num (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u16 amd_nb_num();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff8107daf0)
Location: arch/x86/kernel/amd_nb.c:103
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
**Symbols:**

```
ffffffff8107daf0-ffffffff8107db02: amd_nb_num (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u16 amd_nb_num();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff8107d7d0)
Location: arch/x86/kernel/amd_nb.c:103
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
**Symbols:**

```
ffffffff8107d7d0-ffffffff8107d7e2: amd_nb_num (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u16 amd_nb_num();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff8107e900)
Location: arch/x86/kernel/amd_nb.c:103
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
**Symbols:**

```
ffffffff8107e900-ffffffff8107e912: amd_nb_num (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u16 amd_nb_num();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff8108d590)
Location: arch/x86/kernel/amd_nb.c:116
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
**Symbols:**

```
ffffffff8108d590-ffffffff8108d5a2: amd_nb_num (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u16 amd_nb_num();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff8109e110)
Location: arch/x86/kernel/amd_nb.c:116
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:amd64_cleanup
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
**Symbols:**

```
ffffffff8109e110-ffffffff8109e126: amd_nb_num (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u16 amd_nb_num();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff810b5390)
Location: arch/x86/kernel/amd_nb.c:129
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:amd64_cleanup
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
**Symbols:**

```
ffffffff810b5390-ffffffff810b53a6: amd_nb_num (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u16 amd_nb_num();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff810b8460)
Location: arch/x86/kernel/amd_nb.c:137
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:amd64_cleanup
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
**Symbols:**

```
ffffffff810b8460-ffffffff810b8476: amd_nb_num (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u16 amd_nb_num();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff810bf8a0)
Location: arch/x86/kernel/amd_nb.c:153
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/kernel/amd_gart_64.c:init_amd_gatt
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:amd64_cleanup
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
**Symbols:**

```
ffffffff810bf8a0-ffffffff810bf8b6: amd_nb_num (STB_GLOBAL)
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
u16 amd_nb_num();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff81075850)
Location: arch/x86/kernel/amd_nb.c:100
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
**Symbols:**

```
ffffffff81075850-ffffffff81075862: amd_nb_num (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u16 amd_nb_num();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff81065840)
Location: arch/x86/kernel/amd_nb.c:100
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
**Symbols:**

```
ffffffff81065840-ffffffff81065852: amd_nb_num (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u16 amd_nb_num();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff81075800)
Location: arch/x86/kernel/amd_nb.c:100
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
**Symbols:**

```
ffffffff81075800-ffffffff81075812: amd_nb_num (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u16 amd_nb_num();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/amd_nb.c (ffffffff81077860)
Location: arch/x86/kernel/amd_nb.c:100
Inline: False
Direct callers:
  - arch/x86/kernel/amd_gart_64.c:gart_iommu_init
  - arch/x86/kernel/amd_gart_64.c:gart_resume
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
  - drivers/char/agp/amd64-agp.c:amd_8151_configure
```
**Symbols:**

```
ffffffff81077860-ffffffff81077872: amd_nb_num (STB_GLOBAL)
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
