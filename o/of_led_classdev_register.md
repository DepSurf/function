# Function: <code>of_led_classdev_register</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int of_led_classdev_register(struct device *parent, struct device_node *np, struct led_classdev *led_cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-class.c (ffffffff81782760)
Location: drivers/leds/led-class.c:253
Inline: False
Direct callers:
  - drivers/leds/led-class.c:devm_of_led_classdev_register
```
**Symbols:**

```
ffffffff81782760-ffffffff81782a9e: of_led_classdev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int of_led_classdev_register(struct device *parent, struct device_node *np, struct led_classdev *led_cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-class.c (ffffffff817f8b10)
Location: drivers/leds/led-class.c:253
Inline: False
Direct callers:
  - drivers/leds/led-class.c:devm_of_led_classdev_register
```
**Symbols:**

```
ffffffff817f8b10-ffffffff817f8e4e: of_led_classdev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int of_led_classdev_register(struct device *parent, struct device_node *np, struct led_classdev *led_cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-class.c (ffffffff81842100)
Location: drivers/leds/led-class.c:253
Inline: False
Direct callers:
  - drivers/leds/led-class.c:devm_of_led_classdev_register
```
**Symbols:**

```
ffffffff81842100-ffffffff81842459: of_led_classdev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int of_led_classdev_register(struct device *parent, struct device_node *np, struct led_classdev *led_cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-class.c (ffffffff8186e020)
Location: drivers/leds/led-class.c:253
Inline: False
Direct callers:
  - drivers/leds/led-class.c:devm_of_led_classdev_register
```
**Symbols:**

```
ffffffff8186e020-ffffffff8186e379: of_led_classdev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int of_led_classdev_register(struct device *parent, struct device_node *np, struct led_classdev *led_cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/leds/led-class.c (0)
Location: drivers/leds/led-class.c:251
Inline: False
Direct callers:
  - drivers/leds/led-class.c:devm_of_led_classdev_register
```
**Symbols:**

```
ffffffff818b2664-ffffffff818b26e3: of_led_classdev_register.cold (STB_LOCAL)
ffffffff818b22c0-ffffffff818b2598: of_led_classdev_register (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>
