# Function: <code>__sigqueue_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct sigqueue *__sigqueue_alloc(int sig, struct task_struct *t, gfp_t flags, int override_rlimit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8108cd70)
Location: kernel/signal.c:361
Inline: False
Direct callers:
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
  - kernel/signal.c:sigqueue_alloc
```
**Symbols:**

```
ffffffff8108cd70-ffffffff8108ce35: __sigqueue_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct sigqueue *__sigqueue_alloc(int sig, struct task_struct *t, gfp_t flags, int override_rlimit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8108ff40)
Location: kernel/signal.c:361
Inline: False
Direct callers:
  - kernel/signal.c:sigqueue_alloc
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
```
**Symbols:**

```
ffffffff8108ff40-ffffffff81090005: __sigqueue_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct sigqueue *__sigqueue_alloc(int sig, struct task_struct *t, gfp_t flags, int override_rlimit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81094ec0)
Location: kernel/signal.c:361
Inline: False
Direct callers:
  - kernel/signal.c:sigqueue_alloc
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
```
**Symbols:**

```
ffffffff81094ec0-ffffffff81094f85: __sigqueue_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sigqueue *__sigqueue_alloc(int sig, struct task_struct *t, gfp_t flags, int override_rlimit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81091f50)
Location: kernel/signal.c:367
Inline: False
Direct callers:
  - kernel/signal.c:sigqueue_alloc
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
```
**Symbols:**

```
ffffffff81091f50-ffffffff81092015: __sigqueue_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sigqueue *__sigqueue_alloc(int sig, struct task_struct *t, gfp_t flags, int override_rlimit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81098de0)
Location: kernel/signal.c:369
Inline: False
Direct callers:
  - kernel/signal.c:sigqueue_alloc
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
```
**Symbols:**

```
ffffffff81098de0-ffffffff81098ea5: __sigqueue_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct sigqueue *__sigqueue_alloc(int sig, struct task_struct *t, gfp_t flags, int override_rlimit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:371
Inline: False
Direct callers:
  - kernel/signal.c:sigqueue_alloc
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
```
**Symbols:**

```
ffffffff8109c5d0-ffffffff8109c671: __sigqueue_alloc (STB_LOCAL)
ffffffff810a2e64-ffffffff810a2e8e: __sigqueue_alloc.cold.53 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct sigqueue *__sigqueue_alloc(int sig, struct task_struct *t, gfp_t flags, int override_rlimit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:402
Inline: False
Direct callers:
  - kernel/signal.c:sigqueue_alloc
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
```
**Symbols:**

```
ffffffff810a4830-ffffffff810a48d6: __sigqueue_alloc (STB_LOCAL)
ffffffff810aba64-ffffffff810aba8e: __sigqueue_alloc.cold.58 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct sigqueue *__sigqueue_alloc(int sig, struct task_struct *t, gfp_t flags, int override_rlimit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:412
Inline: False
Direct callers:
  - kernel/signal.c:sigqueue_alloc
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
```
**Symbols:**

```
ffffffff810a94b0-ffffffff810a9565: __sigqueue_alloc (STB_LOCAL)
ffffffff810b0f45-ffffffff810b0f6f: __sigqueue_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct sigqueue *__sigqueue_alloc(int sig, struct task_struct *t, gfp_t flags, int override_rlimit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:412
Inline: False
Direct callers:
  - kernel/signal.c:sigqueue_alloc
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
```
**Symbols:**

```
ffffffff810afa80-ffffffff810afb52: __sigqueue_alloc (STB_LOCAL)
ffffffff810b7695-ffffffff810b76bf: __sigqueue_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct sigqueue *__sigqueue_alloc(int sig, struct task_struct *t, gfp_t flags, int override_rlimit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:412
Inline: False
Direct callers:
  - kernel/signal.c:sigqueue_alloc
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
```
**Symbols:**

```
ffffffff810b78d0-ffffffff810b79ea: __sigqueue_alloc (STB_LOCAL)
ffffffff810bf5e5-ffffffff810bf60f: __sigqueue_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct sigqueue *__sigqueue_alloc(int sig, struct task_struct *t, gfp_t flags, int override_rlimit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:413
Inline: False
Direct callers:
  - kernel/signal.c:sigqueue_alloc
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
```
**Symbols:**

```
ffffffff810b2b60-ffffffff810b2c71: __sigqueue_alloc (STB_LOCAL)
ffffffff81bdba3c-ffffffff81bdba66: __sigqueue_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct sigqueue *__sigqueue_alloc(int sig, struct task_struct *t, gfp_t gfp_flags, int override_rlimit, const unsigned int sigqueue_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:411
Inline: False
Direct callers:
  - kernel/signal.c:sigqueue_alloc
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
```
**Symbols:**

```
ffffffff810b41a0-ffffffff810b42b0: __sigqueue_alloc (STB_LOCAL)
ffffffff81bcdaec-ffffffff81bcdb16: __sigqueue_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct sigqueue *__sigqueue_alloc(int sig, struct task_struct *t, gfp_t gfp_flags, int override_rlimit, const unsigned int sigqueue_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:412
Inline: False
Direct callers:
  - kernel/signal.c:sigqueue_alloc
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
```
**Symbols:**

```
ffffffff810c6270-ffffffff810c6359: __sigqueue_alloc (STB_LOCAL)
ffffffff81ca45d3-ffffffff81ca45fd: __sigqueue_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct sigqueue *__sigqueue_alloc(int sig, struct task_struct *t, gfp_t gfp_flags, int override_rlimit, const unsigned int sigqueue_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:412
Inline: False
Direct callers:
  - kernel/signal.c:sigqueue_alloc
  - kernel/signal.c:__send_signal_locked
  - kernel/signal.c:__send_signal_locked
```
**Symbols:**

```
ffffffff810dda70-ffffffff810ddb79: __sigqueue_alloc (STB_LOCAL)
ffffffff81e53e56-ffffffff81e53e80: __sigqueue_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sigqueue *__sigqueue_alloc(int sig, struct task_struct *t, gfp_t gfp_flags, int override_rlimit, const unsigned int sigqueue_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810fdba0)
Location: kernel/signal.c:412
Inline: False
Direct callers:
  - kernel/signal.c:sigqueue_alloc
  - kernel/signal.c:__send_signal_locked
  - kernel/signal.c:__send_signal_locked
```
**Symbols:**

```
ffffffff810fdba0-ffffffff810fdcca: __sigqueue_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sigqueue *__sigqueue_alloc(int sig, struct task_struct *t, gfp_t gfp_flags, int override_rlimit, const unsigned int sigqueue_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81109c10)
Location: kernel/signal.c:413
Inline: False
Direct callers:
  - kernel/signal.c:sigqueue_alloc
  - kernel/signal.c:__send_signal_locked
  - kernel/signal.c:__send_signal_locked
  - kernel/signal.c:__send_signal_locked
```
**Symbols:**

```
ffffffff81109c10-ffffffff81109d3a: __sigqueue_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sigqueue *__sigqueue_alloc(int sig, struct task_struct *t, gfp_t gfp_flags, int override_rlimit, const unsigned int sigqueue_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff811135b0)
Location: kernel/signal.c:404
Inline: False
Direct callers:
  - kernel/signal.c:sigqueue_alloc
  - kernel/signal.c:__send_signal_locked
  - kernel/signal.c:__send_signal_locked
  - kernel/signal.c:__send_signal_locked
```
**Symbols:**

```
ffffffff811135b0-ffffffff811136da: __sigqueue_alloc (STB_LOCAL)
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
struct sigqueue *__sigqueue_alloc(int sig, struct task_struct *t, gfp_t flags, int override_rlimit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff80001010b420)
Location: kernel/signal.c:412
Inline: False
Direct callers:
  - kernel/signal.c:sigqueue_alloc
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
```
**Symbols:**

```
ffff80001010b420-ffff80001010b57c: __sigqueue_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sigqueue *__sigqueue_alloc(int sig, struct task_struct *t, gfp_t flags, int override_rlimit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0363d00)
Location: kernel/signal.c:412
Inline: False
Direct callers:
  - kernel/signal.c:sigqueue_alloc
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
```
**Symbols:**

```
c0363d00-c0363e4c: __sigqueue_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sigqueue *__sigqueue_alloc(int sig, struct task_struct *t, gfp_t flags, int override_rlimit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000151f40)
Location: kernel/signal.c:412
Inline: False
Direct callers:
  - kernel/signal.c:sigqueue_alloc
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
```
**Symbols:**

```
c000000000151f40-c0000000001520e0: __sigqueue_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sigqueue *__sigqueue_alloc(int sig, struct task_struct *t, gfp_t flags, int override_rlimit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000cd49c)
Location: kernel/signal.c:412
Inline: False
Direct callers:
  - kernel/signal.c:sigqueue_alloc
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
```
**Symbols:**

```
ffffffe0000cd49c-ffffffe0000cd586: __sigqueue_alloc (STB_LOCAL)
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
struct sigqueue *__sigqueue_alloc(int sig, struct task_struct *t, gfp_t flags, int override_rlimit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:412
Inline: False
Direct callers:
  - kernel/signal.c:sigqueue_alloc
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
```
**Symbols:**

```
ffffffff810a9df0-ffffffff810a9ec2: __sigqueue_alloc (STB_LOCAL)
ffffffff810b1a05-ffffffff810b1a2f: __sigqueue_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct sigqueue *__sigqueue_alloc(int sig, struct task_struct *t, gfp_t flags, int override_rlimit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:412
Inline: False
Direct callers:
  - kernel/signal.c:sigqueue_alloc
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
```
**Symbols:**

```
ffffffff810987a0-ffffffff81098872: __sigqueue_alloc (STB_LOCAL)
ffffffff810a0325-ffffffff810a034f: __sigqueue_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct sigqueue *__sigqueue_alloc(int sig, struct task_struct *t, gfp_t flags, int override_rlimit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:412
Inline: False
Direct callers:
  - kernel/signal.c:sigqueue_alloc
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
```
**Symbols:**

```
ffffffff810a9350-ffffffff810a9422: __sigqueue_alloc (STB_LOCAL)
ffffffff810b0f65-ffffffff810b0f8f: __sigqueue_alloc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct sigqueue *__sigqueue_alloc(int sig, struct task_struct *t, gfp_t flags, int override_rlimit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:412
Inline: False
Direct callers:
  - kernel/signal.c:sigqueue_alloc
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
```
**Symbols:**

```
ffffffff810b1560-ffffffff810b164c: __sigqueue_alloc (STB_LOCAL)
ffffffff810b923d-ffffffff810b9267: __sigqueue_alloc.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>gfp_t gfp_flags</code>
</li>
<li>
<b>Param added. </b>
<code>const unsigned int sigqueue_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>gfp_t flags</code>
</li>
</ul>
</details>
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
