# Function: <code>bpf_local_storage_destroy</code>

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
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void bpf_local_storage_destroy(struct bpf_local_storage *local_storage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (0)
Location: kernel/bpf/bpf_local_storage.c:749
Inline: False
Direct callers:
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_free
  - kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_free
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_free
  - net/core/bpf_sk_storage.c:bpf_sk_storage_free
```
**Symbols:**

```
ffffffff820e0d90-ffffffff820e0dba: bpf_local_storage_destroy.cold (STB_LOCAL)
ffffffff81334fe0-ffffffff81335132: bpf_local_storage_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void bpf_local_storage_destroy(struct bpf_local_storage *local_storage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (0)
Location: kernel/bpf/bpf_local_storage.c:730
Inline: False
Direct callers:
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_free
  - kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_free
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_free
  - net/core/bpf_sk_storage.c:bpf_sk_storage_free
```
**Symbols:**

```
ffffffff821bd545-ffffffff821bd56f: bpf_local_storage_destroy.cold (STB_LOCAL)
ffffffff81359650-ffffffff813597a0: bpf_local_storage_destroy (STB_GLOBAL)
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
