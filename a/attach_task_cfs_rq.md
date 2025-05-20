# Function: <code>attach_task_cfs_rq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void attach_task_cfs_rq(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810b2e50)
Location: kernel/sched/fair.c:8022
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_move_group_fair
```
**Symbols:**

```
ffffffff810b2e50-ffffffff810b2ec3: attach_task_cfs_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void attach_task_cfs_rq(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810b9ba0)
Location: kernel/sched/fair.c:8462
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_change_group_fair
```
**Symbols:**

```
ffffffff810b9ba0-ffffffff810ba0cb: attach_task_cfs_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void attach_task_cfs_rq(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c0bf0)
Location: kernel/sched/fair.c:9097
Inline: False
```
**Symbols:**

```
ffffffff810c0bf0-ffffffff810c0c42: attach_task_cfs_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void attach_task_cfs_rq(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bab00)
Location: kernel/sched/fair.c:9121
Inline: False
```
**Symbols:**

```
ffffffff810bab00-ffffffff810bab58: attach_task_cfs_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void attach_task_cfs_rq(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c2af0)
Location: kernel/sched/fair.c:9594
Inline: False
```
**Symbols:**

```
ffffffff810c2af0-ffffffff810c2b48: attach_task_cfs_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void attach_task_cfs_rq(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810cb550)
Location: kernel/sched/fair.c:10101
Inline: False
```
**Symbols:**

```
ffffffff810cb550-ffffffff810cb5a8: attach_task_cfs_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void attach_task_cfs_rq(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d22e0)
Location: kernel/sched/fair.c:10205
Inline: False
```
**Symbols:**

```
ffffffff810d22e0-ffffffff810d2338: attach_task_cfs_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void attach_task_cfs_rq(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810dd290)
Location: kernel/sched/fair.c:10145
Inline: False
```
**Symbols:**

```
ffffffff810dd290-ffffffff810dd2e8: attach_task_cfs_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void attach_task_cfs_rq(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e76c0)
Location: kernel/sched/fair.c:10130
Inline: False
```
**Symbols:**

```
ffffffff810e76c0-ffffffff810e7718: attach_task_cfs_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void attach_task_cfs_rq(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ed9a0)
Location: kernel/sched/fair.c:10815
Inline: True
Direct callers:
  - kernel/sched/fair.c:task_change_group_fair
```
**Symbols:**

```
ffffffff810ed9a0-ffffffff810ed9f8: attach_task_cfs_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void attach_task_cfs_rq(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810eb7d0)
Location: kernel/sched/fair.c:10929
Inline: True
Direct callers:
  - kernel/sched/fair.c:task_change_group_fair
```
**Symbols:**

```
ffffffff810eb7d0-ffffffff810eb82b: attach_task_cfs_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void attach_task_cfs_rq(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ed6b0)
Location: kernel/sched/fair.c:10995
Inline: True
Direct callers:
  - kernel/sched/fair.c:task_change_group_fair
```
**Symbols:**

```
ffffffff810ed6b0-ffffffff810ed70b: attach_task_cfs_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void attach_task_cfs_rq(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff811063c0)
Location: kernel/sched/fair.c:11361
Inline: True
Direct callers:
  - kernel/sched/fair.c:task_change_group_fair
```
**Symbols:**

```
ffffffff811063c0-ffffffff81106419: attach_task_cfs_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void attach_task_cfs_rq(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81121320)
Location: kernel/sched/fair.c:11479
Inline: True
Direct callers:
  - kernel/sched/fair.c:task_change_group_fair
```
**Symbols:**

```
ffffffff81121320-ffffffff8112137e: attach_task_cfs_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void attach_task_cfs_rq(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8114a270)
Location: kernel/sched/fair.c:12012
Inline: True
```
**Symbols:**

```
ffffffff8114a270-ffffffff8114a2ce: attach_task_cfs_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void attach_task_cfs_rq(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8115a140)
Location: kernel/sched/fair.c:12330
Inline: True
```
**Symbols:**

```
ffffffff8115a140-ffffffff8115a19e: attach_task_cfs_rq (STB_LOCAL)
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
In kernel/sched/fair.c (ffffffff811668f5)
Location: kernel/sched/fair.c:12757
Inline: True
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
void attach_task_cfs_rq(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffff800010145e68)
Location: kernel/sched/fair.c:10130
Inline: False
```
**Symbols:**

```
ffff800010145e68-ffff800010145edc: attach_task_cfs_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void attach_task_cfs_rq(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c0393b48)
Location: kernel/sched/fair.c:10130
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_change_group_fair
```
**Symbols:**

```
c0393b48-c0393bc4: attach_task_cfs_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void attach_task_cfs_rq(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c000000000198d00)
Location: kernel/sched/fair.c:10130
Inline: False
```
**Symbols:**

```
c000000000198d00-c000000000198d90: attach_task_cfs_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void attach_task_cfs_rq(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffe0000f0a5a)
Location: kernel/sched/fair.c:10130
Inline: False
```
**Symbols:**

```
ffffffe0000f0a5a-ffffffe0000f0abc: attach_task_cfs_rq (STB_LOCAL)
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
void attach_task_cfs_rq(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e1870)
Location: kernel/sched/fair.c:10130
Inline: False
```
**Symbols:**

```
ffffffff810e1870-ffffffff810e18c8: attach_task_cfs_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void attach_task_cfs_rq(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d0950)
Location: kernel/sched/fair.c:10130
Inline: False
```
**Symbols:**

```
ffffffff810d0950-ffffffff810d09a8: attach_task_cfs_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void attach_task_cfs_rq(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ddbf0)
Location: kernel/sched/fair.c:10130
Inline: False
```
**Symbols:**

```
ffffffff810ddbf0-ffffffff810ddc48: attach_task_cfs_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void attach_task_cfs_rq(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e96d0)
Location: kernel/sched/fair.c:10130
Inline: False
```
**Symbols:**

```
ffffffff810e96d0-ffffffff810e9728: attach_task_cfs_rq (STB_LOCAL)
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
