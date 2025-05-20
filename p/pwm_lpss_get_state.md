# Function: <code>pwm_lpss_get_state</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void pwm_lpss_get_state(struct pwm_chip *chip, struct pwm_device *pwm, struct pwm_state *state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pwm/pwm-lpss.c (ffffffff81527dd0)
Location: drivers/pwm/pwm-lpss.c:165
Inline: True
```
**Symbols:**

```
ffffffff81527dd0-ffffffff81527e8c: pwm_lpss_get_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void pwm_lpss_get_state(struct pwm_chip *chip, struct pwm_device *pwm, struct pwm_state *state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pwm/pwm-lpss.c (ffffffff81557030)
Location: drivers/pwm/pwm-lpss.c:162
Inline: True
```
**Symbols:**

```
ffffffff81557030-ffffffff815570eb: pwm_lpss_get_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void pwm_lpss_get_state(struct pwm_chip *chip, struct pwm_device *pwm, struct pwm_state *state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pwm/pwm-lpss.c (ffffffff81578670)
Location: drivers/pwm/pwm-lpss.c:162
Inline: True
```
**Symbols:**

```
ffffffff81578670-ffffffff8157872b: pwm_lpss_get_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pwm_lpss_get_state(struct pwm_chip *chip, struct pwm_device *pwm, struct pwm_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/pwm-lpss.c (ffffffff8161d400)
Location: drivers/pwm/pwm-lpss.c:161
Inline: False
```
**Symbols:**

```
ffffffff8161d400-ffffffff8161d4d1: pwm_lpss_get_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pwm_lpss_get_state(struct pwm_chip *chip, struct pwm_device *pwm, struct pwm_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/pwm-lpss.c (ffffffff81643cd0)
Location: drivers/pwm/pwm-lpss.c:171
Inline: False
```
**Symbols:**

```
ffffffff81643cd0-ffffffff81643d9a: pwm_lpss_get_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pwm_lpss_get_state(struct pwm_chip *chip, struct pwm_device *pwm, struct pwm_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/pwm-lpss.c (ffffffff81626a90)
Location: drivers/pwm/pwm-lpss.c:171
Inline: False
```
**Symbols:**

```
ffffffff81626a90-ffffffff81626b5a: pwm_lpss_get_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void pwm_lpss_get_state(struct pwm_chip *chip, struct pwm_device *pwm, struct pwm_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pwm/pwm-lpss.c (0)
Location: drivers/pwm/pwm-lpss.c:171
Inline: False
```
**Symbols:**

```
ffffffff81696310-ffffffff816963e4: pwm_lpss_get_state (STB_LOCAL)
ffffffff81ce2f39-ffffffff81ce2f5a: pwm_lpss_get_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void pwm_lpss_get_state(struct pwm_chip *chip, struct pwm_device *pwm, struct pwm_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pwm/pwm-lpss.c (0)
Location: drivers/pwm/pwm-lpss.c:171
Inline: False
```
**Symbols:**

```
ffffffff817b7180-ffffffff817b7262: pwm_lpss_get_state (STB_LOCAL)
ffffffff81ea9a25-ffffffff81ea9a46: pwm_lpss_get_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int pwm_lpss_get_state(struct pwm_chip *chip, struct pwm_device *pwm, struct pwm_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pwm/pwm-lpss.c (0)
Location: drivers/pwm/pwm-lpss.c:208
Inline: False
```
**Symbols:**

```
ffffffff818d1850-ffffffff818d1932: pwm_lpss_get_state (STB_LOCAL)
ffffffff8208ee33-ffffffff8208ee54: pwm_lpss_get_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int pwm_lpss_get_state(struct pwm_chip *chip, struct pwm_device *pwm, struct pwm_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pwm/pwm-lpss.c (0)
Location: drivers/pwm/pwm-lpss.c:208
Inline: False
```
**Symbols:**

```
ffffffff81914840-ffffffff81914922: pwm_lpss_get_state (STB_LOCAL)
ffffffff8210f17b-ffffffff8210f19c: pwm_lpss_get_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int pwm_lpss_get_state(struct pwm_chip *chip, struct pwm_device *pwm, struct pwm_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pwm/pwm-lpss.c (0)
Location: drivers/pwm/pwm-lpss.c:208
Inline: False
```
**Symbols:**

```
ffffffff8195c7b0-ffffffff8195c892: pwm_lpss_get_state (STB_LOCAL)
ffffffff821ece23-ffffffff821ece44: pwm_lpss_get_state.cold (STB_LOCAL)
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
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void pwm_lpss_get_state(struct pwm_chip *chip, struct pwm_device *pwm, struct pwm_state *state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pwm/pwm-lpss.c (ffffffff8156c3c0)
Location: drivers/pwm/pwm-lpss.c:162
Inline: True
```
**Symbols:**

```
ffffffff8156c3c0-ffffffff8156c47b: pwm_lpss_get_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void pwm_lpss_get_state(struct pwm_chip *chip, struct pwm_device *pwm, struct pwm_state *state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pwm/pwm-lpss.c (ffffffff815868c0)
Location: drivers/pwm/pwm-lpss.c:162
Inline: True
```
**Symbols:**

```
ffffffff815868c0-ffffffff8158697b: pwm_lpss_get_state (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
