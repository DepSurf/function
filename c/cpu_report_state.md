# Function: <code>cpu_report_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int cpu_report_state(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810a3f90)
Location: kernel/smpboot.c:379
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_hvm_cpu_up
  - arch/x86/xen/smp.c:xen_cpu_up
```
**Symbols:**

```
ffffffff810a3f90-ffffffff810a3faf: cpu_report_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int cpu_report_state(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810a76d0)
Location: kernel/smpboot.c:381
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_hvm_cpu_up
  - arch/x86/xen/smp.c:xen_cpu_up
```
**Symbols:**

```
ffffffff810a76d0-ffffffff810a76ef: cpu_report_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int cpu_report_state(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810ad380)
Location: kernel/smpboot.c:386
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_cpu_up_prepare
  - arch/x86/xen/smp.c:xen_cpu_up
```
**Symbols:**

```
ffffffff810ad380-ffffffff810ad39f: cpu_report_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cpu_report_state(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810a9f50)
Location: kernel/smpboot.c:387
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
**Symbols:**

```
ffffffff810a9f50-ffffffff810a9f6f: cpu_report_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cpu_report_state(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810b07b0)
Location: kernel/smpboot.c:378
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
**Symbols:**

```
ffffffff810b07b0-ffffffff810b07cf: cpu_report_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int cpu_report_state(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810b75d0)
Location: kernel/smpboot.c:378
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
**Symbols:**

```
ffffffff810b75d0-ffffffff810b75ef: cpu_report_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cpu_report_state(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810c06d0)
Location: kernel/smpboot.c:334
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
  - arch/x86/xen/smp_pv.c:xen_pv_cpu_up
```
**Symbols:**

```
ffffffff810c06d0-ffffffff810c06ef: cpu_report_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cpu_report_state(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810c67c0)
Location: kernel/smpboot.c:335
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
```
**Symbols:**

```
ffffffff810c67c0-ffffffff810c67df: cpu_report_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cpu_report_state(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810cf8a0)
Location: kernel/smpboot.c:335
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
```
**Symbols:**

```
ffffffff810cf8a0-ffffffff810cf8bf: cpu_report_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cpu_report_state(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810d97a0)
Location: kernel/smpboot.c:335
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
```
**Symbols:**

```
ffffffff810d97a0-ffffffff810d97bf: cpu_report_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cpu_report_state(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810d4950)
Location: kernel/smpboot.c:336
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
```
**Symbols:**

```
ffffffff810d4950-ffffffff810d496f: cpu_report_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cpu_report_state(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810d6570)
Location: kernel/smpboot.c:335
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
```
**Symbols:**

```
ffffffff810d6570-ffffffff810d658f: cpu_report_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cpu_report_state(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810e98c0)
Location: kernel/smpboot.c:335
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
```
**Symbols:**

```
ffffffff810e98c0-ffffffff810e98ff: cpu_report_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cpu_report_state(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff81104500)
Location: kernel/smpboot.c:335
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
```
**Symbols:**

```
ffffffff81104500-ffffffff81104547: cpu_report_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cpu_report_state(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff81129d20)
Location: kernel/smpboot.c:335
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
```
**Symbols:**

```
ffffffff81129d20-ffffffff81129d67: cpu_report_state (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int cpu_report_state(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffff80001012f9d8)
Location: kernel/smpboot.c:335
Inline: False
```
**Symbols:**

```
ffff80001012f9d8-ffff80001012fa18: cpu_report_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cpu_report_state(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (c037f584)
Location: kernel/smpboot.c:335
Inline: False
```
**Symbols:**

```
c037f584-c037f5b4: cpu_report_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cpu_report_state(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (c000000000179080)
Location: kernel/smpboot.c:335
Inline: False
```
**Symbols:**

```
c000000000179080-c0000000001790b4: cpu_report_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cpu_report_state(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffe0000e3464)
Location: kernel/smpboot.c:335
Inline: False
```
**Symbols:**

```
ffffffe0000e3464-ffffffe0000e34a0: cpu_report_state (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int cpu_report_state(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810c9c20)
Location: kernel/smpboot.c:335
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
```
**Symbols:**

```
ffffffff810c9c20-ffffffff810c9c3f: cpu_report_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cpu_report_state(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810b8440)
Location: kernel/smpboot.c:335
Inline: False
```
**Symbols:**

```
ffffffff810b8440-ffffffff810b845f: cpu_report_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cpu_report_state(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810c9150)
Location: kernel/smpboot.c:335
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
```
**Symbols:**

```
ffffffff810c9150-ffffffff810c916f: cpu_report_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cpu_report_state(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810d16c0)
Location: kernel/smpboot.c:335
Inline: False
Direct callers:
  - arch/x86/xen/enlighten_hvm.c:xen_cpu_up_prepare_hvm
```
**Symbols:**

```
ffffffff810d16c0-ffffffff810d16df: cpu_report_state (STB_GLOBAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
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
