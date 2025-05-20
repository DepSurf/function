# Function: <code>__traceiter_compact_retry</code>

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
int __traceiter_compact_retry(void *__data, int order, enum compact_priority priority, enum compact_result result, int retries, int max_retries, bool ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff8125f5e0)
Location: include/trace/events/oom.h:155
Inline: False
```
**Symbols:**

```
ffffffff8125f5e0-ffffffff8125f659: __traceiter_compact_retry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_compact_retry(void *__data, int order, enum compact_priority priority, enum compact_result result, int retries, int max_retries, bool ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81264130)
Location: include/trace/events/oom.h:155
Inline: False
```
**Symbols:**

```
ffffffff81264130-ffffffff812641a5: __traceiter_compact_retry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_compact_retry(void *__data, int order, enum compact_priority priority, enum compact_result result, int retries, int max_retries, bool ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff812a0950)
Location: include/trace/events/oom.h:155
Inline: False
```
**Symbols:**

```
ffffffff812a0950-ffffffff812a09c5: __traceiter_compact_retry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_compact_retry(void *__data, int order, enum compact_priority priority, enum compact_result result, int retries, int max_retries, bool ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff812f7fe0)
Location: include/trace/events/oom.h:155
Inline: False
```
**Symbols:**

```
ffffffff812f7fe0-ffffffff812f8069: __traceiter_compact_retry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_compact_retry(void *__data, int order, enum compact_priority priority, enum compact_result result, int retries, int max_retries, bool ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81361a20)
Location: include/trace/events/oom.h:155
Inline: False
```
**Symbols:**

```
ffffffff81361a20-ffffffff81361aa9: __traceiter_compact_retry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_compact_retry(void *__data, int order, enum compact_priority priority, enum compact_result result, int retries, int max_retries, bool ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81393e40)
Location: include/trace/events/oom.h:155
Inline: False
```
**Symbols:**

```
ffffffff81393e40-ffffffff81393ec9: __traceiter_compact_retry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_compact_retry(void *__data, int order, enum compact_priority priority, enum compact_result result, int retries, int max_retries, bool ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff813bdc00)
Location: include/trace/events/oom.h:155
Inline: False
```
**Symbols:**

```
ffffffff813bdc00-ffffffff813bdc89: __traceiter_compact_retry (STB_GLOBAL)
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
