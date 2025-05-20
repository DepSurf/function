# Function: <code>rto_next_cpu</code>

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
In kernel/sched/rt.c (ffffffff810bf221)
Location: kernel/sched/rt.c:1814
Inline: True
Inline callers:
  - kernel/sched/rt.c:find_next_push_cpu
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
In kernel/sched/rt.c (ffffffff810c2b20)
Location: kernel/sched/rt.c:1877
Inline: True
Inline callers:
  - kernel/sched/rt.c:find_next_push_cpu
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
In kernel/sched/rt.c (ffffffff810c8b87)
Location: kernel/sched/rt.c:1876
Inline: True
Inline callers:
  - kernel/sched/rt.c:find_next_push_cpu
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
In kernel/sched/rt.c (ffffffff810c2cc6)
Location: kernel/sched/rt.c:1887
Inline: True
Inline callers:
  - kernel/sched/rt.c:find_next_push_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int rto_next_cpu(struct root_domain *rd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810ca2e0)
Location: kernel/sched/rt.c:1910
Inline: False
Direct callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_push_irq_work_func
```
**Symbols:**

```
ffffffff810ca2e0-ffffffff810ca338: rto_next_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int rto_next_cpu(struct root_domain *rd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810d22c0)
Location: kernel/sched/rt.c:1921
Inline: False
Direct callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_push_irq_work_func
```
**Symbols:**

```
ffffffff810d22c0-ffffffff810d2318: rto_next_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int rto_next_cpu(struct root_domain *rd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810dbc30)
Location: kernel/sched/rt.c:1932
Inline: False
Direct callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_push_irq_work_func
```
**Symbols:**

```
ffffffff810dbc30-ffffffff810dbc88: rto_next_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int rto_next_cpu(struct root_domain *rd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810e2bf0)
Location: kernel/sched/rt.c:1932
Inline: False
Direct callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_push_irq_work_func
```
**Symbols:**

```
ffffffff810e2bf0-ffffffff810e2c48: rto_next_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int rto_next_cpu(struct root_domain *rd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810ed370)
Location: kernel/sched/rt.c:1922
Inline: False
Direct callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_push_irq_work_func
```
**Symbols:**

```
ffffffff810ed370-ffffffff810ed3c8: rto_next_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f994d)
Location: kernel/sched/rt.c:1992
Inline: True
Inline callers:
  - kernel/sched/rt.c:rto_push_irq_work_func
  - kernel/sched/rt.c:tell_cpu_to_push
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f7d0c)
Location: kernel/sched/rt.c:2020
Inline: True
Inline callers:
  - kernel/sched/rt.c:rto_push_irq_work_func
  - kernel/sched/rt.c:tell_cpu_to_push
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
In kernel/sched/rt.c (ffffffff810f9e7c)
Location: kernel/sched/rt.c:2020
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_push_irq_work_func
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
In kernel/sched/rt.c (ffffffff81114c3c)
Location: kernel/sched/rt.c:2045
Inline: True
Inline callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_push_irq_work_func
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
In kernel/sched/build_policy.c (ffffffff81133b38)
Location: kernel/sched/rt.c:2222
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:rto_push_irq_work_func
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
In kernel/sched/build_policy.c (ffffffff8115dffa)
Location: kernel/sched/rt.c:2221
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:rto_push_irq_work_func
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
In kernel/sched/build_policy.c (ffffffff8116e6da)
Location: kernel/sched/rt.c:2225
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:rto_push_irq_work_func
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
In kernel/sched/build_policy.c (ffffffff8117bcaa)
Location: kernel/sched/rt.c:2172
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pull_rt_task
  - kernel/sched/build_policy.c:rto_push_irq_work_func
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
int rto_next_cpu(struct root_domain *rd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffff80001014df40)
Location: kernel/sched/rt.c:1922
Inline: False
Direct callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_push_irq_work_func
  - kernel/sched/rt.c:rto_push_irq_work_func
```
**Symbols:**

```
ffff80001014df40-ffff80001014dfcc: rto_next_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rto_next_cpu(struct root_domain *rd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (c039b330)
Location: kernel/sched/rt.c:1922
Inline: False
Direct callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_push_irq_work_func
```
**Symbols:**

```
c039b330-c039b39c: rto_next_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int rto_next_cpu(struct root_domain *rd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (c0000000001a0a80)
Location: kernel/sched/rt.c:1922
Inline: False
Direct callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_push_irq_work_func
```
**Symbols:**

```
c0000000001a0a80-c0000000001a0b64: rto_next_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int rto_next_cpu(struct root_domain *rd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffe0000f6bdc)
Location: kernel/sched/rt.c:1922
Inline: False
Direct callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_push_irq_work_func
```
**Symbols:**

```
ffffffe0000f6bdc-ffffffe0000f6c56: rto_next_cpu (STB_LOCAL)
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
int rto_next_cpu(struct root_domain *rd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810e7420)
Location: kernel/sched/rt.c:1922
Inline: False
Direct callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_push_irq_work_func
```
**Symbols:**

```
ffffffff810e7420-ffffffff810e7478: rto_next_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int rto_next_cpu(struct root_domain *rd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810d6670)
Location: kernel/sched/rt.c:1922
Inline: False
Direct callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_push_irq_work_func
```
**Symbols:**

```
ffffffff810d6670-ffffffff810d66c8: rto_next_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int rto_next_cpu(struct root_domain *rd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810e38a0)
Location: kernel/sched/rt.c:1922
Inline: False
Direct callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_push_irq_work_func
```
**Symbols:**

```
ffffffff810e38a0-ffffffff810e38f8: rto_next_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int rto_next_cpu(struct root_domain *rd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810ef3e0)
Location: kernel/sched/rt.c:1922
Inline: False
Direct callers:
  - kernel/sched/rt.c:pull_rt_task
  - kernel/sched/rt.c:rto_push_irq_work_func
```
**Symbols:**

```
ffffffff810ef3e0-ffffffff810ef438: rto_next_cpu (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
