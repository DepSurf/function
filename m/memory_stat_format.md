# Function: <code>memory_stat_format</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
char *memory_stat_format(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812ae3a0)
Location: mm/memcontrol.c:1382
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
```
**Symbols:**

```
ffffffff812ae3a0-ffffffff812ae795: memory_stat_format (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
char *memory_stat_format(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bfdb0)
Location: mm/memcontrol.c:1393
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
```
**Symbols:**

```
ffffffff812bfdb0-ffffffff812c01a5: memory_stat_format (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
char *memory_stat_format(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812f4f70)
Location: mm/memcontrol.c:1353
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
```
**Symbols:**

```
ffffffff812f4f70-ffffffff812f53bd: memory_stat_format (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
char *memory_stat_format(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813007a0)
Location: mm/memcontrol.c:1578
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
```
**Symbols:**

```
ffffffff813007a0-ffffffff81300a1d: memory_stat_format (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
char *memory_stat_format(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813075d0)
Location: mm/memcontrol.c:1401
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
```
**Symbols:**

```
ffffffff813075d0-ffffffff813078b6: memory_stat_format (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
char *memory_stat_format(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81353b00)
Location: mm/memcontrol.c:1453
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
```
**Symbols:**

```
ffffffff81353b00-ffffffff81353f08: memory_stat_format (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
char *memory_stat_format(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813cbb60)
Location: mm/memcontrol.c:1463
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
```
**Symbols:**

```
ffffffff813cbb60-ffffffff813cbf17: memory_stat_format (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff81450870)
Location: mm/memcontrol.c:1544
Inline: True
Direct callers:
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
```
**Symbols:**

```
ffffffff81450870-ffffffff81450d1f: memory_stat_format.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff81488900)
Location: mm/memcontrol.c:1623
Inline: True
Direct callers:
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
```
**Symbols:**

```
ffffffff81488900-ffffffff8148894f: memory_stat_format.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff814b68d0)
Location: mm/memcontrol.c:1696
Inline: True
Direct callers:
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
```
**Symbols:**

```
ffffffff814b68d0-ffffffff814b691f: memory_stat_format.constprop.0 (STB_LOCAL)
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
char *memory_stat_format(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff8000103617a0)
Location: mm/memcontrol.c:1393
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
```
**Symbols:**

```
ffff8000103617a0-ffff800010361b5c: memory_stat_format (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
char *memory_stat_format(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c05540d4)
Location: mm/memcontrol.c:1393
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
```
**Symbols:**

```
c05540d4-c05544f4: memory_stat_format (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
char *memory_stat_format(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c00000000044d8f0)
Location: mm/memcontrol.c:1393
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
```
**Symbols:**

```
c00000000044d8f0-c00000000044dde0: memory_stat_format (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
char *memory_stat_format(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffe0002410e4)
Location: mm/memcontrol.c:1393
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
```
**Symbols:**

```
ffffffe0002410e4-ffffffe000241486: memory_stat_format (STB_LOCAL)
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
char *memory_stat_format(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b8390)
Location: mm/memcontrol.c:1393
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
```
**Symbols:**

```
ffffffff812b8390-ffffffff812b8785: memory_stat_format (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
char *memory_stat_format(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812a9560)
Location: mm/memcontrol.c:1393
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
```
**Symbols:**

```
ffffffff812a9560-ffffffff812a9955: memory_stat_format (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
char *memory_stat_format(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b61a0)
Location: mm/memcontrol.c:1393
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
```
**Symbols:**

```
ffffffff812b61a0-ffffffff812b6595: memory_stat_format (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
char *memory_stat_format(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c6970)
Location: mm/memcontrol.c:1393
Inline: False
Direct callers:
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
```
**Symbols:**

```
ffffffff812c6970-ffffffff812c6d65: memory_stat_format (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
