# Function: <code>bpf_selem_free</code>

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
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void bpf_selem_free(struct bpf_local_storage_elem *selem, struct bpf_local_storage_map *smap, bool reuse_now);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff81334293)
Location: kernel/bpf/bpf_local_storage.c:225
Inline: True
Direct callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_storage_nolock
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
**Symbols:**

```
ffffffff820e0cf5-ffffffff820e0d0a: bpf_selem_free.cold (STB_LOCAL)
ffffffff81334250-ffffffff8133430f: bpf_selem_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void bpf_selem_free(struct bpf_local_storage_elem *selem, struct bpf_local_storage_map *smap, bool reuse_now);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff81358983)
Location: kernel/bpf/bpf_local_storage.c:225
Inline: True
Direct callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - net/core/bpf_sk_storage.c:bpf_sk_storage_clone
```
**Symbols:**

```
ffffffff821bd4aa-ffffffff821bd4bf: bpf_selem_free.cold (STB_LOCAL)
ffffffff81358940-ffffffff813589ff: bpf_selem_free (STB_GLOBAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
