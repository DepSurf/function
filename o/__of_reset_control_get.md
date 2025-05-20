# Function: <code>__of_reset_control_get</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct reset_control *__of_reset_control_get(struct device_node *node, const char *id, int index, int shared);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81530283)
Location: drivers/reset/core.c:260
Inline: True
Inline callers:
  - drivers/reset/core.c:device_reset
  - drivers/reset/core.c:__devm_reset_control_get
```
**Symbols:**

```
ffffffff81530240-ffffffff81530266: __of_reset_control_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct reset_control *__of_reset_control_get(struct device_node *node, const char *id, int index, int shared);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8155c853)
Location: drivers/reset/core.c:301
Inline: True
Inline callers:
  - drivers/reset/core.c:device_reset
  - drivers/reset/core.c:__devm_reset_control_get
```
**Symbols:**

```
ffffffff8155c810-ffffffff8155c836: __of_reset_control_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct reset_control *__of_reset_control_get(struct device_node *node, const char *id, int index, bool shared, bool optional);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8157147f)
Location: drivers/reset/core.c:332
Inline: True
Inline callers:
  - drivers/reset/core.c:__devm_reset_control_get
```
**Symbols:**

```
ffffffff81571240-ffffffff8157126d: __of_reset_control_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct reset_control *__of_reset_control_get(struct device_node *node, const char *id, int index, bool shared, bool optional);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff815d574f)
Location: drivers/reset/core.c:432
Inline: True
Inline callers:
  - drivers/reset/core.c:__devm_reset_control_get
```
**Symbols:**

```
ffffffff815d54e0-ffffffff815d550d: __of_reset_control_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct reset_control *__of_reset_control_get(struct device_node *node, const char *id, int index, bool shared, bool optional);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8160ed56)
Location: drivers/reset/core.c:462
Inline: True
Inline callers:
  - drivers/reset/core.c:__device_reset
```
**Symbols:**

```
ffffffff8160e310-ffffffff8160e33d: __of_reset_control_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct reset_control *__of_reset_control_get(struct device_node *node, const char *id, int index, bool shared, bool optional);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8162b936)
Location: drivers/reset/core.c:462
Inline: True
Inline callers:
  - drivers/reset/core.c:__device_reset
```
**Symbols:**

```
ffffffff8162ae30-ffffffff8162ae5d: __of_reset_control_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct reset_control *__of_reset_control_get(struct device_node *node, const char *id, int index, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8165ea00)
Location: drivers/reset/core.c:601
Inline: True
```
**Symbols:**

```
ffffffff8165ea00-ffffffff8165ea2f: __of_reset_control_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct reset_control *__of_reset_control_get(struct device_node *node, const char *id, int index, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff816810f0)
Location: drivers/reset/core.c:600
Inline: True
Direct callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_register_device
```
**Symbols:**

```
ffffffff816810f0-ffffffff8168111f: __of_reset_control_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct reset_control *__of_reset_control_get(struct device_node *node, const char *id, int index, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81732ee7)
Location: drivers/reset/core.c:601
Inline: True
Inline callers:
  - drivers/reset/core.c:__device_reset
```
**Symbols:**

```
ffffffff817322c0-ffffffff817322ef: __of_reset_control_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct reset_control *__of_reset_control_get(struct device_node *node, const char *id, int index, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8174f0a7)
Location: drivers/reset/core.c:675
Inline: True
Inline callers:
  - drivers/reset/core.c:__device_reset
```
**Symbols:**

```
ffffffff8174e370-ffffffff8174e39f: __of_reset_control_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct reset_control *__of_reset_control_get(struct device_node *node, const char *id, int index, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81732816)
Location: drivers/reset/core.c:812
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get
```
**Symbols:**

```
ffffffff81731ef0-ffffffff81731f1f: __of_reset_control_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct reset_control *__of_reset_control_get(struct device_node *node, const char *id, int index, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff817b2650)
Location: drivers/reset/core.c:813
Inline: True
```
**Symbols:**

```
ffffffff817b2650-ffffffff817b267f: __of_reset_control_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct reset_control *__of_reset_control_get(struct device_node *node, const char *id, int index, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff818edfd0)
Location: drivers/reset/core.c:814
Inline: True
```
**Symbols:**

```
ffffffff818edfd0-ffffffff818ee020: __of_reset_control_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct reset_control *__of_reset_control_get(struct device_node *node, const char *id, int index, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81a45b30)
Location: drivers/reset/core.c:814
Inline: True
```
**Symbols:**

```
ffffffff81a45b30-ffffffff81a45b80: __of_reset_control_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct reset_control *__of_reset_control_get(struct device_node *node, const char *id, int index, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81a8fce0)
Location: drivers/reset/core.c:814
Inline: True
```
**Symbols:**

```
ffffffff81a8fce0-ffffffff81a8fd30: __of_reset_control_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct reset_control *__of_reset_control_get(struct device_node *node, const char *id, int index, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81ae2720)
Location: drivers/reset/core.c:817
Inline: True
```
**Symbols:**

```
ffffffff81ae2720-ffffffff81ae2770: __of_reset_control_get (STB_GLOBAL)
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
struct reset_control *__of_reset_control_get(struct device_node *node, const char *id, int index, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffff80001084c438)
Location: drivers/reset/core.c:600
Inline: False
Direct callers:
  - drivers/reset/core.c:of_reset_control_array_get
  - drivers/reset/core.c:__reset_control_get
  - drivers/net/phy/mdio_bus.c:mdiobus_register_device
```
**Symbols:**

```
ffff80001084c438-ffff80001084c5e8: __of_reset_control_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct reset_control *__of_reset_control_get(struct device_node *node, const char *id, int index, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (c0958778)
Location: drivers/reset/core.c:600
Inline: False
Direct callers:
  - arch/arm/mach-meson/platsmp.c:meson_smp_get_core_reset
  - arch/arm/mach-rockchip/platsmp.c:pmu_set_power_domain
  - drivers/reset/core.c:of_reset_control_array_get
  - drivers/reset/core.c:__reset_control_get
  - drivers/net/phy/mdio_bus.c:mdiobus_register_device
  - drivers/clocksource/dw_apb_timer_of.c:timer_get_base_and_rate
```
**Symbols:**

```
c0958778-c0958940: __of_reset_control_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct reset_control *__of_reset_control_get(struct device_node *node, const char *id, int index, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (c0000000008eba40)
Location: drivers/reset/core.c:600
Inline: False
Direct callers:
  - drivers/reset/core.c:of_reset_control_array_get
  - drivers/reset/core.c:__reset_control_get
  - drivers/net/phy/mdio_bus.c:mdiobus_register_device
```
**Symbols:**

```
c0000000008eba40-c0000000008ebc9c: __of_reset_control_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct reset_control *__of_reset_control_get(struct device_node *node, const char *id, int index, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffe00052bce0)
Location: drivers/reset/core.c:600
Inline: False
Direct callers:
  - drivers/reset/core.c:of_reset_control_array_get
  - drivers/reset/core.c:__reset_control_get
  - drivers/net/phy/mdio_bus.c:mdiobus_register_device
```
**Symbols:**

```
ffffffe00052bce0-ffffffe00052be16: __of_reset_control_get (STB_GLOBAL)
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
struct reset_control *__of_reset_control_get(struct device_node *node, const char *id, int index, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81646b70)
Location: drivers/reset/core.c:600
Inline: True
Direct callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_register_device
```
**Symbols:**

```
ffffffff81646b70-ffffffff81646b9f: __of_reset_control_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct reset_control *__of_reset_control_get(struct device_node *node, const char *id, int index, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81626fd0)
Location: drivers/reset/core.c:600
Inline: True
Direct callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_register_device
```
**Symbols:**

```
ffffffff81626fd0-ffffffff81626fff: __of_reset_control_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct reset_control *__of_reset_control_get(struct device_node *node, const char *id, int index, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81674f30)
Location: drivers/reset/core.c:600
Inline: True
Direct callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_register_device
```
**Symbols:**

```
ffffffff81674f30-ffffffff81674f5f: __of_reset_control_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct reset_control *__of_reset_control_get(struct device_node *node, const char *id, int index, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8168f590)
Location: drivers/reset/core.c:600
Inline: True
Direct callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_register_device
```
**Symbols:**

```
ffffffff8168f590-ffffffff8168f5bf: __of_reset_control_get (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool optional</code>
</li>
<li>
<b>Param type changed. </b>
<code>int shared</code> ➡️ <code>bool shared</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool acquired</code>
</li>
</ul>
</details>
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
