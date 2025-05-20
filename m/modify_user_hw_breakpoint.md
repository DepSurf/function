# Function: <code>modify_user_hw_breakpoint</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int modify_user_hw_breakpoint(struct perf_event *bp, struct perf_event_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff811866a0)
Location: kernel/events/hw_breakpoint.c:433
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ptrace_set_breakpoint_addr
  - arch/x86/kernel/ptrace.c:ptrace_modify_breakpoint
```
**Symbols:**

```
ffffffff811866a0-ffffffff811867a9: modify_user_hw_breakpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int modify_user_hw_breakpoint(struct perf_event *bp, struct perf_event_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff81198b60)
Location: kernel/events/hw_breakpoint.c:433
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ptrace_set_breakpoint_addr
  - arch/x86/kernel/ptrace.c:ptrace_modify_breakpoint
```
**Symbols:**

```
ffffffff81198b60-ffffffff81198c70: modify_user_hw_breakpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int modify_user_hw_breakpoint(struct perf_event *bp, struct perf_event_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff811a8540)
Location: kernel/events/hw_breakpoint.c:433
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ptrace_set_breakpoint_addr
  - arch/x86/kernel/ptrace.c:ptrace_modify_breakpoint
```
**Symbols:**

```
ffffffff811a8540-ffffffff811a8650: modify_user_hw_breakpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int modify_user_hw_breakpoint(struct perf_event *bp, struct perf_event_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff811afcf0)
Location: kernel/events/hw_breakpoint.c:433
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ptrace_set_breakpoint_addr
  - arch/x86/kernel/ptrace.c:ptrace_modify_breakpoint
```
**Symbols:**

```
ffffffff811afcf0-ffffffff811afe00: modify_user_hw_breakpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int modify_user_hw_breakpoint(struct perf_event *bp, struct perf_event_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff811c3870)
Location: kernel/events/hw_breakpoint.c:431
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ptrace_set_breakpoint_addr
  - arch/x86/kernel/ptrace.c:ptrace_modify_breakpoint
```
**Symbols:**

```
ffffffff811c3870-ffffffff811c3926: modify_user_hw_breakpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int modify_user_hw_breakpoint(struct perf_event *bp, struct perf_event_attr *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff811e4300)
Location: kernel/events/hw_breakpoint.c:521
Inline: True
Direct callers:
  - arch/x86/kernel/ptrace.c:ptrace_set_breakpoint_addr
  - arch/x86/kernel/ptrace.c:ptrace_modify_breakpoint
```
**Symbols:**

```
ffffffff811e4300-ffffffff811e4391: modify_user_hw_breakpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int modify_user_hw_breakpoint(struct perf_event *bp, struct perf_event_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff811f4800)
Location: kernel/events/hw_breakpoint.c:510
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ptrace_set_breakpoint_addr
  - arch/x86/kernel/ptrace.c:ptrace_modify_breakpoint
```
**Symbols:**

```
ffffffff811f4800-ffffffff811f4885: modify_user_hw_breakpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int modify_user_hw_breakpoint(struct perf_event *bp, struct perf_event_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff8120c510)
Location: kernel/events/hw_breakpoint.c:497
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ptrace_set_breakpoint_addr
  - arch/x86/kernel/ptrace.c:ptrace_modify_breakpoint
```
**Symbols:**

```
ffffffff8120c510-ffffffff8120c59a: modify_user_hw_breakpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int modify_user_hw_breakpoint(struct perf_event *bp, struct perf_event_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff81219810)
Location: kernel/events/hw_breakpoint.c:497
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ptrace_set_breakpoint_addr
  - arch/x86/kernel/ptrace.c:ptrace_modify_breakpoint
```
**Symbols:**

```
ffffffff81219810-ffffffff8121989a: modify_user_hw_breakpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int modify_user_hw_breakpoint(struct perf_event *bp, struct perf_event_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff81245650)
Location: kernel/events/hw_breakpoint.c:513
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ptrace_set_breakpoint_addr
  - arch/x86/kernel/ptrace.c:ptrace_modify_breakpoint
```
**Symbols:**

```
ffffffff81245650-ffffffff812456da: modify_user_hw_breakpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int modify_user_hw_breakpoint(struct perf_event *bp, struct perf_event_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff8124fca0)
Location: kernel/events/hw_breakpoint.c:513
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ptrace_set_breakpoint_addr
  - arch/x86/kernel/ptrace.c:ptrace_modify_breakpoint
```
**Symbols:**

```
ffffffff8124fca0-ffffffff8124fd2a: modify_user_hw_breakpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int modify_user_hw_breakpoint(struct perf_event *bp, struct perf_event_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff81254580)
Location: kernel/events/hw_breakpoint.c:513
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ptrace_set_breakpoint_addr
  - arch/x86/kernel/ptrace.c:ptrace_modify_breakpoint
```
**Symbols:**

```
ffffffff81254580-ffffffff8125460a: modify_user_hw_breakpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int modify_user_hw_breakpoint(struct perf_event *bp, struct perf_event_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff8128fff0)
Location: kernel/events/hw_breakpoint.c:514
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ptrace_set_breakpoint_addr
  - arch/x86/kernel/ptrace.c:ptrace_modify_breakpoint
```
**Symbols:**

```
ffffffff8128fff0-ffffffff8129007a: modify_user_hw_breakpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int modify_user_hw_breakpoint(struct perf_event *bp, struct perf_event_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff812e50a0)
Location: kernel/events/hw_breakpoint.c:514
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ptrace_set_breakpoint_addr
  - arch/x86/kernel/ptrace.c:ptrace_modify_breakpoint
```
**Symbols:**

```
ffffffff812e50a0-ffffffff812e5138: modify_user_hw_breakpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int modify_user_hw_breakpoint(struct perf_event *bp, struct perf_event_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff8134e8e0)
Location: kernel/events/hw_breakpoint.c:825
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ptrace_set_breakpoint_addr
  - arch/x86/kernel/ptrace.c:ptrace_modify_breakpoint
```
**Symbols:**

```
ffffffff8134e8e0-ffffffff8134e97f: modify_user_hw_breakpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int modify_user_hw_breakpoint(struct perf_event *bp, struct perf_event_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff8137fa70)
Location: kernel/events/hw_breakpoint.c:825
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ptrace_set_breakpoint_addr
  - arch/x86/kernel/ptrace.c:ptrace_modify_breakpoint
```
**Symbols:**

```
ffffffff8137fa70-ffffffff8137fb0f: modify_user_hw_breakpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int modify_user_hw_breakpoint(struct perf_event *bp, struct perf_event_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff813a8c80)
Location: kernel/events/hw_breakpoint.c:797
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ptrace_set_breakpoint_addr
  - arch/x86/kernel/ptrace.c:ptrace_modify_breakpoint
```
**Symbols:**

```
ffffffff813a8c80-ffffffff813a8d1f: modify_user_hw_breakpoint (STB_GLOBAL)
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
int modify_user_hw_breakpoint(struct perf_event *bp, struct perf_event_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffff8000102a4988)
Location: kernel/events/hw_breakpoint.c:497
Inline: False
Direct callers:
  - arch/arm64/kernel/ptrace.c:ptrace_hbp_set_addr
  - arch/arm64/kernel/ptrace.c:ptrace_hbp_set_ctrl
```
**Symbols:**

```
ffff8000102a4988-ffff8000102a4a20: modify_user_hw_breakpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int modify_user_hw_breakpoint(struct perf_event *bp, struct perf_event_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (c04d3f2c)
Location: kernel/events/hw_breakpoint.c:497
Inline: False
Direct callers:
  - arch/arm/kernel/ptrace.c:ptrace_sethbpregs
```
**Symbols:**

```
c04d3f2c-c04d3fc4: modify_user_hw_breakpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int modify_user_hw_breakpoint(struct perf_event *bp, struct perf_event_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (c000000000357270)
Location: kernel/events/hw_breakpoint.c:497
Inline: False
Direct callers:
  - arch/powerpc/kernel/ptrace.c:ptrace_set_debugreg
  - arch/powerpc/kernel/ptrace.c:ptrace_triggered
```
**Symbols:**

```
c000000000357270-c000000000357354: modify_user_hw_breakpoint (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int modify_user_hw_breakpoint(struct perf_event *bp, struct perf_event_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff81211e60)
Location: kernel/events/hw_breakpoint.c:497
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ptrace_set_breakpoint_addr
  - arch/x86/kernel/ptrace.c:ptrace_modify_breakpoint
```
**Symbols:**

```
ffffffff81211e60-ffffffff81211eea: modify_user_hw_breakpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int modify_user_hw_breakpoint(struct perf_event *bp, struct perf_event_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff81204bf0)
Location: kernel/events/hw_breakpoint.c:497
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ptrace_set_breakpoint_addr
  - arch/x86/kernel/ptrace.c:ptrace_modify_breakpoint
```
**Symbols:**

```
ffffffff81204bf0-ffffffff81204c75: modify_user_hw_breakpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int modify_user_hw_breakpoint(struct perf_event *bp, struct perf_event_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff8120fc00)
Location: kernel/events/hw_breakpoint.c:497
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ptrace_set_breakpoint_addr
  - arch/x86/kernel/ptrace.c:ptrace_modify_breakpoint
```
**Symbols:**

```
ffffffff8120fc00-ffffffff8120fc8a: modify_user_hw_breakpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int modify_user_hw_breakpoint(struct perf_event *bp, struct perf_event_attr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/hw_breakpoint.c (ffffffff8121eb10)
Location: kernel/events/hw_breakpoint.c:497
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ptrace_set_breakpoint_addr
  - arch/x86/kernel/ptrace.c:ptrace_modify_breakpoint
```
**Symbols:**

```
ffffffff8121eb10-ffffffff8121eb9a: modify_user_hw_breakpoint (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
