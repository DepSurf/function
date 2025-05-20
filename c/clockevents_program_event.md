# Function: <code>clockevents_program_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int clockevents_program_event(struct clock_event_device *dev, ktime_t expires, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff810fbf50)
Location: kernel/time/clockevents.c:306
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_handle_periodic
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
  - kernel/time/tick-broadcast.c:hotplug_cpu__broadcast_tick_pull
  - kernel/time/tick-oneshot.c:tick_program_event
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-oneshot.c:tick_setup_oneshot
```
**Symbols:**

```
ffffffff810fbf50-ffffffff810fc06a: clockevents_program_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int clockevents_program_event(struct clock_event_device *dev, ktime_t expires, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff81103290)
Location: kernel/time/clockevents.c:306
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_handle_periodic
  - kernel/time/tick-broadcast.c:hotplug_cpu__broadcast_tick_pull
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
  - kernel/time/tick-oneshot.c:tick_setup_oneshot
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-oneshot.c:tick_program_event
```
**Symbols:**

```
ffffffff81103290-ffffffff811033a7: clockevents_program_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int clockevents_program_event(struct clock_event_device *dev, ktime_t expires, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff8110a980)
Location: kernel/time/clockevents.c:306
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_handle_periodic
  - kernel/time/tick-broadcast.c:hotplug_cpu__broadcast_tick_pull
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
  - kernel/time/tick-oneshot.c:tick_setup_oneshot
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-oneshot.c:tick_program_event
```
**Symbols:**

```
ffffffff8110a980-ffffffff8110aa97: clockevents_program_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int clockevents_program_event(struct clock_event_device *dev, ktime_t expires, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff8110c8c0)
Location: kernel/time/clockevents.c:306
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_handle_periodic
  - kernel/time/tick-broadcast.c:hotplug_cpu__broadcast_tick_pull
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
  - kernel/time/tick-oneshot.c:tick_setup_oneshot
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-oneshot.c:tick_program_event
```
**Symbols:**

```
ffffffff8110c8c0-ffffffff8110c9b6: clockevents_program_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int clockevents_program_event(struct clock_event_device *dev, ktime_t expires, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff81117b20)
Location: kernel/time/clockevents.c:311
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_handle_periodic
  - kernel/time/tick-broadcast.c:hotplug_cpu__broadcast_tick_pull
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
  - kernel/time/tick-oneshot.c:tick_setup_oneshot
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-oneshot.c:tick_program_event
```
**Symbols:**

```
ffffffff81117b20-ffffffff81117c26: clockevents_program_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int clockevents_program_event(struct clock_event_device *dev, ktime_t expires, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff81124620)
Location: kernel/time/clockevents.c:311
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_handle_periodic
  - kernel/time/tick-broadcast.c:hotplug_cpu__broadcast_tick_pull
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
  - kernel/time/tick-oneshot.c:tick_setup_oneshot
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-oneshot.c:tick_program_event
```
**Symbols:**

```
ffffffff81124620-ffffffff81124709: clockevents_program_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int clockevents_program_event(struct clock_event_device *dev, ktime_t expires, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff8112fd20)
Location: kernel/time/clockevents.c:303
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_handle_periodic
  - kernel/time/tick-broadcast.c:hotplug_cpu__broadcast_tick_pull
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
  - kernel/time/tick-oneshot.c:tick_setup_oneshot
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-oneshot.c:tick_program_event
```
**Symbols:**

```
ffffffff8112fd20-ffffffff8112fe09: clockevents_program_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int clockevents_program_event(struct clock_event_device *dev, ktime_t expires, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff8113a7d0)
Location: kernel/time/clockevents.c:303
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_handle_periodic
  - kernel/time/tick-broadcast.c:hotplug_cpu__broadcast_tick_pull
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
  - kernel/time/tick-oneshot.c:tick_setup_oneshot
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-oneshot.c:tick_program_event
```
**Symbols:**

```
ffffffff8113a7d0-ffffffff8113a8b0: clockevents_program_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int clockevents_program_event(struct clock_event_device *dev, ktime_t expires, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff81146450)
Location: kernel/time/clockevents.c:303
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_handle_periodic
  - kernel/time/tick-broadcast.c:hotplug_cpu__broadcast_tick_pull
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
  - kernel/time/tick-oneshot.c:tick_setup_oneshot
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-oneshot.c:tick_program_event
```
**Symbols:**

```
ffffffff81146450-ffffffff81146530: clockevents_program_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int clockevents_program_event(struct clock_event_device *dev, ktime_t expires, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff811562b0)
Location: kernel/time/clockevents.c:303
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_handle_periodic
  - kernel/time/tick-broadcast.c:hotplug_cpu__broadcast_tick_pull
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
  - kernel/time/tick-oneshot.c:tick_setup_oneshot
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-oneshot.c:tick_program_event
```
**Symbols:**

```
ffffffff811562b0-ffffffff81156390: clockevents_program_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int clockevents_program_event(struct clock_event_device *dev, ktime_t expires, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff81152450)
Location: kernel/time/clockevents.c:303
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_handle_periodic
  - kernel/time/tick-broadcast.c:hotplug_cpu__broadcast_tick_pull
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
  - kernel/time/tick-oneshot.c:tick_setup_oneshot
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-oneshot.c:tick_program_event
```
**Symbols:**

```
ffffffff81152450-ffffffff81152530: clockevents_program_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int clockevents_program_event(struct clock_event_device *dev, ktime_t expires, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff81153890)
Location: kernel/time/clockevents.c:303
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_handle_periodic
  - kernel/time/tick-broadcast.c:hotplug_cpu__broadcast_tick_pull
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
  - kernel/time/tick-oneshot.c:tick_setup_oneshot
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-oneshot.c:tick_program_event
```
**Symbols:**

```
ffffffff81153890-ffffffff81153975: clockevents_program_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int clockevents_program_event(struct clock_event_device *dev, ktime_t expires, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clockevents.c (0)
Location: kernel/time/clockevents.c:303
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_handle_periodic
  - kernel/time/tick-broadcast.c:hotplug_cpu__broadcast_tick_pull
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
  - kernel/time/tick-oneshot.c:tick_setup_oneshot
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-oneshot.c:tick_program_event
```
**Symbols:**

```
ffffffff81cb2045-ffffffff81cb2076: clockevents_program_event.cold (STB_LOCAL)
ffffffff81177f50-ffffffff81178067: clockevents_program_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int clockevents_program_event(struct clock_event_device *dev, ktime_t expires, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clockevents.c (0)
Location: kernel/time/clockevents.c:303
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_handle_periodic
  - kernel/time/tick-broadcast.c:hotplug_cpu__broadcast_tick_pull
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
  - kernel/time/tick-oneshot.c:tick_setup_oneshot
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-oneshot.c:tick_program_event
```
**Symbols:**

```
ffffffff81e635b5-ffffffff81e635e6: clockevents_program_event.cold (STB_LOCAL)
ffffffff811ad0b0-ffffffff811ad1ee: clockevents_program_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int clockevents_program_event(struct clock_event_device *dev, ktime_t expires, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clockevents.c (0)
Location: kernel/time/clockevents.c:303
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_handle_periodic
  - kernel/time/tick-broadcast.c:hotplug_cpu__broadcast_tick_pull
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
  - kernel/time/tick-oneshot.c:tick_setup_oneshot
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-oneshot.c:tick_program_event
```
**Symbols:**

```
ffffffff8205bd28-ffffffff8205bd59: clockevents_program_event.cold (STB_LOCAL)
ffffffff811ed5b0-ffffffff811ed6ee: clockevents_program_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int clockevents_program_event(struct clock_event_device *dev, ktime_t expires, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clockevents.c (0)
Location: kernel/time/clockevents.c:303
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_handle_periodic
  - kernel/time/tick-broadcast.c:hotplug_cpu__broadcast_tick_pull
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
  - kernel/time/tick-oneshot.c:tick_setup_oneshot
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-oneshot.c:tick_program_event
```
**Symbols:**

```
ffffffff820da51d-ffffffff820da54e: clockevents_program_event.cold (STB_LOCAL)
ffffffff81201cd0-ffffffff81201e1a: clockevents_program_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int clockevents_program_event(struct clock_event_device *dev, ktime_t expires, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clockevents.c (0)
Location: kernel/time/clockevents.c:303
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_handle_periodic
  - kernel/time/tick-broadcast.c:hotplug_cpu__broadcast_tick_pull
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
  - kernel/time/tick-oneshot.c:tick_setup_oneshot
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-oneshot.c:tick_program_event
```
**Symbols:**

```
ffffffff821b5e97-ffffffff821b5ec8: clockevents_program_event.cold (STB_LOCAL)
ffffffff81218170-ffffffff812182ba: clockevents_program_event (STB_GLOBAL)
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
int clockevents_program_event(struct clock_event_device *dev, ktime_t expires, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffff8000101b0ec8)
Location: kernel/time/clockevents.c:303
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_handle_periodic
  - kernel/time/tick-broadcast.c:hotplug_cpu__broadcast_tick_pull
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
  - kernel/time/tick-oneshot.c:tick_setup_oneshot
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-oneshot.c:tick_program_event
```
**Symbols:**

```
ffff8000101b0ec8-ffff8000101b0fe8: clockevents_program_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int clockevents_program_event(struct clock_event_device *dev, ktime_t expires, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (c03fb944)
Location: kernel/time/clockevents.c:303
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_handle_periodic
  - kernel/time/tick-broadcast.c:hotplug_cpu__broadcast_tick_pull
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
  - kernel/time/tick-oneshot.c:tick_setup_oneshot
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-oneshot.c:tick_program_event
```
**Symbols:**

```
c03fb944-c03fbae4: clockevents_program_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int clockevents_program_event(struct clock_event_device *dev, ktime_t expires, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (c000000000215d10)
Location: kernel/time/clockevents.c:303
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_handle_periodic
  - kernel/time/tick-common.c:tick_handle_periodic
  - kernel/time/tick-broadcast.c:hotplug_cpu__broadcast_tick_pull
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
  - kernel/time/tick-oneshot.c:tick_setup_oneshot
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-oneshot.c:tick_program_event
```
**Symbols:**

```
c000000000215d10-c000000000215f34: clockevents_program_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int clockevents_program_event(struct clock_event_device *dev, ktime_t expires, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffe000139c36)
Location: kernel/time/clockevents.c:303
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_handle_periodic
  - kernel/time/tick-oneshot.c:tick_setup_oneshot
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-oneshot.c:tick_program_event
```
**Symbols:**

```
ffffffe000139c36-ffffffe000139d2a: clockevents_program_event (STB_GLOBAL)
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
int clockevents_program_event(struct clock_event_device *dev, ktime_t expires, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff8113ec00)
Location: kernel/time/clockevents.c:303
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_handle_periodic
  - kernel/time/tick-broadcast.c:hotplug_cpu__broadcast_tick_pull
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
  - kernel/time/tick-oneshot.c:tick_setup_oneshot
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-oneshot.c:tick_program_event
```
**Symbols:**

```
ffffffff8113ec00-ffffffff8113ece0: clockevents_program_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int clockevents_program_event(struct clock_event_device *dev, ktime_t expires, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff81131720)
Location: kernel/time/clockevents.c:303
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_handle_periodic
  - kernel/time/tick-broadcast.c:hotplug_cpu__broadcast_tick_pull
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
  - kernel/time/tick-oneshot.c:tick_setup_oneshot
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-oneshot.c:tick_program_event
```
**Symbols:**

```
ffffffff81131720-ffffffff81131800: clockevents_program_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int clockevents_program_event(struct clock_event_device *dev, ktime_t expires, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff8113c920)
Location: kernel/time/clockevents.c:303
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_handle_periodic
  - kernel/time/tick-broadcast.c:hotplug_cpu__broadcast_tick_pull
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
  - kernel/time/tick-oneshot.c:tick_setup_oneshot
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-oneshot.c:tick_program_event
```
**Symbols:**

```
ffffffff8113c920-ffffffff8113ca00: clockevents_program_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int clockevents_program_event(struct clock_event_device *dev, ktime_t expires, bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff81149410)
Location: kernel/time/clockevents.c:303
Inline: False
Direct callers:
  - kernel/time/tick-common.c:tick_handle_periodic
  - kernel/time/tick-broadcast.c:hotplug_cpu__broadcast_tick_pull
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/time/tick-broadcast.c:tick_handle_periodic_broadcast
  - kernel/time/tick-oneshot.c:tick_setup_oneshot
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-oneshot.c:tick_program_event
```
**Symbols:**

```
ffffffff81149410-ffffffff811494f0: clockevents_program_event (STB_GLOBAL)
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
