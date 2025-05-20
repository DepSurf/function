# Function: <code>create_pinctrl</code>

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
In drivers/pinctrl/core.c (ffffffff8141e3d4)
Location: drivers/pinctrl/core.c:790
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_get
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
In drivers/pinctrl/core.c (ffffffff81466afd)
Location: drivers/pinctrl/core.c:803
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_get
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
In drivers/pinctrl/core.c (ffffffff81485ded)
Location: drivers/pinctrl/core.c:803
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_get
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct pinctrl *create_pinctrl(struct device *dev, struct pinctrl_dev *pctldev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff8148f830)
Location: drivers/pinctrl/core.c:991
Inline: False
```
**Symbols:**

```
ffffffff8148f830-ffffffff8148fc0d: create_pinctrl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct pinctrl *create_pinctrl(struct device *dev, struct pinctrl_dev *pctldev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff814cb9e0)
Location: drivers/pinctrl/core.c:991
Inline: False
```
**Symbols:**

```
ffffffff814cb9e0-ffffffff814cbdbd: create_pinctrl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct pinctrl *create_pinctrl(struct device *dev, struct pinctrl_dev *pctldev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff814fc980)
Location: drivers/pinctrl/core.c:991
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_get
```
**Symbols:**

```
ffffffff814fc980-ffffffff814fcd31: create_pinctrl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct pinctrl *create_pinctrl(struct device *dev, struct pinctrl_dev *pctldev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff815113e0)
Location: drivers/pinctrl/core.c:1019
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_get
```
**Symbols:**

```
ffffffff815113e0-ffffffff81511791: create_pinctrl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct pinctrl *create_pinctrl(struct device *dev, struct pinctrl_dev *pctldev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/core.c:995
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/pinctrl/core.c:pinctrl_get
```
**Symbols:**

```
ffffffff8153f9f0-ffffffff8153fd96: create_pinctrl (STB_LOCAL)
ffffffff815409ae-ffffffff815409c7: create_pinctrl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct pinctrl *create_pinctrl(struct device *dev, struct pinctrl_dev *pctldev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/core.c:1023
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_enable
```
**Symbols:**

```
ffffffff81560890-ffffffff81560c36: create_pinctrl (STB_LOCAL)
ffffffff81561842-ffffffff8156185b: create_pinctrl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct pinctrl *create_pinctrl(struct device *dev, struct pinctrl_dev *pctldev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff816033b0)
Location: drivers/pinctrl/core.c:1024
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_claim_hogs
  - drivers/pinctrl/core.c:pinctrl_get
```
**Symbols:**

```
ffffffff816033b0-ffffffff81603595: create_pinctrl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct pinctrl *create_pinctrl(struct device *dev, struct pinctrl_dev *pctldev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff816282c0)
Location: drivers/pinctrl/core.c:1025
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_claim_hogs
  - drivers/pinctrl/core.c:pinctrl_get
```
**Symbols:**

```
ffffffff816282c0-ffffffff816284a5: create_pinctrl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct pinctrl *create_pinctrl(struct device *dev, struct pinctrl_dev *pctldev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff8160bda0)
Location: drivers/pinctrl/core.c:1025
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_claim_hogs
  - drivers/pinctrl/core.c:pinctrl_get
```
**Symbols:**

```
ffffffff8160bda0-ffffffff8160bf85: create_pinctrl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct pinctrl *create_pinctrl(struct device *dev, struct pinctrl_dev *pctldev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff8167aab0)
Location: drivers/pinctrl/core.c:1025
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_claim_hogs
  - drivers/pinctrl/core.c:pinctrl_get
```
**Symbols:**

```
ffffffff8167aab0-ffffffff8167ac95: create_pinctrl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct pinctrl *create_pinctrl(struct device *dev, struct pinctrl_dev *pctldev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81796170)
Location: drivers/pinctrl/core.c:1025
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_claim_hogs
  - drivers/pinctrl/core.c:pinctrl_get
```
**Symbols:**

```
ffffffff81796170-ffffffff81796353: create_pinctrl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct pinctrl *create_pinctrl(struct device *dev, struct pinctrl_dev *pctldev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff818ab880)
Location: drivers/pinctrl/core.c:1026
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_claim_hogs
  - drivers/pinctrl/core.c:pinctrl_get
```
**Symbols:**

```
ffffffff818ab880-ffffffff818aba6c: create_pinctrl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct pinctrl *create_pinctrl(struct device *dev, struct pinctrl_dev *pctldev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff818ee7c0)
Location: drivers/pinctrl/core.c:1030
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_claim_hogs
  - drivers/pinctrl/core.c:pinctrl_get
```
**Symbols:**

```
ffffffff818ee7c0-ffffffff818ee9ac: create_pinctrl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct pinctrl *create_pinctrl(struct device *dev, struct pinctrl_dev *pctldev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81935f50)
Location: drivers/pinctrl/core.c:1044
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_claim_hogs
  - drivers/pinctrl/core.c:pinctrl_get
```
**Symbols:**

```
ffffffff81935f50-ffffffff8193616b: create_pinctrl (STB_LOCAL)
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
struct pinctrl *create_pinctrl(struct device *dev, struct pinctrl_dev *pctldev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffff80001068d3b0)
Location: drivers/pinctrl/core.c:1023
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/pinctrl/core.c:pinctrl_get
```
**Symbols:**

```
ffff80001068d3b0-ffff80001068d74c: create_pinctrl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct pinctrl *create_pinctrl(struct device *dev, struct pinctrl_dev *pctldev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (c082f3f0)
Location: drivers/pinctrl/core.c:1023
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_enable
```
**Symbols:**

```
c082f3f0-c082f7bc: create_pinctrl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct pinctrl *create_pinctrl(struct device *dev, struct pinctrl_dev *pctldev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (c000000000826d20)
Location: drivers/pinctrl/core.c:1023
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/pinctrl/core.c:pinctrl_get
```
**Symbols:**

```
c000000000826d20-c00000000082772c: create_pinctrl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct pinctrl *create_pinctrl(struct device *dev, struct pinctrl_dev *pctldev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffe0004995ce)
Location: drivers/pinctrl/core.c:1023
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_enable
```
**Symbols:**

```
ffffffe0004995ce-ffffffe000499920: create_pinctrl (STB_LOCAL)
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
struct pinctrl *create_pinctrl(struct device *dev, struct pinctrl_dev *pctldev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/core.c:1023
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_enable
```
**Symbols:**

```
ffffffff81558e80-ffffffff81559226: create_pinctrl (STB_LOCAL)
ffffffff81559e32-ffffffff81559e4b: create_pinctrl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct pinctrl *create_pinctrl(struct device *dev, struct pinctrl_dev *pctldev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/core.c:1023
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_enable
```
**Symbols:**

```
ffffffff81549340-ffffffff815496e6: create_pinctrl (STB_LOCAL)
ffffffff8154a2f2-ffffffff8154a30b: create_pinctrl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct pinctrl *create_pinctrl(struct device *dev, struct pinctrl_dev *pctldev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/core.c:1023
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_enable
```
**Symbols:**

```
ffffffff81554bc0-ffffffff81554f66: create_pinctrl (STB_LOCAL)
ffffffff81555b72-ffffffff81555b8b: create_pinctrl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct pinctrl *create_pinctrl(struct device *dev, struct pinctrl_dev *pctldev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/core.c:1023
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_enable
```
**Symbols:**

```
ffffffff8156ea50-ffffffff8156edf6: create_pinctrl (STB_LOCAL)
ffffffff8156fa02-ffffffff8156fa1b: create_pinctrl.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
