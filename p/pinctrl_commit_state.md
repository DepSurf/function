# Function: <code>pinctrl_commit_state</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pinctrl_commit_state(struct pinctrl *p, struct pinctrl_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff814ca800)
Location: drivers/pinctrl/core.c:1196
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_pm_select_state
  - drivers/pinctrl/core.c:pinctrl_init_done
  - drivers/pinctrl/core.c:pinctrl_force_default
  - drivers/pinctrl/core.c:pinctrl_force_sleep
```
**Symbols:**

```
ffffffff814ca800-ffffffff814ca92c: pinctrl_commit_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pinctrl_commit_state(struct pinctrl *p, struct pinctrl_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff814fb760)
Location: drivers/pinctrl/core.c:1196
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_pm_select_state
  - drivers/pinctrl/core.c:pinctrl_init_done
  - drivers/pinctrl/core.c:pinctrl_force_default
  - drivers/pinctrl/core.c:pinctrl_force_sleep
```
**Symbols:**

```
ffffffff814fb760-ffffffff814fb88e: pinctrl_commit_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pinctrl_commit_state(struct pinctrl *p, struct pinctrl_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81510230)
Location: drivers/pinctrl/core.c:1224
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_pm_select_state
  - drivers/pinctrl/core.c:pinctrl_init_done
  - drivers/pinctrl/core.c:pinctrl_force_default
  - drivers/pinctrl/core.c:pinctrl_force_sleep
```
**Symbols:**

```
ffffffff81510230-ffffffff8151035e: pinctrl_commit_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int pinctrl_commit_state(struct pinctrl *p, struct pinctrl_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/core.c:1209
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/pinctrl/core.c:pinctrl_pm_select_state
  - drivers/pinctrl/core.c:pinctrl_init_done
  - drivers/pinctrl/core.c:pinctrl_force_default
  - drivers/pinctrl/core.c:pinctrl_force_sleep
```
**Symbols:**

```
ffffffff8153e920-ffffffff8153ea13: pinctrl_commit_state (STB_LOCAL)
ffffffff815408c8-ffffffff81540932: pinctrl_commit_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int pinctrl_commit_state(struct pinctrl *p, struct pinctrl_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/core.c:1237
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/pinctrl/core.c:pinctrl_pm_select_state
  - drivers/pinctrl/core.c:pinctrl_init_done
  - drivers/pinctrl/core.c:pinctrl_force_default
  - drivers/pinctrl/core.c:pinctrl_force_sleep
```
**Symbols:**

```
ffffffff8155f7c0-ffffffff8155f8b3: pinctrl_commit_state (STB_LOCAL)
ffffffff81561782-ffffffff815617ec: pinctrl_commit_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int pinctrl_commit_state(struct pinctrl *p, struct pinctrl_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/core.c:1238
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_claim_hogs
  - drivers/pinctrl/core.c:pinctrl_pm_select_idle_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_sleep_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_default_state
  - drivers/pinctrl/core.c:pinctrl_init_done
  - drivers/pinctrl/core.c:pinctrl_force_default
  - drivers/pinctrl/core.c:pinctrl_force_sleep
```
**Symbols:**

```
ffffffff81601af0-ffffffff81601be3: pinctrl_commit_state (STB_LOCAL)
ffffffff81603c25-ffffffff81603c8f: pinctrl_commit_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int pinctrl_commit_state(struct pinctrl *p, struct pinctrl_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/core.c:1239
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_claim_hogs
  - drivers/pinctrl/core.c:pinctrl_pm_select_idle_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_sleep_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_default_state
  - drivers/pinctrl/core.c:pinctrl_init_done
  - drivers/pinctrl/core.c:pinctrl_force_default
  - drivers/pinctrl/core.c:pinctrl_force_sleep
```
**Symbols:**

```
ffffffff81626950-ffffffff81626a43: pinctrl_commit_state (STB_LOCAL)
ffffffff81bf4e4b-ffffffff81bf4eb5: pinctrl_commit_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int pinctrl_commit_state(struct pinctrl *p, struct pinctrl_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/core.c:1239
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_claim_hogs
  - drivers/pinctrl/core.c:pinctrl_pm_select_idle_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_sleep_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_default_state
  - drivers/pinctrl/core.c:pinctrl_init_done
  - drivers/pinctrl/core.c:pinctrl_force_default
  - drivers/pinctrl/core.c:pinctrl_force_sleep
```
**Symbols:**

```
ffffffff8160b1d0-ffffffff8160b32a: pinctrl_commit_state (STB_LOCAL)
ffffffff81be6e6a-ffffffff81be6edc: pinctrl_commit_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pinctrl_commit_state(struct pinctrl *p, struct pinctrl_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/core.c:1239
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_claim_hogs
  - drivers/pinctrl/core.c:pinctrl_pm_select_idle_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_sleep_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_default_state
  - drivers/pinctrl/core.c:pinctrl_init_done
  - drivers/pinctrl/core.c:pinctrl_force_default
  - drivers/pinctrl/core.c:pinctrl_force_sleep
```
**Symbols:**

```
ffffffff8167a1d0-ffffffff8167a34c: pinctrl_commit_state (STB_LOCAL)
ffffffff81ce0326-ffffffff81ce03ee: pinctrl_commit_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pinctrl_commit_state(struct pinctrl *p, struct pinctrl_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/core.c:1239
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_claim_hogs
  - drivers/pinctrl/core.c:pinctrl_pm_select_idle_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_sleep_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_default_state
  - drivers/pinctrl/core.c:pinctrl_init_done
  - drivers/pinctrl/core.c:pinctrl_force_default
  - drivers/pinctrl/core.c:pinctrl_force_sleep
```
**Symbols:**

```
ffffffff81795750-ffffffff817958d4: pinctrl_commit_state (STB_LOCAL)
ffffffff81ea6a75-ffffffff81ea6b35: pinctrl_commit_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int pinctrl_commit_state(struct pinctrl *p, struct pinctrl_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/core.c:1239
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_claim_hogs
  - drivers/pinctrl/core.c:pinctrl_pm_select_idle_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_sleep_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_default_state
  - drivers/pinctrl/core.c:pinctrl_init_done
  - drivers/pinctrl/core.c:pinctrl_force_default
  - drivers/pinctrl/core.c:pinctrl_force_sleep
  - drivers/pinctrl/core.c:pinctrl_commit_state
```
**Symbols:**

```
ffffffff818aafc0-ffffffff818ab1bf: pinctrl_commit_state (STB_LOCAL)
ffffffff8208deb8-ffffffff8208def2: pinctrl_commit_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int pinctrl_commit_state(struct pinctrl *p, struct pinctrl_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/core.c:1243
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_claim_hogs
  - drivers/pinctrl/core.c:pinctrl_pm_select_idle_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_sleep_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_default_state
  - drivers/pinctrl/core.c:pinctrl_init_done
  - drivers/pinctrl/core.c:pinctrl_force_default
  - drivers/pinctrl/core.c:pinctrl_force_sleep
  - drivers/pinctrl/core.c:pinctrl_commit_state
```
**Symbols:**

```
ffffffff818edeb0-ffffffff818ee0ba: pinctrl_commit_state (STB_LOCAL)
ffffffff8210e1b8-ffffffff8210e1f2: pinctrl_commit_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int pinctrl_commit_state(struct pinctrl *p, struct pinctrl_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/core.c:1257
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_claim_hogs
  - drivers/pinctrl/core.c:pinctrl_pm_select_idle_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_sleep_state
  - drivers/pinctrl/core.c:pinctrl_pm_select_default_state
  - drivers/pinctrl/core.c:pinctrl_init_done
  - drivers/pinctrl/core.c:pinctrl_force_default
  - drivers/pinctrl/core.c:pinctrl_force_sleep
  - drivers/pinctrl/core.c:pinctrl_commit_state
```
**Symbols:**

```
ffffffff81935680-ffffffff8193587f: pinctrl_commit_state (STB_LOCAL)
ffffffff821ebdf5-ffffffff821ebe2f: pinctrl_commit_state.cold (STB_LOCAL)
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
int pinctrl_commit_state(struct pinctrl *p, struct pinctrl_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffff80001068bd20)
Location: drivers/pinctrl/core.c:1237
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/pinctrl/core.c:pinctrl_pm_select_state
  - drivers/pinctrl/core.c:pinctrl_init_done
  - drivers/pinctrl/core.c:pinctrl_force_default
  - drivers/pinctrl/core.c:pinctrl_force_sleep
```
**Symbols:**

```
ffff80001068bd20-ffff80001068be84: pinctrl_commit_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pinctrl_commit_state(struct pinctrl *p, struct pinctrl_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (c082dff4)
Location: drivers/pinctrl/core.c:1237
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/pinctrl/core.c:pinctrl_pm_select_state
  - drivers/pinctrl/core.c:pinctrl_init_done
  - drivers/pinctrl/core.c:pinctrl_force_default
  - drivers/pinctrl/core.c:pinctrl_force_sleep
```
**Symbols:**

```
c082dff4-c082e15c: pinctrl_commit_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pinctrl_commit_state(struct pinctrl *p, struct pinctrl_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (c000000000824960)
Location: drivers/pinctrl/core.c:1237
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/pinctrl/core.c:pinctrl_pm_select_state
  - drivers/pinctrl/core.c:pinctrl_init_done
  - drivers/pinctrl/core.c:pinctrl_force_default
  - drivers/pinctrl/core.c:pinctrl_force_sleep
```
**Symbols:**

```
c000000000824960-c000000000824b4c: pinctrl_commit_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pinctrl_commit_state(struct pinctrl *p, struct pinctrl_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffe00049815c)
Location: drivers/pinctrl/core.c:1237
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/pinctrl/core.c:pinctrl_pm_select_state
  - drivers/pinctrl/core.c:pinctrl_init_done
  - drivers/pinctrl/core.c:pinctrl_force_default
  - drivers/pinctrl/core.c:pinctrl_force_sleep
```
**Symbols:**

```
ffffffe00049815c-ffffffe00049828a: pinctrl_commit_state (STB_LOCAL)
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
int pinctrl_commit_state(struct pinctrl *p, struct pinctrl_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/core.c:1237
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/pinctrl/core.c:pinctrl_pm_select_state
  - drivers/pinctrl/core.c:pinctrl_init_done
  - drivers/pinctrl/core.c:pinctrl_force_default
  - drivers/pinctrl/core.c:pinctrl_force_sleep
```
**Symbols:**

```
ffffffff81557db0-ffffffff81557ea3: pinctrl_commit_state (STB_LOCAL)
ffffffff81559d72-ffffffff81559ddc: pinctrl_commit_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int pinctrl_commit_state(struct pinctrl *p, struct pinctrl_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/core.c:1237
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/pinctrl/core.c:pinctrl_pm_select_state
  - drivers/pinctrl/core.c:pinctrl_init_done
  - drivers/pinctrl/core.c:pinctrl_force_default
  - drivers/pinctrl/core.c:pinctrl_force_sleep
```
**Symbols:**

```
ffffffff81548270-ffffffff81548363: pinctrl_commit_state (STB_LOCAL)
ffffffff8154a232-ffffffff8154a29c: pinctrl_commit_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int pinctrl_commit_state(struct pinctrl *p, struct pinctrl_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/core.c:1237
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/pinctrl/core.c:pinctrl_pm_select_state
  - drivers/pinctrl/core.c:pinctrl_init_done
  - drivers/pinctrl/core.c:pinctrl_force_default
  - drivers/pinctrl/core.c:pinctrl_force_sleep
```
**Symbols:**

```
ffffffff81553af0-ffffffff81553be3: pinctrl_commit_state (STB_LOCAL)
ffffffff81555ab2-ffffffff81555b1c: pinctrl_commit_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int pinctrl_commit_state(struct pinctrl *p, struct pinctrl_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pinctrl/core.c (0)
Location: drivers/pinctrl/core.c:1237
Inline: False
Direct callers:
  - drivers/pinctrl/core.c:pinctrl_enable
  - drivers/pinctrl/core.c:pinctrl_pm_select_state
  - drivers/pinctrl/core.c:pinctrl_init_done
  - drivers/pinctrl/core.c:pinctrl_force_default
  - drivers/pinctrl/core.c:pinctrl_force_sleep
```
**Symbols:**

```
ffffffff8156d980-ffffffff8156da73: pinctrl_commit_state (STB_LOCAL)
ffffffff8156f942-ffffffff8156f9ac: pinctrl_commit_state.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
