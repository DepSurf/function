# Function: <code>ptrace_trap_notify</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void ptrace_trap_notify(struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8108e0e0)
Location: kernel/signal.c:765
Inline: True
Direct callers:
  - kernel/signal.c:prepare_signal
  - kernel/signal.c:do_signal_stop
```
**Symbols:**

```
ffffffff8108e0e0-ffffffff8108e158: ptrace_trap_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void ptrace_trap_notify(struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81091160)
Location: kernel/signal.c:765
Inline: True
Direct callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:prepare_signal
```
**Symbols:**

```
ffffffff81091160-ffffffff810911d1: ptrace_trap_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void ptrace_trap_notify(struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810960d0)
Location: kernel/signal.c:771
Inline: True
Direct callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:prepare_signal
```
**Symbols:**

```
ffffffff810960d0-ffffffff81096141: ptrace_trap_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void ptrace_trap_notify(struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810933d0)
Location: kernel/signal.c:785
Inline: True
Direct callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:prepare_signal
```
**Symbols:**

```
ffffffff810933d0-ffffffff8109341f: ptrace_trap_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void ptrace_trap_notify(struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109a290)
Location: kernel/signal.c:787
Inline: True
Direct callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:prepare_signal
```
**Symbols:**

```
ffffffff8109a290-ffffffff8109a2df: ptrace_trap_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void ptrace_trap_notify(struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109e1b0)
Location: kernel/signal.c:793
Inline: True
Direct callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:prepare_signal
```
**Symbols:**

```
ffffffff8109e1b0-ffffffff8109e1ff: ptrace_trap_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void ptrace_trap_notify(struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a64b0)
Location: kernel/signal.c:864
Inline: True
Direct callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:prepare_signal
```
**Symbols:**

```
ffffffff810a64b0-ffffffff810a64ff: ptrace_trap_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void ptrace_trap_notify(struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ab190)
Location: kernel/signal.c:875
Inline: True
Direct callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:prepare_signal
```
**Symbols:**

```
ffffffff810ab190-ffffffff810ab1ef: ptrace_trap_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void ptrace_trap_notify(struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b1790)
Location: kernel/signal.c:880
Inline: True
Direct callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:prepare_signal
```
**Symbols:**

```
ffffffff810b1790-ffffffff810b17ef: ptrace_trap_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ptrace_trap_notify(struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b8e20)
Location: kernel/signal.c:880
Inline: False
Direct callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:prepare_signal
```
**Symbols:**

```
ffffffff810b8e20-ffffffff810b8eb3: ptrace_trap_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ptrace_trap_notify(struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b40d0)
Location: kernel/signal.c:881
Inline: False
Direct callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:prepare_signal
```
**Symbols:**

```
ffffffff810b40d0-ffffffff810b4163: ptrace_trap_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ptrace_trap_notify(struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b4f30)
Location: kernel/signal.c:880
Inline: False
Direct callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:prepare_signal
```
**Symbols:**

```
ffffffff810b4f30-ffffffff810b4fc0: ptrace_trap_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ptrace_trap_notify(struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810c6ff0)
Location: kernel/signal.c:881
Inline: False
Direct callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:prepare_signal
```
**Symbols:**

```
ffffffff810c6ff0-ffffffff810c7080: ptrace_trap_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ptrace_trap_notify(struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810dee70)
Location: kernel/signal.c:887
Inline: False
Direct callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:prepare_signal
```
**Symbols:**

```
ffffffff810dee70-ffffffff810def13: ptrace_trap_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ptrace_trap_notify(struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ff460)
Location: kernel/signal.c:887
Inline: False
Direct callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:prepare_signal
```
**Symbols:**

```
ffffffff810ff460-ffffffff810ff503: ptrace_trap_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ptrace_trap_notify(struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8110b4b0)
Location: kernel/signal.c:892
Inline: False
Direct callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:prepare_signal
```
**Symbols:**

```
ffffffff8110b4b0-ffffffff8110b553: ptrace_trap_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ptrace_trap_notify(struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81114e60)
Location: kernel/signal.c:883
Inline: False
Direct callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:prepare_signal
```
**Symbols:**

```
ffffffff81114e60-ffffffff81114f03: ptrace_trap_notify (STB_LOCAL)
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
void ptrace_trap_notify(struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff80001010d428)
Location: kernel/signal.c:880
Inline: True
Direct callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:prepare_signal
```
**Symbols:**

```
ffff80001010d428-ffff80001010d494: ptrace_trap_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void ptrace_trap_notify(struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0365720)
Location: kernel/signal.c:880
Inline: True
Direct callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:prepare_signal
```
**Symbols:**

```
c0365720-c03657b4: ptrace_trap_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ptrace_trap_notify(struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0000000001545d0)
Location: kernel/signal.c:880
Inline: False
Direct callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:prepare_signal
```
**Symbols:**

```
c0000000001545d0-c000000000154658: ptrace_trap_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void ptrace_trap_notify(struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000ce6be)
Location: kernel/signal.c:880
Inline: True
Direct callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:prepare_signal
```
**Symbols:**

```
ffffffe0000ce6be-ffffffe0000ce720: ptrace_trap_notify (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void ptrace_trap_notify(struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810abb00)
Location: kernel/signal.c:880
Inline: True
Direct callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:prepare_signal
```
**Symbols:**

```
ffffffff810abb00-ffffffff810abb5f: ptrace_trap_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void ptrace_trap_notify(struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109a490)
Location: kernel/signal.c:880
Inline: True
Direct callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:prepare_signal
```
**Symbols:**

```
ffffffff8109a490-ffffffff8109a4ef: ptrace_trap_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void ptrace_trap_notify(struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ab060)
Location: kernel/signal.c:880
Inline: True
Direct callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:prepare_signal
```
**Symbols:**

```
ffffffff810ab060-ffffffff810ab0bf: ptrace_trap_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void ptrace_trap_notify(struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b3140)
Location: kernel/signal.c:880
Inline: True
Direct callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:prepare_signal
```
**Symbols:**

```
ffffffff810b3140-ffffffff810b319f: ptrace_trap_notify (STB_LOCAL)
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
