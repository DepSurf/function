# Function: <code>mem_cgroup_cgwb_list</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct list_head *mem_cgroup_cgwb_list(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff811fff70)
Location: mm/memcontrol.c:3700
Inline: False
Direct callers:
  - mm/backing-dev.c:wb_get_create
  - mm/backing-dev.c:wb_memcg_offline
```
**Symbols:**

```
ffffffff811fff70-ffffffff811fff82: mem_cgroup_cgwb_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct list_head *mem_cgroup_cgwb_list(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81223ce0)
Location: mm/memcontrol.c:3624
Inline: False
Direct callers:
  - mm/backing-dev.c:wb_memcg_offline
  - mm/backing-dev.c:wb_get_create
```
**Symbols:**

```
ffffffff81223ce0-ffffffff81223cf2: mem_cgroup_cgwb_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct list_head *mem_cgroup_cgwb_list(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812361d0)
Location: mm/memcontrol.c:3597
Inline: False
Direct callers:
  - mm/backing-dev.c:wb_memcg_offline
  - mm/backing-dev.c:wb_get_create
```
**Symbols:**

```
ffffffff812361d0-ffffffff812361e2: mem_cgroup_cgwb_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct list_head *mem_cgroup_cgwb_list(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81241c50)
Location: mm/memcontrol.c:3617
Inline: False
Direct callers:
  - mm/backing-dev.c:wb_memcg_offline
  - mm/backing-dev.c:wb_get_create
```
**Symbols:**

```
ffffffff81241c50-ffffffff81241c62: mem_cgroup_cgwb_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct list_head *mem_cgroup_cgwb_list(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812619a0)
Location: mm/memcontrol.c:3644
Inline: False
Direct callers:
  - mm/backing-dev.c:wb_memcg_offline
  - mm/backing-dev.c:wb_get_create
```
**Symbols:**

```
ffffffff812619a0-ffffffff812619b2: mem_cgroup_cgwb_list (STB_GLOBAL)
```
</details>
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
</ul>
