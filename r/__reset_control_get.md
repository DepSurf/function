# Function: <code>__reset_control_get</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (0)
Location: drivers/reset/core.c:214
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (0)
Location: drivers/reset/core.c:255
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct reset_control *__reset_control_get(struct device *dev, const char *id, int index, bool shared, bool optional);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff815712b5)
Location: drivers/reset/core.c:396
Inline: True
Inline callers:
  - drivers/reset/core.c:device_reset
  - drivers/reset/core.c:__devm_reset_control_get
```
**Symbols:**

```
ffffffff81571270-ffffffff815712a1: __reset_control_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct reset_control *__reset_control_get(struct device *dev, const char *id, int index, bool shared, bool optional);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff815d5555)
Location: drivers/reset/core.c:496
Inline: True
Inline callers:
  - drivers/reset/core.c:device_reset
  - drivers/reset/core.c:__devm_reset_control_get
```
**Symbols:**

```
ffffffff815d5510-ffffffff815d5541: __reset_control_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct reset_control *__reset_control_get(struct device *dev, const char *id, int index, bool shared, bool optional);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8160ed45)
Location: drivers/reset/core.c:590
Inline: True
Inline callers:
  - drivers/reset/core.c:__device_reset
Direct callers:
  - drivers/reset/core.c:__devm_reset_control_get
```
**Symbols:**

```
ffffffff8160eb90-ffffffff8160ebc9: __reset_control_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct reset_control *__reset_control_get(struct device *dev, const char *id, int index, bool shared, bool optional);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8162b925)
Location: drivers/reset/core.c:591
Inline: True
Inline callers:
  - drivers/reset/core.c:__device_reset
Direct callers:
  - drivers/reset/core.c:__devm_reset_control_get
```
**Symbols:**

```
ffffffff8162b380-ffffffff8162b3b9: __reset_control_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct reset_control *__reset_control_get(struct device *dev, const char *id, int index, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/reset/core.c (ffffffff8165f0ab)
Location: drivers/reset/core.c:727
Inline: True
Direct callers:
  - drivers/reset/core.c:__device_reset
  - drivers/reset/core.c:__devm_reset_control_get
```
**Symbols:**

```
ffffffff8165f7f8-ffffffff8165f844: __reset_control_get.cold (STB_LOCAL)
ffffffff8165f070-ffffffff8165f326: __reset_control_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct reset_control *__reset_control_get(struct device *dev, const char *id, int index, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81681760)
Location: drivers/reset/core.c:726
Inline: True
Direct callers:
  - drivers/reset/core.c:__device_reset
  - drivers/reset/core.c:__devm_reset_control_get
```
**Symbols:**

```
ffffffff81681760-ffffffff81681a48: __reset_control_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct reset_control *__reset_control_get(struct device *dev, const char *id, int index, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81732ed5)
Location: drivers/reset/core.c:727
Inline: True
Inline callers:
  - drivers/reset/core.c:__device_reset
Direct callers:
  - drivers/reset/core.c:__devm_reset_control_get
  - drivers/net/phy/mdio_bus.c:mdiobus_register_device
```
**Symbols:**

```
ffffffff81732af0-ffffffff81732b41: __reset_control_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct reset_control *__reset_control_get(struct device *dev, const char *id, int index, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8174f095)
Location: drivers/reset/core.c:801
Inline: True
Inline callers:
  - drivers/reset/core.c:__device_reset
Direct callers:
  - drivers/reset/core.c:__devm_reset_control_get
  - drivers/net/phy/mdio_bus.c:mdiobus_register_device
```
**Symbols:**

```
ffffffff8174ecb0-ffffffff8174ed01: __reset_control_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct reset_control *__reset_control_get(struct device *dev, const char *id, int index, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff817327e0)
Location: drivers/reset/core.c:938
Inline: False
Direct callers:
  - drivers/reset/core.c:__device_reset
  - drivers/reset/core.c:__devm_reset_control_get
  - drivers/reset/core.c:__reset_control_bulk_get
  - drivers/net/phy/mdio_bus.c:mdiobus_register_device
```
**Symbols:**

```
ffffffff817327e0-ffffffff817329c5: __reset_control_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct reset_control *__reset_control_get(struct device *dev, const char *id, int index, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff817b30e0)
Location: drivers/reset/core.c:938
Inline: True
Direct callers:
  - drivers/reset/core.c:__device_reset
  - drivers/reset/core.c:__devm_reset_control_get
  - drivers/reset/core.c:__reset_control_bulk_get
  - drivers/net/phy/mdio_bus.c:mdiobus_register_device
```
**Symbols:**

```
ffffffff817b30e0-ffffffff817b32c5: __reset_control_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct reset_control *__reset_control_get(struct device *dev, const char *id, int index, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff818eeb30)
Location: drivers/reset/core.c:939
Inline: True
Direct callers:
  - drivers/reset/core.c:__device_reset
  - drivers/reset/core.c:__devm_reset_control_get
  - drivers/reset/core.c:__reset_control_bulk_get
  - drivers/net/phy/mdio_bus.c:mdiobus_register_device
```
**Symbols:**

```
ffffffff818eeb30-ffffffff818eed5a: __reset_control_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct reset_control *__reset_control_get(struct device *dev, const char *id, int index, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81a467a0)
Location: drivers/reset/core.c:939
Inline: True
Direct callers:
  - drivers/reset/core.c:__device_reset
  - drivers/reset/core.c:__devm_reset_control_get
  - drivers/reset/core.c:__reset_control_bulk_get
  - drivers/net/phy/mdio_bus.c:mdiobus_register_device
```
**Symbols:**

```
ffffffff81a467a0-ffffffff81a469ca: __reset_control_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct reset_control *__reset_control_get(struct device *dev, const char *id, int index, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81a90940)
Location: drivers/reset/core.c:939
Inline: True
Direct callers:
  - drivers/reset/core.c:__device_reset
  - drivers/reset/core.c:__devm_reset_control_get
  - drivers/reset/core.c:__reset_control_bulk_get
  - drivers/net/phy/mdio_bus.c:mdiobus_register_device
```
**Symbols:**

```
ffffffff81a90940-ffffffff81a90b6a: __reset_control_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct reset_control *__reset_control_get(struct device *dev, const char *id, int index, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81ae33b0)
Location: drivers/reset/core.c:942
Inline: True
Direct callers:
  - drivers/reset/core.c:__device_reset
  - drivers/reset/core.c:__devm_reset_control_get
  - drivers/reset/core.c:__reset_control_bulk_get
  - drivers/net/phy/mdio_bus.c:mdiobus_register_device
```
**Symbols:**

```
ffffffff81ae33b0-ffffffff81ae35da: __reset_control_get (STB_GLOBAL)
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
struct reset_control *__reset_control_get(struct device *dev, const char *id, int index, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffff80001084c608)
Location: drivers/reset/core.c:726
Inline: False
Direct callers:
  - drivers/reset/core.c:__device_reset
  - drivers/reset/core.c:__devm_reset_control_get
```
**Symbols:**

```
ffff80001084c608-ffff80001084c7ec: __reset_control_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct reset_control *__reset_control_get(struct device *dev, const char *id, int index, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (c0958940)
Location: drivers/reset/core.c:726
Inline: False
Direct callers:
  - drivers/reset/core.c:__device_reset
  - drivers/reset/core.c:__devm_reset_control_get
```
**Symbols:**

```
c0958940-c0958b28: __reset_control_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct reset_control *__reset_control_get(struct device *dev, const char *id, int index, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (c0000000008ebfd0)
Location: drivers/reset/core.c:726
Inline: False
Direct callers:
  - drivers/reset/core.c:__device_reset
  - drivers/reset/core.c:__devm_reset_control_get
```
**Symbols:**

```
c0000000008ebfd0-c0000000008ec6f0: __reset_control_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct reset_control *__reset_control_get(struct device *dev, const char *id, int index, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffe00052be16)
Location: drivers/reset/core.c:726
Inline: False
Direct callers:
  - drivers/reset/core.c:__device_reset
  - drivers/reset/core.c:__devm_reset_control_get
```
**Symbols:**

```
ffffffe00052be16-ffffffe00052bfb0: __reset_control_get (STB_GLOBAL)
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
struct reset_control *__reset_control_get(struct device *dev, const char *id, int index, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff816471e0)
Location: drivers/reset/core.c:726
Inline: True
Direct callers:
  - drivers/reset/core.c:__device_reset
  - drivers/reset/core.c:__devm_reset_control_get
```
**Symbols:**

```
ffffffff816471e0-ffffffff816474c8: __reset_control_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct reset_control *__reset_control_get(struct device *dev, const char *id, int index, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81627640)
Location: drivers/reset/core.c:726
Inline: True
Direct callers:
  - drivers/reset/core.c:__device_reset
  - drivers/reset/core.c:__devm_reset_control_get
```
**Symbols:**

```
ffffffff81627640-ffffffff81627928: __reset_control_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct reset_control *__reset_control_get(struct device *dev, const char *id, int index, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff816755a0)
Location: drivers/reset/core.c:726
Inline: True
Direct callers:
  - drivers/reset/core.c:__device_reset
  - drivers/reset/core.c:__devm_reset_control_get
```
**Symbols:**

```
ffffffff816755a0-ffffffff81675888: __reset_control_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct reset_control *__reset_control_get(struct device *dev, const char *id, int index, bool shared, bool optional, bool acquired);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8168fc00)
Location: drivers/reset/core.c:726
Inline: True
Direct callers:
  - drivers/reset/core.c:__device_reset
  - drivers/reset/core.c:__devm_reset_control_get
```
**Symbols:**

```
ffffffff8168fc00-ffffffff8168fee8: __reset_control_get (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
