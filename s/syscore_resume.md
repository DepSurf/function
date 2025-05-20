# Function: <code>syscore_resume</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void syscore_resume();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffffffff8154c280)
Location: drivers/base/syscore.c:93
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/kexec_core.c:kernel_kexec
  - drivers/xen/manage.c:xen_suspend
```
**Symbols:**

```
ffffffff8154c280-ffffffff8154c406: syscore_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void syscore_resume();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffffffff8159e070)
Location: drivers/base/syscore.c:93
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/kexec_core.c:kernel_kexec
  - drivers/xen/manage.c:xen_suspend
```
**Symbols:**

```
ffffffff8159e070-ffffffff8159e1eb: syscore_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void syscore_resume();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffffffff815cc620)
Location: drivers/base/syscore.c:93
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/kexec_core.c:kernel_kexec
  - drivers/xen/manage.c:xen_suspend
```
**Symbols:**

```
ffffffff815cc620-ffffffff815cc79b: syscore_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void syscore_resume();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffffffff815e11c0)
Location: drivers/base/syscore.c:93
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/kexec_core.c:kernel_kexec
  - drivers/xen/manage.c:xen_suspend
```
**Symbols:**

```
ffffffff815e11c0-ffffffff815e132e: syscore_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void syscore_resume();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffffffff816482e0)
Location: drivers/base/syscore.c:93
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/kexec_core.c:kernel_kexec
  - drivers/xen/manage.c:xen_suspend
```
**Symbols:**

```
ffffffff816482e0-ffffffff81648457: syscore_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void syscore_resume();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/syscore.c (0)
Location: drivers/base/syscore.c:92
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/kexec_core.c:kernel_kexec
  - drivers/xen/manage.c:xen_suspend
```
**Symbols:**

```
ffffffff81683c38-ffffffff81683c4d: syscore_resume.cold.6 (STB_LOCAL)
ffffffff816838b0-ffffffff81683a0b: syscore_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void syscore_resume();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/syscore.c (0)
Location: drivers/base/syscore.c:92
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/kexec_core.c:kernel_kexec
  - drivers/xen/manage.c:xen_suspend
```
**Symbols:**

```
ffffffff816a3908-ffffffff816a391d: syscore_resume.cold.7 (STB_LOCAL)
ffffffff816a3580-ffffffff816a36db: syscore_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void syscore_resume();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/syscore.c (0)
Location: drivers/base/syscore.c:92
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/kexec_core.c:kernel_kexec
  - drivers/xen/manage.c:xen_suspend
```
**Symbols:**

```
ffffffff816dc7fd-ffffffff816dc812: syscore_resume.cold (STB_LOCAL)
ffffffff816dc490-ffffffff816dc5e8: syscore_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void syscore_resume();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/syscore.c (0)
Location: drivers/base/syscore.c:92
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/kexec_core.c:kernel_kexec
  - drivers/xen/manage.c:xen_suspend
```
**Symbols:**

```
ffffffff8170088d-ffffffff817008a2: syscore_resume.cold (STB_LOCAL)
ffffffff81700520-ffffffff81700678: syscore_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void syscore_resume();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/syscore.c (0)
Location: drivers/base/syscore.c:92
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:resume_target_kernel
  - kernel/power/hibernate.c:create_image
  - kernel/kexec_core.c:kernel_kexec
  - drivers/xen/manage.c:xen_suspend
```
**Symbols:**

```
ffffffff817ba819-ffffffff817ba82e: syscore_resume.cold (STB_LOCAL)
ffffffff817ba610-ffffffff817ba768: syscore_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void syscore_resume();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffffffff817cf2f0)
Location: drivers/base/syscore.c:91
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:resume_target_kernel
  - kernel/power/hibernate.c:create_image
  - kernel/kexec_core.c:kernel_kexec
  - drivers/xen/manage.c:xen_suspend
```
**Symbols:**

```
ffffffff817cf2f0-ffffffff817cf430: syscore_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void syscore_resume();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffffffff817b2d00)
Location: drivers/base/syscore.c:91
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_restore
  - kernel/power/hibernate.c:create_image
  - kernel/kexec_core.c:kernel_kexec
  - drivers/xen/manage.c:xen_suspend
```
**Symbols:**

```
ffffffff817b2d00-ffffffff817b2e40: syscore_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void syscore_resume();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/syscore.c (0)
Location: drivers/base/syscore.c:91
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_restore
  - kernel/power/hibernate.c:create_image
  - kernel/kexec_core.c:kernel_kexec
  - drivers/xen/manage.c:xen_suspend
```
**Symbols:**

```
ffffffff81d03178-ffffffff81d031a1: syscore_resume.cold (STB_LOCAL)
ffffffff8183c1c0-ffffffff8183c311: syscore_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void syscore_resume();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/syscore.c (0)
Location: drivers/base/syscore.c:91
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:resume_target_kernel
  - kernel/power/hibernate.c:create_image
  - kernel/kexec_core.c:kernel_kexec
  - drivers/xen/manage.c:xen_suspend
```
**Symbols:**

```
ffffffff81ecb7e8-ffffffff81ecb842: syscore_resume.cold (STB_LOCAL)
ffffffff8197e7c0-ffffffff8197e977: syscore_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void syscore_resume();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/syscore.c (0)
Location: drivers/base/syscore.c:91
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:resume_target_kernel
  - kernel/power/hibernate.c:create_image
  - kernel/kexec_core.c:kernel_kexec
  - drivers/xen/manage.c:xen_suspend
```
**Symbols:**

```
ffffffff82098632-ffffffff82098674: syscore_resume.cold (STB_LOCAL)
ffffffff81aebd90-ffffffff81aebf61: syscore_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void syscore_resume();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/syscore.c (0)
Location: drivers/base/syscore.c:91
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:resume_target_kernel
  - kernel/power/hibernate.c:create_image
  - kernel/kexec_core.c:kernel_kexec
  - drivers/xen/manage.c:xen_suspend
```
**Symbols:**

```
ffffffff82119664-ffffffff8211968d: syscore_resume.cold (STB_LOCAL)
ffffffff81b39fd0-ffffffff81b3a18e: syscore_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void syscore_resume();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/syscore.c (0)
Location: drivers/base/syscore.c:91
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:resume_target_kernel
  - kernel/power/hibernate.c:create_image
  - kernel/kexec_core.c:kernel_kexec
  - drivers/xen/manage.c:xen_suspend
```
**Symbols:**

```
ffffffff821f7627-ffffffff821f7650: syscore_resume.cold (STB_LOCAL)
ffffffff81b91a90-ffffffff81b91c4e: syscore_resume (STB_GLOBAL)
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
void syscore_resume();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffff8000108eb7e0)
Location: drivers/base/syscore.c:92
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/suspend.c:suspend_enter
```
**Symbols:**

```
ffff8000108eb7e0-ffff8000108eb9d4: syscore_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void syscore_resume();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (c09d97d8)
Location: drivers/base/syscore.c:92
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_snapshot
```
**Symbols:**

```
c09d97d8-c09d9a10: syscore_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void syscore_resume();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (c000000000982ed0)
Location: drivers/base/syscore.c:92
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
```
**Symbols:**

```
c000000000982ed0-c000000000983154: syscore_resume (STB_GLOBAL)
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
void syscore_resume();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/syscore.c (0)
Location: drivers/base/syscore.c:92
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/kexec_core.c:kernel_kexec
  - drivers/xen/manage.c:xen_suspend
```
**Symbols:**

```
ffffffff816c607d-ffffffff816c6092: syscore_resume.cold (STB_LOCAL)
ffffffff816c5d10-ffffffff816c5e68: syscore_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void syscore_resume();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/syscore.c (0)
Location: drivers/base/syscore.c:92
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff816a12dd-ffffffff816a12f2: syscore_resume.cold (STB_LOCAL)
ffffffff816a0f90-ffffffff816a10de: syscore_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void syscore_resume();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/syscore.c (0)
Location: drivers/base/syscore.c:92
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/kexec_core.c:kernel_kexec
  - drivers/xen/manage.c:xen_suspend
```
**Symbols:**

```
ffffffff816f454d-ffffffff816f4562: syscore_resume.cold (STB_LOCAL)
ffffffff816f41e0-ffffffff816f4338: syscore_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void syscore_resume();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/syscore.c (0)
Location: drivers/base/syscore.c:92
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/kexec_core.c:kernel_kexec
  - drivers/xen/manage.c:xen_suspend
```
**Symbols:**

```
ffffffff8170eddd-ffffffff8170edf2: syscore_resume.cold (STB_LOCAL)
ffffffff8170ea10-ffffffff8170eb9a: syscore_resume (STB_GLOBAL)
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
