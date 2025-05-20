# Function: <code>ktime_mono_to_real</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff81258106)
Location: include/linux/timekeeping.h:204
Inline: True
Inline callers:
  - fs/timerfd.c:timerfd_clock_was_set
  - fs/timerfd.c:SyS_timerfd_create
```
```
In drivers/input/evdev.c (ffffffff8166d581)
Location: include/linux/timekeeping.h:204
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_events
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff812815e2)
Location: include/linux/timekeeping.h:220
Inline: True
Inline callers:
  - fs/timerfd.c:SyS_timerfd_create
  - fs/timerfd.c:timerfd_clock_was_set
```
```
In drivers/input/evdev.c (ffffffff816cd811)
Location: include/linux/timekeeping.h:220
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_events
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff81294f71)
Location: include/linux/timekeeping.h:220
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:SyS_timerfd_create
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_read
  - fs/timerfd.c:timerfd_clock_was_set
```
```
In drivers/input/evdev.c (ffffffff816fb7b1)
Location: include/linux/timekeeping.h:220
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_events
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff812a21b3)
Location: include/linux/timekeeping.h:209
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:SyS_timerfd_create
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_read
  - fs/timerfd.c:timerfd_clock_was_set
```
```
In drivers/input/evdev.c (ffffffff81711221)
Location: include/linux/timekeeping.h:209
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_events
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff812c54d9)
Location: include/linux/timekeeping.h:89
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:SyS_timerfd_create
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_read
  - fs/timerfd.c:timerfd_clock_was_set
```
```
In drivers/input/evdev.c (ffffffff817824a1)
Location: include/linux/timekeeping.h:89
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_events
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff812ed9f0)
Location: include/linux/timekeeping.h:104
Inline: True
Inline callers:
  - fs/timerfd.c:__ia32_sys_timerfd_create
  - fs/timerfd.c:__x64_sys_timerfd_create
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_read
  - fs/timerfd.c:timerfd_clock_was_set
```
```
In drivers/input/evdev.c (ffffffff817c3d1a)
Location: include/linux/timekeeping.h:104
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_events
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff813026e0)
Location: include/linux/timekeeping.h:119
Inline: True
Inline callers:
  - fs/timerfd.c:__ia32_sys_timerfd_create
  - fs/timerfd.c:__x64_sys_timerfd_create
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_read
  - fs/timerfd.c:timerfd_clock_was_set
```
```
In drivers/input/evdev.c (ffffffff817eb2aa)
Location: include/linux/timekeeping.h:119
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_events
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff8132388f)
Location: include/linux/timekeeping.h:147
Inline: True
Inline callers:
  - fs/timerfd.c:__ia32_sys_timerfd_create
  - fs/timerfd.c:__x64_sys_timerfd_create
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_read
  - fs/timerfd.c:timerfd_clock_was_set
```
```
In drivers/input/evdev.c (ffffffff8182be1a)
Location: include/linux/timekeeping.h:147
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_events
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff813365ef)
Location: include/linux/timekeeping.h:147
Inline: True
Inline callers:
  - fs/timerfd.c:__ia32_sys_timerfd_create
  - fs/timerfd.c:__x64_sys_timerfd_create
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_read
  - fs/timerfd.c:timerfd_clock_was_set
```
```
In drivers/input/input.c (ffffffff81856c59)
Location: include/linux/timekeeping.h:147
Inline: True
Inline callers:
  - drivers/input/input.c:input_set_timestamp
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff81370f18)
Location: include/linux/timekeeping.h:147
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:__do_sys_timerfd_create
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_read
  - fs/timerfd.c:timerfd_clock_was_set
```
```
In drivers/input/input.c (ffffffff8192a33d)
Location: include/linux/timekeeping.h:147
Inline: True
Inline callers:
  - drivers/input/input.c:input_get_timestamp
  - drivers/input/input.c:input_repeat_key
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff8137ec96)
Location: include/linux/timekeeping.h:146
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:__do_sys_timerfd_create
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_read
  - fs/timerfd.c:timerfd_clock_was_set
```
```
In drivers/input/input.c (ffffffff8193167d)
Location: include/linux/timekeeping.h:146
Inline: True
Inline callers:
  - drivers/input/input.c:input_get_timestamp
  - drivers/input/input.c:input_repeat_key
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff81385916)
Location: include/linux/timekeeping.h:147
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:__do_sys_timerfd_create
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_read
  - fs/timerfd.c:timerfd_clock_was_set
```
```
In drivers/input/input.c (ffffffff81914c9d)
Location: include/linux/timekeeping.h:147
Inline: True
Inline callers:
  - drivers/input/input.c:input_get_timestamp
  - drivers/input/input.c:input_repeat_key
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff813d2a9c)
Location: include/linux/timekeeping.h:147
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:__do_sys_timerfd_create
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_read
  - fs/timerfd.c:timerfd_clock_was_set
```
```
In drivers/input/input.c (ffffffff819b6e2d)
Location: include/linux/timekeeping.h:147
Inline: True
Inline callers:
  - drivers/input/input.c:input_get_timestamp
  - drivers/input/input.c:input_repeat_key
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff8145b2f5)
Location: include/linux/timekeeping.h:147
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:__do_sys_timerfd_create
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_read
  - fs/timerfd.c:timerfd_clock_was_set
```
```
In drivers/input/input.c (ffffffff81b16b6d)
Location: include/linux/timekeeping.h:147
Inline: True
Inline callers:
  - drivers/input/input.c:input_get_timestamp
  - drivers/input/input.c:input_repeat_key
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff814ea905)
Location: include/linux/timekeeping.h:147
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:__do_sys_timerfd_create
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_read
  - fs/timerfd.c:timerfd_clock_was_set
```
```
In drivers/input/input.c (ffffffff81caa1bf)
Location: include/linux/timekeeping.h:147
Inline: True
Inline callers:
  - drivers/input/input.c:input_repeat_key
  - drivers/input/input.c:input_get_timestamp
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff815216a8)
Location: include/linux/timekeeping.h:147
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:__do_sys_timerfd_create
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_read
  - fs/timerfd.c:timerfd_clock_was_set
```
```
In drivers/input/input.c (ffffffff81d1178f)
Location: include/linux/timekeeping.h:147
Inline: True
Inline callers:
  - drivers/input/input.c:input_repeat_key
  - drivers/input/input.c:input_get_timestamp
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff81555ce8)
Location: include/linux/timekeeping.h:148
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_settime
  - fs/timerfd.c:__do_sys_timerfd_create
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_read
  - fs/timerfd.c:timerfd_clock_was_set
```
```
In drivers/input/input.c (ffffffff81dc738f)
Location: include/linux/timekeeping.h:148
Inline: True
Inline callers:
  - drivers/input/input.c:input_repeat_key
  - drivers/input/input.c:input_get_timestamp
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffff8000103f431c)
Location: include/linux/timekeeping.h:147
Inline: True
Inline callers:
  - fs/timerfd.c:__arm64_sys_timerfd_create
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_read
  - fs/timerfd.c:timerfd_clock_was_set
```
```
In drivers/input/input.c (ffff800010a95e80)
Location: include/linux/timekeeping.h:147
Inline: True
Inline callers:
  - drivers/input/input.c:input_set_timestamp
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (c05ca184)
Location: include/linux/timekeeping.h:147
Inline: True
Inline callers:
  - fs/timerfd.c:__se_sys_timerfd_create
  - fs/timerfd.c:timerfd_clock_was_set
```
```
In drivers/input/input.c (c0b78b40)
Location: include/linux/timekeeping.h:147
Inline: True
Inline callers:
  - drivers/input/input.c:input_set_timestamp
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (c0000000004fc518)
Location: include/linux/timekeeping.h:147
Inline: True
Inline callers:
  - fs/timerfd.c:__se_sys_timerfd_create
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_read
  - fs/timerfd.c:timerfd_clock_was_set
```
```
In drivers/input/input.c (c000000000b75458)
Location: include/linux/timekeeping.h:147
Inline: True
Inline callers:
  - drivers/input/input.c:input_set_timestamp
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
In fs/timerfd.c (ffffffe0002a5fec)
Location: include/linux/timekeeping.h:147
Inline: True
Inline callers:
  - fs/timerfd.c:__se_sys_timerfd_settime
  - fs/timerfd.c:__se_sys_timerfd_create
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_read
  - fs/timerfd.c:timerfd_clock_was_set
```
```
In drivers/input/input.c (ffffffe0006a7866)
Location: include/linux/timekeeping.h:147
Inline: True
Inline callers:
  - drivers/input/input.c:input_set_timestamp
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff8132ebcf)
Location: include/linux/timekeeping.h:147
Inline: True
Inline callers:
  - fs/timerfd.c:__ia32_sys_timerfd_create
  - fs/timerfd.c:__x64_sys_timerfd_create
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_read
  - fs/timerfd.c:timerfd_clock_was_set
```
```
In drivers/input/input.c (ffffffff8180bc69)
Location: include/linux/timekeeping.h:147
Inline: True
Inline callers:
  - drivers/input/input.c:input_set_timestamp
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff8131f80f)
Location: include/linux/timekeeping.h:147
Inline: True
Inline callers:
  - fs/timerfd.c:__ia32_sys_timerfd_create
  - fs/timerfd.c:__x64_sys_timerfd_create
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_read
  - fs/timerfd.c:timerfd_clock_was_set
```
```
In drivers/input/input.c (ffffffff817d33d9)
Location: include/linux/timekeeping.h:147
Inline: True
Inline callers:
  - drivers/input/input.c:input_set_timestamp
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff8132c69f)
Location: include/linux/timekeeping.h:147
Inline: True
Inline callers:
  - fs/timerfd.c:__ia32_sys_timerfd_create
  - fs/timerfd.c:__x64_sys_timerfd_create
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_read
  - fs/timerfd.c:timerfd_clock_was_set
```
```
In drivers/input/input.c (ffffffff8184ade9)
Location: include/linux/timekeeping.h:147
Inline: True
Inline callers:
  - drivers/input/input.c:input_set_timestamp
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff8133f0df)
Location: include/linux/timekeeping.h:147
Inline: True
Inline callers:
  - fs/timerfd.c:__ia32_sys_timerfd_create
  - fs/timerfd.c:__x64_sys_timerfd_create
  - fs/timerfd.c:timerfd_ioctl
  - fs/timerfd.c:timerfd_read
  - fs/timerfd.c:timerfd_clock_was_set
```
```
In drivers/input/input.c (ffffffff81866039)
Location: include/linux/timekeeping.h:147
Inline: True
Inline callers:
  - drivers/input/input.c:input_set_timestamp
```
</details>
</li>
</ul>

## Differences
