# Function: <code>rcu_spawn_tasks_kthread</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff810e9811)
Location: kernel/rcu/update.c:794
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff810f06c1)
Location: kernel/rcu/update.c:797
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff810f06a1)
Location: kernel/rcu/update.c:857
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int rcu_spawn_tasks_kthread();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff826cd15f)
Location: kernel/rcu/update.c:856
Inline: True
```
**Symbols:**

```
ffffffff826cd15f-ffffffff826cd1a8: rcu_spawn_tasks_kthread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int rcu_spawn_tasks_kthread();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff826f7329)
Location: kernel/rcu/update.c:808
Inline: False
```
**Symbols:**

```
ffffffff826f7329-ffffffff826f7372: rcu_spawn_tasks_kthread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int rcu_spawn_tasks_kthread();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff828ae253)
Location: kernel/rcu/update.c:818
Inline: False
```
**Symbols:**

```
ffffffff828ae253-ffffffff828ae2c1: rcu_spawn_tasks_kthread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int rcu_spawn_tasks_kthread();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff828c6c04)
Location: kernel/rcu/update.c:763
Inline: False
```
**Symbols:**

```
ffffffff828c6c04-ffffffff828c6c72: rcu_spawn_tasks_kthread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int rcu_spawn_tasks_kthread();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff828cf219)
Location: kernel/rcu/update.c:790
Inline: False
```
**Symbols:**

```
ffffffff828cf219-ffffffff828cf287: rcu_spawn_tasks_kthread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rcu_spawn_tasks_kthread();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff82cf035e)
Location: kernel/rcu/tasks.h:548
Inline: False
```
**Symbols:**

```
ffffffff82cf035e-ffffffff82cf03ae: rcu_spawn_tasks_kthread (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff8347f3a7)
Location: kernel/rcu/tasks.h:935
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_init_tasks_generic
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff83eab725)
Location: kernel/rcu/tasks.h:986
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_init_tasks_generic
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff836d06e5)
Location: kernel/rcu/tasks.h:1023
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_init_tasks_generic
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff83901b45)
Location: kernel/rcu/tasks.h:1119
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_init_tasks_generic
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
int rcu_spawn_tasks_kthread();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffff800011446894)
Location: kernel/rcu/update.c:790
Inline: False
```
**Symbols:**

```
ffff800011446894-ffff800011446920: rcu_spawn_tasks_kthread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rcu_spawn_tasks_kthread();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (c1520f10)
Location: kernel/rcu/update.c:790
Inline: False
```
**Symbols:**

```
c1520f10-c1520fb8: rcu_spawn_tasks_kthread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int rcu_spawn_tasks_kthread();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (c00000000136b734)
Location: kernel/rcu/update.c:790
Inline: False
```
**Symbols:**

```
c00000000136b734-c00000000136b7ec: rcu_spawn_tasks_kthread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int rcu_spawn_tasks_kthread();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffe000008340)
Location: kernel/rcu/update.c:790
Inline: False
```
**Symbols:**

```
ffffffe000008340-ffffffe0000083c8: rcu_spawn_tasks_kthread (STB_LOCAL)
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
int rcu_spawn_tasks_kthread();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff828b7f11)
Location: kernel/rcu/update.c:790
Inline: False
```
**Symbols:**

```
ffffffff828b7f11-ffffffff828b7f7f: rcu_spawn_tasks_kthread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int rcu_spawn_tasks_kthread();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff828b0191)
Location: kernel/rcu/update.c:790
Inline: False
```
**Symbols:**

```
ffffffff828b0191-ffffffff828b01ff: rcu_spawn_tasks_kthread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int rcu_spawn_tasks_kthread();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff828cae4d)
Location: kernel/rcu/update.c:790
Inline: False
```
**Symbols:**

```
ffffffff828cae4d-ffffffff828caebb: rcu_spawn_tasks_kthread (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int rcu_spawn_tasks_kthread();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff828d0246)
Location: kernel/rcu/update.c:790
Inline: False
```
**Symbols:**

```
ffffffff828d0246-ffffffff828d02b4: rcu_spawn_tasks_kthread (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
