# Function: <code>mem_cgroup_print_oom_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void mem_cgroup_print_oom_info(struct mem_cgroup *memcg, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff811ff040)
Location: mm/memcontrol.c:1250
Inline: False
Direct callers:
  - mm/oom_kill.c:dump_header
```
**Symbols:**

```
ffffffff811ff040-ffffffff811ff25f: mem_cgroup_print_oom_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void mem_cgroup_print_oom_info(struct mem_cgroup *memcg, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81222e00)
Location: mm/memcontrol.c:1114
Inline: False
```
**Symbols:**

```
ffffffff81222e00-ffffffff81223026: mem_cgroup_print_oom_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void mem_cgroup_print_oom_info(struct mem_cgroup *memcg, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812351f0)
Location: mm/memcontrol.c:1152
Inline: False
```
**Symbols:**

```
ffffffff812351f0-ffffffff81235416: mem_cgroup_print_oom_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void mem_cgroup_print_oom_info(struct mem_cgroup *memcg, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81240c20)
Location: mm/memcontrol.c:1144
Inline: False
Direct callers:
  - mm/oom_kill.c:dump_header
```
**Symbols:**

```
ffffffff81240c20-ffffffff81240e3d: mem_cgroup_print_oom_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void mem_cgroup_print_oom_info(struct mem_cgroup *memcg, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81260960)
Location: mm/memcontrol.c:1158
Inline: False
Direct callers:
  - mm/oom_kill.c:dump_header
```
**Symbols:**

```
ffffffff81260960-ffffffff81260b7d: mem_cgroup_print_oom_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void mem_cgroup_print_oom_info(struct mem_cgroup *memcg, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81286d62)
Location: mm/memcontrol.c:1129
Inline: False
Direct callers:
  - mm/oom_kill.c:dump_header
```
**Symbols:**

```
ffffffff81286d62-ffffffff81286f5c: mem_cgroup_print_oom_info (STB_GLOBAL)
```
</details>
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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>
