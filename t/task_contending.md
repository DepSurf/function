# Function: <code>task_contending</code>

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
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void task_contending(struct sched_dl_entity *dl_se, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810c62d0)
Location: kernel/sched/deadline.c:258
Inline: True
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
```
**Symbols:**

```
ffffffff810c62d0-ffffffff810c641c: task_contending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void task_contending(struct sched_dl_entity *dl_se, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810cdaf0)
Location: kernel/sched/deadline.c:259
Inline: True
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
```
**Symbols:**

```
ffffffff810cdaf0-ffffffff810cdc48: task_contending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void task_contending(struct sched_dl_entity *dl_se, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810d6360)
Location: kernel/sched/deadline.c:293
Inline: True
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
```
**Symbols:**

```
ffffffff810d6360-ffffffff810d6507: task_contending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void task_contending(struct sched_dl_entity *dl_se, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810e08a0)
Location: kernel/sched/deadline.c:294
Inline: True
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
```
**Symbols:**

```
ffffffff810e08a0-ffffffff810e0a47: task_contending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void task_contending(struct sched_dl_entity *dl_se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810e69c0)
Location: kernel/sched/deadline.c:293
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
```
**Symbols:**

```
ffffffff810e69c0-ffffffff810e6b90: task_contending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void task_contending(struct sched_dl_entity *dl_se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810f21e0)
Location: kernel/sched/deadline.c:293
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
```
**Symbols:**

```
ffffffff810f21e0-ffffffff810f23b0: task_contending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void task_contending(struct sched_dl_entity *dl_se, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810fac80)
Location: kernel/sched/deadline.c:293
Inline: True
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
```
**Symbols:**

```
ffffffff810fac80-ffffffff810fae81: task_contending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void task_contending(struct sched_dl_entity *dl_se, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810f9130)
Location: kernel/sched/deadline.c:370
Inline: True
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
```
**Symbols:**

```
ffffffff810f9130-ffffffff810f9331: task_contending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void task_contending(struct sched_dl_entity *dl_se, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810fb0e0)
Location: kernel/sched/deadline.c:370
Inline: True
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
```
**Symbols:**

```
ffffffff810fb0e0-ffffffff810fb2dd: task_contending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void task_contending(struct sched_dl_entity *dl_se, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/deadline.c (ffffffff81116c6d)
Location: kernel/sched/deadline.c:370
Inline: True
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
```
**Symbols:**

```
ffffffff81116b80-ffffffff81116dcf: task_contending (STB_LOCAL)
ffffffff81ca69ec-ffffffff81ca6a3e: task_contending.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void task_contending(struct sched_dl_entity *dl_se, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81131e99)
Location: kernel/sched/deadline.c:444
Inline: True
Direct callers:
  - kernel/sched/build_policy.c:enqueue_task_dl
  - kernel/sched/build_policy.c:enqueue_dl_entity
```
**Symbols:**

```
ffffffff81131da0-ffffffff81131ff9: task_contending (STB_LOCAL)
ffffffff81e561b2-ffffffff81e56204: task_contending.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void task_contending(struct sched_dl_entity *dl_se, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8115c159)
Location: kernel/sched/deadline.c:446
Inline: True
Direct callers:
  - kernel/sched/build_policy.c:enqueue_task_dl
  - kernel/sched/build_policy.c:enqueue_dl_entity
```
**Symbols:**

```
ffffffff8115c060-ffffffff8115c2b9: task_contending (STB_LOCAL)
ffffffff820573b8-ffffffff8205740a: task_contending.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void task_contending(struct sched_dl_entity *dl_se, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8116c0d9)
Location: kernel/sched/deadline.c:448
Inline: True
Direct callers:
  - kernel/sched/build_policy.c:enqueue_task_dl
  - kernel/sched/build_policy.c:enqueue_dl_entity
```
**Symbols:**

```
ffffffff8116bfe0-ffffffff8116c23b: task_contending (STB_LOCAL)
ffffffff820d5bde-ffffffff820d5c30: task_contending.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void task_contending(struct sched_dl_entity *dl_se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (0)
Location: kernel/sched/deadline.c:471
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:enqueue_dl_entity
```
**Symbols:**

```
ffffffff81179360-ffffffff811795d3: task_contending (STB_LOCAL)
ffffffff821b0ca6-ffffffff821b0cf8: task_contending.cold (STB_LOCAL)
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
void task_contending(struct sched_dl_entity *dl_se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffff8000101543b8)
Location: kernel/sched/deadline.c:293
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
```
**Symbols:**

```
ffff8000101543b8-ffff800010154594: task_contending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void task_contending(struct sched_dl_entity *dl_se, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (c03a0e18)
Location: kernel/sched/deadline.c:293
Inline: True
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
```
**Symbols:**

```
c03a0e18-c03a10ac: task_contending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void task_contending(struct sched_dl_entity *dl_se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (c0000000001a81f0)
Location: kernel/sched/deadline.c:293
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
```
**Symbols:**

```
c0000000001a81f0-c0000000001a84d4: task_contending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void task_contending(struct sched_dl_entity *dl_se, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffe0000fa9f4)
Location: kernel/sched/deadline.c:293
Inline: True
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
```
**Symbols:**

```
ffffffe0000fa9f4-ffffffe0000fab44: task_contending (STB_LOCAL)
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
void task_contending(struct sched_dl_entity *dl_se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810eb5e0)
Location: kernel/sched/deadline.c:293
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
```
**Symbols:**

```
ffffffff810eb5e0-ffffffff810eb7b0: task_contending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void task_contending(struct sched_dl_entity *dl_se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810db600)
Location: kernel/sched/deadline.c:293
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
```
**Symbols:**

```
ffffffff810db600-ffffffff810db7d0: task_contending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void task_contending(struct sched_dl_entity *dl_se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810e8710)
Location: kernel/sched/deadline.c:293
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
```
**Symbols:**

```
ffffffff810e8710-ffffffff810e88e0: task_contending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void task_contending(struct sched_dl_entity *dl_se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810f36c0)
Location: kernel/sched/deadline.c:293
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:enqueue_dl_entity
```
**Symbols:**

```
ffffffff810f36c0-ffffffff810f3890: task_contending (STB_LOCAL)
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
