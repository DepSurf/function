# Function: <code>__sched_core_account_forceidle</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __sched_core_account_forceidle(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/core_sched.c:239
Inline: False
Direct callers:
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/build_utility.c:__sched_core_tick
```
**Symbols:**

```
ffffffff81e5954c-ffffffff81e59561: __sched_core_account_forceidle.cold (STB_LOCAL)
ffffffff8114baf0-ffffffff8114bcb9: __sched_core_account_forceidle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __sched_core_account_forceidle(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/core_sched.c:240
Inline: False
Direct callers:
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/build_utility.c:__sched_core_tick
```
**Symbols:**

```
ffffffff820581c7-ffffffff820581dc: __sched_core_account_forceidle.cold (STB_LOCAL)
ffffffff8117a5a0-ffffffff8117a778: __sched_core_account_forceidle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __sched_core_account_forceidle(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/core_sched.c:240
Inline: False
Direct callers:
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/build_utility.c:__sched_core_tick
```
**Symbols:**

```
ffffffff820d6abf-ffffffff820d6ad4: __sched_core_account_forceidle.cold (STB_LOCAL)
ffffffff8118b100-ffffffff8118b2da: __sched_core_account_forceidle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __sched_core_account_forceidle(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/core_sched.c:240
Inline: False
Direct callers:
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/build_utility.c:__sched_core_tick
```
**Symbols:**

```
ffffffff821b1d55-ffffffff821b1d6a: __sched_core_account_forceidle.cold (STB_LOCAL)
ffffffff81199a30-ffffffff81199c0a: __sched_core_account_forceidle (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
