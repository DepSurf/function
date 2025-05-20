# Function: <code>clockevents_switch_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void clockevents_switch_state(struct clock_event_device *dev, enum clock_event_state state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff810fbe20)
Location: kernel/time/clockevents.c:153
Inline: True
Direct callers:
  - kernel/time/clockevents.c:clockevents_exchange_device
  - kernel/time/clockevents.c:clockevents_exchange_device
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-broadcast.c:tick_check_oneshot_broadcast_this_cpu
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-oneshot.c:tick_program_event
  - kernel/time/tick-oneshot.c:tick_program_event
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-oneshot.c:tick_setup_oneshot
  - kernel/time/tick-oneshot.c:tick_switch_to_oneshot
```
**Symbols:**

```
ffffffff810fbe20-ffffffff810fbf00: clockevents_switch_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void clockevents_switch_state(struct clock_event_device *dev, enum clock_event_state state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff81103160)
Location: kernel/time/clockevents.c:153
Inline: True
Direct callers:
  - kernel/time/clockevents.c:clockevents_exchange_device
  - kernel/time/clockevents.c:clockevents_exchange_device
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_check_oneshot_broadcast_this_cpu
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-oneshot.c:tick_switch_to_oneshot
  - kernel/time/tick-oneshot.c:tick_setup_oneshot
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-oneshot.c:tick_program_event
  - kernel/time/tick-oneshot.c:tick_program_event
```
**Symbols:**

```
ffffffff81103160-ffffffff81103240: clockevents_switch_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void clockevents_switch_state(struct clock_event_device *dev, enum clock_event_state state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff8110a850)
Location: kernel/time/clockevents.c:153
Inline: True
Direct callers:
  - kernel/time/clockevents.c:clockevents_exchange_device
  - kernel/time/clockevents.c:clockevents_exchange_device
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_check_oneshot_broadcast_this_cpu
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-oneshot.c:tick_switch_to_oneshot
  - kernel/time/tick-oneshot.c:tick_setup_oneshot
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-oneshot.c:tick_program_event
  - kernel/time/tick-oneshot.c:tick_program_event
```
**Symbols:**

```
ffffffff8110a850-ffffffff8110a930: clockevents_switch_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void clockevents_switch_state(struct clock_event_device *dev, enum clock_event_state state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff8110c7a0)
Location: kernel/time/clockevents.c:153
Inline: True
Direct callers:
  - kernel/time/clockevents.c:clockevents_exchange_device
  - kernel/time/clockevents.c:clockevents_exchange_device
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_check_oneshot_broadcast_this_cpu
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-oneshot.c:tick_switch_to_oneshot
  - kernel/time/tick-oneshot.c:tick_setup_oneshot
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-oneshot.c:tick_program_event
  - kernel/time/tick-oneshot.c:tick_program_event
```
**Symbols:**

```
ffffffff8110c7a0-ffffffff8110c865: clockevents_switch_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void clockevents_switch_state(struct clock_event_device *dev, enum clock_event_state state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff811179f0)
Location: kernel/time/clockevents.c:153
Inline: True
Direct callers:
  - kernel/time/clockevents.c:clockevents_exchange_device
  - kernel/time/clockevents.c:clockevents_exchange_device
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_check_oneshot_broadcast_this_cpu
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-oneshot.c:tick_switch_to_oneshot
  - kernel/time/tick-oneshot.c:tick_setup_oneshot
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-oneshot.c:tick_program_event
  - kernel/time/tick-oneshot.c:tick_program_event
```
**Symbols:**

```
ffffffff811179f0-ffffffff81117ac1: clockevents_switch_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void clockevents_switch_state(struct clock_event_device *dev, enum clock_event_state state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff811244f0)
Location: kernel/time/clockevents.c:153
Inline: True
Direct callers:
  - kernel/time/clockevents.c:clockevents_exchange_device
  - kernel/time/clockevents.c:clockevents_exchange_device
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_check_oneshot_broadcast_this_cpu
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-oneshot.c:tick_switch_to_oneshot
  - kernel/time/tick-oneshot.c:tick_setup_oneshot
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-oneshot.c:tick_program_event
  - kernel/time/tick-oneshot.c:tick_program_event
```
**Symbols:**

```
ffffffff811244f0-ffffffff811245ca: clockevents_switch_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void clockevents_switch_state(struct clock_event_device *dev, enum clock_event_state state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff8112fbf0)
Location: kernel/time/clockevents.c:147
Inline: True
Direct callers:
  - kernel/time/clockevents.c:clockevents_exchange_device
  - kernel/time/clockevents.c:clockevents_exchange_device
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_check_oneshot_broadcast_this_cpu
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-oneshot.c:tick_switch_to_oneshot
  - kernel/time/tick-oneshot.c:tick_setup_oneshot
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-oneshot.c:tick_program_event
  - kernel/time/tick-oneshot.c:tick_program_event
```
**Symbols:**

```
ffffffff8112fbf0-ffffffff8112fcc8: clockevents_switch_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void clockevents_switch_state(struct clock_event_device *dev, enum clock_event_state state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/clockevents.c (ffffffff8113a714)
Location: kernel/time/clockevents.c:147
Inline: True
Direct callers:
  - kernel/time/clockevents.c:clockevents_exchange_device
  - kernel/time/clockevents.c:clockevents_exchange_device
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_check_oneshot_broadcast_this_cpu
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-oneshot.c:tick_switch_to_oneshot
  - kernel/time/tick-oneshot.c:tick_setup_oneshot
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-oneshot.c:tick_program_event
  - kernel/time/tick-oneshot.c:tick_program_event
```
**Symbols:**

```
ffffffff8113ad61-ffffffff8113ad7d: clockevents_switch_state.cold (STB_LOCAL)
ffffffff8113a6a0-ffffffff8113a77d: clockevents_switch_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void clockevents_switch_state(struct clock_event_device *dev, enum clock_event_state state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff81146310)
Location: kernel/time/clockevents.c:147
Inline: True
Direct callers:
  - kernel/time/clockevents.c:clockevents_exchange_device
  - kernel/time/clockevents.c:clockevents_exchange_device
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_check_oneshot_broadcast_this_cpu
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-oneshot.c:tick_switch_to_oneshot
  - kernel/time/tick-oneshot.c:tick_setup_oneshot
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-oneshot.c:tick_program_event
  - kernel/time/tick-oneshot.c:tick_program_event
```
**Symbols:**

```
ffffffff81146310-ffffffff811463fb: clockevents_switch_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void clockevents_switch_state(struct clock_event_device *dev, enum clock_event_state state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff811564a3)
Location: kernel/time/clockevents.c:147
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_exchange_device
  - kernel/time/clockevents.c:clockevents_exchange_device
Direct callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_check_oneshot_broadcast_this_cpu
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-oneshot.c:tick_switch_to_oneshot
  - kernel/time/tick-oneshot.c:tick_setup_oneshot
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-oneshot.c:tick_program_event
  - kernel/time/tick-oneshot.c:tick_program_event
```
**Symbols:**

```
ffffffff811561f0-ffffffff81156235: clockevents_switch_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void clockevents_switch_state(struct clock_event_device *dev, enum clock_event_state state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff81152643)
Location: kernel/time/clockevents.c:147
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_exchange_device
  - kernel/time/clockevents.c:clockevents_exchange_device
Direct callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_check_oneshot_broadcast_this_cpu
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-oneshot.c:tick_switch_to_oneshot
  - kernel/time/tick-oneshot.c:tick_setup_oneshot
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-oneshot.c:tick_program_event
  - kernel/time/tick-oneshot.c:tick_program_event
```
**Symbols:**

```
ffffffff81152390-ffffffff811523d5: clockevents_switch_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void clockevents_switch_state(struct clock_event_device *dev, enum clock_event_state state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff81153a93)
Location: kernel/time/clockevents.c:147
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_exchange_device
  - kernel/time/clockevents.c:clockevents_exchange_device
Direct callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_check_oneshot_broadcast_this_cpu
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-oneshot.c:tick_switch_to_oneshot
  - kernel/time/tick-oneshot.c:tick_setup_oneshot
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-oneshot.c:tick_program_event
  - kernel/time/tick-oneshot.c:tick_program_event
```
**Symbols:**

```
ffffffff811537d0-ffffffff81153815: clockevents_switch_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void clockevents_switch_state(struct clock_event_device *dev, enum clock_event_state state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff81178183)
Location: kernel/time/clockevents.c:147
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_exchange_device
  - kernel/time/clockevents.c:clockevents_exchange_device
Direct callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_check_oneshot_broadcast_this_cpu
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-oneshot.c:tick_switch_to_oneshot
  - kernel/time/tick-oneshot.c:tick_setup_oneshot
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-oneshot.c:tick_program_event
  - kernel/time/tick-oneshot.c:tick_program_event
```
**Symbols:**

```
ffffffff81177e90-ffffffff81177ed5: clockevents_switch_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void clockevents_switch_state(struct clock_event_device *dev, enum clock_event_state state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff811ad303)
Location: kernel/time/clockevents.c:147
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_exchange_device
  - kernel/time/clockevents.c:clockevents_exchange_device
Direct callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_check_oneshot_broadcast_this_cpu
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-oneshot.c:tick_switch_to_oneshot
  - kernel/time/tick-oneshot.c:tick_setup_oneshot
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-oneshot.c:tick_program_event
  - kernel/time/tick-oneshot.c:tick_program_event
```
**Symbols:**

```
ffffffff811acfd0-ffffffff811ad029: clockevents_switch_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void clockevents_switch_state(struct clock_event_device *dev, enum clock_event_state state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff811ed853)
Location: kernel/time/clockevents.c:147
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_exchange_device
  - kernel/time/clockevents.c:clockevents_exchange_device
Direct callers:
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_check_oneshot_broadcast_this_cpu
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-oneshot.c:tick_switch_to_oneshot
  - kernel/time/tick-oneshot.c:tick_setup_oneshot
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-oneshot.c:tick_program_event
  - kernel/time/tick-oneshot.c:tick_program_event
```
**Symbols:**

```
ffffffff811ed4a0-ffffffff811ed4f9: clockevents_switch_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void clockevents_switch_state(struct clock_event_device *dev, enum clock_event_state state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff81201f83)
Location: kernel/time/clockevents.c:147
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_exchange_device
  - kernel/time/clockevents.c:clockevents_exchange_device
Direct callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_check_oneshot_broadcast_this_cpu
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-oneshot.c:tick_switch_to_oneshot
  - kernel/time/tick-oneshot.c:tick_setup_oneshot
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-oneshot.c:tick_program_event
  - kernel/time/tick-oneshot.c:tick_program_event
```
**Symbols:**

```
ffffffff81201bc0-ffffffff81201c19: clockevents_switch_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void clockevents_switch_state(struct clock_event_device *dev, enum clock_event_state state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff81218423)
Location: kernel/time/clockevents.c:147
Inline: True
Inline callers:
  - kernel/time/clockevents.c:clockevents_exchange_device
  - kernel/time/clockevents.c:clockevents_exchange_device
Direct callers:
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_check_oneshot_broadcast_this_cpu
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-oneshot.c:tick_switch_to_oneshot
  - kernel/time/tick-oneshot.c:tick_setup_oneshot
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-oneshot.c:tick_program_event
  - kernel/time/tick-oneshot.c:tick_program_event
```
**Symbols:**

```
ffffffff81218060-ffffffff812180b9: clockevents_switch_state (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void clockevents_switch_state(struct clock_event_device *dev, enum clock_event_state state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffff8000101b0d40)
Location: kernel/time/clockevents.c:147
Inline: True
Direct callers:
  - kernel/time/clockevents.c:clockevents_exchange_device
  - kernel/time/clockevents.c:clockevents_exchange_device
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_check_oneshot_broadcast_this_cpu
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-oneshot.c:tick_switch_to_oneshot
  - kernel/time/tick-oneshot.c:tick_setup_oneshot
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-oneshot.c:tick_program_event
  - kernel/time/tick-oneshot.c:tick_program_event
```
**Symbols:**

```
ffff8000101b0d40-ffff8000101b0e54: clockevents_switch_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void clockevents_switch_state(struct clock_event_device *dev, enum clock_event_state state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (c03fb788)
Location: kernel/time/clockevents.c:147
Inline: True
Direct callers:
  - kernel/time/clockevents.c:clockevents_exchange_device
  - kernel/time/clockevents.c:clockevents_exchange_device
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_check_oneshot_broadcast_this_cpu
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-oneshot.c:tick_switch_to_oneshot
  - kernel/time/tick-oneshot.c:tick_setup_oneshot
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-oneshot.c:tick_program_event
  - kernel/time/tick-oneshot.c:tick_program_event
```
**Symbols:**

```
c03fb788-c03fb8e4: clockevents_switch_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void clockevents_switch_state(struct clock_event_device *dev, enum clock_event_state state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (c000000000215a80)
Location: kernel/time/clockevents.c:147
Inline: True
Direct callers:
  - kernel/time/clockevents.c:clockevents_exchange_device
  - kernel/time/clockevents.c:clockevents_exchange_device
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_check_oneshot_broadcast_this_cpu
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-oneshot.c:tick_switch_to_oneshot
  - kernel/time/tick-oneshot.c:tick_setup_oneshot
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-oneshot.c:tick_program_event
  - kernel/time/tick-oneshot.c:tick_program_event
```
**Symbols:**

```
c000000000215a80-c000000000215c54: clockevents_switch_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void clockevents_switch_state(struct clock_event_device *dev, enum clock_event_state state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffe000139afa)
Location: kernel/time/clockevents.c:147
Inline: True
Direct callers:
  - kernel/time/clockevents.c:clockevents_exchange_device
  - kernel/time/clockevents.c:clockevents_exchange_device
  - kernel/time/tick-oneshot.c:tick_switch_to_oneshot
  - kernel/time/tick-oneshot.c:tick_setup_oneshot
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-oneshot.c:tick_program_event
  - kernel/time/tick-oneshot.c:tick_program_event
```
**Symbols:**

```
ffffffe000139afa-ffffffe000139bda: clockevents_switch_state (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void clockevents_switch_state(struct clock_event_device *dev, enum clock_event_state state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff8113eac0)
Location: kernel/time/clockevents.c:147
Inline: True
Direct callers:
  - kernel/time/clockevents.c:clockevents_exchange_device
  - kernel/time/clockevents.c:clockevents_exchange_device
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_check_oneshot_broadcast_this_cpu
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-oneshot.c:tick_switch_to_oneshot
  - kernel/time/tick-oneshot.c:tick_setup_oneshot
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-oneshot.c:tick_program_event
  - kernel/time/tick-oneshot.c:tick_program_event
```
**Symbols:**

```
ffffffff8113eac0-ffffffff8113ebab: clockevents_switch_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void clockevents_switch_state(struct clock_event_device *dev, enum clock_event_state state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff811315e0)
Location: kernel/time/clockevents.c:147
Inline: True
Direct callers:
  - kernel/time/clockevents.c:clockevents_exchange_device
  - kernel/time/clockevents.c:clockevents_exchange_device
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_check_oneshot_broadcast_this_cpu
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-oneshot.c:tick_switch_to_oneshot
  - kernel/time/tick-oneshot.c:tick_setup_oneshot
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-oneshot.c:tick_program_event
  - kernel/time/tick-oneshot.c:tick_program_event
```
**Symbols:**

```
ffffffff811315e0-ffffffff811316cb: clockevents_switch_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void clockevents_switch_state(struct clock_event_device *dev, enum clock_event_state state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff8113c7e0)
Location: kernel/time/clockevents.c:147
Inline: True
Direct callers:
  - kernel/time/clockevents.c:clockevents_exchange_device
  - kernel/time/clockevents.c:clockevents_exchange_device
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_check_oneshot_broadcast_this_cpu
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-oneshot.c:tick_switch_to_oneshot
  - kernel/time/tick-oneshot.c:tick_setup_oneshot
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-oneshot.c:tick_program_event
  - kernel/time/tick-oneshot.c:tick_program_event
```
**Symbols:**

```
ffffffff8113c7e0-ffffffff8113c8cb: clockevents_switch_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void clockevents_switch_state(struct clock_event_device *dev, enum clock_event_state state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/clockevents.c (ffffffff811492d0)
Location: kernel/time/clockevents.c:147
Inline: True
Direct callers:
  - kernel/time/clockevents.c:clockevents_exchange_device
  - kernel/time/clockevents.c:clockevents_exchange_device
  - kernel/time/tick-broadcast.c:tick_broadcast_setup_oneshot
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:__tick_broadcast_oneshot_control
  - kernel/time/tick-broadcast.c:tick_check_oneshot_broadcast_this_cpu
  - kernel/time/tick-broadcast.c:tick_broadcast_set_event
  - kernel/time/tick-broadcast.c:tick_resume_broadcast
  - kernel/time/tick-oneshot.c:tick_switch_to_oneshot
  - kernel/time/tick-oneshot.c:tick_setup_oneshot
  - kernel/time/tick-oneshot.c:tick_resume_oneshot
  - kernel/time/tick-oneshot.c:tick_program_event
  - kernel/time/tick-oneshot.c:tick_program_event
```
**Symbols:**

```
ffffffff811492d0-ffffffff811493bb: clockevents_switch_state (STB_GLOBAL)
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
