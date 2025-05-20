# Function: <code>wake_const_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int wake_const_ops(struct sem_array *sma, int semnum, struct list_head *pt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81327140)
Location: ipc/sem.c:786
Inline: False
Direct callers:
  - ipc/sem.c:do_smart_wakeup_zero
  - ipc/sem.c:do_smart_wakeup_zero
  - ipc/sem.c:do_smart_wakeup_zero
```
**Symbols:**

```
ffffffff81327140-ffffffff81327246: wake_const_ops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int wake_const_ops(struct sem_array *sma, int semnum, struct list_head *pt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8135bc10)
Location: ipc/sem.c:782
Inline: False
Direct callers:
  - ipc/sem.c:do_smart_wakeup_zero
  - ipc/sem.c:do_smart_wakeup_zero
  - ipc/sem.c:do_smart_wakeup_zero
```
**Symbols:**

```
ffffffff8135bc10-ffffffff8135bd19: wake_const_ops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int wake_const_ops(struct sem_array *sma, int semnum, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff813722e0)
Location: ipc/sem.c:790
Inline: False
Direct callers:
  - ipc/sem.c:do_smart_wakeup_zero
  - ipc/sem.c:do_smart_wakeup_zero
  - ipc/sem.c:do_smart_wakeup_zero
```
**Symbols:**

```
ffffffff813722e0-ffffffff813723c9: wake_const_ops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int wake_const_ops(struct sem_array *sma, int semnum, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81385540)
Location: ipc/sem.c:801
Inline: False
Direct callers:
  - ipc/sem.c:do_smart_wakeup_zero
  - ipc/sem.c:do_smart_wakeup_zero
  - ipc/sem.c:do_smart_wakeup_zero
```
**Symbols:**

```
ffffffff81385540-ffffffff81385615: wake_const_ops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int wake_const_ops(struct sem_array *sma, int semnum, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff813a9dc0)
Location: ipc/sem.c:804
Inline: False
Direct callers:
  - ipc/sem.c:do_smart_wakeup_zero
  - ipc/sem.c:do_smart_wakeup_zero
  - ipc/sem.c:do_smart_wakeup_zero
```
**Symbols:**

```
ffffffff813a9dc0-ffffffff813a9e95: wake_const_ops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int wake_const_ops(struct sem_array *sma, int semnum, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff813d9a50)
Location: ipc/sem.c:840
Inline: False
Direct callers:
  - ipc/sem.c:do_smart_wakeup_zero
  - ipc/sem.c:do_smart_wakeup_zero
  - ipc/sem.c:do_smart_wakeup_zero
```
**Symbols:**

```
ffffffff813d9a50-ffffffff813d9b25: wake_const_ops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int wake_const_ops(struct sem_array *sma, int semnum, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff813f4290)
Location: ipc/sem.c:839
Inline: False
Direct callers:
  - ipc/sem.c:do_smart_wakeup_zero
  - ipc/sem.c:do_smart_wakeup_zero
  - ipc/sem.c:do_smart_wakeup_zero
```
**Symbols:**

```
ffffffff813f4290-ffffffff813f4365: wake_const_ops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int wake_const_ops(struct sem_array *sma, int semnum, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81420500)
Location: ipc/sem.c:835
Inline: False
Direct callers:
  - ipc/sem.c:do_smart_wakeup_zero
  - ipc/sem.c:do_smart_wakeup_zero
  - ipc/sem.c:do_smart_wakeup_zero
```
**Symbols:**

```
ffffffff81420500-ffffffff814205cc: wake_const_ops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int wake_const_ops(struct sem_array *sma, int semnum, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8143a2f0)
Location: ipc/sem.c:835
Inline: False
Direct callers:
  - ipc/sem.c:do_smart_wakeup_zero
  - ipc/sem.c:do_smart_wakeup_zero
  - ipc/sem.c:do_smart_wakeup_zero
```
**Symbols:**

```
ffffffff8143a2f0-ffffffff8143a3bc: wake_const_ops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int wake_const_ops(struct sem_array *sma, int semnum, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8148a6a0)
Location: ipc/sem.c:851
Inline: False
Direct callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:do_smart_wakeup_zero
```
**Symbols:**

```
ffffffff8148a6a0-ffffffff8148a7b4: wake_const_ops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int wake_const_ops(struct sem_array *sma, int semnum, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff814a7c50)
Location: ipc/sem.c:850
Inline: False
Direct callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:do_smart_wakeup_zero
```
**Symbols:**

```
ffffffff814a7c50-ffffffff814a7d64: wake_const_ops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int wake_const_ops(struct sem_array *sma, int semnum, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff814adb90)
Location: ipc/sem.c:852
Inline: False
Direct callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:do_smart_wakeup_zero
```
**Symbols:**

```
ffffffff814adb90-ffffffff814adcb4: wake_const_ops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int wake_const_ops(struct sem_array *sma, int semnum, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81506090)
Location: ipc/sem.c:855
Inline: False
Direct callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:do_smart_wakeup_zero
```
**Symbols:**

```
ffffffff81506090-ffffffff815061b4: wake_const_ops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int wake_const_ops(struct sem_array *sma, int semnum, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81597f70)
Location: ipc/sem.c:854
Inline: False
Direct callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:do_smart_wakeup_zero
```
**Symbols:**

```
ffffffff81597f70-ffffffff815980b6: wake_const_ops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int wake_const_ops(struct sem_array *sma, int semnum, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81641170)
Location: ipc/sem.c:854
Inline: False
Direct callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:do_smart_wakeup_zero
```
**Symbols:**

```
ffffffff81641170-ffffffff816412b6: wake_const_ops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int wake_const_ops(struct sem_array *sma, int semnum, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81679700)
Location: ipc/sem.c:854
Inline: False
Direct callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:do_smart_wakeup_zero
```
**Symbols:**

```
ffffffff81679700-ffffffff81679846: wake_const_ops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int wake_const_ops(struct sem_array *sma, int semnum, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff816b5aa0)
Location: ipc/sem.c:854
Inline: False
Direct callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:do_smart_wakeup_zero
```
**Symbols:**

```
ffffffff816b5aa0-ffffffff816b5be6: wake_const_ops (STB_LOCAL)
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
int wake_const_ops(struct sem_array *sma, int semnum, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffff8000105219e0)
Location: ipc/sem.c:835
Inline: False
Direct callers:
  - ipc/sem.c:do_smart_wakeup_zero
  - ipc/sem.c:do_smart_wakeup_zero
  - ipc/sem.c:do_smart_wakeup_zero
```
**Symbols:**

```
ffff8000105219e0-ffff800010521af4: wake_const_ops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int wake_const_ops(struct sem_array *sma, int semnum, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (c06dcb74)
Location: ipc/sem.c:835
Inline: False
Direct callers:
  - ipc/sem.c:do_smart_wakeup_zero
  - ipc/sem.c:do_smart_wakeup_zero
  - ipc/sem.c:do_smart_wakeup_zero
```
**Symbols:**

```
c06dcb74-c06dcc38: wake_const_ops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int wake_const_ops(struct sem_array *sma, int semnum, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (c00000000066b730)
Location: ipc/sem.c:835
Inline: False
Direct callers:
  - ipc/sem.c:do_smart_wakeup_zero
  - ipc/sem.c:do_smart_wakeup_zero
  - ipc/sem.c:do_smart_wakeup_zero
```
**Symbols:**

```
c00000000066b730-c00000000066b8b8: wake_const_ops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int wake_const_ops(struct sem_array *sma, int semnum, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffe0003873b4)
Location: ipc/sem.c:835
Inline: False
Direct callers:
  - ipc/sem.c:do_smart_wakeup_zero
  - ipc/sem.c:do_smart_wakeup_zero
  - ipc/sem.c:do_smart_wakeup_zero
```
**Symbols:**

```
ffffffe0003873b4-ffffffe000387482: wake_const_ops (STB_LOCAL)
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
int wake_const_ops(struct sem_array *sma, int semnum, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff814328d0)
Location: ipc/sem.c:835
Inline: False
Direct callers:
  - ipc/sem.c:do_smart_wakeup_zero
  - ipc/sem.c:do_smart_wakeup_zero
  - ipc/sem.c:do_smart_wakeup_zero
```
**Symbols:**

```
ffffffff814328d0-ffffffff8143299c: wake_const_ops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int wake_const_ops(struct sem_array *sma, int semnum, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81423350)
Location: ipc/sem.c:835
Inline: False
Direct callers:
  - ipc/sem.c:do_smart_wakeup_zero
  - ipc/sem.c:do_smart_wakeup_zero
  - ipc/sem.c:do_smart_wakeup_zero
```
**Symbols:**

```
ffffffff81423350-ffffffff8142341c: wake_const_ops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int wake_const_ops(struct sem_array *sma, int semnum, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8142ea70)
Location: ipc/sem.c:835
Inline: False
Direct callers:
  - ipc/sem.c:do_smart_wakeup_zero
  - ipc/sem.c:do_smart_wakeup_zero
  - ipc/sem.c:do_smart_wakeup_zero
```
**Symbols:**

```
ffffffff8142ea70-ffffffff8142eb3c: wake_const_ops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int wake_const_ops(struct sem_array *sma, int semnum, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81445d60)
Location: ipc/sem.c:835
Inline: False
Direct callers:
  - ipc/sem.c:do_smart_wakeup_zero
  - ipc/sem.c:do_smart_wakeup_zero
  - ipc/sem.c:do_smart_wakeup_zero
```
**Symbols:**

```
ffffffff81445d60-ffffffff81445e2c: wake_const_ops (STB_LOCAL)
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
