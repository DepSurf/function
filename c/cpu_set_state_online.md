# Function: <code>cpu_set_state_online</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void cpu_set_state_online(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810a4000)
Location: kernel/smpboot.c:452
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:cpu_bringup
  - arch/x86/kernel/smpboot.c:start_secondary
  - arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu
```
**Symbols:**

```
ffffffff810a4000-ffffffff810a4024: cpu_set_state_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void cpu_set_state_online(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810a7740)
Location: kernel/smpboot.c:454
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:cpu_bringup
  - arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff810a7740-ffffffff810a7764: cpu_set_state_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cpu_set_state_online(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810ad3f0)
Location: kernel/smpboot.c:459
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:cpu_bringup
  - arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff810ad3f0-ffffffff810ad414: cpu_set_state_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void cpu_set_state_online(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810a9fc0)
Location: kernel/smpboot.c:460
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff810a9fc0-ffffffff810a9fe4: cpu_set_state_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cpu_set_state_online(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810b0820)
Location: kernel/smpboot.c:451
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff810b0820-ffffffff810b0844: cpu_set_state_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void cpu_set_state_online(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810b7640)
Location: kernel/smpboot.c:451
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff810b7640-ffffffff810b7664: cpu_set_state_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cpu_set_state_online(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810c0740)
Location: kernel/smpboot.c:407
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff810c0740-ffffffff810c0764: cpu_set_state_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void cpu_set_state_online(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810c6830)
Location: kernel/smpboot.c:408
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff810c6830-ffffffff810c6854: cpu_set_state_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cpu_set_state_online(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810cf910)
Location: kernel/smpboot.c:408
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff810cf910-ffffffff810cf934: cpu_set_state_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void cpu_set_state_online(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810d9810)
Location: kernel/smpboot.c:408
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff810d9810-ffffffff810d9834: cpu_set_state_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void cpu_set_state_online(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810d49c0)
Location: kernel/smpboot.c:409
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff810d49c0-ffffffff810d49e4: cpu_set_state_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void cpu_set_state_online(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810d65e0)
Location: kernel/smpboot.c:408
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff810d65e0-ffffffff810d6604: cpu_set_state_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void cpu_set_state_online(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810e99a0)
Location: kernel/smpboot.c:408
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff810e99a0-ffffffff810e99e4: cpu_set_state_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void cpu_set_state_online(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff81104620)
Location: kernel/smpboot.c:415
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff81104620-ffffffff8110466e: cpu_set_state_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void cpu_set_state_online(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff81129e60)
Location: kernel/smpboot.c:415
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff81129e60-ffffffff81129eae: cpu_set_state_online (STB_GLOBAL)
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
void cpu_set_state_online(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffff80001012fa98)
Location: kernel/smpboot.c:408
Inline: False
```
**Symbols:**

```
ffff80001012fa98-ffff80001012faf0: cpu_set_state_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cpu_set_state_online(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (c037f618)
Location: kernel/smpboot.c:408
Inline: False
```
**Symbols:**

```
c037f618-c037f668: cpu_set_state_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cpu_set_state_online(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (c000000000179130)
Location: kernel/smpboot.c:408
Inline: False
```
**Symbols:**

```
c000000000179130-c000000000179178: cpu_set_state_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void cpu_set_state_online(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffe0000e34de)
Location: kernel/smpboot.c:408
Inline: False
```
**Symbols:**

```
ffffffe0000e34de-ffffffe0000e351c: cpu_set_state_online (STB_GLOBAL)
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
void cpu_set_state_online(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810c9c90)
Location: kernel/smpboot.c:408
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff810c9c90-ffffffff810c9cb4: cpu_set_state_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cpu_set_state_online(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810b84b0)
Location: kernel/smpboot.c:408
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff810b84b0-ffffffff810b84d4: cpu_set_state_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cpu_set_state_online(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810c91c0)
Location: kernel/smpboot.c:408
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff810c91c0-ffffffff810c91e4: cpu_set_state_online (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cpu_set_state_online(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smpboot.c (ffffffff810d1730)
Location: kernel/smpboot.c:408
Inline: False
Direct callers:
  - arch/x86/xen/smp_pv.c:cpu_bringup
  - arch/x86/kernel/smpboot.c:native_smp_prepare_boot_cpu
  - arch/x86/kernel/smpboot.c:start_secondary
```
**Symbols:**

```
ffffffff810d1730-ffffffff810d1754: cpu_set_state_online (STB_GLOBAL)
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
