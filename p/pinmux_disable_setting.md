# Function: <code>pinmux_disable_setting</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pinmux_disable_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffffffff81420640)
Location: drivers/pinctrl/pinmux.c:481
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_free
  - drivers/pinctrl/core.c:pinctrl_select_state
  - drivers/pinctrl/core.c:pinctrl_select_state
```
**Symbols:**

```
ffffffff81420640-ffffffff814207aa: pinmux_disable_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pinmux_disable_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffffffff81468d30)
Location: drivers/pinctrl/pinmux.c:474
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_select_state
  - drivers/pinctrl/core.c:pinctrl_select_state
  - drivers/pinctrl/core.c:pinctrl_free
```
**Symbols:**

```
ffffffff81468d30-ffffffff81468e9b: pinmux_disable_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pinmux_disable_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffffffff81488010)
Location: drivers/pinctrl/pinmux.c:474
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_select_state
  - drivers/pinctrl/core.c:pinctrl_select_state
  - drivers/pinctrl/core.c:pinctrl_free
```
**Symbols:**

```
ffffffff81488010-ffffffff8148817b: pinmux_disable_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pinmux_disable_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffffffff814918d0)
Location: drivers/pinctrl/pinmux.c:461
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_select_state
  - drivers/pinctrl/core.c:pinctrl_select_state
  - drivers/pinctrl/core.c:pinctrl_free
```
**Symbols:**

```
ffffffff814918d0-ffffffff81491a25: pinmux_disable_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pinmux_disable_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffffffff814cdb20)
Location: drivers/pinctrl/pinmux.c:461
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pinctrl/core.c:pinctrl_free
```
**Symbols:**

```
ffffffff814cdb20-ffffffff814cdc87: pinmux_disable_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pinmux_disable_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffffffff814feb00)
Location: drivers/pinctrl/pinmux.c:461
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pinctrl/core.c:pinctrl_free
```
**Symbols:**

```
ffffffff814feb00-ffffffff814fec6b: pinmux_disable_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pinmux_disable_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffffffff81513570)
Location: drivers/pinctrl/pinmux.c:459
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pinctrl/core.c:pinctrl_free
```
**Symbols:**

```
ffffffff81513570-ffffffff815136db: pinmux_disable_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void pinmux_disable_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinmux.c (0)
Location: drivers/pinctrl/pinmux.c:458
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pinctrl/core.c:pinctrl_free
```
**Symbols:**

```
ffffffff81541fa2-ffffffff81541fc0: pinmux_disable_setting.cold (STB_LOCAL)
ffffffff81541ae0-ffffffff81541c3a: pinmux_disable_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void pinmux_disable_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinmux.c (0)
Location: drivers/pinctrl/pinmux.c:482
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pinctrl/core.c:pinctrl_free
```
**Symbols:**

```
ffffffff81562e2c-ffffffff81562e4a: pinmux_disable_setting.cold (STB_LOCAL)
ffffffff81562980-ffffffff81562ada: pinmux_disable_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void pinmux_disable_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinmux.c (0)
Location: drivers/pinctrl/pinmux.c:482
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pinctrl/core.c:pinctrl_free
```
**Symbols:**

```
ffffffff8160541c-ffffffff8160543a: pinmux_disable_setting.cold (STB_LOCAL)
ffffffff81604f60-ffffffff816050ba: pinmux_disable_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void pinmux_disable_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinmux.c (0)
Location: drivers/pinctrl/pinmux.c:485
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pinctrl/core.c:pinctrl_free
```
**Symbols:**

```
ffffffff81bf543a-ffffffff81bf5458: pinmux_disable_setting.cold (STB_LOCAL)
ffffffff81629ac0-ffffffff81629c1a: pinmux_disable_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void pinmux_disable_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinmux.c (0)
Location: drivers/pinctrl/pinmux.c:486
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pinctrl/core.c:pinctrl_free
```
**Symbols:**

```
ffffffff81be735e-ffffffff81be737c: pinmux_disable_setting.cold (STB_LOCAL)
ffffffff8160d780-ffffffff8160d8da: pinmux_disable_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void pinmux_disable_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinmux.c (0)
Location: drivers/pinctrl/pinmux.c:486
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pinctrl/core.c:pinctrl_free
```
**Symbols:**

```
ffffffff81ce099b-ffffffff81ce09b9: pinmux_disable_setting.cold (STB_LOCAL)
ffffffff8167c4f0-ffffffff8167c64a: pinmux_disable_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void pinmux_disable_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinmux.c (0)
Location: drivers/pinctrl/pinmux.c:486
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pinctrl/core.c:pinctrl_free
```
**Symbols:**

```
ffffffff81ea70c3-ffffffff81ea70e1: pinmux_disable_setting.cold (STB_LOCAL)
ffffffff81797d90-ffffffff81797efb: pinmux_disable_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pinmux_disable_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffffffff818ada50)
Location: drivers/pinctrl/pinmux.c:489
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pinctrl/core.c:pinctrl_free
```
**Symbols:**

```
ffffffff818ada50-ffffffff818adbcf: pinmux_disable_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pinmux_disable_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffffffff818f09a0)
Location: drivers/pinctrl/pinmux.c:489
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pinctrl/core.c:pinctrl_free
```
**Symbols:**

```
ffffffff818f09a0-ffffffff818f0b1f: pinmux_disable_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pinmux_disable_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffffffff81938150)
Location: drivers/pinctrl/pinmux.c:487
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pinctrl/core.c:pinctrl_free
```
**Symbols:**

```
ffffffff81938150-ffffffff819382cf: pinmux_disable_setting (STB_GLOBAL)
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
void pinmux_disable_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffff80001068fb38)
Location: drivers/pinctrl/pinmux.c:482
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pinctrl/core.c:pinctrl_free
```
**Symbols:**

```
ffff80001068fb38-ffff80001068fce4: pinmux_disable_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pinmux_disable_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (c08318f8)
Location: drivers/pinctrl/pinmux.c:482
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pinctrl/core.c:pinctrl_free
```
**Symbols:**

```
c08318f8-c0831a84: pinmux_disable_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pinmux_disable_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (c00000000082b1a0)
Location: drivers/pinctrl/pinmux.c:482
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pinctrl/core.c:pinctrl_free
```
**Symbols:**

```
c00000000082b1a0-c00000000082b3a4: pinmux_disable_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pinmux_disable_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffffffe00049b7d4)
Location: drivers/pinctrl/pinmux.c:482
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pinctrl/core.c:pinctrl_free
```
**Symbols:**

```
ffffffe00049b7d4-ffffffe00049b906: pinmux_disable_setting (STB_GLOBAL)
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
void pinmux_disable_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinmux.c (0)
Location: drivers/pinctrl/pinmux.c:482
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pinctrl/core.c:pinctrl_free
```
**Symbols:**

```
ffffffff8155b41c-ffffffff8155b43a: pinmux_disable_setting.cold (STB_LOCAL)
ffffffff8155af70-ffffffff8155b0ca: pinmux_disable_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void pinmux_disable_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinmux.c (0)
Location: drivers/pinctrl/pinmux.c:482
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pinctrl/core.c:pinctrl_free
```
**Symbols:**

```
ffffffff8154b8dc-ffffffff8154b8fa: pinmux_disable_setting.cold (STB_LOCAL)
ffffffff8154b430-ffffffff8154b58a: pinmux_disable_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void pinmux_disable_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinmux.c (0)
Location: drivers/pinctrl/pinmux.c:482
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pinctrl/core.c:pinctrl_free
```
**Symbols:**

```
ffffffff8155715c-ffffffff8155717a: pinmux_disable_setting.cold (STB_LOCAL)
ffffffff81556cb0-ffffffff81556e0a: pinmux_disable_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void pinmux_disable_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinmux.c (0)
Location: drivers/pinctrl/pinmux.c:482
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pinctrl/core.c:pinctrl_commit_state
  - drivers/pinctrl/core.c:pinctrl_free
```
**Symbols:**

```
ffffffff81570fec-ffffffff8157100a: pinmux_disable_setting.cold (STB_LOCAL)
ffffffff81570b40-ffffffff81570c9a: pinmux_disable_setting (STB_GLOBAL)
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
