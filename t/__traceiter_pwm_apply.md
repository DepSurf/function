# Function: <code>__traceiter_pwm_apply</code>

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
int __traceiter_pwm_apply(void *__data, struct pwm_device *pwm, const struct pwm_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff81641490)
Location: include/trace/events/pwm.h:39
Inline: False
```
**Symbols:**

```
ffffffff81641490-ffffffff816414d7: __traceiter_pwm_apply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_pwm_apply(void *__data, struct pwm_device *pwm, const struct pwm_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff816243d0)
Location: include/trace/events/pwm.h:39
Inline: False
```
**Symbols:**

```
ffffffff816243d0-ffffffff81624415: __traceiter_pwm_apply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_pwm_apply(void *__data, struct pwm_device *pwm, const struct pwm_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff81693c00)
Location: include/trace/events/pwm.h:39
Inline: False
```
**Symbols:**

```
ffffffff81693c00-ffffffff81693c45: __traceiter_pwm_apply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_pwm_apply(void *__data, struct pwm_device *pwm, const struct pwm_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff817b45b0)
Location: include/trace/events/pwm.h:39
Inline: False
```
**Symbols:**

```
ffffffff817b45b0-ffffffff817b45ff: __traceiter_pwm_apply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_pwm_apply(void *__data, struct pwm_device *pwm, const struct pwm_state *state, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff818ce8b0)
Location: include/trace/events/pwm.h:41
Inline: False
```
**Symbols:**

```
ffffffff818ce8b0-ffffffff818ce90b: __traceiter_pwm_apply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_pwm_apply(void *__data, struct pwm_device *pwm, const struct pwm_state *state, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff81911910)
Location: include/trace/events/pwm.h:41
Inline: False
```
**Symbols:**

```
ffffffff81911910-ffffffff8191196b: __traceiter_pwm_apply (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_pwm_apply(void *__data, struct pwm_device *pwm, const struct pwm_state *state, int err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff819597c0)
Location: include/trace/events/pwm.h:41
Inline: False
```
**Symbols:**

```
ffffffff819597c0-ffffffff8195981b: __traceiter_pwm_apply (STB_GLOBAL)
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
