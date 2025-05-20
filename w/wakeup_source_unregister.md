# Function: <code>wakeup_source_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void wakeup_source_unregister(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff8155c220)
Location: drivers/base/power/wakeup.c:225
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:device_wakeup_disable
  - drivers/base/power/wakeup.c:device_wakeup_enable
Direct callers:
  - fs/eventpoll.c:ep_destroy_wakeup_source
  - fs/eventpoll.c:ep_remove
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:SyS_epoll_ctl
  - drivers/acpi/device_pm.c:acpi_remove_pm_notifier
```
**Symbols:**

```
ffffffff8155c220-ffffffff8155c243: wakeup_source_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void wakeup_source_unregister(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff815ae6a8)
Location: drivers/base/power/wakeup.c:225
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:device_wakeup_disable
  - drivers/base/power/wakeup.c:device_wakeup_enable
Direct callers:
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:ep_destroy_wakeup_source
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_remove
  - drivers/acpi/device_pm.c:acpi_remove_pm_notifier
```
**Symbols:**

```
ffffffff815ae420-ffffffff815ae443: wakeup_source_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void wakeup_source_unregister(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff815dd4a8)
Location: drivers/base/power/wakeup.c:225
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:device_wakeup_disable
  - drivers/base/power/wakeup.c:device_wakeup_enable
Direct callers:
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:ep_destroy_wakeup_source
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_remove
  - drivers/acpi/device_pm.c:acpi_remove_pm_notifier
```
**Symbols:**

```
ffffffff815dd220-ffffffff815dd243: wakeup_source_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void wakeup_source_unregister(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff815f2093)
Location: drivers/base/power/wakeup.c:227
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:device_wakeup_disable
  - drivers/base/power/wakeup.c:device_wakeup_enable
Direct callers:
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:ep_destroy_wakeup_source
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_remove
  - drivers/acpi/device_pm.c:acpi_remove_pm_notifier
```
**Symbols:**

```
ffffffff815f2010-ffffffff815f2034: wakeup_source_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void wakeup_source_unregister(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81659643)
Location: drivers/base/power/wakeup.c:227
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:device_wakeup_disable
  - drivers/base/power/wakeup.c:device_wakeup_enable
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:ep_destroy_wakeup_source
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_remove
  - drivers/acpi/device_pm.c:acpi_remove_pm_notifier
```
**Symbols:**

```
ffffffff816595c0-ffffffff816595e4: wakeup_source_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void wakeup_source_unregister(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81695271)
Location: drivers/base/power/wakeup.c:231
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:device_wakeup_disable
  - drivers/base/power/wakeup.c:device_wakeup_enable
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_destroy_wakeup_source
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_remove
  - drivers/acpi/device_pm.c:acpi_remove_pm_notifier
```
**Symbols:**

```
ffffffff816951f0-ffffffff81695213: wakeup_source_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void wakeup_source_unregister(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816b58e1)
Location: drivers/base/power/wakeup.c:237
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:device_wakeup_disable
  - drivers/base/power/wakeup.c:device_wakeup_disable
  - drivers/base/power/wakeup.c:device_wakeup_enable
  - drivers/base/power/wakeup.c:device_wakeup_enable
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_destroy_wakeup_source
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_remove
  - drivers/acpi/device_pm.c:acpi_remove_pm_notifier
```
**Symbols:**

```
ffffffff816b5860-ffffffff816b5883: wakeup_source_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void wakeup_source_unregister(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816ef701)
Location: drivers/base/power/wakeup.c:221
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:device_wakeup_disable
  - drivers/base/power/wakeup.c:device_wakeup_disable
  - drivers/base/power/wakeup.c:device_wakeup_enable
  - drivers/base/power/wakeup.c:device_wakeup_enable
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_destroy_wakeup_source
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_remove
  - drivers/acpi/device_pm.c:acpi_remove_pm_notifier
```
**Symbols:**

```
ffffffff816ef4e0-ffffffff816ef505: wakeup_source_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void wakeup_source_unregister(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff8171372f)
Location: drivers/base/power/wakeup.c:240
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:device_wakeup_disable
  - drivers/base/power/wakeup.c:device_wakeup_enable
Direct callers:
  - kernel/power/wakelock.c:__wakelocks_gc
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_destroy_wakeup_source
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_remove
  - drivers/acpi/device_pm.c:acpi_remove_pm_notifier
  - drivers/base/power/wakeup.c:device_wakeup_disable
  - drivers/base/power/wakeup.c:device_wakeup_enable
```
**Symbols:**

```
ffffffff81713640-ffffffff81713677: wakeup_source_unregister.part.0 (STB_LOCAL)
ffffffff81713680-ffffffff81713696: wakeup_source_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void wakeup_source_unregister(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817cef7f)
Location: drivers/base/power/wakeup.c:243
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:device_wakeup_disable
  - drivers/base/power/wakeup.c:device_wakeup_enable
Direct callers:
  - kernel/power/wakelock.c:__wakelocks_gc
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_destroy_wakeup_source
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_remove
  - drivers/acpi/device_pm.c:acpi_remove_pm_notifier
  - drivers/base/power/wakeup.c:device_wakeup_disable
  - drivers/base/power/wakeup.c:device_wakeup_enable
```
**Symbols:**

```
ffffffff817ceda0-ffffffff817cedfe: wakeup_source_unregister.part.0 (STB_LOCAL)
ffffffff817cee00-ffffffff817cee16: wakeup_source_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void wakeup_source_unregister(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817e357f)
Location: drivers/base/power/wakeup.c:243
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:device_wakeup_disable
  - drivers/base/power/wakeup.c:device_wakeup_enable
Direct callers:
  - kernel/power/wakelock.c:__wakelocks_gc
  - fs/eventpoll.c:ep_destroy_wakeup_source
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_remove
  - drivers/acpi/device_pm.c:acpi_remove_pm_notifier
  - drivers/base/power/wakeup.c:device_wakeup_disable
  - drivers/base/power/wakeup.c:device_wakeup_enable
  - drivers/mmc/core/host.c:mmc_host_classdev_release
```
**Symbols:**

```
ffffffff817e33a0-ffffffff817e33fe: wakeup_source_unregister.part.0 (STB_LOCAL)
ffffffff817e3400-ffffffff817e3416: wakeup_source_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void wakeup_source_unregister(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817c7dba)
Location: drivers/base/power/wakeup.c:243
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:device_set_wakeup_enable
  - drivers/base/power/wakeup.c:device_wakeup_enable
Direct callers:
  - kernel/power/wakelock.c:__wakelocks_gc
  - fs/eventpoll.c:ep_destroy_wakeup_source
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_remove
  - drivers/acpi/device_pm.c:acpi_remove_pm_notifier
  - drivers/base/power/wakeup.c:device_set_wakeup_enable
  - drivers/base/power/wakeup.c:device_wakeup_enable
  - drivers/mmc/core/host.c:mmc_host_classdev_release
```
**Symbols:**

```
ffffffff817c7760-ffffffff817c77be: wakeup_source_unregister.part.0 (STB_LOCAL)
ffffffff817c77c0-ffffffff817c77d6: wakeup_source_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void wakeup_source_unregister(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff818521da)
Location: drivers/base/power/wakeup.c:244
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:device_set_wakeup_enable
  - drivers/base/power/wakeup.c:device_wakeup_enable
Direct callers:
  - kernel/power/wakelock.c:__wakelocks_gc
  - fs/eventpoll.c:ep_destroy_wakeup_source
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_remove
  - drivers/acpi/device_pm.c:acpi_remove_pm_notifier
  - drivers/base/power/wakeup.c:device_set_wakeup_enable
  - drivers/base/power/wakeup.c:device_wakeup_enable
  - drivers/mmc/core/host.c:mmc_host_classdev_release
```
**Symbols:**

```
ffffffff81851b00-ffffffff81851b5e: wakeup_source_unregister.part.0 (STB_LOCAL)
ffffffff81851b60-ffffffff81851b76: wakeup_source_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void wakeup_source_unregister(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81998011)
Location: drivers/base/power/wakeup.c:244
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:device_set_wakeup_enable
  - drivers/base/power/wakeup.c:device_wakeup_enable
Direct callers:
  - kernel/power/wakelock.c:__wakelocks_gc
  - fs/eventpoll.c:ep_destroy_wakeup_source
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_remove
  - drivers/acpi/device_pm.c:acpi_remove_pm_notifier
  - drivers/base/power/wakeup.c:device_set_wakeup_enable
  - drivers/base/power/wakeup.c:device_wakeup_enable
  - drivers/mmc/core/host.c:mmc_host_classdev_release
```
**Symbols:**

```
ffffffff81997990-ffffffff819979f1: wakeup_source_unregister.part.0 (STB_LOCAL)
ffffffff81997a00-ffffffff81997a22: wakeup_source_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void wakeup_source_unregister(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81b08d31)
Location: drivers/base/power/wakeup.c:244
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:device_set_wakeup_enable
  - drivers/base/power/wakeup.c:device_wakeup_enable
Direct callers:
  - kernel/power/wakelock.c:__wakelocks_gc
  - fs/eventpoll.c:ep_destroy_wakeup_source
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_remove
  - drivers/acpi/device_pm.c:acpi_remove_pm_notifier
  - drivers/base/power/wakeup.c:device_set_wakeup_enable
  - drivers/base/power/wakeup.c:device_wakeup_enable
  - drivers/mmc/core/host.c:mmc_host_classdev_release
```
**Symbols:**

```
ffffffff81b08950-ffffffff81b089b1: wakeup_source_unregister.part.0 (STB_LOCAL)
ffffffff81b089d0-ffffffff81b089f2: wakeup_source_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void wakeup_source_unregister(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81b56d51)
Location: drivers/base/power/wakeup.c:239
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:device_set_wakeup_enable
  - drivers/base/power/wakeup.c:device_wakeup_enable
Direct callers:
  - kernel/power/wakelock.c:__wakelocks_gc
  - fs/eventpoll.c:ep_destroy_wakeup_source
  - fs/eventpoll.c:eventpoll_release_file
  - fs/eventpoll.c:ep_clear_and_put
  - fs/eventpoll.c:__ep_remove
  - drivers/acpi/device_pm.c:acpi_remove_pm_notifier
  - drivers/base/power/wakeup.c:device_set_wakeup_enable
  - drivers/base/power/wakeup.c:device_wakeup_enable
  - drivers/mmc/core/host.c:mmc_host_classdev_release
```
**Symbols:**

```
ffffffff81b56970-ffffffff81b569d1: wakeup_source_unregister.part.0 (STB_LOCAL)
ffffffff81b569f0-ffffffff81b56a12: wakeup_source_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void wakeup_source_unregister(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81baf341)
Location: drivers/base/power/wakeup.c:239
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:device_set_wakeup_enable
  - drivers/base/power/wakeup.c:device_wakeup_enable
Direct callers:
  - kernel/power/wakelock.c:__wakelocks_gc
  - fs/eventpoll.c:ep_destroy_wakeup_source
  - fs/eventpoll.c:eventpoll_release_file
  - fs/eventpoll.c:ep_clear_and_put
  - fs/eventpoll.c:__ep_remove
  - drivers/acpi/device_pm.c:acpi_remove_pm_notifier
  - drivers/base/power/wakeup.c:device_set_wakeup_enable
  - drivers/base/power/wakeup.c:device_wakeup_enable
  - drivers/mmc/core/host.c:mmc_host_classdev_release
```
**Symbols:**

```
ffffffff81baef60-ffffffff81baefc1: wakeup_source_unregister.part.0 (STB_LOCAL)
ffffffff81baefe0-ffffffff81baf002: wakeup_source_unregister (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void wakeup_source_unregister(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffff80001090498c)
Location: drivers/base/power/wakeup.c:240
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:device_wakeup_disable
  - drivers/base/power/wakeup.c:device_wakeup_enable
Direct callers:
  - kernel/power/wakelock.c:__wakelocks_gc
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - fs/eventpoll.c:ep_destroy_wakeup_source
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_remove
  - drivers/acpi/device_pm.c:acpi_remove_pm_notifier
  - drivers/base/power/wakeup.c:device_wakeup_disable
  - drivers/base/power/wakeup.c:device_wakeup_enable
```
**Symbols:**

```
ffff800010904898-ffff8000109048e4: wakeup_source_unregister.part.0 (STB_LOCAL)
ffff8000109048e8-ffff800010904918: wakeup_source_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void wakeup_source_unregister(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (c09ee9ec)
Location: drivers/base/power/wakeup.c:240
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:device_wakeup_disable
  - drivers/base/power/wakeup.c:device_wakeup_enable
Direct callers:
  - kernel/power/wakelock.c:__wakelocks_gc
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_destroy_wakeup_source
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_remove
  - drivers/base/power/wakeup.c:device_wakeup_disable
  - drivers/base/power/wakeup.c:device_wakeup_enable
```
**Symbols:**

```
c09ee930-c09ee970: wakeup_source_unregister.part.0 (STB_LOCAL)
c09ee970-c09ee994: wakeup_source_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void wakeup_source_unregister(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (c0000000009a3474)
Location: drivers/base/power/wakeup.c:240
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:device_wakeup_disable
  - drivers/base/power/wakeup.c:device_wakeup_enable
Direct callers:
  - kernel/power/wakelock.c:__wakelocks_gc
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - fs/eventpoll.c:ep_destroy_wakeup_source
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_remove
  - drivers/base/power/wakeup.c:device_wakeup_disable
  - drivers/base/power/wakeup.c:device_wakeup_enable
```
**Symbols:**

```
c0000000009a32f0-c0000000009a334c: wakeup_source_unregister.part.0 (STB_LOCAL)
c0000000009a3350-c0000000009a336c: wakeup_source_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (0)
Location: include/linux/pm_wakeup.h:136
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/pm_wakeup.h:136
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void wakeup_source_unregister(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816d9a9f)
Location: drivers/base/power/wakeup.c:240
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:device_wakeup_disable
  - drivers/base/power/wakeup.c:device_wakeup_enable
Direct callers:
  - kernel/power/wakelock.c:__wakelocks_gc
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_destroy_wakeup_source
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_remove
  - drivers/acpi/device_pm.c:acpi_remove_pm_notifier
  - drivers/base/power/wakeup.c:device_wakeup_disable
  - drivers/base/power/wakeup.c:device_wakeup_enable
```
**Symbols:**

```
ffffffff816d99b0-ffffffff816d99e7: wakeup_source_unregister.part.0 (STB_LOCAL)
ffffffff816d99f0-ffffffff816d9a06: wakeup_source_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void wakeup_source_unregister(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816b40e9)
Location: drivers/base/power/wakeup.c:240
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:device_wakeup_disable
  - drivers/base/power/wakeup.c:device_wakeup_enable
Direct callers:
  - kernel/power/wakelock.c:__wakelocks_gc
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_destroy_wakeup_source
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_remove
  - drivers/acpi/device_pm.c:acpi_remove_pm_notifier
  - drivers/base/power/wakeup.c:device_wakeup_disable
  - drivers/base/power/wakeup.c:device_wakeup_enable
```
**Symbols:**

```
ffffffff816b4000-ffffffff816b4037: wakeup_source_unregister.part.0 (STB_LOCAL)
ffffffff816b4040-ffffffff816b4056: wakeup_source_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void wakeup_source_unregister(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817073ef)
Location: drivers/base/power/wakeup.c:240
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:device_wakeup_disable
  - drivers/base/power/wakeup.c:device_wakeup_enable
Direct callers:
  - kernel/power/wakelock.c:__wakelocks_gc
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_destroy_wakeup_source
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_remove
  - drivers/acpi/device_pm.c:acpi_remove_pm_notifier
  - drivers/base/power/wakeup.c:device_wakeup_disable
  - drivers/base/power/wakeup.c:device_wakeup_enable
```
**Symbols:**

```
ffffffff81707300-ffffffff81707337: wakeup_source_unregister.part.0 (STB_LOCAL)
ffffffff81707340-ffffffff81707356: wakeup_source_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void wakeup_source_unregister(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81721dfb)
Location: drivers/base/power/wakeup.c:240
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:device_wakeup_disable
  - drivers/base/power/wakeup.c:device_wakeup_enable
Direct callers:
  - kernel/power/wakelock.c:__wakelocks_gc
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_destroy_wakeup_source
  - fs/eventpoll.c:ep_free
  - fs/eventpoll.c:ep_remove
  - drivers/acpi/device_pm.c:acpi_remove_pm_notifier
  - drivers/base/power/wakeup.c:device_wakeup_disable
  - drivers/base/power/wakeup.c:device_wakeup_enable
```
**Symbols:**

```
ffffffff81721d50-ffffffff81721d87: wakeup_source_unregister.part.0 (STB_LOCAL)
ffffffff81721d90-ffffffff81721da6: wakeup_source_unregister (STB_GLOBAL)
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
