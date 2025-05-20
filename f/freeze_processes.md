# Function: <code>freeze_processes</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int freeze_processes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/process.c (ffffffff810cdde0)
Location: kernel/power/process.c:118
Inline: False
Direct callers:
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/hibernate.c:hibernate
  - kernel/kexec_core.c:kernel_kexec
  - drivers/xen/manage.c:do_suspend
```
**Symbols:**

```
ffffffff810cdde0-ffffffff810cdeb0: freeze_processes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int freeze_processes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/process.c (ffffffff810d2910)
Location: kernel/power/process.c:119
Inline: False
Direct callers:
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/kexec_core.c:kernel_kexec
  - drivers/xen/manage.c:do_suspend
```
**Symbols:**

```
ffffffff810d2910-ffffffff810d2a08: freeze_processes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int freeze_processes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/process.c (ffffffff810d94c0)
Location: kernel/power/process.c:119
Inline: False
Direct callers:
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/kexec_core.c:kernel_kexec
  - drivers/xen/manage.c:do_suspend
```
**Symbols:**

```
ffffffff810d94c0-ffffffff810d959e: freeze_processes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int freeze_processes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/process.c (ffffffff810d8490)
Location: kernel/power/process.c:122
Inline: False
Direct callers:
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
  - kernel/kexec_core.c:kernel_kexec
  - drivers/xen/manage.c:do_suspend
```
**Symbols:**

```
ffffffff810d8490-ffffffff810d8573: freeze_processes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int freeze_processes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/process.c (ffffffff810e0580)
Location: kernel/power/process.c:123
Inline: False
Direct callers:
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
  - kernel/kexec_core.c:kernel_kexec
  - drivers/xen/manage.c:do_suspend
```
**Symbols:**

```
ffffffff810e0580-ffffffff810e0663: freeze_processes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int freeze_processes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/process.c (0)
Location: kernel/power/process.c:123
Inline: False
Direct callers:
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
  - kernel/kexec_core.c:kernel_kexec
  - drivers/xen/manage.c:do_suspend
```
**Symbols:**

```
ffffffff810e8ca2-ffffffff810e8ce8: freeze_processes.cold.6 (STB_LOCAL)
ffffffff810e8b20-ffffffff810e8bca: freeze_processes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int freeze_processes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/process.c (0)
Location: kernel/power/process.c:123
Inline: False
Direct callers:
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
  - kernel/kexec_core.c:kernel_kexec
  - drivers/xen/manage.c:do_suspend
```
**Symbols:**

```
ffffffff810f429d-ffffffff810f42e7: freeze_processes.cold.7 (STB_LOCAL)
ffffffff810f4130-ffffffff810f41bb: freeze_processes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int freeze_processes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/process.c (0)
Location: kernel/power/process.c:123
Inline: False
Direct callers:
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
  - kernel/kexec_core.c:kernel_kexec
  - drivers/xen/manage.c:do_suspend
```
**Symbols:**

```
ffffffff810fc806-ffffffff810fc84d: freeze_processes.cold (STB_LOCAL)
ffffffff810fc540-ffffffff810fc5f1: freeze_processes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int freeze_processes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/process.c (0)
Location: kernel/power/process.c:123
Inline: False
Direct callers:
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
  - kernel/kexec_core.c:kernel_kexec
  - drivers/xen/manage.c:do_suspend
```
**Symbols:**

```
ffffffff81108bfb-ffffffff81108c42: freeze_processes.cold (STB_LOCAL)
ffffffff81108960-ffffffff81108a11: freeze_processes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int freeze_processes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/process.c (0)
Location: kernel/power/process.c:123
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_prepare
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
  - kernel/kexec_core.c:kernel_kexec
  - drivers/xen/manage.c:do_suspend
```
**Symbols:**

```
ffffffff811137f5-ffffffff8111383c: freeze_processes.cold (STB_LOCAL)
ffffffff81113560-ffffffff81113613: freeze_processes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int freeze_processes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/process.c (0)
Location: kernel/power/process.c:123
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_prepare
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
  - kernel/kexec_core.c:kernel_kexec
  - drivers/xen/manage.c:do_suspend
```
**Symbols:**

```
ffffffff81bdeb28-ffffffff81bdeb6f: freeze_processes.cold (STB_LOCAL)
ffffffff81110590-ffffffff81110643: freeze_processes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int freeze_processes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/process.c (0)
Location: kernel/power/process.c:123
Inline: False
Direct callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
  - kernel/kexec_core.c:kernel_kexec
  - drivers/xen/manage.c:do_suspend
```
**Symbols:**

```
ffffffff81bd0ca1-ffffffff81bd0ce8: freeze_processes.cold (STB_LOCAL)
ffffffff81110fd0-ffffffff81111083: freeze_processes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int freeze_processes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/process.c (0)
Location: kernel/power/process.c:123
Inline: False
Direct callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
  - kernel/kexec_core.c:kernel_kexec
  - drivers/xen/manage.c:do_suspend
```
**Symbols:**

```
ffffffff81ca99da-ffffffff81ca9a36: freeze_processes.cold (STB_LOCAL)
ffffffff81130ac0-ffffffff81130b7f: freeze_processes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int freeze_processes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/process.c (0)
Location: kernel/power/process.c:120
Inline: False
Direct callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
  - kernel/kexec_core.c:kernel_kexec
  - drivers/xen/manage.c:do_suspend
```
**Symbols:**

```
ffffffff81e598f9-ffffffff81e59953: freeze_processes.cold (STB_LOCAL)
ffffffff81152360-ffffffff8115241d: freeze_processes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int freeze_processes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/process.c (0)
Location: kernel/power/process.c:121
Inline: False
Direct callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
  - kernel/kexec_core.c:kernel_kexec
  - drivers/xen/manage.c:do_suspend
```
**Symbols:**

```
ffffffff820583a1-ffffffff820583b5: freeze_processes.cold (STB_LOCAL)
ffffffff811813d0-ffffffff81181499: freeze_processes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int freeze_processes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/process.c (0)
Location: kernel/power/process.c:121
Inline: False
Direct callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
  - kernel/kexec_core.c:kernel_kexec
  - drivers/xen/manage.c:do_suspend
```
**Symbols:**

```
ffffffff820d6cb1-ffffffff820d6cc5: freeze_processes.cold (STB_LOCAL)
ffffffff811922d0-ffffffff81192399: freeze_processes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int freeze_processes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/process.c (0)
Location: kernel/power/process.c:121
Inline: False
Direct callers:
  - kernel/power/suspend.c:enter_state
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
  - kernel/kexec_core.c:kernel_kexec
  - drivers/xen/manage.c:do_suspend
```
**Symbols:**

```
ffffffff821b1f47-ffffffff821b1f5b: freeze_processes.cold (STB_LOCAL)
ffffffff811a0cc0-ffffffff811a0d89: freeze_processes (STB_GLOBAL)
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
int freeze_processes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/process.c (ffff800010170000)
Location: kernel/power/process.c:123
Inline: False
```
**Symbols:**

```
ffff800010170000-ffff800010170114: freeze_processes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int freeze_processes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/process.c (c03bac7c)
Location: kernel/power/process.c:123
Inline: False
Direct callers:
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
```
**Symbols:**

```
c03bac7c-c03badac: freeze_processes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int freeze_processes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/process.c (c0000000001c8170)
Location: kernel/power/process.c:123
Inline: False
```
**Symbols:**

```
c0000000001c8170-c0000000001c82b0: freeze_processes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int freeze_processes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/process.c (ffffffe00010d9a8)
Location: kernel/power/process.c:123
Inline: False
```
**Symbols:**

```
ffffffe00010d9a8-ffffffe00010da9e: freeze_processes (STB_GLOBAL)
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
int freeze_processes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/process.c (0)
Location: kernel/power/process.c:123
Inline: False
Direct callers:
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
  - kernel/kexec_core.c:kernel_kexec
  - drivers/xen/manage.c:do_suspend
```
**Symbols:**

```
ffffffff81101d3b-ffffffff81101d82: freeze_processes.cold (STB_LOCAL)
ffffffff81101aa0-ffffffff81101b51: freeze_processes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int freeze_processes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/process.c (0)
Location: kernel/power/process.c:123
Inline: False
Direct callers:
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff810f20fb-ffffffff810f2142: freeze_processes.cold (STB_LOCAL)
ffffffff810f1e60-ffffffff810f1f11: freeze_processes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int freeze_processes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/process.c (0)
Location: kernel/power/process.c:123
Inline: False
Direct callers:
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
  - kernel/kexec_core.c:kernel_kexec
  - drivers/xen/manage.c:do_suspend
```
**Symbols:**

```
ffffffff810ff0cb-ffffffff810ff112: freeze_processes.cold (STB_LOCAL)
ffffffff810fee30-ffffffff810feee1: freeze_processes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int freeze_processes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/process.c (0)
Location: kernel/power/process.c:123
Inline: False
Direct callers:
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
  - kernel/kexec_core.c:kernel_kexec
  - drivers/xen/manage.c:do_suspend
```
**Symbols:**

```
ffffffff8110a3d0-ffffffff8110a417: freeze_processes.cold (STB_LOCAL)
ffffffff8110a130-ffffffff8110a1e1: freeze_processes (STB_GLOBAL)
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
