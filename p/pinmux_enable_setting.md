# Function: <code>pinmux_enable_setting</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pinmux_enable_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffffffff814203f0)
Location: drivers/pinctrl/pinmux.c:400
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_select_state
```
**Symbols:**

```
ffffffff814203f0-ffffffff81420636: pinmux_enable_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pinmux_enable_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffffffff81468ae0)
Location: drivers/pinctrl/pinmux.c:393
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_select_state
```
**Symbols:**

```
ffffffff81468ae0-ffffffff81468d23: pinmux_enable_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pinmux_enable_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffffffff81487dc0)
Location: drivers/pinctrl/pinmux.c:393
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_select_state
```
**Symbols:**

```
ffffffff81487dc0-ffffffff81488003: pinmux_enable_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pinmux_enable_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffffffff81491670)
Location: drivers/pinctrl/pinmux.c:380
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_select_state
```
**Symbols:**

```
ffffffff81491670-ffffffff814918c8: pinmux_enable_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pinmux_enable_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffffffff814cd8b0)
Location: drivers/pinctrl/pinmux.c:380
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
```
**Symbols:**

```
ffffffff814cd8b0-ffffffff814cdb1c: pinmux_enable_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pinmux_enable_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffffffff814fe880)
Location: drivers/pinctrl/pinmux.c:380
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
```
**Symbols:**

```
ffffffff814fe880-ffffffff814feafe: pinmux_enable_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pinmux_enable_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffffffff815132f0)
Location: drivers/pinctrl/pinmux.c:378
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
```
**Symbols:**

```
ffffffff815132f0-ffffffff8151356e: pinmux_enable_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int pinmux_enable_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinmux.c (0)
Location: drivers/pinctrl/pinmux.c:377
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
```
**Symbols:**

```
ffffffff81541f84-ffffffff81541fa2: pinmux_enable_setting.cold (STB_LOCAL)
ffffffff81541880-ffffffff81541ad4: pinmux_enable_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int pinmux_enable_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinmux.c (0)
Location: drivers/pinctrl/pinmux.c:401
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
```
**Symbols:**

```
ffffffff81562e0e-ffffffff81562e2c: pinmux_enable_setting.cold (STB_LOCAL)
ffffffff81562720-ffffffff81562974: pinmux_enable_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int pinmux_enable_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinmux.c (0)
Location: drivers/pinctrl/pinmux.c:401
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
```
**Symbols:**

```
ffffffff816053fe-ffffffff8160541c: pinmux_enable_setting.cold (STB_LOCAL)
ffffffff81604d00-ffffffff81604f54: pinmux_enable_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int pinmux_enable_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinmux.c (0)
Location: drivers/pinctrl/pinmux.c:404
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
```
**Symbols:**

```
ffffffff81bf541d-ffffffff81bf543a: pinmux_enable_setting.cold (STB_LOCAL)
ffffffff81629860-ffffffff81629ab7: pinmux_enable_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int pinmux_enable_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinmux.c (0)
Location: drivers/pinctrl/pinmux.c:405
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
```
**Symbols:**

```
ffffffff81be7340-ffffffff81be735e: pinmux_enable_setting.cold (STB_LOCAL)
ffffffff8160d520-ffffffff8160d774: pinmux_enable_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pinmux_enable_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinmux.c (0)
Location: drivers/pinctrl/pinmux.c:405
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
```
**Symbols:**

```
ffffffff81ce097d-ffffffff81ce099b: pinmux_enable_setting.cold (STB_LOCAL)
ffffffff8167c290-ffffffff8167c4e4: pinmux_enable_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pinmux_enable_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinmux.c (0)
Location: drivers/pinctrl/pinmux.c:405
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
```
**Symbols:**

```
ffffffff81ea70a6-ffffffff81ea70c3: pinmux_enable_setting.cold (STB_LOCAL)
ffffffff81797b20-ffffffff81797d84: pinmux_enable_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pinmux_enable_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffffffff818ad7c0)
Location: drivers/pinctrl/pinmux.c:408
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
```
**Symbols:**

```
ffffffff818ad7c0-ffffffff818ada3f: pinmux_enable_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pinmux_enable_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffffffff818f0700)
Location: drivers/pinctrl/pinmux.c:408
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
```
**Symbols:**

```
ffffffff818f0700-ffffffff818f0982: pinmux_enable_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pinmux_enable_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffffffff81937eb0)
Location: drivers/pinctrl/pinmux.c:406
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
```
**Symbols:**

```
ffffffff81937eb0-ffffffff81938132: pinmux_enable_setting (STB_GLOBAL)
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
int pinmux_enable_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffff80001068f8b8)
Location: drivers/pinctrl/pinmux.c:401
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
```
**Symbols:**

```
ffff80001068f8b8-ffff80001068fb38: pinmux_enable_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pinmux_enable_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (c083168c)
Location: drivers/pinctrl/pinmux.c:401
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
```
**Symbols:**

```
c083168c-c08318f8: pinmux_enable_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pinmux_enable_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (c00000000082ae50)
Location: drivers/pinctrl/pinmux.c:401
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
```
**Symbols:**

```
c00000000082ae50-c00000000082b198: pinmux_enable_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pinmux_enable_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinmux.c (ffffffe00049b5ce)
Location: drivers/pinctrl/pinmux.c:401
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
```
**Symbols:**

```
ffffffe00049b5ce-ffffffe00049b7d4: pinmux_enable_setting (STB_GLOBAL)
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
int pinmux_enable_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinmux.c (0)
Location: drivers/pinctrl/pinmux.c:401
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
```
**Symbols:**

```
ffffffff8155b3fe-ffffffff8155b41c: pinmux_enable_setting.cold (STB_LOCAL)
ffffffff8155ad10-ffffffff8155af64: pinmux_enable_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int pinmux_enable_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinmux.c (0)
Location: drivers/pinctrl/pinmux.c:401
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
```
**Symbols:**

```
ffffffff8154b8be-ffffffff8154b8dc: pinmux_enable_setting.cold (STB_LOCAL)
ffffffff8154b1d0-ffffffff8154b424: pinmux_enable_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int pinmux_enable_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinmux.c (0)
Location: drivers/pinctrl/pinmux.c:401
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
```
**Symbols:**

```
ffffffff8155713e-ffffffff8155715c: pinmux_enable_setting.cold (STB_LOCAL)
ffffffff81556a50-ffffffff81556ca4: pinmux_enable_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int pinmux_enable_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinmux.c (0)
Location: drivers/pinctrl/pinmux.c:401
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
```
**Symbols:**

```
ffffffff81570fce-ffffffff81570fec: pinmux_enable_setting.cold (STB_LOCAL)
ffffffff815708e0-ffffffff81570b34: pinmux_enable_setting (STB_GLOBAL)
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
