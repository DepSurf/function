# Function: <code>tracing_record_taskinfo_sched_switch</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
void tracing_record_taskinfo_sched_switch(struct task_struct *prev, struct task_struct *next, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81165e40)
Location: kernel/trace/trace.c:2067
Inline: False
Direct callers:
  - kernel/trace/trace_sched_switch.c:probe_sched_switch
```
**Symbols:**

```
ffffffff81165e40-ffffffff81165f35: tracing_record_taskinfo_sched_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tracing_record_taskinfo_sched_switch(struct task_struct *prev, struct task_struct *next, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81172dd0)
Location: kernel/trace/trace.c:2070
Inline: False
Direct callers:
  - kernel/trace/trace_sched_switch.c:probe_sched_switch
```
**Symbols:**

```
ffffffff81172dd0-ffffffff81172ec5: tracing_record_taskinfo_sched_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tracing_record_taskinfo_sched_switch(struct task_struct *prev, struct task_struct *next, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81181db0)
Location: kernel/trace/trace.c:2082
Inline: False
Direct callers:
  - kernel/trace/trace_sched_switch.c:probe_sched_switch
```
**Symbols:**

```
ffffffff81181db0-ffffffff81181ea9: tracing_record_taskinfo_sched_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tracing_record_taskinfo_sched_switch(struct task_struct *prev, struct task_struct *next, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8118f770)
Location: kernel/trace/trace.c:2083
Inline: False
Direct callers:
  - kernel/trace/trace_sched_switch.c:probe_sched_switch
```
**Symbols:**

```
ffffffff8118f770-ffffffff8118f869: tracing_record_taskinfo_sched_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tracing_record_taskinfo_sched_switch(struct task_struct *prev, struct task_struct *next, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119d1a0)
Location: kernel/trace/trace.c:2266
Inline: False
Direct callers:
  - kernel/trace/trace_sched_switch.c:probe_sched_switch
```
**Symbols:**

```
ffffffff8119d1a0-ffffffff8119d29f: tracing_record_taskinfo_sched_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tracing_record_taskinfo_sched_switch(struct task_struct *prev, struct task_struct *next, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a8b50)
Location: kernel/trace/trace.c:2292
Inline: False
Direct callers:
  - kernel/trace/trace_sched_switch.c:probe_sched_switch
```
**Symbols:**

```
ffffffff811a8b50-ffffffff811a8c4f: tracing_record_taskinfo_sched_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tracing_record_taskinfo_sched_switch(struct task_struct *prev, struct task_struct *next, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811c0cd0)
Location: kernel/trace/trace.c:2396
Inline: False
Direct callers:
  - kernel/trace/trace_sched_switch.c:probe_sched_switch
```
**Symbols:**

```
ffffffff811c0cd0-ffffffff811c0e4c: tracing_record_taskinfo_sched_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tracing_record_taskinfo_sched_switch(struct task_struct *prev, struct task_struct *next, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811be900)
Location: kernel/trace/trace.c:2540
Inline: False
Direct callers:
  - kernel/trace/trace_sched_switch.c:probe_sched_switch
```
**Symbols:**

```
ffffffff811be900-ffffffff811bea7c: tracing_record_taskinfo_sched_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tracing_record_taskinfo_sched_switch(struct task_struct *prev, struct task_struct *next, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811be290)
Location: kernel/trace/trace.c:2551
Inline: False
Direct callers:
  - kernel/trace/trace_sched_switch.c:probe_sched_switch
```
**Symbols:**

```
ffffffff811be290-ffffffff811be38f: tracing_record_taskinfo_sched_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tracing_record_taskinfo_sched_switch(struct task_struct *prev, struct task_struct *next, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811e8af0)
Location: kernel/trace/trace.c:2565
Inline: False
Direct callers:
  - kernel/trace/trace_sched_switch.c:probe_sched_switch
```
**Symbols:**

```
ffffffff811e8af0-ffffffff811e8bef: tracing_record_taskinfo_sched_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tracing_record_taskinfo_sched_switch(struct task_struct *prev, struct task_struct *next, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81220760)
Location: kernel/trace/trace.c:2556
Inline: False
Direct callers:
  - kernel/trace/trace_sched_switch.c:probe_sched_wakeup
  - kernel/trace/trace_sched_switch.c:probe_sched_switch
```
**Symbols:**

```
ffffffff81220760-ffffffff81220892: tracing_record_taskinfo_sched_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tracing_record_taskinfo_sched_switch(struct task_struct *prev, struct task_struct *next, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8126b590)
Location: kernel/trace/trace.c:2580
Inline: False
Direct callers:
  - kernel/trace/trace_sched_switch.c:probe_sched_wakeup
  - kernel/trace/trace_sched_switch.c:probe_sched_switch
```
**Symbols:**

```
ffffffff8126b590-ffffffff8126b6c2: tracing_record_taskinfo_sched_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tracing_record_taskinfo_sched_switch(struct task_struct *prev, struct task_struct *next, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81282700)
Location: kernel/trace/trace.c:2651
Inline: False
Direct callers:
  - kernel/trace/trace_sched_switch.c:probe_sched_wakeup
  - kernel/trace/trace_sched_switch.c:probe_sched_switch
```
**Symbols:**

```
ffffffff81282700-ffffffff81282832: tracing_record_taskinfo_sched_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tracing_record_taskinfo_sched_switch(struct task_struct *prev, struct task_struct *next, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8129d7f0)
Location: kernel/trace/trace.c:2646
Inline: False
Direct callers:
  - kernel/trace/trace_sched_switch.c:probe_sched_wakeup
  - kernel/trace/trace_sched_switch.c:probe_sched_switch
```
**Symbols:**

```
ffffffff8129d7f0-ffffffff8129d922: tracing_record_taskinfo_sched_switch (STB_GLOBAL)
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
void tracing_record_taskinfo_sched_switch(struct task_struct *prev, struct task_struct *next, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffff800010225820)
Location: kernel/trace/trace.c:2292
Inline: False
Direct callers:
  - kernel/trace/trace_sched_switch.c:probe_sched_switch
```
**Symbols:**

```
ffff800010225820-ffff800010225920: tracing_record_taskinfo_sched_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tracing_record_taskinfo_sched_switch(struct task_struct *prev, struct task_struct *next, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0462c28)
Location: kernel/trace/trace.c:2292
Inline: False
Direct callers:
  - kernel/trace/trace_sched_switch.c:probe_sched_switch
```
**Symbols:**

```
c0462c28-c0462d44: tracing_record_taskinfo_sched_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tracing_record_taskinfo_sched_switch(struct task_struct *prev, struct task_struct *next, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0000000002aae90)
Location: kernel/trace/trace.c:2292
Inline: False
Direct callers:
  - kernel/trace/trace_sched_switch.c:probe_sched_switch
  - kernel/trace/trace_sched_switch.c:probe_sched_switch
```
**Symbols:**

```
c0000000002aae90-c0000000002ab004: tracing_record_taskinfo_sched_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tracing_record_taskinfo_sched_switch(struct task_struct *prev, struct task_struct *next, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffe00018068e)
Location: kernel/trace/trace.c:2292
Inline: False
Direct callers:
  - kernel/trace/trace_sched_switch.c:probe_sched_switch
```
**Symbols:**

```
ffffffe00018068e-ffffffe00018076c: tracing_record_taskinfo_sched_switch (STB_GLOBAL)
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
void tracing_record_taskinfo_sched_switch(struct task_struct *prev, struct task_struct *next, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a1170)
Location: kernel/trace/trace.c:2292
Inline: False
Direct callers:
  - kernel/trace/trace_sched_switch.c:probe_sched_switch
```
**Symbols:**

```
ffffffff811a1170-ffffffff811a126f: tracing_record_taskinfo_sched_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tracing_record_taskinfo_sched_switch(struct task_struct *prev, struct task_struct *next, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81194140)
Location: kernel/trace/trace.c:2292
Inline: False
Direct callers:
  - kernel/trace/trace_sched_switch.c:probe_sched_switch
```
**Symbols:**

```
ffffffff81194140-ffffffff8119423f: tracing_record_taskinfo_sched_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tracing_record_taskinfo_sched_switch(struct task_struct *prev, struct task_struct *next, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119ef40)
Location: kernel/trace/trace.c:2292
Inline: False
Direct callers:
  - kernel/trace/trace_sched_switch.c:probe_sched_switch
```
**Symbols:**

```
ffffffff8119ef40-ffffffff8119f03f: tracing_record_taskinfo_sched_switch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tracing_record_taskinfo_sched_switch(struct task_struct *prev, struct task_struct *next, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811acc40)
Location: kernel/trace/trace.c:2292
Inline: False
Direct callers:
  - kernel/trace/trace_sched_switch.c:probe_sched_switch
```
**Symbols:**

```
ffffffff811acc40-ffffffff811acd3f: tracing_record_taskinfo_sched_switch (STB_GLOBAL)
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
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
