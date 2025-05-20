# Function: <code>freeze_secondary_cpus</code>

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
<summary>In <code>4.10</code>: ✅</summary>

```c
int freeze_secondary_cpus(int primary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81089c20)
Location: kernel/cpu.c:985
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/kexec_core.c:kernel_kexec
  - arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable
```
**Symbols:**

```
ffffffff81089c20-ffffffff81089e09: freeze_secondary_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int freeze_secondary_cpus(int primary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81086ae0)
Location: kernel/cpu.c:897
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/kexec_core.c:kernel_kexec
  - arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable
```
**Symbols:**

```
ffffffff81086ae0-ffffffff81086ccf: freeze_secondary_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int freeze_secondary_cpus(int primary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8108d890)
Location: kernel/cpu.c:1081
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/kexec_core.c:kernel_kexec
  - arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable
```
**Symbols:**

```
ffffffff8108d890-ffffffff8108da6a: freeze_secondary_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int freeze_secondary_cpus(int primary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:1171
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/kexec_core.c:kernel_kexec
  - arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable
```
**Symbols:**

```
ffffffff81091774-ffffffff810918c6: freeze_secondary_cpus.cold.20 (STB_LOCAL)
ffffffff81091420-ffffffff810914a1: freeze_secondary_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int freeze_secondary_cpus(int primary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:1188
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/kexec_core.c:kernel_kexec
  - arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable
```
**Symbols:**

```
ffffffff81099a54-ffffffff81099ba6: freeze_secondary_cpus.cold.22 (STB_LOCAL)
ffffffff81099700-ffffffff81099781: freeze_secondary_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int freeze_secondary_cpus(int primary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:1200
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/kexec_core.c:kernel_kexec
  - arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable
```
**Symbols:**

```
ffffffff8109e04c-ffffffff8109e1b6: freeze_secondary_cpus.cold (STB_LOCAL)
ffffffff8109da50-ffffffff8109db0c: freeze_secondary_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int freeze_secondary_cpus(int primary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:1215
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/kexec_core.c:kernel_kexec
  - arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable
```
**Symbols:**

```
ffffffff810a45b1-ffffffff810a4713: freeze_secondary_cpus.cold (STB_LOCAL)
ffffffff810a3fa0-ffffffff810a4058: freeze_secondary_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int freeze_secondary_cpus(int primary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:1346
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable
  - kernel/power/hibernate.c:create_image
  - kernel/kexec_core.c:kernel_kexec
  - arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable
```
**Symbols:**

```
ffffffff810ab8b9-ffffffff810aba1b: freeze_secondary_cpus.cold (STB_LOCAL)
ffffffff810ab210-ffffffff810ab2c3: freeze_secondary_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int freeze_secondary_cpus(int primary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:1350
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable
  - kernel/power/hibernate.c:create_image
  - kernel/kexec_core.c:kernel_kexec
  - arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable
```
**Symbols:**

```
ffffffff81bdb52a-ffffffff81bdb65d: freeze_secondary_cpus.cold (STB_LOCAL)
ffffffff810a6aa0-ffffffff810a6b4f: freeze_secondary_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int freeze_secondary_cpus(int primary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:1454
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable
  - kernel/power/hibernate.c:create_image
  - kernel/kexec_core.c:kernel_kexec
  - arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable
```
**Symbols:**

```
ffffffff81bcd61c-ffffffff81bcd74f: freeze_secondary_cpus.cold (STB_LOCAL)
ffffffff810a7b50-ffffffff810a7c04: freeze_secondary_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int freeze_secondary_cpus(int primary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:1484
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable
  - kernel/power/hibernate.c:create_image
  - kernel/kexec_core.c:kernel_kexec
  - arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable
```
**Symbols:**

```
ffffffff81ca3f5d-ffffffff81ca4090: freeze_secondary_cpus.cold (STB_LOCAL)
ffffffff810b95b0-ffffffff810b9661: freeze_secondary_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int freeze_secondary_cpus(int primary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:1496
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable
  - kernel/power/hibernate.c:create_image
  - kernel/kexec_core.c:kernel_kexec
  - arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable
```
**Symbols:**

```
ffffffff81e537ca-ffffffff81e53934: freeze_secondary_cpus.cold (STB_LOCAL)
ffffffff810cffe0-ffffffff810d008a: freeze_secondary_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int freeze_secondary_cpus(int primary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810ee490)
Location: kernel/cpu.c:1520
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable
  - kernel/power/hibernate.c:create_image
  - kernel/kexec_core.c:kernel_kexec
  - arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable
```
**Symbols:**

```
ffffffff810ee490-ffffffff810ee6eb: freeze_secondary_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int freeze_secondary_cpus(int primary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810fa470)
Location: kernel/cpu.c:1880
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable
  - kernel/power/hibernate.c:create_image
  - kernel/kexec_core.c:kernel_kexec
  - arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable
```
**Symbols:**

```
ffffffff810fa470-ffffffff810fa6cb: freeze_secondary_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int freeze_secondary_cpus(int primary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81103890)
Location: kernel/cpu.c:1925
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable
  - kernel/power/hibernate.c:create_image
  - kernel/kexec_core.c:kernel_kexec
  - arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable
```
**Symbols:**

```
ffffffff81103890-ffffffff81103aeb: freeze_secondary_cpus (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int freeze_secondary_cpus(int primary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffff8000100f9ac8)
Location: kernel/cpu.c:1215
Inline: False
Direct callers:
  - arch/arm64/kernel/process.c:machine_shutdown
  - kernel/power/suspend.c:suspend_enter
  - drivers/power/reset/sc27xx-poweroff.c:sc27xx_poweroff_shutdown
```
**Symbols:**

```
ffff8000100f9ac8-ffff8000100f9d7c: freeze_secondary_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int freeze_secondary_cpus(int primary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c0357cf0)
Location: kernel/cpu.c:1215
Inline: False
Direct callers:
  - arch/arm/kernel/reboot.c:machine_shutdown
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable
  - kernel/power/hibernate.c:hibernation_snapshot
```
**Symbols:**

```
c0357cf0-c0357fe8: freeze_secondary_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int freeze_secondary_cpus(int primary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c000000000140aa0)
Location: kernel/cpu.c:1215
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
```
**Symbols:**

```
c000000000140aa0-c000000000140e24: freeze_secondary_cpus (STB_GLOBAL)
```
</details>
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
int freeze_secondary_cpus(int primary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:1215
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/kexec_core.c:kernel_kexec
  - arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable
```
**Symbols:**

```
ffffffff8109ded1-ffffffff8109e033: freeze_secondary_cpus.cold (STB_LOCAL)
ffffffff8109d8c0-ffffffff8109d978: freeze_secondary_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int freeze_secondary_cpus(int primary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:1215
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/kexec_core.c:kernel_kexec
  - arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable
```
**Symbols:**

```
ffffffff8108c8f1-ffffffff8108ca53: freeze_secondary_cpus.cold (STB_LOCAL)
ffffffff8108c2e0-ffffffff8108c398: freeze_secondary_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int freeze_secondary_cpus(int primary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:1215
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/kexec_core.c:kernel_kexec
  - arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable
```
**Symbols:**

```
ffffffff8109de81-ffffffff8109dfe3: freeze_secondary_cpus.cold (STB_LOCAL)
ffffffff8109d870-ffffffff8109d928: freeze_secondary_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int freeze_secondary_cpus(int primary);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:1215
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernate_resume_nonboot_cpu_disable
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/kexec_core.c:kernel_kexec
  - arch/x86/power/cpu.c:hibernate_resume_nonboot_cpu_disable
```
**Symbols:**

```
ffffffff810a5d71-ffffffff810a5f04: freeze_secondary_cpus.cold (STB_LOCAL)
ffffffff810a5700-ffffffff810a57b8: freeze_secondary_cpus (STB_GLOBAL)
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
