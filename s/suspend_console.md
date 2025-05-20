# Function: <code>suspend_console</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void suspend_console();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810d9ac0)
Location: kernel/printk/printk.c:2087
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff810d9ac0-ffffffff810d9afc: suspend_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void suspend_console();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810dec80)
Location: kernel/printk/printk.c:2157
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff810dec80-ffffffff810decbc: suspend_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void suspend_console();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e51e0)
Location: kernel/printk/printk.c:2041
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff810e51e0-ffffffff810e521c: suspend_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void suspend_console();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e44c0)
Location: kernel/printk/printk.c:2009
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff810e44c0-ffffffff810e44f6: suspend_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void suspend_console();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810ec770)
Location: kernel/printk/printk.c:1997
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff810ec770-ffffffff810ec7a6: suspend_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void suspend_console();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:2171
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff810f4fd8-ffffffff810f4ffd: suspend_console.cold.36 (STB_LOCAL)
ffffffff810f4570-ffffffff810f4588: suspend_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void suspend_console();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:2174
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff81100783-ffffffff811007a8: suspend_console.cold.37 (STB_LOCAL)
ffffffff810ffd20-ffffffff810ffd38: suspend_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void suspend_console();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:2229
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff81108f67-ffffffff81108f8c: suspend_console.cold (STB_LOCAL)
ffffffff81108470-ffffffff81108488: suspend_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void suspend_console();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:2239
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff81115349-ffffffff8111536e: suspend_console.cold (STB_LOCAL)
ffffffff81114850-ffffffff81114868: suspend_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void suspend_console();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:2259
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_restore
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff81120dbb-ffffffff81120de0: suspend_console.cold (STB_LOCAL)
ffffffff81120580-ffffffff81120598: suspend_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void suspend_console();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:2343
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_restore
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff81be13c7-ffffffff81be13ec: suspend_console.cold (STB_LOCAL)
ffffffff8111b520-ffffffff8111b538: suspend_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void suspend_console();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:2412
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_restore
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff81bd344a-ffffffff81bd3470: suspend_console.cold (STB_LOCAL)
ffffffff8111bc00-ffffffff8111bc13: suspend_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void suspend_console();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:2473
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_restore
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff81cac487-ffffffff81cac4c0: suspend_console.cold (STB_LOCAL)
ffffffff8113bc10-ffffffff8113bc39: suspend_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void suspend_console();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:2516
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_restore
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff81e5cac2-ffffffff81e5cb0c: suspend_console.cold (STB_LOCAL)
ffffffff8115f0e0-ffffffff8115f115: suspend_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void suspend_console();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:2606
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_restore
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff82058b71-ffffffff82058b85: suspend_console.cold (STB_LOCAL)
ffffffff81192180-ffffffff81192210: suspend_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void suspend_console();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:2548
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_restore
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff820d7409-ffffffff820d741d: suspend_console.cold (STB_LOCAL)
ffffffff811a3a20-ffffffff811a3ab0: suspend_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void suspend_console();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:2540
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_restore
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff821b269f-ffffffff821b26b3: suspend_console.cold (STB_LOCAL)
ffffffff811b2930-ffffffff811b29d0: suspend_console (STB_GLOBAL)
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
void suspend_console();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffff800010175778)
Location: kernel/printk/printk.c:2239
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
```
**Symbols:**

```
ffff800010175778-ffff8000101757c0: suspend_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void suspend_console();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (c03c7a00)
Location: kernel/printk/printk.c:2239
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_snapshot
```
**Symbols:**

```
c03c7a00-c03c7a50: suspend_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void suspend_console();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (c0000000001cf050)
Location: kernel/printk/printk.c:2239
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
```
**Symbols:**

```
c0000000001cf050-c0000000001cf0a8: suspend_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void suspend_console();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffe000110f48)
Location: kernel/printk/printk.c:2239
Inline: False
```
**Symbols:**

```
ffffffe000110f48-ffffffe000110f98: suspend_console (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void suspend_console();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:2239
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff8110d929-ffffffff8110d94e: suspend_console.cold (STB_LOCAL)
ffffffff8110ce30-ffffffff8110ce48: suspend_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void suspend_console();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:2239
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff810fe689-ffffffff810fe6ae: suspend_console.cold (STB_LOCAL)
ffffffff810fdc00-ffffffff810fdc18: suspend_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void suspend_console();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:2239
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff8110b819-ffffffff8110b83e: suspend_console.cold (STB_LOCAL)
ffffffff8110ad20-ffffffff8110ad38: suspend_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void suspend_console();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:2239
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff81116d09-ffffffff81116d54: suspend_console.cold (STB_LOCAL)
ffffffff81116130-ffffffff81116148: suspend_console (STB_GLOBAL)
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
