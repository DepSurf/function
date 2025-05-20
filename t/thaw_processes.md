# Function: <code>thaw_processes</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void thaw_processes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/process.c (ffffffff810cdbe0)
Location: kernel/power/process.c:183
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_release
  - kernel/kexec_core.c:kernel_kexec
  - drivers/xen/manage.c:do_suspend
```
**Symbols:**

```
ffffffff810cdbe0-ffffffff810cddd4: thaw_processes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void thaw_processes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/process.c (ffffffff810d2720)
Location: kernel/power/process.c:196
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_release
  - kernel/kexec_core.c:kernel_kexec
  - drivers/xen/manage.c:do_suspend
```
**Symbols:**

```
ffffffff810d2720-ffffffff810d290f: thaw_processes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void thaw_processes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/process.c (ffffffff810d92d0)
Location: kernel/power/process.c:185
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_release
  - kernel/kexec_core.c:kernel_kexec
  - drivers/xen/manage.c:do_suspend
```
**Symbols:**

```
ffffffff810d92d0-ffffffff810d94bf: thaw_processes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void thaw_processes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/process.c (ffffffff810d82c0)
Location: kernel/power/process.c:188
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/suspend.c:pm_suspend
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_release
  - kernel/kexec_core.c:kernel_kexec
  - drivers/xen/manage.c:do_suspend
```
**Symbols:**

```
ffffffff810d82c0-ffffffff810d8486: thaw_processes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void thaw_processes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/process.c (ffffffff810e03b0)
Location: kernel/power/process.c:189
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_release
  - kernel/kexec_core.c:kernel_kexec
  - drivers/xen/manage.c:do_suspend
```
**Symbols:**

```
ffffffff810e03b0-ffffffff810e057c: thaw_processes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void thaw_processes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/process.c (ffffffff810e8950)
Location: kernel/power/process.c:189
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_release
  - kernel/kexec_core.c:kernel_kexec
  - drivers/xen/manage.c:do_suspend
```
**Symbols:**

```
ffffffff810e8950-ffffffff810e8b1c: thaw_processes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void thaw_processes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/process.c (ffffffff810f3f60)
Location: kernel/power/process.c:189
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_release
  - kernel/kexec_core.c:kernel_kexec
  - drivers/xen/manage.c:do_suspend
```
**Symbols:**

```
ffffffff810f3f60-ffffffff810f412c: thaw_processes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void thaw_processes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/process.c (0)
Location: kernel/power/process.c:189
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_release
  - kernel/kexec_core.c:kernel_kexec
  - drivers/xen/manage.c:do_suspend
```
**Symbols:**

```
ffffffff810fc7db-ffffffff810fc806: thaw_processes.cold (STB_LOCAL)
ffffffff810fc360-ffffffff810fc53d: thaw_processes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void thaw_processes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/process.c (ffffffff81108780)
Location: kernel/power/process.c:189
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_release
  - kernel/kexec_core.c:kernel_kexec
  - drivers/xen/manage.c:do_suspend
```
**Symbols:**

```
ffffffff81108780-ffffffff8110895a: thaw_processes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void thaw_processes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/process.c (ffffffff81113380)
Location: kernel/power/process.c:189
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:suspend_prepare
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_release
  - kernel/kexec_core.c:kernel_kexec
  - drivers/xen/manage.c:do_suspend
```
**Symbols:**

```
ffffffff81113380-ffffffff8111355e: thaw_processes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void thaw_processes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/process.c (ffffffff811103d0)
Location: kernel/power/process.c:189
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:suspend_prepare
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_release
  - kernel/kexec_core.c:kernel_kexec
  - drivers/xen/manage.c:do_suspend
```
**Symbols:**

```
ffffffff811103d0-ffffffff8111058a: thaw_processes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void thaw_processes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/process.c (ffffffff81110e10)
Location: kernel/power/process.c:189
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_release
  - kernel/kexec_core.c:kernel_kexec
  - drivers/xen/manage.c:do_suspend
```
**Symbols:**

```
ffffffff81110e10-ffffffff81110fca: thaw_processes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void thaw_processes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/process.c (0)
Location: kernel/power/process.c:189
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_release
  - kernel/kexec_core.c:kernel_kexec
  - drivers/xen/manage.c:do_suspend
```
**Symbols:**

```
ffffffff81ca99c6-ffffffff81ca99da: thaw_processes.cold (STB_LOCAL)
ffffffff811308f0-ffffffff81130ab3: thaw_processes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void thaw_processes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/process.c (0)
Location: kernel/power/process.c:186
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_release
  - kernel/kexec_core.c:kernel_kexec
  - drivers/xen/manage.c:do_suspend
```
**Symbols:**

```
ffffffff81e598e5-ffffffff81e598f9: thaw_processes.cold (STB_LOCAL)
ffffffff81152160-ffffffff81152353: thaw_processes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void thaw_processes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/process.c (0)
Location: kernel/power/process.c:179
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_release
  - kernel/kexec_core.c:kernel_kexec
  - drivers/xen/manage.c:do_suspend
```
**Symbols:**

```
ffffffff8205838d-ffffffff820583a1: thaw_processes.cold (STB_LOCAL)
ffffffff811811b0-ffffffff811813b1: thaw_processes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void thaw_processes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/process.c (0)
Location: kernel/power/process.c:179
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_release
  - kernel/kexec_core.c:kernel_kexec
  - drivers/xen/manage.c:do_suspend
```
**Symbols:**

```
ffffffff820d6c9d-ffffffff820d6cb1: thaw_processes.cold (STB_LOCAL)
ffffffff811920b0-ffffffff811922b1: thaw_processes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void thaw_processes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/process.c (0)
Location: kernel/power/process.c:179
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
  - kernel/power/suspend.c:enter_state
  - kernel/power/suspend.c:enter_state
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate_quiet_exec
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_release
  - kernel/kexec_core.c:kernel_kexec
  - drivers/xen/manage.c:do_suspend
```
**Symbols:**

```
ffffffff821b1f33-ffffffff821b1f47: thaw_processes.cold (STB_LOCAL)
ffffffff811a0aa0-ffffffff811a0ca1: thaw_processes (STB_GLOBAL)
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
void thaw_processes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/process.c (ffff80001016fd30)
Location: kernel/power/process.c:189
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffff80001016fd30-ffff80001016fffc: thaw_processes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void thaw_processes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/process.c (c03ba9c4)
Location: kernel/power/process.c:189
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_release
```
**Symbols:**

```
c03ba9c4-c03bac7c: thaw_processes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void thaw_processes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/process.c (c0000000001c7e80)
Location: kernel/power/process.c:189
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
c0000000001c7e80-c0000000001c8164: thaw_processes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void thaw_processes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/process.c (ffffffe00010d7b6)
Location: kernel/power/process.c:189
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
```
**Symbols:**

```
ffffffe00010d7b6-ffffffe00010d9a8: thaw_processes (STB_GLOBAL)
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
void thaw_processes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/process.c (ffffffff811018c0)
Location: kernel/power/process.c:189
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_release
  - kernel/kexec_core.c:kernel_kexec
  - drivers/xen/manage.c:do_suspend
```
**Symbols:**

```
ffffffff811018c0-ffffffff81101a9a: thaw_processes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void thaw_processes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/process.c (ffffffff810f1c80)
Location: kernel/power/process.c:189
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_release
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff810f1c80-ffffffff810f1e5a: thaw_processes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void thaw_processes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/process.c (ffffffff810fec50)
Location: kernel/power/process.c:189
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_release
  - kernel/kexec_core.c:kernel_kexec
  - drivers/xen/manage.c:do_suspend
```
**Symbols:**

```
ffffffff810fec50-ffffffff810fee2a: thaw_processes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void thaw_processes();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/process.c (ffffffff81109f20)
Location: kernel/power/process.c:189
Inline: False
Direct callers:
  - kernel/power/process.c:freeze_processes
  - kernel/power/hibernate.c:software_resume
  - kernel/power/hibernate.c:hibernate
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_ioctl
  - kernel/power/user.c:snapshot_release
  - kernel/kexec_core.c:kernel_kexec
  - drivers/xen/manage.c:do_suspend
```
**Symbols:**

```
ffffffff81109f20-ffffffff8110a12b: thaw_processes (STB_GLOBAL)
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
