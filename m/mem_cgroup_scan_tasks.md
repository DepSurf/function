# Function: <code>mem_cgroup_scan_tasks</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mem_cgroup_scan_tasks(struct mem_cgroup *memcg, int (*fn)(struct task_struct *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81234e70)
Location: mm/memcontrol.c:938
Inline: False
```
**Symbols:**

```
ffffffff81234e70-ffffffff81234f57: mem_cgroup_scan_tasks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mem_cgroup_scan_tasks(struct mem_cgroup *memcg, int (*fn)(struct task_struct *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812408f0)
Location: mm/memcontrol.c:908
Inline: False
```
**Symbols:**

```
ffffffff812408f0-ffffffff812409d7: mem_cgroup_scan_tasks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mem_cgroup_scan_tasks(struct mem_cgroup *memcg, int (*fn)(struct task_struct *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81260610)
Location: mm/memcontrol.c:922
Inline: False
```
**Symbols:**

```
ffffffff81260610-ffffffff8126071c: mem_cgroup_scan_tasks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int mem_cgroup_scan_tasks(struct mem_cgroup *memcg, int (*fn)(struct task_struct *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812847e0)
Location: mm/memcontrol.c:893
Inline: False
```
**Symbols:**

```
ffffffff812847e0-ffffffff812848ea: mem_cgroup_scan_tasks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int mem_cgroup_scan_tasks(struct mem_cgroup *memcg, int (*fn)(struct task_struct *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812996f0)
Location: mm/memcontrol.c:1067
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
```
**Symbols:**

```
ffffffff812996f0-ffffffff812997fa: mem_cgroup_scan_tasks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int mem_cgroup_scan_tasks(struct mem_cgroup *memcg, int (*fn)(struct task_struct *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b4a40)
Location: mm/memcontrol.c:1203
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:dump_header
```
**Symbols:**

```
ffffffff812b4a40-ffffffff812b4b53: mem_cgroup_scan_tasks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int mem_cgroup_scan_tasks(struct mem_cgroup *memcg, int (*fn)(struct task_struct *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c6510)
Location: mm/memcontrol.c:1214
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:dump_header
```
**Symbols:**

```
ffffffff812c6510-ffffffff812c6623: mem_cgroup_scan_tasks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int mem_cgroup_scan_tasks(struct mem_cgroup *memcg, int (*fn)(struct task_struct *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812fbfa0)
Location: mm/memcontrol.c:1175
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:dump_header
```
**Symbols:**

```
ffffffff812fbfa0-ffffffff812fc094: mem_cgroup_scan_tasks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mem_cgroup_scan_tasks(struct mem_cgroup *memcg, int (*fn)(struct task_struct *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81307fd0)
Location: mm/memcontrol.c:1300
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:dump_header
```
**Symbols:**

```
ffffffff81307fd0-ffffffff8130811e: mem_cgroup_scan_tasks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mem_cgroup_scan_tasks(struct mem_cgroup *memcg, int (*fn)(struct task_struct *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8130e740)
Location: mm/memcontrol.c:1127
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:dump_header
```
**Symbols:**

```
ffffffff8130e740-ffffffff8130e88e: mem_cgroup_scan_tasks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int mem_cgroup_scan_tasks(struct mem_cgroup *memcg, int (*fn)(struct task_struct *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81359560)
Location: mm/memcontrol.c:1182
Inline: False
Direct callers:
  - mm/oom_kill.c:out_of_memory
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:dump_header
```
**Symbols:**

```
ffffffff81359560-ffffffff813596ae: mem_cgroup_scan_tasks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mem_cgroup_scan_tasks(struct mem_cgroup *memcg, int (*fn)(struct task_struct *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813d1510)
Location: mm/memcontrol.c:1162
Inline: False
Direct callers:
  - mm/oom_kill.c:out_of_memory
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:dump_header
```
**Symbols:**

```
ffffffff813d1510-ffffffff813d167c: mem_cgroup_scan_tasks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mem_cgroup_scan_tasks(struct mem_cgroup *memcg, int (*fn)(struct task_struct *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81456970)
Location: mm/memcontrol.c:1242
Inline: False
Direct callers:
  - mm/oom_kill.c:out_of_memory
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:dump_header
```
**Symbols:**

```
ffffffff81456970-ffffffff81456adc: mem_cgroup_scan_tasks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mem_cgroup_scan_tasks(struct mem_cgroup *memcg, int (*fn)(struct task_struct *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8148c200)
Location: mm/memcontrol.c:1267
Inline: False
Direct callers:
  - mm/oom_kill.c:out_of_memory
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:dump_header
```
**Symbols:**

```
ffffffff8148c200-ffffffff8148c334: mem_cgroup_scan_tasks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mem_cgroup_scan_tasks(struct mem_cgroup *memcg, int (*fn)(struct task_struct *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814bbb50)
Location: mm/memcontrol.c:1318
Inline: False
Direct callers:
  - mm/oom_kill.c:out_of_memory
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:dump_header
```
**Symbols:**

```
ffffffff814bbb50-ffffffff814bbc84: mem_cgroup_scan_tasks (STB_GLOBAL)
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
int mem_cgroup_scan_tasks(struct mem_cgroup *memcg, int (*fn)(struct task_struct *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff800010369270)
Location: mm/memcontrol.c:1214
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:dump_header
```
**Symbols:**

```
ffff800010369270-ffff800010369388: mem_cgroup_scan_tasks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mem_cgroup_scan_tasks(struct mem_cgroup *memcg, int (*fn)(struct task_struct *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c055a760)
Location: mm/memcontrol.c:1214
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:dump_header
```
**Symbols:**

```
c055a760-c055a86c: mem_cgroup_scan_tasks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mem_cgroup_scan_tasks(struct mem_cgroup *memcg, int (*fn)(struct task_struct *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c000000000457870)
Location: mm/memcontrol.c:1214
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:dump_header
```
**Symbols:**

```
c000000000457870-c0000000004579e8: mem_cgroup_scan_tasks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int mem_cgroup_scan_tasks(struct mem_cgroup *memcg, int (*fn)(struct task_struct *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffe000246da8)
Location: mm/memcontrol.c:1214
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:dump_header
```
**Symbols:**

```
ffffffe000246da8-ffffffe000246e72: mem_cgroup_scan_tasks (STB_GLOBAL)
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
int mem_cgroup_scan_tasks(struct mem_cgroup *memcg, int (*fn)(struct task_struct *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812beaf0)
Location: mm/memcontrol.c:1214
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:dump_header
```
**Symbols:**

```
ffffffff812beaf0-ffffffff812bec03: mem_cgroup_scan_tasks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int mem_cgroup_scan_tasks(struct mem_cgroup *memcg, int (*fn)(struct task_struct *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812afbe0)
Location: mm/memcontrol.c:1214
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:dump_header
```
**Symbols:**

```
ffffffff812afbe0-ffffffff812afcf3: mem_cgroup_scan_tasks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int mem_cgroup_scan_tasks(struct mem_cgroup *memcg, int (*fn)(struct task_struct *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bc900)
Location: mm/memcontrol.c:1214
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:dump_header
```
**Symbols:**

```
ffffffff812bc900-ffffffff812bca13: mem_cgroup_scan_tasks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int mem_cgroup_scan_tasks(struct mem_cgroup *memcg, int (*fn)(struct task_struct *, void *), void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812cd0e0)
Location: mm/memcontrol.c:1214
Inline: False
Direct callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:dump_header
```
**Symbols:**

```
ffffffff812cd0e0-ffffffff812cd1f3: mem_cgroup_scan_tasks (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
