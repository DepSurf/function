# Function: <code>__traceiter_suspend_resume</code>

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
int __traceiter_suspend_resume(void *__data, const char *action, int val, bool start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/power-traces.c (ffffffff811ecc80)
Location: include/trace/events/power.h:226
Inline: False
```
**Symbols:**

```
ffffffff811ecc80-ffffffff811ecccd: __traceiter_suspend_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_suspend_resume(void *__data, const char *action, int val, bool start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/power-traces.c (ffffffff811edc10)
Location: include/trace/events/power.h:226
Inline: False
```
**Symbols:**

```
ffffffff811edc10-ffffffff811edc5b: __traceiter_suspend_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_suspend_resume(void *__data, const char *action, int val, bool start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/power-traces.c (ffffffff8121ec80)
Location: include/trace/events/power.h:226
Inline: False
```
**Symbols:**

```
ffffffff8121ec80-ffffffff8121eccb: __traceiter_suspend_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_suspend_resume(void *__data, const char *action, int val, bool start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/power-traces.c (ffffffff8125e3b0)
Location: include/trace/events/power.h:226
Inline: False
```
**Symbols:**

```
ffffffff8125e3b0-ffffffff8125e407: __traceiter_suspend_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_suspend_resume(void *__data, const char *action, int val, bool start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/power-traces.c (ffffffff812aefb0)
Location: include/trace/events/power.h:248
Inline: False
```
**Symbols:**

```
ffffffff812aefb0-ffffffff812af007: __traceiter_suspend_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_suspend_resume(void *__data, const char *action, int val, bool start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/power-traces.c (ffffffff812d15d0)
Location: include/trace/events/power.h:248
Inline: False
```
**Symbols:**

```
ffffffff812d15d0-ffffffff812d1627: __traceiter_suspend_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_suspend_resume(void *__data, const char *action, int val, bool start);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/power-traces.c (ffffffff812ef0d0)
Location: include/trace/events/power.h:248
Inline: False
```
**Symbols:**

```
ffffffff812ef0d0-ffffffff812ef127: __traceiter_suspend_resume (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
