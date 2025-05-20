# Function: <code>led_set_brightness</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void led_set_brightness(struct led_classdev *led_cdev, enum led_brightness brightness);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff816cdc50)
Location: drivers/leds/led-core.c:190
Inline: True
Direct callers:
  - drivers/leds/led-class.c:led_classdev_unregister
  - drivers/leds/led-class.c:brightness_store
  - drivers/leds/led-triggers.c:led_trigger_event
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
ffffffff816cdc50-ffffffff816cdcfa: led_set_brightness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void led_set_brightness(struct led_classdev *led_cdev, enum led_brightness brightness);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff81730d80)
Location: drivers/leds/led-core.c:228
Inline: False
Direct callers:
  - drivers/leds/led-class.c:led_classdev_unregister
  - drivers/leds/led-class.c:brightness_store
  - drivers/leds/led-triggers.c:led_trigger_event
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
ffffffff81730d80-ffffffff81730dde: led_set_brightness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void led_set_brightness(struct led_classdev *led_cdev, enum led_brightness brightness);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff81763d10)
Location: drivers/leds/led-core.c:229
Inline: True
Direct callers:
  - drivers/leds/led-class.c:led_classdev_unregister
  - drivers/leds/led-class.c:brightness_store
  - drivers/leds/led-triggers.c:led_trigger_event
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
ffffffff81763d10-ffffffff81763d68: led_set_brightness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void led_set_brightness(struct led_classdev *led_cdev, enum led_brightness brightness);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff81782320)
Location: drivers/leds/led-core.c:229
Inline: True
Direct callers:
  - drivers/leds/led-class.c:led_classdev_unregister
  - drivers/leds/led-class.c:brightness_store
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
ffffffff81782320-ffffffff81782378: led_set_brightness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void led_set_brightness(struct led_classdev *led_cdev, enum led_brightness brightness);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff817f86d0)
Location: drivers/leds/led-core.c:229
Inline: True
Direct callers:
  - drivers/leds/led-class.c:led_classdev_unregister
  - drivers/leds/led-class.c:brightness_store
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
ffffffff817f86d0-ffffffff817f8728: led_set_brightness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void led_set_brightness(struct led_classdev *led_cdev, enum led_brightness brightness);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff81841cd0)
Location: drivers/leds/led-core.c:229
Inline: True
Direct callers:
  - drivers/leds/led-class.c:led_classdev_unregister
  - drivers/leds/led-class.c:brightness_store
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
ffffffff81841cd0-ffffffff81841d2a: led_set_brightness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void led_set_brightness(struct led_classdev *led_cdev, enum led_brightness brightness);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff8186dbf0)
Location: drivers/leds/led-core.c:229
Inline: True
Direct callers:
  - drivers/leds/led-class.c:led_classdev_unregister
  - drivers/leds/led-class.c:brightness_store
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
ffffffff8186dbf0-ffffffff8186dc4a: led_set_brightness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void led_set_brightness(struct led_classdev *led_cdev, enum led_brightness brightness);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff818b1ea0)
Location: drivers/leds/led-core.c:227
Inline: True
Direct callers:
  - drivers/leds/led-class.c:led_classdev_unregister
  - drivers/leds/led-class.c:brightness_store
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
ffffffff818b1ea0-ffffffff818b1efa: led_set_brightness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void led_set_brightness(struct led_classdev *led_cdev, enum led_brightness brightness);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff818e4650)
Location: drivers/leds/led-core.c:241
Inline: True
Direct callers:
  - drivers/leds/led-class.c:brightness_store
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
ffffffff818e4650-ffffffff818e46aa: led_set_brightness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void led_set_brightness(struct led_classdev *led_cdev, enum led_brightness brightness);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff819b76f0)
Location: drivers/leds/led-core.c:241
Inline: True
Direct callers:
  - drivers/leds/led-class.c:brightness_store
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
ffffffff819b76f0-ffffffff819b7738: led_set_brightness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void led_set_brightness(struct led_classdev *led_cdev, enum led_brightness brightness);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff819b9bf0)
Location: drivers/leds/led-core.c:243
Inline: True
Direct callers:
  - drivers/leds/led-class.c:brightness_store
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
ffffffff819b9bf0-ffffffff819b9c38: led_set_brightness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void led_set_brightness(struct led_classdev *led_cdev, unsigned int brightness);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff8199e4e0)
Location: drivers/leds/led-core.c:241
Inline: True
Direct callers:
  - drivers/leds/led-class.c:brightness_store
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
ffffffff8199e4e0-ffffffff8199e528: led_set_brightness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void led_set_brightness(struct led_classdev *led_cdev, unsigned int brightness);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff81a4b160)
Location: drivers/leds/led-core.c:241
Inline: True
Direct callers:
  - drivers/leds/led-class.c:brightness_store
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
ffffffff81a4b160-ffffffff81a4b1a8: led_set_brightness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void led_set_brightness(struct led_classdev *led_cdev, unsigned int brightness);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff81bb9680)
Location: drivers/leds/led-core.c:241
Inline: True
Direct callers:
  - drivers/leds/led-class.c:led_classdev_unregister
  - drivers/leds/led-class.c:brightness_store
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
ffffffff81bb9680-ffffffff81bb96ec: led_set_brightness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void led_set_brightness(struct led_classdev *led_cdev, unsigned int brightness);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff81d5e9a0)
Location: drivers/leds/led-core.c:241
Inline: False
Direct callers:
  - drivers/leds/led-class.c:led_classdev_unregister
  - drivers/leds/led-class.c:brightness_store
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
ffffffff81d5e9a0-ffffffff81d5ea0c: led_set_brightness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void led_set_brightness(struct led_classdev *led_cdev, unsigned int brightness);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff81dc92f0)
Location: drivers/leds/led-core.c:281
Inline: False
Direct callers:
  - drivers/leds/led-class.c:led_classdev_unregister
  - drivers/leds/led-class.c:brightness_store
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
ffffffff81dc92f0-ffffffff81dc9389: led_set_brightness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void led_set_brightness(struct led_classdev *led_cdev, unsigned int brightness);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff81e81da0)
Location: drivers/leds/led-core.c:286
Inline: False
Direct callers:
  - drivers/leds/led-class.c:led_classdev_unregister
  - drivers/leds/led-class.c:brightness_store
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
ffffffff81e81da0-ffffffff81e81e39: led_set_brightness (STB_GLOBAL)
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
void led_set_brightness(struct led_classdev *led_cdev, enum led_brightness brightness);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffff800010b48f08)
Location: drivers/leds/led-core.c:241
Inline: True
Direct callers:
  - drivers/leds/led-class.c:brightness_store
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
ffff800010b48f08-ffff800010b48fd8: led_set_brightness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void led_set_brightness(struct led_classdev *led_cdev, enum led_brightness brightness);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (c0c3284c)
Location: drivers/leds/led-core.c:241
Inline: True
Direct callers:
  - drivers/leds/led-class.c:brightness_store
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
c0c3284c-c0c328d8: led_set_brightness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void led_set_brightness(struct led_classdev *led_cdev, enum led_brightness brightness);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (c000000000c3d7c0)
Location: drivers/leds/led-core.c:241
Inline: True
Direct callers:
  - drivers/leds/led-class.c:brightness_store
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
c000000000c3d7c0-c000000000c3d89c: led_set_brightness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void led_set_brightness(struct led_classdev *led_cdev, enum led_brightness brightness);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffe00071ca7e)
Location: drivers/leds/led-core.c:241
Inline: True
Direct callers:
  - drivers/leds/led-class.c:brightness_store
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
ffffffe00071ca7e-ffffffe00071cb2c: led_set_brightness (STB_GLOBAL)
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
void led_set_brightness(struct led_classdev *led_cdev, enum led_brightness brightness);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff81888010)
Location: drivers/leds/led-core.c:241
Inline: True
Direct callers:
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
ffffffff81888010-ffffffff8188806a: led_set_brightness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void led_set_brightness(struct led_classdev *led_cdev, enum led_brightness brightness);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff8183f990)
Location: drivers/leds/led-core.c:241
Inline: True
Direct callers:
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
ffffffff8183f990-ffffffff8183f9ea: led_set_brightness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void led_set_brightness(struct led_classdev *led_cdev, enum led_brightness brightness);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff818d94b0)
Location: drivers/leds/led-core.c:241
Inline: True
Direct callers:
  - drivers/leds/led-class.c:brightness_store
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
ffffffff818d94b0-ffffffff818d950a: led_set_brightness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void led_set_brightness(struct led_classdev *led_cdev, enum led_brightness brightness);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-core.c (ffffffff818f5fd0)
Location: drivers/leds/led-core.c:241
Inline: True
Direct callers:
  - drivers/leds/led-class.c:brightness_store
  - drivers/leds/led-triggers.c:led_trigger_set
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
ffffffff818f5fd0-ffffffff818f602a: led_set_brightness (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>enum led_brightness brightness</code> ➡️ <code>unsigned int brightness</code>
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
