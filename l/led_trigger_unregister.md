# Function: <code>led_trigger_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void led_trigger_unregister(struct led_trigger *trig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff816ce8c0)
Location: drivers/leds/led-triggers.c:228
Inline: False
Direct callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister_simple
```
**Symbols:**

```
ffffffff816ce8c0-ffffffff816ce98c: led_trigger_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void led_trigger_unregister(struct led_trigger *trig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff81731920)
Location: drivers/leds/led-triggers.c:221
Inline: False
Direct callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister_simple
  - drivers/leds/led-triggers.c:devm_led_trigger_release
```
**Symbols:**

```
ffffffff81731920-ffffffff817319ec: led_trigger_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void led_trigger_unregister(struct led_trigger *trig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff817648f0)
Location: drivers/leds/led-triggers.c:228
Inline: False
Direct callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/leds/led-triggers.c:led_trigger_unregister_simple
  - drivers/leds/led-triggers.c:devm_led_trigger_release
```
**Symbols:**

```
ffffffff817648f0-ffffffff817649bc: led_trigger_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void led_trigger_unregister(struct led_trigger *trig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff81782fb0)
Location: drivers/leds/led-triggers.c:228
Inline: False
Direct callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/leds/led-triggers.c:led_trigger_unregister_simple
  - drivers/leds/led-triggers.c:devm_led_trigger_release
  - net/rfkill/core.c:rfkill_exit
```
**Symbols:**

```
ffffffff81782fb0-ffffffff8178307f: led_trigger_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void led_trigger_unregister(struct led_trigger *trig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff817f9370)
Location: drivers/leds/led-triggers.c:228
Inline: False
Direct callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/leds/led-triggers.c:led_trigger_unregister_simple
  - drivers/leds/led-triggers.c:devm_led_trigger_release
  - net/rfkill/core.c:rfkill_exit
```
**Symbols:**

```
ffffffff817f9370-ffffffff817f943f: led_trigger_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void led_trigger_unregister(struct led_trigger *trig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff81842970)
Location: drivers/leds/led-triggers.c:228
Inline: False
Direct callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/leds/led-triggers.c:led_trigger_unregister_simple
  - drivers/leds/led-triggers.c:devm_led_trigger_release
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_global_led_trigger_unregister
  - net/rfkill/core.c:rfkill_global_led_trigger_unregister
```
**Symbols:**

```
ffffffff81842970-ffffffff81842a3a: led_trigger_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void led_trigger_unregister(struct led_trigger *trig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff8186e980)
Location: drivers/leds/led-triggers.c:266
Inline: False
Direct callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/leds/led-triggers.c:led_trigger_unregister_simple
  - drivers/leds/led-triggers.c:devm_led_trigger_release
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_global_led_trigger_unregister
  - net/rfkill/core.c:rfkill_global_led_trigger_unregister
```
**Symbols:**

```
ffffffff8186e980-ffffffff8186ea4a: led_trigger_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void led_trigger_unregister(struct led_trigger *trig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff818b2c30)
Location: drivers/leds/led-triggers.c:262
Inline: False
Direct callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/leds/led-triggers.c:led_trigger_unregister_simple
  - drivers/leds/led-triggers.c:devm_led_trigger_release
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_global_led_trigger_unregister
  - net/rfkill/core.c:rfkill_global_led_trigger_unregister
```
**Symbols:**

```
ffffffff818b2c30-ffffffff818b2cfa: led_trigger_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void led_trigger_unregister(struct led_trigger *trig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff818e5550)
Location: drivers/leds/led-triggers.c:263
Inline: False
Direct callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/leds/led-triggers.c:led_trigger_unregister_simple
  - drivers/leds/led-triggers.c:devm_led_trigger_release
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_global_led_trigger_unregister
  - net/rfkill/core.c:rfkill_global_led_trigger_unregister
```
**Symbols:**

```
ffffffff818e5550-ffffffff818e561a: led_trigger_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void led_trigger_unregister(struct led_trigger *trig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff819b8820)
Location: drivers/leds/led-triggers.c:309
Inline: False
Direct callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/leds/led-triggers.c:led_trigger_unregister_simple
  - drivers/leds/led-triggers.c:devm_led_trigger_release
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_unregister
  - net/rfkill/core.c:rfkill_global_led_trigger_unregister
  - net/rfkill/core.c:rfkill_global_led_trigger_unregister
```
**Symbols:**

```
ffffffff819b8820-ffffffff819b88ea: led_trigger_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void led_trigger_unregister(struct led_trigger *trig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff819bac80)
Location: drivers/leds/led-triggers.c:323
Inline: False
Direct callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/leds/led-triggers.c:led_trigger_unregister_simple
  - drivers/leds/led-triggers.c:devm_led_trigger_release
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_unregister
  - net/rfkill/core.c:rfkill_global_led_trigger_unregister
  - net/rfkill/core.c:rfkill_global_led_trigger_unregister
```
**Symbols:**

```
ffffffff819bac80-ffffffff819bad4d: led_trigger_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void led_trigger_unregister(struct led_trigger *trig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff8199f4a0)
Location: drivers/leds/led-triggers.c:323
Inline: False
Direct callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/leds/led-triggers.c:led_trigger_unregister_simple
  - drivers/leds/led-triggers.c:devm_led_trigger_release
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_unregister
  - net/rfkill/core.c:rfkill_global_led_trigger_unregister
  - net/rfkill/core.c:rfkill_global_led_trigger_unregister
```
**Symbols:**

```
ffffffff8199f4a0-ffffffff8199f56d: led_trigger_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void led_trigger_unregister(struct led_trigger *trig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff81a4c140)
Location: drivers/leds/led-triggers.c:323
Inline: False
Direct callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/leds/led-triggers.c:led_trigger_unregister_simple
  - drivers/leds/led-triggers.c:devm_led_trigger_release
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_unregister
  - net/rfkill/core.c:rfkill_global_led_trigger_unregister
  - net/rfkill/core.c:rfkill_global_led_trigger_unregister
```
**Symbols:**

```
ffffffff81a4c140-ffffffff81a4c20d: led_trigger_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void led_trigger_unregister(struct led_trigger *trig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff81bba890)
Location: drivers/leds/led-triggers.c:326
Inline: False
Direct callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/leds/led-triggers.c:led_trigger_unregister_simple
  - drivers/leds/led-triggers.c:devm_led_trigger_release
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_unregister
  - net/rfkill/core.c:rfkill_global_led_trigger_unregister
  - net/rfkill/core.c:rfkill_global_led_trigger_unregister
```
**Symbols:**

```
ffffffff81bba890-ffffffff81bba96c: led_trigger_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void led_trigger_unregister(struct led_trigger *trig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff81d5fe30)
Location: drivers/leds/led-triggers.c:326
Inline: False
Direct callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/leds/led-triggers.c:led_trigger_unregister_simple
  - drivers/leds/led-triggers.c:devm_led_trigger_release
  - net/rfkill/core.c:rfkill_exit
  - net/rfkill/core.c:rfkill_exit
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_unregister
```
**Symbols:**

```
ffffffff81d5fe30-ffffffff81d5ff0c: led_trigger_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void led_trigger_unregister(struct led_trigger *trig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff81dcaf30)
Location: drivers/leds/led-triggers.c:327
Inline: False
Direct callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/leds/led-triggers.c:led_trigger_unregister_simple
  - drivers/leds/led-triggers.c:devm_led_trigger_release
  - net/rfkill/core.c:rfkill_exit
  - net/rfkill/core.c:rfkill_exit
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_unregister
```
**Symbols:**

```
ffffffff81dcaf30-ffffffff81dcb00c: led_trigger_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void led_trigger_unregister(struct led_trigger *trig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff81e83aa0)
Location: drivers/leds/led-triggers.c:314
Inline: False
Direct callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/leds/led-triggers.c:led_trigger_unregister_simple
  - drivers/leds/led-triggers.c:devm_led_trigger_release
  - net/rfkill/core.c:rfkill_exit
  - net/rfkill/core.c:rfkill_exit
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_unregister
```
**Symbols:**

```
ffffffff81e83aa0-ffffffff81e83b7c: led_trigger_unregister (STB_GLOBAL)
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
void led_trigger_unregister(struct led_trigger *trig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffff800010b4ab20)
Location: drivers/leds/led-triggers.c:263
Inline: False
Direct callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/leds/led-triggers.c:led_trigger_unregister_simple
  - drivers/leds/led-triggers.c:devm_led_trigger_release
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_global_led_trigger_unregister
  - net/rfkill/core.c:rfkill_global_led_trigger_unregister
```
**Symbols:**

```
ffff800010b4ab20-ffff800010b4ac2c: led_trigger_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void led_trigger_unregister(struct led_trigger *trig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (c0c336fc)
Location: drivers/leds/led-triggers.c:263
Inline: False
Direct callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/leds/led-triggers.c:led_trigger_unregister_simple
  - drivers/leds/led-triggers.c:devm_led_trigger_release
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_global_led_trigger_unregister
  - net/rfkill/core.c:rfkill_global_led_trigger_unregister
```
**Symbols:**

```
c0c336fc-c0c337d8: led_trigger_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void led_trigger_unregister(struct led_trigger *trig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (c000000000c3efb0)
Location: drivers/leds/led-triggers.c:263
Inline: False
Direct callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/leds/led-triggers.c:led_trigger_unregister_simple
  - drivers/leds/led-triggers.c:devm_led_trigger_release
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_unregister
  - net/rfkill/core.c:rfkill_global_led_trigger_unregister
  - net/rfkill/core.c:rfkill_global_led_trigger_unregister
```
**Symbols:**

```
c000000000c3efb0-c000000000c3f100: led_trigger_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void led_trigger_unregister(struct led_trigger *trig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffe00071d7f2)
Location: drivers/leds/led-triggers.c:263
Inline: False
Direct callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/leds/led-triggers.c:led_trigger_unregister_simple
  - drivers/leds/led-triggers.c:devm_led_trigger_release
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_global_led_trigger_unregister
  - net/rfkill/core.c:rfkill_global_led_trigger_unregister
```
**Symbols:**

```
ffffffe00071d7f2-ffffffe00071d8e8: led_trigger_unregister (STB_GLOBAL)
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
void led_trigger_unregister(struct led_trigger *trig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff818886e0)
Location: drivers/leds/led-triggers.c:263
Inline: False
Direct callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/leds/led-triggers.c:led_trigger_unregister_simple
  - drivers/leds/led-triggers.c:devm_led_trigger_release
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_global_led_trigger_unregister
  - net/rfkill/core.c:rfkill_global_led_trigger_unregister
```
**Symbols:**

```
ffffffff818886e0-ffffffff818887aa: led_trigger_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void led_trigger_unregister(struct led_trigger *trig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff81840060)
Location: drivers/leds/led-triggers.c:263
Inline: False
Direct callers:
  - drivers/leds/led-triggers.c:led_trigger_unregister_simple
  - drivers/leds/led-triggers.c:devm_led_trigger_release
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_global_led_trigger_unregister
  - net/rfkill/core.c:rfkill_global_led_trigger_unregister
```
**Symbols:**

```
ffffffff81840060-ffffffff8184012a: led_trigger_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void led_trigger_unregister(struct led_trigger *trig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff818da3b0)
Location: drivers/leds/led-triggers.c:263
Inline: False
Direct callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/leds/led-triggers.c:led_trigger_unregister_simple
  - drivers/leds/led-triggers.c:devm_led_trigger_release
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_global_led_trigger_unregister
  - net/rfkill/core.c:rfkill_global_led_trigger_unregister
```
**Symbols:**

```
ffffffff818da3b0-ffffffff818da47a: led_trigger_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void led_trigger_unregister(struct led_trigger *trig);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/leds/led-triggers.c (ffffffff818f6ed0)
Location: drivers/leds/led-triggers.c:263
Inline: False
Direct callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_unregister
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
  - drivers/leds/led-triggers.c:led_trigger_unregister_simple
  - drivers/leds/led-triggers.c:devm_led_trigger_release
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_global_led_trigger_unregister
  - net/rfkill/core.c:rfkill_global_led_trigger_unregister
```
**Symbols:**

```
ffffffff818f6ed0-ffffffff818f6f9a: led_trigger_unregister (STB_GLOBAL)
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
