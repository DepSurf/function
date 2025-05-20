# Function: <code>shrink_node_memcg</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void shrink_node_memcg(struct pglist_data *pgdat, struct mem_cgroup *memcg, struct scan_control *sc, long unsigned int *lru_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811bad50)
Location: mm/vmscan.c:2309
Inline: False
Direct callers:
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:shrink_node
```
**Symbols:**

```
ffffffff811bad50-ffffffff811bb4d8: shrink_node_memcg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void shrink_node_memcg(struct pglist_data *pgdat, struct mem_cgroup *memcg, struct scan_control *sc, long unsigned int *lru_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811cb3e0)
Location: mm/vmscan.c:2321
Inline: False
Direct callers:
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:shrink_node
```
**Symbols:**

```
ffffffff811cb3e0-ffffffff811cbbaa: shrink_node_memcg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void shrink_node_memcg(struct pglist_data *pgdat, struct mem_cgroup *memcg, struct scan_control *sc, long unsigned int *lru_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811d3fe0)
Location: mm/vmscan.c:2361
Inline: False
Direct callers:
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:shrink_node
```
**Symbols:**

```
ffffffff811d3fe0-ffffffff811d4747: shrink_node_memcg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void shrink_node_memcg(struct pglist_data *pgdat, struct mem_cgroup *memcg, struct scan_control *sc, long unsigned int *lru_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811e9530)
Location: mm/vmscan.c:2385
Inline: False
Direct callers:
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:shrink_node
```
**Symbols:**

```
ffffffff811e9530-ffffffff811e9c97: shrink_node_memcg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void shrink_node_memcg(struct pglist_data *pgdat, struct mem_cgroup *memcg, struct scan_control *sc, long unsigned int *lru_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8120aaf0)
Location: mm/vmscan.c:2315
Inline: False
Direct callers:
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:shrink_node
```
**Symbols:**

```
ffffffff8120aaf0-ffffffff8120b259: shrink_node_memcg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void shrink_node_memcg(struct pglist_data *pgdat, struct mem_cgroup *memcg, struct scan_control *sc, long unsigned int *lru_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8121d7f0)
Location: mm/vmscan.c:2485
Inline: False
Direct callers:
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:shrink_node
```
**Symbols:**

```
ffffffff8121d7f0-ffffffff8121df69: shrink_node_memcg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void shrink_node_memcg(struct pglist_data *pgdat, struct mem_cgroup *memcg, struct scan_control *sc, long unsigned int *lru_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8122d270)
Location: mm/vmscan.c:2453
Inline: False
Direct callers:
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:shrink_node
```
**Symbols:**

```
ffffffff8122d270-ffffffff8122d5d9: shrink_node_memcg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void shrink_node_memcg(struct pglist_data *pgdat, struct mem_cgroup *memcg, struct scan_control *sc, long unsigned int *lru_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8123b490)
Location: mm/vmscan.c:2563
Inline: False
Direct callers:
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:shrink_node
```
**Symbols:**

```
ffffffff8123b490-ffffffff8123b7f9: shrink_node_memcg (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void shrink_node_memcg(struct pglist_data *pgdat, struct mem_cgroup *memcg, struct scan_control *sc, long unsigned int *lru_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffff8000102cc588)
Location: mm/vmscan.c:2563
Inline: False
Direct callers:
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:shrink_node
```
**Symbols:**

```
ffff8000102cc588-ffff8000102cc8cc: shrink_node_memcg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void shrink_node_memcg(struct pglist_data *pgdat, struct mem_cgroup *memcg, struct scan_control *sc, long unsigned int *lru_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c04f6300)
Location: mm/vmscan.c:2563
Inline: False
Direct callers:
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:shrink_node
```
**Symbols:**

```
c04f6300-c04f6654: shrink_node_memcg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void shrink_node_memcg(struct pglist_data *pgdat, struct mem_cgroup *memcg, struct scan_control *sc, long unsigned int *lru_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c000000000389b90)
Location: mm/vmscan.c:2563
Inline: False
Direct callers:
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:shrink_node
```
**Symbols:**

```
c000000000389b90-c000000000389f94: shrink_node_memcg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void shrink_node_memcg(struct pglist_data *pgdat, struct mem_cgroup *memcg, struct scan_control *sc, long unsigned int *lru_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffe0001eb044)
Location: mm/vmscan.c:2563
Inline: False
Direct callers:
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:shrink_node
```
**Symbols:**

```
ffffffe0001eb044-ffffffe0001eb30e: shrink_node_memcg (STB_LOCAL)
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
void shrink_node_memcg(struct pglist_data *pgdat, struct mem_cgroup *memcg, struct scan_control *sc, long unsigned int *lru_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81233ae0)
Location: mm/vmscan.c:2563
Inline: False
Direct callers:
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:shrink_node
```
**Symbols:**

```
ffffffff81233ae0-ffffffff81233e49: shrink_node_memcg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void shrink_node_memcg(struct pglist_data *pgdat, struct mem_cgroup *memcg, struct scan_control *sc, long unsigned int *lru_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81226b50)
Location: mm/vmscan.c:2563
Inline: False
Direct callers:
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:shrink_node
```
**Symbols:**

```
ffffffff81226b50-ffffffff81226eb9: shrink_node_memcg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void shrink_node_memcg(struct pglist_data *pgdat, struct mem_cgroup *memcg, struct scan_control *sc, long unsigned int *lru_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81231880)
Location: mm/vmscan.c:2563
Inline: False
Direct callers:
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:shrink_node
```
**Symbols:**

```
ffffffff81231880-ffffffff81231be9: shrink_node_memcg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void shrink_node_memcg(struct pglist_data *pgdat, struct mem_cgroup *memcg, struct scan_control *sc, long unsigned int *lru_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81240cc0)
Location: mm/vmscan.c:2563
Inline: False
Direct callers:
  - mm/vmscan.c:mem_cgroup_shrink_node
  - mm/vmscan.c:shrink_node
```
**Symbols:**

```
ffffffff81240cc0-ffffffff8124104a: shrink_node_memcg (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
