# Function: <code>enable_nonboot_cpus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void enable_nonboot_cpus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81081d30)
Location: kernel/cpu.c:623
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff81081d30-ffffffff81081eda: enable_nonboot_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void enable_nonboot_cpus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81084e80)
Location: kernel/cpu.c:1078
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff81084e80-ffffffff81085024: enable_nonboot_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void enable_nonboot_cpus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81089e30)
Location: kernel/cpu.c:1037
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff81089e30-ffffffff81089fcd: enable_nonboot_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void enable_nonboot_cpus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81086cf0)
Location: kernel/cpu.c:949
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff81086cf0-ffffffff81086e93: enable_nonboot_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void enable_nonboot_cpus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8108da90)
Location: kernel/cpu.c:1133
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff8108da90-ffffffff8108dc28: enable_nonboot_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void enable_nonboot_cpus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:1223
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff810918c6-ffffffff81091973: enable_nonboot_cpus.cold.21 (STB_LOCAL)
ffffffff810914d0-ffffffff81091520: enable_nonboot_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void enable_nonboot_cpus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:1240
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff81099ba6-ffffffff81099c53: enable_nonboot_cpus.cold.23 (STB_LOCAL)
ffffffff810997b0-ffffffff81099800: enable_nonboot_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void enable_nonboot_cpus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:1266
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff8109e1b6-ffffffff8109e268: enable_nonboot_cpus.cold (STB_LOCAL)
ffffffff8109db30-ffffffff8109db80: enable_nonboot_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void enable_nonboot_cpus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:1281
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff810a4713-ffffffff810a47c5: enable_nonboot_cpus.cold (STB_LOCAL)
ffffffff810a4080-ffffffff810a40d0: enable_nonboot_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
void enable_nonboot_cpus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffff8000100f9db0)
Location: kernel/cpu.c:1281
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
```
**Symbols:**

```
ffff8000100f9db0-ffff8000100f9edc: enable_nonboot_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void enable_nonboot_cpus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c0358018)
Location: kernel/cpu.c:1281
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_snapshot
```
**Symbols:**

```
c0358018-c0358120: enable_nonboot_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void enable_nonboot_cpus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c000000000140e50)
Location: kernel/cpu.c:1281
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
```
**Symbols:**

```
c000000000140e50-c000000000140fd4: enable_nonboot_cpus (STB_GLOBAL)
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
void enable_nonboot_cpus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:1281
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff8109e033-ffffffff8109e0e5: enable_nonboot_cpus.cold (STB_LOCAL)
ffffffff8109d9a0-ffffffff8109d9f0: enable_nonboot_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void enable_nonboot_cpus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:1281
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff8108ca53-ffffffff8108cb05: enable_nonboot_cpus.cold (STB_LOCAL)
ffffffff8108c3c0-ffffffff8108c410: enable_nonboot_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void enable_nonboot_cpus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:1281
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff8109dfe3-ffffffff8109e095: enable_nonboot_cpus.cold (STB_LOCAL)
ffffffff8109d950-ffffffff8109d9a0: enable_nonboot_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void enable_nonboot_cpus();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cpu.c (0)
Location: kernel/cpu.c:1281
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff810a5f04-ffffffff810a5fb6: enable_nonboot_cpus.cold (STB_LOCAL)
ffffffff810a57e0-ffffffff810a5830: enable_nonboot_cpus (STB_GLOBAL)
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
