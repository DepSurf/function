# Function: <code>trace_event_raw_event_pwm</code>

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
void trace_event_raw_event_pwm(void *__data, struct pwm_device *pwm, const struct pwm_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff8161aef0)
Location: include/trace/events/pwm.h:11
Inline: False
```
**Symbols:**

```
ffffffff8161aef0-ffffffff8161afb6: trace_event_raw_event_pwm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void trace_event_raw_event_pwm(void *__data, struct pwm_device *pwm, const struct pwm_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff81641670)
Location: include/trace/events/pwm.h:11
Inline: False
```
**Symbols:**

```
ffffffff81641670-ffffffff81641738: trace_event_raw_event_pwm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void trace_event_raw_event_pwm(void *__data, struct pwm_device *pwm, const struct pwm_state *state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff816245b0)
Location: include/trace/events/pwm.h:11
Inline: False
```
**Symbols:**

```
ffffffff816245b0-ffffffff8162467a: trace_event_raw_event_pwm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void trace_event_raw_event_pwm(void *__data, struct pwm_device *pwm, const struct pwm_state *state);
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
ffffffff81694090-ffffffff81694166: trace_event_raw_event_pwm (STB_LOCAL)
ffffffff81ce2bf6-ffffffff81ce2c12: trace_event_raw_event_pwm.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void trace_event_raw_event_pwm(void *__data, struct pwm_device *pwm, const struct pwm_state *state);
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
ffffffff817b4d90-ffffffff817b4e61: trace_event_raw_event_pwm (STB_LOCAL)
ffffffff81ea9735-ffffffff81ea9751: trace_event_raw_event_pwm.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void trace_event_raw_event_pwm(void *__data, struct pwm_device *pwm, const struct pwm_state *state, int err);
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
ffffffff818cf060-ffffffff818cf13b: trace_event_raw_event_pwm (STB_LOCAL)
ffffffff8208ece0-ffffffff8208ecfc: trace_event_raw_event_pwm.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void trace_event_raw_event_pwm(void *__data, struct pwm_device *pwm, const struct pwm_state *state, int err);
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
ffffffff819120a0-ffffffff8191217b: trace_event_raw_event_pwm (STB_LOCAL)
ffffffff8210efcd-ffffffff8210efe9: trace_event_raw_event_pwm.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void trace_event_raw_event_pwm(void *__data, struct pwm_device *pwm, const struct pwm_state *state, int err);
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
ffffffff81959f10-ffffffff81959feb: trace_event_raw_event_pwm (STB_LOCAL)
ffffffff821ecc59-ffffffff821ecc75: trace_event_raw_event_pwm.cold (STB_LOCAL)
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
