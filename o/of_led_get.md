# Function: <code>of_led_get</code>

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
struct led_classdev *of_led_get(struct device_node *np, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-class.c (ffffffff819b78c0)
Location: drivers/leds/led-class.c:227
Inline: False
```
**Symbols:**

```
ffffffff819b78c0-ffffffff819b78d2: of_led_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct led_classdev *of_led_get(struct device_node *np, int index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-class.c (ffffffff819b9d40)
Location: drivers/leds/led-class.c:227
Inline: False
```
**Symbols:**

```
ffffffff819b9d40-ffffffff819b9d52: of_led_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct led_classdev *of_led_get(struct device_node *np, int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-class.c (ffffffff8199e530)
Location: drivers/leds/led-class.c:226
Inline: True
```
**Symbols:**

```
ffffffff8199e530-ffffffff8199e542: of_led_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct led_classdev *of_led_get(struct device_node *np, int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-class.c (ffffffff81a4b1b0)
Location: drivers/leds/led-class.c:226
Inline: True
```
**Symbols:**

```
ffffffff81a4b1b0-ffffffff81a4b1c2: of_led_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct led_classdev *of_led_get(struct device_node *np, int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-class.c (ffffffff81bb97c0)
Location: drivers/leds/led-class.c:226
Inline: True
```
**Symbols:**

```
ffffffff81bb97c0-ffffffff81bb97d6: of_led_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct led_classdev *of_led_get(struct device_node *np, int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-class.c (ffffffff81d5eaf0)
Location: drivers/leds/led-class.c:226
Inline: True
```
**Symbols:**

```
ffffffff81d5eaf0-ffffffff81d5eb06: of_led_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct led_classdev *of_led_get(struct device_node *np, int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-class.c (ffffffff81dc9910)
Location: drivers/leds/led-class.c:245
Inline: True
```
**Symbols:**

```
ffffffff81dc9910-ffffffff81dc9926: of_led_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct led_classdev *of_led_get(struct device_node *np, int index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-class.c (ffffffff81e823c0)
Location: drivers/leds/led-class.c:250
Inline: True
```
**Symbols:**

```
ffffffff81e823c0-ffffffff81e823d6: of_led_get (STB_GLOBAL)
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
