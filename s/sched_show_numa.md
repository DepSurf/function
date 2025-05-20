# Function: <code>sched_show_numa</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810c893f)
Location: kernel/sched/debug.c:522
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810cc922)
Location: kernel/sched/debug.c:833
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
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
In kernel/sched/debug.c (ffffffff810d2942)
Location: kernel/sched/debug.c:836
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
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
In kernel/sched/debug.c (ffffffff810d1a9e)
Location: kernel/sched/debug.c:850
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810d963f)
Location: kernel/sched/debug.c:900
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810e0654)
Location: kernel/sched/debug.c:852
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810eae0a)
Location: kernel/sched/debug.c:851
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810f1c27)
Location: kernel/sched/debug.c:831
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810fd8e7)
Location: kernel/sched/debug.c:831
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void sched_show_numa(struct task_struct *p, struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:837
Inline: False
Direct callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
**Symbols:**

```
ffffffff81105a00-ffffffff81105b3c: sched_show_numa (STB_LOCAL)
ffffffff81108d24-ffffffff81108dc2: sched_show_numa.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void sched_show_numa(struct task_struct *p, struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:891
Inline: False
Direct callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
**Symbols:**

```
ffffffff81104050-ffffffff8110418c: sched_show_numa (STB_LOCAL)
ffffffff81bdd108-ffffffff81bdd1a6: sched_show_numa.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void sched_show_numa(struct task_struct *p, struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:905
Inline: False
Direct callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
**Symbols:**

```
ffffffff81106d70-ffffffff81106eac: sched_show_numa (STB_LOCAL)
ffffffff81bcf648-ffffffff81bcf6e6: sched_show_numa.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void sched_show_numa(struct task_struct *p, struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:921
Inline: False
Direct callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
**Symbols:**

```
ffffffff81124950-ffffffff81124ab7: sched_show_numa (STB_LOCAL)
ffffffff81ca7c24-ffffffff81ca7ce8: sched_show_numa.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void sched_show_numa(struct task_struct *p, struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/debug.c:930
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:proc_sched_show_task
```
**Symbols:**

```
ffffffff8113d580-ffffffff8113d6af: sched_show_numa (STB_LOCAL)
ffffffff81e56a88-ffffffff81e56b3c: sched_show_numa.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sched_show_numa(struct task_struct *p, struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81168000)
Location: kernel/sched/debug.c:931
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:proc_sched_show_task
```
**Symbols:**

```
ffffffff81168000-ffffffff811681e8: sched_show_numa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sched_show_numa(struct task_struct *p, struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff811786c0)
Location: kernel/sched/debug.c:977
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:proc_sched_show_task
```
**Symbols:**

```
ffffffff811786c0-ffffffff811788a8: sched_show_numa (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sched_show_numa(struct task_struct *p, struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff811863e0)
Location: kernel/sched/debug.c:974
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:proc_sched_show_task
```
**Symbols:**

```
ffffffff811863e0-ffffffff811865c8: sched_show_numa (STB_LOCAL)
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
In kernel/sched/debug.c (ffff8000101630ec)
Location: kernel/sched/debug.c:831
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
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
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:831
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (c0000000001b98ec)
Location: kernel/sched/debug.c:831
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
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
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:831
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810f6c07)
Location: kernel/sched/debug.c:831
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810e6dd7)
Location: kernel/sched/debug.c:831
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810f3e17)
Location: kernel/sched/debug.c:831
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810fee07)
Location: kernel/sched/debug.c:831
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
