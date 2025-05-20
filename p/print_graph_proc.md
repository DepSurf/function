# Function: <code>print_graph_proc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void print_graph_proc(struct trace_seq *s, pid_t pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_functions_graph.c (ffffffff81158e60)
Location: kernel/trace/trace_functions_graph.c:496
Inline: False
Direct callers:
  - kernel/trace/trace_functions_graph.c:print_graph_irq
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
```
**Symbols:**

```
ffffffff81158e60-ffffffff81158f9a: print_graph_proc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void print_graph_proc(struct trace_seq *s, pid_t pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_functions_graph.c (ffffffff81163710)
Location: kernel/trace/trace_functions_graph.c:496
Inline: False
Direct callers:
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_irq
```
**Symbols:**

```
ffffffff81163710-ffffffff81163859: print_graph_proc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void print_graph_proc(struct trace_seq *s, pid_t pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_functions_graph.c (ffffffff8116ea40)
Location: kernel/trace/trace_functions_graph.c:558
Inline: False
Direct callers:
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_irq
```
**Symbols:**

```
ffffffff8116ea40-ffffffff8116eb89: print_graph_proc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void print_graph_proc(struct trace_seq *s, pid_t pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_functions_graph.c (ffffffff81171c60)
Location: kernel/trace/trace_functions_graph.c:558
Inline: False
Direct callers:
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_irq
```
**Symbols:**

```
ffffffff81171c60-ffffffff81171da7: print_graph_proc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void print_graph_proc(struct trace_seq *s, pid_t pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_functions_graph.c (ffffffff8117edf0)
Location: kernel/trace/trace_functions_graph.c:559
Inline: False
Direct callers:
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_irq
```
**Symbols:**

```
ffffffff8117edf0-ffffffff8117ef37: print_graph_proc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void print_graph_proc(struct trace_seq *s, pid_t pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_functions_graph.c (0)
Location: kernel/trace/trace_functions_graph.c:559
Inline: False
Direct callers:
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_irq
```
**Symbols:**

```
ffffffff8118df00-ffffffff8118e033: print_graph_proc (STB_LOCAL)
ffffffff8118fc81-ffffffff8118fc99: print_graph_proc.cold.15 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void print_graph_proc(struct trace_seq *s, pid_t pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_functions_graph.c (0)
Location: kernel/trace/trace_functions_graph.c:348
Inline: False
Direct callers:
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_irq
```
**Symbols:**

```
ffffffff8119b880-ffffffff8119b9b3: print_graph_proc (STB_LOCAL)
ffffffff8119d451-ffffffff8119d469: print_graph_proc.cold.15 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void print_graph_proc(struct trace_seq *s, pid_t pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_functions_graph.c (0)
Location: kernel/trace/trace_functions_graph.c:345
Inline: False
Direct callers:
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_irq
```
**Symbols:**

```
ffffffff811a9480-ffffffff811a95b5: print_graph_proc (STB_LOCAL)
ffffffff811ab181-ffffffff811ab199: print_graph_proc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void print_graph_proc(struct trace_seq *s, pid_t pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_functions_graph.c (0)
Location: kernel/trace/trace_functions_graph.c:345
Inline: False
Direct callers:
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_irq
```
**Symbols:**

```
ffffffff811b4c70-ffffffff811b4da5: print_graph_proc (STB_LOCAL)
ffffffff811b6971-ffffffff811b6989: print_graph_proc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void print_graph_proc(struct trace_seq *s, pid_t pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_functions_graph.c (0)
Location: kernel/trace/trace_functions_graph.c:345
Inline: False
Direct callers:
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_irq
```
**Symbols:**

```
ffffffff811cd630-ffffffff811cd76a: print_graph_proc (STB_LOCAL)
ffffffff811cf408-ffffffff811cf420: print_graph_proc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void print_graph_proc(struct trace_seq *s, pid_t pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_functions_graph.c (0)
Location: kernel/trace/trace_functions_graph.c:345
Inline: False
Direct callers:
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_irq
```
**Symbols:**

```
ffffffff811cab10-ffffffff811cac4a: print_graph_proc (STB_LOCAL)
ffffffff81be5d36-ffffffff81be5d4e: print_graph_proc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void print_graph_proc(struct trace_seq *s, pid_t pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_functions_graph.c (0)
Location: kernel/trace/trace_functions_graph.c:343
Inline: False
Direct callers:
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_irq
```
**Symbols:**

```
ffffffff811cbe40-ffffffff811cbf70: print_graph_proc (STB_LOCAL)
ffffffff81bd7b4f-ffffffff81bd7b67: print_graph_proc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void print_graph_proc(struct trace_seq *s, pid_t pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_functions_graph.c (0)
Location: kernel/trace/trace_functions_graph.c:343
Inline: False
Direct callers:
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_irq
```
**Symbols:**

```
ffffffff811f8440-ffffffff811f8570: print_graph_proc (STB_LOCAL)
ffffffff81cb6061-ffffffff81cb6079: print_graph_proc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void print_graph_proc(struct trace_seq *s, pid_t pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_functions_graph.c (0)
Location: kernel/trace/trace_functions_graph.c:343
Inline: False
Direct callers:
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_irq
```
**Symbols:**

```
ffffffff81232160-ffffffff812322bc: print_graph_proc (STB_LOCAL)
ffffffff81e6707d-ffffffff81e67095: print_graph_proc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void print_graph_proc(struct trace_seq *s, pid_t pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_functions_graph.c (ffffffff8127e7d0)
Location: kernel/trace/trace_functions_graph.c:343
Inline: False
Direct callers:
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_irq
```
**Symbols:**

```
ffffffff8127e7d0-ffffffff8127e93d: print_graph_proc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void print_graph_proc(struct trace_seq *s, pid_t pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_functions_graph.c (ffffffff8129b330)
Location: kernel/trace/trace_functions_graph.c:349
Inline: False
Direct callers:
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_irq
```
**Symbols:**

```
ffffffff8129b330-ffffffff8129b4c3: print_graph_proc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void print_graph_proc(struct trace_seq *s, pid_t pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_functions_graph.c (ffffffff812b69e0)
Location: kernel/trace/trace_functions_graph.c:349
Inline: False
Direct callers:
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_irq
```
**Symbols:**

```
ffffffff812b69e0-ffffffff812b6b73: print_graph_proc (STB_LOCAL)
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
void print_graph_proc(struct trace_seq *s, pid_t pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_functions_graph.c (ffff800010232a18)
Location: kernel/trace/trace_functions_graph.c:345
Inline: False
Direct callers:
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_irq
```
**Symbols:**

```
ffff800010232a18-ffff800010232b94: print_graph_proc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void print_graph_proc(struct trace_seq *s, pid_t pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_functions_graph.c (c046e6a0)
Location: kernel/trace/trace_functions_graph.c:345
Inline: False
Direct callers:
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_irq
```
**Symbols:**

```
c046e6a0-c046e7f8: print_graph_proc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void print_graph_proc(struct trace_seq *s, pid_t pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_functions_graph.c (c0000000002bd600)
Location: kernel/trace/trace_functions_graph.c:345
Inline: False
Direct callers:
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_irq
```
**Symbols:**

```
c0000000002bd600-c0000000002bd7f4: print_graph_proc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void print_graph_proc(struct trace_seq *s, pid_t pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_functions_graph.c (ffffffe00018a0d2)
Location: kernel/trace/trace_functions_graph.c:345
Inline: False
Direct callers:
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_irq
```
**Symbols:**

```
ffffffe00018a0d2-ffffffe00018a1d8: print_graph_proc (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void print_graph_proc(struct trace_seq *s, pid_t pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_functions_graph.c (0)
Location: kernel/trace/trace_functions_graph.c:345
Inline: False
Direct callers:
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_irq
```
**Symbols:**

```
ffffffff811ad290-ffffffff811ad3c5: print_graph_proc (STB_LOCAL)
ffffffff811aef91-ffffffff811aefa9: print_graph_proc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void print_graph_proc(struct trace_seq *s, pid_t pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_functions_graph.c (0)
Location: kernel/trace/trace_functions_graph.c:345
Inline: False
Direct callers:
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_irq
```
**Symbols:**

```
ffffffff811a0120-ffffffff811a0255: print_graph_proc (STB_LOCAL)
ffffffff811a1de1-ffffffff811a1df9: print_graph_proc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void print_graph_proc(struct trace_seq *s, pid_t pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_functions_graph.c (0)
Location: kernel/trace/trace_functions_graph.c:345
Inline: False
Direct callers:
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_irq
```
**Symbols:**

```
ffffffff811ab060-ffffffff811ab195: print_graph_proc (STB_LOCAL)
ffffffff811acd61-ffffffff811acd79: print_graph_proc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void print_graph_proc(struct trace_seq *s, pid_t pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_functions_graph.c (0)
Location: kernel/trace/trace_functions_graph.c:345
Inline: False
Direct callers:
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_prologue
  - kernel/trace/trace_functions_graph.c:print_graph_irq
```
**Symbols:**

```
ffffffff811b8ed0-ffffffff811b9005: print_graph_proc (STB_LOCAL)
ffffffff811bac31-ffffffff811bac49: print_graph_proc.cold (STB_LOCAL)
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
