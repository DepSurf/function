# Function: <code>led_put</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void led_put(struct led_classdev *led_cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-class.c (ffffffff819b79d0)
Location: drivers/leds/led-class.c:256
Inline: False
```
**Symbols:**

```
ffffffff819b79d0-ffffffff819b79f0: led_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void led_put(struct led_classdev *led_cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-class.c (ffffffff819b9e50)
Location: drivers/leds/led-class.c:256
Inline: False
```
**Symbols:**

```
ffffffff819b9e50-ffffffff819b9e70: led_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void led_put(struct led_classdev *led_cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-class.c (ffffffff8199e640)
Location: drivers/leds/led-class.c:255
Inline: False
```
**Symbols:**

```
ffffffff8199e640-ffffffff8199e660: led_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void led_put(struct led_classdev *led_cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-class.c (ffffffff81a4b2c0)
Location: drivers/leds/led-class.c:255
Inline: False
```
**Symbols:**

```
ffffffff81a4b2c0-ffffffff81a4b2e0: led_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void led_put(struct led_classdev *led_cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-class.c (ffffffff81bb9900)
Location: drivers/leds/led-class.c:255
Inline: False
```
**Symbols:**

```
ffffffff81bb9900-ffffffff81bb9928: led_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void led_put(struct led_classdev *led_cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-class.c (ffffffff81d5ec90)
Location: drivers/leds/led-class.c:258
Inline: False
```
**Symbols:**

```
ffffffff81d5ec90-ffffffff81d5ecc9: led_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void led_put(struct led_classdev *led_cdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-class.c (ffffffff81dca69d)
Location: drivers/leds/led-class.c:266
Inline: True
Inline callers:
  - drivers/leds/led-class.c:devm_led_release
Direct callers:
  - drivers/leds/led-class.c:devm_led_get
```
**Symbols:**

```
ffffffff81dc9ab0-ffffffff81dc9ae9: led_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void led_put(struct led_classdev *led_cdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-class.c (ffffffff81e8320d)
Location: drivers/leds/led-class.c:271
Inline: True
Inline callers:
  - drivers/leds/led-class.c:devm_led_release
Direct callers:
  - drivers/leds/led-class.c:devm_led_get
```
**Symbols:**

```
ffffffff81e82840-ffffffff81e82879: led_put (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
