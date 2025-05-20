# Function: <code>ktime_mono_to_any</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ktime_t ktime_mono_to_any(ktime_t tmono, enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810f42c0)
Location: kernel/time/timekeeping.c:751
Inline: False
Direct callers:
  - fs/timerfd.c:timerfd_clock_was_set
  - fs/timerfd.c:SyS_timerfd_create
  - drivers/input/evdev.c:evdev_events
  - drivers/input/evdev.c:evdev_events
```
**Symbols:**

```
ffffffff810f42c0-ffffffff810f42f2: ktime_mono_to_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ktime_t ktime_mono_to_any(ktime_t tmono, enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810fb4d0)
Location: kernel/time/timekeeping.c:756
Inline: False
Direct callers:
  - fs/timerfd.c:SyS_timerfd_create
  - fs/timerfd.c:timerfd_clock_was_set
  - drivers/input/evdev.c:evdev_events
  - drivers/input/evdev.c:evdev_events
```
**Symbols:**

```
ffffffff810fb4d0-ffffffff810fb501: ktime_mono_to_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ktime_t ktime_mono_to_any(ktime_t tmono, enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810fe2d0)
Location: kernel/time/timekeeping.c:785
Inline: False
Direct callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:SyS_timerfd_create
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_read
  - fs/timerfd.c:timerfd_clock_was_set
  - drivers/input/evdev.c:evdev_events
  - drivers/input/evdev.c:evdev_events
```
**Symbols:**

```
ffffffff810fe2d0-ffffffff810fe301: ktime_mono_to_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ktime_t ktime_mono_to_any(ktime_t tmono, enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81100630)
Location: kernel/time/timekeeping.c:817
Inline: False
Direct callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:SyS_timerfd_create
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_read
  - fs/timerfd.c:timerfd_clock_was_set
  - drivers/input/evdev.c:evdev_events
  - drivers/input/evdev.c:evdev_events
```
**Symbols:**

```
ffffffff81100630-ffffffff81100661: ktime_mono_to_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ktime_t ktime_mono_to_any(ktime_t tmono, enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8110b410)
Location: kernel/time/timekeeping.c:821
Inline: False
Direct callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:SyS_timerfd_create
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_read
  - fs/timerfd.c:timerfd_clock_was_set
  - drivers/input/evdev.c:evdev_events
  - drivers/input/evdev.c:evdev_events
```
**Symbols:**

```
ffffffff8110b410-ffffffff8110b441: ktime_mono_to_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ktime_t ktime_mono_to_any(ktime_t tmono, enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81116fb0)
Location: kernel/time/timekeeping.c:822
Inline: False
Direct callers:
  - fs/timerfd.c:__ia32_sys_timerfd_create
  - fs/timerfd.c:__x64_sys_timerfd_create
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_read
  - fs/timerfd.c:timerfd_clock_was_set
  - drivers/input/evdev.c:evdev_events
  - drivers/input/evdev.c:evdev_events
```
**Symbols:**

```
ffffffff81116fb0-ffffffff81116fe3: ktime_mono_to_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ktime_t ktime_mono_to_any(ktime_t tmono, enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811225f0)
Location: kernel/time/timekeeping.c:829
Inline: False
Direct callers:
  - fs/timerfd.c:__ia32_sys_timerfd_create
  - fs/timerfd.c:__x64_sys_timerfd_create
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_read
  - fs/timerfd.c:timerfd_clock_was_set
  - drivers/input/evdev.c:evdev_events
  - drivers/input/evdev.c:evdev_events
```
**Symbols:**

```
ffffffff811225f0-ffffffff81122623: ktime_mono_to_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ktime_t ktime_mono_to_any(ktime_t tmono, enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8112cf10)
Location: kernel/time/timekeeping.c:836
Inline: False
Direct callers:
  - fs/timerfd.c:__ia32_sys_timerfd_create
  - fs/timerfd.c:__x64_sys_timerfd_create
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_read
  - fs/timerfd.c:timerfd_clock_was_set
  - drivers/input/evdev.c:evdev_events
  - drivers/input/evdev.c:evdev_events
```
**Symbols:**

```
ffffffff8112cf10-ffffffff8112cf42: ktime_mono_to_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ktime_t ktime_mono_to_any(ktime_t tmono, enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81138ee0)
Location: kernel/time/timekeeping.c:836
Inline: False
Direct callers:
  - fs/timerfd.c:__ia32_sys_timerfd_create
  - fs/timerfd.c:__x64_sys_timerfd_create
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_read
  - fs/timerfd.c:timerfd_clock_was_set
  - drivers/input/input.c:input_set_timestamp
  - drivers/input/input.c:input_set_timestamp
```
**Symbols:**

```
ffffffff81138ee0-ffffffff81138f12: ktime_mono_to_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ktime_t ktime_mono_to_any(ktime_t tmono, enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81147e40)
Location: kernel/time/timekeeping.c:836
Inline: False
Direct callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:__do_sys_timerfd_create
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_read
  - fs/timerfd.c:timerfd_clock_was_set
  - drivers/input/input.c:input_get_timestamp
  - drivers/input/input.c:input_get_timestamp
  - drivers/input/input.c:input_repeat_key
  - drivers/input/input.c:input_repeat_key
```
**Symbols:**

```
ffffffff81147e40-ffffffff81147e74: ktime_mono_to_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ktime_t ktime_mono_to_any(ktime_t tmono, enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81144270)
Location: kernel/time/timekeeping.c:906
Inline: False
Direct callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:__do_sys_timerfd_create
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_read
  - fs/timerfd.c:timerfd_clock_was_set
  - drivers/input/input.c:input_get_timestamp
  - drivers/input/input.c:input_get_timestamp
  - drivers/input/input.c:input_repeat_key
  - drivers/input/input.c:input_repeat_key
```
**Symbols:**

```
ffffffff81144270-ffffffff811442a7: ktime_mono_to_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ktime_t ktime_mono_to_any(ktime_t tmono, enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81145400)
Location: kernel/time/timekeeping.c:906
Inline: False
Direct callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:__do_sys_timerfd_create
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_read
  - fs/timerfd.c:timerfd_clock_was_set
  - drivers/input/input.c:input_get_timestamp
  - drivers/input/input.c:input_get_timestamp
  - drivers/input/input.c:input_repeat_key
  - drivers/input/input.c:input_repeat_key
```
**Symbols:**

```
ffffffff81145400-ffffffff81145434: ktime_mono_to_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ktime_t ktime_mono_to_any(ktime_t tmono, enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81168bc0)
Location: kernel/time/timekeeping.c:906
Inline: False
Direct callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:__do_sys_timerfd_create
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_read
  - fs/timerfd.c:timerfd_clock_was_set
  - drivers/input/input.c:input_get_timestamp
  - drivers/input/input.c:input_get_timestamp
  - drivers/input/input.c:input_repeat_key
  - drivers/input/input.c:input_repeat_key
```
**Symbols:**

```
ffffffff81168bc0-ffffffff81168c14: ktime_mono_to_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ktime_t ktime_mono_to_any(ktime_t tmono, enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8119c750)
Location: kernel/time/timekeeping.c:925
Inline: False
Direct callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:__do_sys_timerfd_create
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_read
  - fs/timerfd.c:timerfd_clock_was_set
  - drivers/input/input.c:input_get_timestamp
  - drivers/input/input.c:input_get_timestamp
  - drivers/input/input.c:input_repeat_key
  - drivers/input/input.c:input_repeat_key
```
**Symbols:**

```
ffffffff8119c750-ffffffff8119c7b0: ktime_mono_to_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ktime_t ktime_mono_to_any(ktime_t tmono, enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811db150)
Location: kernel/time/timekeeping.c:925
Inline: False
Direct callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:__do_sys_timerfd_create
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_read
  - fs/timerfd.c:timerfd_clock_was_set
  - drivers/input/input.c:input_repeat_key
  - drivers/input/input.c:input_repeat_key
  - drivers/input/input.c:input_get_timestamp
  - drivers/input/input.c:input_get_timestamp
```
**Symbols:**

```
ffffffff811db150-ffffffff811db1b0: ktime_mono_to_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ktime_t ktime_mono_to_any(ktime_t tmono, enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811ef6f0)
Location: kernel/time/timekeeping.c:925
Inline: False
Direct callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:__do_sys_timerfd_create
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_read
  - fs/timerfd.c:timerfd_clock_was_set
  - drivers/input/input.c:input_repeat_key
  - drivers/input/input.c:input_repeat_key
  - drivers/input/input.c:input_get_timestamp
  - drivers/input/input.c:input_get_timestamp
```
**Symbols:**

```
ffffffff811ef6f0-ffffffff811ef750: ktime_mono_to_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ktime_t ktime_mono_to_any(ktime_t tmono, enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81205780)
Location: kernel/time/timekeeping.c:925
Inline: False
Direct callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:__do_sys_timerfd_create
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_read
  - fs/timerfd.c:timerfd_clock_was_set
  - drivers/input/input.c:input_repeat_key
  - drivers/input/input.c:input_repeat_key
  - drivers/input/input.c:input_get_timestamp
  - drivers/input/input.c:input_get_timestamp
```
**Symbols:**

```
ffffffff81205780-ffffffff812057e0: ktime_mono_to_any (STB_GLOBAL)
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
ktime_t ktime_mono_to_any(ktime_t tmono, enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffff8000101a2bf0)
Location: kernel/time/timekeeping.c:836
Inline: False
Direct callers:
  - fs/timerfd.c:__arm64_sys_timerfd_create
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_read
  - fs/timerfd.c:timerfd_clock_was_set
  - drivers/input/input.c:input_set_timestamp
  - drivers/input/input.c:input_set_timestamp
```
**Symbols:**

```
ffff8000101a2bf0-ffff8000101a2c58: ktime_mono_to_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ktime_t ktime_mono_to_any(ktime_t tmono, enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (c03ec740)
Location: kernel/time/timekeeping.c:836
Inline: False
Direct callers:
  - fs/timerfd.c:__se_sys_timerfd_create
  - fs/timerfd.c:timerfd_clock_was_set
  - drivers/input/input.c:input_set_timestamp
  - drivers/input/input.c:input_set_timestamp
```
**Symbols:**

```
c03ec740-c03ec7c8: ktime_mono_to_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ktime_t ktime_mono_to_any(ktime_t tmono, enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (c0000000002040c0)
Location: kernel/time/timekeeping.c:836
Inline: False
Direct callers:
  - fs/timerfd.c:__se_sys_timerfd_create
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_read
  - fs/timerfd.c:timerfd_clock_was_set
  - drivers/input/input.c:input_set_timestamp
  - drivers/input/input.c:input_set_timestamp
```
**Symbols:**

```
c0000000002040c0-c00000000020412c: ktime_mono_to_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ktime_t ktime_mono_to_any(ktime_t tmono, enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffe00012f928)
Location: kernel/time/timekeeping.c:836
Inline: False
Direct callers:
  - fs/timerfd.c:__se_sys_timerfd_settime
  - fs/timerfd.c:__se_sys_timerfd_create
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_read
  - fs/timerfd.c:timerfd_clock_was_set
  - drivers/input/input.c:input_set_timestamp
  - drivers/input/input.c:input_set_timestamp
```
**Symbols:**

```
ffffffe00012f928-ffffffe00012f988: ktime_mono_to_any (STB_GLOBAL)
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
ktime_t ktime_mono_to_any(ktime_t tmono, enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81131690)
Location: kernel/time/timekeeping.c:836
Inline: False
Direct callers:
  - fs/timerfd.c:__ia32_sys_timerfd_create
  - fs/timerfd.c:__x64_sys_timerfd_create
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_read
  - fs/timerfd.c:timerfd_clock_was_set
  - drivers/input/input.c:input_set_timestamp
  - drivers/input/input.c:input_set_timestamp
```
**Symbols:**

```
ffffffff81131690-ffffffff811316c2: ktime_mono_to_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ktime_t ktime_mono_to_any(ktime_t tmono, enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811240f0)
Location: kernel/time/timekeeping.c:836
Inline: False
Direct callers:
  - fs/timerfd.c:__ia32_sys_timerfd_create
  - fs/timerfd.c:__x64_sys_timerfd_create
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_read
  - fs/timerfd.c:timerfd_clock_was_set
  - drivers/input/input.c:input_set_timestamp
  - drivers/input/input.c:input_set_timestamp
```
**Symbols:**

```
ffffffff811240f0-ffffffff81124122: ktime_mono_to_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ktime_t ktime_mono_to_any(ktime_t tmono, enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8112f3b0)
Location: kernel/time/timekeeping.c:836
Inline: False
Direct callers:
  - fs/timerfd.c:__ia32_sys_timerfd_create
  - fs/timerfd.c:__x64_sys_timerfd_create
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_read
  - fs/timerfd.c:timerfd_clock_was_set
  - drivers/input/input.c:input_set_timestamp
  - drivers/input/input.c:input_set_timestamp
```
**Symbols:**

```
ffffffff8112f3b0-ffffffff8112f3e2: ktime_mono_to_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ktime_t ktime_mono_to_any(ktime_t tmono, enum tk_offsets offs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8113bdd0)
Location: kernel/time/timekeeping.c:836
Inline: False
Direct callers:
  - fs/timerfd.c:__ia32_sys_timerfd_create
  - fs/timerfd.c:__x64_sys_timerfd_create
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_read
  - fs/timerfd.c:timerfd_clock_was_set
  - drivers/input/input.c:input_set_timestamp
  - drivers/input/input.c:input_set_timestamp
```
**Symbols:**

```
ffffffff8113bdd0-ffffffff8113be02: ktime_mono_to_any (STB_GLOBAL)
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
