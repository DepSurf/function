# Function: <code>bpf_local_storage_cache_idx_free</code>

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
void bpf_local_storage_cache_idx_free(struct bpf_local_storage_cache *cache, u16 idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff81230230)
Location: kernel/bpf/bpf_local_storage.c:463
Inline: False
Direct callers:
  - kernel/bpf/bpf_inode_storage.c:inode_storage_map_free
  - kernel/bpf/bpf_task_storage.c:task_storage_map_free
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
```
**Symbols:**

```
ffffffff81230230-ffffffff8123025e: bpf_local_storage_cache_idx_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bpf_local_storage_cache_idx_free(struct bpf_local_storage_cache *cache, u16 idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff812257f0)
Location: kernel/bpf/bpf_local_storage.c:469
Inline: False
Direct callers:
  - kernel/bpf/bpf_task_storage.c:task_storage_map_free
  - kernel/bpf/bpf_inode_storage.c:inode_storage_map_free
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
```
**Symbols:**

```
ffffffff812257f0-ffffffff8122581e: bpf_local_storage_cache_idx_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bpf_local_storage_cache_idx_free(struct bpf_local_storage_cache *cache, u16 idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff8125d7e0)
Location: kernel/bpf/bpf_local_storage.c:469
Inline: False
Direct callers:
  - kernel/bpf/bpf_task_storage.c:task_storage_map_free
  - kernel/bpf/bpf_inode_storage.c:inode_storage_map_free
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
```
**Symbols:**

```
ffffffff8125d7e0-ffffffff8125d80e: bpf_local_storage_cache_idx_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bpf_local_storage_cache_idx_free(struct bpf_local_storage_cache *cache, u16 idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff812a7af0)
Location: kernel/bpf/bpf_local_storage.c:518
Inline: False
Direct callers:
  - kernel/bpf/bpf_task_storage.c:task_storage_map_free
  - kernel/bpf/bpf_inode_storage.c:inode_storage_map_free
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_free
```
**Symbols:**

```
ffffffff812a7af0-ffffffff812a7b26: bpf_local_storage_cache_idx_free (STB_GLOBAL)
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
In kernel/bpf/bpf_local_storage.c (ffffffff81306537)
Location: kernel/bpf/bpf_local_storage.c:528
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free
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
In kernel/bpf/bpf_local_storage.c (ffffffff81335450)
Location: kernel/bpf/bpf_local_storage.c:708
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free
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
In kernel/bpf/bpf_local_storage.c (ffffffff81359ab0)
Location: kernel/bpf/bpf_local_storage.c:689
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free
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
