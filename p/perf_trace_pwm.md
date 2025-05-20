# Function: <code>perf_trace_pwm</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void perf_trace_pwm(void *__data, struct pwm_device *pwm, const struct pwm_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff8161adf0)
Location: include/trace/events/pwm.h:11
Inline: False
```
**Symbols:**

```
ffffffff8161adf0-ffffffff8161aee5: perf_trace_pwm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void perf_trace_pwm(void *__data, struct pwm_device *pwm, const struct pwm_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff81641570)
Location: include/trace/events/pwm.h:11
Inline: False
```
**Symbols:**

```
ffffffff81641570-ffffffff81641667: perf_trace_pwm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void perf_trace_pwm(void *__data, struct pwm_device *pwm, const struct pwm_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff816244b0)
Location: include/trace/events/pwm.h:11
Inline: False
```
**Symbols:**

```
ffffffff816244b0-ffffffff816245a7: perf_trace_pwm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void perf_trace_pwm(void *__data, struct pwm_device *pwm, const struct pwm_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pwm/core.c (0)
Location: include/trace/events/pwm.h:11
Inline: False
```
**Symbols:**

```
ffffffff81693f90-ffffffff81694090: perf_trace_pwm (STB_LOCAL)
ffffffff81ce2bd6-ffffffff81ce2bf6: perf_trace_pwm.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void perf_trace_pwm(void *__data, struct pwm_device *pwm, const struct pwm_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pwm/core.c (0)
Location: include/trace/events/pwm.h:11
Inline: False
```
**Symbols:**

```
ffffffff817b4c50-ffffffff817b4d82: perf_trace_pwm (STB_LOCAL)
ffffffff81ea9714-ffffffff81ea9735: perf_trace_pwm.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void perf_trace_pwm(void *__data, struct pwm_device *pwm, const struct pwm_state *state, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pwm/core.c (0)
Location: include/trace/events/pwm.h:11
Inline: False
```
**Symbols:**

```
ffffffff818cef10-ffffffff818cf046: perf_trace_pwm (STB_LOCAL)
ffffffff8208ecbf-ffffffff8208ece0: perf_trace_pwm.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void perf_trace_pwm(void *__data, struct pwm_device *pwm, const struct pwm_state *state, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pwm/core.c (0)
Location: include/trace/events/pwm.h:11
Inline: False
```
**Symbols:**

```
ffffffff81911f50-ffffffff81912086: perf_trace_pwm (STB_LOCAL)
ffffffff8210efac-ffffffff8210efcd: perf_trace_pwm.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void perf_trace_pwm(void *__data, struct pwm_device *pwm, const struct pwm_state *state, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pwm/core.c (0)
Location: include/trace/events/pwm.h:11
Inline: False
```
**Symbols:**

```
ffffffff81959dc0-ffffffff81959ef6: perf_trace_pwm (STB_LOCAL)
ffffffff821ecc38-ffffffff821ecc59: perf_trace_pwm.cold (STB_LOCAL)
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
