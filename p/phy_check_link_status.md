# Function: <code>phy_check_link_status</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int phy_check_link_status(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81758100)
Location: drivers/net/phy/phy.c:507
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start_aneg
```
**Symbols:**

```
ffffffff81758100-ffffffff817581cc: phy_check_link_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int phy_check_link_status(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81794b34)
Location: drivers/net/phy/phy.c:522
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start_aneg
```
**Symbols:**

```
ffffffff81794ae0-ffffffff81794bd1: phy_check_link_status (STB_LOCAL)
ffffffff81795bd3-ffffffff81795be6: phy_check_link_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int phy_check_link_status(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff817b8680)
Location: drivers/net/phy/phy.c:527
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start_aneg
```
**Symbols:**

```
ffffffff817b8680-ffffffff817b877d: phy_check_link_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int phy_check_link_status(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff8187f610)
Location: drivers/net/phy/phy.c:640
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start_aneg
```
**Symbols:**

```
ffffffff8187f610-ffffffff8187f707: phy_check_link_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int phy_check_link_status(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff8188dec0)
Location: drivers/net/phy/phy.c:725
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start_aneg
```
**Symbols:**

```
ffffffff8188dec0-ffffffff8188dfb7: phy_check_link_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int phy_check_link_status(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81870710)
Location: drivers/net/phy/phy.c:726
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start_aneg
```
**Symbols:**

```
ffffffff81870710-ffffffff818707e2: phy_check_link_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int phy_check_link_status(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81900d30)
Location: drivers/net/phy/phy.c:674
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:_phy_start_aneg
```
**Symbols:**

```
ffffffff81900d30-ffffffff81900e02: phy_check_link_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int phy_check_link_status(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81a52850)
Location: drivers/net/phy/phy.c:679
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:_phy_start_aneg
```
**Symbols:**

```
ffffffff81a52850-ffffffff81a52929: phy_check_link_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int phy_check_link_status(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81bdc3c0)
Location: drivers/net/phy/phy.c:708
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:_phy_start_aneg
```
**Symbols:**

```
ffffffff81bdc3c0-ffffffff81bdc4a8: phy_check_link_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int phy_check_link_status(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81c33050)
Location: drivers/net/phy/phy.c:913
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:_phy_start_aneg
```
**Symbols:**

```
ffffffff81c33050-ffffffff81c33138: phy_check_link_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int phy_check_link_status(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81ce7d40)
Location: drivers/net/phy/phy.c:967
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:_phy_state_machine
  - drivers/net/phy/phy.c:_phy_start_aneg
```
**Symbols:**

```
ffffffff81ce7d40-ffffffff81ce7e28: phy_check_link_status (STB_LOCAL)
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
int phy_check_link_status(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffff8000109d0c38)
Location: drivers/net/phy/phy.c:527
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start_aneg
```
**Symbols:**

```
ffff8000109d0c38-ffff8000109d0d1c: phy_check_link_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int phy_check_link_status(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (c0ab8f68)
Location: drivers/net/phy/phy.c:527
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start_aneg
```
**Symbols:**

```
c0ab8f68-c0ab9074: phy_check_link_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int phy_check_link_status(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (c000000000a90270)
Location: drivers/net/phy/phy.c:527
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start_aneg
```
**Symbols:**

```
c000000000a90270-c000000000a903b8: phy_check_link_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int phy_check_link_status(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffe00061dad2)
Location: drivers/net/phy/phy.c:527
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start_aneg
```
**Symbols:**

```
ffffffe00061dad2-ffffffe00061db9a: phy_check_link_status (STB_LOCAL)
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
int phy_check_link_status(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff8177d150)
Location: drivers/net/phy/phy.c:527
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start_aneg
```
**Symbols:**

```
ffffffff8177d150-ffffffff8177d24d: phy_check_link_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int phy_check_link_status(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff8175cf00)
Location: drivers/net/phy/phy.c:527
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start_aneg
```
**Symbols:**

```
ffffffff8175cf00-ffffffff8175d003: phy_check_link_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int phy_check_link_status(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff817ad500)
Location: drivers/net/phy/phy.c:527
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start_aneg
```
**Symbols:**

```
ffffffff817ad500-ffffffff817ad5fd: phy_check_link_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int phy_check_link_status(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff817c7490)
Location: drivers/net/phy/phy.c:527
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start_aneg
```
**Symbols:**

```
ffffffff817c7490-ffffffff817c758d: phy_check_link_status (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
