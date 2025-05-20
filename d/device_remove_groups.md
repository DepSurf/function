# Function: <code>device_remove_groups</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void device_remove_groups(struct device *dev, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8154654e)
Location: drivers/base/core.c:463
Inline: True
Inline callers:
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
Direct callers:
  - drivers/base/bus.c:bus_add_device
  - drivers/base/bus.c:bus_remove_device
```
**Symbols:**

```
ffffffff81547de0-ffffffff81547df4: device_remove_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void device_remove_groups(struct device *dev, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8159a3a1)
Location: drivers/base/core.c:463
Inline: True
Inline callers:
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
Direct callers:
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
```
**Symbols:**

```
ffffffff81599a40-ffffffff81599a54: device_remove_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void device_remove_groups(struct device *dev, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815c8a90)
Location: drivers/base/core.c:1029
Inline: True
Inline callers:
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
Direct callers:
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
```
**Symbols:**

```
ffffffff815c7d10-ffffffff815c7d24: device_remove_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void device_remove_groups(struct device *dev, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815dd7ce)
Location: drivers/base/core.c:1027
Inline: True
Inline callers:
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
Direct callers:
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
```
**Symbols:**

```
ffffffff815dc9a0-ffffffff815dc9b4: device_remove_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void device_remove_groups(struct device *dev, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816447d4)
Location: drivers/base/core.c:1031
Inline: True
Inline callers:
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
Direct callers:
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
```
**Symbols:**

```
ffffffff81641840-ffffffff81641854: device_remove_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void device_remove_groups(struct device *dev, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8167fba8)
Location: drivers/base/core.c:1073
Inline: True
Inline callers:
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
Direct callers:
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
```
**Symbols:**

```
ffffffff8167cb70-ffffffff8167cb84: device_remove_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void device_remove_groups(struct device *dev, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169e8db)
Location: drivers/base/core.c:1147
Inline: True
Inline callers:
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
Direct callers:
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
ffffffff8169c500-ffffffff8169c514: device_remove_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void device_remove_groups(struct device *dev, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816d6e92)
Location: drivers/base/core.c:1292
Inline: True
Inline callers:
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
Direct callers:
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
ffffffff816d5290-ffffffff816d52a0: device_remove_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void device_remove_groups(struct device *dev, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816faf92)
Location: drivers/base/core.c:1329
Inline: True
Inline callers:
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
Direct callers:
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
ffffffff816f9040-ffffffff816f9050: device_remove_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void device_remove_groups(struct device *dev, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817b42c3)
Location: drivers/base/core.c:1807
Inline: True
Inline callers:
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
Direct callers:
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/dd.c:__device_release_driver
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
ffffffff817b1f10-ffffffff817b1f20: device_remove_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void device_remove_groups(struct device *dev, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817c6c60)
Location: drivers/base/core.c:2208
Inline: True
Inline callers:
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
Direct callers:
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:really_probe
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
ffffffff817c67e0-ffffffff817c67f0: device_remove_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void device_remove_groups(struct device *dev, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817aa120)
Location: drivers/base/core.c:2420
Inline: True
Inline callers:
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
Direct callers:
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:really_probe
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
ffffffff817a9ca0-ffffffff817a9cb0: device_remove_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void device_remove_groups(struct device *dev, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81833301)
Location: drivers/base/core.c:2476
Inline: True
Inline callers:
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
Direct callers:
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/dd.c:__device_release_driver
  - drivers/base/dd.c:really_probe
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
ffffffff81832e20-ffffffff81832e30: device_remove_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void device_remove_groups(struct device *dev, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81975cfd)
Location: drivers/base/core.c:2487
Inline: True
Inline callers:
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
Direct callers:
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
ffffffff81974690-ffffffff819746a8: device_remove_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void device_remove_groups(struct device *dev, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81ae1ccd)
Location: drivers/base/core.c:2724
Inline: True
Inline callers:
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
Direct callers:
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
ffffffff81adfe10-ffffffff81adfe28: device_remove_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void device_remove_groups(struct device *dev, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b2faed)
Location: drivers/base/core.c:2730
Inline: True
Inline callers:
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
Direct callers:
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
ffffffff81b2e030-ffffffff81b2e048: device_remove_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void device_remove_groups(struct device *dev, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b872ed)
Location: drivers/base/core.c:2745
Inline: True
Inline callers:
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
  - drivers/base/core.c:device_add_attrs
Direct callers:
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
ffffffff81b85830-ffffffff81b85848: device_remove_groups (STB_GLOBAL)
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
void device_remove_groups(struct device *dev, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffff8000108e5560)
Location: drivers/base/core.c:1329
Inline: True
Inline callers:
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
Direct callers:
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
ffff8000108e3128-ffff8000108e315c: device_remove_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void device_remove_groups(struct device *dev, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c09d3d18)
Location: drivers/base/core.c:1329
Inline: True
Inline callers:
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
Direct callers:
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
c09d1c38-c09d1c54: device_remove_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void device_remove_groups(struct device *dev, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c00000000097af48)
Location: drivers/base/core.c:1329
Inline: True
Inline callers:
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
Direct callers:
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
c000000000977ef0-c000000000977f24: device_remove_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void device_remove_groups(struct device *dev, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffe00057a26a)
Location: drivers/base/core.c:1329
Inline: True
Inline callers:
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
Direct callers:
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
ffffffe000578570-ffffffe0005785a2: device_remove_groups (STB_GLOBAL)
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
void device_remove_groups(struct device *dev, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816c0782)
Location: drivers/base/core.c:1329
Inline: True
Inline callers:
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
Direct callers:
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
ffffffff816be830-ffffffff816be840: device_remove_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void device_remove_groups(struct device *dev, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169ba32)
Location: drivers/base/core.c:1329
Inline: True
Inline callers:
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
Direct callers:
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
ffffffff81699ae0-ffffffff81699af0: device_remove_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void device_remove_groups(struct device *dev, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816eec52)
Location: drivers/base/core.c:1329
Inline: True
Inline callers:
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
Direct callers:
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
ffffffff816ecd00-ffffffff816ecd10: device_remove_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void device_remove_groups(struct device *dev, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81709172)
Location: drivers/base/core.c:1329
Inline: True
Inline callers:
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
  - drivers/base/core.c:device_remove_attrs
Direct callers:
  - drivers/base/bus.c:bus_remove_device
  - drivers/base/bus.c:bus_add_device
  - drivers/base/dd.c:device_release_driver_internal
  - drivers/leds/led-triggers.c:led_trigger_set
```
**Symbols:**

```
ffffffff81707540-ffffffff81707550: device_remove_groups (STB_GLOBAL)
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
