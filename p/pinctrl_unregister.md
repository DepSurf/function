# Function: <code>pinctrl_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pinctrl_unregister(struct pinctrl_dev *pctldev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff8141df90)
Location: drivers/pinctrl/core.c:1833
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_remove
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
**Symbols:**

```
ffffffff8141df90-ffffffff8141e0af: pinctrl_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pinctrl_unregister(struct pinctrl_dev *pctldev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff814666a0)
Location: drivers/pinctrl/core.c:1845
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_dev_release
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
**Symbols:**

```
ffffffff814666a0-ffffffff814667bc: pinctrl_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pinctrl_unregister(struct pinctrl_dev *pctldev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81485990)
Location: drivers/pinctrl/core.c:1845
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_dev_release
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
**Symbols:**

```
ffffffff81485990-ffffffff81485aac: pinctrl_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pinctrl_unregister(struct pinctrl_dev *pctldev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff8148f258)
Location: drivers/pinctrl/core.c:2140
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_dev_release
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_dev_release
```
**Symbols:**

```
ffffffff8148f120-ffffffff8148f221: pinctrl_unregister.part.16 (STB_LOCAL)
ffffffff8148f230-ffffffff8148f247: pinctrl_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pinctrl_unregister(struct pinctrl_dev *pctldev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff814cb3b8)
Location: drivers/pinctrl/core.c:2149
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_dev_release
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_dev_release
```
**Symbols:**

```
ffffffff814cb280-ffffffff814cb390: pinctrl_unregister.part.16 (STB_LOCAL)
ffffffff814cb390-ffffffff814cb3a7: pinctrl_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pinctrl_unregister(struct pinctrl_dev *pctldev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff814fc348)
Location: drivers/pinctrl/core.c:2098
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_dev_release
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_dev_release
```
**Symbols:**

```
ffffffff814fc200-ffffffff814fc319: pinctrl_unregister.part.17 (STB_LOCAL)
ffffffff814fc320-ffffffff814fc336: pinctrl_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pinctrl_unregister(struct pinctrl_dev *pctldev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81511258)
Location: drivers/pinctrl/core.c:2126
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_dev_release
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_dev_release
```
**Symbols:**

```
ffffffff81511110-ffffffff81511229: pinctrl_unregister.part.17 (STB_LOCAL)
ffffffff81511230-ffffffff81511246: pinctrl_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pinctrl_unregister(struct pinctrl_dev *pctldev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff8153f858)
Location: drivers/pinctrl/core.c:2115
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_dev_release
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_dev_release
```
**Symbols:**

```
ffffffff8153f710-ffffffff8153f823: pinctrl_unregister.part.0 (STB_LOCAL)
ffffffff8153f830-ffffffff8153f846: pinctrl_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pinctrl_unregister(struct pinctrl_dev *pctldev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff815606f8)
Location: drivers/pinctrl/core.c:2142
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_dev_release
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_dev_release
```
**Symbols:**

```
ffffffff815605b0-ffffffff815606c3: pinctrl_unregister.part.0 (STB_LOCAL)
ffffffff815606d0-ffffffff815606e6: pinctrl_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pinctrl_unregister(struct pinctrl_dev *pctldev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81602d18)
Location: drivers/pinctrl/core.c:2139
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_dev_release
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_dev_release
```
**Symbols:**

```
ffffffff81602bc0-ffffffff81602cf0: pinctrl_unregister.part.0 (STB_LOCAL)
ffffffff81602cf0-ffffffff81602d06: pinctrl_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pinctrl_unregister(struct pinctrl_dev *pctldev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81627c28)
Location: drivers/pinctrl/core.c:2162
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_dev_release
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_dev_release
```
**Symbols:**

```
ffffffff81627ad0-ffffffff81627c00: pinctrl_unregister.part.0 (STB_LOCAL)
ffffffff81627c00-ffffffff81627c16: pinctrl_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pinctrl_unregister(struct pinctrl_dev *pctldev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff8160b6a8)
Location: drivers/pinctrl/core.c:2186
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_dev_release
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_dev_release
```
**Symbols:**

```
ffffffff8160b550-ffffffff8160b680: pinctrl_unregister.part.0 (STB_LOCAL)
ffffffff8160b680-ffffffff8160b696: pinctrl_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pinctrl_unregister(struct pinctrl_dev *pctldev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff8167a1b8)
Location: drivers/pinctrl/core.c:2188
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_dev_release
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_dev_release
```
**Symbols:**

```
ffffffff8167a060-ffffffff8167a190: pinctrl_unregister.part.0 (STB_LOCAL)
ffffffff8167a190-ffffffff8167a1a6: pinctrl_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pinctrl_unregister(struct pinctrl_dev *pctldev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81795728)
Location: drivers/pinctrl/core.c:2188
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_dev_release
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_dev_release
```
**Symbols:**

```
ffffffff817955b0-ffffffff817956e5: pinctrl_unregister.part.0 (STB_LOCAL)
ffffffff817956f0-ffffffff81795712: pinctrl_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pinctrl_unregister(struct pinctrl_dev *pctldev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff818aacb8)
Location: drivers/pinctrl/core.c:2187
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_dev_release
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_dev_release
```
**Symbols:**

```
ffffffff818aab20-ffffffff818aac55: pinctrl_unregister.part.0 (STB_LOCAL)
ffffffff818aac70-ffffffff818aac92: pinctrl_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pinctrl_unregister(struct pinctrl_dev *pctldev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff818edb98)
Location: drivers/pinctrl/core.c:2196
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_dev_release
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_dev_release
```
**Symbols:**

```
ffffffff818eda00-ffffffff818edb35: pinctrl_unregister.part.0 (STB_LOCAL)
ffffffff818edb50-ffffffff818edb72: pinctrl_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pinctrl_unregister(struct pinctrl_dev *pctldev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81935368)
Location: drivers/pinctrl/core.c:2210
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_dev_release
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_dev_release
```
**Symbols:**

```
ffffffff819351d0-ffffffff81935305: pinctrl_unregister.part.0 (STB_LOCAL)
ffffffff81935320-ffffffff81935342: pinctrl_unregister (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pinctrl_unregister(struct pinctrl_dev *pctldev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (ffff80001068d234)
Location: drivers/pinctrl/core.c:2142
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_dev_release
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_dev_release
  - drivers/pinctrl/pinctrl-single.c:pcs_free_resources
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_probe
  - drivers/pinctrl/sprd/pinctrl-sprd.c:sprd_pinctrl_remove
```
**Symbols:**

```
ffff80001068d048-ffff80001068d1e8: pinctrl_unregister.part.0 (STB_LOCAL)
ffff80001068d1e8-ffff80001068d218: pinctrl_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pinctrl_unregister(struct pinctrl_dev *pctldev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (c082f2c8)
Location: drivers/pinctrl/core.c:2142
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_dev_release
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_dev_release
  - drivers/pinctrl/pinctrl-single.c:pcs_free_resources
  - drivers/pinctrl/freescale/pinctrl-imx.c:imx_pinctrl_probe
  - drivers/pinctrl/ti/pinctrl-ti-iodelay.c:ti_iodelay_remove
  - drivers/rtc/rtc-omap.c:omap_rtc_remove
  - drivers/rtc/rtc-omap.c:omap_rtc_probe
```
**Symbols:**

```
c082f0f0-c082f28c: pinctrl_unregister.part.0 (STB_LOCAL)
c082f28c-c082f2b0: pinctrl_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pinctrl_unregister(struct pinctrl_dev *pctldev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (c000000000826024)
Location: drivers/pinctrl/core.c:2142
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_dev_release
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_dev_release
  - drivers/pinctrl/pinctrl-single.c:pcs_free_resources
```
**Symbols:**

```
c000000000825d80-c000000000825ff0: pinctrl_unregister.part.0 (STB_LOCAL)
c000000000825ff0-c00000000082600c: pinctrl_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pinctrl_unregister(struct pinctrl_dev *pctldev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (ffffffe0004993dc)
Location: drivers/pinctrl/core.c:2142
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_dev_release
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_dev_release
  - drivers/pinctrl/pinctrl-single.c:pcs_free_resources
```
**Symbols:**

```
ffffffe000499228-ffffffe000499398: pinctrl_unregister.part.0 (STB_LOCAL)
ffffffe000499398-ffffffe0004993c4: pinctrl_unregister (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pinctrl_unregister(struct pinctrl_dev *pctldev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81558ce8)
Location: drivers/pinctrl/core.c:2142
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_dev_release
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_dev_release
```
**Symbols:**

```
ffffffff81558ba0-ffffffff81558cb3: pinctrl_unregister.part.0 (STB_LOCAL)
ffffffff81558cc0-ffffffff81558cd6: pinctrl_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pinctrl_unregister(struct pinctrl_dev *pctldev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff815491a8)
Location: drivers/pinctrl/core.c:2142
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_dev_release
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_dev_release
```
**Symbols:**

```
ffffffff81549060-ffffffff81549173: pinctrl_unregister.part.0 (STB_LOCAL)
ffffffff81549180-ffffffff81549196: pinctrl_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pinctrl_unregister(struct pinctrl_dev *pctldev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81554a28)
Location: drivers/pinctrl/core.c:2142
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_dev_release
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_dev_release
```
**Symbols:**

```
ffffffff815548e0-ffffffff815549f3: pinctrl_unregister.part.0 (STB_LOCAL)
ffffffff81554a00-ffffffff81554a16: pinctrl_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pinctrl_unregister(struct pinctrl_dev *pctldev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff8156e8b8)
Location: drivers/pinctrl/core.c:2142
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:devm_pinctrl_dev_release
Direct callers:
  - drivers/pinctrl/core.c:devm_pinctrl_dev_release
```
**Symbols:**

```
ffffffff8156e770-ffffffff8156e883: pinctrl_unregister.part.0 (STB_LOCAL)
ffffffff8156e890-ffffffff8156e8a6: pinctrl_unregister (STB_GLOBAL)
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
