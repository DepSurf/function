# Function: <code>mem_cgroup_print_oom_context</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void mem_cgroup_print_oom_context(struct mem_cgroup *memcg, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8129bc6d)
Location: mm/memcontrol.c:1304
Inline: False
Direct callers:
  - mm/oom_kill.c:dump_header
```
**Symbols:**

```
ffffffff8129bc6d-ffffffff8129bcde: mem_cgroup_print_oom_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void mem_cgroup_print_oom_context(struct mem_cgroup *memcg, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:1501
Inline: False
Direct callers:
  - mm/oom_kill.c:dump_header
```
**Symbols:**

```
ffffffff812b6e69-ffffffff812b6edc: mem_cgroup_print_oom_context.cold (STB_LOCAL)
ffffffff812b4c50-ffffffff812b4c6c: mem_cgroup_print_oom_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void mem_cgroup_print_oom_context(struct mem_cgroup *memcg, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:1512
Inline: False
Direct callers:
  - mm/oom_kill.c:dump_header
```
**Symbols:**

```
ffffffff812c8d3e-ffffffff812c8db1: mem_cgroup_print_oom_context.cold (STB_LOCAL)
ffffffff812c6720-ffffffff812c673c: mem_cgroup_print_oom_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void mem_cgroup_print_oom_context(struct mem_cgroup *memcg, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:1477
Inline: False
Direct callers:
  - mm/oom_kill.c:dump_header
```
**Symbols:**

```
ffffffff812fe395-ffffffff812fe40a: mem_cgroup_print_oom_context.cold (STB_LOCAL)
ffffffff812fc190-ffffffff812fc1ac: mem_cgroup_print_oom_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void mem_cgroup_print_oom_context(struct mem_cgroup *memcg, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:1658
Inline: False
Direct callers:
  - mm/oom_kill.c:dump_header
```
**Symbols:**

```
ffffffff81be9bd1-ffffffff81be9c4b: mem_cgroup_print_oom_context.cold (STB_LOCAL)
ffffffff81308350-ffffffff8130836c: mem_cgroup_print_oom_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void mem_cgroup_print_oom_context(struct mem_cgroup *memcg, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:1481
Inline: False
Direct callers:
  - mm/oom_kill.c:dump_header
```
**Symbols:**

```
ffffffff81bdbbee-ffffffff81bdbc68: mem_cgroup_print_oom_context.cold (STB_LOCAL)
ffffffff8130eae0-ffffffff8130eafc: mem_cgroup_print_oom_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void mem_cgroup_print_oom_context(struct mem_cgroup *memcg, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:1533
Inline: False
Direct callers:
  - mm/oom_kill.c:dump_header
```
**Symbols:**

```
ffffffff81cc2936-ffffffff81cc29b0: mem_cgroup_print_oom_context.cold (STB_LOCAL)
ffffffff81359960-ffffffff8135997c: mem_cgroup_print_oom_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void mem_cgroup_print_oom_context(struct mem_cgroup *memcg, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:1550
Inline: False
Direct callers:
  - mm/oom_kill.c:dump_header
```
**Symbols:**

```
ffffffff81e74eba-ffffffff81e74f23: mem_cgroup_print_oom_context.cold (STB_LOCAL)
ffffffff813d1990-ffffffff813d19b5: mem_cgroup_print_oom_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mem_cgroup_print_oom_context(struct mem_cgroup *memcg, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81456e50)
Location: mm/memcontrol.c:1610
Inline: False
Direct callers:
  - mm/oom_kill.c:dump_header
```
**Symbols:**

```
ffffffff81456e50-ffffffff81456ed5: mem_cgroup_print_oom_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mem_cgroup_print_oom_context(struct mem_cgroup *memcg, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8148c6b0)
Location: mm/memcontrol.c:1642
Inline: False
Direct callers:
  - mm/oom_kill.c:dump_header
```
**Symbols:**

```
ffffffff8148c6b0-ffffffff8148c735: mem_cgroup_print_oom_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mem_cgroup_print_oom_context(struct mem_cgroup *memcg, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814bc000)
Location: mm/memcontrol.c:1714
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff814bc000-ffffffff814bc085: mem_cgroup_print_oom_context (STB_GLOBAL)
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
void mem_cgroup_print_oom_context(struct mem_cgroup *memcg, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff8000103694d0)
Location: mm/memcontrol.c:1512
Inline: False
Direct callers:
  - mm/oom_kill.c:dump_header
```
**Symbols:**

```
ffff8000103694d0-ffff80001036954c: mem_cgroup_print_oom_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mem_cgroup_print_oom_context(struct mem_cgroup *memcg, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c055a9a4)
Location: mm/memcontrol.c:1512
Inline: False
Direct callers:
  - mm/oom_kill.c:dump_header
```
**Symbols:**

```
c055a9a4-c055aa34: mem_cgroup_print_oom_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mem_cgroup_print_oom_context(struct mem_cgroup *memcg, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c000000000457b80)
Location: mm/memcontrol.c:1512
Inline: False
Direct callers:
  - mm/oom_kill.c:dump_header
```
**Symbols:**

```
c000000000457b80-c000000000457c3c: mem_cgroup_print_oom_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void mem_cgroup_print_oom_context(struct mem_cgroup *memcg, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffe000246f90)
Location: mm/memcontrol.c:1512
Inline: False
Direct callers:
  - mm/oom_kill.c:dump_header
```
**Symbols:**

```
ffffffe000246f90-ffffffe000247018: mem_cgroup_print_oom_context (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void mem_cgroup_print_oom_context(struct mem_cgroup *memcg, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:1512
Inline: False
Direct callers:
  - mm/oom_kill.c:dump_header
```
**Symbols:**

```
ffffffff812c131e-ffffffff812c1391: mem_cgroup_print_oom_context.cold (STB_LOCAL)
ffffffff812bed00-ffffffff812bed1c: mem_cgroup_print_oom_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void mem_cgroup_print_oom_context(struct mem_cgroup *memcg, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:1512
Inline: False
Direct callers:
  - mm/oom_kill.c:dump_header
```
**Symbols:**

```
ffffffff812b236e-ffffffff812b23e1: mem_cgroup_print_oom_context.cold (STB_LOCAL)
ffffffff812afdf0-ffffffff812afe0c: mem_cgroup_print_oom_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void mem_cgroup_print_oom_context(struct mem_cgroup *memcg, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:1512
Inline: False
Direct callers:
  - mm/oom_kill.c:dump_header
```
**Symbols:**

```
ffffffff812bf12e-ffffffff812bf1a1: mem_cgroup_print_oom_context.cold (STB_LOCAL)
ffffffff812bcb10-ffffffff812bcb2c: mem_cgroup_print_oom_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void mem_cgroup_print_oom_context(struct mem_cgroup *memcg, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:1512
Inline: False
Direct callers:
  - mm/oom_kill.c:dump_header
```
**Symbols:**

```
ffffffff812cfb9e-ffffffff812cfbfd: mem_cgroup_print_oom_context.cold (STB_LOCAL)
ffffffff812cd2f0-ffffffff812cd315: mem_cgroup_print_oom_context (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
