# Function: <code>pinconf_apply_setting</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pinconf_apply_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinconf.c (ffffffff814213f0)
Location: drivers/pinctrl/pinconf.c:151
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_select_state
```
**Symbols:**

```
ffffffff814213f0-ffffffff81421501: pinconf_apply_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pinconf_apply_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinconf.c (ffffffff81469b20)
Location: drivers/pinctrl/pinconf.c:151
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_select_state
```
**Symbols:**

```
ffffffff81469b20-ffffffff81469c31: pinconf_apply_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pinconf_apply_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinconf.c (ffffffff81488e00)
Location: drivers/pinctrl/pinconf.c:151
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_select_state
```
**Symbols:**

```
ffffffff81488e00-ffffffff81488f11: pinconf_apply_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pinconf_apply_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinconf.c (ffffffff81492690)
Location: drivers/pinctrl/pinconf.c:150
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_select_state
```
**Symbols:**

```
ffffffff81492690-ffffffff814927a1: pinconf_apply_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pinconf_apply_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinconf.c (ffffffff814ce920)
Location: drivers/pinctrl/pinconf.c:150
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
```
**Symbols:**

```
ffffffff814ce920-ffffffff814cea3b: pinconf_apply_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pinconf_apply_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinconf.c (ffffffff814ff900)
Location: drivers/pinctrl/pinconf.c:150
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
```
**Symbols:**

```
ffffffff814ff900-ffffffff814ffa1c: pinconf_apply_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pinconf_apply_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinconf.c (ffffffff81514370)
Location: drivers/pinctrl/pinconf.c:150
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
```
**Symbols:**

```
ffffffff81514370-ffffffff8151448c: pinconf_apply_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int pinconf_apply_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinconf.c (0)
Location: drivers/pinctrl/pinconf.c:148
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
```
**Symbols:**

```
ffffffff815427ce-ffffffff8154285d: pinconf_apply_setting.cold (STB_LOCAL)
ffffffff815424e0-ffffffff81542581: pinconf_apply_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int pinconf_apply_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinconf.c (0)
Location: drivers/pinctrl/pinconf.c:148
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
```
**Symbols:**

```
ffffffff8156365e-ffffffff815636ed: pinconf_apply_setting.cold (STB_LOCAL)
ffffffff81563370-ffffffff81563411: pinconf_apply_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int pinconf_apply_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinconf.c (0)
Location: drivers/pinctrl/pinconf.c:148
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
```
**Symbols:**

```
ffffffff81605c4e-ffffffff81605cdd: pinconf_apply_setting.cold (STB_LOCAL)
ffffffff81605960-ffffffff81605a01: pinconf_apply_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int pinconf_apply_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinconf.c (0)
Location: drivers/pinctrl/pinconf.c:148
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
```
**Symbols:**

```
ffffffff81bf54f1-ffffffff81bf5580: pinconf_apply_setting.cold (STB_LOCAL)
ffffffff8162a250-ffffffff8162a2f1: pinconf_apply_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int pinconf_apply_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinconf.c (0)
Location: drivers/pinctrl/pinconf.c:148
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
```
**Symbols:**

```
ffffffff81be7415-ffffffff81be74a4: pinconf_apply_setting.cold (STB_LOCAL)
ffffffff8160df30-ffffffff8160dfd1: pinconf_apply_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pinconf_apply_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinconf.c (0)
Location: drivers/pinctrl/pinconf.c:148
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
```
**Symbols:**

```
ffffffff81ce0a52-ffffffff81ce0ae1: pinconf_apply_setting.cold (STB_LOCAL)
ffffffff8167cca0-ffffffff8167cd41: pinconf_apply_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pinconf_apply_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinconf.c (0)
Location: drivers/pinctrl/pinconf.c:148
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
```
**Symbols:**

```
ffffffff81ea717c-ffffffff81ea71fb: pinconf_apply_setting.cold (STB_LOCAL)
ffffffff817985e0-ffffffff81798680: pinconf_apply_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pinconf_apply_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinconf.c (ffffffff818ae410)
Location: drivers/pinctrl/pinconf.c:148
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
```
**Symbols:**

```
ffffffff818ae410-ffffffff818ae51c: pinconf_apply_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pinconf_apply_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinconf.c (ffffffff818f1360)
Location: drivers/pinctrl/pinconf.c:148
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
```
**Symbols:**

```
ffffffff818f1360-ffffffff818f146c: pinconf_apply_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pinconf_apply_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinconf.c (ffffffff81938b10)
Location: drivers/pinctrl/pinconf.c:150
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
```
**Symbols:**

```
ffffffff81938b10-ffffffff81938c1c: pinconf_apply_setting (STB_GLOBAL)
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
int pinconf_apply_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinconf.c (ffff8000106905b8)
Location: drivers/pinctrl/pinconf.c:148
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
```
**Symbols:**

```
ffff8000106905b8-ffff8000106906d4: pinconf_apply_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pinconf_apply_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinconf.c (c0832284)
Location: drivers/pinctrl/pinconf.c:148
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
```
**Symbols:**

```
c0832284-c083239c: pinconf_apply_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pinconf_apply_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinconf.c (c00000000082c010)
Location: drivers/pinctrl/pinconf.c:148
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
```
**Symbols:**

```
c00000000082c010-c00000000082c1d4: pinconf_apply_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pinconf_apply_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinconf.c (ffffffe00049c088)
Location: drivers/pinctrl/pinconf.c:148
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
```
**Symbols:**

```
ffffffe00049c088-ffffffe00049c170: pinconf_apply_setting (STB_GLOBAL)
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
int pinconf_apply_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinconf.c (0)
Location: drivers/pinctrl/pinconf.c:148
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
```
**Symbols:**

```
ffffffff8155bc4e-ffffffff8155bcdd: pinconf_apply_setting.cold (STB_LOCAL)
ffffffff8155b960-ffffffff8155ba01: pinconf_apply_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int pinconf_apply_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinconf.c (0)
Location: drivers/pinctrl/pinconf.c:148
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
```
**Symbols:**

```
ffffffff8154c10e-ffffffff8154c19d: pinconf_apply_setting.cold (STB_LOCAL)
ffffffff8154be20-ffffffff8154bec1: pinconf_apply_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int pinconf_apply_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinconf.c (0)
Location: drivers/pinctrl/pinconf.c:148
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
```
**Symbols:**

```
ffffffff8155798e-ffffffff81557a1d: pinconf_apply_setting.cold (STB_LOCAL)
ffffffff815576a0-ffffffff81557741: pinconf_apply_setting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int pinconf_apply_setting(const struct pinctrl_setting *setting);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/pinconf.c (0)
Location: drivers/pinctrl/pinconf.c:148
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_commit_state
```
**Symbols:**

```
ffffffff8157181e-ffffffff815718ad: pinconf_apply_setting.cold (STB_LOCAL)
ffffffff81571530-ffffffff815715d1: pinconf_apply_setting (STB_GLOBAL)
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
