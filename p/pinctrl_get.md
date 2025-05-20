# Function: <code>pinctrl_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct pinctrl *pinctrl_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff8141e330)
Location: drivers/pinctrl/core.c:870
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_get
  - drivers/pinctrl/core.c:pinctrl_register
```
**Symbols:**

```
ffffffff8141e330-ffffffff8141e7bc: pinctrl_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct pinctrl *pinctrl_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81466a60)
Location: drivers/pinctrl/core.c:883
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_register
  - drivers/pinctrl/core.c:devm_pinctrl_get
```
**Symbols:**

```
ffffffff81466a60-ffffffff81466ef8: pinctrl_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct pinctrl *pinctrl_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81485d50)
Location: drivers/pinctrl/core.c:883
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_register
  - drivers/pinctrl/core.c:devm_pinctrl_get
```
**Symbols:**

```
ffffffff81485d50-ffffffff814861e8: pinctrl_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct pinctrl *pinctrl_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff8148fc10)
Location: drivers/pinctrl/core.c:1080
Inline: True
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_get
```
**Symbols:**

```
ffffffff8148fc10-ffffffff8148fcca: pinctrl_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct pinctrl *pinctrl_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff814cbdc0)
Location: drivers/pinctrl/core.c:1080
Inline: True
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_get
```
**Symbols:**

```
ffffffff814cbdc0-ffffffff814cbe80: pinctrl_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct pinctrl *pinctrl_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff814fcd40)
Location: drivers/pinctrl/core.c:1080
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_get
```
**Symbols:**

```
ffffffff814fcd40-ffffffff814fce00: pinctrl_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct pinctrl *pinctrl_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff815117a0)
Location: drivers/pinctrl/core.c:1108
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_get
```
**Symbols:**

```
ffffffff815117a0-ffffffff81511860: pinctrl_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct pinctrl *pinctrl_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/core.c:1084
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_get
```
**Symbols:**

```
ffffffff815409c7-ffffffff815409e1: pinctrl_get.cold (STB_LOCAL)
ffffffff8153fda0-ffffffff8153fe50: pinctrl_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct pinctrl *pinctrl_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81560c40)
Location: drivers/pinctrl/core.c:1112
Inline: True
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_get
```
**Symbols:**

```
ffffffff81560c40-ffffffff81560d02: pinctrl_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct pinctrl *pinctrl_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff816035a0)
Location: drivers/pinctrl/core.c:1113
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_get
```
**Symbols:**

```
ffffffff816035a0-ffffffff81603691: pinctrl_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct pinctrl *pinctrl_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff816284b0)
Location: drivers/pinctrl/core.c:1114
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_get
```
**Symbols:**

```
ffffffff816284b0-ffffffff816285a1: pinctrl_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct pinctrl *pinctrl_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff8160bf90)
Location: drivers/pinctrl/core.c:1114
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_get
```
**Symbols:**

```
ffffffff8160bf90-ffffffff8160c081: pinctrl_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct pinctrl *pinctrl_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff8167aca0)
Location: drivers/pinctrl/core.c:1114
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_get
```
**Symbols:**

```
ffffffff8167aca0-ffffffff8167ad8e: pinctrl_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct pinctrl *pinctrl_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81796360)
Location: drivers/pinctrl/core.c:1114
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_get
```
**Symbols:**

```
ffffffff81796360-ffffffff81796473: pinctrl_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct pinctrl *pinctrl_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff818aba80)
Location: drivers/pinctrl/core.c:1114
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_get
```
**Symbols:**

```
ffffffff818aba80-ffffffff818abb93: pinctrl_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct pinctrl *pinctrl_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff818ee9c0)
Location: drivers/pinctrl/core.c:1118
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_get
```
**Symbols:**

```
ffffffff818ee9c0-ffffffff818eead3: pinctrl_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct pinctrl *pinctrl_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81936180)
Location: drivers/pinctrl/core.c:1132
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_get
```
**Symbols:**

```
ffffffff81936180-ffffffff81936293: pinctrl_get (STB_GLOBAL)
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
struct pinctrl *pinctrl_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffff80001068d750)
Location: drivers/pinctrl/core.c:1112
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_get
```
**Symbols:**

```
ffff80001068d750-ffff80001068d83c: pinctrl_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct pinctrl *pinctrl_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (c082f7bc)
Location: drivers/pinctrl/core.c:1112
Inline: True
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_get
```
**Symbols:**

```
c082f7bc-c082f8a8: pinctrl_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct pinctrl *pinctrl_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (c000000000827730)
Location: drivers/pinctrl/core.c:1112
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_get
```
**Symbols:**

```
c000000000827730-c000000000827868: pinctrl_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct pinctrl *pinctrl_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffe000499920)
Location: drivers/pinctrl/core.c:1112
Inline: True
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_get
```
**Symbols:**

```
ffffffe000499920-ffffffe000499a02: pinctrl_get (STB_GLOBAL)
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
struct pinctrl *pinctrl_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81559230)
Location: drivers/pinctrl/core.c:1112
Inline: True
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_get
```
**Symbols:**

```
ffffffff81559230-ffffffff815592f2: pinctrl_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct pinctrl *pinctrl_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff815496f0)
Location: drivers/pinctrl/core.c:1112
Inline: True
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_get
```
**Symbols:**

```
ffffffff815496f0-ffffffff815497b2: pinctrl_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct pinctrl *pinctrl_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81554f70)
Location: drivers/pinctrl/core.c:1112
Inline: True
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_get
```
**Symbols:**

```
ffffffff81554f70-ffffffff81555032: pinctrl_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct pinctrl *pinctrl_get(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff8156ee00)
Location: drivers/pinctrl/core.c:1112
Inline: True
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_get
```
**Symbols:**

```
ffffffff8156ee00-ffffffff8156eec2: pinctrl_get (STB_GLOBAL)
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
