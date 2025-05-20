# Function: <code>__update_blocked_fair</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e7aec)
Location: kernel/sched/fair.c:7563
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_blocked_averages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool __update_blocked_fair(struct rq *rq, bool *done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ed2c0)
Location: kernel/sched/fair.c:7868
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_blocked_averages
```
**Symbols:**

```
ffffffff810ed2c0-ffffffff810ed690: __update_blocked_fair (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool __update_blocked_fair(struct rq *rq, bool *done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810eb0a0)
Location: kernel/sched/fair.c:7944
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_blocked_averages
```
**Symbols:**

```
ffffffff810eb0a0-ffffffff810eb477: __update_blocked_fair (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool __update_blocked_fair(struct rq *rq, bool *done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ed920)
Location: kernel/sched/fair.c:8055
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_blocked_averages
```
**Symbols:**

```
ffffffff810ed920-ffffffff810edd1a: __update_blocked_fair (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool __update_blocked_fair(struct rq *rq, bool *done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:8193
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_blocked_averages
```
**Symbols:**

```
ffffffff81106620-ffffffff81106ae7: __update_blocked_fair (STB_LOCAL)
ffffffff81ca6366-ffffffff81ca63a4: __update_blocked_fair.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool __update_blocked_fair(struct rq *rq, bool *done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:8167
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_blocked_averages
```
**Symbols:**

```
ffffffff81120a10-ffffffff81120f5a: __update_blocked_fair (STB_LOCAL)
ffffffff81e55bf6-ffffffff81e55c34: __update_blocked_fair.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool __update_blocked_fair(struct rq *rq, bool *done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:8621
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_blocked_averages
```
**Symbols:**

```
ffffffff81149670-ffffffff81149bb5: __update_blocked_fair (STB_LOCAL)
ffffffff82056e86-ffffffff82056ec4: __update_blocked_fair.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool __update_blocked_fair(struct rq *rq, bool *done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:8979
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_blocked_averages
```
**Symbols:**

```
ffffffff81159520-ffffffff81159a65: __update_blocked_fair (STB_LOCAL)
ffffffff820d55d1-ffffffff820d560f: __update_blocked_fair.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool __update_blocked_fair(struct rq *rq, bool *done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:9302
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_blocked_averages
```
**Symbols:**

```
ffffffff81165b00-ffffffff8116609e: __update_blocked_fair (STB_LOCAL)
ffffffff821b0549-ffffffff821b0587: __update_blocked_fair.cold (STB_LOCAL)
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
In kernel/sched/fair.c (ffff8000101480d0)
Location: kernel/sched/fair.c:7563
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_blocked_averages
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
In kernel/sched/fair.c (c039406c)
Location: kernel/sched/fair.c:7563
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_blocked_averages
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
In kernel/sched/fair.c (c000000000198f80)
Location: kernel/sched/fair.c:7563
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_blocked_averages
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
In kernel/sched/fair.c (ffffffe0000f0c00)
Location: kernel/sched/fair.c:7563
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_blocked_averages
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
In kernel/sched/fair.c (ffffffff810e1c9c)
Location: kernel/sched/fair.c:7563
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_blocked_averages
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
In kernel/sched/fair.c (ffffffff810d0d7c)
Location: kernel/sched/fair.c:7563
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_blocked_averages
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
In kernel/sched/fair.c (ffffffff810de01c)
Location: kernel/sched/fair.c:7563
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_blocked_averages
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
In kernel/sched/fair.c (ffffffff810e9b0c)
Location: kernel/sched/fair.c:7563
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_blocked_averages
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
