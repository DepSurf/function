# Function: <code>__serio_register_driver</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __serio_register_driver(struct serio_driver *drv, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/serio.c (ffffffff81663ca0)
Location: drivers/input/serio/serio.c:830
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_init
```
**Symbols:**

```
ffffffff81663ca0-ffffffff81663d37: __serio_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __serio_register_driver(struct serio_driver *drv, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/serio.c (ffffffff816c3ea0)
Location: drivers/input/serio/serio.c:830
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_init
```
**Symbols:**

```
ffffffff816c3ea0-ffffffff816c3f32: __serio_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __serio_register_driver(struct serio_driver *drv, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/serio.c (ffffffff816f1e60)
Location: drivers/input/serio/serio.c:830
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_init
```
**Symbols:**

```
ffffffff816f1e60-ffffffff816f1ef2: __serio_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __serio_register_driver(struct serio_driver *drv, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/serio.c (ffffffff81707750)
Location: drivers/input/serio/serio.c:830
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_init
```
**Symbols:**

```
ffffffff81707750-ffffffff817077e2: __serio_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __serio_register_driver(struct serio_driver *drv, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/serio.c (ffffffff81778930)
Location: drivers/input/serio/serio.c:830
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_init
```
**Symbols:**

```
ffffffff81778930-ffffffff817789c2: __serio_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int __serio_register_driver(struct serio_driver *drv, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/serio.c (0)
Location: drivers/input/serio/serio.c:830
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_init
```
**Symbols:**

```
ffffffff817ba231-ffffffff817ba248: __serio_register_driver.cold.8 (STB_LOCAL)
ffffffff817b96a0-ffffffff817b9718: __serio_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int __serio_register_driver(struct serio_driver *drv, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/serio.c (0)
Location: drivers/input/serio/serio.c:826
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_init
```
**Symbols:**

```
ffffffff817e165a-ffffffff817e1671: __serio_register_driver.cold.8 (STB_LOCAL)
ffffffff817e0ab0-ffffffff817e0b28: __serio_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __serio_register_driver(struct serio_driver *drv, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/serio.c (0)
Location: drivers/input/serio/serio.c:814
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_init
```
**Symbols:**

```
ffffffff81821ec9-ffffffff81821ee1: __serio_register_driver.cold (STB_LOCAL)
ffffffff81821390-ffffffff81821408: __serio_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int __serio_register_driver(struct serio_driver *drv, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/serio.c (0)
Location: drivers/input/serio/serio.c:814
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_init
```
**Symbols:**

```
ffffffff81853339-ffffffff81853351: __serio_register_driver.cold (STB_LOCAL)
ffffffff81852800-ffffffff81852878: __serio_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int __serio_register_driver(struct serio_driver *drv, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/serio.c (0)
Location: drivers/input/serio/serio.c:814
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_init
```
**Symbols:**

```
ffffffff819254f0-ffffffff81925508: __serio_register_driver.cold (STB_LOCAL)
ffffffff81924760-ffffffff819247d8: __serio_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int __serio_register_driver(struct serio_driver *drv, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/serio.c (0)
Location: drivers/input/serio/serio.c:814
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_init
```
**Symbols:**

```
ffffffff81c229bb-ffffffff81c229d3: __serio_register_driver.cold (STB_LOCAL)
ffffffff8192c510-ffffffff8192c588: __serio_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __serio_register_driver(struct serio_driver *drv, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/serio.c (0)
Location: drivers/input/serio/serio.c:814
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_init
```
**Symbols:**

```
ffffffff81c14bc0-ffffffff81c14bd8: __serio_register_driver.cold (STB_LOCAL)
ffffffff8190f960-ffffffff8190f9d8: __serio_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __serio_register_driver(struct serio_driver *drv, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/serio.c (0)
Location: drivers/input/serio/serio.c:813
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_init
```
**Symbols:**

```
ffffffff81d22211-ffffffff81d22245: __serio_register_driver.cold (STB_LOCAL)
ffffffff819b0830-ffffffff819b08c5: __serio_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __serio_register_driver(struct serio_driver *drv, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/serio.c (0)
Location: drivers/input/serio/serio.c:813
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_init
```
**Symbols:**

```
ffffffff81eedde1-ffffffff81eede15: __serio_register_driver.cold (STB_LOCAL)
ffffffff81b0f640-ffffffff81b0f6dd: __serio_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __serio_register_driver(struct serio_driver *drv, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/serio.c (0)
Location: drivers/input/serio/serio.c:810
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_init
```
**Symbols:**

```
ffffffff820a5f24-ffffffff820a5f41: __serio_register_driver.cold (STB_LOCAL)
ffffffff81c9fab0-ffffffff81c9fb75: __serio_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __serio_register_driver(struct serio_driver *drv, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/serio.c (0)
Location: drivers/input/serio/serio.c:810
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_init
```
**Symbols:**

```
ffffffff8212732e-ffffffff8212734b: __serio_register_driver.cold (STB_LOCAL)
ffffffff81d06df0-ffffffff81d06eb3: __serio_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __serio_register_driver(struct serio_driver *drv, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/serio.c (0)
Location: drivers/input/serio/serio.c:810
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_init
```
**Symbols:**

```
ffffffff82208caf-ffffffff82208ccc: __serio_register_driver.cold (STB_LOCAL)
ffffffff81dbca20-ffffffff81dbcae3: __serio_register_driver (STB_GLOBAL)
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
int __serio_register_driver(struct serio_driver *drv, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/serio.c (ffff800010a92a00)
Location: drivers/input/serio/serio.c:814
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_init
```
**Symbols:**

```
ffff800010a92a00-ffff800010a92ab4: __serio_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __serio_register_driver(struct serio_driver *drv, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/serio.c (c0b760e4)
Location: drivers/input/serio/serio.c:814
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_init
```
**Symbols:**

```
c0b760e4-c0b76180: __serio_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __serio_register_driver(struct serio_driver *drv, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/serio.c (c000000000b6eb60)
Location: drivers/input/serio/serio.c:814
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_init
```
**Symbols:**

```
c000000000b6eb60-c000000000b6ec48: __serio_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __serio_register_driver(struct serio_driver *drv, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/serio.c (ffffffe0006a504e)
Location: drivers/input/serio/serio.c:814
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_init
```
**Symbols:**

```
ffffffe0006a504e-ffffffe0006a50ee: __serio_register_driver (STB_GLOBAL)
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
int __serio_register_driver(struct serio_driver *drv, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/serio.c (0)
Location: drivers/input/serio/serio.c:814
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_init
```
**Symbols:**

```
ffffffff81808419-ffffffff81808431: __serio_register_driver.cold (STB_LOCAL)
ffffffff818078e0-ffffffff81807958: __serio_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int __serio_register_driver(struct serio_driver *drv, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/serio.c (0)
Location: drivers/input/serio/serio.c:814
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_init
```
**Symbols:**

```
ffffffff817cfaf9-ffffffff817cfb11: __serio_register_driver.cold (STB_LOCAL)
ffffffff817ceff0-ffffffff817cf068: __serio_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int __serio_register_driver(struct serio_driver *drv, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/serio.c (0)
Location: drivers/input/serio/serio.c:814
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_init
```
**Symbols:**

```
ffffffff818474c9-ffffffff818474e1: __serio_register_driver.cold (STB_LOCAL)
ffffffff81846990-ffffffff81846a08: __serio_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int __serio_register_driver(struct serio_driver *drv, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/serio.c (0)
Location: drivers/input/serio/serio.c:814
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_init
```
**Symbols:**

```
ffffffff81862706-ffffffff8186271e: __serio_register_driver.cold (STB_LOCAL)
ffffffff81861fa0-ffffffff81862018: __serio_register_driver (STB_GLOBAL)
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
