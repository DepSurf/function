# Function: <code>bpf_local_storage_cache_idx_get</code>

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
u16 bpf_local_storage_cache_idx_get(struct bpf_local_storage_cache *cache);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff812301c0)
Location: kernel/bpf/bpf_local_storage.c:439
Inline: False
Direct callers:
  - kernel/bpf/bpf_inode_storage.c:inode_storage_map_alloc
  - kernel/bpf/bpf_task_storage.c:task_storage_map_alloc
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
**Symbols:**

```
ffffffff812301c0-ffffffff81230226: bpf_local_storage_cache_idx_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u16 bpf_local_storage_cache_idx_get(struct bpf_local_storage_cache *cache);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff81225780)
Location: kernel/bpf/bpf_local_storage.c:445
Inline: False
Direct callers:
  - kernel/bpf/bpf_task_storage.c:task_storage_map_alloc
  - kernel/bpf/bpf_inode_storage.c:inode_storage_map_alloc
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
**Symbols:**

```
ffffffff81225780-ffffffff812257e6: bpf_local_storage_cache_idx_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u16 bpf_local_storage_cache_idx_get(struct bpf_local_storage_cache *cache);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff8125d770)
Location: kernel/bpf/bpf_local_storage.c:445
Inline: False
Direct callers:
  - kernel/bpf/bpf_task_storage.c:task_storage_map_alloc
  - kernel/bpf/bpf_inode_storage.c:inode_storage_map_alloc
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
**Symbols:**

```
ffffffff8125d770-ffffffff8125d7d6: bpf_local_storage_cache_idx_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u16 bpf_local_storage_cache_idx_get(struct bpf_local_storage_cache *cache);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff812a7a80)
Location: kernel/bpf/bpf_local_storage.c:494
Inline: False
Direct callers:
  - kernel/bpf/bpf_task_storage.c:task_storage_map_alloc
  - kernel/bpf/bpf_inode_storage.c:inode_storage_map_alloc
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
**Symbols:**

```
ffffffff812a7a80-ffffffff812a7aef: bpf_local_storage_cache_idx_get (STB_GLOBAL)
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
In kernel/bpf/bpf_local_storage.c (ffffffff81306467)
Location: kernel/bpf/bpf_local_storage.c:504
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
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
In kernel/bpf/bpf_local_storage.c (ffffffff813352ba)
Location: kernel/bpf/bpf_local_storage.c:684
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
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
In kernel/bpf/bpf_local_storage.c (ffffffff8135991a)
Location: kernel/bpf/bpf_local_storage.c:665
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_alloc
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
</ul>
