# Function: <code>phy_trigger_machine</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void phy_trigger_machine(struct phy_device *phydev, bool sync);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81679b50)
Location: drivers/net/phy/phy.c:659
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_change
  - drivers/net/phy/phy.c:phy_error
```
**Symbols:**

```
ffffffff81679b50-ffffffff81679b8e: phy_trigger_machine (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void phy_trigger_machine(struct phy_device *phydev, bool sync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff8168e650)
Location: drivers/net/phy/phy.c:727
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_change
  - drivers/net/phy/phy.c:phy_error
  - drivers/net/phy/phy.c:phy_start_aneg_priv
```
**Symbols:**

```
ffffffff8168e650-ffffffff8168e68e: phy_trigger_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void phy_trigger_machine(struct phy_device *phydev, bool sync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff816f8100)
Location: drivers/net/phy/phy.c:572
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_change
  - drivers/net/phy/phy.c:phy_error
  - drivers/net/phy/phy.c:phy_start_aneg_priv
```
**Symbols:**

```
ffffffff816f8100-ffffffff816f813e: phy_trigger_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void phy_trigger_machine(struct phy_device *phydev, bool sync);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff817352d0)
Location: drivers/net/phy/phy.c:575
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_change
  - drivers/net/phy/phy.c:phy_error
  - drivers/net/phy/phy.c:phy_start_aneg_priv
```
**Symbols:**

```
ffffffff817352d0-ffffffff8173530e: phy_trigger_machine (STB_GLOBAL)
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
In drivers/net/phy/phy.c (ffffffff81757cc5)
Location: drivers/net/phy/phy.c:481
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mac_interrupt
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_interrupt
  - drivers/net/phy/phy.c:phy_error
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
In drivers/net/phy/phy.c (ffffffff817943e5)
Location: drivers/net/phy/phy.c:496
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mac_interrupt
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_interrupt
  - drivers/net/phy/phy.c:phy_error
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
In drivers/net/phy/phy.c (ffffffff817b7f15)
Location: drivers/net/phy/phy.c:501
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mac_interrupt
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_interrupt
  - drivers/net/phy/phy.c:phy_error
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
In drivers/net/phy/phy.c (ffffffff8187f0a5)
Location: drivers/net/phy/phy.c:476
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mac_interrupt
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_interrupt
  - drivers/net/phy/phy.c:phy_error
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void phy_trigger_machine(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff8188db38)
Location: drivers/net/phy/phy.c:481
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_error
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
Direct callers:
  - drivers/net/phy/phy_device.c:genphy_handle_interrupt_no_ack
```
**Symbols:**

```
ffffffff8188d560-ffffffff8188d585: phy_trigger_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void phy_trigger_machine(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81870478)
Location: drivers/net/phy/phy.c:481
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_error
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
Direct callers:
  - drivers/net/phy/phy_device.c:genphy_handle_interrupt_no_ack
```
**Symbols:**

```
ffffffff8186fea0-ffffffff8186fec5: phy_trigger_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void phy_trigger_machine(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81901fd2)
Location: drivers/net/phy/phy.c:429
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
Direct callers:
  - drivers/net/phy/phy_device.c:genphy_handle_interrupt_no_ack
```
**Symbols:**

```
ffffffff819005e0-ffffffff81900605: phy_trigger_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void phy_trigger_machine(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81a52685)
Location: drivers/net/phy/phy.c:434
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mac_interrupt
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
Direct callers:
  - drivers/net/phy/phy_device.c:genphy_handle_interrupt_no_ack
```
**Symbols:**

```
ffffffff81a522a0-ffffffff81a522d3: phy_trigger_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void phy_trigger_machine(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81bdbc85)
Location: drivers/net/phy/phy.c:463
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mac_interrupt
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
Direct callers:
  - drivers/net/phy/phy_device.c:genphy_handle_interrupt_no_ack
```
**Symbols:**

```
ffffffff81bdb5a0-ffffffff81bdb5d3: phy_trigger_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void phy_trigger_machine(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81c32cf5)
Location: drivers/net/phy/phy.c:476
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mac_interrupt
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_error
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
Direct callers:
  - drivers/net/phy/phy_device.c:genphy_handle_interrupt_no_ack
```
**Symbols:**

```
ffffffff81c32080-ffffffff81c320b3: phy_trigger_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void phy_trigger_machine(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81ce7cc8)
Location: drivers/net/phy/phy.c:530
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:_phy_state_machine
  - drivers/net/phy/phy.c:phy_error
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
Direct callers:
  - drivers/net/phy/phy_device.c:genphy_handle_interrupt_no_ack
```
**Symbols:**

```
ffffffff81ce6d70-ffffffff81ce6da3: phy_trigger_machine (STB_GLOBAL)
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
In drivers/net/phy/phy.c (ffff8000109d0698)
Location: drivers/net/phy/phy.c:501
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mac_interrupt
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_interrupt
  - drivers/net/phy/phy.c:phy_error
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
In drivers/net/phy/phy.c (c0ab88ac)
Location: drivers/net/phy/phy.c:501
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mac_interrupt
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_interrupt
  - drivers/net/phy/phy.c:phy_error
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
In drivers/net/phy/phy.c (c000000000a8fa8c)
Location: drivers/net/phy/phy.c:501
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mac_interrupt
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_interrupt
  - drivers/net/phy/phy.c:phy_error
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
In drivers/net/phy/phy.c (ffffffe00061d318)
Location: drivers/net/phy/phy.c:501
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mac_interrupt
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_interrupt
  - drivers/net/phy/phy.c:phy_error
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
In drivers/net/phy/phy.c (ffffffff8177c9e5)
Location: drivers/net/phy/phy.c:501
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mac_interrupt
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_interrupt
  - drivers/net/phy/phy.c:phy_error
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
In drivers/net/phy/phy.c (ffffffff8175c795)
Location: drivers/net/phy/phy.c:501
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mac_interrupt
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_interrupt
  - drivers/net/phy/phy.c:phy_error
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
In drivers/net/phy/phy.c (ffffffff817acd95)
Location: drivers/net/phy/phy.c:501
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mac_interrupt
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_interrupt
  - drivers/net/phy/phy.c:phy_error
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
In drivers/net/phy/phy.c (ffffffff817c6d25)
Location: drivers/net/phy/phy.c:501
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mac_interrupt
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_interrupt
  - drivers/net/phy/phy.c:phy_error
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
