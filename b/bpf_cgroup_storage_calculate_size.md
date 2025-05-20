# Function: <code>bpf_cgroup_storage_calculate_size</code>

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
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
size_t bpf_cgroup_storage_calculate_size(struct bpf_map *map, u32 *pages);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811d82c0)
Location: kernel/bpf/local_storage.c:440
Inline: True
Direct callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_free
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
```
**Symbols:**

```
ffffffff811d82c0-ffffffff811d8338: bpf_cgroup_storage_calculate_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
size_t bpf_cgroup_storage_calculate_size(struct bpf_map *map, u32 *pages);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811ecd70)
Location: kernel/bpf/local_storage.c:460
Inline: True
Direct callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_free
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
```
**Symbols:**

```
ffffffff811ecd70-ffffffff811ecddb: bpf_cgroup_storage_calculate_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
size_t bpf_cgroup_storage_calculate_size(struct bpf_map *map, u32 *pages);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811f94c0)
Location: kernel/bpf/local_storage.c:460
Inline: True
Direct callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_free
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
```
**Symbols:**

```
ffffffff811f94c0-ffffffff811f952b: bpf_cgroup_storage_calculate_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
size_t bpf_cgroup_storage_calculate_size(struct bpf_map *map, u32 *pages);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff8121cf20)
Location: kernel/bpf/local_storage.c:460
Inline: True
Direct callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_free
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
```
**Symbols:**

```
ffffffff8121cf20-ffffffff8121cf8b: bpf_cgroup_storage_calculate_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff812204e2)
Location: kernel/bpf/local_storage.c:469
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff81223f72)
Location: kernel/bpf/local_storage.c:470
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
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
In kernel/bpf/local_storage.c (ffffffff8125be73)
Location: kernel/bpf/local_storage.c:476
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
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
In kernel/bpf/local_storage.c (ffffffff812a59a3)
Location: kernel/bpf/local_storage.c:476
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
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
In kernel/bpf/local_storage.c (ffffffff8130393b)
Location: kernel/bpf/local_storage.c:475
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
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
In kernel/bpf/local_storage.c (ffffffff8133236b)
Location: kernel/bpf/local_storage.c:482
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
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
In kernel/bpf/local_storage.c (ffffffff8135691b)
Location: kernel/bpf/local_storage.c:482
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
size_t bpf_cgroup_storage_calculate_size(struct bpf_map *map, u32 *pages);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffff80001027e720)
Location: kernel/bpf/local_storage.c:460
Inline: True
Direct callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_free
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
```
**Symbols:**

```
ffff80001027e720-ffff80001027e7b4: bpf_cgroup_storage_calculate_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
size_t bpf_cgroup_storage_calculate_size(struct bpf_map *map, u32 *pages);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (c04b0138)
Location: kernel/bpf/local_storage.c:460
Inline: True
Direct callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_free
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
```
**Symbols:**

```
c04b0138-c04b01b0: bpf_cgroup_storage_calculate_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
size_t bpf_cgroup_storage_calculate_size(struct bpf_map *map, u32 *pages);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (c000000000328d20)
Location: kernel/bpf/local_storage.c:460
Inline: True
Direct callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_free
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
```
**Symbols:**

```
c000000000328d20-c000000000328de4: bpf_cgroup_storage_calculate_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
size_t bpf_cgroup_storage_calculate_size(struct bpf_map *map, u32 *pages);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffe0001b5b58)
Location: kernel/bpf/local_storage.c:460
Inline: True
Direct callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_free
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
```
**Symbols:**

```
ffffffe0001b5b58-ffffffe0001b5be0: bpf_cgroup_storage_calculate_size (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
size_t bpf_cgroup_storage_calculate_size(struct bpf_map *map, u32 *pages);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811f1ae0)
Location: kernel/bpf/local_storage.c:460
Inline: True
Direct callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_free
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
```
**Symbols:**

```
ffffffff811f1ae0-ffffffff811f1b4b: bpf_cgroup_storage_calculate_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
size_t bpf_cgroup_storage_calculate_size(struct bpf_map *map, u32 *pages);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811e4830)
Location: kernel/bpf/local_storage.c:460
Inline: True
Direct callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_free
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
```
**Symbols:**

```
ffffffff811e4830-ffffffff811e489b: bpf_cgroup_storage_calculate_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
size_t bpf_cgroup_storage_calculate_size(struct bpf_map *map, u32 *pages);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811ef8b0)
Location: kernel/bpf/local_storage.c:460
Inline: True
Direct callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_free
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
```
**Symbols:**

```
ffffffff811ef8b0-ffffffff811ef91b: bpf_cgroup_storage_calculate_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
size_t bpf_cgroup_storage_calculate_size(struct bpf_map *map, u32 *pages);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811fdd90)
Location: kernel/bpf/local_storage.c:460
Inline: True
Direct callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_free
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_alloc
```
**Symbols:**

```
ffffffff811fdd90-ffffffff811fddfb: bpf_cgroup_storage_calculate_size (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
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
