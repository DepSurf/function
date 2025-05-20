# Function: <code>pinctrl_claim_hogs</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff8148fd61)
Location: drivers/pinctrl/core.c:2009
Inline: True
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
In drivers/pinctrl/core.c (ffffffff814cbf11)
Location: drivers/pinctrl/core.c:2018
Inline: True
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
In drivers/pinctrl/core.c (ffffffff814fce85)
Location: drivers/pinctrl/core.c:1967
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
In drivers/pinctrl/core.c (ffffffff815118e5)
Location: drivers/pinctrl/core.c:1995
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
In drivers/pinctrl/core.c (ffffffff8153fed5)
Location: drivers/pinctrl/core.c:1984
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_enable
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
In drivers/pinctrl/core.c (ffffffff81560d95)
Location: drivers/pinctrl/core.c:2012
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int pinctrl_claim_hogs(struct pinctrl_dev *pctldev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/core.c:2009
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_enable
```
**Symbols:**

```
ffffffff81603720-ffffffff81603820: pinctrl_claim_hogs (STB_LOCAL)
ffffffff81603f0d-ffffffff81603f45: pinctrl_claim_hogs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int pinctrl_claim_hogs(struct pinctrl_dev *pctldev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/core.c:2032
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_enable
```
**Symbols:**

```
ffffffff81628630-ffffffff81628730: pinctrl_claim_hogs (STB_LOCAL)
ffffffff81bf5132-ffffffff81bf516a: pinctrl_claim_hogs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int pinctrl_claim_hogs(struct pinctrl_dev *pctldev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/core.c:2057
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_enable
```
**Symbols:**

```
ffffffff8160c110-ffffffff8160c210: pinctrl_claim_hogs (STB_LOCAL)
ffffffff81be6fa9-ffffffff81be6fe1: pinctrl_claim_hogs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pinctrl_claim_hogs(struct pinctrl_dev *pctldev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/core.c:2057
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_enable
```
**Symbols:**

```
ffffffff8167ae10-ffffffff8167af07: pinctrl_claim_hogs (STB_LOCAL)
ffffffff81ce04bb-ffffffff81ce04f3: pinctrl_claim_hogs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pinctrl_claim_hogs(struct pinctrl_dev *pctldev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/core.c:2057
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_enable
```
**Symbols:**

```
ffffffff81796510-ffffffff81796601: pinctrl_claim_hogs (STB_LOCAL)
ffffffff81ea6c0a-ffffffff81ea6c3e: pinctrl_claim_hogs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pinctrl_claim_hogs(struct pinctrl_dev *pctldev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff818abc50)
Location: drivers/pinctrl/core.c:2056
Inline: False
```
**Symbols:**

```
ffffffff818abc50-ffffffff818abd78: pinctrl_claim_hogs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pinctrl_claim_hogs(struct pinctrl_dev *pctldev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff818eeb90)
Location: drivers/pinctrl/core.c:2065
Inline: False
```
**Symbols:**

```
ffffffff818eeb90-ffffffff818eecb8: pinctrl_claim_hogs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pinctrl_claim_hogs(struct pinctrl_dev *pctldev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81936350)
Location: drivers/pinctrl/core.c:2079
Inline: False
```
**Symbols:**

```
ffffffff81936350-ffffffff81936478: pinctrl_claim_hogs (STB_LOCAL)
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
In drivers/pinctrl/core.c (ffff80001068d8e4)
Location: drivers/pinctrl/core.c:2012
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_enable
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
In drivers/pinctrl/core.c (c082f938)
Location: drivers/pinctrl/core.c:2012
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_enable
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
In drivers/pinctrl/core.c (c000000000827958)
Location: drivers/pinctrl/core.c:2012
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_enable
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
In drivers/pinctrl/core.c (ffffffe000499a98)
Location: drivers/pinctrl/core.c:2012
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_enable
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
In drivers/pinctrl/core.c (ffffffff81559385)
Location: drivers/pinctrl/core.c:2012
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_enable
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
In drivers/pinctrl/core.c (ffffffff81549845)
Location: drivers/pinctrl/core.c:2012
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_enable
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
In drivers/pinctrl/core.c (ffffffff815550c5)
Location: drivers/pinctrl/core.c:2012
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_enable
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
In drivers/pinctrl/core.c (ffffffff8156ef55)
Location: drivers/pinctrl/core.c:2012
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_enable
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
