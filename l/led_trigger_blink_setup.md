# Function: <code>led_trigger_blink_setup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void led_trigger_blink_setup(struct led_trigger *trig, long unsigned int *delay_on, long unsigned int *delay_off, int oneshot, int invert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff816ce9c0)
Location: drivers/leds/led-triggers.c:269
Inline: False
Direct callers:
  - drivers/leds/led-triggers.c:led_trigger_blink
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
**Symbols:**

```
ffffffff816ce9c0-ffffffff816cea68: led_trigger_blink_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void led_trigger_blink_setup(struct led_trigger *trig, long unsigned int *delay_on, long unsigned int *delay_off, int oneshot, int invert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff81731a40)
Location: drivers/leds/led-triggers.c:290
Inline: False
Direct callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
  - drivers/leds/led-triggers.c:led_trigger_blink
```
**Symbols:**

```
ffffffff81731a40-ffffffff81731ae8: led_trigger_blink_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void led_trigger_blink_setup(struct led_trigger *trig, long unsigned int *delay_on, long unsigned int *delay_off, int oneshot, int invert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff81764a10)
Location: drivers/leds/led-triggers.c:297
Inline: False
Direct callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
  - drivers/leds/led-triggers.c:led_trigger_blink
```
**Symbols:**

```
ffffffff81764a10-ffffffff81764ab8: led_trigger_blink_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff817833f5)
Location: drivers/leds/led-triggers.c:297
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff817f97b5)
Location: drivers/leds/led-triggers.c:297
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff81842dc5)
Location: drivers/leds/led-triggers.c:297
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff8186ee55)
Location: drivers/leds/led-triggers.c:335
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff818b3105)
Location: drivers/leds/led-triggers.c:331
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff818e5a25)
Location: drivers/leds/led-triggers.c:332
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff819b8ac5)
Location: drivers/leds/led-triggers.c:378
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff819bafc5)
Location: drivers/leds/led-triggers.c:393
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff8199f7d5)
Location: drivers/leds/led-triggers.c:393
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff81a4c475)
Location: drivers/leds/led-triggers.c:393
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff81bbac05)
Location: drivers/leds/led-triggers.c:395
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff81d60215)
Location: drivers/leds/led-triggers.c:395
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff81dcb479)
Location: drivers/leds/led-triggers.c:396
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
  - drivers/leds/led-triggers.c:led_trigger_blink
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff81e83fb9)
Location: drivers/leds/led-triggers.c:383
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
  - drivers/leds/led-triggers.c:led_trigger_blink
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffff800010b4a1ac)
Location: drivers/leds/led-triggers.c:332
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (c0c33b94)
Location: drivers/leds/led-triggers.c:332
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (c000000000c3faf8)
Location: drivers/leds/led-triggers.c:332
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
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
In drivers/leds/led-triggers.c (ffffffe00071dd70)
Location: drivers/leds/led-triggers.c:332
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff81888bb5)
Location: drivers/leds/led-triggers.c:332
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff81840535)
Location: drivers/leds/led-triggers.c:332
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff818da885)
Location: drivers/leds/led-triggers.c:332
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff818f73a5)
Location: drivers/leds/led-triggers.c:332
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
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
</ul>
