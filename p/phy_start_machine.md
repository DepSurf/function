# Function: <code>phy_start_machine</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void phy_start_machine(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff815ea900)
Location: drivers/net/phy/phy.c:523
Inline: False
Direct callers:
  - drivers/net/phy/mdio_bus.c:mdio_bus_restore
  - drivers/net/phy/mdio_bus.c:mdio_bus_resume
```
**Symbols:**

```
ffffffff815ea900-ffffffff815ea928: phy_start_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void phy_start_machine(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81649240)
Location: drivers/net/phy/phy.c:605
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:mdio_bus_phy_resume
```
**Symbols:**

```
ffffffff81649240-ffffffff81649268: phy_start_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void phy_start_machine(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff8167a490)
Location: drivers/net/phy/phy.c:644
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:mdio_bus_phy_resume
```
**Symbols:**

```
ffffffff8167a490-ffffffff8167a4b8: phy_start_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void phy_start_machine(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff8168e620)
Location: drivers/net/phy/phy.c:712
Inline: False
```
**Symbols:**

```
ffffffff8168e620-ffffffff8168e648: phy_start_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void phy_start_machine(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff816f79a0)
Location: drivers/net/phy/phy.c:556
Inline: False
```
**Symbols:**

```
ffffffff816f79a0-ffffffff816f79c8: phy_start_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void phy_start_machine(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81734c10)
Location: drivers/net/phy/phy.c:559
Inline: False
```
**Symbols:**

```
ffffffff81734c10-ffffffff81734c38: phy_start_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void phy_start_machine(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (0)
Location: drivers/net/phy/phy.c:693
Inline: False
```
**Symbols:**

```
ffffffff81757cf0-ffffffff81757d00: phy_start_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void phy_start_machine(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81794563)
Location: drivers/net/phy/phy.c:701
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_start
```
**Symbols:**

```
ffffffff817943b0-ffffffff817943d5: phy_start_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void phy_start_machine(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff817b8103)
Location: drivers/net/phy/phy.c:681
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_start
```
**Symbols:**

```
ffffffff817b7ee0-ffffffff817b7f05: phy_start_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void phy_start_machine(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff8187f188)
Location: drivers/net/phy/phy.c:795
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_start
```
**Symbols:**

```
ffffffff8187f070-ffffffff8187f095: phy_start_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void phy_start_machine(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff8188db38)
Location: drivers/net/phy/phy.c:880
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_start
```
**Symbols:**

```
ffffffff8188da00-ffffffff8188da25: phy_start_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void phy_start_machine(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81870478)
Location: drivers/net/phy/phy.c:881
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_start
```
**Symbols:**

```
ffffffff81870340-ffffffff81870365: phy_start_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void phy_start_machine(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81900a58)
Location: drivers/net/phy/phy.c:907
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_start
```
**Symbols:**

```
ffffffff81900920-ffffffff81900945: phy_start_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void phy_start_machine(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81a527e8)
Location: drivers/net/phy/phy.c:912
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_start
Direct callers:
  - drivers/net/phy/phy_device.c:mdio_bus_phy_resume
```
**Symbols:**

```
ffffffff81a52640-ffffffff81a52673: phy_start_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void phy_start_machine(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81bdbfd8)
Location: drivers/net/phy/phy.c:941
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_start
Direct callers:
  - drivers/net/phy/phy_device.c:mdio_bus_phy_resume
```
**Symbols:**

```
ffffffff81bdbc30-ffffffff81bdbc63: phy_start_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void phy_start_machine(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81c32fd8)
Location: drivers/net/phy/phy.c:1161
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_start
Direct callers:
  - drivers/net/phy/phy_device.c:mdio_bus_phy_resume
```
**Symbols:**

```
ffffffff81c32ca0-ffffffff81c32cd3: phy_start_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void phy_start_machine(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81ce7cc8)
Location: drivers/net/phy/phy.c:1216
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_start
Direct callers:
  - drivers/net/phy/phy_device.c:mdio_bus_phy_resume
```
**Symbols:**

```
ffffffff81ce79e0-ffffffff81ce7a13: phy_start_machine (STB_GLOBAL)
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
void phy_start_machine(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffff8000109d08c8)
Location: drivers/net/phy/phy.c:681
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_start
```
**Symbols:**

```
ffff8000109d06c0-ffff8000109d06e8: phy_start_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void phy_start_machine(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (c0ab8ae8)
Location: drivers/net/phy/phy.c:681
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_start
```
**Symbols:**

```
c0ab88cc-c0ab88ec: phy_start_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void phy_start_machine(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (c000000000a8fda8)
Location: drivers/net/phy/phy.c:681
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_start
```
**Symbols:**

```
c000000000a8fa20-c000000000a8fa70: phy_start_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void phy_start_machine(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffe00061d5ac)
Location: drivers/net/phy/phy.c:681
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_start
```
**Symbols:**

```
ffffffe00061d33a-ffffffe00061d362: phy_start_machine (STB_GLOBAL)
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
void phy_start_machine(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff8177cbd3)
Location: drivers/net/phy/phy.c:681
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_start
```
**Symbols:**

```
ffffffff8177c9b0-ffffffff8177c9d5: phy_start_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void phy_start_machine(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff8175c983)
Location: drivers/net/phy/phy.c:681
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_start
```
**Symbols:**

```
ffffffff8175c760-ffffffff8175c785: phy_start_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void phy_start_machine(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff817acf83)
Location: drivers/net/phy/phy.c:681
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_start
```
**Symbols:**

```
ffffffff817acd60-ffffffff817acd85: phy_start_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void phy_start_machine(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff817c6f13)
Location: drivers/net/phy/phy.c:681
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_start
```
**Symbols:**

```
ffffffff817c6cf0-ffffffff817c6d15: phy_start_machine (STB_GLOBAL)
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
