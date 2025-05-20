# Function: <code>bpf_selem_unlink_map</code>

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
void bpf_selem_unlink_map(struct bpf_local_storage_elem *selem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff8122fba0)
Location: kernel/bpf/bpf_local_storage.c:166
Inline: False
Direct callers:
  - kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_free
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_free
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_alloc
  - net/core/bpf_sk_storage.c:bpf_sk_storage_free
```
**Symbols:**

```
ffffffff8122fba0-ffffffff8122fc1e: bpf_selem_unlink_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bpf_selem_unlink_map(struct bpf_local_storage_elem *selem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff81225150)
Location: kernel/bpf/bpf_local_storage.c:167
Inline: False
Direct callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_alloc
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_free
  - kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_free
  - net/core/bpf_sk_storage.c:bpf_sk_storage_free
```
**Symbols:**

```
ffffffff81225150-ffffffff812251d1: bpf_selem_unlink_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void bpf_selem_unlink_map(struct bpf_local_storage_elem *selem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (0)
Location: kernel/bpf/bpf_local_storage.c:167
Inline: False
Direct callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_alloc
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_free
  - kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_free
  - net/core/bpf_sk_storage.c:bpf_sk_storage_free
```
**Symbols:**

```
ffffffff81cb92d5-ffffffff81cb92f1: bpf_selem_unlink_map.cold (STB_LOCAL)
ffffffff8125d0d0-ffffffff8125d16d: bpf_selem_unlink_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void bpf_selem_unlink_map(struct bpf_local_storage_elem *selem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (0)
Location: kernel/bpf/bpf_local_storage.c:196
Inline: False
Direct callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_alloc
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_free
  - kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_free
  - net/core/bpf_sk_storage.c:bpf_sk_storage_free
```
**Symbols:**

```
ffffffff81e6a5c9-ffffffff81e6a5e5: bpf_selem_unlink_map.cold (STB_LOCAL)
ffffffff812a7210-ffffffff812a72c9: bpf_selem_unlink_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void bpf_selem_unlink_map(struct bpf_local_storage_elem *selem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (0)
Location: kernel/bpf/bpf_local_storage.c:205
Inline: False
Direct callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_unlink_nolock
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_alloc
```
**Symbols:**

```
ffffffff8206171c-ffffffff82061738: bpf_selem_unlink_map.cold (STB_LOCAL)
ffffffff813058e0-ffffffff81305999: bpf_selem_unlink_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void bpf_selem_unlink_map(struct bpf_local_storage_elem *selem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (0)
Location: kernel/bpf/bpf_local_storage.c:377
Inline: False
Direct callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_destroy
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_alloc
```
**Symbols:**

```
ffffffff81333e50-ffffffff81333f0b: bpf_selem_unlink_map (STB_LOCAL)
ffffffff820e0cbe-ffffffff820e0cda: bpf_selem_unlink_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void bpf_selem_unlink_map(struct bpf_local_storage_elem *selem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (0)
Location: kernel/bpf/bpf_local_storage.c:377
Inline: False
Direct callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_destroy
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_alloc
```
**Symbols:**

```
ffffffff81358540-ffffffff813585fb: bpf_selem_unlink_map (STB_LOCAL)
ffffffff821bd473-ffffffff821bd48f: bpf_selem_unlink_map.cold (STB_LOCAL)
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
