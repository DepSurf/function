# Function: <code>trace_is_tracepoint_string</code>

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
bool trace_is_tracepoint_string(const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_printk.c (ffffffff811c6fe0)
Location: kernel/trace/trace_printk.c:254
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_check_vprintf
```
**Symbols:**

```
ffffffff811c6fe0-ffffffff811c700b: trace_is_tracepoint_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool trace_is_tracepoint_string(const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_printk.c (ffffffff811f2680)
Location: kernel/trace/trace_printk.c:254
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_check_vprintf
```
**Symbols:**

```
ffffffff811f2680-ffffffff811f26ab: trace_is_tracepoint_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool trace_is_tracepoint_string(const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_printk.c (ffffffff8122b1f0)
Location: kernel/trace/trace_printk.c:254
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_check_vprintf
```
**Symbols:**

```
ffffffff8122b1f0-ffffffff8122b227: trace_is_tracepoint_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool trace_is_tracepoint_string(const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_printk.c (ffffffff81276b90)
Location: kernel/trace/trace_printk.c:254
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_check_vprintf
```
**Symbols:**

```
ffffffff81276b90-ffffffff81276bc7: trace_is_tracepoint_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool trace_is_tracepoint_string(const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_printk.c (ffffffff8128e580)
Location: kernel/trace/trace_printk.c:254
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_check_vprintf
```
**Symbols:**

```
ffffffff8128e580-ffffffff8128e5b7: trace_is_tracepoint_string (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool trace_is_tracepoint_string(const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_printk.c (ffffffff812a9a00)
Location: kernel/trace/trace_printk.c:254
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_check_vprintf
```
**Symbols:**

```
ffffffff812a9a00-ffffffff812a9a37: trace_is_tracepoint_string (STB_GLOBAL)
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
