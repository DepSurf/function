# Function: <code>mem_cgroup_swapin_uncharge_swap</code>

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
void mem_cgroup_swapin_uncharge_swap(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81310db0)
Location: mm/memcontrol.c:6618
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:__read_swap_cache_async
```
**Symbols:**

```
ffffffff81310db0-ffffffff81310dda: mem_cgroup_swapin_uncharge_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mem_cgroup_swapin_uncharge_swap(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8135c080)
Location: mm/memcontrol.c:6802
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:__read_swap_cache_async
```
**Symbols:**

```
ffffffff8135c080-ffffffff8135c0b1: mem_cgroup_swapin_uncharge_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mem_cgroup_swapin_uncharge_swap(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813d59b0)
Location: mm/memcontrol.c:6792
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:__read_swap_cache_async
```
**Symbols:**

```
ffffffff813d59b0-ffffffff813d59f4: mem_cgroup_swapin_uncharge_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mem_cgroup_swapin_uncharge_swap(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8145b410)
Location: mm/memcontrol.c:6981
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:__read_swap_cache_async
```
**Symbols:**

```
ffffffff8145b410-ffffffff8145b445: mem_cgroup_swapin_uncharge_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mem_cgroup_swapin_uncharge_swap(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81491080)
Location: mm/memcontrol.c:7049
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:__read_swap_cache_async
```
**Symbols:**

```
ffffffff81491080-ffffffff814910b5: mem_cgroup_swapin_uncharge_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mem_cgroup_swapin_uncharge_swap(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814c09f0)
Location: mm/memcontrol.c:7376
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/swap_state.c:__read_swap_cache_async
```
**Symbols:**

```
ffffffff814c09f0-ffffffff814c0a25: mem_cgroup_swapin_uncharge_swap (STB_GLOBAL)
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
