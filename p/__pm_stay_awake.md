# Function: <code>__pm_stay_awake</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __pm_stay_awake(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff8155bb90)
Location: drivers/base/power/wakeup.c:569
Inline: False
Direct callers:
  - kernel/power/wakelock.c:pm_wake_lock
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_scan_ready_list
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
  - drivers/base/power/wakeup.c:pm_stay_awake
```
**Symbols:**

```
ffffffff8155bb90-ffffffff8155bbe1: __pm_stay_awake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __pm_stay_awake(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff815adda0)
Location: drivers/base/power/wakeup.c:567
Inline: False
Direct callers:
  - kernel/power/wakelock.c:pm_wake_lock
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_poll_callback
  - drivers/base/power/wakeup.c:pm_stay_awake
```
**Symbols:**

```
ffffffff815adda0-ffffffff815addf1: __pm_stay_awake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __pm_stay_awake(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff815dcb70)
Location: drivers/base/power/wakeup.c:567
Inline: False
Direct callers:
  - kernel/power/wakelock.c:pm_wake_lock
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_poll_callback
  - drivers/base/power/wakeup.c:pm_stay_awake
```
**Symbols:**

```
ffffffff815dcb70-ffffffff815dcbc1: __pm_stay_awake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __pm_stay_awake(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff815f1d10)
Location: drivers/base/power/wakeup.c:567
Inline: True
Direct callers:
  - kernel/power/wakelock.c:pm_wake_lock
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_poll_callback
```
**Symbols:**

```
ffffffff815f1d10-ffffffff815f1d5d: __pm_stay_awake.part.12 (STB_LOCAL)
ffffffff815f1d60-ffffffff815f1d77: __pm_stay_awake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __pm_stay_awake(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816592c0)
Location: drivers/base/power/wakeup.c:568
Inline: True
Direct callers:
  - kernel/power/wakelock.c:pm_wake_lock
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:SyS_epoll_ctl
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_poll_callback
```
**Symbols:**

```
ffffffff816592c0-ffffffff8165930d: __pm_stay_awake.part.13 (STB_LOCAL)
ffffffff81659310-ffffffff81659327: __pm_stay_awake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __pm_stay_awake(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81694fb0)
Location: drivers/base/power/wakeup.c:567
Inline: True
Direct callers:
  - kernel/power/wakelock.c:pm_wake_lock
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_modify
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_poll_callback
```
**Symbols:**

```
ffffffff81694fb0-ffffffff81694ffd: __pm_stay_awake.part.17 (STB_LOCAL)
ffffffff81695000-ffffffff81695016: __pm_stay_awake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __pm_stay_awake(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816b5650)
Location: drivers/base/power/wakeup.c:573
Inline: True
Direct callers:
  - kernel/power/wakelock.c:pm_wake_lock
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_modify
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_poll_callback
```
**Symbols:**

```
ffffffff816b5650-ffffffff816b569d: __pm_stay_awake.part.17 (STB_LOCAL)
ffffffff816b56a0-ffffffff816b56b6: __pm_stay_awake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __pm_stay_awake(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816ef1f0)
Location: drivers/base/power/wakeup.c:557
Inline: True
Direct callers:
  - kernel/power/wakelock.c:pm_wake_lock
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_poll_callback
```
**Symbols:**

```
ffffffff816ef1f0-ffffffff816ef23d: __pm_stay_awake.part.0 (STB_LOCAL)
ffffffff816ef240-ffffffff816ef256: __pm_stay_awake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __pm_stay_awake(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81713350)
Location: drivers/base/power/wakeup.c:577
Inline: True
Direct callers:
  - kernel/power/wakelock.c:pm_wake_lock
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_poll_callback
```
**Symbols:**

```
ffffffff81713350-ffffffff8171339d: __pm_stay_awake.part.0 (STB_LOCAL)
ffffffff817133a0-ffffffff817133b6: __pm_stay_awake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __pm_stay_awake(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817cf130)
Location: drivers/base/power/wakeup.c:636
Inline: True
Direct callers:
  - kernel/power/wakelock.c:pm_wake_lock
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_modify
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
```
**Symbols:**

```
ffffffff817cf130-ffffffff817cf19f: __pm_stay_awake.part.0 (STB_LOCAL)
ffffffff817cf1a0-ffffffff817cf1b6: __pm_stay_awake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __pm_stay_awake(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817e3730)
Location: drivers/base/power/wakeup.c:636
Inline: True
Direct callers:
  - kernel/power/wakelock.c:pm_wake_lock
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_modify
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_done_scan
```
**Symbols:**

```
ffffffff817e3730-ffffffff817e379f: __pm_stay_awake.part.0 (STB_LOCAL)
ffffffff817e37a0-ffffffff817e37b6: __pm_stay_awake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __pm_stay_awake(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817c78f0)
Location: drivers/base/power/wakeup.c:637
Inline: True
Direct callers:
  - kernel/power/wakelock.c:pm_wake_lock
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_done_scan
```
**Symbols:**

```
ffffffff817c78f0-ffffffff817c795f: __pm_stay_awake.part.0 (STB_LOCAL)
ffffffff817c7960-ffffffff817c7976: __pm_stay_awake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __pm_stay_awake(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81851d73)
Location: drivers/base/power/wakeup.c:638
Inline: True
Direct callers:
  - kernel/power/wakelock.c:pm_wake_lock
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_done_scan
```
**Symbols:**

```
ffffffff81851f30-ffffffff81851f83: __pm_stay_awake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __pm_stay_awake(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81997d57)
Location: drivers/base/power/wakeup.c:638
Inline: True
Direct callers:
  - kernel/power/wakelock.c:pm_wake_lock
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_done_scan
```
**Symbols:**

```
ffffffff81997f40-ffffffff81997fa7: __pm_stay_awake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __pm_stay_awake(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81b08e47)
Location: drivers/base/power/wakeup.c:608
Inline: True
Direct callers:
  - kernel/power/wakelock.c:pm_wake_lock
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_done_scan
```
**Symbols:**

```
ffffffff81b09070-ffffffff81b090d7: __pm_stay_awake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __pm_stay_awake(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81b56e67)
Location: drivers/base/power/wakeup.c:603
Inline: True
Direct callers:
  - kernel/power/wakelock.c:pm_wake_lock
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_done_scan
```
**Symbols:**

```
ffffffff81b57090-ffffffff81b570f7: __pm_stay_awake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __pm_stay_awake(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81baf457)
Location: drivers/base/power/wakeup.c:603
Inline: True
Direct callers:
  - kernel/power/wakelock.c:pm_wake_lock
  - fs/eventpoll.c:do_epoll_ctl
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_send_events
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_done_scan
```
**Symbols:**

```
ffffffff81baf680-ffffffff81baf6e7: __pm_stay_awake (STB_GLOBAL)
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
void __pm_stay_awake(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffff800010904230)
Location: drivers/base/power/wakeup.c:577
Inline: True
Direct callers:
  - kernel/power/wakelock.c:pm_wake_lock
  - fs/eventpoll.c:__do_sys_epoll_ctl
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_poll_callback
```
**Symbols:**

```
ffff800010904230-ffff8000109042e4: __pm_stay_awake.part.0 (STB_LOCAL)
ffff8000109042e8-ffff800010904318: __pm_stay_awake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __pm_stay_awake(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (c09ee360)
Location: drivers/base/power/wakeup.c:577
Inline: True
Direct callers:
  - kernel/power/wakelock.c:pm_wake_lock
  - fs/eventpoll.c:__do_sys_epoll_ctl
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_poll_callback
```
**Symbols:**

```
c09ee360-c09ee3b4: __pm_stay_awake.part.0 (STB_LOCAL)
c09ee3b4-c09ee3d8: __pm_stay_awake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __pm_stay_awake(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (c0000000009a2bf0)
Location: drivers/base/power/wakeup.c:577
Inline: True
Direct callers:
  - kernel/power/wakelock.c:pm_wake_lock
  - fs/eventpoll.c:__se_sys_epoll_ctl
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_poll_callback
```
**Symbols:**

```
c0000000009a2bf0-c0000000009a2c7c: __pm_stay_awake.part.0 (STB_LOCAL)
c0000000009a2c80-c0000000009a2c9c: __pm_stay_awake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (0)
Location: include/linux/pm_wakeup.h:170
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
void __pm_stay_awake(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816d96c0)
Location: drivers/base/power/wakeup.c:577
Inline: True
Direct callers:
  - kernel/power/wakelock.c:pm_wake_lock
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_poll_callback
```
**Symbols:**

```
ffffffff816d96c0-ffffffff816d970d: __pm_stay_awake.part.0 (STB_LOCAL)
ffffffff816d9710-ffffffff816d9726: __pm_stay_awake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __pm_stay_awake(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816b3d10)
Location: drivers/base/power/wakeup.c:577
Inline: True
Direct callers:
  - kernel/power/wakelock.c:pm_wake_lock
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_poll_callback
```
**Symbols:**

```
ffffffff816b3d10-ffffffff816b3d5d: __pm_stay_awake.part.0 (STB_LOCAL)
ffffffff816b3d60-ffffffff816b3d76: __pm_stay_awake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __pm_stay_awake(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81707010)
Location: drivers/base/power/wakeup.c:577
Inline: True
Direct callers:
  - kernel/power/wakelock.c:pm_wake_lock
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_insert
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_poll_callback
```
**Symbols:**

```
ffffffff81707010-ffffffff8170705d: __pm_stay_awake.part.0 (STB_LOCAL)
ffffffff81707060-ffffffff81707076: __pm_stay_awake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __pm_stay_awake(struct wakeup_source *ws);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81721a60)
Location: drivers/base/power/wakeup.c:577
Inline: True
Direct callers:
  - kernel/power/wakelock.c:pm_wake_lock
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__ia32_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:__x64_sys_epoll_ctl
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_send_events_proc
  - fs/eventpoll.c:ep_poll_callback
  - fs/eventpoll.c:ep_poll_callback
```
**Symbols:**

```
ffffffff81721a60-ffffffff81721aad: __pm_stay_awake.part.0 (STB_LOCAL)
ffffffff81721ab0-ffffffff81721ac6: __pm_stay_awake (STB_GLOBAL)
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
