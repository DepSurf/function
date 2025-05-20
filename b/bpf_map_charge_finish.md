# Function: <code>bpf_map_charge_finish</code>

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
void bpf_map_charge_finish(struct bpf_map_memory *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d3ee0)
Location: kernel/bpf/syscall.c:222
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_free_deferred
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
**Symbols:**

```
ffffffff811d3ee0-ffffffff811d3f07: bpf_map_charge_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bpf_map_charge_finish(struct bpf_map_memory *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e0270)
Location: kernel/bpf/syscall.c:225
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_free_deferred
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
**Symbols:**

```
ffffffff811e0270-ffffffff811e0297: bpf_map_charge_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_charge_finish(struct bpf_map_memory *mem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811feef6)
Location: kernel/bpf/syscall.c:379
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_free_deferred
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
  - kernel/bpf/devmap.c:dev_map_init_map
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
**Symbols:**

```
ffffffff811fe810-ffffffff811fe837: bpf_map_charge_finish (STB_GLOBAL)
```
</details>
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
void bpf_map_charge_finish(struct bpf_map_memory *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffff800010262838)
Location: kernel/bpf/syscall.c:225
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_free_deferred
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
  - kernel/bpf/devmap.c:dev_map_init_map
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
**Symbols:**

```
ffff800010262838-ffff80001026289c: bpf_map_charge_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bpf_map_charge_finish(struct bpf_map_memory *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c0495398)
Location: kernel/bpf/syscall.c:225
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_free_deferred
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
  - kernel/bpf/devmap.c:dev_map_init_map
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
**Symbols:**

```
c0495398-c04953e8: bpf_map_charge_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bpf_map_charge_finish(struct bpf_map_memory *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c000000000307510)
Location: kernel/bpf/syscall.c:225
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_free_deferred
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
**Symbols:**

```
c000000000307510-c000000000307570: bpf_map_charge_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_charge_finish(struct bpf_map_memory *mem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffe00019fa8e)
Location: kernel/bpf/syscall.c:225
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_free_deferred
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
  - kernel/bpf/devmap.c:dev_map_init_map
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
**Symbols:**

```
ffffffe00019f1ee-ffffffe00019f22c: bpf_map_charge_finish (STB_GLOBAL)
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
void bpf_map_charge_finish(struct bpf_map_memory *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d8890)
Location: kernel/bpf/syscall.c:225
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_free_deferred
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
**Symbols:**

```
ffffffff811d8890-ffffffff811d88b7: bpf_map_charge_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bpf_map_charge_finish(struct bpf_map_memory *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811cb650)
Location: kernel/bpf/syscall.c:225
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_free_deferred
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
**Symbols:**

```
ffffffff811cb650-ffffffff811cb677: bpf_map_charge_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bpf_map_charge_finish(struct bpf_map_memory *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d6660)
Location: kernel/bpf/syscall.c:225
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_free_deferred
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
**Symbols:**

```
ffffffff811d6660-ffffffff811d6687: bpf_map_charge_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bpf_map_charge_finish(struct bpf_map_memory *mem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e49d0)
Location: kernel/bpf/syscall.c:225
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_free_deferred
  - kernel/bpf/hashtab.c:htab_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
  - net/core/bpf_sk_storage.c:bpf_sk_storage_map_alloc
```
**Symbols:**

```
ffffffff811e49d0-ffffffff811e49f7: bpf_map_charge_finish (STB_GLOBAL)
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
