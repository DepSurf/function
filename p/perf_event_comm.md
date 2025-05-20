# Function: <code>perf_event_comm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void perf_event_comm(struct task_struct *task, bool exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81183e90)
Location: kernel/events/core.c:5905
Inline: False
Direct callers:
  - fs/exec.c:__set_task_comm
```
**Symbols:**

```
ffffffff81183e90-ffffffff81183f94: perf_event_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void perf_event_comm(struct task_struct *task, bool exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81195b80)
Location: kernel/events/core.c:6422
Inline: False
Direct callers:
  - fs/exec.c:__set_task_comm
```
**Symbols:**

```
ffffffff81195b80-ffffffff81195c85: perf_event_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void perf_event_comm(struct task_struct *task, bool exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a55d0)
Location: kernel/events/core.c:6520
Inline: False
Direct callers:
  - fs/exec.c:__set_task_comm
```
**Symbols:**

```
ffffffff811a55d0-ffffffff811a56d5: perf_event_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void perf_event_comm(struct task_struct *task, bool exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811acc20)
Location: kernel/events/core.c:6617
Inline: False
Direct callers:
  - fs/exec.c:__set_task_comm
```
**Symbols:**

```
ffffffff811acc20-ffffffff811acda8: perf_event_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void perf_event_comm(struct task_struct *task, bool exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811c0770)
Location: kernel/events/core.c:6605
Inline: False
Direct callers:
  - fs/exec.c:__set_task_comm
```
**Symbols:**

```
ffffffff811c0770-ffffffff811c08f8: perf_event_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void perf_event_comm(struct task_struct *task, bool exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/core.c:6979
Inline: False
Direct callers:
  - fs/exec.c:__set_task_comm
```
**Symbols:**

```
ffffffff811e2022-ffffffff811e203a: perf_event_comm.cold.131 (STB_LOCAL)
ffffffff811e0b90-ffffffff811e0cf8: perf_event_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void perf_event_comm(struct task_struct *task, bool exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/core.c:6988
Inline: False
Direct callers:
  - fs/exec.c:__set_task_comm
```
**Symbols:**

```
ffffffff811f2492-ffffffff811f24aa: perf_event_comm.cold.131 (STB_LOCAL)
ffffffff811f0ff0-ffffffff811f1158: perf_event_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void perf_event_comm(struct task_struct *task, bool exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/core.c:7070
Inline: False
Direct callers:
  - fs/exec.c:__set_task_comm
```
**Symbols:**

```
ffffffff8120a145-ffffffff8120a15d: perf_event_comm.cold (STB_LOCAL)
ffffffff812087f0-ffffffff81208967: perf_event_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void perf_event_comm(struct task_struct *task, bool exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/core.c:7186
Inline: False
Direct callers:
  - fs/exec.c:__set_task_comm
```
**Symbols:**

```
ffffffff8121743f-ffffffff81217457: perf_event_comm.cold (STB_LOCAL)
ffffffff81215b60-ffffffff81215cd7: perf_event_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void perf_event_comm(struct task_struct *task, bool exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81241eb0)
Location: kernel/events/core.c:7638
Inline: False
Direct callers:
  - fs/exec.c:__set_task_comm
```
**Symbols:**

```
ffffffff81241eb0-ffffffff81241f26: perf_event_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void perf_event_comm(struct task_struct *task, bool exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8124c5f0)
Location: kernel/events/core.c:7820
Inline: False
Direct callers:
  - fs/exec.c:__set_task_comm
```
**Symbols:**

```
ffffffff8124c5f0-ffffffff8124c666: perf_event_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void perf_event_comm(struct task_struct *task, bool exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/core.c:7931
Inline: False
Direct callers:
  - fs/exec.c:__set_task_comm
```
**Symbols:**

```
ffffffff81bd8474-ffffffff81bd848c: perf_event_comm.cold (STB_LOCAL)
ffffffff81250ba0-ffffffff81250cac: perf_event_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void perf_event_comm(struct task_struct *task, bool exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/core.c:8055
Inline: False
Direct callers:
  - fs/exec.c:__set_task_comm
```
**Symbols:**

```
ffffffff81cb995e-ffffffff81cb9976: perf_event_comm.cold (STB_LOCAL)
ffffffff8128b960-ffffffff8128ba6c: perf_event_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void perf_event_comm(struct task_struct *task, bool exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/core.c:7960
Inline: False
Direct callers:
  - fs/exec.c:__set_task_comm
```
**Symbols:**

```
ffffffff81e6af36-ffffffff81e6af4e: perf_event_comm.cold (STB_LOCAL)
ffffffff812e01d0-ffffffff812e02ec: perf_event_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void perf_event_comm(struct task_struct *task, bool exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81348600)
Location: kernel/events/core.c:8242
Inline: False
Direct callers:
  - fs/exec.c:__set_task_comm
```
**Symbols:**

```
ffffffff81348600-ffffffff81348728: perf_event_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void perf_event_comm(struct task_struct *task, bool exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff813797c0)
Location: kernel/events/core.c:8270
Inline: False
Direct callers:
  - fs/exec.c:__set_task_comm
```
**Symbols:**

```
ffffffff813797c0-ffffffff8137983f: perf_event_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void perf_event_comm(struct task_struct *task, bool exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff813a2ad0)
Location: kernel/events/core.c:8351
Inline: False
Direct callers:
  - fs/exec.c:__set_task_comm
```
**Symbols:**

```
ffffffff813a2ad0-ffffffff813a2b4f: perf_event_comm (STB_GLOBAL)
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
void perf_event_comm(struct task_struct *task, bool exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff80001029fc58)
Location: kernel/events/core.c:7186
Inline: False
Direct callers:
  - fs/exec.c:__set_task_comm
```
**Symbols:**

```
ffff80001029fc58-ffff80001029fd78: perf_event_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void perf_event_comm(struct task_struct *task, bool exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04cfaec)
Location: kernel/events/core.c:7186
Inline: False
Direct callers:
  - fs/exec.c:__set_task_comm
```
**Symbols:**

```
c04cfaec-c04cfc28: perf_event_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void perf_event_comm(struct task_struct *task, bool exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c000000000351210)
Location: kernel/events/core.c:7186
Inline: False
Direct callers:
  - fs/exec.c:__set_task_comm
```
**Symbols:**

```
c000000000351210-c0000000003513bc: perf_event_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void perf_event_comm(struct task_struct *task, bool exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001cf412)
Location: kernel/events/core.c:7186
Inline: False
Direct callers:
  - fs/exec.c:__set_task_comm
```
**Symbols:**

```
ffffffe0001cf412-ffffffe0001cf4ac: perf_event_comm (STB_GLOBAL)
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
void perf_event_comm(struct task_struct *task, bool exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/core.c:7186
Inline: False
Direct callers:
  - fs/exec.c:__set_task_comm
```
**Symbols:**

```
ffffffff8120fa8f-ffffffff8120faa7: perf_event_comm.cold (STB_LOCAL)
ffffffff8120e1b0-ffffffff8120e327: perf_event_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void perf_event_comm(struct task_struct *task, bool exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/core.c:7186
Inline: False
Direct callers:
  - fs/exec.c:__set_task_comm
```
**Symbols:**

```
ffffffff8120281f-ffffffff81202837: perf_event_comm.cold (STB_LOCAL)
ffffffff81200f60-ffffffff812010d7: perf_event_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void perf_event_comm(struct task_struct *task, bool exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/core.c:7186
Inline: False
Direct callers:
  - fs/exec.c:__set_task_comm
```
**Symbols:**

```
ffffffff8120d82f-ffffffff8120d847: perf_event_comm.cold (STB_LOCAL)
ffffffff8120bf50-ffffffff8120c0c7: perf_event_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void perf_event_comm(struct task_struct *task, bool exec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/core.c:7186
Inline: False
Direct callers:
  - fs/exec.c:__set_task_comm
```
**Symbols:**

```
ffffffff8121c6cf-ffffffff8121c6e7: perf_event_comm.cold (STB_LOCAL)
ffffffff8121adc0-ffffffff8121af37: perf_event_comm (STB_GLOBAL)
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
