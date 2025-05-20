# Function: <code>led_blink_set_oneshot</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void led_blink_set_oneshot(struct led_classdev *led_cdev, long unsigned int *delay_on, long unsigned int *delay_off, int invert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff816cda20)
Location: drivers/leds/led-core.c:161
Inline: False
Direct callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_setup
```
**Symbols:**

```
ffffffff816cda20-ffffffff816cda79: led_blink_set_oneshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void led_blink_set_oneshot(struct led_classdev *led_cdev, long unsigned int *delay_on, long unsigned int *delay_off, int invert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff81730d20)
Location: drivers/leds/led-core.c:198
Inline: False
Direct callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_setup
```
**Symbols:**

```
ffffffff81730d20-ffffffff81730d78: led_blink_set_oneshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void led_blink_set_oneshot(struct led_classdev *led_cdev, long unsigned int *delay_on, long unsigned int *delay_off, int invert);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff81763cd0)
Location: drivers/leds/led-core.c:199
Inline: True
Direct callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_setup
```
**Symbols:**

```
ffffffff81763cd0-ffffffff81763d0d: led_blink_set_oneshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void led_blink_set_oneshot(struct led_classdev *led_cdev, long unsigned int *delay_on, long unsigned int *delay_off, int invert);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff817822d0)
Location: drivers/leds/led-core.c:199
Inline: True
Direct callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
**Symbols:**

```
ffffffff817822d0-ffffffff81782313: led_blink_set_oneshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void led_blink_set_oneshot(struct led_classdev *led_cdev, long unsigned int *delay_on, long unsigned int *delay_off, int invert);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff817f8680)
Location: drivers/leds/led-core.c:199
Inline: True
Direct callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
**Symbols:**

```
ffffffff817f8680-ffffffff817f86c3: led_blink_set_oneshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void led_blink_set_oneshot(struct led_classdev *led_cdev, long unsigned int *delay_on, long unsigned int *delay_off, int invert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff81841c80)
Location: drivers/leds/led-core.c:199
Inline: False
Direct callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
**Symbols:**

```
ffffffff81841c80-ffffffff81841cc2: led_blink_set_oneshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void led_blink_set_oneshot(struct led_classdev *led_cdev, long unsigned int *delay_on, long unsigned int *delay_off, int invert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff8186dba0)
Location: drivers/leds/led-core.c:199
Inline: False
Direct callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
**Symbols:**

```
ffffffff8186dba0-ffffffff8186dbe2: led_blink_set_oneshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void led_blink_set_oneshot(struct led_classdev *led_cdev, long unsigned int *delay_on, long unsigned int *delay_off, int invert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff818b1e50)
Location: drivers/leds/led-core.c:197
Inline: False
Direct callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
**Symbols:**

```
ffffffff818b1e50-ffffffff818b1e92: led_blink_set_oneshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void led_blink_set_oneshot(struct led_classdev *led_cdev, long unsigned int *delay_on, long unsigned int *delay_off, int invert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff818e4600)
Location: drivers/leds/led-core.c:211
Inline: False
Direct callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
**Symbols:**

```
ffffffff818e4600-ffffffff818e4642: led_blink_set_oneshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void led_blink_set_oneshot(struct led_classdev *led_cdev, long unsigned int *delay_on, long unsigned int *delay_off, int invert);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff819b76a0)
Location: drivers/leds/led-core.c:211
Inline: True
Direct callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
**Symbols:**

```
ffffffff819b76a0-ffffffff819b76e4: led_blink_set_oneshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void led_blink_set_oneshot(struct led_classdev *led_cdev, long unsigned int *delay_on, long unsigned int *delay_off, int invert);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff819b9ba0)
Location: drivers/leds/led-core.c:213
Inline: True
Direct callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
**Symbols:**

```
ffffffff819b9ba0-ffffffff819b9be4: led_blink_set_oneshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void led_blink_set_oneshot(struct led_classdev *led_cdev, long unsigned int *delay_on, long unsigned int *delay_off, int invert);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff8199e490)
Location: drivers/leds/led-core.c:211
Inline: True
Direct callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
**Symbols:**

```
ffffffff8199e490-ffffffff8199e4d4: led_blink_set_oneshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void led_blink_set_oneshot(struct led_classdev *led_cdev, long unsigned int *delay_on, long unsigned int *delay_off, int invert);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff81a4b110)
Location: drivers/leds/led-core.c:211
Inline: True
Direct callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
**Symbols:**

```
ffffffff81a4b110-ffffffff81a4b154: led_blink_set_oneshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void led_blink_set_oneshot(struct led_classdev *led_cdev, long unsigned int *delay_on, long unsigned int *delay_off, int invert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff81bb9610)
Location: drivers/leds/led-core.c:211
Inline: False
```
**Symbols:**

```
ffffffff81bb9610-ffffffff81bb967e: led_blink_set_oneshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void led_blink_set_oneshot(struct led_classdev *led_cdev, long unsigned int *delay_on, long unsigned int *delay_off, int invert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff81d5e920)
Location: drivers/leds/led-core.c:211
Inline: False
```
**Symbols:**

```
ffffffff81d5e920-ffffffff81d5e98e: led_blink_set_oneshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void led_blink_set_oneshot(struct led_classdev *led_cdev, long unsigned int *delay_on, long unsigned int *delay_off, int invert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff81dc9890)
Location: drivers/leds/led-core.c:235
Inline: False
Direct callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
**Symbols:**

```
ffffffff81dc9890-ffffffff81dc98fe: led_blink_set_oneshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void led_blink_set_oneshot(struct led_classdev *led_cdev, long unsigned int *delay_on, long unsigned int *delay_off, int invert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff81e82340)
Location: drivers/leds/led-core.c:240
Inline: False
Direct callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
**Symbols:**

```
ffffffff81e82340-ffffffff81e823ae: led_blink_set_oneshot (STB_GLOBAL)
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
void led_blink_set_oneshot(struct led_classdev *led_cdev, long unsigned int *delay_on, long unsigned int *delay_off, int invert);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffff800010b48e08)
Location: drivers/leds/led-core.c:211
Inline: True
Direct callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
**Symbols:**

```
ffff800010b48e08-ffff800010b48f04: led_blink_set_oneshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void led_blink_set_oneshot(struct led_classdev *led_cdev, long unsigned int *delay_on, long unsigned int *delay_off, int invert);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (c0c327c4)
Location: drivers/leds/led-core.c:211
Inline: True
Direct callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
**Symbols:**

```
c0c327c4-c0c3284c: led_blink_set_oneshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void led_blink_set_oneshot(struct led_classdev *led_cdev, long unsigned int *delay_on, long unsigned int *delay_off, int invert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (c000000000c3d720)
Location: drivers/leds/led-core.c:211
Inline: False
Direct callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
**Symbols:**

```
c000000000c3d720-c000000000c3d7b4: led_blink_set_oneshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void led_blink_set_oneshot(struct led_classdev *led_cdev, long unsigned int *delay_on, long unsigned int *delay_off, int invert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffe00071c9fc)
Location: drivers/leds/led-core.c:211
Inline: False
Direct callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
**Symbols:**

```
ffffffe00071c9fc-ffffffe00071ca7e: led_blink_set_oneshot (STB_GLOBAL)
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
void led_blink_set_oneshot(struct led_classdev *led_cdev, long unsigned int *delay_on, long unsigned int *delay_off, int invert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff81887fc0)
Location: drivers/leds/led-core.c:211
Inline: False
Direct callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
**Symbols:**

```
ffffffff81887fc0-ffffffff81888002: led_blink_set_oneshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void led_blink_set_oneshot(struct led_classdev *led_cdev, long unsigned int *delay_on, long unsigned int *delay_off, int invert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff8183f940)
Location: drivers/leds/led-core.c:211
Inline: False
Direct callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
**Symbols:**

```
ffffffff8183f940-ffffffff8183f982: led_blink_set_oneshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void led_blink_set_oneshot(struct led_classdev *led_cdev, long unsigned int *delay_on, long unsigned int *delay_off, int invert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff818d9460)
Location: drivers/leds/led-core.c:211
Inline: False
Direct callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
**Symbols:**

```
ffffffff818d9460-ffffffff818d94a2: led_blink_set_oneshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void led_blink_set_oneshot(struct led_classdev *led_cdev, long unsigned int *delay_on, long unsigned int *delay_off, int invert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff818f5f80)
Location: drivers/leds/led-core.c:211
Inline: False
Direct callers:
  - drivers/leds/led-triggers.c:led_trigger_blink_oneshot
```
**Symbols:**

```
ffffffff818f5f80-ffffffff818f5fc2: led_blink_set_oneshot (STB_GLOBAL)
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
