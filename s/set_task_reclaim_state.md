# Function: <code>set_task_reclaim_state</code>

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
void set_task_reclaim_state(struct task_struct *task, struct reclaim_state *rs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81228230)
Location: mm/vmscan.c:241
Inline: False
Direct callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
```
**Symbols:**

```
ffffffff81228230-ffffffff81228265: set_task_reclaim_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void set_task_reclaim_state(struct task_struct *task, struct reclaim_state *rs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812360d0)
Location: mm/vmscan.c:174
Inline: False
Direct callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
```
**Symbols:**

```
ffffffff812360d0-ffffffff81236105: set_task_reclaim_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void set_task_reclaim_state(struct task_struct *task, struct reclaim_state *rs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81263760)
Location: mm/vmscan.c:179
Inline: False
Direct callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
```
**Symbols:**

```
ffffffff81263760-ffffffff81263795: set_task_reclaim_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void set_task_reclaim_state(struct task_struct *task, struct reclaim_state *rs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8126e0f0)
Location: mm/vmscan.c:172
Inline: False
Direct callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
```
**Symbols:**

```
ffffffff8126e0f0-ffffffff8126e125: set_task_reclaim_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void set_task_reclaim_state(struct task_struct *task, struct reclaim_state *rs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81272df0)
Location: mm/vmscan.c:175
Inline: False
Direct callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
```
**Symbols:**

```
ffffffff81272df0-ffffffff81272e25: set_task_reclaim_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812b6c5b)
Location: mm/vmscan.c:179
Inline: True
Inline callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81312b5e)
Location: mm/vmscan.c:181
Inline: True
Inline callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81385fac)
Location: mm/vmscan.c:195
Inline: True
Inline callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:lru_gen_seq_write
  - mm/vmscan.c:lru_gen_seq_write
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813b9279)
Location: mm/vmscan.c:508
Inline: True
Inline callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:lru_gen_seq_write
  - mm/vmscan.c:lru_gen_seq_write
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813e227e)
Location: mm/vmscan.c:247
Inline: True
Inline callers:
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:__node_reclaim
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:lru_gen_seq_write
  - mm/vmscan.c:lru_gen_seq_write
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
void set_task_reclaim_state(struct task_struct *task, struct reclaim_state *rs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffff8000102c5e98)
Location: mm/vmscan.c:174
Inline: False
Direct callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
```
**Symbols:**

```
ffff8000102c5e98-ffff8000102c5eec: set_task_reclaim_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void set_task_reclaim_state(struct task_struct *task, struct reclaim_state *rs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c04f1314)
Location: mm/vmscan.c:174
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
```
**Symbols:**

```
c04f1314-c04f13bc: set_task_reclaim_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void set_task_reclaim_state(struct task_struct *task, struct reclaim_state *rs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c000000000381e90)
Location: mm/vmscan.c:174
Inline: False
Direct callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
```
**Symbols:**

```
c000000000381e90-c000000000381ed4: set_task_reclaim_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void set_task_reclaim_state(struct task_struct *task, struct reclaim_state *rs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffe0001e68ee)
Location: mm/vmscan.c:174
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
```
**Symbols:**

```
ffffffe0001e68ee-ffffffe0001e6938: set_task_reclaim_state (STB_LOCAL)
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
void set_task_reclaim_state(struct task_struct *task, struct reclaim_state *rs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8122e720)
Location: mm/vmscan.c:174
Inline: False
Direct callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
```
**Symbols:**

```
ffffffff8122e720-ffffffff8122e755: set_task_reclaim_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void set_task_reclaim_state(struct task_struct *task, struct reclaim_state *rs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812217e0)
Location: mm/vmscan.c:174
Inline: False
Direct callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
```
**Symbols:**

```
ffffffff812217e0-ffffffff81221815: set_task_reclaim_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void set_task_reclaim_state(struct task_struct *task, struct reclaim_state *rs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8122c4c0)
Location: mm/vmscan.c:174
Inline: False
Direct callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
```
**Symbols:**

```
ffffffff8122c4c0-ffffffff8122c4f5: set_task_reclaim_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void set_task_reclaim_state(struct task_struct *task, struct reclaim_state *rs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8123b8b0)
Location: mm/vmscan.c:174
Inline: False
Direct callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:shrink_all_memory
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_mem_cgroup_pages
  - mm/vmscan.c:try_to_free_pages
  - mm/vmscan.c:try_to_free_pages
```
**Symbols:**

```
ffffffff8123b8b0-ffffffff8123b8e5: set_task_reclaim_state (STB_LOCAL)
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
