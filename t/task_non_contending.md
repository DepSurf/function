# Function: <code>task_non_contending</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void task_non_contending(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810c6f30)
Location: kernel/sched/deadline.c:204
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dequeue_task_dl
```
**Symbols:**

```
ffffffff810c6f30-ffffffff810c729f: task_non_contending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void task_non_contending(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810ce500)
Location: kernel/sched/deadline.c:205
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dequeue_task_dl
```
**Symbols:**

```
ffffffff810ce500-ffffffff810ce865: task_non_contending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void task_non_contending(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810d7600)
Location: kernel/sched/deadline.c:236
Inline: False
Direct callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:dequeue_task_dl
```
**Symbols:**

```
ffffffff810d7600-ffffffff810d79f7: task_non_contending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void task_non_contending(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810e0230)
Location: kernel/sched/deadline.c:237
Inline: False
Direct callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:dequeue_task_dl
```
**Symbols:**

```
ffffffff810e0230-ffffffff810e0627: task_non_contending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void task_non_contending(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/deadline.c (0)
Location: kernel/sched/deadline.c:237
Inline: False
Direct callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:dequeue_task_dl
```
**Symbols:**

```
ffffffff810e6d90-ffffffff810e715f: task_non_contending (STB_LOCAL)
ffffffff810e96af-ffffffff810e96c9: task_non_contending.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void task_non_contending(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810f23b0)
Location: kernel/sched/deadline.c:237
Inline: False
Direct callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:dequeue_task_dl
```
**Symbols:**

```
ffffffff810f23b0-ffffffff810f277f: task_non_contending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void task_non_contending(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810fbb80)
Location: kernel/sched/deadline.c:237
Inline: False
Direct callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:dequeue_task_dl
```
**Symbols:**

```
ffffffff810fbb80-ffffffff810fbf7f: task_non_contending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void task_non_contending(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810fa0a0)
Location: kernel/sched/deadline.c:314
Inline: False
Direct callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:dequeue_task_dl
```
**Symbols:**

```
ffffffff810fa0a0-ffffffff810fa4dc: task_non_contending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void task_non_contending(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810fbfb0)
Location: kernel/sched/deadline.c:314
Inline: False
Direct callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:dequeue_task_dl
```
**Symbols:**

```
ffffffff810fbfb0-ffffffff810fc40a: task_non_contending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void task_non_contending(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/deadline.c (0)
Location: kernel/sched/deadline.c:314
Inline: False
Direct callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:dequeue_task_dl
```
**Symbols:**

```
ffffffff81117a00-ffffffff81117f75: task_non_contending (STB_LOCAL)
ffffffff81ca6b7d-ffffffff81ca6bf6: task_non_contending.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void task_non_contending(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (0)
Location: kernel/sched/deadline.c:388
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:switched_from_dl
  - kernel/sched/build_policy.c:dequeue_task_dl
```
**Symbols:**

```
ffffffff81132510-ffffffff81132a6e: task_non_contending (STB_LOCAL)
ffffffff81e562c8-ffffffff81e5634d: task_non_contending.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void task_non_contending(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (0)
Location: kernel/sched/deadline.c:390
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:switched_from_dl
  - kernel/sched/build_policy.c:dequeue_task_dl
```
**Symbols:**

```
ffffffff8115c7f0-ffffffff8115cd63: task_non_contending (STB_LOCAL)
ffffffff820574ce-ffffffff82057553: task_non_contending.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void task_non_contending(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (0)
Location: kernel/sched/deadline.c:392
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:switched_from_dl
  - kernel/sched/build_policy.c:dequeue_task_dl
```
**Symbols:**

```
ffffffff8116d5a0-ffffffff8116db23: task_non_contending (STB_LOCAL)
ffffffff820d5db4-ffffffff820d5e39: task_non_contending.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void task_non_contending(struct sched_dl_entity *dl_se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (0)
Location: kernel/sched/deadline.c:407
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:switched_from_dl
  - kernel/sched/build_policy.c:dl_server_stop
```
**Symbols:**

```
ffffffff8117a250-ffffffff8117a8fa: task_non_contending (STB_LOCAL)
ffffffff821b0dbc-ffffffff821b0e6d: task_non_contending.cold (STB_LOCAL)
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
void task_non_contending(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffff800010154598)
Location: kernel/sched/deadline.c:237
Inline: False
Direct callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:dequeue_task_dl
```
**Symbols:**

```
ffff800010154598-ffff800010154994: task_non_contending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void task_non_contending(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (c03a10ac)
Location: kernel/sched/deadline.c:237
Inline: False
Direct callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:dequeue_task_dl
```
**Symbols:**

```
c03a10ac-c03a166c: task_non_contending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void task_non_contending(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (c0000000001a84e0)
Location: kernel/sched/deadline.c:237
Inline: False
Direct callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:dequeue_task_dl
```
**Symbols:**

```
c0000000001a84e0-c0000000001a89cc: task_non_contending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void task_non_contending(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffe0000fc20c)
Location: kernel/sched/deadline.c:237
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dequeue_task_dl
```
**Symbols:**

```
ffffffe0000fc20c-ffffffe0000fc538: task_non_contending (STB_LOCAL)
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
void task_non_contending(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810eb7b0)
Location: kernel/sched/deadline.c:237
Inline: False
Direct callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:dequeue_task_dl
```
**Symbols:**

```
ffffffff810eb7b0-ffffffff810ebb7f: task_non_contending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void task_non_contending(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810db7d0)
Location: kernel/sched/deadline.c:237
Inline: False
Direct callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:dequeue_task_dl
```
**Symbols:**

```
ffffffff810db7d0-ffffffff810dbb9f: task_non_contending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void task_non_contending(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810e88e0)
Location: kernel/sched/deadline.c:237
Inline: False
Direct callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:dequeue_task_dl
```
**Symbols:**

```
ffffffff810e88e0-ffffffff810e8caf: task_non_contending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void task_non_contending(struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810f3890)
Location: kernel/sched/deadline.c:237
Inline: False
Direct callers:
  - kernel/sched/deadline.c:switched_from_dl
  - kernel/sched/deadline.c:dequeue_task_dl
```
**Symbols:**

```
ffffffff810f3890-ffffffff810f3c5d: task_non_contending (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct sched_dl_entity *dl_se</code>
</li>
<li>
<b>Param removed. </b>
<code>struct task_struct *p</code>
</li>
</ul>
</details>
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
