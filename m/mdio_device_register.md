# Function: <code>mdio_device_register</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mdio_device_register(struct mdio_device *mdiodev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_device.c (ffffffff8164bf40)
Location: drivers/net/phy/mdio_device.c:66
Inline: False
```
**Symbols:**

```
ffffffff8164bf40-ffffffff8164bf9c: mdio_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mdio_device_register(struct mdio_device *mdiodev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_device.c (ffffffff8167d900)
Location: drivers/net/phy/mdio_device.c:66
Inline: False
```
**Symbols:**

```
ffffffff8167d900-ffffffff8167d95c: mdio_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int mdio_device_register(struct mdio_device *mdiodev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_device.c (ffffffff81692aa0)
Location: drivers/net/phy/mdio_device.c:77
Inline: True
Direct callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_create_device
```
**Symbols:**

```
ffffffff81692aa0-ffffffff81692b0d: mdio_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int mdio_device_register(struct mdio_device *mdiodev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_device.c (ffffffff816fc8b0)
Location: drivers/net/phy/mdio_device.c:77
Inline: True
Direct callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_create_device
```
**Symbols:**

```
ffffffff816fc8b0-ffffffff816fc91d: mdio_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mdio_device_register(struct mdio_device *mdiodev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/phy/mdio_device.c (0)
Location: drivers/net/phy/mdio_device.c:80
Inline: True
Direct callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_create_device
```
**Symbols:**

```
ffffffff8173a175-ffffffff8173a196: mdio_device_register.cold.3 (STB_LOCAL)
ffffffff8173a010-ffffffff8173a076: mdio_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mdio_device_register(struct mdio_device *mdiodev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/phy/mdio_device.c (ffffffff8175d76d)
Location: drivers/net/phy/mdio_device.c:80
Inline: True
Direct callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_create_device
```
**Symbols:**

```
ffffffff8175d885-ffffffff8175d8a6: mdio_device_register.cold.3 (STB_LOCAL)
ffffffff8175d720-ffffffff8175d786: mdio_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mdio_device_register(struct mdio_device *mdiodev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/phy/mdio_device.c (ffffffff8179ad82)
Location: drivers/net/phy/mdio_device.c:76
Inline: True
Direct callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_create_device
```
**Symbols:**

```
ffffffff8179ae95-ffffffff8179aeb5: mdio_device_register.cold (STB_LOCAL)
ffffffff8179ad30-ffffffff8179ad9e: mdio_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mdio_device_register(struct mdio_device *mdiodev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/phy/mdio_device.c (ffffffff817be812)
Location: drivers/net/phy/mdio_device.c:76
Inline: True
Direct callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_create_device
```
**Symbols:**

```
ffffffff817be925-ffffffff817be945: mdio_device_register.cold (STB_LOCAL)
ffffffff817be7c0-ffffffff817be82e: mdio_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mdio_device_register(struct mdio_device *mdiodev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/phy/mdio_device.c (ffffffff818875b2)
Location: drivers/net/phy/mdio_device.c:76
Inline: True
Direct callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_create_device
```
**Symbols:**

```
ffffffff818876c5-ffffffff818876e5: mdio_device_register.cold (STB_LOCAL)
ffffffff81887560-ffffffff818875ce: mdio_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mdio_device_register(struct mdio_device *mdiodev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/phy/mdio_device.c (ffffffff818958d2)
Location: drivers/net/phy/mdio_device.c:76
Inline: True
Direct callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_create_device
```
**Symbols:**

```
ffffffff81c194e6-ffffffff81c19506: mdio_device_register.cold (STB_LOCAL)
ffffffff81895880-ffffffff818958ee: mdio_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mdio_device_register(struct mdio_device *mdiodev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/phy/mdio_device.c (ffffffff81878142)
Location: drivers/net/phy/mdio_device.c:76
Inline: True
Direct callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_create_device
```
**Symbols:**

```
ffffffff81c0b339-ffffffff81c0b359: mdio_device_register.cold (STB_LOCAL)
ffffffff818780f0-ffffffff8187815e: mdio_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int mdio_device_register(struct mdio_device *mdiodev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/mdio_device.c (0)
Location: drivers/net/phy/mdio_device.c:76
Inline: False
Direct callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_create_device
```
**Symbols:**

```
ffffffff81d10728-ffffffff81d10748: mdio_device_register.cold (STB_LOCAL)
ffffffff81908cf0-ffffffff81908d62: mdio_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mdio_device_register(struct mdio_device *mdiodev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/mdio_device.c (0)
Location: drivers/net/phy/mdio_device.c:76
Inline: False
Direct callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_create_device
```
**Symbols:**

```
ffffffff81edb4b9-ffffffff81edb4da: mdio_device_register.cold (STB_LOCAL)
ffffffff81a5c250-ffffffff81a5c2d2: mdio_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int mdio_device_register(struct mdio_device *mdiodev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_device.c (ffffffff81be7030)
Location: drivers/net/phy/mdio_device.c:78
Inline: True
Direct callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_create_device
```
**Symbols:**

```
ffffffff81be7030-ffffffff81be70b9: mdio_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int mdio_device_register(struct mdio_device *mdiodev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_device.c (ffffffff81c3f3a0)
Location: drivers/net/phy/mdio_device.c:78
Inline: True
Direct callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_create_device
```
**Symbols:**

```
ffffffff81c3f3a0-ffffffff81c3f429: mdio_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int mdio_device_register(struct mdio_device *mdiodev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_device.c (ffffffff81cf4970)
Location: drivers/net/phy/mdio_device.c:79
Inline: True
Direct callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_create_device
```
**Symbols:**

```
ffffffff81cf4970-ffffffff81cf49f9: mdio_device_register (STB_GLOBAL)
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
int mdio_device_register(struct mdio_device *mdiodev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_device.c (ffff8000109d7fd8)
Location: drivers/net/phy/mdio_device.c:76
Inline: True
Direct callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_create_device
```
**Symbols:**

```
ffff8000109d7fd8-ffff8000109d806c: mdio_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int mdio_device_register(struct mdio_device *mdiodev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_device.c (c0abf7b4)
Location: drivers/net/phy/mdio_device.c:76
Inline: True
Direct callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_create_device
```
**Symbols:**

```
c0abf7b4-c0abf83c: mdio_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int mdio_device_register(struct mdio_device *mdiodev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_device.c (c000000000a99e70)
Location: drivers/net/phy/mdio_device.c:76
Inline: True
Direct callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_create_device
```
**Symbols:**

```
c000000000a99e70-c000000000a99f38: mdio_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int mdio_device_register(struct mdio_device *mdiodev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_device.c (ffffffe000623c8a)
Location: drivers/net/phy/mdio_device.c:76
Inline: True
Direct callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_create_device
```
**Symbols:**

```
ffffffe000623c8a-ffffffe000623d18: mdio_device_register (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mdio_device_register(struct mdio_device *mdiodev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/phy/mdio_device.c (ffffffff817832e2)
Location: drivers/net/phy/mdio_device.c:76
Inline: True
Direct callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_create_device
```
**Symbols:**

```
ffffffff817833f5-ffffffff81783415: mdio_device_register.cold (STB_LOCAL)
ffffffff81783290-ffffffff817832fe: mdio_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mdio_device_register(struct mdio_device *mdiodev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/phy/mdio_device.c (ffffffff81763072)
Location: drivers/net/phy/mdio_device.c:76
Inline: True
Direct callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_create_device
```
**Symbols:**

```
ffffffff81763185-ffffffff817631a5: mdio_device_register.cold (STB_LOCAL)
ffffffff81763020-ffffffff8176308e: mdio_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mdio_device_register(struct mdio_device *mdiodev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/phy/mdio_device.c (ffffffff817b3692)
Location: drivers/net/phy/mdio_device.c:76
Inline: True
Direct callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_create_device
```
**Symbols:**

```
ffffffff817b37a5-ffffffff817b37c5: mdio_device_register.cold (STB_LOCAL)
ffffffff817b3640-ffffffff817b36ae: mdio_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mdio_device_register(struct mdio_device *mdiodev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/phy/mdio_device.c (ffffffff817cd662)
Location: drivers/net/phy/mdio_device.c:76
Inline: True
Direct callers:
  - drivers/net/phy/mdio_bus.c:mdiobus_create_device
```
**Symbols:**

```
ffffffff817cd775-ffffffff817cd795: mdio_device_register.cold (STB_LOCAL)
ffffffff817cd610-ffffffff817cd67e: mdio_device_register (STB_GLOBAL)
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
