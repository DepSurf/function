# Function: <code>cpudl_clear</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cpudl_clear(struct cpudl *cp, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff810ce310)
Location: kernel/sched/cpudeadline.c:156
Inline: False
Direct callers:
  - kernel/sched/deadline.c:rq_offline_dl
  - kernel/sched/deadline.c:__dequeue_dl_entity
```
**Symbols:**

```
ffffffff810ce310-ffffffff810ce3d5: cpudl_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void cpudl_clear(struct cpudl *cp, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff810cac30)
Location: kernel/sched/cpudeadline.c:156
Inline: False
Direct callers:
  - kernel/sched/deadline.c:rq_offline_dl
  - kernel/sched/deadline.c:__dequeue_dl_entity
```
**Symbols:**

```
ffffffff810cac30-ffffffff810cace6: cpudl_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cpudl_clear(struct cpudl *cp, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff810d23d0)
Location: kernel/sched/cpudeadline.c:156
Inline: False
Direct callers:
  - kernel/sched/deadline.c:rq_offline_dl
  - kernel/sched/deadline.c:__dequeue_dl_entity
```
**Symbols:**

```
ffffffff810d23d0-ffffffff810d2486: cpudl_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void cpudl_clear(struct cpudl *cp, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff810da4b0)
Location: kernel/sched/cpudeadline.c:154
Inline: False
Direct callers:
  - kernel/sched/deadline.c:rq_offline_dl
  - kernel/sched/deadline.c:__dequeue_dl_entity
```
**Symbols:**

```
ffffffff810da4b0-ffffffff810da566: cpudl_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cpudl_clear(struct cpudl *cp, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff810e4000)
Location: kernel/sched/cpudeadline.c:154
Inline: False
Direct callers:
  - kernel/sched/deadline.c:rq_offline_dl
  - kernel/sched/deadline.c:__dequeue_dl_entity
```
**Symbols:**

```
ffffffff810e4000-ffffffff810e40b6: cpudl_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void cpudl_clear(struct cpudl *cp, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/cpudeadline.c (0)
Location: kernel/sched/cpudeadline.c:150
Inline: False
Direct callers:
  - kernel/sched/deadline.c:rq_offline_dl
  - kernel/sched/deadline.c:__dequeue_dl_entity
```
**Symbols:**

```
ffffffff810eae85-ffffffff810eae98: cpudl_clear.cold (STB_LOCAL)
ffffffff810eac00-ffffffff810eacb5: cpudl_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cpudl_clear(struct cpudl *cp, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff810f65d0)
Location: kernel/sched/cpudeadline.c:150
Inline: False
Direct callers:
  - kernel/sched/deadline.c:rq_offline_dl
  - kernel/sched/deadline.c:__dequeue_dl_entity
```
**Symbols:**

```
ffffffff810f65d0-ffffffff810f668c: cpudl_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void cpudl_clear(struct cpudl *cp, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff810fff60)
Location: kernel/sched/cpudeadline.c:150
Inline: False
Direct callers:
  - kernel/sched/deadline.c:rq_offline_dl
  - kernel/sched/deadline.c:__dequeue_dl_entity
```
**Symbols:**

```
ffffffff810fff60-ffffffff8110001f: cpudl_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void cpudl_clear(struct cpudl *cp, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff810feac0)
Location: kernel/sched/cpudeadline.c:174
Inline: False
Direct callers:
  - kernel/sched/deadline.c:rq_offline_dl
  - kernel/sched/deadline.c:__dequeue_dl_entity
```
**Symbols:**

```
ffffffff810feac0-ffffffff810feb7f: cpudl_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void cpudl_clear(struct cpudl *cp, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff81100ea0)
Location: kernel/sched/cpudeadline.c:174
Inline: False
Direct callers:
  - kernel/sched/deadline.c:rq_offline_dl
  - kernel/sched/deadline.c:__dequeue_dl_entity
```
**Symbols:**

```
ffffffff81100ea0-ffffffff81100f5f: cpudl_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void cpudl_clear(struct cpudl *cp, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff8111d040)
Location: kernel/sched/cpudeadline.c:174
Inline: False
Direct callers:
  - kernel/sched/deadline.c:rq_offline_dl
  - kernel/sched/deadline.c:__dequeue_dl_entity
```
**Symbols:**

```
ffffffff8111d040-ffffffff8111d0ff: cpudl_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void cpudl_clear(struct cpudl *cp, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81134e80)
Location: kernel/sched/cpudeadline.c:173
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:rq_offline_dl
  - kernel/sched/build_policy.c:__dequeue_dl_entity
```
**Symbols:**

```
ffffffff81134e80-ffffffff81134f46: cpudl_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void cpudl_clear(struct cpudl *cp, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8115f3b0)
Location: kernel/sched/cpudeadline.c:173
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:rq_offline_dl
  - kernel/sched/build_policy.c:__dequeue_task_dl
```
**Symbols:**

```
ffffffff8115f3b0-ffffffff8115f476: cpudl_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void cpudl_clear(struct cpudl *cp, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8116faa0)
Location: kernel/sched/cpudeadline.c:173
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:rq_offline_dl
  - kernel/sched/build_policy.c:__dequeue_task_dl
```
**Symbols:**

```
ffffffff8116faa0-ffffffff8116fb66: cpudl_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void cpudl_clear(struct cpudl *cp, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8117cff0)
Location: kernel/sched/cpudeadline.c:173
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:rq_offline_dl
  - kernel/sched/build_policy.c:__dequeue_dl_entity
```
**Symbols:**

```
ffffffff8117cff0-ffffffff8117d0b6: cpudl_clear (STB_GLOBAL)
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
void cpudl_clear(struct cpudl *cp, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (ffff80001015a4a8)
Location: kernel/sched/cpudeadline.c:150
Inline: False
Direct callers:
  - kernel/sched/deadline.c:rq_offline_dl
  - kernel/sched/deadline.c:__dequeue_dl_entity
```
**Symbols:**

```
ffff80001015a4a8-ffff80001015a62c: cpudl_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cpudl_clear(struct cpudl *cp, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (c03a7290)
Location: kernel/sched/cpudeadline.c:150
Inline: False
Direct callers:
  - kernel/sched/deadline.c:rq_offline_dl
  - kernel/sched/deadline.c:__dequeue_dl_entity
```
**Symbols:**

```
c03a7290-c03a7390: cpudl_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cpudl_clear(struct cpudl *cp, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (c0000000001ae7a0)
Location: kernel/sched/cpudeadline.c:150
Inline: False
Direct callers:
  - kernel/sched/deadline.c:rq_offline_dl
  - kernel/sched/deadline.c:__dequeue_dl_entity
```
**Symbols:**

```
c0000000001ae7a0-c0000000001ae8e8: cpudl_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void cpudl_clear(struct cpudl *cp, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffe0000ffe44)
Location: kernel/sched/cpudeadline.c:150
Inline: False
Direct callers:
  - kernel/sched/deadline.c:rq_offline_dl
  - kernel/sched/deadline.c:__dequeue_dl_entity
```
**Symbols:**

```
ffffffe0000ffe44-ffffffe0000fff38: cpudl_clear (STB_GLOBAL)
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
void cpudl_clear(struct cpudl *cp, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff810ef9d0)
Location: kernel/sched/cpudeadline.c:150
Inline: False
Direct callers:
  - kernel/sched/deadline.c:rq_offline_dl
  - kernel/sched/deadline.c:__dequeue_dl_entity
```
**Symbols:**

```
ffffffff810ef9d0-ffffffff810efa8c: cpudl_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cpudl_clear(struct cpudl *cp, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff810dfa40)
Location: kernel/sched/cpudeadline.c:150
Inline: False
Direct callers:
  - kernel/sched/deadline.c:rq_offline_dl
  - kernel/sched/deadline.c:__dequeue_dl_entity
```
**Symbols:**

```
ffffffff810dfa40-ffffffff810dfafc: cpudl_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cpudl_clear(struct cpudl *cp, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff810ecb00)
Location: kernel/sched/cpudeadline.c:150
Inline: False
Direct callers:
  - kernel/sched/deadline.c:rq_offline_dl
  - kernel/sched/deadline.c:__dequeue_dl_entity
```
**Symbols:**

```
ffffffff810ecb00-ffffffff810ecbbc: cpudl_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cpudl_clear(struct cpudl *cp, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpudeadline.c (ffffffff810f7b40)
Location: kernel/sched/cpudeadline.c:150
Inline: False
Direct callers:
  - kernel/sched/deadline.c:rq_offline_dl
  - kernel/sched/deadline.c:__dequeue_dl_entity
```
**Symbols:**

```
ffffffff810f7b40-ffffffff810f7bfc: cpudl_clear (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
