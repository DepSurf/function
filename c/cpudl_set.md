# Function: <code>cpudl_set</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void cpudl_set(struct cpudl *cp, int cpu, u64 dl, int is_valid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff810c4620)
Location: kernel/sched/cpudeadline.c:132
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:rq_offline_dl
```
**Symbols:**

```
ffffffff810c4620-ffffffff810c47ea: cpudl_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void cpudl_set(struct cpudl *cp, int cpu, u64 dl, int is_valid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff810c82f0)
Location: kernel/sched/cpudeadline.c:132
Inline: False
Direct callers:
  - kernel/sched/deadline.c:rq_offline_dl
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
```
**Symbols:**

```
ffffffff810c82f0-ffffffff810c84a4: cpudl_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cpudl_set(struct cpudl *cp, int cpu, u64 dl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff810ce3e0)
Location: kernel/sched/cpudeadline.c:196
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:__dequeue_dl_entity
```
**Symbols:**

```
ffffffff810ce3e0-ffffffff810ce4a3: cpudl_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void cpudl_set(struct cpudl *cp, int cpu, u64 dl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff810cacf0)
Location: kernel/sched/cpudeadline.c:196
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:__dequeue_dl_entity
```
**Symbols:**

```
ffffffff810cacf0-ffffffff810cada4: cpudl_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cpudl_set(struct cpudl *cp, int cpu, u64 dl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff810d2490)
Location: kernel/sched/cpudeadline.c:196
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:__dequeue_dl_entity
```
**Symbols:**

```
ffffffff810d2490-ffffffff810d2544: cpudl_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void cpudl_set(struct cpudl *cp, int cpu, u64 dl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff810da570)
Location: kernel/sched/cpudeadline.c:194
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:__dequeue_dl_entity
```
**Symbols:**

```
ffffffff810da570-ffffffff810da624: cpudl_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cpudl_set(struct cpudl *cp, int cpu, u64 dl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff810e40c0)
Location: kernel/sched/cpudeadline.c:194
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:__dequeue_dl_entity
```
**Symbols:**

```
ffffffff810e40c0-ffffffff810e4174: cpudl_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void cpudl_set(struct cpudl *cp, int cpu, u64 dl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/cpudeadline.c (0)
Location: kernel/sched/cpudeadline.c:190
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
```
**Symbols:**

```
ffffffff810eae98-ffffffff810eaeab: cpudl_set.cold (STB_LOCAL)
ffffffff810eacc0-ffffffff810ead75: cpudl_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cpudl_set(struct cpudl *cp, int cpu, u64 dl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff810f6690)
Location: kernel/sched/cpudeadline.c:190
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
```
**Symbols:**

```
ffffffff810f6690-ffffffff810f674c: cpudl_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void cpudl_set(struct cpudl *cp, int cpu, u64 dl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff81100020)
Location: kernel/sched/cpudeadline.c:190
Inline: False
Direct callers:
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:__enqueue_dl_entity
```
**Symbols:**

```
ffffffff81100020-ffffffff811000da: cpudl_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void cpudl_set(struct cpudl *cp, int cpu, u64 dl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff810feb80)
Location: kernel/sched/cpudeadline.c:214
Inline: False
Direct callers:
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:__enqueue_dl_entity
```
**Symbols:**

```
ffffffff810feb80-ffffffff810fec3a: cpudl_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void cpudl_set(struct cpudl *cp, int cpu, u64 dl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff81100f60)
Location: kernel/sched/cpudeadline.c:214
Inline: False
Direct callers:
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:__enqueue_dl_entity
```
**Symbols:**

```
ffffffff81100f60-ffffffff8110101a: cpudl_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void cpudl_set(struct cpudl *cp, int cpu, u64 dl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff8111d100)
Location: kernel/sched/cpudeadline.c:214
Inline: False
Direct callers:
  - kernel/sched/deadline.c:__dequeue_dl_entity
  - kernel/sched/deadline.c:__enqueue_dl_entity
```
**Symbols:**

```
ffffffff8111d100-ffffffff8111d1ba: cpudl_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void cpudl_set(struct cpudl *cp, int cpu, u64 dl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81134f50)
Location: kernel/sched/cpudeadline.c:213
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:__dequeue_dl_entity
```
**Symbols:**

```
ffffffff81134f50-ffffffff81135011: cpudl_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void cpudl_set(struct cpudl *cp, int cpu, u64 dl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8115f490)
Location: kernel/sched/cpudeadline.c:213
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:__dequeue_task_dl
  - kernel/sched/build_policy.c:enqueue_dl_entity
```
**Symbols:**

```
ffffffff8115f490-ffffffff8115f551: cpudl_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void cpudl_set(struct cpudl *cp, int cpu, u64 dl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8116fb80)
Location: kernel/sched/cpudeadline.c:213
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:__dequeue_task_dl
  - kernel/sched/build_policy.c:enqueue_dl_entity
```
**Symbols:**

```
ffffffff8116fb80-ffffffff8116fc41: cpudl_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void cpudl_set(struct cpudl *cp, int cpu, u64 dl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8117d0d0)
Location: kernel/sched/cpudeadline.c:213
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:enqueue_dl_entity
  - kernel/sched/build_policy.c:__dequeue_dl_entity
```
**Symbols:**

```
ffffffff8117d0d0-ffffffff8117d191: cpudl_set (STB_GLOBAL)
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
void cpudl_set(struct cpudl *cp, int cpu, u64 dl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (ffff80001015a630)
Location: kernel/sched/cpudeadline.c:190
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
```
**Symbols:**

```
ffff80001015a630-ffff80001015a7ac: cpudl_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cpudl_set(struct cpudl *cp, int cpu, u64 dl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (c03a7390)
Location: kernel/sched/cpudeadline.c:190
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
```
**Symbols:**

```
c03a7390-c03a7494: cpudl_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cpudl_set(struct cpudl *cp, int cpu, u64 dl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (c0000000001ae8f0)
Location: kernel/sched/cpudeadline.c:190
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
```
**Symbols:**

```
c0000000001ae8f0-c0000000001aea64: cpudl_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void cpudl_set(struct cpudl *cp, int cpu, u64 dl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffe0000fff38)
Location: kernel/sched/cpudeadline.c:190
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
```
**Symbols:**

```
ffffffe0000fff38-ffffffe000100030: cpudl_set (STB_GLOBAL)
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
void cpudl_set(struct cpudl *cp, int cpu, u64 dl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff810efa90)
Location: kernel/sched/cpudeadline.c:190
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
```
**Symbols:**

```
ffffffff810efa90-ffffffff810efb4c: cpudl_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cpudl_set(struct cpudl *cp, int cpu, u64 dl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff810dfb00)
Location: kernel/sched/cpudeadline.c:190
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
```
**Symbols:**

```
ffffffff810dfb00-ffffffff810dfbbc: cpudl_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cpudl_set(struct cpudl *cp, int cpu, u64 dl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff810ecbc0)
Location: kernel/sched/cpudeadline.c:190
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
```
**Symbols:**

```
ffffffff810ecbc0-ffffffff810ecc7c: cpudl_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cpudl_set(struct cpudl *cp, int cpu, u64 dl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff810f7c00)
Location: kernel/sched/cpudeadline.c:190
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_dl_entity
  - kernel/sched/deadline.c:__dequeue_dl_entity
```
**Symbols:**

```
ffffffff810f7c00-ffffffff810f7cbc: cpudl_set (STB_GLOBAL)
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
<b>Param removed. </b>
<code>int is_valid</code>
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
