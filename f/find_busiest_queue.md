# Function: <code>find_busiest_queue</code>

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
In kernel/sched/fair.c (ffffffff810bd2dc)
Location: kernel/sched/fair.c:6815
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
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
In kernel/sched/fair.c (ffffffff810c0a5b)
Location: kernel/sched/fair.c:7281
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
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
In kernel/sched/fair.c (ffffffff810c6a44)
Location: kernel/sched/fair.c:7860
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
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
In kernel/sched/fair.c (ffffffff810c0667)
Location: kernel/sched/fair.c:7857
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
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
In kernel/sched/fair.c (ffffffff810c7e01)
Location: kernel/sched/fair.c:8310
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
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
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:8663
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
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
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:8730
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
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
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:8629
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
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
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:8612
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct rq *find_busiest_queue(struct lb_env *env, struct sched_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ea750)
Location: kernel/sched/fair.c:9266
Inline: False
Direct callers:
  - kernel/sched/fair.c:load_balance
```
**Symbols:**

```
ffffffff810ea750-ffffffff810ea965: find_busiest_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct rq *find_busiest_queue(struct lb_env *env, struct sched_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e8a80)
Location: kernel/sched/fair.c:9367
Inline: False
Direct callers:
  - kernel/sched/fair.c:load_balance
```
**Symbols:**

```
ffffffff810e8a80-ffffffff810e8ca7: find_busiest_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct rq *find_busiest_queue(struct lb_env *env, struct sched_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ea310)
Location: kernel/sched/fair.c:9421
Inline: False
Direct callers:
  - kernel/sched/fair.c:load_balance
```
**Symbols:**

```
ffffffff810ea310-ffffffff810ea531: find_busiest_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct rq *find_busiest_queue(struct lb_env *env, struct sched_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8110bfd0)
Location: kernel/sched/fair.c:9656
Inline: False
Direct callers:
  - kernel/sched/fair.c:load_balance
```
**Symbols:**

```
ffffffff8110bfd0-ffffffff8110c3da: find_busiest_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct rq *find_busiest_queue(struct lb_env *env, struct sched_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff811279a0)
Location: kernel/sched/fair.c:9739
Inline: False
Direct callers:
  - kernel/sched/fair.c:load_balance
```
**Symbols:**

```
ffffffff811279a0-ffffffff81127dc4: find_busiest_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct rq *find_busiest_queue(struct lb_env *env, struct sched_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81150da0)
Location: kernel/sched/fair.c:10260
Inline: False
Direct callers:
  - kernel/sched/fair.c:load_balance
```
**Symbols:**

```
ffffffff81150da0-ffffffff811511cf: find_busiest_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct rq *find_busiest_queue(struct lb_env *env, struct sched_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81161240)
Location: kernel/sched/fair.c:10546
Inline: False
Direct callers:
  - kernel/sched/fair.c:load_balance
```
**Symbols:**

```
ffffffff81161240-ffffffff811615ac: find_busiest_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct rq *find_busiest_queue(struct lb_env *env, struct sched_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8116b5b0)
Location: kernel/sched/fair.c:10979
Inline: False
Direct callers:
  - kernel/sched/fair.c:load_balance
```
**Symbols:**

```
ffffffff8116b5b0-ffffffff8116b90d: find_busiest_queue (STB_LOCAL)
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
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:8612
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
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
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:8612
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
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
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:8612
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
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
In kernel/sched/fair.c (ffffffe0000f48da)
Location: kernel/sched/fair.c:8612
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
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
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:8612
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
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
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:8612
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
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
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:8612
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
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
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:8612
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
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
