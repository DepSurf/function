# Function: <code>rcu_tasks_kthread</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int rcu_tasks_kthread(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff810e9380)
Location: kernel/rcu/update.c:648
Inline: False
```
**Symbols:**

```
ffffffff810e9380-ffffffff810e9785: rcu_tasks_kthread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int rcu_tasks_kthread(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff810f0250)
Location: kernel/rcu/update.c:651
Inline: False
```
**Symbols:**

```
ffffffff810f0250-ffffffff810f0633: rcu_tasks_kthread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int rcu_tasks_kthread(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff810f0260)
Location: kernel/rcu/update.c:711
Inline: False
```
**Symbols:**

```
ffffffff810f0260-ffffffff810f0618: rcu_tasks_kthread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int rcu_tasks_kthread(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff810f9f20)
Location: kernel/rcu/update.c:710
Inline: False
```
**Symbols:**

```
ffffffff810f9f20-ffffffff810fa2e1: rcu_tasks_kthread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int rcu_tasks_kthread(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/update.c (0)
Location: kernel/rcu/update.c:662
Inline: False
```
**Symbols:**

```
ffffffff81102490-ffffffff811027e9: rcu_tasks_kthread (STB_LOCAL)
ffffffff811029ab-ffffffff81102a1c: rcu_tasks_kthread.cold.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int rcu_tasks_kthread(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/update.c (0)
Location: kernel/rcu/update.c:658
Inline: False
```
**Symbols:**

```
ffffffff8110de80-ffffffff8110e1f1: rcu_tasks_kthread (STB_LOCAL)
ffffffff8110e36b-ffffffff8110e3de: rcu_tasks_kthread.cold.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int rcu_tasks_kthread(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/update.c (0)
Location: kernel/rcu/update.c:603
Inline: False
```
**Symbols:**

```
ffffffff81117560-ffffffff811178f9: rcu_tasks_kthread (STB_LOCAL)
ffffffff81117a2b-ffffffff81117ac0: rcu_tasks_kthread.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int rcu_tasks_kthread(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/update.c (0)
Location: kernel/rcu/update.c:630
Inline: False
```
**Symbols:**

```
ffffffff81123930-ffffffff81123cdb: rcu_tasks_kthread (STB_LOCAL)
ffffffff81123e0b-ffffffff81123e7a: rcu_tasks_kthread.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rcu_tasks_kthread(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811303e0)
Location: kernel/rcu/tasks.h:174
Inline: False
```
**Symbols:**

```
ffffffff811303e0-ffffffff8113058a: rcu_tasks_kthread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rcu_tasks_kthread(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff8112c280)
Location: kernel/rcu/tasks.h:182
Inline: False
```
**Symbols:**

```
ffffffff8112c280-ffffffff8112c438: rcu_tasks_kthread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rcu_tasks_kthread(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff8112c7b0)
Location: kernel/rcu/tasks.h:182
Inline: False
```
**Symbols:**

```
ffffffff8112c7b0-ffffffff8112c968: rcu_tasks_kthread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int rcu_tasks_kthread(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff8114d4b0)
Location: kernel/rcu/tasks.h:182
Inline: False
```
**Symbols:**

```
ffffffff8114d4b0-ffffffff8114d66b: rcu_tasks_kthread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int rcu_tasks_kthread(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811741b0)
Location: kernel/rcu/tasks.h:501
Inline: False
```
**Symbols:**

```
ffffffff811741b0-ffffffff811742d5: rcu_tasks_kthread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rcu_tasks_kthread(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811a9c70)
Location: kernel/rcu/tasks.h:538
Inline: False
```
**Symbols:**

```
ffffffff811a9c70-ffffffff811a9cae: rcu_tasks_kthread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rcu_tasks_kthread(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811bbb60)
Location: kernel/rcu/tasks.h:550
Inline: False
```
**Symbols:**

```
ffffffff811bbb60-ffffffff811bbb9e: rcu_tasks_kthread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rcu_tasks_kthread(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811cc930)
Location: kernel/rcu/tasks.h:600
Inline: False
```
**Symbols:**

```
ffffffff811cc930-ffffffff811cc9f3: rcu_tasks_kthread (STB_LOCAL)
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
int rcu_tasks_kthread(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffff800010188b50)
Location: kernel/rcu/update.c:630
Inline: False
```
**Symbols:**

```
ffff800010188b50-ffff800010188fb8: rcu_tasks_kthread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rcu_tasks_kthread(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (c03d73d8)
Location: kernel/rcu/update.c:630
Inline: False
```
**Symbols:**

```
c03d73d8-c03d787c: rcu_tasks_kthread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int rcu_tasks_kthread(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (c0000000001e2d40)
Location: kernel/rcu/update.c:630
Inline: False
```
**Symbols:**

```
c0000000001e2d40-c0000000001e32b8: rcu_tasks_kthread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int rcu_tasks_kthread(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffe00011dfb6)
Location: kernel/rcu/update.c:630
Inline: False
```
**Symbols:**

```
ffffffe00011dfb6-ffffffe00011e340: rcu_tasks_kthread (STB_LOCAL)
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
int rcu_tasks_kthread(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/update.c (0)
Location: kernel/rcu/update.c:630
Inline: False
```
**Symbols:**

```
ffffffff8111bf10-ffffffff8111c2bb: rcu_tasks_kthread (STB_LOCAL)
ffffffff8111c3eb-ffffffff8111c45a: rcu_tasks_kthread.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int rcu_tasks_kthread(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/update.c (0)
Location: kernel/rcu/update.c:630
Inline: False
```
**Symbols:**

```
ffffffff8110cf80-ffffffff8110d39a: rcu_tasks_kthread (STB_LOCAL)
ffffffff8110d4cb-ffffffff8110d52f: rcu_tasks_kthread.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int rcu_tasks_kthread(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/update.c (0)
Location: kernel/rcu/update.c:630
Inline: False
```
**Symbols:**

```
ffffffff81119e00-ffffffff8111a1ab: rcu_tasks_kthread (STB_LOCAL)
ffffffff8111a2db-ffffffff8111a34a: rcu_tasks_kthread.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int rcu_tasks_kthread(void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/update.c (0)
Location: kernel/rcu/update.c:630
Inline: False
```
**Symbols:**

```
ffffffff81125560-ffffffff811258fe: rcu_tasks_kthread (STB_LOCAL)
ffffffff81125a5b-ffffffff81125aca: rcu_tasks_kthread.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
