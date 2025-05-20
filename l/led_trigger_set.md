# Function: <code>led_trigger_set</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void led_trigger_set(struct led_classdev *led_cdev, struct led_trigger *trig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff816ce4b0)
Location: drivers/leds/led-triggers.c:111
Inline: False
Direct callers:
  - drivers/leds/led-class.c:led_classdev_unregister
  - drivers/leds/led-triggers.c:led_trigger_remove
  - drivers/leds/led-triggers.c:led_trigger_store
  - drivers/leds/led-triggers.c:led_trigger_set_default
  - drivers/leds/led-triggers.c:led_trigger_unregister
```
**Symbols:**

```
ffffffff816ce4b0-ffffffff816ce647: led_trigger_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void led_trigger_set(struct led_classdev *led_cdev, struct led_trigger *trig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff81731580)
Location: drivers/leds/led-triggers.c:104
Inline: False
Direct callers:
  - drivers/leds/led-class.c:led_classdev_unregister
  - drivers/leds/led-triggers.c:led_trigger_unregister
  - drivers/leds/led-triggers.c:led_trigger_set_default
  - drivers/leds/led-triggers.c:led_trigger_remove
  - drivers/leds/led-triggers.c:led_trigger_store
```
**Symbols:**

```
ffffffff81731580-ffffffff81731717: led_trigger_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void led_trigger_set(struct led_classdev *led_cdev, struct led_trigger *trig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff81764520)
Location: drivers/leds/led-triggers.c:106
Inline: False
Direct callers:
  - drivers/leds/led-class.c:led_classdev_unregister
  - drivers/leds/led-triggers.c:led_trigger_unregister
  - drivers/leds/led-triggers.c:led_trigger_set_default
  - drivers/leds/led-triggers.c:led_trigger_remove
  - drivers/leds/led-triggers.c:led_trigger_store
```
**Symbols:**

```
ffffffff81764520-ffffffff817646ee: led_trigger_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void led_trigger_set(struct led_classdev *led_cdev, struct led_trigger *trig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff81782c90)
Location: drivers/leds/led-triggers.c:106
Inline: False
Direct callers:
  - drivers/leds/led-class.c:led_classdev_unregister
  - drivers/leds/led-triggers.c:led_trigger_unregister
  - drivers/leds/led-triggers.c:led_trigger_remove
  - drivers/leds/led-triggers.c:led_trigger_store
```
**Symbols:**

```
ffffffff81782c90-ffffffff81782e5b: led_trigger_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void led_trigger_set(struct led_classdev *led_cdev, struct led_trigger *trig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff817f9040)
Location: drivers/leds/led-triggers.c:106
Inline: False
Direct callers:
  - drivers/leds/led-class.c:led_classdev_unregister
  - drivers/leds/led-triggers.c:led_trigger_unregister
  - drivers/leds/led-triggers.c:led_trigger_remove
  - drivers/leds/led-triggers.c:led_trigger_store
```
**Symbols:**

```
ffffffff817f9040-ffffffff817f9211: led_trigger_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void led_trigger_set(struct led_classdev *led_cdev, struct led_trigger *trig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff81842640)
Location: drivers/leds/led-triggers.c:106
Inline: False
Direct callers:
  - drivers/leds/led-class.c:led_classdev_unregister
  - drivers/leds/led-triggers.c:led_trigger_unregister
  - drivers/leds/led-triggers.c:led_trigger_remove
  - drivers/leds/led-triggers.c:led_trigger_store
```
**Symbols:**

```
ffffffff81842640-ffffffff81842811: led_trigger_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int led_trigger_set(struct led_classdev *led_cdev, struct led_trigger *trig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff8186e560)
Location: drivers/leds/led-triggers.c:106
Inline: False
Direct callers:
  - drivers/leds/led-class.c:led_classdev_unregister
  - drivers/leds/led-triggers.c:led_trigger_unregister
  - drivers/leds/led-triggers.c:led_trigger_remove
  - drivers/leds/led-triggers.c:led_trigger_store
```
**Symbols:**

```
ffffffff8186e560-ffffffff8186e823: led_trigger_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int led_trigger_set(struct led_classdev *led_cdev, struct led_trigger *trig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/leds/led-triggers.c (0)
Location: drivers/leds/led-triggers.c:102
Inline: False
Direct callers:
  - drivers/leds/led-class.c:led_classdev_unregister
  - drivers/leds/led-triggers.c:led_trigger_unregister
  - drivers/leds/led-triggers.c:led_trigger_remove
  - drivers/leds/led-triggers.c:led_trigger_store
```
**Symbols:**

```
ffffffff818b3204-ffffffff818b324d: led_trigger_set.cold (STB_LOCAL)
ffffffff818b2840-ffffffff818b2ad1: led_trigger_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int led_trigger_set(struct led_classdev *led_cdev, struct led_trigger *trig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/leds/led-triggers.c (0)
Location: drivers/leds/led-triggers.c:102
Inline: False
Direct callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister
  - drivers/leds/led-triggers.c:led_trigger_remove
  - drivers/leds/led-triggers.c:led_trigger_store
```
**Symbols:**

```
ffffffff818e5b24-ffffffff818e5b6d: led_trigger_set.cold (STB_LOCAL)
ffffffff818e5160-ffffffff818e5400: led_trigger_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int led_trigger_set(struct led_classdev *led_cdev, struct led_trigger *trig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/leds/led-triggers.c (0)
Location: drivers/leds/led-triggers.c:148
Inline: False
Direct callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister
  - drivers/leds/led-triggers.c:led_trigger_register
  - drivers/leds/led-triggers.c:led_trigger_write
  - drivers/leds/led-triggers.c:led_trigger_write
```
**Symbols:**

```
ffffffff819b8dde-ffffffff819b8e27: led_trigger_set.cold (STB_LOCAL)
ffffffff819b83f0-ffffffff819b8690: led_trigger_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int led_trigger_set(struct led_classdev *led_cdev, struct led_trigger *trig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/leds/led-triggers.c (0)
Location: drivers/leds/led-triggers.c:158
Inline: False
Direct callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister
  - drivers/leds/led-triggers.c:led_trigger_register
  - drivers/leds/led-triggers.c:led_trigger_write
  - drivers/leds/led-triggers.c:led_trigger_write
```
**Symbols:**

```
ffffffff81c2b468-ffffffff81c2b4b1: led_trigger_set.cold (STB_LOCAL)
ffffffff819ba820-ffffffff819baac0: led_trigger_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int led_trigger_set(struct led_classdev *led_cdev, struct led_trigger *trig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/leds/led-triggers.c (0)
Location: drivers/leds/led-triggers.c:158
Inline: False
Direct callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister
  - drivers/leds/led-triggers.c:led_trigger_register
  - drivers/leds/led-triggers.c:led_trigger_write
  - drivers/leds/led-triggers.c:led_trigger_write
```
**Symbols:**

```
ffffffff81c1d80f-ffffffff81c1d858: led_trigger_set.cold (STB_LOCAL)
ffffffff8199f040-ffffffff8199f2e0: led_trigger_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int led_trigger_set(struct led_classdev *led_cdev, struct led_trigger *trig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/leds/led-triggers.c (0)
Location: drivers/leds/led-triggers.c:158
Inline: False
Direct callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister
  - drivers/leds/led-triggers.c:led_trigger_register
  - drivers/leds/led-triggers.c:led_trigger_write
  - drivers/leds/led-triggers.c:led_trigger_write
```
**Symbols:**

```
ffffffff81d2eb2e-ffffffff81d2eb77: led_trigger_set.cold (STB_LOCAL)
ffffffff81a4bce0-ffffffff81a4bf80: led_trigger_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int led_trigger_set(struct led_classdev *led_cdev, struct led_trigger *trig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/leds/led-triggers.c (0)
Location: drivers/leds/led-triggers.c:158
Inline: False
Direct callers:
  - drivers/leds/led-class.c:led_classdev_unregister
  - drivers/leds/led-triggers.c:led_trigger_unregister
  - drivers/leds/led-triggers.c:led_trigger_register
  - drivers/leds/led-triggers.c:led_trigger_write
  - drivers/leds/led-triggers.c:led_trigger_write
```
**Symbols:**

```
ffffffff81efafa8-ffffffff81efaffc: led_trigger_set.cold (STB_LOCAL)
ffffffff81bba410-ffffffff81bba6a2: led_trigger_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int led_trigger_set(struct led_classdev *led_cdev, struct led_trigger *trig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff81d5f950)
Location: drivers/leds/led-triggers.c:158
Inline: False
Direct callers:
  - drivers/leds/led-class.c:led_classdev_unregister
  - drivers/leds/led-triggers.c:led_trigger_unregister
  - drivers/leds/led-triggers.c:led_trigger_register
  - drivers/leds/led-triggers.c:led_trigger_write
  - drivers/leds/led-triggers.c:led_trigger_write
```
**Symbols:**

```
ffffffff81d5f950-ffffffff81d5fc18: led_trigger_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int led_trigger_set(struct led_classdev *led_cdev, struct led_trigger *trig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff81dcaa50)
Location: drivers/leds/led-triggers.c:158
Inline: False
Direct callers:
  - drivers/leds/led-class.c:led_classdev_unregister
  - drivers/leds/led-triggers.c:led_trigger_unregister
  - drivers/leds/led-triggers.c:led_trigger_register
  - drivers/leds/led-triggers.c:led_trigger_write
  - drivers/leds/led-triggers.c:led_trigger_write
```
**Symbols:**

```
ffffffff81dcaa50-ffffffff81dcad1f: led_trigger_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int led_trigger_set(struct led_classdev *led_cdev, struct led_trigger *trig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff81e835c0)
Location: drivers/leds/led-triggers.c:158
Inline: False
Direct callers:
  - drivers/leds/led-class.c:led_classdev_unregister
  - drivers/leds/led-triggers.c:led_trigger_unregister
  - drivers/leds/led-triggers.c:led_trigger_register
  - drivers/leds/led-triggers.c:led_trigger_write
  - drivers/leds/led-triggers.c:led_trigger_write
```
**Symbols:**

```
ffffffff81e835c0-ffffffff81e8388f: led_trigger_set (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int led_trigger_set(struct led_classdev *led_cdev, struct led_trigger *trig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffff800010b4a270)
Location: drivers/leds/led-triggers.c:102
Inline: False
Direct callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister
  - drivers/leds/led-triggers.c:led_trigger_remove
  - drivers/leds/led-triggers.c:led_trigger_store
```
**Symbols:**

```
ffff800010b4a270-ffff800010b4a610: led_trigger_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int led_trigger_set(struct led_classdev *led_cdev, struct led_trigger *trig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (c0c33354)
Location: drivers/leds/led-triggers.c:102
Inline: False
Direct callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister
  - drivers/leds/led-triggers.c:led_trigger_remove
  - drivers/leds/led-triggers.c:led_trigger_store
```
**Symbols:**

```
c0c33354-c0c335c4: led_trigger_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int led_trigger_set(struct led_classdev *led_cdev, struct led_trigger *trig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (c000000000c3e980)
Location: drivers/leds/led-triggers.c:102
Inline: False
Direct callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister
  - drivers/leds/led-triggers.c:led_trigger_remove
  - drivers/leds/led-triggers.c:led_trigger_store
```
**Symbols:**

```
c000000000c3e980-c000000000c3ed1c: led_trigger_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int led_trigger_set(struct led_classdev *led_cdev, struct led_trigger *trig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffe00071d496)
Location: drivers/leds/led-triggers.c:102
Inline: False
Direct callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister
  - drivers/leds/led-triggers.c:led_trigger_remove
  - drivers/leds/led-triggers.c:led_trigger_store
```
**Symbols:**

```
ffffffe00071d496-ffffffe00071d69c: led_trigger_set (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int led_trigger_set(struct led_classdev *led_cdev, struct led_trigger *trig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/leds/led-triggers.c (0)
Location: drivers/leds/led-triggers.c:102
Inline: False
Direct callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister
  - drivers/leds/led-triggers.c:led_trigger_remove
  - drivers/leds/led-triggers.c:led_trigger_store
```
**Symbols:**

```
ffffffff81888cb4-ffffffff81888cfd: led_trigger_set.cold (STB_LOCAL)
ffffffff818882f0-ffffffff81888590: led_trigger_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int led_trigger_set(struct led_classdev *led_cdev, struct led_trigger *trig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/leds/led-triggers.c (0)
Location: drivers/leds/led-triggers.c:102
Inline: False
Direct callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister
  - drivers/leds/led-triggers.c:led_trigger_remove
  - drivers/leds/led-triggers.c:led_trigger_store
```
**Symbols:**

```
ffffffff81840634-ffffffff8184067d: led_trigger_set.cold (STB_LOCAL)
ffffffff8183fc70-ffffffff8183ff10: led_trigger_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int led_trigger_set(struct led_classdev *led_cdev, struct led_trigger *trig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/leds/led-triggers.c (0)
Location: drivers/leds/led-triggers.c:102
Inline: False
Direct callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister
  - drivers/leds/led-triggers.c:led_trigger_remove
  - drivers/leds/led-triggers.c:led_trigger_store
```
**Symbols:**

```
ffffffff818da984-ffffffff818da9cd: led_trigger_set.cold (STB_LOCAL)
ffffffff818d9fc0-ffffffff818da260: led_trigger_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int led_trigger_set(struct led_classdev *led_cdev, struct led_trigger *trig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/leds/led-triggers.c (0)
Location: drivers/leds/led-triggers.c:102
Inline: False
Direct callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister
  - drivers/leds/led-triggers.c:led_trigger_remove
  - drivers/leds/led-triggers.c:led_trigger_store
```
**Symbols:**

```
ffffffff818f74a4-ffffffff818f74ed: led_trigger_set.cold (STB_LOCAL)
ffffffff818f6ae0-ffffffff818f6d80: led_trigger_set (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
