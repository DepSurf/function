# Function: <code>bpf_map_charge_move</code>

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
void bpf_map_charge_move(struct bpf_map_memory *dst, struct bpf_map_memory *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d3f10)
Location: kernel/bpf/syscall.c:228
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_free_deferred
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
```
**Symbols:**

```
ffffffff811d3f10-ffffffff811d3f38: bpf_map_charge_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bpf_map_charge_move(struct bpf_map_memory *dst, struct bpf_map_memory *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e02a0)
Location: kernel/bpf/syscall.c:231
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_free_deferred
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
```
**Symbols:**

```
ffffffff811e02a0-ffffffff811e02c8: bpf_map_charge_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_charge_move(struct bpf_map_memory *dst, struct bpf_map_memory *src);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811feece)
Location: kernel/bpf/syscall.c:385
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_free_deferred
Direct callers:
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
```
**Symbols:**

```
ffffffff811fe840-ffffffff811fe868: bpf_map_charge_move (STB_GLOBAL)
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
void bpf_map_charge_move(struct bpf_map_memory *dst, struct bpf_map_memory *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffff8000102628a0)
Location: kernel/bpf/syscall.c:231
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_free_deferred
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
```
**Symbols:**

```
ffff8000102628a0-ffff8000102628d4: bpf_map_charge_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bpf_map_charge_move(struct bpf_map_memory *dst, struct bpf_map_memory *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c04953e8)
Location: kernel/bpf/syscall.c:231
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_free_deferred
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
```
**Symbols:**

```
c04953e8-c049541c: bpf_map_charge_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bpf_map_charge_move(struct bpf_map_memory *dst, struct bpf_map_memory *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c000000000307570)
Location: kernel/bpf/syscall.c:231
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_free_deferred
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
```
**Symbols:**

```
c000000000307570-c000000000307598: bpf_map_charge_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_charge_move(struct bpf_map_memory *dst, struct bpf_map_memory *src);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffe00019fa6c)
Location: kernel/bpf/syscall.c:231
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_free_deferred
Direct callers:
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
```
**Symbols:**

```
ffffffe00019f22c-ffffffe00019f26c: bpf_map_charge_move (STB_GLOBAL)
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
void bpf_map_charge_move(struct bpf_map_memory *dst, struct bpf_map_memory *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d88c0)
Location: kernel/bpf/syscall.c:231
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_free_deferred
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
```
**Symbols:**

```
ffffffff811d88c0-ffffffff811d88e8: bpf_map_charge_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bpf_map_charge_move(struct bpf_map_memory *dst, struct bpf_map_memory *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811cb680)
Location: kernel/bpf/syscall.c:231
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_free_deferred
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
```
**Symbols:**

```
ffffffff811cb680-ffffffff811cb6a8: bpf_map_charge_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bpf_map_charge_move(struct bpf_map_memory *dst, struct bpf_map_memory *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d6690)
Location: kernel/bpf/syscall.c:231
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_free_deferred
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
```
**Symbols:**

```
ffffffff811d6690-ffffffff811d66b8: bpf_map_charge_move (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bpf_map_charge_move(struct bpf_map_memory *dst, struct bpf_map_memory *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e4a00)
Location: kernel/bpf/syscall.c:231
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_free_deferred
  - kernel/bpf/arraymap.c:array_map_alloc
  - kernel/bpf/local_storage.c:cgroup_storage_map_alloc
  - kernel/bpf/queue_stack_maps.c:queue_stack_map_alloc
  - kernel/bpf/stackmap.c:stack_map_alloc
  - kernel/bpf/reuseport_array.c:reuseport_array_alloc
```
**Symbols:**

```
ffffffff811e4a00-ffffffff811e4a28: bpf_map_charge_move (STB_GLOBAL)
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
