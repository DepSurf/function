# Function: <code>phy_queue_state_machine</code>

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
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81757cc5)
Location: drivers/net/phy/phy.c:474
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mac_interrupt
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_interrupt
  - drivers/net/phy/phy.c:phy_error
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void phy_queue_state_machine(struct phy_device *phydev, long unsigned int jiffies);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff817943e5)
Location: drivers/net/phy/phy.c:489
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mac_interrupt
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_interrupt
  - drivers/net/phy/phy.c:phy_error
```
**Symbols:**

```
ffffffff81794380-ffffffff817943a6: phy_queue_state_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void phy_queue_state_machine(struct phy_device *phydev, long unsigned int jiffies);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff817b7f15)
Location: drivers/net/phy/phy.c:494
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mac_interrupt
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_interrupt
  - drivers/net/phy/phy.c:phy_error
```
**Symbols:**

```
ffffffff817b7eb0-ffffffff817b7ed6: phy_queue_state_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void phy_queue_state_machine(struct phy_device *phydev, long unsigned int jiffies);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff8187f0a5)
Location: drivers/net/phy/phy.c:469
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mac_interrupt
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_interrupt
  - drivers/net/phy/phy.c:phy_error
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
**Symbols:**

```
ffffffff8187ee20-ffffffff8187ee46: phy_queue_state_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void phy_queue_state_machine(struct phy_device *phydev, long unsigned int jiffies);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff8188f092)
Location: drivers/net/phy/phy.c:469
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_error
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
**Symbols:**

```
ffffffff8188d530-ffffffff8188d556: phy_queue_state_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void phy_queue_state_machine(struct phy_device *phydev, long unsigned int jiffies);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff818719d2)
Location: drivers/net/phy/phy.c:469
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_error
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
**Symbols:**

```
ffffffff8186fe70-ffffffff8186fe96: phy_queue_state_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void phy_queue_state_machine(struct phy_device *phydev, long unsigned int jiffies);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81901fd2)
Location: drivers/net/phy/phy.c:417
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
**Symbols:**

```
ffffffff819005b0-ffffffff819005d6: phy_queue_state_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void phy_queue_state_machine(struct phy_device *phydev, long unsigned int jiffies);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81a52685)
Location: drivers/net/phy/phy.c:422
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mac_interrupt
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
**Symbols:**

```
ffffffff81a52260-ffffffff81a52294: phy_queue_state_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void phy_queue_state_machine(struct phy_device *phydev, long unsigned int jiffies);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81bdbc85)
Location: drivers/net/phy/phy.c:451
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mac_interrupt
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
**Symbols:**

```
ffffffff81bdb550-ffffffff81bdb584: phy_queue_state_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void phy_queue_state_machine(struct phy_device *phydev, long unsigned int jiffies);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81c32cf5)
Location: drivers/net/phy/phy.c:464
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mac_interrupt
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_error
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
**Symbols:**

```
ffffffff81c32030-ffffffff81c32064: phy_queue_state_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void phy_queue_state_machine(struct phy_device *phydev, long unsigned int jiffies);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81ce7cc8)
Location: drivers/net/phy/phy.c:518
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:_phy_state_machine
  - drivers/net/phy/phy.c:_phy_state_machine
  - drivers/net/phy/phy.c:phy_error
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
**Symbols:**

```
ffffffff81ce6d20-ffffffff81ce6d54: phy_queue_state_machine (STB_GLOBAL)
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
void phy_queue_state_machine(struct phy_device *phydev, long unsigned int jiffies);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffff8000109d0698)
Location: drivers/net/phy/phy.c:494
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mac_interrupt
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_interrupt
  - drivers/net/phy/phy.c:phy_error
```
**Symbols:**

```
ffff8000109d0640-ffff8000109d0680: phy_queue_state_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void phy_queue_state_machine(struct phy_device *phydev, long unsigned int jiffies);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (c0ab88ac)
Location: drivers/net/phy/phy.c:494
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mac_interrupt
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_interrupt
  - drivers/net/phy/phy.c:phy_error
```
**Symbols:**

```
c0ab8864-c0ab8898: phy_queue_state_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void phy_queue_state_machine(struct phy_device *phydev, long unsigned int jiffies);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (c000000000a8fa8c)
Location: drivers/net/phy/phy.c:494
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mac_interrupt
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_interrupt
  - drivers/net/phy/phy.c:phy_error
```
**Symbols:**

```
c000000000a8f9d0-c000000000a8fa20: phy_queue_state_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void phy_queue_state_machine(struct phy_device *phydev, long unsigned int jiffies);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffe00061d318)
Location: drivers/net/phy/phy.c:494
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mac_interrupt
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_interrupt
  - drivers/net/phy/phy.c:phy_error
```
**Symbols:**

```
ffffffe00061d2c4-ffffffe00061d302: phy_queue_state_machine (STB_GLOBAL)
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
void phy_queue_state_machine(struct phy_device *phydev, long unsigned int jiffies);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff8177c9e5)
Location: drivers/net/phy/phy.c:494
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mac_interrupt
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_interrupt
  - drivers/net/phy/phy.c:phy_error
```
**Symbols:**

```
ffffffff8177c980-ffffffff8177c9a6: phy_queue_state_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void phy_queue_state_machine(struct phy_device *phydev, long unsigned int jiffies);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff8175c795)
Location: drivers/net/phy/phy.c:494
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mac_interrupt
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_interrupt
  - drivers/net/phy/phy.c:phy_error
```
**Symbols:**

```
ffffffff8175c730-ffffffff8175c756: phy_queue_state_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void phy_queue_state_machine(struct phy_device *phydev, long unsigned int jiffies);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff817acd95)
Location: drivers/net/phy/phy.c:494
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mac_interrupt
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_interrupt
  - drivers/net/phy/phy.c:phy_error
```
**Symbols:**

```
ffffffff817acd30-ffffffff817acd56: phy_queue_state_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void phy_queue_state_machine(struct phy_device *phydev, long unsigned int jiffies);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff817c6d25)
Location: drivers/net/phy/phy.c:494
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mac_interrupt
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_interrupt
  - drivers/net/phy/phy.c:phy_error
```
**Symbols:**

```
ffffffff817c6cc0-ffffffff817c6ce6: phy_queue_state_machine (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
