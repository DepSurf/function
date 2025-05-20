# Function: <code>mdio_bus_phy_may_suspend</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool mdio_bus_phy_may_suspend(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_bus.c (ffffffff815ec940)
Location: drivers/net/phy/mdio_bus.c:518
Inline: False
Direct callers:
  - drivers/net/phy/mdio_bus.c:mdio_bus_resume
  - drivers/net/phy/mdio_bus.c:mdio_bus_suspend
```
**Symbols:**

```
ffffffff815ec940-ffffffff815ec9b9: mdio_bus_phy_may_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool mdio_bus_phy_may_suspend(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff816498a0)
Location: drivers/net/phy/phy_device.c:83
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:mdio_bus_phy_resume
  - drivers/net/phy/phy_device.c:mdio_bus_phy_suspend
```
**Symbols:**

```
ffffffff816498a0-ffffffff81649919: mdio_bus_phy_may_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool mdio_bus_phy_may_suspend(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff8167ab80)
Location: drivers/net/phy/phy_device.c:84
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:mdio_bus_phy_resume
  - drivers/net/phy/phy_device.c:mdio_bus_phy_suspend
```
**Symbols:**

```
ffffffff8167ab80-ffffffff8167abf9: mdio_bus_phy_may_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool mdio_bus_phy_may_suspend(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff8168fb90)
Location: drivers/net/phy/phy_device.c:79
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:mdio_bus_phy_suspend
```
**Symbols:**

```
ffffffff8168fb90-ffffffff8168fc05: mdio_bus_phy_may_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool mdio_bus_phy_may_suspend(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff816f9890)
Location: drivers/net/phy/phy_device.c:79
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:mdio_bus_phy_suspend
```
**Symbols:**

```
ffffffff816f9890-ffffffff816f9905: mdio_bus_phy_may_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool mdio_bus_phy_may_suspend(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81736eb0)
Location: drivers/net/phy/phy_device.c:79
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:mdio_bus_phy_suspend
```
**Symbols:**

```
ffffffff81736eb0-ffffffff81736f2f: mdio_bus_phy_may_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool mdio_bus_phy_may_suspend(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff8175a050)
Location: drivers/net/phy/phy_device.c:242
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:mdio_bus_phy_suspend
```
**Symbols:**

```
ffffffff8175a050-ffffffff8175a0d8: mdio_bus_phy_may_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool mdio_bus_phy_may_suspend(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81797290)
Location: drivers/net/phy/phy_device.c:234
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:mdio_bus_phy_suspend
```
**Symbols:**

```
ffffffff81797290-ffffffff81797315: mdio_bus_phy_may_suspend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff817bc495)
Location: drivers/net/phy/phy_device.c:234
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81883e75)
Location: drivers/net/phy/phy_device.c:235
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81892555)
Location: drivers/net/phy/phy_device.c:233
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81874b70)
Location: drivers/net/phy/phy_device.c:233
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff819055c0)
Location: drivers/net/phy/phy_device.c:234
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81a57c35)
Location: drivers/net/phy/phy_device.c:235
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:mdio_bus_phy_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81be1b05)
Location: drivers/net/phy/phy_device.c:237
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:mdio_bus_phy_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81c393f5)
Location: drivers/net/phy/phy_device.c:269
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:mdio_bus_phy_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81cee785)
Location: drivers/net/phy/phy_device.c:271
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:mdio_bus_phy_suspend
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffff8000109d54cc)
Location: drivers/net/phy/phy_device.c:234
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (c0abd00c)
Location: drivers/net/phy/phy_device.c:234
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (c000000000a96230)
Location: drivers/net/phy/phy_device.c:234
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffe0006216d8)
Location: drivers/net/phy/phy_device.c:234
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81780f65)
Location: drivers/net/phy/phy_device.c:234
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81760cf5)
Location: drivers/net/phy/phy_device.c:234
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff817b1315)
Location: drivers/net/phy/phy_device.c:234
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff817cb2a5)
Location: drivers/net/phy/phy_device.c:234
Inline: True
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
</ul>
