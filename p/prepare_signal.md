# Function: <code>prepare_signal</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool prepare_signal(int sig, struct task_struct *p, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8108e160)
Location: kernel/signal.c:784
Inline: False
Direct callers:
  - kernel/signal.c:__send_signal
  - kernel/signal.c:send_sigqueue
```
**Symbols:**

```
ffffffff8108e160-ffffffff8108e3d1: prepare_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool prepare_signal(int sig, struct task_struct *p, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810911e0)
Location: kernel/signal.c:784
Inline: False
Direct callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
**Symbols:**

```
ffffffff810911e0-ffffffff81091454: prepare_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool prepare_signal(int sig, struct task_struct *p, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81096150)
Location: kernel/signal.c:790
Inline: False
Direct callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
**Symbols:**

```
ffffffff81096150-ffffffff810963e2: prepare_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool prepare_signal(int sig, struct task_struct *p, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81093420)
Location: kernel/signal.c:804
Inline: False
Direct callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
**Symbols:**

```
ffffffff81093420-ffffffff810936ba: prepare_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool prepare_signal(int sig, struct task_struct *p, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109a2e0)
Location: kernel/signal.c:806
Inline: False
Direct callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
**Symbols:**

```
ffffffff8109a2e0-ffffffff8109a5a9: prepare_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool prepare_signal(int sig, struct task_struct *p, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109e200)
Location: kernel/signal.c:812
Inline: False
Direct callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
**Symbols:**

```
ffffffff8109e200-ffffffff8109e4b7: prepare_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool prepare_signal(int sig, struct task_struct *p, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a6500)
Location: kernel/signal.c:883
Inline: False
Direct callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
**Symbols:**

```
ffffffff810a6500-ffffffff810a67dd: prepare_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
bool prepare_signal(int sig, struct task_struct *p, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:894
Inline: False
Direct callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
**Symbols:**

```
ffffffff810ab1f0-ffffffff810ab506: prepare_signal (STB_LOCAL)
ffffffff810b0f85-ffffffff810b0f9c: prepare_signal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool prepare_signal(int sig, struct task_struct *p, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b17f0)
Location: kernel/signal.c:899
Inline: False
Direct callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
**Symbols:**

```
ffffffff810b17f0-ffffffff810b1b1f: prepare_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool prepare_signal(int sig, struct task_struct *p, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b9e00)
Location: kernel/signal.c:899
Inline: False
Direct callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
**Symbols:**

```
ffffffff810b9e00-ffffffff810ba12b: prepare_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool prepare_signal(int sig, struct task_struct *p, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b50b0)
Location: kernel/signal.c:900
Inline: False
Direct callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
**Symbols:**

```
ffffffff810b50b0-ffffffff810b53db: prepare_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool prepare_signal(int sig, struct task_struct *p, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b6ca0)
Location: kernel/signal.c:899
Inline: False
Direct callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
**Symbols:**

```
ffffffff810b6ca0-ffffffff810b6fcb: prepare_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool prepare_signal(int sig, struct task_struct *p, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:900
Inline: False
Direct callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
**Symbols:**

```
ffffffff810c7080-ffffffff810c740b: prepare_signal (STB_LOCAL)
ffffffff81ca466e-ffffffff81ca46bd: prepare_signal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool prepare_signal(int sig, struct task_struct *p, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:906
Inline: False
Direct callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal_locked
```
**Symbols:**

```
ffffffff810df580-ffffffff810df990: prepare_signal (STB_LOCAL)
ffffffff81e53f12-ffffffff81e53f82: prepare_signal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool prepare_signal(int sig, struct task_struct *p, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:906
Inline: False
Direct callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal_locked
```
**Symbols:**

```
ffffffff810ff8e0-ffffffff810ffca7: prepare_signal (STB_LOCAL)
ffffffff82055fde-ffffffff8205603b: prepare_signal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool prepare_signal(int sig, struct task_struct *p, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:911
Inline: False
Direct callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal_locked
```
**Symbols:**

```
ffffffff8110b920-ffffffff8110bd3a: prepare_signal (STB_LOCAL)
ffffffff820d45b9-ffffffff820d45e5: prepare_signal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool prepare_signal(int sig, struct task_struct *p, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:902
Inline: False
Direct callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal_locked
```
**Symbols:**

```
ffffffff811152d0-ffffffff811156ea: prepare_signal (STB_LOCAL)
ffffffff821af4b2-ffffffff821af4de: prepare_signal.cold (STB_LOCAL)
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
bool prepare_signal(int sig, struct task_struct *p, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff80001010d498)
Location: kernel/signal.c:899
Inline: False
Direct callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
**Symbols:**

```
ffff80001010d498-ffff80001010d774: prepare_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool prepare_signal(int sig, struct task_struct *p, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c03657b4)
Location: kernel/signal.c:899
Inline: False
Direct callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
**Symbols:**

```
c03657b4-c0365b04: prepare_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool prepare_signal(int sig, struct task_struct *p, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000154660)
Location: kernel/signal.c:899
Inline: False
Direct callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
**Symbols:**

```
c000000000154660-c000000000154a14: prepare_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool prepare_signal(int sig, struct task_struct *p, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000ce720)
Location: kernel/signal.c:899
Inline: False
Direct callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
**Symbols:**

```
ffffffe0000ce720-ffffffe0000ce99c: prepare_signal (STB_LOCAL)
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
bool prepare_signal(int sig, struct task_struct *p, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810abb60)
Location: kernel/signal.c:899
Inline: False
Direct callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
**Symbols:**

```
ffffffff810abb60-ffffffff810abe8f: prepare_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool prepare_signal(int sig, struct task_struct *p, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109a4f0)
Location: kernel/signal.c:899
Inline: False
Direct callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
**Symbols:**

```
ffffffff8109a4f0-ffffffff8109a81f: prepare_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool prepare_signal(int sig, struct task_struct *p, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ab0c0)
Location: kernel/signal.c:899
Inline: False
Direct callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
**Symbols:**

```
ffffffff810ab0c0-ffffffff810ab3ef: prepare_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool prepare_signal(int sig, struct task_struct *p, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b31a0)
Location: kernel/signal.c:899
Inline: False
Direct callers:
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:__send_signal
```
**Symbols:**

```
ffffffff810b31a0-ffffffff810b34cf: prepare_signal (STB_LOCAL)
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
