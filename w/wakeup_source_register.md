# Function: <code>wakeup_source_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct wakeup_source *wakeup_source_register(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff8155b970)
Location: drivers/base/power/wakeup.c:209
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:device_wakeup_enable
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
  - fs/eventpoll.c:ep_create_wakeup_source
  - fs/eventpoll.c:ep_create_wakeup_source
```
**Symbols:**

```
ffffffff8155b970-ffffffff8155b995: wakeup_source_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct wakeup_source *wakeup_source_register(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff815ae704)
Location: drivers/base/power/wakeup.c:209
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:device_wakeup_enable
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
  - fs/eventpoll.c:ep_create_wakeup_source
  - fs/eventpoll.c:ep_create_wakeup_source
```
**Symbols:**

```
ffffffff815adbf0-ffffffff815adc15: wakeup_source_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct wakeup_source *wakeup_source_register(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff815dd504)
Location: drivers/base/power/wakeup.c:209
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:device_wakeup_enable
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_init
  - fs/eventpoll.c:ep_create_wakeup_source
  - fs/eventpoll.c:ep_create_wakeup_source
```
**Symbols:**

```
ffffffff815dc9c0-ffffffff815dc9e5: wakeup_source_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct wakeup_source *wakeup_source_register(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff815f20f4)
Location: drivers/base/power/wakeup.c:211
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:device_wakeup_enable
Direct callers:
  - fs/eventpoll.c:ep_create_wakeup_source
  - fs/eventpoll.c:ep_create_wakeup_source
```
**Symbols:**

```
ffffffff815f1530-ffffffff815f1559: wakeup_source_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct wakeup_source *wakeup_source_register(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816596a4)
Location: drivers/base/power/wakeup.c:211
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:device_wakeup_enable
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - fs/eventpoll.c:ep_create_wakeup_source
  - fs/eventpoll.c:ep_create_wakeup_source
```
**Symbols:**

```
ffffffff81658b20-ffffffff81658b49: wakeup_source_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct wakeup_source *wakeup_source_register(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816952e5)
Location: drivers/base/power/wakeup.c:215
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:device_wakeup_enable
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - fs/eventpoll.c:ep_create_wakeup_source
  - fs/eventpoll.c:ep_create_wakeup_source
```
**Symbols:**

```
ffffffff81694ac0-ffffffff81694ae5: wakeup_source_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct wakeup_source *wakeup_source_register(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816b5955)
Location: drivers/base/power/wakeup.c:221
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:device_wakeup_enable
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - fs/eventpoll.c:ep_create_wakeup_source
  - fs/eventpoll.c:ep_create_wakeup_source
```
**Symbols:**

```
ffffffff816b5150-ffffffff816b5175: wakeup_source_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct wakeup_source *wakeup_source_register(const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816ef776)
Location: drivers/base/power/wakeup.c:205
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:device_wakeup_enable
Direct callers:
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - fs/eventpoll.c:ep_create_wakeup_source
  - fs/eventpoll.c:ep_create_wakeup_source
```
**Symbols:**

```
ffffffff816eebc0-ffffffff816eebe7: wakeup_source_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct wakeup_source *wakeup_source_register(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81712cc0)
Location: drivers/base/power/wakeup.c:215
Inline: False
Direct callers:
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - fs/eventpoll.c:ep_create_wakeup_source
  - fs/eventpoll.c:ep_create_wakeup_source
  - drivers/base/power/wakeup.c:device_wakeup_enable
```
**Symbols:**

```
ffffffff81712cc0-ffffffff81712d19: wakeup_source_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct wakeup_source *wakeup_source_register(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817ce870)
Location: drivers/base/power/wakeup.c:218
Inline: False
Direct callers:
  - kernel/power/wakelock.c:wakelock_lookup_add
  - fs/eventpoll.c:ep_create_wakeup_source
  - fs/eventpoll.c:ep_create_wakeup_source
  - drivers/base/power/wakeup.c:device_wakeup_enable
```
**Symbols:**

```
ffffffff817ce870-ffffffff817ce8e3: wakeup_source_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct wakeup_source *wakeup_source_register(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817e2f30)
Location: drivers/base/power/wakeup.c:218
Inline: False
Direct callers:
  - kernel/power/wakelock.c:wakelock_lookup_add
  - fs/eventpoll.c:ep_create_wakeup_source
  - fs/eventpoll.c:ep_create_wakeup_source
  - drivers/base/power/wakeup.c:device_wakeup_enable
  - drivers/mmc/core/host.c:mmc_alloc_host
```
**Symbols:**

```
ffffffff817e2f30-ffffffff817e2fa3: wakeup_source_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct wakeup_source *wakeup_source_register(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817c72f0)
Location: drivers/base/power/wakeup.c:218
Inline: False
Direct callers:
  - kernel/power/wakelock.c:wakelock_lookup_add
  - fs/eventpoll.c:ep_create_wakeup_source
  - fs/eventpoll.c:ep_create_wakeup_source
  - drivers/base/power/wakeup.c:device_wakeup_enable
  - drivers/mmc/core/host.c:mmc_alloc_host
```
**Symbols:**

```
ffffffff817c72f0-ffffffff817c7363: wakeup_source_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct wakeup_source *wakeup_source_register(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff818516d0)
Location: drivers/base/power/wakeup.c:219
Inline: False
Direct callers:
  - kernel/power/wakelock.c:wakelock_lookup_add
  - fs/eventpoll.c:ep_create_wakeup_source
  - fs/eventpoll.c:ep_create_wakeup_source
  - drivers/base/power/wakeup.c:device_wakeup_enable
  - drivers/mmc/core/host.c:mmc_alloc_host
```
**Symbols:**

```
ffffffff818516d0-ffffffff81851743: wakeup_source_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct wakeup_source *wakeup_source_register(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff819974f0)
Location: drivers/base/power/wakeup.c:219
Inline: False
Direct callers:
  - kernel/power/wakelock.c:wakelock_lookup_add
  - fs/eventpoll.c:ep_create_wakeup_source
  - fs/eventpoll.c:ep_create_wakeup_source
  - drivers/base/power/wakeup.c:device_wakeup_enable
  - drivers/mmc/core/host.c:mmc_alloc_host
```
**Symbols:**

```
ffffffff819974f0-ffffffff81997566: wakeup_source_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct wakeup_source *wakeup_source_register(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81b084e0)
Location: drivers/base/power/wakeup.c:219
Inline: False
Direct callers:
  - kernel/power/wakelock.c:wakelock_lookup_add
  - fs/eventpoll.c:ep_create_wakeup_source
  - fs/eventpoll.c:ep_create_wakeup_source
  - drivers/base/power/wakeup.c:device_wakeup_enable
  - drivers/mmc/core/host.c:mmc_alloc_host
```
**Symbols:**

```
ffffffff81b084e0-ffffffff81b08556: wakeup_source_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct wakeup_source *wakeup_source_register(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81b56510)
Location: drivers/base/power/wakeup.c:214
Inline: False
Direct callers:
  - kernel/power/wakelock.c:wakelock_lookup_add
  - fs/eventpoll.c:ep_create_wakeup_source
  - fs/eventpoll.c:ep_create_wakeup_source
  - drivers/base/power/wakeup.c:device_wakeup_enable
  - drivers/mmc/core/host.c:mmc_alloc_host
```
**Symbols:**

```
ffffffff81b56510-ffffffff81b56586: wakeup_source_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct wakeup_source *wakeup_source_register(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81baeb00)
Location: drivers/base/power/wakeup.c:214
Inline: False
Direct callers:
  - kernel/power/wakelock.c:wakelock_lookup_add
  - fs/eventpoll.c:ep_create_wakeup_source
  - fs/eventpoll.c:ep_create_wakeup_source
  - drivers/base/power/wakeup.c:device_wakeup_enable
  - drivers/mmc/core/host.c:mmc_alloc_host
```
**Symbols:**

```
ffffffff81baeb00-ffffffff81baeb76: wakeup_source_register (STB_GLOBAL)
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
struct wakeup_source *wakeup_source_register(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffff800010904af0)
Location: drivers/base/power/wakeup.c:215
Inline: False
Direct callers:
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - fs/eventpoll.c:ep_create_wakeup_source
  - fs/eventpoll.c:ep_create_wakeup_source
  - drivers/base/power/wakeup.c:device_wakeup_enable
```
**Symbols:**

```
ffff800010904af0-ffff800010904b60: wakeup_source_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct wakeup_source *wakeup_source_register(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (c09edc9c)
Location: drivers/base/power/wakeup.c:215
Inline: False
Direct callers:
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - fs/eventpoll.c:ep_create_wakeup_source
  - fs/eventpoll.c:ep_create_wakeup_source
  - drivers/base/power/wakeup.c:device_wakeup_enable
```
**Symbols:**

```
c09edc9c-c09edd0c: wakeup_source_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct wakeup_source *wakeup_source_register(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (c0000000009a30a0)
Location: drivers/base/power/wakeup.c:215
Inline: False
Direct callers:
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - fs/eventpoll.c:ep_create_wakeup_source
  - fs/eventpoll.c:ep_create_wakeup_source
  - drivers/base/power/wakeup.c:device_wakeup_enable
```
**Symbols:**

```
c0000000009a30a0-c0000000009a3138: wakeup_source_register (STB_GLOBAL)
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
Location: include/linux/pm_wakeup.h:130
Inline: True
```
```
In fs/eventpoll.c (0)
Location: include/linux/pm_wakeup.h:130
Inline: True
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
struct wakeup_source *wakeup_source_register(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816d9060)
Location: drivers/base/power/wakeup.c:215
Inline: False
Direct callers:
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - fs/eventpoll.c:ep_create_wakeup_source
  - fs/eventpoll.c:ep_create_wakeup_source
  - drivers/base/power/wakeup.c:device_wakeup_enable
```
**Symbols:**

```
ffffffff816d9060-ffffffff816d90b9: wakeup_source_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct wakeup_source *wakeup_source_register(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816b3680)
Location: drivers/base/power/wakeup.c:215
Inline: False
Direct callers:
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - fs/eventpoll.c:ep_create_wakeup_source
  - fs/eventpoll.c:ep_create_wakeup_source
  - drivers/base/power/wakeup.c:device_wakeup_enable
```
**Symbols:**

```
ffffffff816b3680-ffffffff816b36d9: wakeup_source_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct wakeup_source *wakeup_source_register(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81706980)
Location: drivers/base/power/wakeup.c:215
Inline: False
Direct callers:
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - fs/eventpoll.c:ep_create_wakeup_source
  - fs/eventpoll.c:ep_create_wakeup_source
  - drivers/base/power/wakeup.c:device_wakeup_enable
```
**Symbols:**

```
ffffffff81706980-ffffffff817069d9: wakeup_source_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct wakeup_source *wakeup_source_register(struct device *dev, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81721390)
Location: drivers/base/power/wakeup.c:215
Inline: False
Direct callers:
  - kernel/power/wakelock.c:wakelock_lookup_add
  - kernel/time/alarmtimer.c:alarmtimer_rtc_add_device
  - fs/eventpoll.c:ep_create_wakeup_source
  - fs/eventpoll.c:ep_create_wakeup_source
  - drivers/base/power/wakeup.c:device_wakeup_enable
```
**Symbols:**

```
ffffffff81721390-ffffffff817213e9: wakeup_source_register (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct device *dev</code>
</li>
<li>
<b>Param reordered. </b>
<code>name</code> ➡️ <code>dev, name</code>
</li>
</ul>
</details>
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
