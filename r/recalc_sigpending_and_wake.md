# Function: <code>recalc_sigpending_and_wake</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void recalc_sigpending_and_wake(struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8108dda0)
Location: kernel/signal.c:152
Inline: False
Direct callers:
  - kernel/signal.c:force_sig_info
```
**Symbols:**

```
ffffffff8108dda0-ffffffff8108ddc3: recalc_sigpending_and_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void recalc_sigpending_and_wake(struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81090e20)
Location: kernel/signal.c:152
Inline: False
Direct callers:
  - kernel/signal.c:force_sig_info
```
**Symbols:**

```
ffffffff81090e20-ffffffff81090e43: recalc_sigpending_and_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void recalc_sigpending_and_wake(struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81095da0)
Location: kernel/signal.c:152
Inline: False
Direct callers:
  - kernel/signal.c:force_sig_info
```
**Symbols:**

```
ffffffff81095da0-ffffffff81095dc3: recalc_sigpending_and_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void recalc_sigpending_and_wake(struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81092d50)
Location: kernel/signal.c:158
Inline: False
Direct callers:
  - kernel/signal.c:force_sig_info
```
**Symbols:**

```
ffffffff81092d50-ffffffff81092d73: recalc_sigpending_and_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void recalc_sigpending_and_wake(struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81099c30)
Location: kernel/signal.c:160
Inline: False
Direct callers:
  - kernel/signal.c:force_sig_info
```
**Symbols:**

```
ffffffff81099c30-ffffffff81099c53: recalc_sigpending_and_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void recalc_sigpending_and_wake(struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109dc00)
Location: kernel/signal.c:161
Inline: False
Direct callers:
  - kernel/signal.c:force_sig_info
```
**Symbols:**

```
ffffffff8109dc00-ffffffff8109dc26: recalc_sigpending_and_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void recalc_sigpending_and_wake(struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a5f10)
Location: kernel/signal.c:166
Inline: False
Direct callers:
  - kernel/signal.c:force_sig_info
```
**Symbols:**

```
ffffffff810a5f10-ffffffff810a5f36: recalc_sigpending_and_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void recalc_sigpending_and_wake(struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aabe0)
Location: kernel/signal.c:176
Inline: False
Direct callers:
  - kernel/signal.c:force_sig_info_to_task
```
**Symbols:**

```
ffffffff810aabe0-ffffffff810aac09: recalc_sigpending_and_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void recalc_sigpending_and_wake(struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b11e0)
Location: kernel/signal.c:176
Inline: False
Direct callers:
  - kernel/signal.c:force_sig_info_to_task
```
**Symbols:**

```
ffffffff810b11e0-ffffffff810b1209: recalc_sigpending_and_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void recalc_sigpending_and_wake(struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810bd711)
Location: kernel/signal.c:176
Inline: True
Inline callers:
  - kernel/signal.c:force_sig_info_to_task
```
**Symbols:**

```
ffffffff810b9950-ffffffff810b99c8: recalc_sigpending_and_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void recalc_sigpending_and_wake(struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b8a21)
Location: kernel/signal.c:176
Inline: True
Inline callers:
  - kernel/signal.c:force_sig_info_to_task
```
**Symbols:**

```
ffffffff810b4c00-ffffffff810b4c78: recalc_sigpending_and_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void recalc_sigpending_and_wake(struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b9fa0)
Location: kernel/signal.c:175
Inline: True
Inline callers:
  - kernel/signal.c:force_sig_info_to_task
```
**Symbols:**

```
ffffffff810b6810-ffffffff810b6888: recalc_sigpending_and_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void recalc_sigpending_and_wake(struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810cc5f3)
Location: kernel/signal.c:176
Inline: True
Inline callers:
  - kernel/signal.c:force_sig_info_to_task
```
**Symbols:**

```
ffffffff810c96a0-ffffffff810c9718: recalc_sigpending_and_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void recalc_sigpending_and_wake(struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810e3898)
Location: kernel/signal.c:176
Inline: True
Inline callers:
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:force_sig_info_to_task
```
**Symbols:**

```
ffffffff810e1090-ffffffff810e111b: recalc_sigpending_and_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void recalc_sigpending_and_wake(struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81103e38)
Location: kernel/signal.c:176
Inline: True
Inline callers:
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:force_sig_info_to_task
```
**Symbols:**

```
ffffffff81101290-ffffffff8110131b: recalc_sigpending_and_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void recalc_sigpending_and_wake(struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81110085)
Location: kernel/signal.c:177
Inline: True
Inline callers:
  - kernel/signal.c:force_sig_info_to_task
  - kernel/signal.c:force_sig_info_to_task
```
**Symbols:**

```
ffffffff8110d3f0-ffffffff8110d47b: recalc_sigpending_and_wake (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void recalc_sigpending_and_wake(struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff80001010ce18)
Location: kernel/signal.c:176
Inline: False
Direct callers:
  - kernel/signal.c:force_sig_info_to_task
```
**Symbols:**

```
ffff80001010ce18-ffff80001010ce64: recalc_sigpending_and_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void recalc_sigpending_and_wake(struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c036506c)
Location: kernel/signal.c:176
Inline: False
Direct callers:
  - kernel/signal.c:force_sig_info_to_task
```
**Symbols:**

```
c036506c-c03650a0: recalc_sigpending_and_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void recalc_sigpending_and_wake(struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000153d80)
Location: kernel/signal.c:176
Inline: False
Direct callers:
  - kernel/signal.c:force_sig_info_to_task
```
**Symbols:**

```
c000000000153d80-c000000000153dec: recalc_sigpending_and_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void recalc_sigpending_and_wake(struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000ce3aa)
Location: kernel/signal.c:176
Inline: False
Direct callers:
  - kernel/signal.c:force_sig_info_to_task
```
**Symbols:**

```
ffffffe0000ce3aa-ffffffe0000ce40c: recalc_sigpending_and_wake (STB_GLOBAL)
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
void recalc_sigpending_and_wake(struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ab550)
Location: kernel/signal.c:176
Inline: False
Direct callers:
  - kernel/signal.c:force_sig_info_to_task
```
**Symbols:**

```
ffffffff810ab550-ffffffff810ab579: recalc_sigpending_and_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void recalc_sigpending_and_wake(struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81099ef0)
Location: kernel/signal.c:176
Inline: False
Direct callers:
  - kernel/signal.c:force_sig_info_to_task
```
**Symbols:**

```
ffffffff81099ef0-ffffffff81099f19: recalc_sigpending_and_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void recalc_sigpending_and_wake(struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aaab0)
Location: kernel/signal.c:176
Inline: False
Direct callers:
  - kernel/signal.c:force_sig_info_to_task
```
**Symbols:**

```
ffffffff810aaab0-ffffffff810aaad9: recalc_sigpending_and_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void recalc_sigpending_and_wake(struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b2b90)
Location: kernel/signal.c:176
Inline: False
Direct callers:
  - kernel/signal.c:force_sig_info_to_task
```
**Symbols:**

```
ffffffff810b2b90-ffffffff810b2bb9: recalc_sigpending_and_wake (STB_GLOBAL)
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
