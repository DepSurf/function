# Function: <code>oom_unkillable_task</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool oom_unkillable_task(struct task_struct *p, struct mem_cgroup *memcg, const nodemask_t *nodemask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81190700)
Location: mm/oom_kill.c:131
Inline: True
Direct callers:
  - mm/oom_kill.c:dump_header
```
**Symbols:**

```
ffffffff81190700-ffffffff811907c6: oom_unkillable_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool oom_unkillable_task(struct task_struct *p, struct mem_cgroup *memcg, const nodemask_t *nodemask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811a4880)
Location: mm/oom_kill.c:136
Inline: True
```
**Symbols:**

```
ffffffff811a4880-ffffffff811a4946: oom_unkillable_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool oom_unkillable_task(struct task_struct *p, struct mem_cgroup *memcg, const nodemask_t *nodemask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811b4e50)
Location: mm/oom_kill.c:141
Inline: True
```
**Symbols:**

```
ffffffff811b4e50-ffffffff811b4f16: oom_unkillable_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool oom_unkillable_task(struct task_struct *p, struct mem_cgroup *memcg, const nodemask_t *nodemask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811bc180)
Location: mm/oom_kill.c:144
Inline: True
Direct callers:
  - mm/oom_kill.c:dump_header
```
**Symbols:**

```
ffffffff811bc180-ffffffff811bc246: oom_unkillable_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool oom_unkillable_task(struct task_struct *p, struct mem_cgroup *memcg, const nodemask_t *nodemask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811d0db0)
Location: mm/oom_kill.c:146
Inline: True
Direct callers:
  - mm/oom_kill.c:dump_header
```
**Symbols:**

```
ffffffff811d0db0-ffffffff811d0e6d: oom_unkillable_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool oom_unkillable_task(struct task_struct *p, struct mem_cgroup *memcg, const nodemask_t *nodemask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811f2050)
Location: mm/oom_kill.c:146
Inline: True
Direct callers:
  - mm/oom_kill.c:dump_header
```
**Symbols:**

```
ffffffff811f2050-ffffffff811f210f: oom_unkillable_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool oom_unkillable_task(struct task_struct *p, struct mem_cgroup *memcg, const nodemask_t *nodemask);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81203ec0)
Location: mm/oom_kill.c:154
Inline: True
Direct callers:
  - mm/oom_kill.c:dump_header
```
**Symbols:**

```
ffffffff81203ec0-ffffffff81203f7f: oom_unkillable_task (STB_LOCAL)
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
In mm/oom_kill.c (ffffffff8121bcb5)
Location: mm/oom_kill.c:161
Inline: True
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
In mm/oom_kill.c (ffffffff81229645)
Location: mm/oom_kill.c:161
Inline: True
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
In mm/oom_kill.c (ffffffff812563c5)
Location: mm/oom_kill.c:162
Inline: True
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
In mm/oom_kill.c (ffffffff81261045)
Location: mm/oom_kill.c:164
Inline: True
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
In mm/oom_kill.c (ffffffff81265a95)
Location: mm/oom_kill.c:164
Inline: True
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
In mm/oom_kill.c (ffffffff812a3700)
Location: mm/oom_kill.c:165
Inline: True
Inline callers:
  - mm/oom_kill.c:out_of_memory
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
In mm/oom_kill.c (ffffffff812fb651)
Location: mm/oom_kill.c:162
Inline: True
Inline callers:
  - mm/oom_kill.c:out_of_memory
  - mm/oom_kill.c:oom_evaluate_task
  - mm/oom_kill.c:oom_badness
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
In mm/oom_kill.c (ffffffff813656fb)
Location: mm/oom_kill.c:162
Inline: True
Inline callers:
  - mm/oom_kill.c:out_of_memory
  - mm/oom_kill.c:oom_evaluate_task
  - mm/oom_kill.c:oom_badness
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
In mm/oom_kill.c (ffffffff81397b9e)
Location: mm/oom_kill.c:162
Inline: True
Inline callers:
  - mm/oom_kill.c:out_of_memory
  - mm/oom_kill.c:oom_evaluate_task
  - mm/oom_kill.c:oom_badness
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
In mm/oom_kill.c (ffffffff813c19cc)
Location: mm/oom_kill.c:162
Inline: True
Inline callers:
  - mm/oom_kill.c:out_of_memory
  - mm/oom_kill.c:oom_evaluate_task
  - mm/oom_kill.c:oom_badness
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
In mm/oom_kill.c (ffff8000102b73c0)
Location: mm/oom_kill.c:161
Inline: True
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
In mm/oom_kill.c (c04e56ac)
Location: mm/oom_kill.c:161
Inline: True
Inline callers:
  - mm/oom_kill.c:dump_header
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
In mm/oom_kill.c (c00000000036efd0)
Location: mm/oom_kill.c:161
Inline: True
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
In mm/oom_kill.c (ffffffe0001dcad4)
Location: mm/oom_kill.c:161
Inline: True
Inline callers:
  - mm/oom_kill.c:dump_header
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
In mm/oom_kill.c (ffffffff81221c95)
Location: mm/oom_kill.c:161
Inline: True
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
In mm/oom_kill.c (ffffffff81214e45)
Location: mm/oom_kill.c:161
Inline: True
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
In mm/oom_kill.c (ffffffff8121fa35)
Location: mm/oom_kill.c:161
Inline: True
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
In mm/oom_kill.c (ffffffff8122eae5)
Location: mm/oom_kill.c:161
Inline: True
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
</ul>
