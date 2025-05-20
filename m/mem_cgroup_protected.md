# Function: <code>mem_cgroup_protected</code>

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
enum mem_cgroup_protection mem_cgroup_protected(struct mem_cgroup *root, struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81285ad0)
Location: mm/memcontrol.c:5468
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
```
**Symbols:**

```
ffffffff81285ad0-ffffffff81285be6: mem_cgroup_protected (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
enum mem_cgroup_protection mem_cgroup_protected(struct mem_cgroup *root, struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8129a9e0)
Location: mm/memcontrol.c:5786
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
```
**Symbols:**

```
ffffffff8129a9e0-ffffffff8129aaf6: mem_cgroup_protected (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
enum mem_cgroup_protection mem_cgroup_protected(struct mem_cgroup *root, struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b5c80)
Location: mm/memcontrol.c:6078
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
```
**Symbols:**

```
ffffffff812b5c80-ffffffff812b5d96: mem_cgroup_protected (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
enum mem_cgroup_protection mem_cgroup_protected(struct mem_cgroup *root, struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c7b70)
Location: mm/memcontrol.c:6418
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
```
**Symbols:**

```
ffffffff812c7b70-ffffffff812c7c86: mem_cgroup_protected (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
enum mem_cgroup_protection mem_cgroup_protected(struct mem_cgroup *root, struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812fd600)
Location: mm/memcontrol.c:6401
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node_memcgs
```
**Symbols:**

```
ffffffff812fd600-ffffffff812fd75d: mem_cgroup_protected (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
enum mem_cgroup_protection mem_cgroup_protected(struct mem_cgroup *root, struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff80001036aa40)
Location: mm/memcontrol.c:6418
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
```
**Symbols:**

```
ffff80001036aa40-ffff80001036ab64: mem_cgroup_protected (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
enum mem_cgroup_protection mem_cgroup_protected(struct mem_cgroup *root, struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c055c038)
Location: mm/memcontrol.c:6418
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
```
**Symbols:**

```
c055c038-c055c174: mem_cgroup_protected (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
enum mem_cgroup_protection mem_cgroup_protected(struct mem_cgroup *root, struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c000000000459d90)
Location: mm/memcontrol.c:6418
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
```
**Symbols:**

```
c000000000459d90-c000000000459f88: mem_cgroup_protected (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
enum mem_cgroup_protection mem_cgroup_protected(struct mem_cgroup *root, struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffe000248236)
Location: mm/memcontrol.c:6418
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
```
**Symbols:**

```
ffffffe000248236-ffffffe000248326: mem_cgroup_protected (STB_GLOBAL)
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
enum mem_cgroup_protection mem_cgroup_protected(struct mem_cgroup *root, struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c0150)
Location: mm/memcontrol.c:6418
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
```
**Symbols:**

```
ffffffff812c0150-ffffffff812c0266: mem_cgroup_protected (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
enum mem_cgroup_protection mem_cgroup_protected(struct mem_cgroup *root, struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b1220)
Location: mm/memcontrol.c:6418
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
```
**Symbols:**

```
ffffffff812b1220-ffffffff812b1336: mem_cgroup_protected (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
enum mem_cgroup_protection mem_cgroup_protected(struct mem_cgroup *root, struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bdf60)
Location: mm/memcontrol.c:6418
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
```
**Symbols:**

```
ffffffff812bdf60-ffffffff812be076: mem_cgroup_protected (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
enum mem_cgroup_protection mem_cgroup_protected(struct mem_cgroup *root, struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812ce900)
Location: mm/memcontrol.c:6418
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
```
**Symbols:**

```
ffffffff812ce900-ffffffff812cea16: mem_cgroup_protected (STB_GLOBAL)
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
