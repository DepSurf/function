# Function: <code>klp_update_patch_state</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void klp_update_patch_state(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff810f8e00)
Location: kernel/livepatch/transition.c:159
Inline: False
Direct callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
ffffffff810f8e00-ffffffff810f8e1e: klp_update_patch_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void klp_update_patch_state(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff81103820)
Location: kernel/livepatch/transition.c:184
Inline: False
Direct callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
ffffffff81103820-ffffffff8110383e: klp_update_patch_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void klp_update_patch_state(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff8110c558)
Location: kernel/livepatch/transition.c:175
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_force_transition
Direct callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
ffffffff8110bdc0-ffffffff8110bddf: klp_update_patch_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void klp_update_patch_state(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff81117d48)
Location: kernel/livepatch/transition.c:175
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_force_transition
Direct callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
ffffffff811175b0-ffffffff811175cf: klp_update_patch_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void klp_update_patch_state(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff81122089)
Location: kernel/livepatch/transition.c:163
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_force_transition
Direct callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
ffffffff81121850-ffffffff8112186f: klp_update_patch_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void klp_update_patch_state(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff8112e6a9)
Location: kernel/livepatch/transition.c:163
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_force_transition
Direct callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
ffffffff8112de70-ffffffff8112de8f: klp_update_patch_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void klp_update_patch_state(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff8113c850)
Location: kernel/livepatch/transition.c:163
Inline: False
Direct callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
  - kernel/sched/idle.c:do_idle
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_force_transition
```
**Symbols:**

```
ffffffff8113c850-ffffffff8113c86f: klp_update_patch_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void klp_update_patch_state(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff81136f60)
Location: kernel/livepatch/transition.c:163
Inline: False
Direct callers:
  - kernel/sched/idle.c:do_idle
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/entry/common.c:exit_to_user_mode_loop
```
**Symbols:**

```
ffffffff81136f60-ffffffff81136f7f: klp_update_patch_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void klp_update_patch_state(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff81137c30)
Location: kernel/livepatch/transition.c:164
Inline: False
Direct callers:
  - kernel/sched/idle.c:do_idle
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/entry/common.c:exit_to_user_mode_loop
```
**Symbols:**

```
ffffffff81137c30-ffffffff81137c4f: klp_update_patch_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void klp_update_patch_state(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff8115a980)
Location: kernel/livepatch/transition.c:164
Inline: False
Direct callers:
  - kernel/sched/idle.c:do_idle
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/entry/common.c:exit_to_user_mode_loop
```
**Symbols:**

```
ffffffff8115a980-ffffffff8115a99f: klp_update_patch_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void klp_update_patch_state(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff81184230)
Location: kernel/livepatch/transition.c:162
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:do_idle
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/entry/common.c:exit_to_user_mode_loop
```
**Symbols:**

```
ffffffff81184230-ffffffff81184275: klp_update_patch_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void klp_update_patch_state(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff811bf4c0)
Location: kernel/livepatch/transition.c:162
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:do_idle
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/entry/common.c:exit_to_user_mode_loop
```
**Symbols:**

```
ffffffff811bf4c0-ffffffff811bf505: klp_update_patch_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void klp_update_patch_state(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff811d1fa0)
Location: kernel/livepatch/transition.c:184
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:do_idle
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/entry/common.c:exit_to_user_mode_loop
```
**Symbols:**

```
ffffffff811d1fa0-ffffffff811d1fe5: klp_update_patch_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void klp_update_patch_state(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff811e6c20)
Location: kernel/livepatch/transition.c:184
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:do_idle
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/entry/common.c:irqentry_exit_to_user_mode
  - kernel/entry/common.c:syscall_exit_to_user_mode
  - kernel/entry/common.c:syscall_exit_to_user_mode_work
```
**Symbols:**

```
ffffffff811e6c20-ffffffff811e6c65: klp_update_patch_state (STB_GLOBAL)
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
In kernel/sched/idle.c (0)
Location: include/linux/livepatch.h:225
Inline: True
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
In kernel/sched/idle.c (0)
Location: include/linux/livepatch.h:225
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void klp_update_patch_state(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (c0000000001f3a60)
Location: kernel/livepatch/transition.c:163
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_force_transition
Direct callers:
  - arch/powerpc/kernel/signal.c:do_notify_resume
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
c0000000001f2e40-c0000000001f2e88: klp_update_patch_state (STB_GLOBAL)
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
In kernel/sched/idle.c (0)
Location: include/linux/livepatch.h:225
Inline: True
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
void klp_update_patch_state(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff81126c89)
Location: kernel/livepatch/transition.c:163
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_force_transition
Direct callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
ffffffff81126450-ffffffff8112646f: klp_update_patch_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void klp_update_patch_state(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff811196e9)
Location: kernel/livepatch/transition.c:163
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_force_transition
Direct callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
ffffffff81118eb0-ffffffff81118ecf: klp_update_patch_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void klp_update_patch_state(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff81124b79)
Location: kernel/livepatch/transition.c:163
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_force_transition
Direct callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
  - kernel/sched/idle.c:do_idle
```
**Symbols:**

```
ffffffff81124340-ffffffff8112435f: klp_update_patch_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void klp_update_patch_state(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/transition.c (ffffffff81130980)
Location: kernel/livepatch/transition.c:163
Inline: False
Direct callers:
  - arch/x86/entry/common.c:exit_to_usermode_loop
  - kernel/sched/idle.c:do_idle
  - kernel/livepatch/transition.c:klp_force_transition
  - kernel/livepatch/transition.c:klp_force_transition
```
**Symbols:**

```
ffffffff81130980-ffffffff811309b5: klp_update_patch_state (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
