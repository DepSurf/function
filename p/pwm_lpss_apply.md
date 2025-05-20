# Function: <code>pwm_lpss_apply</code>

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
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int pwm_lpss_apply(struct pwm_chip *chip, struct pwm_device *pwm, struct pwm_state *state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pwm/pwm-lpss.c (ffffffff815126a0)
Location: drivers/pwm/pwm-lpss.c:132
Inline: True
```
**Symbols:**

```
ffffffff815126a0-ffffffff81512898: pwm_lpss_apply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int pwm_lpss_apply(struct pwm_chip *chip, struct pwm_device *pwm, struct pwm_state *state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pwm/pwm-lpss.c (ffffffff81527f20)
Location: drivers/pwm/pwm-lpss.c:127
Inline: True
```
**Symbols:**

```
ffffffff81527f20-ffffffff815280c8: pwm_lpss_apply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int pwm_lpss_apply(struct pwm_chip *chip, struct pwm_device *pwm, struct pwm_state *state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pwm/pwm-lpss.c (ffffffff81557160)
Location: drivers/pwm/pwm-lpss.c:124
Inline: True
```
**Symbols:**

```
ffffffff81557160-ffffffff81557308: pwm_lpss_apply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int pwm_lpss_apply(struct pwm_chip *chip, struct pwm_device *pwm, const struct pwm_state *state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pwm/pwm-lpss.c (ffffffff815787a0)
Location: drivers/pwm/pwm-lpss.c:124
Inline: True
```
**Symbols:**

```
ffffffff815787a0-ffffffff81578948: pwm_lpss_apply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pwm_lpss_apply(struct pwm_chip *chip, struct pwm_device *pwm, const struct pwm_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/pwm-lpss.c (ffffffff8161d7b0)
Location: drivers/pwm/pwm-lpss.c:124
Inline: False
```
**Symbols:**

```
ffffffff8161d7b0-ffffffff8161d95b: pwm_lpss_apply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pwm_lpss_apply(struct pwm_chip *chip, struct pwm_device *pwm, const struct pwm_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/pwm-lpss.c (ffffffff81644120)
Location: drivers/pwm/pwm-lpss.c:148
Inline: False
```
**Symbols:**

```
ffffffff81644120-ffffffff816441dd: pwm_lpss_apply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pwm_lpss_apply(struct pwm_chip *chip, struct pwm_device *pwm, const struct pwm_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/pwm-lpss.c (ffffffff81626e80)
Location: drivers/pwm/pwm-lpss.c:148
Inline: False
```
**Symbols:**

```
ffffffff81626e80-ffffffff81626f3d: pwm_lpss_apply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pwm_lpss_apply(struct pwm_chip *chip, struct pwm_device *pwm, const struct pwm_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pwm/pwm-lpss.c (0)
Location: drivers/pwm/pwm-lpss.c:148
Inline: False
```
**Symbols:**

```
ffffffff81696740-ffffffff8169681e: pwm_lpss_apply (STB_LOCAL)
ffffffff81ce3001-ffffffff81ce304e: pwm_lpss_apply.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pwm_lpss_apply(struct pwm_chip *chip, struct pwm_device *pwm, const struct pwm_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pwm/pwm-lpss.c (0)
Location: drivers/pwm/pwm-lpss.c:148
Inline: False
```
**Symbols:**

```
ffffffff817b75f0-ffffffff817b76f8: pwm_lpss_apply (STB_LOCAL)
ffffffff81ea9aec-ffffffff81ea9b3b: pwm_lpss_apply.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int pwm_lpss_apply(struct pwm_chip *chip, struct pwm_device *pwm, const struct pwm_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pwm/pwm-lpss.c (0)
Location: drivers/pwm/pwm-lpss.c:185
Inline: False
```
**Symbols:**

```
ffffffff818d1d00-ffffffff818d1e08: pwm_lpss_apply (STB_LOCAL)
ffffffff8208eea8-ffffffff8208eef7: pwm_lpss_apply.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int pwm_lpss_apply(struct pwm_chip *chip, struct pwm_device *pwm, const struct pwm_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pwm/pwm-lpss.c (0)
Location: drivers/pwm/pwm-lpss.c:185
Inline: False
```
**Symbols:**

```
ffffffff81914d00-ffffffff81914e08: pwm_lpss_apply (STB_LOCAL)
ffffffff8210f1f0-ffffffff8210f23f: pwm_lpss_apply.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int pwm_lpss_apply(struct pwm_chip *chip, struct pwm_device *pwm, const struct pwm_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pwm/pwm-lpss.c (0)
Location: drivers/pwm/pwm-lpss.c:185
Inline: False
```
**Symbols:**

```
ffffffff8195cc70-ffffffff8195cd78: pwm_lpss_apply (STB_LOCAL)
ffffffff821ece98-ffffffff821ecee7: pwm_lpss_apply.cold (STB_LOCAL)
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
int pwm_lpss_apply(struct pwm_chip *chip, struct pwm_device *pwm, const struct pwm_state *state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pwm/pwm-lpss.c (ffffffff8156c4f0)
Location: drivers/pwm/pwm-lpss.c:124
Inline: True
```
**Symbols:**

```
ffffffff8156c4f0-ffffffff8156c698: pwm_lpss_apply (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int pwm_lpss_apply(struct pwm_chip *chip, struct pwm_device *pwm, const struct pwm_state *state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pwm/pwm-lpss.c (ffffffff815869f0)
Location: drivers/pwm/pwm-lpss.c:124
Inline: True
```
**Symbols:**

```
ffffffff815869f0-ffffffff81586b98: pwm_lpss_apply (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
