# Function: <code>chv_config_set_oden</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int chv_config_set_oden(struct chv_pinctrl *pctrl, unsigned int pin, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8148d3b0)
Location: drivers/pinctrl/intel/pinctrl-cherryview.c:1127
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
```
**Symbols:**

```
ffffffff8148d3b0-ffffffff8148d425: chv_config_set_oden (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int chv_config_set_oden(struct chv_pinctrl *pctrl, unsigned int pin, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81496cc0)
Location: drivers/pinctrl/intel/pinctrl-cherryview.c:1133
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
```
**Symbols:**

```
ffffffff81496cc0-ffffffff81496d35: chv_config_set_oden (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int chv_config_set_oden(struct chv_pinctrl *pctrl, unsigned int pin, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff814d2fe0)
Location: drivers/pinctrl/intel/pinctrl-cherryview.c:1126
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
```
**Symbols:**

```
ffffffff814d2fe0-ffffffff814d3055: chv_config_set_oden (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int chv_config_set_oden(struct chv_pinctrl *pctrl, unsigned int pin, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81504090)
Location: drivers/pinctrl/intel/pinctrl-cherryview.c:1126
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
```
**Symbols:**

```
ffffffff81504090-ffffffff81504105: chv_config_set_oden (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int chv_config_set_oden(struct chv_pinctrl *pctrl, unsigned int pin, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81518bb0)
Location: drivers/pinctrl/intel/pinctrl-cherryview.c:1112
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
```
**Symbols:**

```
ffffffff81518bb0-ffffffff81518c25: chv_config_set_oden (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int chv_config_set_oden(struct chv_pinctrl *pctrl, unsigned int pin, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81546d30)
Location: drivers/pinctrl/intel/pinctrl-cherryview.c:1112
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
```
**Symbols:**

```
ffffffff81546d30-ffffffff81546dae: chv_config_set_oden (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int chv_config_set_oden(struct chv_pinctrl *pctrl, unsigned int pin, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81567c50)
Location: drivers/pinctrl/intel/pinctrl-cherryview.c:1114
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
```
**Symbols:**

```
ffffffff81567c50-ffffffff81567cce: chv_config_set_oden (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8160b470)
Location: drivers/pinctrl/intel/pinctrl-cherryview.c:1048
Inline: True
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
```
**Symbols:**

```
ffffffff8160b470-ffffffff8160b4e6: chv_config_set_oden.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int chv_config_set_oden(struct intel_pinctrl *pctrl, unsigned int pin, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8162ec00)
Location: drivers/pinctrl/intel/pinctrl-cherryview.c:1037
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
```
**Symbols:**

```
ffffffff8162ec00-ffffffff8162ec91: chv_config_set_oden (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int chv_config_set_oden(struct intel_pinctrl *pctrl, unsigned int pin, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff816128a0)
Location: drivers/pinctrl/intel/pinctrl-cherryview.c:1037
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
```
**Symbols:**

```
ffffffff816128a0-ffffffff81612931: chv_config_set_oden (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int chv_config_set_oden(struct intel_pinctrl *pctrl, unsigned int pin, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff816819d0)
Location: drivers/pinctrl/intel/pinctrl-cherryview.c:1037
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
```
**Symbols:**

```
ffffffff816819d0-ffffffff81681a61: chv_config_set_oden (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int chv_config_set_oden(struct intel_pinctrl *pctrl, unsigned int pin, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8179da40)
Location: drivers/pinctrl/intel/pinctrl-cherryview.c:1039
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
```
**Symbols:**

```
ffffffff8179da40-ffffffff8179dae0: chv_config_set_oden (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int chv_config_set_oden(struct intel_pinctrl *pctrl, unsigned int pin, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff818b4680)
Location: drivers/pinctrl/intel/pinctrl-cherryview.c:1041
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
```
**Symbols:**

```
ffffffff818b4680-ffffffff818b4720: chv_config_set_oden (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int chv_config_set_oden(struct intel_pinctrl *pctrl, unsigned int pin, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff818f7700)
Location: drivers/pinctrl/intel/pinctrl-cherryview.c:1046
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
```
**Symbols:**

```
ffffffff818f7700-ffffffff818f77a0: chv_config_set_oden (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int chv_config_set_oden(struct intel_pinctrl *pctrl, unsigned int pin, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8193f6a0)
Location: drivers/pinctrl/intel/pinctrl-cherryview.c:978
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
```
**Symbols:**

```
ffffffff8193f6a0-ffffffff8193f74f: chv_config_set_oden (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int chv_config_set_oden(struct chv_pinctrl *pctrl, unsigned int pin, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8154e260)
Location: drivers/pinctrl/intel/pinctrl-cherryview.c:1114
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
```
**Symbols:**

```
ffffffff8154e260-ffffffff8154e2de: chv_config_set_oden (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int chv_config_set_oden(struct chv_pinctrl *pctrl, unsigned int pin, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff8155bf80)
Location: drivers/pinctrl/intel/pinctrl-cherryview.c:1114
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
```
**Symbols:**

```
ffffffff8155bf80-ffffffff8155bffe: chv_config_set_oden (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int chv_config_set_oden(struct chv_pinctrl *pctrl, unsigned int pin, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/intel/pinctrl-cherryview.c (ffffffff81575e10)
Location: drivers/pinctrl/intel/pinctrl-cherryview.c:1114
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_config_set
```
**Symbols:**

```
ffffffff81575e10-ffffffff81575e8e: chv_config_set_oden (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Flavor</b>
<ul>
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
