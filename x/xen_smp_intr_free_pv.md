# Function: <code>xen_smp_intr_free_pv</code>

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
void xen_smp_intr_free_pv(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff810298f0)
Location: arch/x86/xen/smp_pv.c:89
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
```
**Symbols:**

```
ffffffff810298f0-ffffffff810299ad: xen_smp_intr_free_pv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void xen_smp_intr_free_pv(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff81029b10)
Location: arch/x86/xen/smp_pv.c:91
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
```
**Symbols:**

```
ffffffff81029b10-ffffffff81029bcd: xen_smp_intr_free_pv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void xen_smp_intr_free_pv(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff8102a5b0)
Location: arch/x86/xen/smp_pv.c:94
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
```
**Symbols:**

```
ffffffff8102a5b0-ffffffff8102a66d: xen_smp_intr_free_pv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xen_smp_intr_free_pv(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff8102abf0)
Location: arch/x86/xen/smp_pv.c:96
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
```
**Symbols:**

```
ffffffff8102abf0-ffffffff8102acad: xen_smp_intr_free_pv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void xen_smp_intr_free_pv(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff8102c9c0)
Location: arch/x86/xen/smp_pv.c:97
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
```
**Symbols:**

```
ffffffff8102c9c0-ffffffff8102ca7d: xen_smp_intr_free_pv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void xen_smp_intr_free_pv(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff8102d290)
Location: arch/x86/xen/smp_pv.c:97
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
```
**Symbols:**

```
ffffffff8102d290-ffffffff8102d34d: xen_smp_intr_free_pv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xen_smp_intr_free_pv(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff8102f3a0)
Location: arch/x86/xen/smp_pv.c:100
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
```
**Symbols:**

```
ffffffff8102f3a0-ffffffff8102f45d: xen_smp_intr_free_pv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xen_smp_intr_free_pv(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff81030140)
Location: arch/x86/xen/smp_pv.c:99
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
```
**Symbols:**

```
ffffffff81030140-ffffffff810301fd: xen_smp_intr_free_pv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xen_smp_intr_free_pv(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff81030c40)
Location: arch/x86/xen/smp_pv.c:99
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
```
**Symbols:**

```
ffffffff81030c40-ffffffff81030cfd: xen_smp_intr_free_pv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xen_smp_intr_free_pv(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff81035bb0)
Location: arch/x86/xen/smp_pv.c:98
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
```
**Symbols:**

```
ffffffff81035bb0-ffffffff81035de1: xen_smp_intr_free_pv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xen_smp_intr_free_pv(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff8103b9e0)
Location: arch/x86/xen/smp_pv.c:98
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
```
**Symbols:**

```
ffffffff8103b9e0-ffffffff8103bc29: xen_smp_intr_free_pv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xen_smp_intr_free_pv(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff810441e0)
Location: arch/x86/xen/smp_pv.c:98
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
```
**Symbols:**

```
ffffffff810441e0-ffffffff8104442c: xen_smp_intr_free_pv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xen_smp_intr_free_pv(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff81044330)
Location: arch/x86/xen/smp_pv.c:99
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
```
**Symbols:**

```
ffffffff81044330-ffffffff8104457c: xen_smp_intr_free_pv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xen_smp_intr_free_pv(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff8104a860)
Location: arch/x86/xen/smp_pv.c:99
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
```
**Symbols:**

```
ffffffff8104a860-ffffffff8104aaac: xen_smp_intr_free_pv (STB_GLOBAL)
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
void xen_smp_intr_free_pv(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff8102d3f0)
Location: arch/x86/xen/smp_pv.c:97
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
```
**Symbols:**

```
ffffffff8102d3f0-ffffffff8102d4ad: xen_smp_intr_free_pv (STB_GLOBAL)
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
void xen_smp_intr_free_pv(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff8102d250)
Location: arch/x86/xen/smp_pv.c:97
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
```
**Symbols:**

```
ffffffff8102d250-ffffffff8102d30d: xen_smp_intr_free_pv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void xen_smp_intr_free_pv(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff8102e040)
Location: arch/x86/xen/smp_pv.c:97
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
```
**Symbols:**

```
ffffffff8102e040-ffffffff8102e0fd: xen_smp_intr_free_pv (STB_GLOBAL)
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
