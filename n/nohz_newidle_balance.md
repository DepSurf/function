# Function: <code>nohz_newidle_balance</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d0f71)
Location: kernel/sched/fair.c:9703
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
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
In kernel/sched/fair.c (ffffffff810da80d)
Location: kernel/sched/fair.c:9804
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
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
In kernel/sched/fair.c (ffffffff810e1aab)
Location: kernel/sched/fair.c:9744
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
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
In kernel/sched/fair.c (ffffffff810ec286)
Location: kernel/sched/fair.c:9728
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void nohz_newidle_balance(struct rq *this_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f5bd0)
Location: kernel/sched/fair.c:10408
Inline: False
Direct callers:
  - kernel/sched/fair.c:newidle_balance
```
**Symbols:**

```
ffffffff810f5bd0-ffffffff810f5c61: nohz_newidle_balance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void nohz_newidle_balance(struct rq *this_rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f3d20)
Location: kernel/sched/fair.c:10522
Inline: False
Direct callers:
  - kernel/sched/fair.c:newidle_balance
```
**Symbols:**

```
ffffffff810f3d20-ffffffff810f3db1: nohz_newidle_balance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f59c2)
Location: kernel/sched/fair.c:10584
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8110f4cc)
Location: kernel/sched/fair.c:10826
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8112b687)
Location: kernel/sched/fair.c:10942
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81155057)
Location: kernel/sched/fair.c:11469
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81165203)
Location: kernel/sched/fair.c:11773
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
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
In kernel/sched/fair.c (ffffffff81171f53)
Location: kernel/sched/fair.c:12248
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
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
In kernel/sched/fair.c (ffff80001014c744)
Location: kernel/sched/fair.c:9728
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
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
In kernel/sched/fair.c (c039a3e0)
Location: kernel/sched/fair.c:9728
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
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
In kernel/sched/fair.c (c00000000019f17c)
Location: kernel/sched/fair.c:9728
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
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
In kernel/sched/fair.c (ffffffe0000f5c60)
Location: kernel/sched/fair.c:9728
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
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
In kernel/sched/fair.c (ffffffff810e63e6)
Location: kernel/sched/fair.c:9728
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
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
In kernel/sched/fair.c (ffffffff810d5586)
Location: kernel/sched/fair.c:9728
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
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
In kernel/sched/fair.c (ffffffff810e27b6)
Location: kernel/sched/fair.c:9728
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
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
In kernel/sched/fair.c (ffffffff810ee1fe)
Location: kernel/sched/fair.c:9728
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
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
</ul>
