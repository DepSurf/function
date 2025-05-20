# Function: <code>mem_cgroup_get_max</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int mem_cgroup_get_max(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81284b70)
Location: mm/memcontrol.c:1182
Inline: False
```
**Symbols:**

```
ffffffff81284b70-ffffffff81284bd7: mem_cgroup_get_max (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int mem_cgroup_get_max(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81299a80)
Location: mm/memcontrol.c:1363
Inline: False
```
**Symbols:**

```
ffffffff81299a80-ffffffff81299ae7: mem_cgroup_get_max (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int mem_cgroup_get_max(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b4c70)
Location: mm/memcontrol.c:1555
Inline: False
```
**Symbols:**

```
ffffffff812b4c70-ffffffff812b4cd6: mem_cgroup_get_max (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int mem_cgroup_get_max(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c6740)
Location: mm/memcontrol.c:1566
Inline: False
```
**Symbols:**

```
ffffffff812c6740-ffffffff812c67a6: mem_cgroup_get_max (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int mem_cgroup_get_max(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812fc1b0)
Location: mm/memcontrol.c:1531
Inline: False
Direct callers:
  - mm/oom_kill.c:constrained_alloc
```
**Symbols:**

```
ffffffff812fc1b0-ffffffff812fc216: mem_cgroup_get_max (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int mem_cgroup_get_max(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81308370)
Location: mm/memcontrol.c:1712
Inline: False
Direct callers:
  - mm/oom_kill.c:constrained_alloc
```
**Symbols:**

```
ffffffff81308370-ffffffff81308427: mem_cgroup_get_max (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int mem_cgroup_get_max(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8130eb00)
Location: mm/memcontrol.c:1535
Inline: False
Direct callers:
  - mm/oom_kill.c:constrained_alloc
```
**Symbols:**

```
ffffffff8130eb00-ffffffff8130eba9: mem_cgroup_get_max (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int mem_cgroup_get_max(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81359980)
Location: mm/memcontrol.c:1587
Inline: False
Direct callers:
  - mm/oom_kill.c:constrained_alloc
```
**Symbols:**

```
ffffffff81359980-ffffffff81359a17: mem_cgroup_get_max (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int mem_cgroup_get_max(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813d19c0)
Location: mm/memcontrol.c:1604
Inline: False
Direct callers:
  - mm/oom_kill.c:constrained_alloc
```
**Symbols:**

```
ffffffff813d19c0-ffffffff813d1a6e: mem_cgroup_get_max (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int mem_cgroup_get_max(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81457020)
Location: mm/memcontrol.c:1664
Inline: False
Direct callers:
  - mm/oom_kill.c:constrained_alloc
```
**Symbols:**

```
ffffffff81457020-ffffffff814570be: mem_cgroup_get_max (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int mem_cgroup_get_max(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8148c8f0)
Location: mm/memcontrol.c:1698
Inline: False
Direct callers:
  - mm/oom_kill.c:constrained_alloc
```
**Symbols:**

```
ffffffff8148c8f0-ffffffff8148c98e: mem_cgroup_get_max (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int mem_cgroup_get_max(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814bc230)
Location: mm/memcontrol.c:1770
Inline: False
Direct callers:
  - mm/oom_kill.c:constrained_alloc
```
**Symbols:**

```
ffffffff814bc230-ffffffff814bc2ce: mem_cgroup_get_max (STB_GLOBAL)
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
long unsigned int mem_cgroup_get_max(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff800010369550)
Location: mm/memcontrol.c:1566
Inline: False
```
**Symbols:**

```
ffff800010369550-ffff8000103695d4: mem_cgroup_get_max (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int mem_cgroup_get_max(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c055aa34)
Location: mm/memcontrol.c:1566
Inline: False
```
**Symbols:**

```
c055aa34-c055aad4: mem_cgroup_get_max (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int mem_cgroup_get_max(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c000000000457d80)
Location: mm/memcontrol.c:1566
Inline: False
```
**Symbols:**

```
c000000000457d80-c000000000457e30: mem_cgroup_get_max (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int mem_cgroup_get_max(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffe000247018)
Location: mm/memcontrol.c:1566
Inline: False
```
**Symbols:**

```
ffffffe000247018-ffffffe0002470a4: mem_cgroup_get_max (STB_GLOBAL)
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
long unsigned int mem_cgroup_get_max(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bed20)
Location: mm/memcontrol.c:1566
Inline: False
```
**Symbols:**

```
ffffffff812bed20-ffffffff812bed86: mem_cgroup_get_max (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int mem_cgroup_get_max(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812afe10)
Location: mm/memcontrol.c:1566
Inline: False
```
**Symbols:**

```
ffffffff812afe10-ffffffff812afe76: mem_cgroup_get_max (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int mem_cgroup_get_max(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bcb30)
Location: mm/memcontrol.c:1566
Inline: False
```
**Symbols:**

```
ffffffff812bcb30-ffffffff812bcb96: mem_cgroup_get_max (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int mem_cgroup_get_max(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812cd320)
Location: mm/memcontrol.c:1566
Inline: False
```
**Symbols:**

```
ffffffff812cd320-ffffffff812cd386: mem_cgroup_get_max (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
