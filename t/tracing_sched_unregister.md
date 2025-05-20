# Function: <code>tracing_sched_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_sched_switch.c (ffffffff81156739)
Location: kernel/trace/trace_sched_switch.c:71
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_sched_switch.c (ffffffff81160fa9)
Location: kernel/trace/trace_sched_switch.c:71
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
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
In kernel/trace/trace_sched_switch.c (ffffffff8116ba09)
Location: kernel/trace/trace_sched_switch.c:71
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tracing_sched_unregister();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_sched_switch.c (ffffffff8116eaa0)
Location: kernel/trace/trace_sched_switch.c:82
Inline: False
Direct callers:
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
```
**Symbols:**

```
ffffffff8116eaa0-ffffffff8116eae5: tracing_sched_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tracing_sched_unregister();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_sched_switch.c (ffffffff8117bb90)
Location: kernel/trace/trace_sched_switch.c:83
Inline: False
Direct callers:
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
```
**Symbols:**

```
ffffffff8117bb90-ffffffff8117bbd5: tracing_sched_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tracing_sched_unregister();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_sched_switch.c (ffffffff8118ac80)
Location: kernel/trace/trace_sched_switch.c:83
Inline: False
Direct callers:
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
```
**Symbols:**

```
ffffffff8118ac80-ffffffff8118acc5: tracing_sched_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tracing_sched_unregister();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_sched_switch.c (ffffffff811985e0)
Location: kernel/trace/trace_sched_switch.c:83
Inline: False
Direct callers:
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
```
**Symbols:**

```
ffffffff811985e0-ffffffff81198625: tracing_sched_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tracing_sched_unregister();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_sched_switch.c (ffffffff811a6170)
Location: kernel/trace/trace_sched_switch.c:83
Inline: False
Direct callers:
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
```
**Symbols:**

```
ffffffff811a6170-ffffffff811a61b5: tracing_sched_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tracing_sched_unregister();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_sched_switch.c (ffffffff811b1960)
Location: kernel/trace/trace_sched_switch.c:83
Inline: False
Direct callers:
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
```
**Symbols:**

```
ffffffff811b1960-ffffffff811b19a5: tracing_sched_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_sched_switch.c (ffffffff811c9d05)
Location: kernel/trace/trace_sched_switch.c:83
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_sched_switch.c (ffffffff811c73c5)
Location: kernel/trace/trace_sched_switch.c:83
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_sched_switch.c (ffffffff811c84e5)
Location: kernel/trace/trace_sched_switch.c:83
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_sched_switch.c (ffffffff811f3eb5)
Location: kernel/trace/trace_sched_switch.c:83
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_sched_switch.c (ffffffff8122d6a1)
Location: kernel/trace/trace_sched_switch.c:84
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_sched_switch.c (ffffffff81279431)
Location: kernel/trace/trace_sched_switch.c:84
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_sched_switch.c (ffffffff81290e71)
Location: kernel/trace/trace_sched_switch.c:84
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_sched_switch.c (ffffffff812ac481)
Location: kernel/trace/trace_sched_switch.c:84
Inline: True
Inline callers:
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
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
void tracing_sched_unregister();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_sched_switch.c (ffff80001022f748)
Location: kernel/trace/trace_sched_switch.c:83
Inline: False
Direct callers:
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
```
**Symbols:**

```
ffff80001022f748-ffff80001022f7a8: tracing_sched_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tracing_sched_unregister();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_sched_switch.c (c046b3e8)
Location: kernel/trace/trace_sched_switch.c:83
Inline: False
Direct callers:
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
```
**Symbols:**

```
c046b3e8-c046b440: tracing_sched_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tracing_sched_unregister();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_sched_switch.c (c0000000002b9170)
Location: kernel/trace/trace_sched_switch.c:83
Inline: False
Direct callers:
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
```
**Symbols:**

```
c0000000002b9170-c0000000002b91f0: tracing_sched_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tracing_sched_unregister();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_sched_switch.c (ffffffe00018778c)
Location: kernel/trace/trace_sched_switch.c:83
Inline: False
Direct callers:
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
```
**Symbols:**

```
ffffffe00018778c-ffffffe0001877ea: tracing_sched_unregister (STB_LOCAL)
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
void tracing_sched_unregister();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_sched_switch.c (ffffffff811a9f80)
Location: kernel/trace/trace_sched_switch.c:83
Inline: False
Direct callers:
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
```
**Symbols:**

```
ffffffff811a9f80-ffffffff811a9fc5: tracing_sched_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tracing_sched_unregister();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_sched_switch.c (ffffffff8119cf00)
Location: kernel/trace/trace_sched_switch.c:83
Inline: False
Direct callers:
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
```
**Symbols:**

```
ffffffff8119cf00-ffffffff8119cf45: tracing_sched_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tracing_sched_unregister();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_sched_switch.c (ffffffff811a7d50)
Location: kernel/trace/trace_sched_switch.c:83
Inline: False
Direct callers:
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
```
**Symbols:**

```
ffffffff811a7d50-ffffffff811a7d95: tracing_sched_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tracing_sched_unregister();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_sched_switch.c (ffffffff811b5af0)
Location: kernel/trace/trace_sched_switch.c:83
Inline: False
Direct callers:
  - kernel/trace/trace_sched_switch.c:tracing_stop_tgid_record
  - kernel/trace/trace_sched_switch.c:tracing_stop_cmdline_record
```
**Symbols:**

```
ffffffff811b5af0-ffffffff811b5b35: tracing_sched_unregister (STB_LOCAL)
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
