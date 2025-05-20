# Function: <code>syscall_exit_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int syscall_exit_register(struct trace_event_call *event, enum trace_reg type, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff81161a00)
Location: kernel/trace/trace_syscalls.c:725
Inline: True
```
**Symbols:**

```
ffffffff81161a00-ffffffff81161c5f: syscall_exit_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int syscall_exit_register(struct trace_event_call *event, enum trace_reg type, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff8116c100)
Location: kernel/trace/trace_syscalls.c:739
Inline: True
```
**Symbols:**

```
ffffffff8116c100-ffffffff8116c34c: syscall_exit_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int syscall_exit_register(struct trace_event_call *event, enum trace_reg type, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff81177510)
Location: kernel/trace/trace_syscalls.c:737
Inline: True
```
**Symbols:**

```
ffffffff81177510-ffffffff8117775c: syscall_exit_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int syscall_exit_register(struct trace_event_call *event, enum trace_reg type, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff8117a1b0)
Location: kernel/trace/trace_syscalls.c:737
Inline: True
```
**Symbols:**

```
ffffffff8117a1b0-ffffffff8117a3b6: syscall_exit_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int syscall_exit_register(struct trace_event_call *event, enum trace_reg type, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff81187980)
Location: kernel/trace/trace_syscalls.c:791
Inline: True
```
**Symbols:**

```
ffffffff81187980-ffffffff81187b86: syscall_exit_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int syscall_exit_register(struct trace_event_call *event, enum trace_reg type, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_syscalls.c (0)
Location: kernel/trace/trace_syscalls.c:791
Inline: True
```
**Symbols:**

```
ffffffff81196b70-ffffffff81196d4f: syscall_exit_register (STB_LOCAL)
ffffffff81197543-ffffffff81197554: syscall_exit_register.cold.24 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int syscall_exit_register(struct trace_event_call *event, enum trace_reg type, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff811a4d5a)
Location: kernel/trace/trace_syscalls.c:791
Inline: True
```
**Symbols:**

```
ffffffff811a4cb0-ffffffff811a4e8f: syscall_exit_register (STB_LOCAL)
ffffffff811a56b3-ffffffff811a56c4: syscall_exit_register.cold.24 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int syscall_exit_register(struct trace_event_call *event, enum trace_reg type, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff811b2b63)
Location: kernel/trace/trace_syscalls.c:794
Inline: True
```
**Symbols:**

```
ffffffff811b2a20-ffffffff811b2bdd: syscall_exit_register (STB_LOCAL)
ffffffff811b35c3-ffffffff811b35d4: syscall_exit_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int syscall_exit_register(struct trace_event_call *event, enum trace_reg type, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff811be6a3)
Location: kernel/trace/trace_syscalls.c:794
Inline: True
```
**Symbols:**

```
ffffffff811be560-ffffffff811be71d: syscall_exit_register (STB_LOCAL)
ffffffff811bebcb-ffffffff811bebdc: syscall_exit_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int syscall_exit_register(struct trace_event_call *event, enum trace_reg type, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_syscalls.c (0)
Location: kernel/trace/trace_syscalls.c:803
Inline: False
```
**Symbols:**

```
ffffffff811d7f30-ffffffff811d810c: syscall_exit_register (STB_LOCAL)
ffffffff811d846e-ffffffff811d847f: syscall_exit_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int syscall_exit_register(struct trace_event_call *event, enum trace_reg type, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_syscalls.c (0)
Location: kernel/trace/trace_syscalls.c:803
Inline: False
```
**Symbols:**

```
ffffffff811d4ff0-ffffffff811d51cc: syscall_exit_register (STB_LOCAL)
ffffffff81be62fa-ffffffff81be630b: syscall_exit_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int syscall_exit_register(struct trace_event_call *event, enum trace_reg type, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_syscalls.c (0)
Location: kernel/trace/trace_syscalls.c:799
Inline: False
```
**Symbols:**

```
ffffffff811d62d0-ffffffff811d64aa: syscall_exit_register (STB_LOCAL)
ffffffff81bd7fa9-ffffffff81bd7fba: syscall_exit_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int syscall_exit_register(struct trace_event_call *event, enum trace_reg type, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_syscalls.c (0)
Location: kernel/trace/trace_syscalls.c:797
Inline: False
```
**Symbols:**

```
ffffffff81203120-ffffffff8120333d: syscall_exit_register (STB_LOCAL)
ffffffff81cb66a5-ffffffff81cb66b6: syscall_exit_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int syscall_exit_register(struct trace_event_call *event, enum trace_reg type, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_syscalls.c (0)
Location: kernel/trace/trace_syscalls.c:784
Inline: False
```
**Symbols:**

```
ffffffff8123e3f0-ffffffff8123e622: syscall_exit_register (STB_LOCAL)
ffffffff81e67665-ffffffff81e67676: syscall_exit_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int syscall_exit_register(struct trace_event_call *event, enum trace_reg type, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff8128bdd0)
Location: kernel/trace/trace_syscalls.c:782
Inline: False
```
**Symbols:**

```
ffffffff8128bdd0-ffffffff8128c010: syscall_exit_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int syscall_exit_register(struct trace_event_call *event, enum trace_reg type, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff812a8f20)
Location: kernel/trace/trace_syscalls.c:782
Inline: False
```
**Symbols:**

```
ffffffff812a8f20-ffffffff812a915f: syscall_exit_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int syscall_exit_register(struct trace_event_call *event, enum trace_reg type, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff812c4c30)
Location: kernel/trace/trace_syscalls.c:786
Inline: False
```
**Symbols:**

```
ffffffff812c4c30-ffffffff812c4e6f: syscall_exit_register (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int syscall_exit_register(struct trace_event_call *event, enum trace_reg type, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffff80001023d3d0)
Location: kernel/trace/trace_syscalls.c:794
Inline: True
```
**Symbols:**

```
ffff80001023d3d0-ffff80001023d65c: syscall_exit_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int syscall_exit_register(struct trace_event_call *event, enum trace_reg type, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (c0478d48)
Location: kernel/trace/trace_syscalls.c:794
Inline: False
```
**Symbols:**

```
c0478d48-c0478fbc: syscall_exit_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int syscall_exit_register(struct trace_event_call *event, enum trace_reg type, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (c0000000002ccd00)
Location: kernel/trace/trace_syscalls.c:794
Inline: True
```
**Symbols:**

```
c0000000002ccd00-c0000000002cd064: syscall_exit_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int syscall_exit_register(struct trace_event_call *event, enum trace_reg type, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffe000193560)
Location: kernel/trace/trace_syscalls.c:794
Inline: True
```
**Symbols:**

```
ffffffe000193560-ffffffe00019377c: syscall_exit_register (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int syscall_exit_register(struct trace_event_call *event, enum trace_reg type, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff811b6cc3)
Location: kernel/trace/trace_syscalls.c:794
Inline: True
```
**Symbols:**

```
ffffffff811b6b80-ffffffff811b6d3d: syscall_exit_register (STB_LOCAL)
ffffffff811b71eb-ffffffff811b71fc: syscall_exit_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int syscall_exit_register(struct trace_event_call *event, enum trace_reg type, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff811a9ab3)
Location: kernel/trace/trace_syscalls.c:794
Inline: True
```
**Symbols:**

```
ffffffff811a9970-ffffffff811a9b2d: syscall_exit_register (STB_LOCAL)
ffffffff811a9fdb-ffffffff811a9fec: syscall_exit_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int syscall_exit_register(struct trace_event_call *event, enum trace_reg type, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff811b4a93)
Location: kernel/trace/trace_syscalls.c:794
Inline: True
```
**Symbols:**

```
ffffffff811b4950-ffffffff811b4b0d: syscall_exit_register (STB_LOCAL)
ffffffff811b4fbb-ffffffff811b4fcc: syscall_exit_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int syscall_exit_register(struct trace_event_call *event, enum trace_reg type, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_syscalls.c (ffffffff811c2b33)
Location: kernel/trace/trace_syscalls.c:794
Inline: True
```
**Symbols:**

```
ffffffff811c29f0-ffffffff811c2bad: syscall_exit_register (STB_LOCAL)
ffffffff811c305b-ffffffff811c306c: syscall_exit_register.cold (STB_LOCAL)
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
