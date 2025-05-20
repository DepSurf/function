# Function: <code>ptrace_stop</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ptrace_stop(int exit_code, int why, int clear_code, siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8108ea70)
Location: kernel/signal.c:1777
Inline: False
Direct callers:
  - kernel/signal.c:ptrace_do_notify
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
```
**Symbols:**

```
ffffffff8108ea70-ffffffff8108ed0c: ptrace_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ptrace_stop(int exit_code, int why, int clear_code, siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81091af0)
Location: kernel/signal.c:1777
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
```
**Symbols:**

```
ffffffff81091af0-ffffffff81091d8c: ptrace_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ptrace_stop(int exit_code, int why, int clear_code, siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81096a80)
Location: kernel/signal.c:1783
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
```
**Symbols:**

```
ffffffff81096a80-ffffffff81096d11: ptrace_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ptrace_stop(int exit_code, int why, int clear_code, siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81093d90)
Location: kernel/signal.c:1805
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
```
**Symbols:**

```
ffffffff81093d90-ffffffff8109402b: ptrace_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ptrace_stop(int exit_code, int why, int clear_code, siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109ac70)
Location: kernel/signal.c:1806
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
```
**Symbols:**

```
ffffffff8109ac70-ffffffff8109aecf: ptrace_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ptrace_stop(int exit_code, int why, int clear_code, siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109ebb0)
Location: kernel/signal.c:1925
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
```
**Symbols:**

```
ffffffff8109ebb0-ffffffff8109ee18: ptrace_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ptrace_stop(int exit_code, int why, int clear_code, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a6e90)
Location: kernel/signal.c:2015
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
```
**Symbols:**

```
ffffffff810a6e90-ffffffff810a70f8: ptrace_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ptrace_stop(int exit_code, int why, int clear_code, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810acf40)
Location: kernel/signal.c:2115
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
```
**Symbols:**

```
ffffffff810acf40-ffffffff810ad1d1: ptrace_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ptrace_stop(int exit_code, int why, int clear_code, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b3560)
Location: kernel/signal.c:2120
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
```
**Symbols:**

```
ffffffff810b3560-ffffffff810b37f1: ptrace_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ptrace_stop(int exit_code, int why, int clear_code, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810bbf80)
Location: kernel/signal.c:2120
Inline: False
Direct callers:
  - kernel/signal.c:ptrace_signal
  - kernel/signal.c:do_jobctl_trap
  - kernel/signal.c:ptrace_do_notify
```
**Symbols:**

```
ffffffff810bbf80-ffffffff810bc239: ptrace_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ptrace_stop(int exit_code, int why, int clear_code, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b7270)
Location: kernel/signal.c:2121
Inline: False
Direct callers:
  - kernel/signal.c:ptrace_signal
  - kernel/signal.c:do_jobctl_trap
  - kernel/signal.c:ptrace_do_notify
```
**Symbols:**

```
ffffffff810b7270-ffffffff810b7529: ptrace_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ptrace_stop(int exit_code, int why, int clear_code, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b8870)
Location: kernel/signal.c:2133
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
```
**Symbols:**

```
ffffffff810b8870-ffffffff810b8b29: ptrace_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ptrace_stop(int exit_code, int why, int clear_code, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810cad60)
Location: kernel/signal.c:2216
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
```
**Symbols:**

```
ffffffff810cad60-ffffffff810cb0b7: ptrace_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/signal.c (ffffffff810e54df)
Location: kernel/signal.c:2205
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_signal
  - kernel/signal.c:ptrace_do_notify
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_signal
  - kernel/signal.c:ptrace_do_notify
```
**Symbols:**

```
ffffffff810e41f0-ffffffff810e4512: ptrace_stop.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/signal.c (ffffffff81105b2f)
Location: kernel/signal.c:2206
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_signal
  - kernel/signal.c:ptrace_do_notify
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_signal
  - kernel/signal.c:ptrace_do_notify
```
**Symbols:**

```
ffffffff81104880-ffffffff81104b56: ptrace_stop.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/signal.c (ffffffff81111dc1)
Location: kernel/signal.c:2228
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_signal
  - kernel/signal.c:ptrace_do_notify
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_signal
  - kernel/signal.c:ptrace_do_notify
```
**Symbols:**

```
ffffffff81110b00-ffffffff81110dd6: ptrace_stop.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/signal.c (ffffffff8111b761)
Location: kernel/signal.c:2219
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_signal
  - kernel/signal.c:ptrace_do_notify
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_signal
  - kernel/signal.c:ptrace_do_notify
```
**Symbols:**

```
ffffffff8111a470-ffffffff8111a746: ptrace_stop.part.0 (STB_LOCAL)
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
void ptrace_stop(int exit_code, int why, int clear_code, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff80001010f3e8)
Location: kernel/signal.c:2120
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
```
**Symbols:**

```
ffff80001010f3e8-ffff80001010f730: ptrace_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ptrace_stop(int exit_code, int why, int clear_code, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c03670cc)
Location: kernel/signal.c:2120
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
```
**Symbols:**

```
c03670cc-c0367470: ptrace_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ptrace_stop(int exit_code, int why, int clear_code, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0000000001568d0)
Location: kernel/signal.c:2120
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
```
**Symbols:**

```
c0000000001568d0-c000000000156c34: ptrace_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ptrace_stop(int exit_code, int why, int clear_code, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000cf8f4)
Location: kernel/signal.c:2120
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
```
**Symbols:**

```
ffffffe0000cf8f4-ffffffe0000cfb96: ptrace_stop (STB_LOCAL)
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
void ptrace_stop(int exit_code, int why, int clear_code, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ad8d0)
Location: kernel/signal.c:2120
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
```
**Symbols:**

```
ffffffff810ad8d0-ffffffff810adb61: ptrace_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ptrace_stop(int exit_code, int why, int clear_code, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109c250)
Location: kernel/signal.c:2120
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
```
**Symbols:**

```
ffffffff8109c250-ffffffff8109c4db: ptrace_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ptrace_stop(int exit_code, int why, int clear_code, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ace30)
Location: kernel/signal.c:2120
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
```
**Symbols:**

```
ffffffff810ace30-ffffffff810ad0c1: ptrace_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ptrace_stop(int exit_code, int why, int clear_code, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b5000)
Location: kernel/signal.c:2120
Inline: False
Direct callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:ptrace_do_notify
```
**Symbols:**

```
ffffffff810b5000-ffffffff810b528f: ptrace_stop (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>siginfo_t *info</code> ➡️ <code>kernel_siginfo_t *info</code>
</li>
</ul>
</details>
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
