# Function: <code>do_smart_wakeup_zero</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int do_smart_wakeup_zero(struct sem_array *sma, struct sembuf *sops, int nsops, struct list_head *pt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81327250)
Location: ipc/sem.c:832
Inline: False
Direct callers:
  - ipc/sem.c:update_queue
  - ipc/sem.c:do_smart_update
```
**Symbols:**

```
ffffffff81327250-ffffffff8132732f: do_smart_wakeup_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int do_smart_wakeup_zero(struct sem_array *sma, struct sembuf *sops, int nsops, struct list_head *pt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8135bd20)
Location: ipc/sem.c:828
Inline: False
Direct callers:
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:update_queue
```
**Symbols:**

```
ffffffff8135bd20-ffffffff8135bdff: do_smart_wakeup_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int do_smart_wakeup_zero(struct sem_array *sma, struct sembuf *sops, int nsops, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff813723d0)
Location: ipc/sem.c:829
Inline: False
Direct callers:
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:update_queue
```
**Symbols:**

```
ffffffff813723d0-ffffffff813724af: do_smart_wakeup_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int do_smart_wakeup_zero(struct sem_array *sma, struct sembuf *sops, int nsops, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81385620)
Location: ipc/sem.c:840
Inline: False
Direct callers:
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:update_queue
```
**Symbols:**

```
ffffffff81385620-ffffffff81385729: do_smart_wakeup_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_smart_wakeup_zero(struct sem_array *sma, struct sembuf *sops, int nsops, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff813a9ea0)
Location: ipc/sem.c:843
Inline: False
Direct callers:
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:update_queue
```
**Symbols:**

```
ffffffff813a9ea0-ffffffff813a9fa9: do_smart_wakeup_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int do_smart_wakeup_zero(struct sem_array *sma, struct sembuf *sops, int nsops, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff813d9b30)
Location: ipc/sem.c:879
Inline: False
Direct callers:
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:update_queue
```
**Symbols:**

```
ffffffff813d9b30-ffffffff813d9c1b: do_smart_wakeup_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int do_smart_wakeup_zero(struct sem_array *sma, struct sembuf *sops, int nsops, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff813f4370)
Location: ipc/sem.c:878
Inline: False
Direct callers:
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:update_queue
```
**Symbols:**

```
ffffffff813f4370-ffffffff813f445b: do_smart_wakeup_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int do_smart_wakeup_zero(struct sem_array *sma, struct sembuf *sops, int nsops, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff814205d0)
Location: ipc/sem.c:874
Inline: False
Direct callers:
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:update_queue
```
**Symbols:**

```
ffffffff814205d0-ffffffff814206b8: do_smart_wakeup_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int do_smart_wakeup_zero(struct sem_array *sma, struct sembuf *sops, int nsops, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8143a3c0)
Location: ipc/sem.c:874
Inline: False
Direct callers:
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:update_queue
```
**Symbols:**

```
ffffffff8143a3c0-ffffffff8143a4a8: do_smart_wakeup_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int do_smart_wakeup_zero(struct sem_array *sma, struct sembuf *sops, int nsops, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8148a7c0)
Location: ipc/sem.c:890
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
Direct callers:
  - ipc/sem.c:update_queue
```
**Symbols:**

```
ffffffff8148a7c0-ffffffff8148a8a6: do_smart_wakeup_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int do_smart_wakeup_zero(struct sem_array *sma, struct sembuf *sops, int nsops, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff814a7d70)
Location: ipc/sem.c:889
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
Direct callers:
  - ipc/sem.c:update_queue
```
**Symbols:**

```
ffffffff814a7d70-ffffffff814a7e56: do_smart_wakeup_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int do_smart_wakeup_zero(struct sem_array *sma, struct sembuf *sops, int nsops, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff814adcc0)
Location: ipc/sem.c:891
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
Direct callers:
  - ipc/sem.c:update_queue
```
**Symbols:**

```
ffffffff814adcc0-ffffffff814adda6: do_smart_wakeup_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int do_smart_wakeup_zero(struct sem_array *sma, struct sembuf *sops, int nsops, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff815061c0)
Location: ipc/sem.c:894
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
Direct callers:
  - ipc/sem.c:update_queue
```
**Symbols:**

```
ffffffff815061c0-ffffffff815062a6: do_smart_wakeup_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int do_smart_wakeup_zero(struct sem_array *sma, struct sembuf *sops, int nsops, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff815980c0)
Location: ipc/sem.c:893
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
Direct callers:
  - ipc/sem.c:update_queue
```
**Symbols:**

```
ffffffff815980c0-ffffffff815981b7: do_smart_wakeup_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int do_smart_wakeup_zero(struct sem_array *sma, struct sembuf *sops, int nsops, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff816412d0)
Location: ipc/sem.c:893
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
Direct callers:
  - ipc/sem.c:update_queue
```
**Symbols:**

```
ffffffff816412d0-ffffffff816413c7: do_smart_wakeup_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int do_smart_wakeup_zero(struct sem_array *sma, struct sembuf *sops, int nsops, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8167ba2f)
Location: ipc/sem.c:893
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
Direct callers:
  - ipc/sem.c:update_queue
```
**Symbols:**

```
ffffffff81679860-ffffffff81679957: do_smart_wakeup_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int do_smart_wakeup_zero(struct sem_array *sma, struct sembuf *sops, int nsops, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff816b7de2)
Location: ipc/sem.c:893
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
Direct callers:
  - ipc/sem.c:update_queue
```
**Symbols:**

```
ffffffff816b5c00-ffffffff816b5cf7: do_smart_wakeup_zero (STB_LOCAL)
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
int do_smart_wakeup_zero(struct sem_array *sma, struct sembuf *sops, int nsops, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffff800010521af8)
Location: ipc/sem.c:874
Inline: False
Direct callers:
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:update_queue
```
**Symbols:**

```
ffff800010521af8-ffff800010521c14: do_smart_wakeup_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int do_smart_wakeup_zero(struct sem_array *sma, struct sembuf *sops, int nsops, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (c06dcc38)
Location: ipc/sem.c:874
Inline: False
Direct callers:
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:update_queue
```
**Symbols:**

```
c06dcc38-c06dcd3c: do_smart_wakeup_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_smart_wakeup_zero(struct sem_array *sma, struct sembuf *sops, int nsops, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (c00000000066b8c0)
Location: ipc/sem.c:874
Inline: False
Direct callers:
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:update_queue
```
**Symbols:**

```
c00000000066b8c0-c00000000066ba38: do_smart_wakeup_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int do_smart_wakeup_zero(struct sem_array *sma, struct sembuf *sops, int nsops, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffe000387482)
Location: ipc/sem.c:874
Inline: False
Direct callers:
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:update_queue
```
**Symbols:**

```
ffffffe000387482-ffffffe00038756a: do_smart_wakeup_zero (STB_LOCAL)
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
int do_smart_wakeup_zero(struct sem_array *sma, struct sembuf *sops, int nsops, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff814329a0)
Location: ipc/sem.c:874
Inline: False
Direct callers:
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:update_queue
```
**Symbols:**

```
ffffffff814329a0-ffffffff81432a88: do_smart_wakeup_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int do_smart_wakeup_zero(struct sem_array *sma, struct sembuf *sops, int nsops, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81423420)
Location: ipc/sem.c:874
Inline: False
Direct callers:
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:update_queue
```
**Symbols:**

```
ffffffff81423420-ffffffff81423508: do_smart_wakeup_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int do_smart_wakeup_zero(struct sem_array *sma, struct sembuf *sops, int nsops, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8142eb40)
Location: ipc/sem.c:874
Inline: False
Direct callers:
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:update_queue
```
**Symbols:**

```
ffffffff8142eb40-ffffffff8142ec28: do_smart_wakeup_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int do_smart_wakeup_zero(struct sem_array *sma, struct sembuf *sops, int nsops, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81445e30)
Location: ipc/sem.c:874
Inline: False
Direct callers:
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:update_queue
```
**Symbols:**

```
ffffffff81445e30-ffffffff81445f18: do_smart_wakeup_zero (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct wake_q_head *wake_q</code>
</li>
<li>
<b>Param removed. </b>
<code>struct list_head *pt</code>
</li>
</ul>
</details>
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
