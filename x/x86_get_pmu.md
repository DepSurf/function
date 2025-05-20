# Function: <code>x86_get_pmu</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct pmu *x86_get_pmu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810072d0)
Location: arch/x86/events/core.c:679
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_ds_init
```
**Symbols:**

```
ffffffff810072d0-ffffffff810072e2: x86_get_pmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct pmu *x86_get_pmu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81007440)
Location: arch/x86/events/core.c:687
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_ds_init
  - arch/x86/events/intel/ds.c:intel_ds_init
```
**Symbols:**

```
ffffffff81007440-ffffffff81007452: x86_get_pmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct pmu *x86_get_pmu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810084c0)
Location: arch/x86/events/core.c:688
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_ds_init
  - arch/x86/events/intel/ds.c:intel_ds_init
```
**Symbols:**

```
ffffffff810084c0-ffffffff810084d2: x86_get_pmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct pmu *x86_get_pmu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81007570)
Location: arch/x86/events/core.c:720
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_ds_init
  - arch/x86/events/intel/ds.c:intel_ds_init
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_init_skl
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_init_hsw
  - arch/x86/events/intel/lbr.c:release_lbr_buffers
```
**Symbols:**

```
ffffffff81007570-ffffffff81007582: x86_get_pmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct pmu *x86_get_pmu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81007cf0)
Location: arch/x86/events/core.c:760
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_ds_init
  - arch/x86/events/intel/ds.c:intel_ds_init
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_init_skl
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_init_hsw
  - arch/x86/events/intel/lbr.c:reserve_lbr_buffers
  - arch/x86/events/intel/lbr.c:release_lbr_buffers
```
**Symbols:**

```
ffffffff81007cf0-ffffffff81007d24: x86_get_pmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct pmu *x86_get_pmu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81008720)
Location: arch/x86/events/core.c:760
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_ds_init
  - arch/x86/events/intel/ds.c:intel_ds_init
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_init_skl
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_init_hsw
  - arch/x86/events/intel/lbr.c:reserve_lbr_buffers
  - arch/x86/events/intel/lbr.c:release_lbr_buffers
```
**Symbols:**

```
ffffffff81008720-ffffffff81008777: x86_get_pmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct pmu *x86_get_pmu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81007d50)
Location: arch/x86/events/core.c:762
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_ds_init
  - arch/x86/events/intel/ds.c:intel_ds_init
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_init_skl
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_init_hsw
  - arch/x86/events/intel/lbr.c:reserve_lbr_buffers
  - arch/x86/events/intel/lbr.c:release_lbr_buffers
```
**Symbols:**

```
ffffffff81007d50-ffffffff81007db7: x86_get_pmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct pmu *x86_get_pmu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81009660)
Location: arch/x86/events/core.c:766
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_ds_init
  - arch/x86/events/intel/ds.c:intel_ds_init
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_init_skl
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_init_hsw
  - arch/x86/events/intel/lbr.c:reserve_lbr_buffers
  - arch/x86/events/intel/lbr.c:release_lbr_buffers
```
**Symbols:**

```
ffffffff81009660-ffffffff810096c7: x86_get_pmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct pmu *x86_get_pmu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81008e70)
Location: arch/x86/events/core.c:766
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_ds_init
  - arch/x86/events/intel/ds.c:intel_ds_init
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_init_skl
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_init_hsw
  - arch/x86/events/intel/lbr.c:reserve_lbr_buffers
  - arch/x86/events/intel/lbr.c:release_lbr_buffers
```
**Symbols:**

```
ffffffff81008e70-ffffffff81008ed7: x86_get_pmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct pmu *x86_get_pmu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff8100e590)
Location: arch/x86/events/core.c:764
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_ds_init
  - arch/x86/events/intel/ds.c:intel_ds_init
  - arch/x86/events/intel/lbr.c:intel_pmu_arch_lbr_init
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_init_skl
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_init_hsw
  - arch/x86/events/intel/lbr.c:reserve_lbr_buffers
  - arch/x86/events/intel/lbr.c:release_lbr_buffers
```
**Symbols:**

```
ffffffff8100e590-ffffffff8100e5f7: x86_get_pmu (STB_GLOBAL)
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
struct pmu *x86_get_pmu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81007440)
Location: arch/x86/events/core.c:687
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_ds_init
  - arch/x86/events/intel/ds.c:intel_ds_init
```
**Symbols:**

```
ffffffff81007440-ffffffff81007452: x86_get_pmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct pmu *x86_get_pmu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81005be0)
Location: arch/x86/events/core.c:687
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_ds_init
  - arch/x86/events/intel/ds.c:intel_ds_init
```
**Symbols:**

```
ffffffff81005be0-ffffffff81005bf2: x86_get_pmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct pmu *x86_get_pmu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81007400)
Location: arch/x86/events/core.c:687
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_ds_init
  - arch/x86/events/intel/ds.c:intel_ds_init
```
**Symbols:**

```
ffffffff81007400-ffffffff81007412: x86_get_pmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct pmu *x86_get_pmu();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81007560)
Location: arch/x86/events/core.c:687
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_ds_init
  - arch/x86/events/intel/ds.c:intel_ds_init
```
**Symbols:**

```
ffffffff81007560-ffffffff81007572: x86_get_pmu (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int cpu</code>
</li>
</ul>
</details>
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
