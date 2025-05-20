# Function: <code>trace_check_vprintf</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void trace_check_vprintf(struct trace_iterator *iter, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bfdf0)
Location: kernel/trace/trace.c:3720
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:trace_event_printf
```
**Symbols:**

```
ffffffff811bfdf0-ffffffff811c0299: trace_check_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void trace_check_vprintf(struct trace_iterator *iter, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:3780
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:trace_event_printf
```
**Symbols:**

```
ffffffff81cb53ad-ffffffff81cb53db: trace_check_vprintf.cold (STB_LOCAL)
ffffffff811ea790-ffffffff811eacae: trace_check_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void trace_check_vprintf(struct trace_iterator *iter, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:3783
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:trace_event_printf
```
**Symbols:**

```
ffffffff81e663ee-ffffffff81e66422: trace_check_vprintf.cold (STB_LOCAL)
ffffffff81222670-ffffffff81222c9c: trace_check_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void trace_check_vprintf(struct trace_iterator *iter, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:3807
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:trace_event_printf
```
**Symbols:**

```
ffffffff8205d671-ffffffff8205d6a5: trace_check_vprintf.cold (STB_LOCAL)
ffffffff8126d6d0-ffffffff8126dcf8: trace_check_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void trace_check_vprintf(struct trace_iterator *iter, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:3901
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:trace_event_printf
```
**Symbols:**

```
ffffffff820dbfb1-ffffffff820dbfdd: trace_check_vprintf.cold (STB_LOCAL)
ffffffff812848c0-ffffffff81284f1d: trace_check_vprintf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void trace_check_vprintf(struct trace_iterator *iter, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:3869
Inline: False
Direct callers:
  - kernel/trace/trace_output.c:trace_event_printf
```
**Symbols:**

```
ffffffff821b7e3f-ffffffff821b7e6b: trace_check_vprintf.cold (STB_LOCAL)
ffffffff8129f9c0-ffffffff812a001c: trace_check_vprintf (STB_GLOBAL)
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
