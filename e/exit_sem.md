# Function: <code>exit_sem</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void exit_sem(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81329a30)
Location: ipc/sem.c:2074
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:SyS_unshare
  - kernel/exit.c:do_exit
  - ipc/namespace.c:ipcns_install
```
**Symbols:**

```
ffffffff81329a30-ffffffff81329dd6: exit_sem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void exit_sem(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8135e6c0)
Location: ipc/sem.c:2072
Inline: False
Direct callers:
  - kernel/fork.c:SyS_unshare
  - kernel/exit.c:do_exit
  - ipc/namespace.c:ipcns_install
```
**Symbols:**

```
ffffffff8135e6c0-ffffffff8135ea68: exit_sem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void exit_sem(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81374e80)
Location: ipc/sem.c:2051
Inline: False
Direct callers:
  - kernel/fork.c:SyS_unshare
  - kernel/exit.c:do_exit
  - ipc/namespace.c:ipcns_install
```
**Symbols:**

```
ffffffff81374e80-ffffffff81375267: exit_sem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void exit_sem(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81388960)
Location: ipc/sem.c:2064
Inline: False
Direct callers:
  - kernel/fork.c:SyS_unshare
  - kernel/exit.c:do_exit
  - ipc/namespace.c:ipcns_install
```
**Symbols:**

```
ffffffff81388960-ffffffff81388df1: exit_sem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void exit_sem(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff813ad630)
Location: ipc/sem.c:2179
Inline: False
Direct callers:
  - kernel/fork.c:SyS_unshare
  - kernel/exit.c:do_exit
  - ipc/namespace.c:ipcns_install
```
**Symbols:**

```
ffffffff813ad630-ffffffff813adacc: exit_sem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void exit_sem(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff813dd0a0)
Location: ipc/sem.c:2268
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/exit.c:do_exit
  - ipc/namespace.c:ipcns_install
```
**Symbols:**

```
ffffffff813dd0a0-ffffffff813dd565: exit_sem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void exit_sem(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff813f7700)
Location: ipc/sem.c:2275
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/exit.c:do_exit
  - ipc/namespace.c:ipcns_install
```
**Symbols:**

```
ffffffff813f7700-ffffffff813f7bf2: exit_sem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void exit_sem(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81423c00)
Location: ipc/sem.c:2297
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
  - ipc/namespace.c:ipcns_install
```
**Symbols:**

```
ffffffff81423c00-ffffffff814240d6: exit_sem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void exit_sem(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8143d940)
Location: ipc/sem.c:2298
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
  - ipc/namespace.c:ipcns_install
```
**Symbols:**

```
ffffffff8143d940-ffffffff8143de2c: exit_sem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void exit_sem(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8148e4a0)
Location: ipc/sem.c:2314
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
  - kernel/nsproxy.c:__do_sys_setns
```
**Symbols:**

```
ffffffff8148e4a0-ffffffff8148eae7: exit_sem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void exit_sem(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff814abbe0)
Location: ipc/sem.c:2313
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
  - kernel/nsproxy.c:__do_sys_setns
```
**Symbols:**

```
ffffffff814abbe0-ffffffff814ac232: exit_sem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void exit_sem(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff814b1a70)
Location: ipc/sem.c:2315
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
  - kernel/nsproxy.c:__do_sys_setns
```
**Symbols:**

```
ffffffff814b1a70-ffffffff814b20c2: exit_sem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void exit_sem(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/sem.c (0)
Location: ipc/sem.c:2339
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
  - kernel/nsproxy.c:__do_sys_setns
```
**Symbols:**

```
ffffffff81cd2bb3-ffffffff81cd2bc8: exit_sem.cold (STB_LOCAL)
ffffffff8150a020-ffffffff8150a66d: exit_sem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void exit_sem(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/sem.c (0)
Location: ipc/sem.c:2336
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
  - kernel/nsproxy.c:__do_sys_setns
```
**Symbols:**

```
ffffffff81e85d8b-ffffffff81e85da0: exit_sem.cold (STB_LOCAL)
ffffffff8159bd60-ffffffff8159c3e3: exit_sem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void exit_sem(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/sem.c (0)
Location: ipc/sem.c:2337
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
  - kernel/nsproxy.c:__do_sys_setns
```
**Symbols:**

```
ffffffff82072f04-ffffffff82072f19: exit_sem.cold (STB_LOCAL)
ffffffff81645160-ffffffff816457e3: exit_sem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void exit_sem(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/sem.c (0)
Location: ipc/sem.c:2337
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
  - kernel/nsproxy.c:__do_sys_setns
```
**Symbols:**

```
ffffffff820f2b4c-ffffffff820f2b61: exit_sem.cold (STB_LOCAL)
ffffffff8167d660-ffffffff8167dcbc: exit_sem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void exit_sem(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/sem.c (0)
Location: ipc/sem.c:2335
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
  - kernel/nsproxy.c:__do_sys_setns
```
**Symbols:**

```
ffffffff821cfde4-ffffffff821cfdf9: exit_sem.cold (STB_LOCAL)
ffffffff816b9a30-ffffffff816ba0aa: exit_sem (STB_GLOBAL)
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
void exit_sem(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffff8000105257d0)
Location: ipc/sem.c:2298
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
  - ipc/namespace.c:ipcns_install
```
**Symbols:**

```
ffff8000105257d0-ffff800010525d2c: exit_sem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void exit_sem(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (c06dfca0)
Location: ipc/sem.c:2298
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
  - ipc/namespace.c:ipcns_install
```
**Symbols:**

```
c06dfca0-c06e0130: exit_sem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void exit_sem(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (c00000000066fc30)
Location: ipc/sem.c:2298
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
  - ipc/namespace.c:ipcns_install
```
**Symbols:**

```
c00000000066fc30-c000000000670364: exit_sem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void exit_sem(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffe00038a11e)
Location: ipc/sem.c:2298
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
  - ipc/namespace.c:ipcns_install
```
**Symbols:**

```
ffffffe00038a11e-ffffffe00038a5e4: exit_sem (STB_GLOBAL)
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
void exit_sem(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81435f20)
Location: ipc/sem.c:2298
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
  - ipc/namespace.c:ipcns_install
```
**Symbols:**

```
ffffffff81435f20-ffffffff8143640c: exit_sem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void exit_sem(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff814269a0)
Location: ipc/sem.c:2298
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
  - ipc/namespace.c:ipcns_install
```
**Symbols:**

```
ffffffff814269a0-ffffffff81426e8c: exit_sem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void exit_sem(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff814320c0)
Location: ipc/sem.c:2298
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
  - ipc/namespace.c:ipcns_install
```
**Symbols:**

```
ffffffff814320c0-ffffffff814325ac: exit_sem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void exit_sem(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81449190)
Location: ipc/sem.c:2298
Inline: False
Direct callers:
  - kernel/fork.c:ksys_unshare
  - kernel/fork.c:copy_process
  - kernel/exit.c:do_exit
  - ipc/namespace.c:ipcns_install
```
**Symbols:**

```
ffffffff81449190-ffffffff81449678: exit_sem (STB_GLOBAL)
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
