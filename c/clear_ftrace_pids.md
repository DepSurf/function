# Function: <code>clear_ftrace_pids</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8114df0f)
Location: kernel/trace/ftrace.c:5341
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_pid_open
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81157e4c)
Location: kernel/trace/ftrace.c:5390
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_pid_open
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void clear_ftrace_pids(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811550e0)
Location: kernel/trace/ftrace.c:6161
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_clear_pids
```
**Symbols:**

```
ffffffff811550e0-ffffffff8115516e: clear_ftrace_pids (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void clear_ftrace_pids(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81161980)
Location: kernel/trace/ftrace.c:6460
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_clear_pids
```
**Symbols:**

```
ffffffff81161980-ffffffff81161a01: clear_ftrace_pids (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void clear_ftrace_pids(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81170840)
Location: kernel/trace/ftrace.c:6446
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_clear_pids
```
**Symbols:**

```
ffffffff81170840-ffffffff811708c1: clear_ftrace_pids (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void clear_ftrace_pids(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8117e2e0)
Location: kernel/trace/ftrace.c:6385
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_clear_pids
```
**Symbols:**

```
ffffffff8117e2e0-ffffffff8117e361: clear_ftrace_pids (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void clear_ftrace_pids(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8118b380)
Location: kernel/trace/ftrace.c:6439
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_clear_pids
```
**Symbols:**

```
ffffffff8118b380-ffffffff8118b3fa: clear_ftrace_pids (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void clear_ftrace_pids(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811972b0)
Location: kernel/trace/ftrace.c:6472
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_clear_pids
```
**Symbols:**

```
ffffffff811972b0-ffffffff8119732a: clear_ftrace_pids (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void clear_ftrace_pids(struct trace_array *tr, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811ac830)
Location: kernel/trace/ftrace.c:6980
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_no_pid_open
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_clear_pids
```
**Symbols:**

```
ffffffff811ac830-ffffffff811ac980: clear_ftrace_pids (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void clear_ftrace_pids(struct trace_array *tr, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811aa140)
Location: kernel/trace/ftrace.c:7150
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_no_pid_open
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_clear_pids
```
**Symbols:**

```
ffffffff811aa140-ffffffff811aa290: clear_ftrace_pids (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void clear_ftrace_pids(struct trace_array *tr, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811aad00)
Location: kernel/trace/ftrace.c:7155
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_no_pid_open
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_clear_pids
```
**Symbols:**

```
ffffffff811aad00-ffffffff811aae67: clear_ftrace_pids (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void clear_ftrace_pids(struct trace_array *tr, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811d49a0)
Location: kernel/trace/ftrace.c:7156
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_no_pid_open
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_clear_pids
```
**Symbols:**

```
ffffffff811d49a0-ffffffff811d4b45: clear_ftrace_pids (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void clear_ftrace_pids(struct trace_array *tr, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81209a40)
Location: kernel/trace/ftrace.c:7596
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_no_pid_open
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_clear_pids
```
**Symbols:**

```
ffffffff81209a40-ffffffff81209c0e: clear_ftrace_pids (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void clear_ftrace_pids(struct trace_array *tr, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81252b20)
Location: kernel/trace/ftrace.c:7710
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_no_pid_open
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_clear_pids
```
**Symbols:**

```
ffffffff81252b20-ffffffff81252d0a: clear_ftrace_pids (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void clear_ftrace_pids(struct trace_array *tr, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8126a080)
Location: kernel/trace/ftrace.c:7525
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_no_pid_open
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_clear_pids
```
**Symbols:**

```
ffffffff8126a080-ffffffff8126a26e: clear_ftrace_pids (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void clear_ftrace_pids(struct trace_array *tr, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff812841f0)
Location: kernel/trace/ftrace.c:7525
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_no_pid_open
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_clear_pids
```
**Symbols:**

```
ffffffff812841f0-ffffffff812843de: clear_ftrace_pids (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void clear_ftrace_pids(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffff80001020f6d8)
Location: kernel/trace/ftrace.c:6472
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_clear_pids
```
**Symbols:**

```
ffff80001020f6d8-ffff80001020f778: clear_ftrace_pids (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void clear_ftrace_pids(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c044eb98)
Location: kernel/trace/ftrace.c:6472
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_clear_pids
```
**Symbols:**

```
c044eb98-c044ec28: clear_ftrace_pids (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void clear_ftrace_pids(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c00000000028e630)
Location: kernel/trace/ftrace.c:6472
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_clear_pids
```
**Symbols:**

```
c00000000028e630-c00000000028e718: clear_ftrace_pids (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void clear_ftrace_pids(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffe00017042c)
Location: kernel/trace/ftrace.c:6472
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_clear_pids
```
**Symbols:**

```
ffffffe00017042c-ffffffe0001704d8: clear_ftrace_pids (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void clear_ftrace_pids(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8118f8d0)
Location: kernel/trace/ftrace.c:6472
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_clear_pids
```
**Symbols:**

```
ffffffff8118f8d0-ffffffff8118f94a: clear_ftrace_pids (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void clear_ftrace_pids(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81182a10)
Location: kernel/trace/ftrace.c:6472
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_clear_pids
```
**Symbols:**

```
ffffffff81182a10-ffffffff81182a8a: clear_ftrace_pids (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void clear_ftrace_pids(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8118d6a0)
Location: kernel/trace/ftrace.c:6472
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_clear_pids
```
**Symbols:**

```
ffffffff8118d6a0-ffffffff8118d71a: clear_ftrace_pids (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void clear_ftrace_pids(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8119b230)
Location: kernel/trace/ftrace.c:6472
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_pid_open
  - kernel/trace/ftrace.c:ftrace_clear_pids
```
**Symbols:**

```
ffffffff8119b230-ffffffff8119b2aa: clear_ftrace_pids (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int type</code>
</li>
</ul>
</details>
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
