# Function: <code>free_shrinker_info</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void free_shrinker_info(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812763e0)
Location: mm/vmscan.c:249
Inline: False
Direct callers:
  - mm/vmscan.c:alloc_shrinker_info
  - mm/memcontrol.c:mem_cgroup_css_free
```
**Symbols:**

```
ffffffff812763e0-ffffffff8127645d: free_shrinker_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void free_shrinker_info(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812b3c00)
Location: mm/vmscan.c:253
Inline: False
Direct callers:
  - mm/vmscan.c:alloc_shrinker_info
  - mm/memcontrol.c:mem_cgroup_css_free
```
**Symbols:**

```
ffffffff812b3c00-ffffffff812b3c7d: free_shrinker_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void free_shrinker_info(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8130fb60)
Location: mm/vmscan.c:255
Inline: False
Direct callers:
  - mm/vmscan.c:alloc_shrinker_info
  - mm/memcontrol.c:mem_cgroup_css_free
```
**Symbols:**

```
ffffffff8130fb60-ffffffff8130fbf1: free_shrinker_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void free_shrinker_info(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81383170)
Location: mm/vmscan.c:269
Inline: False
Direct callers:
  - mm/vmscan.c:alloc_shrinker_info
  - mm/memcontrol.c:mem_cgroup_css_free
```
**Symbols:**

```
ffffffff81383170-ffffffff813831f1: free_shrinker_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void free_shrinker_info(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813b4990)
Location: mm/vmscan.c:259
Inline: False
Direct callers:
  - mm/vmscan.c:alloc_shrinker_info
  - mm/memcontrol.c:mem_cgroup_css_free
```
**Symbols:**

```
ffffffff813b4990-ffffffff813b4a11: free_shrinker_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void free_shrinker_info(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shrinker.c (ffffffff813e4530)
Location: mm/shrinker.c:62
Inline: False
Direct callers:
  - mm/shrinker.c:alloc_shrinker_info
  - mm/memcontrol.c:mem_cgroup_css_free
```
**Symbols:**

```
ffffffff813e4530-ffffffff813e4618: free_shrinker_info (STB_GLOBAL)
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
