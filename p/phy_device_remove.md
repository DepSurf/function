# Function: <code>phy_device_remove</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void phy_device_remove(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff815eb470)
Location: drivers/net/phy/phy_device.c:418
Inline: False
Direct callers:
  - drivers/net/phy/mdio_bus.c:__mdiobus_register
```
**Symbols:**

```
ffffffff815eb470-ffffffff815eb4a1: phy_device_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void phy_device_remove(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff8164a02d)
Location: drivers/net/phy/phy_device.c:623
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_mdio_device_remove
Direct callers:
  - drivers/net/phy/fixed_phy.c:fixed_phy_unregister
```
**Symbols:**

```
ffffffff8164a000-ffffffff8164a01d: phy_device_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void phy_device_remove(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff8167b44d)
Location: drivers/net/phy/phy_device.c:671
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_mdio_device_remove
Direct callers:
  - drivers/net/phy/fixed_phy.c:fixed_phy_unregister
```
**Symbols:**

```
ffffffff8167b420-ffffffff8167b43d: phy_device_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void phy_device_remove(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff8169030d)
Location: drivers/net/phy/phy_device.c:666
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_mdio_device_remove
Direct callers:
  - drivers/net/phy/fixed_phy.c:fixed_phy_unregister
```
**Symbols:**

```
ffffffff816902e0-ffffffff816902fd: phy_device_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void phy_device_remove(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff816f9fdd)
Location: drivers/net/phy/phy_device.c:666
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_mdio_device_remove
Direct callers:
  - drivers/net/phy/fixed_phy.c:fixed_phy_unregister
```
**Symbols:**

```
ffffffff816f9fb0-ffffffff816f9fcd: phy_device_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void phy_device_remove(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff817376c0)
Location: drivers/net/phy/phy_device.c:685
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_mdio_device_remove
  - drivers/net/phy/fixed_phy.c:fixed_phy_unregister
```
**Symbols:**

```
ffffffff817376c0-ffffffff817376ea: phy_device_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void phy_device_remove(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff8175a890)
Location: drivers/net/phy/phy_device.c:863
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_mdio_device_remove
  - drivers/net/phy/fixed_phy.c:fixed_phy_unregister
```
**Symbols:**

```
ffffffff8175a890-ffffffff8175a8ba: phy_device_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void phy_device_remove(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81797d70)
Location: drivers/net/phy/phy_device.c:878
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_mdio_device_remove
  - drivers/net/phy/fixed_phy.c:fixed_phy_unregister
```
**Symbols:**

```
ffffffff81797d70-ffffffff81797d9c: phy_device_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void phy_device_remove(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff817bb890)
Location: drivers/net/phy/phy_device.c:886
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_mdio_device_remove
  - drivers/net/phy/fixed_phy.c:fixed_phy_unregister
```
**Symbols:**

```
ffffffff817bb890-ffffffff817bb8bc: phy_device_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void phy_device_remove(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81884755)
Location: drivers/net/phy/phy_device.c:885
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_mdio_device_remove
Direct callers:
  - drivers/net/phy/fixed_phy.c:fixed_phy_unregister
```
**Symbols:**

```
ffffffff818830c0-ffffffff81883102: phy_device_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void phy_device_remove(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81892f15)
Location: drivers/net/phy/phy_device.c:907
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_mdio_device_remove
Direct callers:
  - drivers/net/phy/fixed_phy.c:fixed_phy_unregister
```
**Symbols:**

```
ffffffff818917d0-ffffffff81891812: phy_device_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void phy_device_remove(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81875a25)
Location: drivers/net/phy/phy_device.c:924
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_mdio_device_remove
Direct callers:
  - drivers/net/phy/fixed_phy.c:fixed_phy_unregister
```
**Symbols:**

```
ffffffff81874000-ffffffff81874042: phy_device_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void phy_device_remove(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff8190653e)
Location: drivers/net/phy/phy_device.c:958
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_mdio_device_remove
Direct callers:
  - drivers/net/phy/fixed_phy.c:fixed_phy_unregister
```
**Symbols:**

```
ffffffff819049a0-ffffffff819049dd: phy_device_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void phy_device_remove(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81a5931d)
Location: drivers/net/phy/phy_device.c:989
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_mdio_device_remove
Direct callers:
  - drivers/net/phy/fixed_phy.c:fixed_phy_unregister
```
**Symbols:**

```
ffffffff81a57830-ffffffff81a57876: phy_device_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void phy_device_remove(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81be31ad)
Location: drivers/net/phy/phy_device.c:993
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_mdio_device_remove
Direct callers:
  - drivers/net/phy/fixed_phy.c:fixed_phy_unregister
```
**Symbols:**

```
ffffffff81be1670-ffffffff81be16c2: phy_device_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void phy_device_remove(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81c3b0ad)
Location: drivers/net/phy/phy_device.c:1024
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_mdio_device_remove
Direct callers:
  - drivers/net/phy/fixed_phy.c:fixed_phy_unregister
```
**Symbols:**

```
ffffffff81c38f00-ffffffff81c38f52: phy_device_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void phy_device_remove(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81cf022d)
Location: drivers/net/phy/phy_device.c:1027
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_mdio_device_remove
Direct callers:
  - drivers/net/phy/fixed_phy.c:fixed_phy_unregister
```
**Symbols:**

```
ffffffff81cee290-ffffffff81cee2e2: phy_device_remove (STB_GLOBAL)
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
void phy_device_remove(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffff8000109d4630)
Location: drivers/net/phy/phy_device.c:886
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_mdio_device_remove
  - drivers/net/phy/fixed_phy.c:fixed_phy_unregister
```
**Symbols:**

```
ffff8000109d4630-ffff8000109d4670: phy_device_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void phy_device_remove(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (c0abc2b8)
Location: drivers/net/phy/phy_device.c:886
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_mdio_device_remove
  - drivers/net/phy/fixed_phy.c:fixed_phy_unregister
```
**Symbols:**

```
c0abc2b8-c0abc2ec: phy_device_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void phy_device_remove(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (c000000000a94e30)
Location: drivers/net/phy/phy_device.c:886
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_mdio_device_remove
  - drivers/net/phy/fixed_phy.c:fixed_phy_unregister
```
**Symbols:**

```
c000000000a94e30-c000000000a94e8c: phy_device_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void phy_device_remove(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffe0006209c2)
Location: drivers/net/phy/phy_device.c:886
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_mdio_device_remove
  - drivers/net/phy/fixed_phy.c:fixed_phy_unregister
```
**Symbols:**

```
ffffffe0006209c2-ffffffe000620a02: phy_device_remove (STB_GLOBAL)
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
void phy_device_remove(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81780360)
Location: drivers/net/phy/phy_device.c:886
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_mdio_device_remove
  - drivers/net/phy/fixed_phy.c:fixed_phy_unregister
```
**Symbols:**

```
ffffffff81780360-ffffffff8178038c: phy_device_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void phy_device_remove(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81760100)
Location: drivers/net/phy/phy_device.c:886
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_mdio_device_remove
  - drivers/net/phy/fixed_phy.c:fixed_phy_unregister
```
**Symbols:**

```
ffffffff81760100-ffffffff8176012c: phy_device_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void phy_device_remove(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff817b0710)
Location: drivers/net/phy/phy_device.c:886
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_mdio_device_remove
  - drivers/net/phy/fixed_phy.c:fixed_phy_unregister
```
**Symbols:**

```
ffffffff817b0710-ffffffff817b073c: phy_device_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void phy_device_remove(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff817ca6a0)
Location: drivers/net/phy/phy_device.c:886
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:phy_mdio_device_remove
  - drivers/net/phy/fixed_phy.c:fixed_phy_unregister
```
**Symbols:**

```
ffffffff817ca6a0-ffffffff817ca6cc: phy_device_remove (STB_GLOBAL)
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
