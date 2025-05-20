# Function: <code>phy_led_trigger_change_speed</code>

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
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void phy_led_trigger_change_speed(struct phy_device *phy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_led_triggers.c (ffffffff8167dc60)
Location: drivers/net/phy/phy_led_triggers.c:30
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
**Symbols:**

```
ffffffff8167dc60-ffffffff8167dd2f: phy_led_trigger_change_speed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void phy_led_trigger_change_speed(struct phy_device *phy);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_led_triggers.c (ffffffff81692d90)
Location: drivers/net/phy/phy_led_triggers.c:30
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
**Symbols:**

```
ffffffff81692d90-ffffffff81692e60: phy_led_trigger_change_speed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void phy_led_trigger_change_speed(struct phy_device *phy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_led_triggers.c (ffffffff816fcbb0)
Location: drivers/net/phy/phy_led_triggers.c:39
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
**Symbols:**

```
ffffffff816fcbb0-ffffffff816fccb1: phy_led_trigger_change_speed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void phy_led_trigger_change_speed(struct phy_device *phy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_led_triggers.c (ffffffff8173a350)
Location: drivers/net/phy/phy_led_triggers.c:39
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
**Symbols:**

```
ffffffff8173a350-ffffffff8173a455: phy_led_trigger_change_speed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void phy_led_trigger_change_speed(struct phy_device *phy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_led_triggers.c (ffffffff8175da90)
Location: drivers/net/phy/phy_led_triggers.c:39
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
**Symbols:**

```
ffffffff8175da90-ffffffff8175db96: phy_led_trigger_change_speed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void phy_led_trigger_change_speed(struct phy_device *phy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_led_triggers.c (0)
Location: drivers/net/phy/phy_led_triggers.c:29
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
**Symbols:**

```
ffffffff8179b45b-ffffffff8179b482: phy_led_trigger_change_speed.cold (STB_LOCAL)
ffffffff8179b0b0-ffffffff8179b1be: phy_led_trigger_change_speed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void phy_led_trigger_change_speed(struct phy_device *phy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_led_triggers.c (0)
Location: drivers/net/phy/phy_led_triggers.c:29
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
**Symbols:**

```
ffffffff817bef0b-ffffffff817bef32: phy_led_trigger_change_speed.cold (STB_LOCAL)
ffffffff817beb60-ffffffff817bec6e: phy_led_trigger_change_speed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void phy_led_trigger_change_speed(struct phy_device *phy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_led_triggers.c (ffffffff81887940)
Location: drivers/net/phy/phy_led_triggers.c:29
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
  - drivers/net/phy/phy.c:phy_start_cable_test
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
**Symbols:**

```
ffffffff81887940-ffffffff81887a45: phy_led_trigger_change_speed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void phy_led_trigger_change_speed(struct phy_device *phy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_led_triggers.c (ffffffff81895c00)
Location: drivers/net/phy/phy_led_triggers.c:29
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
  - drivers/net/phy/phy.c:phy_start_cable_test
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
**Symbols:**

```
ffffffff81895c00-ffffffff81895d05: phy_led_trigger_change_speed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void phy_led_trigger_change_speed(struct phy_device *phy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_led_triggers.c (ffffffff81878470)
Location: drivers/net/phy/phy_led_triggers.c:29
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
  - drivers/net/phy/phy.c:phy_start_cable_test
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
**Symbols:**

```
ffffffff81878470-ffffffff81878575: phy_led_trigger_change_speed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void phy_led_trigger_change_speed(struct phy_device *phy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_led_triggers.c (ffffffff81909380)
Location: drivers/net/phy/phy_led_triggers.c:29
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
  - drivers/net/phy/phy.c:phy_start_cable_test
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
**Symbols:**

```
ffffffff81909380-ffffffff81909485: phy_led_trigger_change_speed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void phy_led_trigger_change_speed(struct phy_device *phy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_led_triggers.c (ffffffff81a5c9b0)
Location: drivers/net/phy/phy_led_triggers.c:29
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_check_link_status
  - drivers/net/phy/phy.c:phy_check_link_status
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
  - drivers/net/phy/phy.c:phy_start_cable_test
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
**Symbols:**

```
ffffffff81a5c9b0-ffffffff81a5cacc: phy_led_trigger_change_speed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void phy_led_trigger_change_speed(struct phy_device *phy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_led_triggers.c (ffffffff81be7560)
Location: drivers/net/phy/phy_led_triggers.c:29
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_check_link_status
  - drivers/net/phy/phy.c:phy_check_link_status
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
  - drivers/net/phy/phy.c:phy_start_cable_test
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
**Symbols:**

```
ffffffff81be7560-ffffffff81be766b: phy_led_trigger_change_speed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void phy_led_trigger_change_speed(struct phy_device *phy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_led_triggers.c (ffffffff81c3f930)
Location: drivers/net/phy/phy_led_triggers.c:29
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_check_link_status
  - drivers/net/phy/phy.c:phy_check_link_status
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
  - drivers/net/phy/phy.c:phy_start_cable_test
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
**Symbols:**

```
ffffffff81c3f930-ffffffff81c3fa3b: phy_led_trigger_change_speed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void phy_led_trigger_change_speed(struct phy_device *phy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_led_triggers.c (ffffffff81cf4f30)
Location: drivers/net/phy/phy_led_triggers.c:29
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:_phy_state_machine
  - drivers/net/phy/phy.c:phy_check_link_status
  - drivers/net/phy/phy.c:phy_check_link_status
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
  - drivers/net/phy/phy.c:phy_start_cable_test
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
**Symbols:**

```
ffffffff81cf4f30-ffffffff81cf503b: phy_led_trigger_change_speed (STB_GLOBAL)
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
void phy_led_trigger_change_speed(struct phy_device *phy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_led_triggers.c (ffff8000109d8338)
Location: drivers/net/phy/phy_led_triggers.c:29
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
**Symbols:**

```
ffff8000109d8338-ffff8000109d841c: phy_led_trigger_change_speed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void phy_led_trigger_change_speed(struct phy_device *phy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_led_triggers.c (c0abfaa4)
Location: drivers/net/phy/phy_led_triggers.c:29
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
**Symbols:**

```
c0abfaa4-c0abfb60: phy_led_trigger_change_speed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void phy_led_trigger_change_speed(struct phy_device *phy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_led_triggers.c (c000000000a9a500)
Location: drivers/net/phy/phy_led_triggers.c:29
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
**Symbols:**

```
c000000000a9a500-c000000000a9a680: phy_led_trigger_change_speed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void phy_led_trigger_change_speed(struct phy_device *phy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_led_triggers.c (ffffffe000624002)
Location: drivers/net/phy/phy_led_triggers.c:29
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
**Symbols:**

```
ffffffe000624002-ffffffe0006240ce: phy_led_trigger_change_speed (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void phy_led_trigger_change_speed(struct phy_device *phy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_led_triggers.c (0)
Location: drivers/net/phy/phy_led_triggers.c:29
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
**Symbols:**

```
ffffffff817839db-ffffffff81783a02: phy_led_trigger_change_speed.cold (STB_LOCAL)
ffffffff81783630-ffffffff8178373e: phy_led_trigger_change_speed (STB_GLOBAL)
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
In drivers/net/phy/phy.c (0)
Location: include/linux/phy_led_triggers.h:38
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void phy_led_trigger_change_speed(struct phy_device *phy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_led_triggers.c (0)
Location: drivers/net/phy/phy_led_triggers.c:29
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
**Symbols:**

```
ffffffff817b3d8b-ffffffff817b3db2: phy_led_trigger_change_speed.cold (STB_LOCAL)
ffffffff817b39e0-ffffffff817b3aee: phy_led_trigger_change_speed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void phy_led_trigger_change_speed(struct phy_device *phy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy_led_triggers.c (0)
Location: drivers/net/phy/phy_led_triggers.c:29
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
**Symbols:**

```
ffffffff817cdd5b-ffffffff817cdd82: phy_led_trigger_change_speed.cold (STB_LOCAL)
ffffffff817cd9b0-ffffffff817cdabe: phy_led_trigger_change_speed (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
