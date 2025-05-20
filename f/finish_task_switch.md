# Function: <code>finish_task_switch</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct rq *finish_task_switch(struct task_struct *prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810a9410)
Location: kernel/sched/core.c:2538
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:schedule_tail
```
**Symbols:**

```
ffffffff810a9410-ffffffff810a962c: finish_task_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct rq *finish_task_switch(struct task_struct *prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810aaa50)
Location: kernel/sched/core.c:2721
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:schedule_tail
```
**Symbols:**

```
ffffffff810aaa50-ffffffff810aac39: finish_task_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct rq *finish_task_switch(struct task_struct *prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b0b40)
Location: kernel/sched/core.c:2731
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:schedule_tail
```
**Symbols:**

```
ffffffff810b0b40-ffffffff810b0d42: finish_task_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct rq *finish_task_switch(struct task_struct *prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ad030)
Location: kernel/sched/core.c:2599
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:schedule_tail
```
**Symbols:**

```
ffffffff810ad030-ffffffff810ad22b: finish_task_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct rq *finish_task_switch(struct task_struct *prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b4180)
Location: kernel/sched/core.c:2618
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:schedule_tail
```
**Symbols:**

```
ffffffff810b4180-ffffffff810b4384: finish_task_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct rq *finish_task_switch(struct task_struct *prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bb460)
Location: kernel/sched/core.c:2665
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:schedule_tail
```
**Symbols:**

```
ffffffff810bb460-ffffffff810bb6b0: finish_task_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct rq *finish_task_switch(struct task_struct *prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c4a00)
Location: kernel/sched/core.c:2654
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:schedule_tail
```
**Symbols:**

```
ffffffff810c4a00-ffffffff810c4c63: finish_task_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct rq *finish_task_switch(struct task_struct *prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ca600)
Location: kernel/sched/core.c:3064
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:schedule_tail
```
**Symbols:**

```
ffffffff810ca600-ffffffff810ca850: finish_task_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct rq *finish_task_switch(struct task_struct *prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d3c70)
Location: kernel/sched/core.c:3184
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:schedule_tail
```
**Symbols:**

```
ffffffff810d3c70-ffffffff810d3eb5: finish_task_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct rq *finish_task_switch(struct task_struct *prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810defa0)
Location: kernel/sched/core.c:3345
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:schedule_tail
```
**Symbols:**

```
ffffffff810defa0-ffffffff810df1f9: finish_task_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810dbc40)
Location: kernel/sched/core.c:4151
Inline: True
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:schedule_tail
```
**Symbols:**

```
ffffffff810dbc40-ffffffff810dbe9b: finish_task_switch.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810ddc60)
Location: kernel/sched/core.c:4172
Inline: True
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:schedule_tail
```
**Symbols:**

```
ffffffff810ddc60-ffffffff810ddebb: finish_task_switch.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:4784
Inline: True
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:schedule_tail
```
**Symbols:**

```
ffffffff810f28e0-ffffffff810f2b50: finish_task_switch.isra.0 (STB_LOCAL)
ffffffff81ca5c7a-ffffffff81ca5c8e: finish_task_switch.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:4993
Inline: True
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:schedule_tail
```
**Symbols:**

```
ffffffff8110ef40-ffffffff8110f1cc: finish_task_switch.isra.0 (STB_LOCAL)
ffffffff81e555c5-ffffffff81e555e1: finish_task_switch.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:5132
Inline: True
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:schedule_tail
```
**Symbols:**

```
ffffffff81135d50-ffffffff81135fe6: finish_task_switch.isra.0 (STB_LOCAL)
ffffffff82056a0e-ffffffff82056a2a: finish_task_switch.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:5210
Inline: True
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:schedule_tail
```
**Symbols:**

```
ffffffff811434c0-ffffffff8114376e: finish_task_switch.isra.0 (STB_LOCAL)
ffffffff820d504d-ffffffff820d5061: finish_task_switch.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:5231
Inline: True
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:schedule_tail
```
**Symbols:**

```
ffffffff8114e990-ffffffff8114ec8c: finish_task_switch.isra.0 (STB_LOCAL)
ffffffff821aff5c-ffffffff821aff84: finish_task_switch.isra.0.cold (STB_LOCAL)
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
struct rq *finish_task_switch(struct task_struct *prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff800010133688)
Location: kernel/sched/core.c:3184
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:schedule_tail
```
**Symbols:**

```
ffff800010133688-ffff8000101338b4: finish_task_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct rq *finish_task_switch(struct task_struct *prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c0382348)
Location: kernel/sched/core.c:3184
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:schedule_tail
```
**Symbols:**

```
c0382348-c0382590: finish_task_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct rq *finish_task_switch(struct task_struct *prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c00000000017ef90)
Location: kernel/sched/core.c:3184
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:schedule_tail
```
**Symbols:**

```
c00000000017ef90-c00000000017f2f4: finish_task_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct rq *finish_task_switch(struct task_struct *prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000e6fd0)
Location: kernel/sched/core.c:3184
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:schedule_tail
```
**Symbols:**

```
ffffffe0000e6fd0-ffffffe0000e719c: finish_task_switch (STB_LOCAL)
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
struct rq *finish_task_switch(struct task_struct *prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cdf60)
Location: kernel/sched/core.c:3184
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:schedule_tail
```
**Symbols:**

```
ffffffff810cdf60-ffffffff810ce1a5: finish_task_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct rq *finish_task_switch(struct task_struct *prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bc7f0)
Location: kernel/sched/core.c:3184
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:schedule_tail
```
**Symbols:**

```
ffffffff810bc7f0-ffffffff810bca74: finish_task_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct rq *finish_task_switch(struct task_struct *prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cd390)
Location: kernel/sched/core.c:3184
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:schedule_tail
```
**Symbols:**

```
ffffffff810cd390-ffffffff810cd5d5: finish_task_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct rq *finish_task_switch(struct task_struct *prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d46e0)
Location: kernel/sched/core.c:3184
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:schedule_tail
```
**Symbols:**

```
ffffffff810d46e0-ffffffff810d4922: finish_task_switch (STB_LOCAL)
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
