# Function: <code>genphy_config_advert</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff815ebb66)
Location: drivers/net/phy/phy_device.c:815
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff8164a95a)
Location: drivers/net/phy/phy_device.c:1054
Inline: True
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
In drivers/net/phy/phy_device.c (ffffffff8167b995)
Location: drivers/net/phy/phy_device.c:1137
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_config_aneg
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81690890)
Location: drivers/net/phy/phy_device.c:1185
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_config_aneg
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff816fa6a0)
Location: drivers/net/phy/phy_device.c:1237
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_config_aneg
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81738195)
Location: drivers/net/phy/phy_device.c:1290
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff8175b676)
Location: drivers/net/phy/phy_device.c:1467
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81798cdc)
Location: drivers/net/phy/phy_device.c:1565
Inline: True
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
In drivers/net/phy/phy_device.c (ffffffff817bc743)
Location: drivers/net/phy/phy_device.c:1573
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int genphy_config_advert(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81883f80)
Location: drivers/net/phy/phy_device.c:1787
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:__genphy_config_aneg
```
**Symbols:**

```
ffffffff81883f80-ffffffff818840bd: genphy_config_advert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int genphy_config_advert(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff818926b0)
Location: drivers/net/phy/phy_device.c:1824
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:__genphy_config_aneg
```
**Symbols:**

```
ffffffff818926b0-ffffffff818927ed: genphy_config_advert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int genphy_config_advert(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81874e70)
Location: drivers/net/phy/phy_device.c:1846
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:__genphy_config_aneg
```
**Symbols:**

```
ffffffff81874e70-ffffffff81874fae: genphy_config_advert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int genphy_config_advert(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81905940)
Location: drivers/net/phy/phy_device.c:1892
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:__genphy_config_aneg
```
**Symbols:**

```
ffffffff81905940-ffffffff81905a7e: genphy_config_advert (STB_LOCAL)
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
In drivers/net/phy/phy_device.c (ffffffff81a5a6a4)
Location: drivers/net/phy/phy_device.c:1921
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:__genphy_config_aneg
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int genphy_config_advert(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81be45f0)
Location: drivers/net/phy/phy_device.c:1939
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:__genphy_config_aneg
```
**Symbols:**

```
ffffffff81be45f0-ffffffff81be4732: genphy_config_advert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int genphy_config_advert(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81c3c280)
Location: drivers/net/phy/phy_device.c:1978
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:__genphy_config_aneg
```
**Symbols:**

```
ffffffff81c3c280-ffffffff81c3c3b0: genphy_config_advert (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int genphy_config_advert(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81cf1680)
Location: drivers/net/phy/phy_device.c:1985
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:__genphy_config_aneg
```
**Symbols:**

```
ffffffff81cf1680-ffffffff81cf17b0: genphy_config_advert (STB_LOCAL)
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
In drivers/net/phy/phy_device.c (ffff8000109d578c)
Location: drivers/net/phy/phy_device.c:1573
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
In drivers/net/phy/phy_device.c (c0abd27c)
Location: drivers/net/phy/phy_device.c:1573
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
In drivers/net/phy/phy_device.c (c000000000a966b8)
Location: drivers/net/phy/phy_device.c:1573
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
In drivers/net/phy/phy_device.c (ffffffe00062191c)
Location: drivers/net/phy/phy_device.c:1573
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
In drivers/net/phy/phy_device.c (ffffffff81781213)
Location: drivers/net/phy/phy_device.c:1573
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
In drivers/net/phy/phy_device.c (ffffffff81760fa3)
Location: drivers/net/phy/phy_device.c:1573
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
In drivers/net/phy/phy_device.c (ffffffff817b15c3)
Location: drivers/net/phy/phy_device.c:1573
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
In drivers/net/phy/phy_device.c (ffffffff817cb553)
Location: drivers/net/phy/phy_device.c:1573
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
