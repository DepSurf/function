# Function: <code>pinctrl_init_device_debugfs</code>

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
In drivers/pinctrl/core.c (ffffffff8141eb79)
Location: drivers/pinctrl/core.c:1650
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_register
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
In drivers/pinctrl/core.c (ffffffff81467295)
Location: drivers/pinctrl/core.c:1662
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_register
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
In drivers/pinctrl/core.c (ffffffff81486585)
Location: drivers/pinctrl/core.c:1662
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_register
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
In drivers/pinctrl/core.c (ffffffff8148fe13)
Location: drivers/pinctrl/core.c:1857
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
In drivers/pinctrl/core.c (ffffffff814cbfcf)
Location: drivers/pinctrl/core.c:1866
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
In drivers/pinctrl/core.c (ffffffff814fcf3d)
Location: drivers/pinctrl/core.c:1801
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
In drivers/pinctrl/core.c (ffffffff8151199d)
Location: drivers/pinctrl/core.c:1829
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
In drivers/pinctrl/core.c (ffffffff8153ffa9)
Location: drivers/pinctrl/core.c:1818
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
In drivers/pinctrl/core.c (ffffffff81560e5d)
Location: drivers/pinctrl/core.c:1846
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
void pinctrl_init_device_debugfs(struct pinctrl_dev *pctldev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/core.c:1843
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_enable
```
**Symbols:**

```
ffffffff81601cd0-ffffffff81601e29: pinctrl_init_device_debugfs (STB_LOCAL)
ffffffff81603d52-ffffffff81603d9a: pinctrl_init_device_debugfs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void pinctrl_init_device_debugfs(struct pinctrl_dev *pctldev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/core.c:1866
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_enable
```
**Symbols:**

```
ffffffff81626b30-ffffffff81626c89: pinctrl_init_device_debugfs (STB_LOCAL)
ffffffff81bf4f78-ffffffff81bf4fc0: pinctrl_init_device_debugfs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void pinctrl_init_device_debugfs(struct pinctrl_dev *pctldev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/core.c:1891
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_enable
```
**Symbols:**

```
ffffffff8160a3e0-ffffffff8160a539: pinctrl_init_device_debugfs (STB_LOCAL)
ffffffff81be6d86-ffffffff81be6dce: pinctrl_init_device_debugfs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void pinctrl_init_device_debugfs(struct pinctrl_dev *pctldev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/core.c:1891
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_enable
```
**Symbols:**

```
ffffffff816790c0-ffffffff81679219: pinctrl_init_device_debugfs (STB_LOCAL)
ffffffff81ce0212-ffffffff81ce025a: pinctrl_init_device_debugfs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void pinctrl_init_device_debugfs(struct pinctrl_dev *pctldev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/core.c:1891
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_enable
```
**Symbols:**

```
ffffffff817944c0-ffffffff81794627: pinctrl_init_device_debugfs (STB_LOCAL)
ffffffff81ea697e-ffffffff81ea69c4: pinctrl_init_device_debugfs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pinctrl_init_device_debugfs(struct pinctrl_dev *pctldev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff818a9790)
Location: drivers/pinctrl/core.c:1890
Inline: False
```
**Symbols:**

```
ffffffff818a9790-ffffffff818a9946: pinctrl_init_device_debugfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pinctrl_init_device_debugfs(struct pinctrl_dev *pctldev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff818ec680)
Location: drivers/pinctrl/core.c:1899
Inline: False
```
**Symbols:**

```
ffffffff818ec680-ffffffff818ec836: pinctrl_init_device_debugfs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pinctrl_init_device_debugfs(struct pinctrl_dev *pctldev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81933a40)
Location: drivers/pinctrl/core.c:1913
Inline: False
```
**Symbols:**

```
ffffffff81933a40-ffffffff81933bf6: pinctrl_init_device_debugfs (STB_LOCAL)
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
In drivers/pinctrl/core.c (ffff80001068d984)
Location: drivers/pinctrl/core.c:1846
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
In drivers/pinctrl/core.c (c082f9e0)
Location: drivers/pinctrl/core.c:1846
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
In drivers/pinctrl/core.c (c000000000827a1c)
Location: drivers/pinctrl/core.c:1846
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
In drivers/pinctrl/core.c (ffffffe000499b2c)
Location: drivers/pinctrl/core.c:1846
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
In drivers/pinctrl/core.c (ffffffff8155944d)
Location: drivers/pinctrl/core.c:1846
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
In drivers/pinctrl/core.c (ffffffff8154990d)
Location: drivers/pinctrl/core.c:1846
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
In drivers/pinctrl/core.c (ffffffff8155518d)
Location: drivers/pinctrl/core.c:1846
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
In drivers/pinctrl/core.c (ffffffff8156f01d)
Location: drivers/pinctrl/core.c:1846
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
