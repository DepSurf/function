# Function: <code>nohz_balancer_kick</code>

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
In kernel/sched/fair.c (ffffffff810be6ec)
Location: kernel/sched/fair.c:7462
Inline: True
Inline callers:
  - kernel/sched/fair.c:trigger_load_balance
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
In kernel/sched/fair.c (ffffffff810c1ecd)
Location: kernel/sched/fair.c:7924
Inline: True
Inline callers:
  - kernel/sched/fair.c:trigger_load_balance
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
In kernel/sched/fair.c (ffffffff810c7ed9)
Location: kernel/sched/fair.c:8502
Inline: True
Inline callers:
  - kernel/sched/fair.c:trigger_load_balance
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
In kernel/sched/fair.c (ffffffff810c1b83)
Location: kernel/sched/fair.c:8518
Inline: True
Inline callers:
  - kernel/sched/fair.c:trigger_load_balance
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
In kernel/sched/fair.c (ffffffff810c92f3)
Location: kernel/sched/fair.c:8991
Inline: True
Inline callers:
  - kernel/sched/fair.c:trigger_load_balance
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
In kernel/sched/fair.c (ffffffff810d147b)
Location: kernel/sched/fair.c:9379
Inline: True
Inline callers:
  - kernel/sched/fair.c:trigger_load_balance
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
In kernel/sched/fair.c (ffffffff810dad9b)
Location: kernel/sched/fair.c:9482
Inline: True
Inline callers:
  - kernel/sched/fair.c:trigger_load_balance
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
In kernel/sched/fair.c (ffffffff810e216f)
Location: kernel/sched/fair.c:9392
Inline: True
Inline callers:
  - kernel/sched/fair.c:trigger_load_balance
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
In kernel/sched/fair.c (ffffffff810ec81f)
Location: kernel/sched/fair.c:9376
Inline: True
Inline callers:
  - kernel/sched/fair.c:trigger_load_balance
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void nohz_balancer_kick(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f6540)
Location: kernel/sched/fair.c:10062
Inline: False
Direct callers:
  - kernel/sched/fair.c:trigger_load_balance
```
**Symbols:**

```
ffffffff810f6540-ffffffff810f6720: nohz_balancer_kick (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void nohz_balancer_kick(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f46b0)
Location: kernel/sched/fair.c:10176
Inline: False
Direct callers:
  - kernel/sched/fair.c:trigger_load_balance
```
**Symbols:**

```
ffffffff810f46b0-ffffffff810f48a3: nohz_balancer_kick (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void nohz_balancer_kick(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f6670)
Location: kernel/sched/fair.c:10215
Inline: False
Direct callers:
  - kernel/sched/fair.c:trigger_load_balance
```
**Symbols:**

```
ffffffff810f6670-ffffffff810f691e: nohz_balancer_kick (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void nohz_balancer_kick(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff811104c0)
Location: kernel/sched/fair.c:10457
Inline: False
Direct callers:
  - kernel/sched/fair.c:trigger_load_balance
```
**Symbols:**

```
ffffffff811104c0-ffffffff81110836: nohz_balancer_kick (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void nohz_balancer_kick(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8112c600)
Location: kernel/sched/fair.c:10559
Inline: False
Direct callers:
  - kernel/sched/fair.c:trigger_load_balance
```
**Symbols:**

```
ffffffff8112c600-ffffffff8112c9c8: nohz_balancer_kick (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void nohz_balancer_kick(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff811562e0)
Location: kernel/sched/fair.c:11087
Inline: False
Direct callers:
  - kernel/sched/fair.c:trigger_load_balance
```
**Symbols:**

```
ffffffff811562e0-ffffffff811566aa: nohz_balancer_kick (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void nohz_balancer_kick(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81166450)
Location: kernel/sched/fair.c:11387
Inline: False
Direct callers:
  - kernel/sched/fair.c:trigger_load_balance
```
**Symbols:**

```
ffffffff81166450-ffffffff81166726: nohz_balancer_kick (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void nohz_balancer_kick(struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff811731b0)
Location: kernel/sched/fair.c:11852
Inline: False
Direct callers:
  - kernel/sched/fair.c:trigger_load_balance
```
**Symbols:**

```
ffffffff811731b0-ffffffff81173468: nohz_balancer_kick (STB_LOCAL)
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
In kernel/sched/fair.c (ffff80001014ccd8)
Location: kernel/sched/fair.c:9376
Inline: True
Inline callers:
  - kernel/sched/fair.c:trigger_load_balance
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
In kernel/sched/fair.c (c039aa08)
Location: kernel/sched/fair.c:9376
Inline: True
Inline callers:
  - kernel/sched/fair.c:trigger_load_balance
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
In kernel/sched/fair.c (c00000000019f96c)
Location: kernel/sched/fair.c:9376
Inline: True
Inline callers:
  - kernel/sched/fair.c:trigger_load_balance
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
In kernel/sched/fair.c (ffffffe0000f6168)
Location: kernel/sched/fair.c:9376
Inline: True
Inline callers:
  - kernel/sched/fair.c:trigger_load_balance
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
In kernel/sched/fair.c (ffffffff810e697f)
Location: kernel/sched/fair.c:9376
Inline: True
Inline callers:
  - kernel/sched/fair.c:trigger_load_balance
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
In kernel/sched/fair.c (ffffffff810d5b1f)
Location: kernel/sched/fair.c:9376
Inline: True
Inline callers:
  - kernel/sched/fair.c:trigger_load_balance
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
In kernel/sched/fair.c (ffffffff810e2d4f)
Location: kernel/sched/fair.c:9376
Inline: True
Inline callers:
  - kernel/sched/fair.c:trigger_load_balance
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
In kernel/sched/fair.c (ffffffff810ee91f)
Location: kernel/sched/fair.c:9376
Inline: True
Inline callers:
  - kernel/sched/fair.c:trigger_load_balance
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
