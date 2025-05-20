# Function: <code>tasklet_unlock_wait</code>

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
In kernel/softirq.c (ffffffff81084d4a)
Location: include/linux/interrupt.h:521
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_kill
```
```
In drivers/tty/vt/keyboard.c (ffffffff814f1c90)
Location: include/linux/interrupt.h:521
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
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
In kernel/softirq.c (ffffffff81088079)
Location: include/linux/interrupt.h:540
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_kill
```
```
In drivers/tty/vt/keyboard.c (ffffffff815428b0)
Location: include/linux/interrupt.h:540
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
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
In kernel/softirq.c (ffffffff8108cfd9)
Location: include/linux/interrupt.h:560
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_kill
```
```
In drivers/tty/vt/keyboard.c (ffffffff8156eef0)
Location: include/linux/interrupt.h:560
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
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
In kernel/softirq.c (ffffffff81089dd9)
Location: include/linux/interrupt.h:569
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_kill
```
```
In drivers/tty/vt/keyboard.c (ffffffff81583480)
Location: include/linux/interrupt.h:569
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
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
In kernel/softirq.c (ffffffff81090b19)
Location: include/linux/interrupt.h:571
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_kill
```
```
In drivers/tty/vt/keyboard.c (ffffffff815e7f80)
Location: include/linux/interrupt.h:571
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
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
In kernel/softirq.c (ffffffff810948bd)
Location: include/linux/interrupt.h:576
Inline: True
```
```
In drivers/tty/vt/keyboard.c (ffffffff81621250)
Location: include/linux/interrupt.h:576
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
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
In kernel/softirq.c (ffffffff8109cc1d)
Location: include/linux/interrupt.h:592
Inline: True
```
```
In drivers/tty/vt/keyboard.c (ffffffff8163e6a0)
Location: include/linux/interrupt.h:592
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
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
In kernel/softirq.c (0)
Location: include/linux/interrupt.h:621
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_kill
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/interrupt.h:621
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
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
In kernel/softirq.c (0)
Location: include/linux/interrupt.h:626
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_kill
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/interrupt.h:626
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
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
In kernel/softirq.c (0)
Location: include/linux/interrupt.h:640
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_kill
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/interrupt.h:640
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
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
In kernel/softirq.c (0)
Location: include/linux/interrupt.h:678
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_kill
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/interrupt.h:678
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void tasklet_unlock_wait(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810ab5b0)
Location: kernel/softirq.c:886
Inline: True
Direct callers:
  - kernel/softirq.c:tasklet_kill
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
```
**Symbols:**

```
ffffffff810ab5b0-ffffffff810ab64b: tasklet_unlock_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void tasklet_unlock_wait(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810bd170)
Location: kernel/softirq.c:885
Inline: True
Direct callers:
  - kernel/softirq.c:tasklet_kill
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
```
**Symbols:**

```
ffffffff810bd170-ffffffff810bd20b: tasklet_unlock_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void tasklet_unlock_wait(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810d4290)
Location: kernel/softirq.c:899
Inline: True
Direct callers:
  - kernel/softirq.c:tasklet_kill
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
```
**Symbols:**

```
ffffffff810d4290-ffffffff810d434f: tasklet_unlock_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tasklet_unlock_wait(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810f3000)
Location: kernel/softirq.c:899
Inline: False
Direct callers:
  - kernel/softirq.c:tasklet_kill
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
```
**Symbols:**

```
ffffffff810f3000-ffffffff810f30bf: tasklet_unlock_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tasklet_unlock_wait(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810ff340)
Location: kernel/softirq.c:886
Inline: False
Direct callers:
  - kernel/softirq.c:tasklet_kill
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
```
**Symbols:**

```
ffffffff810ff340-ffffffff810ff3ff: tasklet_unlock_wait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tasklet_unlock_wait(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff811089f0)
Location: kernel/softirq.c:886
Inline: False
Direct callers:
  - kernel/softirq.c:tasklet_kill
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
```
**Symbols:**

```
ffffffff811089f0-ffffffff81108aaf: tasklet_unlock_wait (STB_GLOBAL)
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
In kernel/softirq.c (ffff8000100fe9bc)
Location: include/linux/interrupt.h:626
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_kill
```
```
In drivers/dma/ipu/ipu_idmac.c (ffff80001080d488)
Location: include/linux/interrupt.h:626
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources
  - drivers/dma/ipu/ipu_idmac.c:__idmac_terminate_all
```
```
In drivers/tty/vt/keyboard.c (ffff80001086a558)
Location: include/linux/interrupt.h:626
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
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
In kernel/softirq.c (c035b81c)
Location: include/linux/interrupt.h:626
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_kill
```
```
In drivers/dma/ipu/ipu_idmac.c (c092813c)
Location: include/linux/interrupt.h:626
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_idmac.c:idmac_alloc_chan_resources
  - drivers/dma/ipu/ipu_idmac.c:__idmac_terminate_all
```
```
In drivers/tty/vt/keyboard.c (c096f37c)
Location: include/linux/interrupt.h:626
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
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
In kernel/softirq.c (c000000000145bbc)
Location: include/linux/interrupt.h:626
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_kill
```
```
In drivers/tty/vt/keyboard.c (c0000000009096c0)
Location: include/linux/interrupt.h:626
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
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
In kernel/softirq.c (ffffffe0000c6d2a)
Location: include/linux/interrupt.h:626
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_kill
```
```
In drivers/tty/vt/keyboard.c (ffffffe00053e500)
Location: include/linux/interrupt.h:626
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
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
In kernel/softirq.c (0)
Location: include/linux/interrupt.h:626
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_kill
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/interrupt.h:626
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_start
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
In kernel/softirq.c (0)
Location: include/linux/interrupt.h:626
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_kill
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/interrupt.h:626
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_start
```
```
In drivers/hv/channel.c (0)
Location: include/linux/interrupt.h:626
Inline: True
Inline callers:
  - drivers/hv/channel.c:vmbus_reset_channel_cb
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
In kernel/softirq.c (0)
Location: include/linux/interrupt.h:626
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_kill
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/interrupt.h:626
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
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
In kernel/softirq.c (0)
Location: include/linux/interrupt.h:626
Inline: True
Inline callers:
  - kernel/softirq.c:tasklet_kill
```
```
In drivers/tty/vt/keyboard.c (0)
Location: include/linux/interrupt.h:626
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_start
  - drivers/tty/vt/keyboard.c:kbd_led_trigger_activate
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
