# Function: <code>__traceiter_pwm_get</code>

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
<summary>In <code>5.11</code>: ✅</summary>

```c
int __traceiter_pwm_get(void *__data, struct pwm_device *pwm, const struct pwm_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff816414e0)
Location: include/trace/events/pwm.h:47
Inline: False
```
**Symbols:**

```
ffffffff816414e0-ffffffff81641527: __traceiter_pwm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_pwm_get(void *__data, struct pwm_device *pwm, const struct pwm_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff81624420)
Location: include/trace/events/pwm.h:47
Inline: False
```
**Symbols:**

```
ffffffff81624420-ffffffff81624465: __traceiter_pwm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_pwm_get(void *__data, struct pwm_device *pwm, const struct pwm_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff81693c50)
Location: include/trace/events/pwm.h:47
Inline: False
```
**Symbols:**

```
ffffffff81693c50-ffffffff81693c95: __traceiter_pwm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_pwm_get(void *__data, struct pwm_device *pwm, const struct pwm_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff817b4600)
Location: include/trace/events/pwm.h:47
Inline: False
```
**Symbols:**

```
ffffffff817b4600-ffffffff817b464f: __traceiter_pwm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_pwm_get(void *__data, struct pwm_device *pwm, const struct pwm_state *state, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff818ce920)
Location: include/trace/events/pwm.h:48
Inline: False
```
**Symbols:**

```
ffffffff818ce920-ffffffff818ce97b: __traceiter_pwm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_pwm_get(void *__data, struct pwm_device *pwm, const struct pwm_state *state, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff819119a0)
Location: include/trace/events/pwm.h:48
Inline: False
```
**Symbols:**

```
ffffffff819119a0-ffffffff819119fb: __traceiter_pwm_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_pwm_get(void *__data, struct pwm_device *pwm, const struct pwm_state *state, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff81959850)
Location: include/trace/events/pwm.h:48
Inline: False
```
**Symbols:**

```
ffffffff81959850-ffffffff819598ab: __traceiter_pwm_get (STB_GLOBAL)
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
<b>Param added. </b>
<code>int err</code>
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
