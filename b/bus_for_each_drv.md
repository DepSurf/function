# Function: <code>bus_for_each_drv</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int bus_for_each_drv(struct bus_type *bus, struct device_driver *start, void *data, int (*fn)(struct device_driver *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff815499b0)
Location: drivers/base/bus.c:451
Inline: False
Direct callers:
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:__device_attach
  - drivers/i2c/i2c-core.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff815499b0-ffffffff81549a5c: bus_for_each_drv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int bus_for_each_drv(struct bus_type *bus, struct device_driver *start, void *data, int (*fn)(struct device_driver *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff8159b600)
Location: drivers/base/bus.c:450
Inline: False
Direct callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/i2c/i2c-core.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff8159b600-ffffffff8159b6ac: bus_for_each_drv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int bus_for_each_drv(struct bus_type *bus, struct device_driver *start, void *data, int (*fn)(struct device_driver *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff815c9b60)
Location: drivers/base/bus.c:450
Inline: False
Direct callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/i2c/i2c-core.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff815c9b60-ffffffff815c9c0c: bus_for_each_drv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int bus_for_each_drv(struct bus_type *bus, struct device_driver *start, void *data, int (*fn)(struct device_driver *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff815de8a0)
Location: drivers/base/bus.c:450
Inline: False
Direct callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff815de8a0-ffffffff815de94a: bus_for_each_drv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int bus_for_each_drv(struct bus_type *bus, struct device_driver *start, void *data, int (*fn)(struct device_driver *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816458d0)
Location: drivers/base/bus.c:450
Inline: False
Direct callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff816458d0-ffffffff8164597c: bus_for_each_drv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int bus_for_each_drv(struct bus_type *bus, struct device_driver *start, void *data, int (*fn)(struct device_driver *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81680d20)
Location: drivers/base/bus.c:448
Inline: False
Direct callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff81680d20-ffffffff81680ddc: bus_for_each_drv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bus_for_each_drv(struct bus_type *bus, struct device_driver *start, void *data, int (*fn)(struct device_driver *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816a07b0)
Location: drivers/base/bus.c:451
Inline: False
Direct callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff816a07b0-ffffffff816a086d: bus_for_each_drv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bus_for_each_drv(struct bus_type *bus, struct device_driver *start, void *data, int (*fn)(struct device_driver *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816d96e0)
Location: drivers/base/bus.c:441
Inline: False
Direct callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff816d96e0-ffffffff816d97a5: bus_for_each_drv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bus_for_each_drv(struct bus_type *bus, struct device_driver *start, void *data, int (*fn)(struct device_driver *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816fd6e0)
Location: drivers/base/bus.c:417
Inline: False
Direct callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff816fd6e0-ffffffff816fd7a8: bus_for_each_drv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bus_for_each_drv(struct bus_type *bus, struct device_driver *start, void *data, int (*fn)(struct device_driver *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff817b6f50)
Location: drivers/base/bus.c:418
Inline: False
Direct callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff817b6f50-ffffffff817b7018: bus_for_each_drv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bus_for_each_drv(struct bus_type *bus, struct device_driver *start, void *data, int (*fn)(struct device_driver *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff817cbc80)
Location: drivers/base/bus.c:418
Inline: False
Direct callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff817cbc80-ffffffff817cbd48: bus_for_each_drv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bus_for_each_drv(struct bus_type *bus, struct device_driver *start, void *data, int (*fn)(struct device_driver *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff817af5f0)
Location: drivers/base/bus.c:418
Inline: False
Direct callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff817af5f0-ffffffff817af6b8: bus_for_each_drv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bus_for_each_drv(struct bus_type *bus, struct device_driver *start, void *data, int (*fn)(struct device_driver *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81838850)
Location: drivers/base/bus.c:414
Inline: False
Direct callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff81838850-ffffffff81838918: bus_for_each_drv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bus_for_each_drv(struct bus_type *bus, struct device_driver *start, void *data, int (*fn)(struct device_driver *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff8197ace0)
Location: drivers/base/bus.c:414
Inline: False
Direct callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/usb/core/generic.c:usb_generic_driver_match
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff8197ace0-ffffffff8197adbd: bus_for_each_drv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bus_for_each_drv(struct bus_type *bus, struct device_driver *start, void *data, int (*fn)(struct device_driver *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81ae7c50)
Location: drivers/base/bus.c:414
Inline: False
Direct callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/usb/core/generic.c:usb_generic_driver_match
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff81ae7c50-ffffffff81ae7d2d: bus_for_each_drv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bus_for_each_drv(const struct bus_type *bus, struct device_driver *start, void *data, int (*fn)(struct device_driver *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81b36410)
Location: drivers/base/bus.c:443
Inline: False
Direct callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/usb/core/generic.c:usb_generic_driver_match
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff81b36410-ffffffff81b36500: bus_for_each_drv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bus_for_each_drv(const struct bus_type *bus, struct device_driver *start, void *data, int (*fn)(struct device_driver *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81b8de30)
Location: drivers/base/bus.c:443
Inline: False
Direct callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/usb/core/generic.c:usb_generic_driver_match
  - drivers/i2c/i2c-core-base.c:i2c_del_adapter
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff81b8de30-ffffffff81b8df20: bus_for_each_drv (STB_GLOBAL)
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
int bus_for_each_drv(struct bus_type *bus, struct device_driver *start, void *data, int (*fn)(struct device_driver *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffff8000108e8338)
Location: drivers/base/bus.c:417
Inline: False
Direct callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffff8000108e8338-ffff8000108e8410: bus_for_each_drv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bus_for_each_drv(struct bus_type *bus, struct device_driver *start, void *data, int (*fn)(struct device_driver *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (c09d6740)
Location: drivers/base/bus.c:417
Inline: False
Direct callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
c09d6740-c09d6820: bus_for_each_drv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bus_for_each_drv(struct bus_type *bus, struct device_driver *start, void *data, int (*fn)(struct device_driver *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (c00000000097e6a0)
Location: drivers/base/bus.c:417
Inline: False
Direct callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
c00000000097e6a0-c00000000097e7c8: bus_for_each_drv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bus_for_each_drv(struct bus_type *bus, struct device_driver *start, void *data, int (*fn)(struct device_driver *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffe00057c5ec)
Location: drivers/base/bus.c:417
Inline: False
Direct callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffe00057c5ec-ffffffe00057c67e: bus_for_each_drv (STB_GLOBAL)
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
int bus_for_each_drv(struct bus_type *bus, struct device_driver *start, void *data, int (*fn)(struct device_driver *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816c2ed0)
Location: drivers/base/bus.c:417
Inline: False
Direct callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
```
**Symbols:**

```
ffffffff816c2ed0-ffffffff816c2f98: bus_for_each_drv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bus_for_each_drv(struct bus_type *bus, struct device_driver *start, void *data, int (*fn)(struct device_driver *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff8169e180)
Location: drivers/base/bus.c:417
Inline: False
Direct callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
```
**Symbols:**

```
ffffffff8169e180-ffffffff8169e248: bus_for_each_drv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bus_for_each_drv(struct bus_type *bus, struct device_driver *start, void *data, int (*fn)(struct device_driver *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816f13a0)
Location: drivers/base/bus.c:417
Inline: False
Direct callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff816f13a0-ffffffff816f1468: bus_for_each_drv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bus_for_each_drv(struct bus_type *bus, struct device_driver *start, void *data, int (*fn)(struct device_driver *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff8170bbe0)
Location: drivers/base/bus.c:417
Inline: False
Direct callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff8170bbe0-ffffffff8170bca8: bus_for_each_drv (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct bus_type *bus</code> ➡️ <code>const struct bus_type *bus</code>
</li>
</ul>
</details>
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
