# Function: <code>xen_smp_intr_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void xen_smp_intr_free(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8102ae50)
Location: arch/x86/xen/smp.c:118
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_hvm_cpu_up
```
**Symbols:**

```
ffffffff8102ae50-ffffffff8102b070: xen_smp_intr_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void xen_smp_intr_free(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8102a170)
Location: arch/x86/xen/smp.c:118
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_hvm_cpu_up
  - arch/x86/xen/smp.c:xen_smp_intr_init
```
**Symbols:**

```
ffffffff8102a170-ffffffff8102a390: xen_smp_intr_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void xen_smp_intr_free(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8102b090)
Location: arch/x86/xen/smp.c:118
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_cpu_dead
  - arch/x86/xen/enlighten.c:xen_cpu_up_prepare
  - arch/x86/xen/smp.c:xen_smp_intr_init
```
**Symbols:**

```
ffffffff8102b090-ffffffff8102b2b0: xen_smp_intr_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void xen_smp_intr_free(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff81028b20)
Location: arch/x86/xen/smp.c:32
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
```
**Symbols:**

```
ffffffff81028b20-ffffffff81028c87: xen_smp_intr_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void xen_smp_intr_free(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff81028d30)
Location: arch/x86/xen/smp.c:33
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
```
**Symbols:**

```
ffffffff81028d30-ffffffff81028e97: xen_smp_intr_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void xen_smp_intr_free(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff81029780)
Location: arch/x86/xen/smp.c:33
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
```
**Symbols:**

```
ffffffff81029780-ffffffff810298e7: xen_smp_intr_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xen_smp_intr_free(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff81029d60)
Location: arch/x86/xen/smp.c:33
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
```
**Symbols:**

```
ffffffff81029d60-ffffffff81029ec7: xen_smp_intr_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void xen_smp_intr_free(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8102bb10)
Location: arch/x86/xen/smp.c:33
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
```
**Symbols:**

```
ffffffff8102bb10-ffffffff8102bc77: xen_smp_intr_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void xen_smp_intr_free(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8102c3f0)
Location: arch/x86/xen/smp.c:33
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
```
**Symbols:**

```
ffffffff8102c3f0-ffffffff8102c557: xen_smp_intr_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xen_smp_intr_free(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8102e3b0)
Location: arch/x86/xen/smp.c:33
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
```
**Symbols:**

```
ffffffff8102e3b0-ffffffff8102e517: xen_smp_intr_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xen_smp_intr_free(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8102f210)
Location: arch/x86/xen/smp.c:33
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
```
**Symbols:**

```
ffffffff8102f210-ffffffff8102f377: xen_smp_intr_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xen_smp_intr_free(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8102fd20)
Location: arch/x86/xen/smp.c:33
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
```
**Symbols:**

```
ffffffff8102fd20-ffffffff8102fe87: xen_smp_intr_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xen_smp_intr_free(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff81034710)
Location: arch/x86/xen/smp.c:33
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
```
**Symbols:**

```
ffffffff81034710-ffffffff81034b6a: xen_smp_intr_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xen_smp_intr_free(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8103a420)
Location: arch/x86/xen/smp.c:33
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
```
**Symbols:**

```
ffffffff8103a420-ffffffff8103a896: xen_smp_intr_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xen_smp_intr_free(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff81042ae0)
Location: arch/x86/xen/smp.c:33
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
```
**Symbols:**

```
ffffffff81042ae0-ffffffff81042f52: xen_smp_intr_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xen_smp_intr_free(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff81042ce0)
Location: arch/x86/xen/smp.c:33
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_pv_cleanup_dead_cpu
```
**Symbols:**

```
ffffffff81042ce0-ffffffff81043152: xen_smp_intr_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xen_smp_intr_free(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff810491b0)
Location: arch/x86/xen/smp.c:33
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_pv_cleanup_dead_cpu
```
**Symbols:**

```
ffffffff810491b0-ffffffff81049622: xen_smp_intr_free (STB_GLOBAL)
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
void xen_smp_intr_free(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8102c550)
Location: arch/x86/xen/smp.c:33
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
```
**Symbols:**

```
ffffffff8102c550-ffffffff8102c6b7: xen_smp_intr_free (STB_GLOBAL)
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
void xen_smp_intr_free(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8102c3b0)
Location: arch/x86/xen/smp.c:33
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
```
**Symbols:**

```
ffffffff8102c3b0-ffffffff8102c517: xen_smp_intr_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void xen_smp_intr_free(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp.c (ffffffff8102d1a0)
Location: arch/x86/xen/smp.c:33
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/enlighten_pv.c:xen_cpu_dead_pv
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_die
```
**Symbols:**

```
ffffffff8102d1a0-ffffffff8102d307: xen_smp_intr_free (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
