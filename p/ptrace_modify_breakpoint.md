# Function: <code>ptrace_modify_breakpoint</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ptrace_modify_breakpoint(struct perf_event *bp, int len, int type, int disabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103bdf0)
Location: arch/x86/kernel/ptrace.c:629
Inline: False
```
**Symbols:**

```
ffffffff8103bdf0-ffffffff8103bf1f: ptrace_modify_breakpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ptrace_modify_breakpoint(struct perf_event *bp, int len, int type, int disabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103bbd0)
Location: arch/x86/kernel/ptrace.c:582
Inline: False
```
**Symbols:**

```
ffffffff8103bbd0-ffffffff8103bcff: ptrace_modify_breakpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ptrace_modify_breakpoint(struct perf_event *bp, int len, int type, int disabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103b3c0)
Location: arch/x86/kernel/ptrace.c:582
Inline: False
```
**Symbols:**

```
ffffffff8103b3c0-ffffffff8103b4ef: ptrace_modify_breakpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ptrace_modify_breakpoint(struct perf_event *bp, int len, int type, int disabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81039410)
Location: arch/x86/kernel/ptrace.c:583
Inline: False
```
**Symbols:**

```
ffffffff81039410-ffffffff8103953f: ptrace_modify_breakpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ptrace_modify_breakpoint(struct perf_event *bp, int len, int type, int disabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103be10)
Location: arch/x86/kernel/ptrace.c:583
Inline: False
```
**Symbols:**

```
ffffffff8103be10-ffffffff8103bf3f: ptrace_modify_breakpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ptrace_modify_breakpoint(struct perf_event *bp, int len, int type, int disabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103d300)
Location: arch/x86/kernel/ptrace.c:583
Inline: False
```
**Symbols:**

```
ffffffff8103d300-ffffffff8103d42f: ptrace_modify_breakpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ptrace_modify_breakpoint(struct perf_event *bp, int len, int type, int disabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103e830)
Location: arch/x86/kernel/ptrace.c:574
Inline: False
```
**Symbols:**

```
ffffffff8103e830-ffffffff8103e95f: ptrace_modify_breakpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ptrace_modify_breakpoint(struct perf_event *bp, int len, int type, int disabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81040f20)
Location: arch/x86/kernel/ptrace.c:548
Inline: False
```
**Symbols:**

```
ffffffff81040f20-ffffffff8104105b: ptrace_modify_breakpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ptrace_modify_breakpoint(struct perf_event *bp, int len, int type, int disabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff810416b0)
Location: arch/x86/kernel/ptrace.c:548
Inline: False
```
**Symbols:**

```
ffffffff810416b0-ffffffff810417eb: ptrace_modify_breakpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ptrace_modify_breakpoint(struct perf_event *bp, int len, int type, int disabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81044dc0)
Location: arch/x86/kernel/ptrace.c:560
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ptrace_write_dr7
```
**Symbols:**

```
ffffffff81044dc0-ffffffff81044f0c: ptrace_modify_breakpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ptrace_modify_breakpoint(struct perf_event *bp, int len, int type, int disabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81044820)
Location: arch/x86/kernel/ptrace.c:525
Inline: False
Direct callers:
  - arch/x86/kernel/ptrace.c:ptrace_write_dr7
```
**Symbols:**

```
ffffffff81044820-ffffffff8104496c: ptrace_modify_breakpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ptrace_modify_breakpoint(struct perf_event *bp, int len, int type, int disabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81046440)
Location: arch/x86/kernel/ptrace.c:525
Inline: False
```
**Symbols:**

```
ffffffff81046440-ffffffff8104659b: ptrace_modify_breakpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ptrace_modify_breakpoint(struct perf_event *bp, int len, int type, int disabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8104cb20)
Location: arch/x86/kernel/ptrace.c:525
Inline: False
```
**Symbols:**

```
ffffffff8104cb20-ffffffff8104cc7b: ptrace_modify_breakpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ptrace_modify_breakpoint(struct perf_event *bp, int len, int type, int disabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81057c70)
Location: arch/x86/kernel/ptrace.c:524
Inline: False
```
**Symbols:**

```
ffffffff81057c70-ffffffff81057ddf: ptrace_modify_breakpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ptrace_modify_breakpoint(struct perf_event *bp, int len, int type, int disabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81065490)
Location: arch/x86/kernel/ptrace.c:543
Inline: False
```
**Symbols:**

```
ffffffff81065490-ffffffff810655ff: ptrace_modify_breakpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ptrace_modify_breakpoint(struct perf_event *bp, int len, int type, int disabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81066cd0)
Location: arch/x86/kernel/ptrace.c:543
Inline: False
```
**Symbols:**

```
ffffffff81066cd0-ffffffff81066daa: ptrace_modify_breakpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ptrace_modify_breakpoint(struct perf_event *bp, int len, int type, int disabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8106e150)
Location: arch/x86/kernel/ptrace.c:544
Inline: False
```
**Symbols:**

```
ffffffff8106e150-ffffffff8106e22a: ptrace_modify_breakpoint (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int ptrace_modify_breakpoint(struct perf_event *bp, int len, int type, int disabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81041830)
Location: arch/x86/kernel/ptrace.c:548
Inline: False
```
**Symbols:**

```
ffffffff81041830-ffffffff8104196b: ptrace_modify_breakpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ptrace_modify_breakpoint(struct perf_event *bp, int len, int type, int disabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81030ef0)
Location: arch/x86/kernel/ptrace.c:548
Inline: False
```
**Symbols:**

```
ffffffff81030ef0-ffffffff8103102b: ptrace_modify_breakpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ptrace_modify_breakpoint(struct perf_event *bp, int len, int type, int disabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81041670)
Location: arch/x86/kernel/ptrace.c:548
Inline: False
```
**Symbols:**

```
ffffffff81041670-ffffffff810417ab: ptrace_modify_breakpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ptrace_modify_breakpoint(struct perf_event *bp, int len, int type, int disabled);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81042a50)
Location: arch/x86/kernel/ptrace.c:548
Inline: False
```
**Symbols:**

```
ffffffff81042a50-ffffffff81042b8b: ptrace_modify_breakpoint (STB_LOCAL)
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
