# Function: <code>unregister_fair_sched_group</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void unregister_fair_sched_group(struct task_group *tg, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810be930)
Location: kernel/sched/fair.c:8169
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_offline_group
```
**Symbols:**

```
ffffffff810be930-ffffffff810be9d1: unregister_fair_sched_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void unregister_fair_sched_group(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c21e0)
Location: kernel/sched/fair.c:8652
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_offline_group
```
**Symbols:**

```
ffffffff810c21e0-ffffffff810c22c9: unregister_fair_sched_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void unregister_fair_sched_group(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c8230)
Location: kernel/sched/fair.c:9273
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_offline_group
```
**Symbols:**

```
ffffffff810c8230-ffffffff810c831b: unregister_fair_sched_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void unregister_fair_sched_group(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c1f10)
Location: kernel/sched/fair.c:9298
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_offline_group
```
**Symbols:**

```
ffffffff810c1f10-ffffffff810c1ff8: unregister_fair_sched_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void unregister_fair_sched_group(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c9650)
Location: kernel/sched/fair.c:9767
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_offline_group
```
**Symbols:**

```
ffffffff810c9650-ffffffff810c9728: unregister_fair_sched_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void unregister_fair_sched_group(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d17c0)
Location: kernel/sched/fair.c:10274
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_offline_group
```
**Symbols:**

```
ffffffff810d17c0-ffffffff810d189d: unregister_fair_sched_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void unregister_fair_sched_group(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810db100)
Location: kernel/sched/fair.c:10378
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_offline_group
```
**Symbols:**

```
ffffffff810db100-ffffffff810db1dd: unregister_fair_sched_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void unregister_fair_sched_group(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e2540)
Location: kernel/sched/fair.c:10318
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_offline_group
```
**Symbols:**

```
ffffffff810e2540-ffffffff810e2647: unregister_fair_sched_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void unregister_fair_sched_group(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ecbf0)
Location: kernel/sched/fair.c:10313
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_offline_group
```
**Symbols:**

```
ffffffff810ecbf0-ffffffff810eccf7: unregister_fair_sched_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void unregister_fair_sched_group(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f6a90)
Location: kernel/sched/fair.c:10998
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_released
```
**Symbols:**

```
ffffffff810f6a90-ffffffff810f6b90: unregister_fair_sched_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void unregister_fair_sched_group(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f4c60)
Location: kernel/sched/fair.c:11112
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_released
```
**Symbols:**

```
ffffffff810f4c60-ffffffff810f4d67: unregister_fair_sched_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void unregister_fair_sched_group(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f6d50)
Location: kernel/sched/fair.c:11178
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_released
```
**Symbols:**

```
ffffffff810f6d50-ffffffff810f6e57: unregister_fair_sched_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void unregister_fair_sched_group(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81110fe0)
Location: kernel/sched/fair.c:11542
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_free
  - kernel/sched/core.c:sched_unregister_group_rcu
```
**Symbols:**

```
ffffffff81110fe0-ffffffff81111158: unregister_fair_sched_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void unregister_fair_sched_group(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8112d200)
Location: kernel/sched/fair.c:11660
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_free
  - kernel/sched/core.c:sched_unregister_group_rcu
```
**Symbols:**

```
ffffffff8112d200-ffffffff8112d379: unregister_fair_sched_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void unregister_fair_sched_group(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81156f90)
Location: kernel/sched/fair.c:12176
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_free
  - kernel/sched/core.c:sched_unregister_group_rcu
```
**Symbols:**

```
ffffffff81156f90-ffffffff81157118: unregister_fair_sched_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void unregister_fair_sched_group(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81167060)
Location: kernel/sched/fair.c:12494
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_free
  - kernel/sched/core.c:sched_unregister_group_rcu
```
**Symbols:**

```
ffffffff81167060-ffffffff811671d1: unregister_fair_sched_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void unregister_fair_sched_group(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81173de0)
Location: kernel/sched/fair.c:12917
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_free
  - kernel/sched/core.c:sched_unregister_group_rcu
```
**Symbols:**

```
ffffffff81173de0-ffffffff81173f51: unregister_fair_sched_group (STB_GLOBAL)
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
void unregister_fair_sched_group(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffff80001014d170)
Location: kernel/sched/fair.c:10313
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_offline_group
```
**Symbols:**

```
ffff80001014d170-ffff80001014d2fc: unregister_fair_sched_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void unregister_fair_sched_group(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c039ae24)
Location: kernel/sched/fair.c:10313
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_offline_group
```
**Symbols:**

```
c039ae24-c039af28: unregister_fair_sched_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void unregister_fair_sched_group(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c00000000019ffa0)
Location: kernel/sched/fair.c:10313
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_offline_group
```
**Symbols:**

```
c00000000019ffa0-c0000000001a013c: unregister_fair_sched_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void unregister_fair_sched_group(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffe0000f654a)
Location: kernel/sched/fair.c:10313
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_offline_group
```
**Symbols:**

```
ffffffe0000f654a-ffffffe0000f6656: unregister_fair_sched_group (STB_GLOBAL)
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
void unregister_fair_sched_group(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e6d50)
Location: kernel/sched/fair.c:10313
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_offline_group
```
**Symbols:**

```
ffffffff810e6d50-ffffffff810e6e57: unregister_fair_sched_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void unregister_fair_sched_group(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d5ef0)
Location: kernel/sched/fair.c:10313
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_offline_group
```
**Symbols:**

```
ffffffff810d5ef0-ffffffff810d5ff7: unregister_fair_sched_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void unregister_fair_sched_group(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e3120)
Location: kernel/sched/fair.c:10313
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_offline_group
```
**Symbols:**

```
ffffffff810e3120-ffffffff810e3227: unregister_fair_sched_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void unregister_fair_sched_group(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810eed00)
Location: kernel/sched/fair.c:10313
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_offline_group
```
**Symbols:**

```
ffffffff810eed00-ffffffff810eee07: unregister_fair_sched_group (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int cpu</code>
</li>
</ul>
</details>
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
