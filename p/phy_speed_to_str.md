# Function: <code>phy_speed_to_str</code>

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
In drivers/net/phy/phy.c (ffffffff815ea13b)
Location: drivers/net/phy/phy.c:41
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
In drivers/net/phy/phy.c (ffffffff81648bfb)
Location: drivers/net/phy/phy.c:41
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
In drivers/net/phy/phy.c (ffffffff81679deb)
Location: drivers/net/phy/phy.c:42
Inline: True
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
In drivers/net/phy/phy.c (ffffffff8168df69)
Location: drivers/net/phy/phy.c:42
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
const char *phy_speed_to_str(int speed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff816f9420)
Location: drivers/net/phy/phy-core.c:12
Inline: False
```
**Symbols:**

```
ffffffff816f9420-ffffffff816f950b: phy_speed_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
const char *phy_speed_to_str(int speed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81736620)
Location: drivers/net/phy/phy-core.c:12
Inline: False
```
**Symbols:**

```
ffffffff81736620-ffffffff8173672c: phy_speed_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
const char *phy_speed_to_str(int speed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81759710)
Location: drivers/net/phy/phy-core.c:12
Inline: False
Direct callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
**Symbols:**

```
ffffffff81759710-ffffffff8175981c: phy_speed_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
const char *phy_speed_to_str(int speed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81796710)
Location: drivers/net/phy/phy-core.c:9
Inline: False
Direct callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
**Symbols:**

```
ffffffff81796710-ffffffff81796841: phy_speed_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
const char *phy_speed_to_str(int speed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817ba190)
Location: drivers/net/phy/phy-core.c:9
Inline: False
Direct callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
**Symbols:**

```
ffffffff817ba190-ffffffff817ba2c1: phy_speed_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const char *phy_speed_to_str(int speed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff818816b0)
Location: drivers/net/phy/phy-core.c:9
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_print_status
  - drivers/net/phy/phy-core.c:phy_check_downshift
  - drivers/net/phy/phy-core.c:phy_check_downshift
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
**Symbols:**

```
ffffffff818816b0-ffffffff818817fb: phy_speed_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const char *phy_speed_to_str(int speed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff8188fde0)
Location: drivers/net/phy/phy-core.c:14
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_print_status
  - drivers/net/phy/phy-core.c:phy_check_downshift
  - drivers/net/phy/phy-core.c:phy_check_downshift
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
**Symbols:**

```
ffffffff8188fde0-ffffffff8188ff2b: phy_speed_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const char *phy_speed_to_str(int speed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff818726e0)
Location: drivers/net/phy/phy-core.c:14
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_print_status
  - drivers/net/phy/phy-core.c:phy_check_downshift
  - drivers/net/phy/phy-core.c:phy_check_downshift
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
**Symbols:**

```
ffffffff818726e0-ffffffff8187282b: phy_speed_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const char *phy_speed_to_str(int speed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81902df0)
Location: drivers/net/phy/phy-core.c:14
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_print_status
  - drivers/net/phy/phy-core.c:phy_check_downshift
  - drivers/net/phy/phy-core.c:phy_check_downshift
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
**Symbols:**

```
ffffffff81902df0-ffffffff81902f3b: phy_speed_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const char *phy_speed_to_str(int speed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81a55660)
Location: drivers/net/phy/phy-core.c:14
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_print_status
  - drivers/net/phy/phy-core.c:phy_check_downshift
  - drivers/net/phy/phy-core.c:phy_check_downshift
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
**Symbols:**

```
ffffffff81a55660-ffffffff81a5580b: phy_speed_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const char *phy_speed_to_str(int speed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81bdf000)
Location: drivers/net/phy/phy-core.c:14
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_check_downshift
  - drivers/net/phy/phy-core.c:phy_check_downshift
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
**Symbols:**

```
ffffffff81bdf000-ffffffff81bdf1c9: phy_speed_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const char *phy_speed_to_str(int speed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81c36900)
Location: drivers/net/phy/phy-core.c:14
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_check_downshift
  - drivers/net/phy/phy-core.c:phy_check_downshift
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
**Symbols:**

```
ffffffff81c36900-ffffffff81c36abd: phy_speed_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const char *phy_speed_to_str(int speed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81ceb880)
Location: drivers/net/phy/phy-core.c:14
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_check_downshift
  - drivers/net/phy/phy-core.c:phy_check_downshift
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
**Symbols:**

```
ffffffff81ceb880-ffffffff81ceba3d: phy_speed_to_str (STB_GLOBAL)
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
const char *phy_speed_to_str(int speed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffff8000109d2798)
Location: drivers/net/phy/phy-core.c:9
Inline: False
Direct callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
**Symbols:**

```
ffff8000109d2798-ffff8000109d292c: phy_speed_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const char *phy_speed_to_str(int speed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (c0aba894)
Location: drivers/net/phy/phy-core.c:9
Inline: False
Direct callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
**Symbols:**

```
c0aba894-c0abaa44: phy_speed_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
const char *phy_speed_to_str(int speed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (c000000000a92960)
Location: drivers/net/phy/phy-core.c:9
Inline: False
Direct callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
**Symbols:**

```
c000000000a92960-c000000000a92ad8: phy_speed_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
const char *phy_speed_to_str(int speed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffe00061f0d0)
Location: drivers/net/phy/phy-core.c:9
Inline: False
Direct callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
**Symbols:**

```
ffffffe00061f0d0-ffffffe00061f21e: phy_speed_to_str (STB_GLOBAL)
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
const char *phy_speed_to_str(int speed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff8177ec60)
Location: drivers/net/phy/phy-core.c:9
Inline: False
Direct callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
**Symbols:**

```
ffffffff8177ec60-ffffffff8177ed91: phy_speed_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
const char *phy_speed_to_str(int speed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff8175ea00)
Location: drivers/net/phy/phy-core.c:9
Inline: False
```
**Symbols:**

```
ffffffff8175ea00-ffffffff8175eb31: phy_speed_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
const char *phy_speed_to_str(int speed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817af010)
Location: drivers/net/phy/phy-core.c:9
Inline: False
Direct callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
**Symbols:**

```
ffffffff817af010-ffffffff817af141: phy_speed_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
const char *phy_speed_to_str(int speed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817c8fa0)
Location: drivers/net/phy/phy-core.c:9
Inline: False
Direct callers:
  - drivers/net/phy/phy_led_triggers.c:phy_led_triggers_register
```
**Symbols:**

```
ffffffff817c8fa0-ffffffff817c90d1: phy_speed_to_str (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
