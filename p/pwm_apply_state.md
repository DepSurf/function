# Function: <code>pwm_apply_state</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int pwm_apply_state(struct pwm_device *pwm, struct pwm_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff81477c40)
Location: drivers/pwm/core.c:456
Inline: True
Direct callers:
  - drivers/pwm/core.c:pwm_adjust_config
  - drivers/pwm/core.c:pwm_adjust_config
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/pwm/sysfs.c:enable_store
  - drivers/pwm/sysfs.c:duty_cycle_store
  - drivers/pwm/sysfs.c:period_store
```
**Symbols:**

```
ffffffff81477c40-ffffffff81477dc3: pwm_apply_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int pwm_apply_state(struct pwm_device *pwm, struct pwm_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff81498fa0)
Location: drivers/pwm/core.c:458
Inline: True
Direct callers:
  - drivers/pwm/core.c:pwm_adjust_config
  - drivers/pwm/core.c:pwm_adjust_config
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/pwm/sysfs.c:enable_store
  - drivers/pwm/sysfs.c:duty_cycle_store
  - drivers/pwm/sysfs.c:period_store
```
**Symbols:**

```
ffffffff81498fa0-ffffffff81499123: pwm_apply_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int pwm_apply_state(struct pwm_device *pwm, struct pwm_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff814a2720)
Location: drivers/pwm/core.c:467
Inline: True
Direct callers:
  - drivers/pwm/core.c:pwm_adjust_config
  - drivers/pwm/core.c:pwm_adjust_config
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/pwm/sysfs.c:enable_store
  - drivers/pwm/sysfs.c:duty_cycle_store
  - drivers/pwm/sysfs.c:period_store
```
**Symbols:**

```
ffffffff814a2720-ffffffff814a2878: pwm_apply_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int pwm_apply_state(struct pwm_device *pwm, struct pwm_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff814e1470)
Location: drivers/pwm/core.c:467
Inline: True
Direct callers:
  - drivers/pwm/core.c:pwm_adjust_config
  - drivers/pwm/core.c:pwm_adjust_config
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/pwm/sysfs.c:enable_store
  - drivers/pwm/sysfs.c:duty_cycle_store
  - drivers/pwm/sysfs.c:period_store
```
**Symbols:**

```
ffffffff814e1470-ffffffff814e15ec: pwm_apply_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int pwm_apply_state(struct pwm_device *pwm, struct pwm_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff81510d70)
Location: drivers/pwm/core.c:467
Inline: True
Direct callers:
  - drivers/pwm/core.c:pwm_adjust_config
  - drivers/pwm/core.c:pwm_adjust_config
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/pwm/sysfs.c:enable_store
  - drivers/pwm/sysfs.c:duty_cycle_store
  - drivers/pwm/sysfs.c:period_store
```
**Symbols:**

```
ffffffff81510d70-ffffffff81510eee: pwm_apply_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int pwm_apply_state(struct pwm_device *pwm, struct pwm_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff81526420)
Location: drivers/pwm/core.c:467
Inline: True
Direct callers:
  - drivers/pwm/core.c:pwm_adjust_config
  - drivers/pwm/core.c:pwm_adjust_config
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/pwm/sysfs.c:enable_store
  - drivers/pwm/sysfs.c:duty_cycle_store
  - drivers/pwm/sysfs.c:period_store
```
**Symbols:**

```
ffffffff81526420-ffffffff8152659e: pwm_apply_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pwm_apply_state(struct pwm_device *pwm, struct pwm_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff81554cc0)
Location: drivers/pwm/core.c:455
Inline: False
Direct callers:
  - drivers/pwm/core.c:pwm_adjust_config
  - drivers/pwm/core.c:pwm_adjust_config
  - drivers/pwm/sysfs.c:pwm_class_suspend
  - drivers/pwm/sysfs.c:pwm_class_resume_npwm
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/pwm/sysfs.c:enable_store
  - drivers/pwm/sysfs.c:duty_cycle_store
  - drivers/pwm/sysfs.c:period_store
```
**Symbols:**

```
ffffffff81554cc0-ffffffff81554e88: pwm_apply_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pwm_apply_state(struct pwm_device *pwm, const struct pwm_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff81576300)
Location: drivers/pwm/core.c:453
Inline: False
Direct callers:
  - drivers/pwm/core.c:pwm_adjust_config
  - drivers/pwm/core.c:pwm_adjust_config
  - drivers/pwm/sysfs.c:pwm_class_suspend
  - drivers/pwm/sysfs.c:pwm_class_resume_npwm
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/pwm/sysfs.c:enable_store
  - drivers/pwm/sysfs.c:duty_cycle_store
  - drivers/pwm/sysfs.c:period_store
```
**Symbols:**

```
ffffffff81576300-ffffffff815764cd: pwm_apply_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pwm_apply_state(struct pwm_device *pwm, const struct pwm_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff8161b690)
Location: drivers/pwm/core.c:573
Inline: False
Direct callers:
  - drivers/pwm/core.c:pwm_adjust_config
  - drivers/pwm/core.c:pwm_adjust_config
  - drivers/pwm/sysfs.c:pwm_class_suspend
  - drivers/pwm/sysfs.c:pwm_class_resume_npwm
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/pwm/sysfs.c:enable_store
  - drivers/pwm/sysfs.c:duty_cycle_store
  - drivers/pwm/sysfs.c:period_store
```
**Symbols:**

```
ffffffff8161b690-ffffffff8161b8da: pwm_apply_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pwm_apply_state(struct pwm_device *pwm, const struct pwm_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff81642310)
Location: drivers/pwm/core.c:573
Inline: False
Direct callers:
  - drivers/pwm/core.c:pwm_adjust_config
  - drivers/pwm/core.c:pwm_adjust_config
  - drivers/pwm/sysfs.c:pwm_class_suspend
  - drivers/pwm/sysfs.c:pwm_class_resume_npwm
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/pwm/sysfs.c:enable_store
  - drivers/pwm/sysfs.c:duty_cycle_store
  - drivers/pwm/sysfs.c:period_store
```
**Symbols:**

```
ffffffff81642310-ffffffff81642533: pwm_apply_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pwm_apply_state(struct pwm_device *pwm, const struct pwm_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff81624ce0)
Location: drivers/pwm/core.c:543
Inline: False
Direct callers:
  - drivers/pwm/core.c:pwm_adjust_config
  - drivers/pwm/core.c:pwm_adjust_config
  - drivers/pwm/sysfs.c:pwm_class_suspend
  - drivers/pwm/sysfs.c:pwm_class_resume_npwm
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/pwm/sysfs.c:enable_store
  - drivers/pwm/sysfs.c:duty_cycle_store
  - drivers/pwm/sysfs.c:period_store
```
**Symbols:**

```
ffffffff81624ce0-ffffffff81624ef5: pwm_apply_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pwm_apply_state(struct pwm_device *pwm, const struct pwm_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pwm/core.c (0)
Location: drivers/pwm/core.c:530
Inline: False
Direct callers:
  - drivers/pwm/core.c:pwm_adjust_config
  - drivers/pwm/core.c:pwm_adjust_config
  - drivers/pwm/sysfs.c:pwm_class_suspend
  - drivers/pwm/sysfs.c:pwm_class_resume_npwm
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/pwm/sysfs.c:enable_store
  - drivers/pwm/sysfs.c:duty_cycle_store
  - drivers/pwm/sysfs.c:period_store
```
**Symbols:**

```
ffffffff81ce2c8b-ffffffff81ce2cf8: pwm_apply_state.cold (STB_LOCAL)
ffffffff816944a0-ffffffff8169470b: pwm_apply_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pwm_apply_state(struct pwm_device *pwm, const struct pwm_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff817b5560)
Location: drivers/pwm/core.c:623
Inline: False
Direct callers:
  - drivers/pwm/core.c:pwm_adjust_config
  - drivers/pwm/core.c:pwm_adjust_config
  - drivers/pwm/sysfs.c:pwm_class_suspend
  - drivers/pwm/sysfs.c:pwm_class_resume_npwm
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/pwm/sysfs.c:enable_store
  - drivers/pwm/sysfs.c:duty_cycle_store
  - drivers/pwm/sysfs.c:period_store
```
**Symbols:**

```
ffffffff817b5560-ffffffff817b5679: pwm_apply_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pwm_apply_state(struct pwm_device *pwm, const struct pwm_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff818cf8c0)
Location: drivers/pwm/core.c:556
Inline: False
Direct callers:
  - drivers/pwm/core.c:pwm_adjust_config
  - drivers/pwm/core.c:pwm_adjust_config
  - drivers/pwm/sysfs.c:pwm_class_suspend
  - drivers/pwm/sysfs.c:pwm_class_resume_npwm
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/pwm/sysfs.c:enable_store
  - drivers/pwm/sysfs.c:duty_cycle_store
  - drivers/pwm/sysfs.c:period_store
```
**Symbols:**

```
ffffffff818cf8c0-ffffffff818cf9e2: pwm_apply_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pwm_apply_state(struct pwm_device *pwm, const struct pwm_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff81912900)
Location: drivers/pwm/core.c:499
Inline: False
Direct callers:
  - drivers/pwm/core.c:pwm_adjust_config
  - drivers/pwm/core.c:pwm_adjust_config
  - drivers/pwm/sysfs.c:pwm_class_suspend
  - drivers/pwm/sysfs.c:pwm_class_resume_npwm
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/pwm/sysfs.c:enable_store
  - drivers/pwm/sysfs.c:duty_cycle_store
  - drivers/pwm/sysfs.c:period_store
```
**Symbols:**

```
ffffffff81912900-ffffffff81912a22: pwm_apply_state (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int pwm_apply_state(struct pwm_device *pwm, const struct pwm_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffff8000106d7598)
Location: drivers/pwm/core.c:453
Inline: False
Direct callers:
  - drivers/pwm/core.c:pwm_adjust_config
  - drivers/pwm/core.c:pwm_adjust_config
  - drivers/pwm/sysfs.c:pwm_class_suspend
  - drivers/pwm/sysfs.c:pwm_class_resume_npwm
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/pwm/sysfs.c:enable_store
  - drivers/pwm/sysfs.c:duty_cycle_store
  - drivers/pwm/sysfs.c:period_store
```
**Symbols:**

```
ffff8000106d7598-ffff8000106d7790: pwm_apply_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pwm_apply_state(struct pwm_device *pwm, const struct pwm_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (c087452c)
Location: drivers/pwm/core.c:453
Inline: False
Direct callers:
  - drivers/pwm/core.c:pwm_adjust_config
  - drivers/pwm/core.c:pwm_adjust_config
  - drivers/pwm/sysfs.c:pwm_class_suspend
  - drivers/pwm/sysfs.c:pwm_class_resume_npwm
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/pwm/sysfs.c:enable_store
  - drivers/pwm/sysfs.c:duty_cycle_store
  - drivers/pwm/sysfs.c:period_store
```
**Symbols:**

```
c087452c-c0874738: pwm_apply_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pwm_apply_state(struct pwm_device *pwm, const struct pwm_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (c00000000084e330)
Location: drivers/pwm/core.c:453
Inline: False
Direct callers:
  - drivers/pwm/core.c:pwm_adjust_config
  - drivers/pwm/core.c:pwm_adjust_config
  - drivers/pwm/sysfs.c:pwm_class_suspend
  - drivers/pwm/sysfs.c:pwm_class_resume_npwm
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/pwm/sysfs.c:enable_store
  - drivers/pwm/sysfs.c:duty_cycle_store
  - drivers/pwm/sysfs.c:period_store
```
**Symbols:**

```
c00000000084e330-c00000000084e61c: pwm_apply_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pwm_apply_state(struct pwm_device *pwm, const struct pwm_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffe0004b0e34)
Location: drivers/pwm/core.c:453
Inline: False
Direct callers:
  - drivers/pwm/core.c:pwm_adjust_config
  - drivers/pwm/core.c:pwm_adjust_config
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/pwm/sysfs.c:enable_store
  - drivers/pwm/sysfs.c:duty_cycle_store
  - drivers/pwm/sysfs.c:period_store
```
**Symbols:**

```
ffffffe0004b0e34-ffffffe0004b0f8c: pwm_apply_state (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int pwm_apply_state(struct pwm_device *pwm, const struct pwm_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff8156b110)
Location: drivers/pwm/core.c:453
Inline: False
Direct callers:
  - drivers/pwm/core.c:pwm_adjust_config
  - drivers/pwm/core.c:pwm_adjust_config
  - drivers/pwm/sysfs.c:pwm_class_suspend
  - drivers/pwm/sysfs.c:pwm_class_resume_npwm
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/pwm/sysfs.c:enable_store
  - drivers/pwm/sysfs.c:duty_cycle_store
  - drivers/pwm/sysfs.c:period_store
```
**Symbols:**

```
ffffffff8156b110-ffffffff8156b2dd: pwm_apply_state (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pwm_apply_state(struct pwm_device *pwm, const struct pwm_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff8156a050)
Location: drivers/pwm/core.c:453
Inline: False
Direct callers:
  - drivers/pwm/core.c:pwm_adjust_config
  - drivers/pwm/core.c:pwm_adjust_config
  - drivers/pwm/sysfs.c:pwm_class_suspend
  - drivers/pwm/sysfs.c:pwm_class_resume_npwm
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/pwm/sysfs.c:enable_store
  - drivers/pwm/sysfs.c:duty_cycle_store
  - drivers/pwm/sysfs.c:period_store
```
**Symbols:**

```
ffffffff8156a050-ffffffff8156a21d: pwm_apply_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pwm_apply_state(struct pwm_device *pwm, const struct pwm_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff81584550)
Location: drivers/pwm/core.c:453
Inline: False
Direct callers:
  - drivers/pwm/core.c:pwm_adjust_config
  - drivers/pwm/core.c:pwm_adjust_config
  - drivers/pwm/sysfs.c:pwm_class_suspend
  - drivers/pwm/sysfs.c:pwm_class_resume_npwm
  - drivers/pwm/sysfs.c:polarity_store
  - drivers/pwm/sysfs.c:enable_store
  - drivers/pwm/sysfs.c:duty_cycle_store
  - drivers/pwm/sysfs.c:period_store
```
**Symbols:**

```
ffffffff81584550-ffffffff8158471d: pwm_apply_state (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct pwm_state *state</code> ➡️ <code>const struct pwm_state *state</code>
</li>
</ul>
</details>
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
