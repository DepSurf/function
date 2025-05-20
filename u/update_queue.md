# Function: <code>update_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int update_queue(struct sem_array *sma, int semnum, struct list_head *pt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81327330)
Location: ipc/sem.c:888
Inline: False
Direct callers:
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:do_smart_update
```
**Symbols:**

```
ffffffff81327330-ffffffff813274e4: update_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int update_queue(struct sem_array *sma, int semnum, struct list_head *pt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8135be00)
Location: ipc/sem.c:884
Inline: False
Direct callers:
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:do_smart_update
```
**Symbols:**

```
ffffffff8135be00-ffffffff8135c01b: update_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int update_queue(struct sem_array *sma, int semnum, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff813724b0)
Location: ipc/sem.c:885
Inline: False
Direct callers:
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:do_smart_update
```
**Symbols:**

```
ffffffff813724b0-ffffffff81372634: update_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int update_queue(struct sem_array *sma, int semnum, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81385730)
Location: ipc/sem.c:896
Inline: False
Direct callers:
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:do_smart_update
```
**Symbols:**

```
ffffffff81385730-ffffffff813858a9: update_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int update_queue(struct sem_array *sma, int semnum, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff813a9fb0)
Location: ipc/sem.c:899
Inline: False
Direct callers:
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:do_smart_update
```
**Symbols:**

```
ffffffff813a9fb0-ffffffff813aa129: update_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int update_queue(struct sem_array *sma, int semnum, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff813d9c20)
Location: ipc/sem.c:935
Inline: False
Direct callers:
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:do_smart_update
```
**Symbols:**

```
ffffffff813d9c20-ffffffff813d9d99: update_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int update_queue(struct sem_array *sma, int semnum, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff813f4460)
Location: ipc/sem.c:934
Inline: False
Direct callers:
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:do_smart_update
```
**Symbols:**

```
ffffffff813f4460-ffffffff813f45d9: update_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int update_queue(struct sem_array *sma, int semnum, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff814206c0)
Location: ipc/sem.c:930
Inline: False
Direct callers:
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:do_smart_update
```
**Symbols:**

```
ffffffff814206c0-ffffffff8142084a: update_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int update_queue(struct sem_array *sma, int semnum, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8143a4b0)
Location: ipc/sem.c:930
Inline: False
Direct callers:
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:do_smart_update
```
**Symbols:**

```
ffffffff8143a4b0-ffffffff8143a63a: update_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int update_queue(struct sem_array *sma, int semnum, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8148a8b0)
Location: ipc/sem.c:946
Inline: False
Direct callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_setval
```
**Symbols:**

```
ffffffff8148a8b0-ffffffff8148aa72: update_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int update_queue(struct sem_array *sma, int semnum, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff814a7e60)
Location: ipc/sem.c:945
Inline: False
Direct callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_setval
```
**Symbols:**

```
ffffffff814a7e60-ffffffff814a8022: update_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int update_queue(struct sem_array *sma, int semnum, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff814addb0)
Location: ipc/sem.c:947
Inline: False
Direct callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_setval
```
**Symbols:**

```
ffffffff814addb0-ffffffff814adf7e: update_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int update_queue(struct sem_array *sma, int semnum, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff815062b0)
Location: ipc/sem.c:950
Inline: False
Direct callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_setval
```
**Symbols:**

```
ffffffff815062b0-ffffffff8150647e: update_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int update_queue(struct sem_array *sma, int semnum, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff815981c0)
Location: ipc/sem.c:949
Inline: False
Direct callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_setval
```
**Symbols:**

```
ffffffff815981c0-ffffffff8159839e: update_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int update_queue(struct sem_array *sma, int semnum, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff816413e0)
Location: ipc/sem.c:949
Inline: False
Direct callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_setval
```
**Symbols:**

```
ffffffff816413e0-ffffffff816415be: update_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int update_queue(struct sem_array *sma, int semnum, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81679970)
Location: ipc/sem.c:949
Inline: False
Direct callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_setval
```
**Symbols:**

```
ffffffff81679970-ffffffff81679b4e: update_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int update_queue(struct sem_array *sma, int semnum, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff816b5d10)
Location: ipc/sem.c:949
Inline: False
Direct callers:
  - ipc/sem.c:exit_sem
  - ipc/sem.c:exit_sem
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_setval
  - ipc/sem.c:semctl_setval
```
**Symbols:**

```
ffffffff816b5d10-ffffffff816b5eee: update_queue (STB_LOCAL)
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
int update_queue(struct sem_array *sma, int semnum, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffff800010521c18)
Location: ipc/sem.c:930
Inline: False
Direct callers:
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:do_smart_update
```
**Symbols:**

```
ffff800010521c18-ffff800010521d8c: update_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int update_queue(struct sem_array *sma, int semnum, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (c06dcd3c)
Location: ipc/sem.c:930
Inline: False
Direct callers:
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:do_smart_update
```
**Symbols:**

```
c06dcd3c-c06dce98: update_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int update_queue(struct sem_array *sma, int semnum, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (c00000000066ba40)
Location: ipc/sem.c:930
Inline: False
Direct callers:
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:do_smart_update
```
**Symbols:**

```
c00000000066ba40-c00000000066bc48: update_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int update_queue(struct sem_array *sma, int semnum, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffe00038756a)
Location: ipc/sem.c:930
Inline: False
Direct callers:
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:do_smart_update
```
**Symbols:**

```
ffffffe00038756a-ffffffe0003876c4: update_queue (STB_LOCAL)
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
int update_queue(struct sem_array *sma, int semnum, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81432a90)
Location: ipc/sem.c:930
Inline: False
Direct callers:
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:do_smart_update
```
**Symbols:**

```
ffffffff81432a90-ffffffff81432c1a: update_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int update_queue(struct sem_array *sma, int semnum, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81423510)
Location: ipc/sem.c:930
Inline: False
Direct callers:
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:do_smart_update
```
**Symbols:**

```
ffffffff81423510-ffffffff8142369a: update_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int update_queue(struct sem_array *sma, int semnum, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8142ec30)
Location: ipc/sem.c:930
Inline: False
Direct callers:
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:do_smart_update
```
**Symbols:**

```
ffffffff8142ec30-ffffffff8142edba: update_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int update_queue(struct sem_array *sma, int semnum, struct wake_q_head *wake_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81445f20)
Location: ipc/sem.c:930
Inline: False
Direct callers:
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:do_smart_update
  - ipc/sem.c:do_smart_update
```
**Symbols:**

```
ffffffff81445f20-ffffffff814460aa: update_queue (STB_LOCAL)
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
