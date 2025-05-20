# Function: <code>ptrace_signal</code>

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
In kernel/signal.c (ffffffff8109056e)
Location: kernel/signal.c:2082
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
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
In kernel/signal.c (ffffffff810935d5)
Location: kernel/signal.c:2082
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
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
In kernel/signal.c (ffffffff81098565)
Location: kernel/signal.c:2088
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81095862)
Location: kernel/signal.c:2110
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109c6c6)
Location: kernel/signal.c:2111
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a0aad)
Location: kernel/signal.c:2243
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a8fc5)
Location: kernel/signal.c:2333
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aed2c)
Location: kernel/signal.c:2473
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b5343)
Location: kernel/signal.c:2478
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ptrace_signal(int signr, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810bdc10)
Location: kernel/signal.c:2478
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
```
**Symbols:**

```
ffffffff810bdc10-ffffffff810bdd10: ptrace_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ptrace_signal(int signr, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b8f20)
Location: kernel/signal.c:2479
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
```
**Symbols:**

```
ffffffff810b8f20-ffffffff810b9038: ptrace_signal (STB_LOCAL)
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
In kernel/signal.c (ffffffff810bab0f)
Location: kernel/signal.c:2491
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
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
In kernel/signal.c (ffffffff810cd3b2)
Location: kernel/signal.c:2573
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ptrace_signal(int signr, kernel_siginfo_t *info, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:2558
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
```
**Symbols:**

```
ffffffff810e4c60-ffffffff810e4dc2: ptrace_signal (STB_LOCAL)
ffffffff81e541b1-ffffffff81e541c5: ptrace_signal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ptrace_signal(int signr, kernel_siginfo_t *info, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:2559
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
```
**Symbols:**

```
ffffffff811052c0-ffffffff81105422: ptrace_signal (STB_LOCAL)
ffffffff8205626a-ffffffff8205627e: ptrace_signal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ptrace_signal(int signr, kernel_siginfo_t *info, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:2581
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
```
**Symbols:**

```
ffffffff81111550-ffffffff811116b1: ptrace_signal (STB_LOCAL)
ffffffff820d47f1-ffffffff820d4802: ptrace_signal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ptrace_signal(int signr, kernel_siginfo_t *info, enum pid_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:2593
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
```
**Symbols:**

```
ffffffff8111aef0-ffffffff8111b051: ptrace_signal (STB_LOCAL)
ffffffff821af6da-ffffffff821af6eb: ptrace_signal.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff800010111524)
Location: kernel/signal.c:2478
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0368ba4)
Location: kernel/signal.c:2478
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000158f00)
Location: kernel/signal.c:2478
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000d0e44)
Location: kernel/signal.c:2478
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810af6b3)
Location: kernel/signal.c:2478
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109dfeb)
Location: kernel/signal.c:2478
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aec13)
Location: kernel/signal.c:2478
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b6eed)
Location: kernel/signal.c:2478
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
