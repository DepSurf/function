# Function: <code>led_classdev_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int led_classdev_register(struct device *parent, struct led_classdev *led_cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-class.c (ffffffff816ce080)
Location: drivers/leds/led-class.c:188
Inline: False
Direct callers:
  - drivers/leds/led-class.c:devm_led_classdev_register
```
**Symbols:**

```
ffffffff816ce080-ffffffff816ce273: led_classdev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int led_classdev_register(struct device *parent, struct led_classdev *led_cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-class.c (ffffffff81731150)
Location: drivers/leds/led-class.c:188
Inline: False
Direct callers:
  - drivers/leds/led-class.c:devm_led_classdev_register
```
**Symbols:**

```
ffffffff81731150-ffffffff81731336: led_classdev_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int led_classdev_register(struct device *parent, struct led_classdev *led_cdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-class.c (ffffffff817640e0)
Location: drivers/leds/led-class.c:189
Inline: False
Direct callers:
  - drivers/leds/led-class.c:devm_led_classdev_register
```
**Symbols:**

```
ffffffff817640e0-ffffffff817642ce: led_classdev_register (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/host/sdhci.c (c0c25710)
Location: include/linux/leds.h:178
Inline: True
Inline callers:
  - drivers/mmc/host/sdhci.c:__sdhci_add_host
```
```
In drivers/leds/leds-asic3.c (c0c33ffc)
Location: include/linux/leds.h:178
Inline: True
Inline callers:
  - drivers/leds/leds-asic3.c:asic3_led_probe
```
</details>
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
