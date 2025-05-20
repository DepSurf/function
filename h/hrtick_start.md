# Function: <code>hrtick_start</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void hrtick_start(struct rq *rq, u64 delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810aa1f0)
Location: kernel/sched/core.c:361
Inline: False
Direct callers:
  - kernel/sched/deadline.c:pick_next_task_dl
```
**Symbols:**

```
ffffffff810aa1f0-ffffffff810aa281: hrtick_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void hrtick_start(struct rq *rq, u64 delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ace50)
Location: kernel/sched/core.c:295
Inline: False
Direct callers:
  - kernel/sched/deadline.c:pick_next_task_dl
```
**Symbols:**

```
ffffffff810ace50-ffffffff810aceeb: hrtick_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void hrtick_start(struct rq *rq, u64 delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b2ee0)
Location: kernel/sched/core.c:295
Inline: False
Direct callers:
  - kernel/sched/deadline.c:pick_next_task_dl
```
**Symbols:**

```
ffffffff810b2ee0-ffffffff810b2f7b: hrtick_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void hrtick_start(struct rq *rq, u64 delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810aee00)
Location: kernel/sched/core.c:293
Inline: False
Direct callers:
  - kernel/sched/fair.c:hrtick_start_fair
  - kernel/sched/deadline.c:pick_next_task_dl
```
**Symbols:**

```
ffffffff810aee00-ffffffff810aee9e: hrtick_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void hrtick_start(struct rq *rq, u64 delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b6040)
Location: kernel/sched/core.c:295
Inline: False
Direct callers:
  - kernel/sched/fair.c:hrtick_start_fair
  - kernel/sched/deadline.c:pick_next_task_dl
```
**Symbols:**

```
ffffffff810b6040-ffffffff810b60e4: hrtick_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void hrtick_start(struct rq *rq, u64 delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bdea0)
Location: kernel/sched/core.c:273
Inline: False
Direct callers:
  - kernel/sched/fair.c:hrtick_start_fair
  - kernel/sched/deadline.c:pick_next_task_dl
```
**Symbols:**

```
ffffffff810bdea0-ffffffff810bdf49: hrtick_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void hrtick_start(struct rq *rq, u64 delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c7150)
Location: kernel/sched/core.c:266
Inline: False
Direct callers:
  - kernel/sched/fair.c:hrtick_start_fair
  - kernel/sched/deadline.c:pick_next_task_dl
```
**Symbols:**

```
ffffffff810c7150-ffffffff810c71f9: hrtick_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void hrtick_start(struct rq *rq, u64 delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cd660)
Location: kernel/sched/core.c:280
Inline: False
Direct callers:
  - kernel/sched/fair.c:hrtick_start_fair
  - kernel/sched/deadline.c:pick_next_task_dl
```
**Symbols:**

```
ffffffff810cd660-ffffffff810cd709: hrtick_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void hrtick_start(struct rq *rq, u64 delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d7190)
Location: kernel/sched/core.c:280
Inline: False
Direct callers:
  - kernel/sched/fair.c:hrtick_start_fair
```
**Symbols:**

```
ffffffff810d7190-ffffffff810d7239: hrtick_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void hrtick_start(struct rq *rq, u64 delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e1bd0)
Location: kernel/sched/core.c:289
Inline: False
Direct callers:
  - kernel/sched/fair.c:hrtick_start_fair
```
**Symbols:**

```
ffffffff810e1bd0-ffffffff810e1c5c: hrtick_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void hrtick_start(struct rq *rq, u64 delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810defb0)
Location: kernel/sched/core.c:381
Inline: False
Direct callers:
  - kernel/sched/fair.c:hrtick_start_fair
```
**Symbols:**

```
ffffffff810defb0-ffffffff810df034: hrtick_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void hrtick_start(struct rq *rq, u64 delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e0c50)
Location: kernel/sched/core.c:391
Inline: False
Direct callers:
  - kernel/sched/fair.c:hrtick_start_fair
```
**Symbols:**

```
ffffffff810e0c50-ffffffff810e0cd6: hrtick_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void hrtick_start(struct rq *rq, u64 delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810f5b90)
Location: kernel/sched/core.c:744
Inline: False
Direct callers:
  - kernel/sched/fair.c:hrtick_start_fair
```
**Symbols:**

```
ffffffff810f5b90-ffffffff810f5c16: hrtick_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void hrtick_start(struct rq *rq, u64 delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81110c60)
Location: kernel/sched/core.c:814
Inline: False
Direct callers:
  - kernel/sched/fair.c:hrtick_start_fair
```
**Symbols:**

```
ffffffff81110c60-ffffffff81110d02: hrtick_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void hrtick_start(struct rq *rq, u64 delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81137be0)
Location: kernel/sched/core.c:808
Inline: False
Direct callers:
  - kernel/sched/fair.c:hrtick_start_fair
```
**Symbols:**

```
ffffffff81137be0-ffffffff81137c82: hrtick_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void hrtick_start(struct rq *rq, u64 delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81146d00)
Location: kernel/sched/core.c:830
Inline: False
Direct callers:
  - kernel/sched/fair.c:hrtick_start_fair
```
**Symbols:**

```
ffffffff81146d00-ffffffff81146da2: hrtick_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void hrtick_start(struct rq *rq, u64 delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81152530)
Location: kernel/sched/core.c:831
Inline: False
Direct callers:
  - kernel/sched/fair.c:hrtick_start_fair
  - kernel/sched/build_policy.c:pick_next_task_dl
```
**Symbols:**

```
ffffffff81152530-ffffffff811525d2: hrtick_start (STB_GLOBAL)
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
void hrtick_start(struct rq *rq, u64 delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff800010137c70)
Location: kernel/sched/core.c:280
Inline: False
Direct callers:
  - kernel/sched/fair.c:hrtick_start_fair
```
**Symbols:**

```
ffff800010137c70-ffff800010137d2c: hrtick_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void hrtick_start(struct rq *rq, u64 delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c03866f0)
Location: kernel/sched/core.c:280
Inline: False
Direct callers:
  - kernel/sched/fair.c:hrtick_start_fair
```
**Symbols:**

```
c03866f0-c038679c: hrtick_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void hrtick_start(struct rq *rq, u64 delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c000000000183130)
Location: kernel/sched/core.c:280
Inline: False
Direct callers:
  - kernel/sched/fair.c:hrtick_start_fair
```
**Symbols:**

```
c000000000183130-c00000000018322c: hrtick_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void hrtick_start(struct rq *rq, u64 delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000e7eb0)
Location: kernel/sched/core.c:280
Inline: False
Direct callers:
  - kernel/sched/fair.c:hrtick_start_fair
```
**Symbols:**

```
ffffffe0000e7eb0-ffffffe0000e7f6a: hrtick_start (STB_GLOBAL)
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
void hrtick_start(struct rq *rq, u64 delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d1660)
Location: kernel/sched/core.c:280
Inline: False
Direct callers:
  - kernel/sched/fair.c:hrtick_start_fair
```
**Symbols:**

```
ffffffff810d1660-ffffffff810d1709: hrtick_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void hrtick_start(struct rq *rq, u64 delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bfc20)
Location: kernel/sched/core.c:280
Inline: False
Direct callers:
  - kernel/sched/fair.c:hrtick_start_fair
```
**Symbols:**

```
ffffffff810bfc20-ffffffff810bfcc9: hrtick_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void hrtick_start(struct rq *rq, u64 delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cf820)
Location: kernel/sched/core.c:280
Inline: False
Direct callers:
  - kernel/sched/fair.c:hrtick_start_fair
```
**Symbols:**

```
ffffffff810cf820-ffffffff810cf8c9: hrtick_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void hrtick_start(struct rq *rq, u64 delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d8d40)
Location: kernel/sched/core.c:280
Inline: False
Direct callers:
  - kernel/sched/fair.c:hrtick_start_fair
```
**Symbols:**

```
ffffffff810d8d40-ffffffff810d8de9: hrtick_start (STB_GLOBAL)
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
