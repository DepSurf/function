# Function: <code>syscore_suspend</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int syscore_suspend();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffffffff8154c410)
Location: drivers/base/syscore.c:48
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
ffffffff8154c410-ffffffff8154c630: syscore_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int syscore_suspend();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffffffff8159e1f0)
Location: drivers/base/syscore.c:48
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
ffffffff8159e1f0-ffffffff8159e414: syscore_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int syscore_suspend();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffffffff815cc7a0)
Location: drivers/base/syscore.c:48
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
ffffffff815cc7a0-ffffffff815cc9c4: syscore_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int syscore_suspend();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffffffff815e1330)
Location: drivers/base/syscore.c:48
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
ffffffff815e1330-ffffffff815e1525: syscore_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int syscore_suspend();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffffffff81648460)
Location: drivers/base/syscore.c:48
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
ffffffff81648460-ffffffff81648661: syscore_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int syscore_suspend();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/syscore.c (0)
Location: drivers/base/syscore.c:47
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
ffffffff81683c4d-ffffffff81683c96: syscore_suspend.cold.7 (STB_LOCAL)
ffffffff81683a10-ffffffff81683bc7: syscore_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int syscore_suspend();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/syscore.c (0)
Location: drivers/base/syscore.c:47
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
ffffffff816a391d-ffffffff816a3966: syscore_suspend.cold.8 (STB_LOCAL)
ffffffff816a36e0-ffffffff816a3897: syscore_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int syscore_suspend();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/syscore.c (0)
Location: drivers/base/syscore.c:47
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
ffffffff816dc812-ffffffff816dc85b: syscore_suspend.cold (STB_LOCAL)
ffffffff816dc5f0-ffffffff816dc791: syscore_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int syscore_suspend();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/syscore.c (0)
Location: drivers/base/syscore.c:47
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
ffffffff817008a2-ffffffff817008eb: syscore_suspend.cold (STB_LOCAL)
ffffffff81700680-ffffffff81700821: syscore_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int syscore_suspend();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/syscore.c (0)
Location: drivers/base/syscore.c:47
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
ffffffff817ba7d0-ffffffff817ba819: syscore_suspend.cold (STB_LOCAL)
ffffffff817ba460-ffffffff817ba601: syscore_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int syscore_suspend();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/syscore.c (0)
Location: drivers/base/syscore.c:47
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
ffffffff81c0e444-ffffffff81c0e478: syscore_suspend.cold (STB_LOCAL)
ffffffff817cf170-ffffffff817cf2ee: syscore_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int syscore_suspend();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/syscore.c (0)
Location: drivers/base/syscore.c:47
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
ffffffff81c00844-ffffffff81c00878: syscore_suspend.cold (STB_LOCAL)
ffffffff817b2b80-ffffffff817b2cfe: syscore_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int syscore_suspend();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/syscore.c (0)
Location: drivers/base/syscore.c:47
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
ffffffff81d0311b-ffffffff81d03178: syscore_suspend.cold (STB_LOCAL)
ffffffff8183c020-ffffffff8183c1b6: syscore_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int syscore_suspend();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/syscore.c (0)
Location: drivers/base/syscore.c:47
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
ffffffff81ecb842-ffffffff81ecb8f5: syscore_suspend.cold (STB_LOCAL)
ffffffff8197e980-ffffffff8197eb95: syscore_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int syscore_suspend();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/syscore.c (0)
Location: drivers/base/syscore.c:47
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
ffffffff82098674-ffffffff820986ca: syscore_suspend.cold (STB_LOCAL)
ffffffff81aebf80-ffffffff81aec231: syscore_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int syscore_suspend();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/syscore.c (0)
Location: drivers/base/syscore.c:47
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
ffffffff8211968d-ffffffff821196b6: syscore_suspend.cold (STB_LOCAL)
ffffffff81b3a1a0-ffffffff81b3a429: syscore_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int syscore_suspend();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/syscore.c (0)
Location: drivers/base/syscore.c:47
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
ffffffff821f7650-ffffffff821f7679: syscore_suspend.cold (STB_LOCAL)
ffffffff81b91c60-ffffffff81b91ee9: syscore_suspend (STB_GLOBAL)
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
int syscore_suspend();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (ffff8000108eb9d8)
Location: drivers/base/syscore.c:47
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_enter
```
**Symbols:**

```
ffff8000108eb9d8-ffff8000108ebc5c: syscore_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int syscore_suspend();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (c09d9a10)
Location: drivers/base/syscore.c:47
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_snapshot
```
**Symbols:**

```
c09d9a10-c09d9cdc: syscore_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int syscore_suspend();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/syscore.c (c000000000983160)
Location: drivers/base/syscore.c:47
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
```
**Symbols:**

```
c000000000983160-c000000000983498: syscore_suspend (STB_GLOBAL)
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
int syscore_suspend();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/syscore.c (0)
Location: drivers/base/syscore.c:47
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/kexec_core.c:kernel_kexec
  - drivers/xen/manage.c:xen_suspend
```
**Symbols:**

```
ffffffff816c6092-ffffffff816c60db: syscore_suspend.cold (STB_LOCAL)
ffffffff816c5e70-ffffffff816c6011: syscore_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int syscore_suspend();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/syscore.c (0)
Location: drivers/base/syscore.c:47
Inline: False
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
  - kernel/power/hibernate.c:hibernation_platform_enter
  - kernel/power/hibernate.c:hibernation_snapshot
  - kernel/kexec_core.c:kernel_kexec
```
**Symbols:**

```
ffffffff816a12f2-ffffffff816a133b: syscore_suspend.cold (STB_LOCAL)
ffffffff816a10e0-ffffffff816a1277: syscore_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int syscore_suspend();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/syscore.c (0)
Location: drivers/base/syscore.c:47
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
ffffffff816f4562-ffffffff816f45ab: syscore_suspend.cold (STB_LOCAL)
ffffffff816f4340-ffffffff816f44e1: syscore_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int syscore_suspend();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/syscore.c (0)
Location: drivers/base/syscore.c:47
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
ffffffff8170edf2-ffffffff8170ee3b: syscore_suspend.cold (STB_LOCAL)
ffffffff8170eba0-ffffffff8170ed71: syscore_suspend (STB_GLOBAL)
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
