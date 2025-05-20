# Function: <code>led_set_brightness_nosleep</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void led_set_brightness_nosleep(struct led_classdev *led_cdev, enum led_brightness value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff81730da7)
Location: drivers/leds/led-core.c:268
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_set_brightness
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
**Symbols:**

```
ffffffff81730aa0-ffffffff81730ac1: led_set_brightness_nosleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void led_set_brightness_nosleep(struct led_classdev *led_cdev, enum led_brightness value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff81763bf2)
Location: drivers/leds/led-core.c:270
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
**Symbols:**

```
ffffffff81763a80-ffffffff81763aa1: led_set_brightness_nosleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void led_set_brightness_nosleep(struct led_classdev *led_cdev, enum led_brightness value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff8178220f)
Location: drivers/leds/led-core.c:270
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
**Symbols:**

```
ffffffff81782080-ffffffff817820a2: led_set_brightness_nosleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void led_set_brightness_nosleep(struct led_classdev *led_cdev, enum led_brightness value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff817f85b2)
Location: drivers/leds/led-core.c:270
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
**Symbols:**

```
ffffffff817f8420-ffffffff817f8442: led_set_brightness_nosleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void led_set_brightness_nosleep(struct led_classdev *led_cdev, enum led_brightness value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff81841bad)
Location: drivers/leds/led-core.c:270
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
**Symbols:**

```
ffffffff81841a20-ffffffff81841a41: led_set_brightness_nosleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void led_set_brightness_nosleep(struct led_classdev *led_cdev, enum led_brightness value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff8186dad0)
Location: drivers/leds/led-core.c:270
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
**Symbols:**

```
ffffffff8186d940-ffffffff8186d961: led_set_brightness_nosleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void led_set_brightness_nosleep(struct led_classdev *led_cdev, enum led_brightness value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff818b1d73)
Location: drivers/leds/led-core.c:268
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
**Symbols:**

```
ffffffff818b1bb0-ffffffff818b1bd1: led_set_brightness_nosleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void led_set_brightness_nosleep(struct led_classdev *led_cdev, enum led_brightness value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff818e4523)
Location: drivers/leds/led-core.c:282
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
**Symbols:**

```
ffffffff818e4360-ffffffff818e4381: led_set_brightness_nosleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void led_set_brightness_nosleep(struct led_classdev *led_cdev, enum led_brightness value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff819b7510)
Location: drivers/leds/led-core.c:282
Inline: False
Direct callers:
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
**Symbols:**

```
ffffffff819b7510-ffffffff819b755a: led_set_brightness_nosleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void led_set_brightness_nosleep(struct led_classdev *led_cdev, enum led_brightness value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff819b9a10)
Location: drivers/leds/led-core.c:284
Inline: False
Direct callers:
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
**Symbols:**

```
ffffffff819b9a10-ffffffff819b9a5a: led_set_brightness_nosleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void led_set_brightness_nosleep(struct led_classdev *led_cdev, unsigned int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff8199e200)
Location: drivers/leds/led-core.c:280
Inline: False
Direct callers:
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
**Symbols:**

```
ffffffff8199e200-ffffffff8199e24b: led_set_brightness_nosleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void led_set_brightness_nosleep(struct led_classdev *led_cdev, unsigned int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff81a4ae80)
Location: drivers/leds/led-core.c:280
Inline: False
Direct callers:
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
**Symbols:**

```
ffffffff81a4ae80-ffffffff81a4aecb: led_set_brightness_nosleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void led_set_brightness_nosleep(struct led_classdev *led_cdev, unsigned int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff81bb9310)
Location: drivers/leds/led-core.c:280
Inline: False
Direct callers:
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
**Symbols:**

```
ffffffff81bb9310-ffffffff81bb937f: led_set_brightness_nosleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void led_set_brightness_nosleep(struct led_classdev *led_cdev, unsigned int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff81d5e5e0)
Location: drivers/leds/led-core.c:280
Inline: False
Direct callers:
  - drivers/leds/led-core.c:led_set_brightness
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
**Symbols:**

```
ffffffff81d5e5e0-ffffffff81d5e64f: led_set_brightness_nosleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void led_set_brightness_nosleep(struct led_classdev *led_cdev, unsigned int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff81dc931e)
Location: drivers/leds/led-core.c:335
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_set_brightness
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
**Symbols:**

```
ffffffff81dc9290-ffffffff81dc92e0: led_set_brightness_nosleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void led_set_brightness_nosleep(struct led_classdev *led_cdev, unsigned int value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff81e81dce)
Location: drivers/leds/led-core.c:340
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_set_brightness
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
**Symbols:**

```
ffffffff81e81d40-ffffffff81e81d90: led_set_brightness_nosleep (STB_GLOBAL)
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
void led_set_brightness_nosleep(struct led_classdev *led_cdev, enum led_brightness value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffff800010b48c74)
Location: drivers/leds/led-core.c:282
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
**Symbols:**

```
ffff800010b48a80-ffff800010b48ac4: led_set_brightness_nosleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void led_set_brightness_nosleep(struct led_classdev *led_cdev, enum led_brightness value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (c0c326e4)
Location: drivers/leds/led-core.c:282
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
**Symbols:**

```
c0c324e0-c0c32518: led_set_brightness_nosleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void led_set_brightness_nosleep(struct led_classdev *led_cdev, enum led_brightness value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (c000000000c3d568)
Location: drivers/leds/led-core.c:282
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
**Symbols:**

```
c000000000c3d240-c000000000c3d278: led_set_brightness_nosleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void led_set_brightness_nosleep(struct led_classdev *led_cdev, enum led_brightness value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffe00071c904)
Location: drivers/leds/led-core.c:282
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
**Symbols:**

```
ffffffe00071c72e-ffffffe00071c776: led_set_brightness_nosleep (STB_GLOBAL)
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
void led_set_brightness_nosleep(struct led_classdev *led_cdev, enum led_brightness value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff81887ee3)
Location: drivers/leds/led-core.c:282
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
**Symbols:**

```
ffffffff81887d20-ffffffff81887d41: led_set_brightness_nosleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void led_set_brightness_nosleep(struct led_classdev *led_cdev, enum led_brightness value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff8183f863)
Location: drivers/leds/led-core.c:282
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
**Symbols:**

```
ffffffff8183f6a0-ffffffff8183f6c1: led_set_brightness_nosleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void led_set_brightness_nosleep(struct led_classdev *led_cdev, enum led_brightness value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff818d9383)
Location: drivers/leds/led-core.c:282
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
**Symbols:**

```
ffffffff818d91c0-ffffffff818d91e1: led_set_brightness_nosleep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void led_set_brightness_nosleep(struct led_classdev *led_cdev, enum led_brightness value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff818f5ea3)
Location: drivers/leds/led-core.c:282
Inline: True
Inline callers:
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_blink_setup
  - drivers/leds/led-core.c:led_timer_function
  - drivers/leds/led-core.c:led_timer_function
```
**Symbols:**

```
ffffffff818f5ce0-ffffffff818f5d01: led_set_brightness_nosleep (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>enum led_brightness value</code> ➡️ <code>unsigned int value</code>
</li>
</ul>
</details>
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
