# Function: <code>xen_smp_intr_init_pv</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int xen_smp_intr_init_pv(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff810299b0)
Location: arch/x86/xen/smp_pv.c:106
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_cpu_up_prepare_pv
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
**Symbols:**

```
ffffffff810299b0-ffffffff81029abb: xen_smp_intr_init_pv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xen_smp_intr_init_pv(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff81029bd0)
Location: arch/x86/xen/smp_pv.c:108
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
**Symbols:**

```
ffffffff81029bd0-ffffffff81029cdb: xen_smp_intr_init_pv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xen_smp_intr_init_pv(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff8102a670)
Location: arch/x86/xen/smp_pv.c:111
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
**Symbols:**

```
ffffffff8102a670-ffffffff8102a777: xen_smp_intr_init_pv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xen_smp_intr_init_pv(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff8102acb0)
Location: arch/x86/xen/smp_pv.c:113
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
**Symbols:**

```
ffffffff8102acb0-ffffffff8102adb7: xen_smp_intr_init_pv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int xen_smp_intr_init_pv(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff8102ca80)
Location: arch/x86/xen/smp_pv.c:114
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
**Symbols:**

```
ffffffff8102ca80-ffffffff8102cb8d: xen_smp_intr_init_pv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int xen_smp_intr_init_pv(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff8102d350)
Location: arch/x86/xen/smp_pv.c:114
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
**Symbols:**

```
ffffffff8102d350-ffffffff8102d45d: xen_smp_intr_init_pv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xen_smp_intr_init_pv(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff8102f460)
Location: arch/x86/xen/smp_pv.c:117
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_cpu_up_prepare_pv
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
**Symbols:**

```
ffffffff8102f460-ffffffff8102f56d: xen_smp_intr_init_pv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xen_smp_intr_init_pv(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff81030200)
Location: arch/x86/xen/smp_pv.c:116
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_cpu_up_prepare_pv
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
**Symbols:**

```
ffffffff81030200-ffffffff8103030d: xen_smp_intr_init_pv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xen_smp_intr_init_pv(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff81030d00)
Location: arch/x86/xen/smp_pv.c:116
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_cpu_up_prepare_pv
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
**Symbols:**

```
ffffffff81030d00-ffffffff81030e0d: xen_smp_intr_init_pv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int xen_smp_intr_init_pv(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff81035df0)
Location: arch/x86/xen/smp_pv.c:115
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
**Symbols:**

```
ffffffff81035df0-ffffffff81035f7c: xen_smp_intr_init_pv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int xen_smp_intr_init_pv(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/smp_pv.c (0)
Location: arch/x86/xen/smp_pv.c:115
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
**Symbols:**

```
ffffffff81e46ff7-ffffffff81e4700b: xen_smp_intr_init_pv.cold (STB_LOCAL)
ffffffff8103bc30-ffffffff8103bdd9: xen_smp_intr_init_pv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int xen_smp_intr_init_pv(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/smp_pv.c (0)
Location: arch/x86/xen/smp_pv.c:115
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
**Symbols:**

```
ffffffff82051e57-ffffffff82051e6c: xen_smp_intr_init_pv.cold (STB_LOCAL)
ffffffff81044440-ffffffff81044614: xen_smp_intr_init_pv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int xen_smp_intr_init_pv(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/smp_pv.c (0)
Location: arch/x86/xen/smp_pv.c:116
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
**Symbols:**

```
ffffffff820d02cc-ffffffff820d02e1: xen_smp_intr_init_pv.cold (STB_LOCAL)
ffffffff81044590-ffffffff81044764: xen_smp_intr_init_pv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int xen_smp_intr_init_pv(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/xen/smp_pv.c (0)
Location: arch/x86/xen/smp_pv.c:116
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
**Symbols:**

```
ffffffff821aac39-ffffffff821aac4e: xen_smp_intr_init_pv.cold (STB_LOCAL)
ffffffff8104aac0-ffffffff8104ac94: xen_smp_intr_init_pv (STB_GLOBAL)
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
int xen_smp_intr_init_pv(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff8102d4b0)
Location: arch/x86/xen/smp_pv.c:114
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
**Symbols:**

```
ffffffff8102d4b0-ffffffff8102d5bd: xen_smp_intr_init_pv (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int xen_smp_intr_init_pv(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff8102d310)
Location: arch/x86/xen/smp_pv.c:114
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
**Symbols:**

```
ffffffff8102d310-ffffffff8102d41d: xen_smp_intr_init_pv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int xen_smp_intr_init_pv(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff8102e100)
Location: arch/x86/xen/smp_pv.c:114
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
**Symbols:**

```
ffffffff8102e100-ffffffff8102e20d: xen_smp_intr_init_pv (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
