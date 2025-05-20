# Function: <code>task_scan_start</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int task_scan_start(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810be490)
Location: kernel/sched/fair.c:1113
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_tick_numa
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_migrate
```
**Symbols:**

```
ffffffff810be490-ffffffff810be5bf: task_scan_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int task_scan_start(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c65e0)
Location: kernel/sched/fair.c:1100
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_tick_numa
  - kernel/sched/fair.c:task_numa_work
  - kernel/sched/fair.c:task_numa_migrate
```
**Symbols:**

```
ffffffff810c65e0-ffffffff810c670e: task_scan_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int task_scan_start(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ceb60)
Location: kernel/sched/fair.c:1096
Inline: False
Direct callers:
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:task_tick_numa
  - kernel/sched/fair.c:task_numa_work
```
**Symbols:**

```
ffffffff810ceb60-ffffffff810cec8e: task_scan_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int task_scan_start(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d7430)
Location: kernel/sched/fair.c:1143
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:task_numa_work
```
**Symbols:**

```
ffffffff810d7430-ffffffff810d755e: task_scan_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int task_scan_start(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e1a40)
Location: kernel/sched/fair.c:1142
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:task_numa_work
```
**Symbols:**

```
ffffffff810e1a40-ffffffff810e1b6e: task_scan_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int task_scan_start(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e95c0)
Location: kernel/sched/fair.c:1153
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:task_numa_work
```
**Symbols:**

```
ffffffff810e95c0-ffffffff810e9730: task_scan_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int task_scan_start(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e73e0)
Location: kernel/sched/fair.c:1160
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:task_numa_work
```
**Symbols:**

```
ffffffff810e73e0-ffffffff810e755f: task_scan_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int task_scan_start(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e92d0)
Location: kernel/sched/fair.c:1157
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:task_numa_work
```
**Symbols:**

```
ffffffff810e92d0-ffffffff810e9447: task_scan_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int task_scan_start(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81100b60)
Location: kernel/sched/fair.c:1146
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:task_numa_work
```
**Symbols:**

```
ffffffff81100b60-ffffffff81100cdb: task_scan_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int task_scan_start(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8111c0a0)
Location: kernel/sched/fair.c:1148
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:task_numa_work
```
**Symbols:**

```
ffffffff8111c0a0-ffffffff8111c22e: task_scan_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int task_scan_start(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81143980)
Location: kernel/sched/fair.c:1187
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:task_numa_work
```
**Symbols:**

```
ffffffff81143980-ffffffff81143af4: task_scan_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int task_scan_start(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81153950)
Location: kernel/sched/fair.c:1204
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:task_numa_work
```
**Symbols:**

```
ffffffff81153950-ffffffff81153ac0: task_scan_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int task_scan_start(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8115fac0)
Location: kernel/sched/fair.c:1445
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:task_numa_work
```
**Symbols:**

```
ffffffff8115fac0-ffffffff8115fc30: task_scan_start (STB_LOCAL)
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
unsigned int task_scan_start(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffff800010141f68)
Location: kernel/sched/fair.c:1142
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:task_numa_work
```
**Symbols:**

```
ffff800010141f68-ffff8000101420c0: task_scan_start (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned int task_scan_start(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c0000000001925f0)
Location: kernel/sched/fair.c:1142
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:task_numa_work
```
**Symbols:**

```
c0000000001925f0-c0000000001927cc: task_scan_start (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
unsigned int task_scan_start(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810dbbf0)
Location: kernel/sched/fair.c:1142
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:task_numa_work
```
**Symbols:**

```
ffffffff810dbbf0-ffffffff810dbd1e: task_scan_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int task_scan_start(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810cac00)
Location: kernel/sched/fair.c:1142
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:task_numa_work
```
**Symbols:**

```
ffffffff810cac00-ffffffff810cad2e: task_scan_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int task_scan_start(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d7f70)
Location: kernel/sched/fair.c:1142
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:task_numa_work
```
**Symbols:**

```
ffffffff810d7f70-ffffffff810d809e: task_scan_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int task_scan_start(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e3a10)
Location: kernel/sched/fair.c:1142
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/sched/fair.c:migrate_task_rq_fair
  - kernel/sched/fair.c:task_numa_work
```
**Symbols:**

```
ffffffff810e3a10-ffffffff810e3b50: task_scan_start (STB_LOCAL)
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
