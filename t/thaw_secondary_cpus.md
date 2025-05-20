# Function: <code>thaw_secondary_cpus</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void thaw_secondary_cpus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:1412
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:resume_target_kernel
  - kernel/power/hibernate.c:resume_target_kernel
  - kernel/power/hibernate.c:resume_target_kernel
  - kernel/power/hibernate.c:create_image
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff810aba1b-ffffffff810abacd: thaw_secondary_cpus.cold (STB_LOCAL)
ffffffff810ab2f0-ffffffff810ab340: thaw_secondary_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void thaw_secondary_cpus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:1416
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:resume_target_kernel
  - kernel/power/hibernate.c:resume_target_kernel
  - kernel/power/hibernate.c:resume_target_kernel
  - kernel/power/hibernate.c:create_image
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff81bdb65d-ffffffff81bdb70f: thaw_secondary_cpus.cold (STB_LOCAL)
ffffffff810a6b70-ffffffff810a6bc0: thaw_secondary_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void thaw_secondary_cpus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:1520
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_restore
  - kernel/power/hibernate.c:hibernation_restore
  - kernel/power/hibernate.c:hibernation_restore
  - kernel/power/hibernate.c:create_image
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff81bcd74f-ffffffff81bcd801: thaw_secondary_cpus.cold (STB_LOCAL)
ffffffff810a7c30-ffffffff810a7c80: thaw_secondary_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void thaw_secondary_cpus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:1550
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_restore
  - kernel/power/hibernate.c:hibernation_restore
  - kernel/power/hibernate.c:hibernation_restore
  - kernel/power/hibernate.c:create_image
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff81ca4090-ffffffff81ca4142: thaw_secondary_cpus.cold (STB_LOCAL)
ffffffff810b9690-ffffffff810b96e0: thaw_secondary_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void thaw_secondary_cpus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:1562
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:resume_target_kernel
  - kernel/power/hibernate.c:resume_target_kernel
  - kernel/power/hibernate.c:resume_target_kernel
  - kernel/power/hibernate.c:create_image
  - kernel/power/hibernate.c:create_image
  - kernel/power/hibernate.c:create_image
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff81e53934-ffffffff81e539de: thaw_secondary_cpus.cold (STB_LOCAL)
ffffffff810d00b0-ffffffff810d0108: thaw_secondary_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void thaw_secondary_cpus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810ee740)
Location: kernel/cpu.c:1586
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:resume_target_kernel
  - kernel/power/hibernate.c:resume_target_kernel
  - kernel/power/hibernate.c:resume_target_kernel
  - kernel/power/hibernate.c:create_image
  - kernel/power/hibernate.c:create_image
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff810ee740-ffffffff810ee8ef: thaw_secondary_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void thaw_secondary_cpus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810fa720)
Location: kernel/cpu.c:1946
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:resume_target_kernel
  - kernel/power/hibernate.c:resume_target_kernel
  - kernel/power/hibernate.c:resume_target_kernel
  - kernel/power/hibernate.c:create_image
  - kernel/power/hibernate.c:create_image
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff810fa720-ffffffff810fa8cf: thaw_secondary_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void thaw_secondary_cpus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81103b40)
Location: kernel/cpu.c:1991
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:resume_target_kernel
  - kernel/power/hibernate.c:resume_target_kernel
  - kernel/power/hibernate.c:resume_target_kernel
  - kernel/power/hibernate.c:create_image
  - kernel/power/hibernate.c:create_image
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff81103b40-ffffffff81103cef: thaw_secondary_cpus (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
