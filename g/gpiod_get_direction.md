# Function: <code>gpiod_get_direction</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int gpiod_get_direction(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81423f60)
Location: drivers/gpio/gpiolib.c:157
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:__gpiod_request
  - drivers/gpio/gpiolib.c:gpiolib_seq_show
  - drivers/gpio/gpiolib-sysfs.c:direction_show
```
**Symbols:**

```
ffffffff81423f60-ffffffff81423fc4: gpiod_get_direction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int gpiod_get_direction(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8146d560)
Location: drivers/gpio/gpiolib.c:179
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiolib_seq_show
  - drivers/gpio/gpiolib.c:__gpiod_request
  - drivers/gpio/gpiolib-sysfs.c:direction_show
```
**Symbols:**

```
ffffffff8146d560-ffffffff8146d5cd: gpiod_get_direction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int gpiod_get_direction(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8148f430)
Location: drivers/gpio/gpiolib.c:182
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiolib_seq_show
  - drivers/gpio/gpiolib.c:__gpiod_request
  - drivers/gpio/gpiolib-sysfs.c:direction_show
```
**Symbols:**

```
ffffffff8148f430-ffffffff8148f49d: gpiod_get_direction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int gpiod_get_direction(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8149a180)
Location: drivers/gpio/gpiolib.c:183
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiolib_seq_show
  - drivers/gpio/gpiolib.c:__gpiod_request
  - drivers/gpio/gpiolib-sysfs.c:direction_show
```
**Symbols:**

```
ffffffff8149a180-ffffffff8149a1df: gpiod_get_direction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int gpiod_get_direction(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814d8470)
Location: drivers/gpio/gpiolib.c:203
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiolib_seq_show
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib-sysfs.c:direction_show
```
**Symbols:**

```
ffffffff814d8470-ffffffff814d84d2: gpiod_get_direction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int gpiod_get_direction(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff815079c0)
Location: drivers/gpio/gpiolib.c:211
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiolib_seq_show
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib-sysfs.c:direction_show
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff815079c0-ffffffff81507a23: gpiod_get_direction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int gpiod_get_direction(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8151c170)
Location: drivers/gpio/gpiolib.c:212
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiolib_seq_show
  - drivers/gpio/gpiolib.c:gpiochip_lock_as_irq
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib-sysfs.c:direction_show
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff8151c170-ffffffff8151c1d3: gpiod_get_direction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int gpiod_get_direction(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8154a450)
Location: drivers/gpio/gpiolib.c:212
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiolib_seq_show
  - drivers/gpio/gpiolib.c:gpiochip_lock_as_irq
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib-sysfs.c:direction_show
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff8154a450-ffffffff8154a4b3: gpiod_get_direction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int gpiod_get_direction(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff815699c0)
Location: drivers/gpio/gpiolib.c:214
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiolib_seq_show
  - drivers/gpio/gpiolib.c:gpiochip_lock_as_irq
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib-sysfs.c:direction_show
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff815699c0-ffffffff81569a36: gpiod_get_direction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int gpiod_get_direction(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8160f630)
Location: drivers/gpio/gpiolib.c:215
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiolib_dbg_show
  - drivers/gpio/gpiolib.c:gpiochip_lock_as_irq
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib-sysfs.c:direction_show
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff8160f630-ffffffff8160f6ac: gpiod_get_direction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int gpiod_get_direction(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff816351e0)
Location: drivers/gpio/gpiolib.c:212
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiolib_dbg_show
  - drivers/gpio/gpiolib.c:gpiochip_lock_as_irq
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib-sysfs.c:direction_show
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff816351e0-ffffffff8163526a: gpiod_get_direction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int gpiod_get_direction(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81618c80)
Location: drivers/gpio/gpiolib.c:214
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiolib_seq_show
  - drivers/gpio/gpiolib.c:gpiochip_lock_as_irq
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib-sysfs.c:direction_show
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
```
**Symbols:**

```
ffffffff81618c80-ffffffff81618d02: gpiod_get_direction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int gpiod_get_direction(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81687f10)
Location: drivers/gpio/gpiolib.c:214
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiolib_seq_show
  - drivers/gpio/gpiolib.c:gpiochip_lock_as_irq
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib-sysfs.c:direction_show
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
```
**Symbols:**

```
ffffffff81687f10-ffffffff81687f92: gpiod_get_direction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int gpiod_get_direction(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff817a2a40)
Location: drivers/gpio/gpiolib.c:213
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiolib_seq_show
  - drivers/gpio/gpiolib.c:gpiochip_lock_as_irq
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib-sysfs.c:direction_show
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
```
**Symbols:**

```
ffffffff817a2a40-ffffffff817a2ad1: gpiod_get_direction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int gpiod_get_direction(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818ba0c0)
Location: drivers/gpio/gpiolib.c:214
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_lock_as_irq
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib-sysfs.c:direction_show
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
```
**Symbols:**

```
ffffffff818ba0c0-ffffffff818ba151: gpiod_get_direction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int gpiod_get_direction(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818fd1c0)
Location: drivers/gpio/gpiolib.c:233
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_lock_as_irq
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib-sysfs.c:direction_show
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
```
**Symbols:**

```
ffffffff818fd1c0-ffffffff818fd251: gpiod_get_direction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int gpiod_get_direction(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff819447d0)
Location: drivers/gpio/gpiolib.c:312
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_lock_as_irq
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib-sysfs.c:direction_show
  - drivers/i2c/i2c-core-base.c:i2c_init_recovery
```
**Symbols:**

```
ffffffff819447d0-ffffffff8194485b: gpiod_get_direction (STB_GLOBAL)
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
int gpiod_get_direction(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106c1760)
Location: drivers/gpio/gpiolib.c:214
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiolib_seq_show
  - drivers/gpio/gpiolib.c:gpiochip_lock_as_irq
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib-sysfs.c:direction_show
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffff8000106c1760-ffff8000106c184c: gpiod_get_direction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int gpiod_get_direction(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c085d5fc)
Location: drivers/gpio/gpiolib.c:214
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiolib_seq_show
  - drivers/gpio/gpiolib.c:gpiochip_lock_as_irq
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib-sysfs.c:direction_show
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
c085d5fc-c085d6b8: gpiod_get_direction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int gpiod_get_direction(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c000000000838db0)
Location: drivers/gpio/gpiolib.c:214
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiolib_seq_show
  - drivers/gpio/gpiolib.c:gpiochip_lock_as_irq
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib-sysfs.c:direction_show
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
c000000000838db0-c000000000838ee0: gpiod_get_direction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int gpiod_get_direction(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a3ee6)
Location: drivers/gpio/gpiolib.c:214
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiolib_seq_show
  - drivers/gpio/gpiolib.c:gpiochip_lock_as_irq
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib-sysfs.c:direction_show
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffe0004a3ee6-ffffffe0004a3f66: gpiod_get_direction (STB_GLOBAL)
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
int gpiod_get_direction(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8155f180)
Location: drivers/gpio/gpiolib.c:214
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiolib_seq_show
  - drivers/gpio/gpiolib.c:gpiochip_lock_as_irq
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib-sysfs.c:direction_show
```
**Symbols:**

```
ffffffff8155f180-ffffffff8155f1f6: gpiod_get_direction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int gpiod_get_direction(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8154ffd0)
Location: drivers/gpio/gpiolib.c:214
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiolib_seq_show
  - drivers/gpio/gpiolib.c:gpiochip_lock_as_irq
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib-sysfs.c:direction_show
```
**Symbols:**

```
ffffffff8154ffd0-ffffffff81550046: gpiod_get_direction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int gpiod_get_direction(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8155dcf0)
Location: drivers/gpio/gpiolib.c:214
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiolib_seq_show
  - drivers/gpio/gpiolib.c:gpiochip_lock_as_irq
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib-sysfs.c:direction_show
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff8155dcf0-ffffffff8155dd66: gpiod_get_direction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int gpiod_get_direction(struct gpio_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81577b80)
Location: drivers/gpio/gpiolib.c:214
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiolib_seq_show
  - drivers/gpio/gpiolib.c:gpiochip_lock_as_irq
  - drivers/gpio/gpiolib.c:gpiod_request_commit
  - drivers/gpio/gpiolib-sysfs.c:direction_show
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff81577b80-ffffffff81577bf6: gpiod_get_direction (STB_GLOBAL)
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
