# Function: <code>pinctrl_pm_select_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pinctrl_pm_select_state(struct device *dev, struct pinctrl_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff8141d6e0)
Location: drivers/pinctrl/core.c:1282
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_pm_select_default_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_sleep_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_idle_state
```
**Symbols:**

```
ffffffff8141d6e0-ffffffff8141d736: pinctrl_pm_select_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pinctrl_pm_select_state(struct device *dev, struct pinctrl_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81465d90)
Location: drivers/pinctrl/core.c:1295
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_pm_select_idle_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_sleep_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_default_state
```
**Symbols:**

```
ffffffff81465d90-ffffffff81465de7: pinctrl_pm_select_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pinctrl_pm_select_state(struct device *dev, struct pinctrl_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81485090)
Location: drivers/pinctrl/core.c:1295
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_pm_select_idle_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_sleep_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_default_state
```
**Symbols:**

```
ffffffff81485090-ffffffff814850e7: pinctrl_pm_select_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pinctrl_pm_select_state(struct device *dev, struct pinctrl_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff8148e860)
Location: drivers/pinctrl/core.c:1490
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_pm_select_idle_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_sleep_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_default_state
```
**Symbols:**

```
ffffffff8148e860-ffffffff8148e8b7: pinctrl_pm_select_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pinctrl_pm_select_state(struct device *dev, struct pinctrl_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff814ca950)
Location: drivers/pinctrl/core.c:1499
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_pm_select_idle_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_sleep_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_default_state
```
**Symbols:**

```
ffffffff814ca950-ffffffff814ca9bd: pinctrl_pm_select_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pinctrl_pm_select_state(struct device *dev, struct pinctrl_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff814fb8b0)
Location: drivers/pinctrl/core.c:1500
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_pm_select_idle_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_sleep_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_default_state
```
**Symbols:**

```
ffffffff814fb8b0-ffffffff814fb919: pinctrl_pm_select_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pinctrl_pm_select_state(struct device *dev, struct pinctrl_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81510380)
Location: drivers/pinctrl/core.c:1528
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_pm_select_idle_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_sleep_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_default_state
```
**Symbols:**

```
ffffffff81510380-ffffffff815103e9: pinctrl_pm_select_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int pinctrl_pm_select_state(struct device *dev, struct pinctrl_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/core.c:1517
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_pm_select_idle_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_sleep_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_default_state
```
**Symbols:**

```
ffffffff8153ea40-ffffffff8153ea8a: pinctrl_pm_select_state (STB_LOCAL)
ffffffff81540932-ffffffff81540950: pinctrl_pm_select_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int pinctrl_pm_select_state(struct device *dev, struct pinctrl_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/core.c:1545
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_pm_select_idle_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_sleep_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_default_state
```
**Symbols:**

```
ffffffff8155f8e0-ffffffff8155f92a: pinctrl_pm_select_state (STB_LOCAL)
ffffffff815617ec-ffffffff8156180a: pinctrl_pm_select_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int pinctrl_pm_select_state(struct device *dev, struct pinctrl_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffff80001068bed8)
Location: drivers/pinctrl/core.c:1545
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_pm_select_idle_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_sleep_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_default_state
```
**Symbols:**

```
ffff80001068bed8-ffff80001068bf6c: pinctrl_pm_select_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pinctrl_pm_select_state(struct device *dev, struct pinctrl_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (c082e18c)
Location: drivers/pinctrl/core.c:1545
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_pm_select_idle_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_sleep_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_default_state
```
**Symbols:**

```
c082e18c-c082e1fc: pinctrl_pm_select_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pinctrl_pm_select_state(struct device *dev, struct pinctrl_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (c000000000824b80)
Location: drivers/pinctrl/core.c:1545
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_pm_select_idle_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_sleep_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_default_state
```
**Symbols:**

```
c000000000824b80-c000000000824c60: pinctrl_pm_select_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pinctrl_pm_select_state(struct device *dev, struct pinctrl_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffe0004982c4)
Location: drivers/pinctrl/core.c:1545
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_pm_select_idle_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_sleep_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_default_state
```
**Symbols:**

```
ffffffe0004982c4-ffffffe00049833a: pinctrl_pm_select_state (STB_LOCAL)
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
int pinctrl_pm_select_state(struct device *dev, struct pinctrl_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/core.c:1545
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_pm_select_idle_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_sleep_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_default_state
```
**Symbols:**

```
ffffffff81557ed0-ffffffff81557f1a: pinctrl_pm_select_state (STB_LOCAL)
ffffffff81559ddc-ffffffff81559dfa: pinctrl_pm_select_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int pinctrl_pm_select_state(struct device *dev, struct pinctrl_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/core.c:1545
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_pm_select_idle_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_sleep_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_default_state
```
**Symbols:**

```
ffffffff81548390-ffffffff815483da: pinctrl_pm_select_state (STB_LOCAL)
ffffffff8154a29c-ffffffff8154a2ba: pinctrl_pm_select_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int pinctrl_pm_select_state(struct device *dev, struct pinctrl_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/core.c:1545
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_pm_select_idle_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_sleep_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_default_state
```
**Symbols:**

```
ffffffff81553c10-ffffffff81553c5a: pinctrl_pm_select_state (STB_LOCAL)
ffffffff81555b1c-ffffffff81555b3a: pinctrl_pm_select_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int pinctrl_pm_select_state(struct device *dev, struct pinctrl_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/core.c:1545
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_pm_select_idle_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_sleep_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_default_state
```
**Symbols:**

```
ffffffff8156daa0-ffffffff8156daea: pinctrl_pm_select_state (STB_LOCAL)
ffffffff8156f9ac-ffffffff8156f9ca: pinctrl_pm_select_state.cold (STB_LOCAL)
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
