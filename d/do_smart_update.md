# Function: <code>do_smart_update</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void do_smart_update(struct sem_array *sma, struct sembuf *sops, int nsops, int otime, struct list_head *pt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81327850)
Location: ipc/sem.c:973
Inline: False
Direct callers:
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:SyS_semctl
  - ipc/sem.c:exit_sem
```
**Symbols:**

```
ffffffff81327850-ffffffff81327973: do_smart_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void do_smart_update(struct sem_array *sma, struct sembuf *sops, int nsops, int otime, struct list_head *pt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8135c500)
Location: ipc/sem.c:969
Inline: False
Direct callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SyS_semctl
  - ipc/sem.c:semctl_main
```
**Symbols:**

```
ffffffff8135c500-ffffffff8135c617: do_smart_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void do_smart_update(struct sem_array *sma, struct sembuf *sops, int nsops, int otime, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81372ba0)
Location: ipc/sem.c:965
Inline: False
Direct callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SyS_semctl
  - ipc/sem.c:semctl_main
```
**Symbols:**

```
ffffffff81372ba0-ffffffff81372cb7: do_smart_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void do_smart_update(struct sem_array *sma, struct sembuf *sops, int nsops, int otime, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81386020)
Location: ipc/sem.c:976
Inline: False
Direct callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SyS_semctl
  - ipc/sem.c:semctl_main
```
**Symbols:**

```
ffffffff81386020-ffffffff81386140: do_smart_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void do_smart_update(struct sem_array *sma, struct sembuf *sops, int nsops, int otime, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff813aa930)
Location: ipc/sem.c:979
Inline: False
Direct callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
```
**Symbols:**

```
ffffffff813aa930-ffffffff813aaa50: do_smart_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void do_smart_update(struct sem_array *sma, struct sembuf *sops, int nsops, int otime, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff813d9da0)
Location: ipc/sem.c:1015
Inline: False
Direct callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
```
**Symbols:**

```
ffffffff813d9da0-ffffffff813d9ec2: do_smart_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void do_smart_update(struct sem_array *sma, struct sembuf *sops, int nsops, int otime, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff813f45e0)
Location: ipc/sem.c:1014
Inline: False
Direct callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
```
**Symbols:**

```
ffffffff813f45e0-ffffffff813f4702: do_smart_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void do_smart_update(struct sem_array *sma, struct sembuf *sops, int nsops, int otime, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81420850)
Location: ipc/sem.c:1010
Inline: False
Direct callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
```
**Symbols:**

```
ffffffff81420850-ffffffff81420973: do_smart_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void do_smart_update(struct sem_array *sma, struct sembuf *sops, int nsops, int otime, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8143a640)
Location: ipc/sem.c:1010
Inline: False
Direct callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
```
**Symbols:**

```
ffffffff8143a640-ffffffff8143a763: do_smart_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void do_smart_update(struct sem_array *sma, struct sembuf *sops, int nsops, int otime, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8148c22d)
Location: ipc/sem.c:1026
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
Direct callers:
  - ipc/sem.c:do_semtimedop
```
**Symbols:**

```
ffffffff8148aa80-ffffffff8148aba3: do_smart_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void do_smart_update(struct sem_array *sma, struct sembuf *sops, int nsops, int otime, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff814a987b)
Location: ipc/sem.c:1025
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
Direct callers:
  - ipc/sem.c:do_semtimedop
```
**Symbols:**

```
ffffffff814a8030-ffffffff814a8153: do_smart_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void do_smart_update(struct sem_array *sma, struct sembuf *sops, int nsops, int otime, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff814af637)
Location: ipc/sem.c:1027
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
Direct callers:
  - ipc/sem.c:do_semtimedop
```
**Symbols:**

```
ffffffff814adf80-ffffffff814ae0a3: do_smart_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void do_smart_update(struct sem_array *sma, struct sembuf *sops, int nsops, int otime, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81507af9)
Location: ipc/sem.c:1030
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
Direct callers:
  - ipc/sem.c:__do_semtimedop
```
**Symbols:**

```
ffffffff81506480-ffffffff815065a3: do_smart_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void do_smart_update(struct sem_array *sma, struct sembuf *sops, int nsops, int otime, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8159a25c)
Location: ipc/sem.c:1029
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
Direct callers:
  - ipc/sem.c:__do_semtimedop
```
**Symbols:**

```
ffffffff815983a0-ffffffff815984ea: do_smart_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void do_smart_update(struct sem_array *sma, struct sembuf *sops, int nsops, int otime, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff816434e9)
Location: ipc/sem.c:1029
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
Direct callers:
  - ipc/sem.c:__do_semtimedop
```
**Symbols:**

```
ffffffff816415d0-ffffffff8164171a: do_smart_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void do_smart_update(struct sem_array *sma, struct sembuf *sops, int nsops, int otime, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8167ba2f)
Location: ipc/sem.c:1029
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
Direct callers:
  - ipc/sem.c:__do_semtimedop
```
**Symbols:**

```
ffffffff81679b60-ffffffff81679caa: do_smart_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void do_smart_update(struct sem_array *sma, struct sembuf *sops, int nsops, int otime, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff816b7de2)
Location: ipc/sem.c:1029
Inline: True
Inline callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
Direct callers:
  - ipc/sem.c:__do_semtimedop
```
**Symbols:**

```
ffffffff816b5f00-ffffffff816b604a: do_smart_update (STB_LOCAL)
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
void do_smart_update(struct sem_array *sma, struct sembuf *sops, int nsops, int otime, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffff800010521d90)
Location: ipc/sem.c:1010
Inline: False
Direct callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
```
**Symbols:**

```
ffff800010521d90-ffff800010521edc: do_smart_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void do_smart_update(struct sem_array *sma, struct sembuf *sops, int nsops, int otime, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (c06dce98)
Location: ipc/sem.c:1010
Inline: False
Direct callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:ksys_semctl
  - ipc/sem.c:semctl_main
```
**Symbols:**

```
c06dce98-c06dcf9c: do_smart_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void do_smart_update(struct sem_array *sma, struct sembuf *sops, int nsops, int otime, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (c00000000066bc50)
Location: ipc/sem.c:1010
Inline: False
Direct callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
```
**Symbols:**

```
c00000000066bc50-c00000000066be0c: do_smart_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void do_smart_update(struct sem_array *sma, struct sembuf *sops, int nsops, int otime, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffe00038799a)
Location: ipc/sem.c:1010
Inline: False
Direct callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:__se_sys_semctl
  - ipc/sem.c:semctl_main
```
**Symbols:**

```
ffffffe00038799a-ffffffe000387aa4: do_smart_update (STB_LOCAL)
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
void do_smart_update(struct sem_array *sma, struct sembuf *sops, int nsops, int otime, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81432c20)
Location: ipc/sem.c:1010
Inline: False
Direct callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
```
**Symbols:**

```
ffffffff81432c20-ffffffff81432d43: do_smart_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void do_smart_update(struct sem_array *sma, struct sembuf *sops, int nsops, int otime, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff814236a0)
Location: ipc/sem.c:1010
Inline: False
Direct callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
```
**Symbols:**

```
ffffffff814236a0-ffffffff814237c3: do_smart_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void do_smart_update(struct sem_array *sma, struct sembuf *sops, int nsops, int otime, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8142edc0)
Location: ipc/sem.c:1010
Inline: False
Direct callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
```
**Symbols:**

```
ffffffff8142edc0-ffffffff8142eee3: do_smart_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void do_smart_update(struct sem_array *sma, struct sembuf *sops, int nsops, int otime, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff814460b0)
Location: ipc/sem.c:1010
Inline: False
Direct callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
```
**Symbols:**

```
ffffffff814460b0-ffffffff814461d3: do_smart_update (STB_LOCAL)
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
