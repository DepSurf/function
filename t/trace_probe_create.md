# Function: <code>trace_probe_create</code>

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
int trace_probe_create(const char *raw_command, int (*createfn)(int, const char **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff811f3f10)
Location: kernel/trace/trace_probe.c:1138
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:kprobe_event_delete
  - kernel/trace/trace_kprobe.c:trace_kprobe_run_command
```
**Symbols:**

```
ffffffff811f3f10-ffffffff811f3f9a: trace_probe_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int trace_probe_create(const char *raw_command, int (*createfn)(int, const char **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff81225260)
Location: kernel/trace/trace_probe.c:1195
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_create
  - kernel/trace/trace_kprobe.c:kprobe_event_delete
  - kernel/trace/trace_kprobe.c:trace_kprobe_run_command
```
**Symbols:**

```
ffffffff81225260-ffffffff812252ea: trace_probe_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int trace_probe_create(const char *raw_command, int (*createfn)(int, const char **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff81265150)
Location: kernel/trace/trace_probe.c:1201
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_create
  - kernel/trace/trace_kprobe.c:kprobe_event_delete
  - kernel/trace/trace_kprobe.c:trace_kprobe_run_command
```
**Symbols:**

```
ffffffff81265150-ffffffff812651e5: trace_probe_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int trace_probe_create(const char *raw_command, int (*createfn)(int, const char **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff812b6d50)
Location: kernel/trace/trace_probe.c:1224
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_create
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:kprobe_event_delete
  - kernel/trace/trace_kprobe.c:trace_kprobe_run_command
```
**Symbols:**

```
ffffffff812b6d50-ffffffff812b6de5: trace_probe_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int trace_probe_create(const char *raw_command, int (*createfn)(int, const char **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff812da240)
Location: kernel/trace/trace_probe.c:1705
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_create
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:kprobe_event_delete
  - kernel/trace/trace_kprobe.c:trace_kprobe_run_command
  - kernel/trace/trace_fprobe.c:trace_fprobe_create
```
**Symbols:**

```
ffffffff812da240-ffffffff812da2d5: trace_probe_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int trace_probe_create(const char *raw_command, int (*createfn)(int, const char **));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_probe.c (ffffffff812f81d0)
Location: kernel/trace/trace_probe.c:1942
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_create
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_kprobe.c:kprobe_event_delete
  - kernel/trace/trace_kprobe.c:trace_kprobe_run_command
  - kernel/trace/trace_fprobe.c:trace_fprobe_create
```
**Symbols:**

```
ffffffff812f81d0-ffffffff812f8265: trace_probe_create (STB_GLOBAL)
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
