# Function: <code>crc_pwm_get_state</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void crc_pwm_get_state(struct pwm_chip *chip, struct pwm_device *pwm, struct pwm_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pwm/pwm-crc.c (0)
Location: drivers/pwm/pwm-crc.c:124
Inline: False
```
**Symbols:**

```
ffffffff81643950-ffffffff81643a2d: crc_pwm_get_state (STB_LOCAL)
ffffffff81bf6d11-ffffffff81bf6d3d: crc_pwm_get_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void crc_pwm_get_state(struct pwm_chip *chip, struct pwm_device *pwm, struct pwm_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pwm/pwm-crc.c (0)
Location: drivers/pwm/pwm-crc.c:124
Inline: False
```
**Symbols:**

```
ffffffff81626770-ffffffff8162684d: crc_pwm_get_state (STB_LOCAL)
ffffffff81be8b80-ffffffff81be8bac: crc_pwm_get_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void crc_pwm_get_state(struct pwm_chip *chip, struct pwm_device *pwm, struct pwm_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pwm/pwm-crc.c (0)
Location: drivers/pwm/pwm-crc.c:124
Inline: False
```
**Symbols:**

```
ffffffff81695fa0-ffffffff8169607d: crc_pwm_get_state (STB_LOCAL)
ffffffff81ce2da0-ffffffff81ce2dcc: crc_pwm_get_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void crc_pwm_get_state(struct pwm_chip *chip, struct pwm_device *pwm, struct pwm_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pwm/pwm-crc.c (0)
Location: drivers/pwm/pwm-crc.c:124
Inline: False
```
**Symbols:**

```
ffffffff817b6de0-ffffffff817b6ed3: crc_pwm_get_state (STB_LOCAL)
ffffffff81ea9891-ffffffff81ea98bd: crc_pwm_get_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int crc_pwm_get_state(struct pwm_chip *chip, struct pwm_device *pwm, struct pwm_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/pwm-crc.c (ffffffff818d13d0)
Location: drivers/pwm/pwm-crc.c:124
Inline: False
```
**Symbols:**

```
ffffffff818d13d0-ffffffff818d14f6: crc_pwm_get_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int crc_pwm_get_state(struct pwm_chip *chip, struct pwm_device *pwm, struct pwm_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/pwm-crc.c (ffffffff819143c0)
Location: drivers/pwm/pwm-crc.c:124
Inline: False
```
**Symbols:**

```
ffffffff819143c0-ffffffff819144e6: crc_pwm_get_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int crc_pwm_get_state(struct pwm_chip *chip, struct pwm_device *pwm, struct pwm_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/pwm-crc.c (ffffffff8195c330)
Location: drivers/pwm/pwm-crc.c:124
Inline: False
```
**Symbols:**

```
ffffffff8195c330-ffffffff8195c456: crc_pwm_get_state (STB_LOCAL)
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
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
