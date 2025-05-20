# Function: <code>device_shutdown</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void device_shutdown();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815492e0)
Location: drivers/base/core.c:2041
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_restart_prepare
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_power_off
```
**Symbols:**

```
ffffffff815492e0-ffffffff81549464: device_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void device_shutdown();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8159af10)
Location: drivers/base/core.c:2041
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart_prepare
```
**Symbols:**

```
ffffffff8159af10-ffffffff8159b0b4: device_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void device_shutdown();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815c9470)
Location: drivers/base/core.c:2632
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart_prepare
```
**Symbols:**

```
ffffffff815c9470-ffffffff815c9614: device_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void device_shutdown();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815de190)
Location: drivers/base/core.c:2630
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart_prepare
```
**Symbols:**

```
ffffffff815de190-ffffffff815de378: device_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void device_shutdown();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81645190)
Location: drivers/base/core.c:2765
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart_prepare
```
**Symbols:**

```
ffffffff81645190-ffffffff81645387: device_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void device_shutdown();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816805d0)
Location: drivers/base/core.c:2817
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart_prepare
```
**Symbols:**

```
ffffffff816805d0-ffffffff816807ce: device_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void device_shutdown();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816a0060)
Location: drivers/base/core.c:2892
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart_prepare
```
**Symbols:**

```
ffffffff816a0060-ffffffff816a025e: device_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void device_shutdown();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (0)
Location: drivers/base/core.c:3146
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart_prepare
```
**Symbols:**

```
ffffffff816d91b3-ffffffff816d920a: device_shutdown.cold (STB_LOCAL)
ffffffff816d87c0-ffffffff816d8949: device_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void device_shutdown();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (0)
Location: drivers/base/core.c:3296
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart_prepare
```
**Symbols:**

```
ffffffff816fd1b2-ffffffff816fd209: device_shutdown.cold (STB_LOCAL)
ffffffff816fc8c0-ffffffff816fca4e: device_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void device_shutdown();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (0)
Location: drivers/base/core.c:3764
Inline: False
Direct callers:
  - kernel/reboot.c:deferred_cad
  - kernel/reboot.c:__do_sys_reboot
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
```
**Symbols:**

```
ffffffff817b6b05-ffffffff817b6b5c: device_shutdown.cold (STB_LOCAL)
ffffffff817b6260-ffffffff817b6411: device_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void device_shutdown();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (0)
Location: drivers/base/core.c:4176
Inline: False
Direct callers:
  - kernel/reboot.c:deferred_cad
  - kernel/reboot.c:__do_sys_reboot
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
```
**Symbols:**

```
ffffffff81c0e26a-ffffffff81c0e2c1: device_shutdown.cold (STB_LOCAL)
ffffffff817cb6d0-ffffffff817cb881: device_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void device_shutdown();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (0)
Location: drivers/base/core.c:4403
Inline: False
Direct callers:
  - kernel/reboot.c:deferred_cad
  - kernel/reboot.c:__do_sys_reboot
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
```
**Symbols:**

```
ffffffff81c00665-ffffffff81c006bc: device_shutdown.cold (STB_LOCAL)
ffffffff817af040-ffffffff817af1f1: device_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void device_shutdown();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (0)
Location: drivers/base/core.c:4468
Inline: False
Direct callers:
  - kernel/reboot.c:deferred_cad
  - kernel/reboot.c:__do_sys_reboot
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
```
**Symbols:**

```
ffffffff81d02c83-ffffffff81d02cfe: device_shutdown.cold (STB_LOCAL)
ffffffff81838260-ffffffff81838460: device_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void device_shutdown();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (0)
Location: drivers/base/core.c:4502
Inline: False
Direct callers:
  - kernel/reboot.c:deferred_cad
  - kernel/reboot.c:__do_sys_reboot
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
```
**Symbols:**

```
ffffffff81ecb3ca-ffffffff81ecb445: device_shutdown.cold (STB_LOCAL)
ffffffff8197a5d0-ffffffff8197a821: device_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void device_shutdown();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (0)
Location: drivers/base/core.c:4721
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart
```
**Symbols:**

```
ffffffff82098372-ffffffff820983b1: device_shutdown.cold (STB_LOCAL)
ffffffff81ae7440-ffffffff81ae76cd: device_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void device_shutdown();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (0)
Location: drivers/base/core.c:4726
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart
```
**Symbols:**

```
ffffffff8211939e-ffffffff821193dd: device_shutdown.cold (STB_LOCAL)
ffffffff81b35870-ffffffff81b35aed: device_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void device_shutdown();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (0)
Location: drivers/base/core.c:4739
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart
```
**Symbols:**

```
ffffffff821f7361-ffffffff821f73a0: device_shutdown.cold (STB_LOCAL)
ffffffff81b8d290-ffffffff81b8d50d: device_shutdown (STB_GLOBAL)
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
void device_shutdown();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffff8000108e7298)
Location: drivers/base/core.c:3296
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart_prepare
```
**Symbols:**

```
ffff8000108e7298-ffff8000108e7524: device_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void device_shutdown();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c09d586c)
Location: drivers/base/core.c:3296
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart_prepare
```
**Symbols:**

```
c09d586c-c09d5ab8: device_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void device_shutdown();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c00000000097d4f0)
Location: drivers/base/core.c:3296
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart_prepare
```
**Symbols:**

```
c00000000097d4f0-c00000000097d88c: device_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void device_shutdown();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffe00057ba52)
Location: drivers/base/core.c:3296
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart_prepare
```
**Symbols:**

```
ffffffe00057ba52-ffffffe00057bc8e: device_shutdown (STB_GLOBAL)
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
void device_shutdown();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (0)
Location: drivers/base/core.c:3296
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart_prepare
```
**Symbols:**

```
ffffffff816c29a2-ffffffff816c29f9: device_shutdown.cold (STB_LOCAL)
ffffffff816c20b0-ffffffff816c223e: device_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void device_shutdown();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (0)
Location: drivers/base/core.c:3296
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart_prepare
```
**Symbols:**

```
ffffffff8169dc52-ffffffff8169dca9: device_shutdown.cold (STB_LOCAL)
ffffffff8169d360-ffffffff8169d4ee: device_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void device_shutdown();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (0)
Location: drivers/base/core.c:3296
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart_prepare
```
**Symbols:**

```
ffffffff816f0e72-ffffffff816f0ec9: device_shutdown.cold (STB_LOCAL)
ffffffff816f0580-ffffffff816f070e: device_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void device_shutdown();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (0)
Location: drivers/base/core.c:3296
Inline: False
Direct callers:
  - kernel/reboot.c:kernel_power_off
  - kernel/reboot.c:kernel_halt
  - kernel/reboot.c:kernel_restart_prepare
```
**Symbols:**

```
ffffffff8170b6b2-ffffffff8170b709: device_shutdown.cold (STB_LOCAL)
ffffffff8170adc0-ffffffff8170af4a: device_shutdown (STB_GLOBAL)
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
