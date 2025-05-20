# Function: <code>task_numa_group</code>

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
In kernel/sched/fair.c (ffffffff810ba636)
Location: kernel/sched/fair.c:1948
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
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
In kernel/sched/fair.c (ffffffff810bdff1)
Location: kernel/sched/fair.c:2061
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
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
In kernel/sched/fair.c (ffffffff810c34e9)
Location: kernel/sched/fair.c:2193
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
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
In kernel/sched/fair.c (ffffffff810bdccc)
Location: kernel/sched/fair.c:2189
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
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
In kernel/sched/fair.c (ffffffff810c59bc)
Location: kernel/sched/fair.c:2241
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
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
In kernel/sched/fair.c (ffffffff810cd633)
Location: kernel/sched/fair.c:2269
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
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
In kernel/sched/fair.c (ffffffff810d5ed3)
Location: kernel/sched/fair.c:2215
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
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
In kernel/sched/fair.c (ffffffff810de946)
Location: kernel/sched/fair.c:2286
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
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
In kernel/sched/fair.c (ffffffff810e8e96)
Location: kernel/sched/fair.c:2244
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void task_numa_group(struct task_struct *p, int cpupid, int flags, int *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ef0f0)
Location: kernel/sched/fair.c:2473
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
```
**Symbols:**

```
ffffffff810ef0f0-ffffffff810ef3ae: task_numa_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void task_numa_group(struct task_struct *p, int cpupid, int flags, int *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ed0c0)
Location: kernel/sched/fair.c:2487
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
```
**Symbols:**

```
ffffffff810ed0c0-ffffffff810ed38d: task_numa_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void task_numa_group(struct task_struct *p, int cpupid, int flags, int *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f08c0)
Location: kernel/sched/fair.c:2484
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
```
**Symbols:**

```
ffffffff810f08c0-ffffffff810f0b9c: task_numa_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void task_numa_group(struct task_struct *p, int cpupid, int flags, int *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81109340)
Location: kernel/sched/fair.c:2473
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
```
**Symbols:**

```
ffffffff81109340-ffffffff8110961c: task_numa_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void task_numa_group(struct task_struct *p, int cpupid, int flags, int *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8111d800)
Location: kernel/sched/fair.c:2493
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
```
**Symbols:**

```
ffffffff8111d800-ffffffff8111dada: task_numa_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void task_numa_group(struct task_struct *p, int cpupid, int flags, int *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81144ba0)
Location: kernel/sched/fair.c:2688
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
```
**Symbols:**

```
ffffffff81144ba0-ffffffff81144e82: task_numa_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void task_numa_group(struct task_struct *p, int cpupid, int flags, int *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff811550c0)
Location: kernel/sched/fair.c:2688
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
```
**Symbols:**

```
ffffffff811550c0-ffffffff81155399: task_numa_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void task_numa_group(struct task_struct *p, int cpupid, int flags, int *priv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81161b20)
Location: kernel/sched/fair.c:2917
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
```
**Symbols:**

```
ffffffff81161b20-ffffffff81161df9: task_numa_group (STB_LOCAL)
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
In kernel/sched/fair.c (ffff800010148e68)
Location: kernel/sched/fair.c:2244
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c00000000019aad0)
Location: kernel/sched/fair.c:2244
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e3046)
Location: kernel/sched/fair.c:2244
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
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
In kernel/sched/fair.c (ffffffff810d2156)
Location: kernel/sched/fair.c:2244
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
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
In kernel/sched/fair.c (ffffffff810df3c6)
Location: kernel/sched/fair.c:2244
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
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
In kernel/sched/fair.c (ffffffff810eaf06)
Location: kernel/sched/fair.c:2244
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
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
