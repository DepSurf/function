# Function: <code>mem_cgroup_calculate_protection</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mem_cgroup_calculate_protection(struct mem_cgroup *root, struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81309a40)
Location: mm/memcontrol.c:6646
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node_memcgs
```
**Symbols:**

```
ffffffff81309a40-ffffffff81309b7f: mem_cgroup_calculate_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mem_cgroup_calculate_protection(struct mem_cgroup *root, struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81310090)
Location: mm/memcontrol.c:6475
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node_memcgs
```
**Symbols:**

```
ffffffff81310090-ffffffff813101d2: mem_cgroup_calculate_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mem_cgroup_calculate_protection(struct mem_cgroup *root, struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8135b3e0)
Location: mm/memcontrol.c:6661
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node_memcgs
```
**Symbols:**

```
ffffffff8135b3e0-ffffffff8135b522: mem_cgroup_calculate_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mem_cgroup_calculate_protection(struct mem_cgroup *root, struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813d4b20)
Location: mm/memcontrol.c:6667
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node_memcgs
```
**Symbols:**

```
ffffffff813d4b20-ffffffff813d4c99: mem_cgroup_calculate_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mem_cgroup_calculate_protection(struct mem_cgroup *root, struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8145a590)
Location: mm/memcontrol.c:6857
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:lru_gen_age_node
```
**Symbols:**

```
ffffffff8145a590-ffffffff8145a709: mem_cgroup_calculate_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mem_cgroup_calculate_protection(struct mem_cgroup *root, struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814901f0)
Location: mm/memcontrol.c:6925
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_one
  - mm/vmscan.c:lru_gen_age_node
```
**Symbols:**

```
ffffffff814901f0-ffffffff81490369: mem_cgroup_calculate_protection (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mem_cgroup_calculate_protection(struct mem_cgroup *root, struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814bfa00)
Location: mm/memcontrol.c:7224
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_one
  - mm/vmscan.c:lru_gen_age_node
```
**Symbols:**

```
ffffffff814bfa00-ffffffff814bfb79: mem_cgroup_calculate_protection (STB_GLOBAL)
```
</details>
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
