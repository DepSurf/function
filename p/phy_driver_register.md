# Function: <code>phy_driver_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int phy_driver_register(struct phy_driver *new_driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff815ec050)
Location: drivers/net/phy/phy_device.c:1386
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_drivers_register
```
**Symbols:**

```
ffffffff815ec050-ffffffff815ec0e9: phy_driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int phy_driver_register(struct phy_driver *new_driver, struct module *owner);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff8164aec0)
Location: drivers/net/phy/phy_device.c:1627
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_drivers_register
```
**Symbols:**

```
ffffffff8164aec0-ffffffff8164af4e: phy_driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int phy_driver_register(struct phy_driver *new_driver, struct module *owner);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff8167c400)
Location: drivers/net/phy/phy_device.c:1803
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_drivers_register
```
**Symbols:**

```
ffffffff8167c400-ffffffff8167c48e: phy_driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int phy_driver_register(struct phy_driver *new_driver, struct module *owner);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81691460)
Location: drivers/net/phy/phy_device.c:1813
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_drivers_register
```
**Symbols:**

```
ffffffff81691460-ffffffff816914ee: phy_driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int phy_driver_register(struct phy_driver *new_driver, struct module *owner);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff816fb260)
Location: drivers/net/phy/phy_device.c:1861
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_drivers_register
```
**Symbols:**

```
ffffffff816fb260-ffffffff816fb2ee: phy_driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int phy_driver_register(struct phy_driver *new_driver, struct module *owner);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:1908
Inline: True
Direct callers:
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_drivers_register
```
**Symbols:**

```
ffffffff81739059-ffffffff81739073: phy_driver_register.cold.28 (STB_LOCAL)
ffffffff81738860-ffffffff817388de: phy_driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int phy_driver_register(struct phy_driver *new_driver, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:2254
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_drivers_register
```
**Symbols:**

```
ffffffff8175c74b-ffffffff8175c765: phy_driver_register.cold.30 (STB_LOCAL)
ffffffff8175ae50-ffffffff8175aef8: phy_driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int phy_driver_register(struct phy_driver *new_driver, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:2337
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_drivers_register
```
**Symbols:**

```
ffffffff81799b8a-ffffffff81799bd1: phy_driver_register.cold (STB_LOCAL)
ffffffff81798440-ffffffff817984da: phy_driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int phy_driver_register(struct phy_driver *new_driver, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:2306
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_drivers_register
```
**Symbols:**

```
ffffffff817bd696-ffffffff817bd6cd: phy_driver_register.cold (STB_LOCAL)
ffffffff817bbde0-ffffffff817bbe7a: phy_driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int phy_driver_register(struct phy_driver *new_driver, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:2805
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_drivers_register
```
**Symbols:**

```
ffffffff81885e33-ffffffff81885e6a: phy_driver_register.cold (STB_LOCAL)
ffffffff81883840-ffffffff818838e1: phy_driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int phy_driver_register(struct phy_driver *new_driver, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:2961
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_drivers_register
```
**Symbols:**

```
ffffffff81c192d6-ffffffff81c1930d: phy_driver_register.cold (STB_LOCAL)
ffffffff81891f90-ffffffff81892039: phy_driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int phy_driver_register(struct phy_driver *new_driver, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:3007
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_drivers_register
```
**Symbols:**

```
ffffffff81c0b104-ffffffff81c0b13b: phy_driver_register.cold (STB_LOCAL)
ffffffff818745d0-ffffffff81874679: phy_driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int phy_driver_register(struct phy_driver *new_driver, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:3139
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_drivers_register
```
**Symbols:**

```
ffffffff81d104f4-ffffffff81d1052b: phy_driver_register.cold (STB_LOCAL)
ffffffff81904fb0-ffffffff81905056: phy_driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int phy_driver_register(struct phy_driver *new_driver, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:3167
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_drivers_register
```
**Symbols:**

```
ffffffff81edb299-ffffffff81edb2c9: phy_driver_register.cold (STB_LOCAL)
ffffffff81a58190-ffffffff81a5827d: phy_driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int phy_driver_register(struct phy_driver *new_driver, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81be1f70)
Location: drivers/net/phy/phy_device.c:3173
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_drivers_register
```
**Symbols:**

```
ffffffff81be1f70-ffffffff81be2092: phy_driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int phy_driver_register(struct phy_driver *new_driver, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81c398a0)
Location: drivers/net/phy/phy_device.c:3343
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_drivers_register
```
**Symbols:**

```
ffffffff81c398a0-ffffffff81c399ba: phy_driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int phy_driver_register(struct phy_driver *new_driver, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81ceec30)
Location: drivers/net/phy/phy_device.c:3418
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_drivers_register
```
**Symbols:**

```
ffffffff81ceec30-ffffffff81ceed4a: phy_driver_register (STB_GLOBAL)
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
int phy_driver_register(struct phy_driver *new_driver, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffff8000109d4ce0)
Location: drivers/net/phy/phy_device.c:2306
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_drivers_register
```
**Symbols:**

```
ffff8000109d4ce0-ffff8000109d4dcc: phy_driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int phy_driver_register(struct phy_driver *new_driver, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (c0abc898)
Location: drivers/net/phy/phy_device.c:2306
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_drivers_register
```
**Symbols:**

```
c0abc898-c0abc990: phy_driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int phy_driver_register(struct phy_driver *new_driver, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (c000000000a95710)
Location: drivers/net/phy/phy_device.c:2306
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_drivers_register
```
**Symbols:**

```
c000000000a95710-c000000000a95844: phy_driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int phy_driver_register(struct phy_driver *new_driver, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffe000621002)
Location: drivers/net/phy/phy_device.c:2306
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_drivers_register
```
**Symbols:**

```
ffffffe000621002-ffffffe0006210d2: phy_driver_register (STB_GLOBAL)
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
int phy_driver_register(struct phy_driver *new_driver, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:2306
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_drivers_register
```
**Symbols:**

```
ffffffff81782166-ffffffff8178219d: phy_driver_register.cold (STB_LOCAL)
ffffffff817808b0-ffffffff8178094a: phy_driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int phy_driver_register(struct phy_driver *new_driver, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:2306
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_drivers_register
```
**Symbols:**

```
ffffffff81761ef6-ffffffff81761f2d: phy_driver_register.cold (STB_LOCAL)
ffffffff81760640-ffffffff817606da: phy_driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int phy_driver_register(struct phy_driver *new_driver, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:2306
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_drivers_register
```
**Symbols:**

```
ffffffff817b2516-ffffffff817b254d: phy_driver_register.cold (STB_LOCAL)
ffffffff817b0c60-ffffffff817b0cfa: phy_driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int phy_driver_register(struct phy_driver *new_driver, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_device.c (0)
Location: drivers/net/phy/phy_device.c:2306
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_init
  - drivers/net/phy/phy_device.c:phy_drivers_register
```
**Symbols:**

```
ffffffff817cc4a6-ffffffff817cc4dd: phy_driver_register.cold (STB_LOCAL)
ffffffff817cabf0-ffffffff817cac8a: phy_driver_register (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct module *owner</code>
</li>
</ul>
</details>
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
