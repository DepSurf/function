# Function: <code>nohz_balance_exit_idle</code>

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
In kernel/sched/fair.c (ffffffff810b474c)
Location: kernel/sched/fair.c:7485
Inline: True
Inline callers:
  - kernel/sched/fair.c:trigger_load_balance
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void nohz_balance_exit_idle(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c1e84)
Location: kernel/sched/fair.c:7947
Inline: True
Inline callers:
  - kernel/sched/fair.c:trigger_load_balance
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/fair.c:trigger_load_balance
```
**Symbols:**

```
ffffffff810b70c0-ffffffff810b70fb: nohz_balance_exit_idle.part.80 (STB_LOCAL)
ffffffff810c1cd0-ffffffff810c1cfa: nohz_balance_exit_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
void nohz_balance_exit_idle(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c7e90)
Location: kernel/sched/fair.c:8525
Inline: True
Inline callers:
  - kernel/sched/fair.c:trigger_load_balance
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/fair.c:trigger_load_balance
```
**Symbols:**

```
ffffffff810bd9a0-ffffffff810bd9da: nohz_balance_exit_idle.part.88 (STB_LOCAL)
ffffffff810c7ce0-ffffffff810c7d0a: nohz_balance_exit_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void nohz_balance_exit_idle(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c1b2a)
Location: kernel/sched/fair.c:8541
Inline: True
Inline callers:
  - kernel/sched/fair.c:trigger_load_balance
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/fair.c:trigger_load_balance
```
**Symbols:**

```
ffffffff810b8950-ffffffff810b898a: nohz_balance_exit_idle.part.95 (STB_LOCAL)
ffffffff810c1980-ffffffff810c19ab: nohz_balance_exit_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void nohz_balance_exit_idle(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c929a)
Location: kernel/sched/fair.c:9014
Inline: True
Inline callers:
  - kernel/sched/fair.c:trigger_load_balance
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/fair.c:trigger_load_balance
```
**Symbols:**

```
ffffffff810bf7b0-ffffffff810bf7ea: nohz_balance_exit_idle.part.98 (STB_LOCAL)
ffffffff810c90e0-ffffffff810c910b: nohz_balance_exit_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void nohz_balance_exit_idle(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d1270)
Location: kernel/sched/fair.c:9475
Inline: True
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/fair.c:trigger_load_balance
```
**Symbols:**

```
ffffffff810d1270-ffffffff810d1314: nohz_balance_exit_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void nohz_balance_exit_idle(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810dab90)
Location: kernel/sched/fair.c:9578
Inline: True
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/fair.c:trigger_load_balance
```
**Symbols:**

```
ffffffff810dab90-ffffffff810dac34: nohz_balance_exit_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void nohz_balance_exit_idle(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e1f60)
Location: kernel/sched/fair.c:9519
Inline: True
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/fair.c:trigger_load_balance
```
**Symbols:**

```
ffffffff810e1f60-ffffffff810e2005: nohz_balance_exit_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void nohz_balance_exit_idle(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ebe60)
Location: kernel/sched/fair.c:9503
Inline: True
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/fair.c:trigger_load_balance
```
**Symbols:**

```
ffffffff810ebe60-ffffffff810ebf05: nohz_balance_exit_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void nohz_balance_exit_idle(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f6490)
Location: kernel/sched/fair.c:10189
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/fair.c:nohz_balancer_kick
```
**Symbols:**

```
ffffffff810f6490-ffffffff810f653b: nohz_balance_exit_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void nohz_balance_exit_idle(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f4600)
Location: kernel/sched/fair.c:10303
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/fair.c:nohz_balancer_kick
```
**Symbols:**

```
ffffffff810f4600-ffffffff810f46b0: nohz_balance_exit_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void nohz_balance_exit_idle(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f65c0)
Location: kernel/sched/fair.c:10342
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/fair.c:nohz_balancer_kick
```
**Symbols:**

```
ffffffff810f65c0-ffffffff810f6670: nohz_balance_exit_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void nohz_balance_exit_idle(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:10584
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/fair.c:nohz_balancer_kick
```
**Symbols:**

```
ffffffff81ca678c-ffffffff81ca67a1: nohz_balance_exit_idle.cold (STB_LOCAL)
ffffffff811103e0-ffffffff811104b9: nohz_balance_exit_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void nohz_balance_exit_idle(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:10689
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/fair.c:nohz_balancer_kick
```
**Symbols:**

```
ffffffff81e55fc0-ffffffff81e55fd5: nohz_balance_exit_idle.cold (STB_LOCAL)
ffffffff8112c500-ffffffff8112c5ff: nohz_balance_exit_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void nohz_balance_exit_idle(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:11217
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/fair.c:nohz_balancer_kick
```
**Symbols:**

```
ffffffff820571e4-ffffffff820571f9: nohz_balance_exit_idle.cold (STB_LOCAL)
ffffffff811561d0-ffffffff811562cf: nohz_balance_exit_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void nohz_balance_exit_idle(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff811663ac)
Location: kernel/sched/fair.c:11521
Inline: True
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/fair.c:nohz_balancer_kick
```
**Symbols:**

```
ffffffff820d5a0e-ffffffff820d5a23: nohz_balance_exit_idle.cold (STB_LOCAL)
ffffffff81166340-ffffffff8116643a: nohz_balance_exit_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void nohz_balance_exit_idle(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff8117310c)
Location: kernel/sched/fair.c:11985
Inline: True
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/fair.c:nohz_balancer_kick
```
**Symbols:**

```
ffffffff821b0a86-ffffffff821b0a9b: nohz_balance_exit_idle.cold (STB_LOCAL)
ffffffff811730a0-ffffffff8117319a: nohz_balance_exit_idle (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void nohz_balance_exit_idle(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffff80001014c1e8)
Location: kernel/sched/fair.c:9503
Inline: True
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/fair.c:trigger_load_balance
```
**Symbols:**

```
ffff80001014c1e8-ffff80001014c314: nohz_balance_exit_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void nohz_balance_exit_idle(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c0399e24)
Location: kernel/sched/fair.c:9503
Inline: True
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/fair.c:trigger_load_balance
```
**Symbols:**

```
c0399e24-c0399f2c: nohz_balance_exit_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void nohz_balance_exit_idle(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c00000000019eaf0)
Location: kernel/sched/fair.c:9503
Inline: True
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/fair.c:trigger_load_balance
```
**Symbols:**

```
c00000000019eaf0-c00000000019ec4c: nohz_balance_exit_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void nohz_balance_exit_idle(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffe0000f57d6)
Location: kernel/sched/fair.c:9503
Inline: True
Direct callers:
  - kernel/sched/fair.c:trigger_load_balance
```
**Symbols:**

```
ffffffe0000f57d6-ffffffe0000f58c4: nohz_balance_exit_idle (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void nohz_balance_exit_idle(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e5fc0)
Location: kernel/sched/fair.c:9503
Inline: True
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/fair.c:trigger_load_balance
```
**Symbols:**

```
ffffffff810e5fc0-ffffffff810e6065: nohz_balance_exit_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void nohz_balance_exit_idle(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d5160)
Location: kernel/sched/fair.c:9503
Inline: True
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/fair.c:trigger_load_balance
```
**Symbols:**

```
ffffffff810d5160-ffffffff810d5205: nohz_balance_exit_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void nohz_balance_exit_idle(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e2390)
Location: kernel/sched/fair.c:9503
Inline: True
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/fair.c:trigger_load_balance
```
**Symbols:**

```
ffffffff810e2390-ffffffff810e2435: nohz_balance_exit_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void nohz_balance_exit_idle(struct rq *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810edf30)
Location: kernel/sched/fair.c:9503
Inline: True
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/fair.c:trigger_load_balance
```
**Symbols:**

```
ffffffff810edf30-ffffffff810edfdf: nohz_balance_exit_idle (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct rq *rq</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int cpu</code>
</li>
</ul>
</details>
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
