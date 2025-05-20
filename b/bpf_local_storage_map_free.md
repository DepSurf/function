# Function: <code>bpf_local_storage_map_free</code>

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
void bpf_local_storage_map_free(struct bpf_local_storage_map *smap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff81230260)
Location: kernel/bpf/bpf_local_storage.c:471
Inline: False
Direct callers:
  - kernel/bpf/bpf_inode_storage.c:inode_storage_map_free
  - kernel/bpf/bpf_task_storage.c:task_storage_map_free
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
```
**Symbols:**

```
ffffffff81230260-ffffffff8123030b: bpf_local_storage_map_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bpf_local_storage_map_free(struct bpf_local_storage_map *smap, int *busy_counter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff81225820)
Location: kernel/bpf/bpf_local_storage.c:477
Inline: False
Direct callers:
  - kernel/bpf/bpf_task_storage.c:task_storage_map_free
  - kernel/bpf/bpf_inode_storage.c:inode_storage_map_free
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
```
**Symbols:**

```
ffffffff81225820-ffffffff812258e3: bpf_local_storage_map_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void bpf_local_storage_map_free(struct bpf_local_storage_map *smap, int *busy_counter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (0)
Location: kernel/bpf/bpf_local_storage.c:477
Inline: False
Direct callers:
  - kernel/bpf/bpf_task_storage.c:task_storage_map_free
  - kernel/bpf/bpf_inode_storage.c:inode_storage_map_free
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
```
**Symbols:**

```
ffffffff81cb930d-ffffffff81cb932b: bpf_local_storage_map_free.cold (STB_LOCAL)
ffffffff8125d810-ffffffff8125d8e9: bpf_local_storage_map_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void bpf_local_storage_map_free(struct bpf_local_storage_map *smap, int *busy_counter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (0)
Location: kernel/bpf/bpf_local_storage.c:526
Inline: False
Direct callers:
  - kernel/bpf/bpf_task_storage.c:task_storage_map_free
  - kernel/bpf/bpf_inode_storage.c:inode_storage_map_free
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
```
**Symbols:**

```
ffffffff81e6a601-ffffffff81e6a61f: bpf_local_storage_map_free.cold (STB_LOCAL)
ffffffff812a7b30-ffffffff812a7c14: bpf_local_storage_map_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void bpf_local_storage_map_free(struct bpf_map *map, struct bpf_local_storage_cache *cache, int *busy_counter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (0)
Location: kernel/bpf/bpf_local_storage.c:653
Inline: False
Direct callers:
  - kernel/bpf/bpf_task_storage.c:task_storage_map_free
  - kernel/bpf/bpf_inode_storage.c:inode_storage_map_free
  - kernel/bpf/bpf_cgrp_storage.c:cgroup_storage_map_free
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
```
**Symbols:**

```
ffffffff82061772-ffffffff82061790: bpf_local_storage_map_free.cold (STB_LOCAL)
ffffffff81306510-ffffffff81306618: bpf_local_storage_map_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void bpf_local_storage_map_free(struct bpf_map *map, struct bpf_local_storage_cache *cache, int *busy_counter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (0)
Location: kernel/bpf/bpf_local_storage.c:867
Inline: False
Direct callers:
  - kernel/bpf/bpf_task_storage.c:task_storage_map_free
  - kernel/bpf/bpf_inode_storage.c:inode_storage_map_free
  - kernel/bpf/bpf_cgrp_storage.c:cgroup_storage_map_free
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
```
**Symbols:**

```
ffffffff820e0e12-ffffffff820e0e3e: bpf_local_storage_map_free.cold (STB_LOCAL)
ffffffff81335430-ffffffff81335588: bpf_local_storage_map_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void bpf_local_storage_map_free(struct bpf_map *map, struct bpf_local_storage_cache *cache, int *busy_counter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (0)
Location: kernel/bpf/bpf_local_storage.c:848
Inline: False
Direct callers:
  - kernel/bpf/bpf_task_storage.c:task_storage_map_free
  - kernel/bpf/bpf_inode_storage.c:inode_storage_map_free
  - kernel/bpf/bpf_cgrp_storage.c:cgroup_storage_map_free
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
```
**Symbols:**

```
ffffffff821bd5c7-ffffffff821bd5f3: bpf_local_storage_map_free.cold (STB_LOCAL)
ffffffff81359a90-ffffffff81359be8: bpf_local_storage_map_free (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int *busy_counter</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bpf_map *map</code>
</li>
<li>
<b>Param added. </b>
<code>struct bpf_local_storage_cache *cache</code>
</li>
<li>
<b>Param removed. </b>
<code>struct bpf_local_storage_map *smap</code>
</li>
<li>
<b>Param reordered. </b>
<code>smap, busy_counter</code> ➡️ <code>map, cache, busy_counter</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
