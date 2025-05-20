# Function: <code>cache_mod</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811591fc)
Location: kernel/trace/ftrace.c:3951
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_mod_callback
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81165cfc)
Location: kernel/trace/ftrace.c:3919
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_mod_callback
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811749ee)
Location: kernel/trace/ftrace.c:3907
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_mod_callback
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8118262e)
Location: kernel/trace/ftrace.c:3866
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_mod_callback
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8118f3c0)
Location: kernel/trace/ftrace.c:3902
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_mod_callback
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8119b380)
Location: kernel/trace/ftrace.c:3926
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_mod_callback
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cache_mod(struct trace_array *tr, const char *func, char *module, int enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811ade50)
Location: kernel/trace/ftrace.c:4053
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_mod_callback
```
**Symbols:**

```
ffffffff811ade50-ffffffff811ae091: cache_mod (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cache_mod(struct trace_array *tr, const char *func, char *module, int enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811ab760)
Location: kernel/trace/ftrace.c:4131
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_mod_callback
```
**Symbols:**

```
ffffffff811ab760-ffffffff811ab9a1: cache_mod (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cache_mod(struct trace_array *tr, const char *func, char *module, int enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811ac1f0)
Location: kernel/trace/ftrace.c:4131
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_mod_callback
```
**Symbols:**

```
ffffffff811ac1f0-ffffffff811ac434: cache_mod (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cache_mod(struct trace_array *tr, const char *func, char *module, int enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811d5e80)
Location: kernel/trace/ftrace.c:4132
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_mod_callback
```
**Symbols:**

```
ffffffff811d5e80-ffffffff811d60c4: cache_mod (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cache_mod(struct trace_array *tr, const char *func, char *module, int enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8120b1f0)
Location: kernel/trace/ftrace.c:4272
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_mod_callback
```
**Symbols:**

```
ffffffff8120b1f0-ffffffff8120b446: cache_mod (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cache_mod(struct trace_array *tr, const char *func, char *module, int enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81253b70)
Location: kernel/trace/ftrace.c:4293
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_mod_callback
```
**Symbols:**

```
ffffffff81253b70-ffffffff81253dcd: cache_mod (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cache_mod(struct trace_array *tr, const char *func, char *module, int enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8126aec0)
Location: kernel/trace/ftrace.c:4448
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_mod_callback
```
**Symbols:**

```
ffffffff8126aec0-ffffffff8126b11d: cache_mod (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cache_mod(struct trace_array *tr, const char *func, char *module, int enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff812851d0)
Location: kernel/trace/ftrace.c:4414
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_mod_callback
```
**Symbols:**

```
ffffffff812851d0-ffffffff8128545c: cache_mod (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffff800010214198)
Location: kernel/trace/ftrace.c:3926
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_mod_callback
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c0452f40)
Location: kernel/trace/ftrace.c:3926
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_mod_callback
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c000000000294d5c)
Location: kernel/trace/ftrace.c:3926
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_mod_callback
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffe0001741d2)
Location: kernel/trace/ftrace.c:3926
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_mod_callback
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811939a0)
Location: kernel/trace/ftrace.c:3926
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_mod_callback
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81186ab0)
Location: kernel/trace/ftrace.c:3926
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_mod_callback
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81191770)
Location: kernel/trace/ftrace.c:3926
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_mod_callback
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8119f300)
Location: kernel/trace/ftrace.c:3926
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_mod_callback
```
</details>
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
