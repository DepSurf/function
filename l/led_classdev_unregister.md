# Function: <code>led_classdev_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void led_classdev_unregister(struct led_classdev *led_cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-class.c (ffffffff816cde00)
Location: drivers/leds/led-class.c:241
Inline: False
Direct callers:
  - drivers/leds/led-class.c:devm_led_classdev_release
```
**Symbols:**

```
ffffffff816cde00-ffffffff816cdea9: led_classdev_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void led_classdev_unregister(struct led_classdev *led_cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-class.c (ffffffff81730ed0)
Location: drivers/leds/led-class.c:239
Inline: False
Direct callers:
  - drivers/leds/led-class.c:devm_led_classdev_release
```
**Symbols:**

```
ffffffff81730ed0-ffffffff81730f7d: led_classdev_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void led_classdev_unregister(struct led_classdev *led_cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-class.c (ffffffff81763e60)
Location: drivers/leds/led-class.c:241
Inline: False
Direct callers:
  - drivers/leds/led-class.c:devm_led_classdev_release
```
**Symbols:**

```
ffffffff81763e60-ffffffff81763f0d: led_classdev_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void led_classdev_unregister(struct led_classdev *led_cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-class.c (ffffffff81782580)
Location: drivers/leds/led-class.c:318
Inline: False
Direct callers:
  - drivers/leds/led-class.c:devm_led_classdev_release
```
**Symbols:**

```
ffffffff81782580-ffffffff8178264b: led_classdev_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void led_classdev_unregister(struct led_classdev *led_cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-class.c (ffffffff817f8930)
Location: drivers/leds/led-class.c:318
Inline: False
Direct callers:
  - drivers/leds/led-class.c:devm_led_classdev_release
```
**Symbols:**

```
ffffffff817f8930-ffffffff817f89fb: led_classdev_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void led_classdev_unregister(struct led_classdev *led_cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-class.c (ffffffff81841f20)
Location: drivers/leds/led-class.c:324
Inline: False
Direct callers:
  - drivers/leds/led-class.c:devm_led_classdev_release
```
**Symbols:**

```
ffffffff81841f20-ffffffff81841fed: led_classdev_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void led_classdev_unregister(struct led_classdev *led_cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-class.c (ffffffff8186de40)
Location: drivers/leds/led-class.c:324
Inline: False
Direct callers:
  - drivers/leds/led-class.c:devm_led_classdev_release
```
**Symbols:**

```
ffffffff8186de40-ffffffff8186df0d: led_classdev_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void led_classdev_unregister(struct led_classdev *led_cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-class.c (ffffffff818b20e0)
Location: drivers/leds/led-class.c:322
Inline: False
Direct callers:
  - drivers/leds/led-class.c:devm_led_classdev_release
```
**Symbols:**

```
ffffffff818b20e0-ffffffff818b21ab: led_classdev_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void led_classdev_unregister(struct led_classdev *led_cdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/leds/led-class.c (ffffffff818e4b58)
Location: drivers/leds/led-class.c:334
Inline: True
Inline callers:
  - drivers/leds/led-class.c:devm_led_classdev_release
Direct callers:
  - drivers/leds/led-class.c:devm_led_classdev_release
```
**Symbols:**

```
ffffffff818e4a50-ffffffff818e4b1b: led_classdev_unregister.part.0 (STB_LOCAL)
ffffffff818e4b20-ffffffff818e4b42: led_classdev_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void led_classdev_unregister(struct led_classdev *led_cdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/leds/led-class.c (ffffffff819b8018)
Location: drivers/leds/led-class.c:430
Inline: True
Inline callers:
  - drivers/leds/led-class.c:devm_led_classdev_release
Direct callers:
  - drivers/leds/led-class.c:devm_led_classdev_release
```
**Symbols:**

```
ffffffff819b7b60-ffffffff819b7c2b: led_classdev_unregister.part.0 (STB_LOCAL)
ffffffff819b7c30-ffffffff819b7c52: led_classdev_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void led_classdev_unregister(struct led_classdev *led_cdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/leds/led-class.c (ffffffff819ba4b8)
Location: drivers/leds/led-class.c:435
Inline: True
Inline callers:
  - drivers/leds/led-class.c:devm_led_classdev_release
Direct callers:
  - drivers/leds/led-class.c:devm_led_classdev_release
```
**Symbols:**

```
ffffffff819b9fe0-ffffffff819ba0ab: led_classdev_unregister.part.0 (STB_LOCAL)
ffffffff819ba0b0-ffffffff819ba0d2: led_classdev_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void led_classdev_unregister(struct led_classdev *led_cdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-class.c (ffffffff8199e7d0)
Location: drivers/leds/led-class.c:430
Inline: True
Direct callers:
  - drivers/leds/led-class.c:devm_led_classdev_release
```
**Symbols:**

```
ffffffff8199e7d0-ffffffff8199e8b6: led_classdev_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void led_classdev_unregister(struct led_classdev *led_cdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/leds/led-class.c (ffffffff81a4b480)
Location: drivers/leds/led-class.c:435
Inline: True
Direct callers:
  - drivers/leds/led-class.c:devm_led_classdev_release
```
**Symbols:**

```
ffffffff81a4b480-ffffffff81a4b56e: led_classdev_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void led_classdev_unregister(struct led_classdev *led_cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-class.c (ffffffff81bb99f0)
Location: drivers/leds/led-class.c:433
Inline: False
Direct callers:
  - drivers/leds/led-class.c:devm_led_classdev_release
```
**Symbols:**

```
ffffffff81bb99f0-ffffffff81bb9afc: led_classdev_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void led_classdev_unregister(struct led_classdev *led_cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-class.c (ffffffff81d5edd0)
Location: drivers/leds/led-class.c:437
Inline: False
Direct callers:
  - drivers/leds/led-class.c:devm_led_classdev_release
```
**Symbols:**

```
ffffffff81d5edd0-ffffffff81d5eedc: led_classdev_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void led_classdev_unregister(struct led_classdev *led_cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-class.c (ffffffff81dc9cc0)
Location: drivers/leds/led-class.c:532
Inline: False
Direct callers:
  - drivers/leds/led-class.c:devm_led_classdev_release
```
**Symbols:**

```
ffffffff81dc9cc0-ffffffff81dc9dcc: led_classdev_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void led_classdev_unregister(struct led_classdev *led_cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-class.c (ffffffff81e82890)
Location: drivers/leds/led-class.c:573
Inline: False
Direct callers:
  - drivers/leds/led-class.c:devm_led_classdev_release
```
**Symbols:**

```
ffffffff81e82890-ffffffff81e8299c: led_classdev_unregister (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void led_classdev_unregister(struct led_classdev *led_cdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/leds/led-class.c (ffff800010b49944)
Location: drivers/leds/led-class.c:334
Inline: True
Inline callers:
  - drivers/leds/led-class.c:devm_led_classdev_release
Direct callers:
  - drivers/leds/led-class.c:devm_led_classdev_release
```
**Symbols:**

```
ffff800010b49808-ffff800010b498e4: led_classdev_unregister.part.0 (STB_LOCAL)
ffff800010b498e8-ffff800010b49924: led_classdev_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void led_classdev_unregister(struct led_classdev *led_cdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/leds/led-class.c (c0c32da4)
Location: drivers/leds/led-class.c:334
Inline: True
Inline callers:
  - drivers/leds/led-class.c:devm_led_classdev_release
Direct callers:
  - drivers/mmc/host/sdhci.c:sdhci_remove_host
  - drivers/mmc/host/sdhci.c:sdhci_remove_host
  - drivers/mmc/host/sdhci.c:__sdhci_add_host
  - drivers/leds/led-class.c:devm_led_classdev_release
  - drivers/leds/leds-asic3.c:asic3_led_remove
```
**Symbols:**

```
c0c32c88-c0c32d5c: led_classdev_unregister.part.0 (STB_LOCAL)
c0c32d5c-c0c32d8c: led_classdev_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void led_classdev_unregister(struct led_classdev *led_cdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/leds/led-class.c (c000000000c3e034)
Location: drivers/leds/led-class.c:334
Inline: True
Inline callers:
  - drivers/leds/led-class.c:devm_led_classdev_release
Direct callers:
  - drivers/leds/led-class.c:devm_led_classdev_release
```
**Symbols:**

```
c000000000c3de90-c000000000c3dfe4: led_classdev_unregister.part.0 (STB_LOCAL)
c000000000c3dff0-c000000000c3e01c: led_classdev_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void led_classdev_unregister(struct led_classdev *led_cdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/leds/led-class.c (ffffffe00071cf5c)
Location: drivers/leds/led-class.c:334
Inline: True
Inline callers:
  - drivers/leds/led-class.c:devm_led_classdev_release
Direct callers:
  - drivers/leds/led-class.c:devm_led_classdev_release
```
**Symbols:**

```
ffffffe00071ce30-ffffffe00071cf10: led_classdev_unregister.part.0 (STB_LOCAL)
ffffffe00071cf10-ffffffe00071cf44: led_classdev_unregister (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void led_classdev_unregister(struct led_classdev *led_cdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/leds/led-class.c (ffffffff818d99b8)
Location: drivers/leds/led-class.c:334
Inline: True
Inline callers:
  - drivers/leds/led-class.c:devm_led_classdev_release
Direct callers:
  - drivers/leds/led-class.c:devm_led_classdev_release
```
**Symbols:**

```
ffffffff818d98b0-ffffffff818d997b: led_classdev_unregister.part.0 (STB_LOCAL)
ffffffff818d9980-ffffffff818d99a2: led_classdev_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void led_classdev_unregister(struct led_classdev *led_cdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/leds/led-class.c (ffffffff818f64d8)
Location: drivers/leds/led-class.c:334
Inline: True
Inline callers:
  - drivers/leds/led-class.c:devm_led_classdev_release
Direct callers:
  - drivers/leds/led-class.c:devm_led_classdev_release
```
**Symbols:**

```
ffffffff818f63d0-ffffffff818f649b: led_classdev_unregister.part.0 (STB_LOCAL)
ffffffff818f64a0-ffffffff818f64c2: led_classdev_unregister (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
