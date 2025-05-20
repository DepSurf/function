# Function: <code>pinmux_func_name_to_selector</code>

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
In drivers/pinctrl/pinmux.c (ffffffff814201e6)
Location: drivers/pinctrl/pinmux.c:307
Inline: True
Inline callers:
  - drivers/pinctrl/pinmux.c:pinmux_map_to_setting
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
In drivers/pinctrl/pinmux.c (ffffffff814688f6)
Location: drivers/pinctrl/pinmux.c:307
Inline: True
Inline callers:
  - drivers/pinctrl/pinmux.c:pinmux_map_to_setting
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
In drivers/pinctrl/pinmux.c (ffffffff81487bd6)
Location: drivers/pinctrl/pinmux.c:307
Inline: True
Inline callers:
  - drivers/pinctrl/pinmux.c:pinmux_map_to_setting
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
In drivers/pinctrl/pinmux.c (ffffffff81491486)
Location: drivers/pinctrl/pinmux.c:294
Inline: True
Inline callers:
  - drivers/pinctrl/pinmux.c:pinmux_map_to_setting
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
In drivers/pinctrl/pinmux.c (ffffffff814cd6b6)
Location: drivers/pinctrl/pinmux.c:294
Inline: True
Inline callers:
  - drivers/pinctrl/pinmux.c:pinmux_map_to_setting
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
In drivers/pinctrl/pinmux.c (ffffffff814fe6ab)
Location: drivers/pinctrl/pinmux.c:294
Inline: True
Inline callers:
  - drivers/pinctrl/pinmux.c:pinmux_map_to_setting
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
In drivers/pinctrl/pinmux.c (ffffffff81513123)
Location: drivers/pinctrl/pinmux.c:293
Inline: True
Inline callers:
  - drivers/pinctrl/pinmux.c:pinmux_map_to_setting
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
In drivers/pinctrl/pinmux.c (ffffffff8154175f)
Location: drivers/pinctrl/pinmux.c:292
Inline: True
Inline callers:
  - drivers/pinctrl/pinmux.c:pinmux_map_to_setting
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
In drivers/pinctrl/pinmux.c (ffffffff815625ff)
Location: drivers/pinctrl/pinmux.c:316
Inline: True
Inline callers:
  - drivers/pinctrl/pinmux.c:pinmux_map_to_setting
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
In drivers/pinctrl/pinmux.c (ffffffff81604be0)
Location: drivers/pinctrl/pinmux.c:316
Inline: True
Inline callers:
  - drivers/pinctrl/pinmux.c:pinmux_map_to_setting
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
In drivers/pinctrl/pinmux.c (ffffffff81629740)
Location: drivers/pinctrl/pinmux.c:319
Inline: True
Inline callers:
  - drivers/pinctrl/pinmux.c:pinmux_map_to_setting
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pinmux_func_name_to_selector(struct pinctrl_dev *pctldev, const char *function);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffffffff8160c900)
Location: drivers/pinctrl/pinmux.c:320
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_select
  - drivers/pinctrl/pinmux.c:pinmux_map_to_setting
```
**Symbols:**

```
ffffffff8160c900-ffffffff8160c976: pinmux_func_name_to_selector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pinmux_func_name_to_selector(struct pinctrl_dev *pctldev, const char *function);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffffffff8167b600)
Location: drivers/pinctrl/pinmux.c:320
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_select
  - drivers/pinctrl/pinmux.c:pinmux_map_to_setting
```
**Symbols:**

```
ffffffff8167b600-ffffffff8167b676: pinmux_func_name_to_selector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pinmux_func_name_to_selector(struct pinctrl_dev *pctldev, const char *function);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffffffff81796db0)
Location: drivers/pinctrl/pinmux.c:320
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_select
  - drivers/pinctrl/pinmux.c:pinmux_map_to_setting
```
**Symbols:**

```
ffffffff81796db0-ffffffff81796e36: pinmux_func_name_to_selector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pinmux_func_name_to_selector(struct pinctrl_dev *pctldev, const char *function);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffffffff818ac6b0)
Location: drivers/pinctrl/pinmux.c:323
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_select
  - drivers/pinctrl/pinmux.c:pinmux_map_to_setting
```
**Symbols:**

```
ffffffff818ac6b0-ffffffff818ac736: pinmux_func_name_to_selector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pinmux_func_name_to_selector(struct pinctrl_dev *pctldev, const char *function);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffffffff818ef640)
Location: drivers/pinctrl/pinmux.c:323
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_select
  - drivers/pinctrl/pinmux.c:pinmux_map_to_setting
```
**Symbols:**

```
ffffffff818ef640-ffffffff818ef6c6: pinmux_func_name_to_selector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pinmux_func_name_to_selector(struct pinctrl_dev *pctldev, const char *function);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffffffff81936e00)
Location: drivers/pinctrl/pinmux.c:321
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_select
  - drivers/pinctrl/pinmux.c:pinmux_map_to_setting
```
**Symbols:**

```
ffffffff81936e00-ffffffff81936e86: pinmux_func_name_to_selector (STB_LOCAL)
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
int pinmux_func_name_to_selector(struct pinctrl_dev *pctldev, const char *function);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffff80001068e958)
Location: drivers/pinctrl/pinmux.c:316
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_map_to_setting
```
**Symbols:**

```
ffff80001068e958-ffff80001068e9fc: pinmux_func_name_to_selector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pinmux_func_name_to_selector(struct pinctrl_dev *pctldev, const char *function);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (c0830838)
Location: drivers/pinctrl/pinmux.c:316
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_map_to_setting
```
**Symbols:**

```
c0830838-c08308b4: pinmux_func_name_to_selector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pinmux_func_name_to_selector(struct pinctrl_dev *pctldev, const char *function);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (c0000000008293c0)
Location: drivers/pinctrl/pinmux.c:316
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_map_to_setting
```
**Symbols:**

```
c0000000008293c0-c000000000829674: pinmux_func_name_to_selector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pinmux_func_name_to_selector(struct pinctrl_dev *pctldev, const char *function);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffffffe00049a8f6)
Location: drivers/pinctrl/pinmux.c:316
Inline: False
Direct callers:
  - drivers/pinctrl/pinmux.c:pinmux_map_to_setting
```
**Symbols:**

```
ffffffe00049a8f6-ffffffe00049a96a: pinmux_func_name_to_selector (STB_LOCAL)
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
In drivers/pinctrl/pinmux.c (ffffffff8155abef)
Location: drivers/pinctrl/pinmux.c:316
Inline: True
Inline callers:
  - drivers/pinctrl/pinmux.c:pinmux_map_to_setting
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
In drivers/pinctrl/pinmux.c (ffffffff8154b0af)
Location: drivers/pinctrl/pinmux.c:316
Inline: True
Inline callers:
  - drivers/pinctrl/pinmux.c:pinmux_map_to_setting
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
In drivers/pinctrl/pinmux.c (ffffffff8155692f)
Location: drivers/pinctrl/pinmux.c:316
Inline: True
Inline callers:
  - drivers/pinctrl/pinmux.c:pinmux_map_to_setting
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
In drivers/pinctrl/pinmux.c (ffffffff815707bf)
Location: drivers/pinctrl/pinmux.c:316
Inline: True
Inline callers:
  - drivers/pinctrl/pinmux.c:pinmux_map_to_setting
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
