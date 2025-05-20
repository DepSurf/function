# Function: <code>cgroup_storage_lookup</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
struct bpf_cgroup_storage *cgroup_storage_lookup(struct bpf_cgroup_storage_map *map, struct bpf_cgroup_storage_key *key, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811d7f90)
Location: kernel/bpf/local_storage.c:48
Inline: False
Direct callers:
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_lookup_elem
```
**Symbols:**

```
ffffffff811d7f90-ffffffff811d805c: cgroup_storage_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct bpf_cgroup_storage *cgroup_storage_lookup(struct bpf_cgroup_storage_map *map, struct bpf_cgroup_storage_key *key, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811ec9b0)
Location: kernel/bpf/local_storage.c:48
Inline: False
Direct callers:
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_lookup_elem
```
**Symbols:**

```
ffffffff811ec9b0-ffffffff811eca6c: cgroup_storage_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct bpf_cgroup_storage *cgroup_storage_lookup(struct bpf_cgroup_storage_map *map, struct bpf_cgroup_storage_key *key, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811f9100)
Location: kernel/bpf/local_storage.c:48
Inline: False
Direct callers:
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_lookup_elem
```
**Symbols:**

```
ffffffff811f9100-ffffffff811f91bc: cgroup_storage_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct bpf_cgroup_storage *cgroup_storage_lookup(struct bpf_cgroup_storage_map *map, struct bpf_cgroup_storage_key *key, bool locked);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff8121d335)
Location: kernel/bpf/local_storage.c:48
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:cgroup_storage_lookup_elem
Direct callers:
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
```
**Symbols:**

```
ffffffff8121cf90-ffffffff8121d043: cgroup_storage_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct bpf_cgroup_storage *cgroup_storage_lookup(struct bpf_cgroup_storage_map *map, void *key, bool locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff8121fef0)
Location: kernel/bpf/local_storage.c:67
Inline: False
Direct callers:
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_lookup_elem
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
```
**Symbols:**

```
ffffffff8121fef0-ffffffff8121ffbe: cgroup_storage_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct bpf_cgroup_storage *cgroup_storage_lookup(struct bpf_cgroup_storage_map *map, void *key, bool locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff81223980)
Location: kernel/bpf/local_storage.c:68
Inline: False
Direct callers:
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_lookup_elem
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
```
**Symbols:**

```
ffffffff81223980-ffffffff81223a4e: cgroup_storage_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct bpf_cgroup_storage *cgroup_storage_lookup(struct bpf_cgroup_storage_map *map, void *key, bool locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff8125b7b0)
Location: kernel/bpf/local_storage.c:66
Inline: False
Direct callers:
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_lookup_elem
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
```
**Symbols:**

```
ffffffff8125b7b0-ffffffff8125b87e: cgroup_storage_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct bpf_cgroup_storage *cgroup_storage_lookup(struct bpf_cgroup_storage_map *map, void *key, bool locked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff812a51c0)
Location: kernel/bpf/local_storage.c:67
Inline: False
Direct callers:
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_lookup_elem
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
```
**Symbols:**

```
ffffffff812a51c0-ffffffff812a52ea: cgroup_storage_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline ⚠️</summary>

```c
struct bpf_cgroup_storage *cgroup_storage_lookup(struct bpf_cgroup_storage_map *map, void *key, bool locked);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff81302fb0)
Location: kernel/bpf/local_storage.c:67
Inline: False
Direct callers:
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_lookup_elem
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
```
```
In kernel/bpf/bpf_cgrp_storage.c (ffffffff813258bd)
Location: kernel/bpf/bpf_cgrp_storage.c:71
Inline: True
Inline callers:
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_delete
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_get
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_delete_elem
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_lookup_elem
```
**Symbols:**

```
ffffffff81302fb0-ffffffff813030da: cgroup_storage_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline ⚠️</summary>

```c
struct bpf_cgroup_storage *cgroup_storage_lookup(struct bpf_cgroup_storage_map *map, void *key, bool locked);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff81331a50)
Location: kernel/bpf/local_storage.c:67
Inline: False
Direct callers:
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_lookup_elem
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
```
```
In kernel/bpf/bpf_cgrp_storage.c (ffffffff81355b0d)
Location: kernel/bpf/bpf_cgrp_storage.c:64
Inline: True
Inline callers:
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_delete
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_get
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_delete_elem
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_lookup_elem
```
**Symbols:**

```
ffffffff81331a50-ffffffff81331b7b: cgroup_storage_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline ⚠️</summary>

```c
struct bpf_cgroup_storage *cgroup_storage_lookup(struct bpf_cgroup_storage_map *map, void *key, bool locked);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff81355ff0)
Location: kernel/bpf/local_storage.c:67
Inline: False
Direct callers:
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_lookup_elem
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
```
```
In kernel/bpf/bpf_cgrp_storage.c (ffffffff8137e63d)
Location: kernel/bpf/bpf_cgrp_storage.c:64
Inline: True
Inline callers:
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_delete
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_get
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_delete_elem
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_lookup_elem
```
**Symbols:**

```
ffffffff81355ff0-ffffffff8135611b: cgroup_storage_lookup (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct bpf_cgroup_storage *cgroup_storage_lookup(struct bpf_cgroup_storage_map *map, struct bpf_cgroup_storage_key *key, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffff80001027e7b8)
Location: kernel/bpf/local_storage.c:48
Inline: False
Direct callers:
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_lookup_elem
```
**Symbols:**

```
ffff80001027e7b8-ffff80001027e928: cgroup_storage_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct bpf_cgroup_storage *cgroup_storage_lookup(struct bpf_cgroup_storage_map *map, struct bpf_cgroup_storage_key *key, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (c04afd28)
Location: kernel/bpf/local_storage.c:48
Inline: False
Direct callers:
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_lookup_elem
```
**Symbols:**

```
c04afd28-c04afe00: cgroup_storage_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct bpf_cgroup_storage *cgroup_storage_lookup(struct bpf_cgroup_storage_map *map, struct bpf_cgroup_storage_key *key, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (c000000000328690)
Location: kernel/bpf/local_storage.c:48
Inline: False
Direct callers:
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_lookup_elem
```
**Symbols:**

```
c000000000328690-c000000000328824: cgroup_storage_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct bpf_cgroup_storage *cgroup_storage_lookup(struct bpf_cgroup_storage_map *map, struct bpf_cgroup_storage_key *key, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffe0001b56f4)
Location: kernel/bpf/local_storage.c:48
Inline: False
Direct callers:
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_lookup_elem
```
**Symbols:**

```
ffffffe0001b56f4-ffffffe0001b57a0: cgroup_storage_lookup (STB_LOCAL)
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
struct bpf_cgroup_storage *cgroup_storage_lookup(struct bpf_cgroup_storage_map *map, struct bpf_cgroup_storage_key *key, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811f1720)
Location: kernel/bpf/local_storage.c:48
Inline: False
Direct callers:
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_lookup_elem
```
**Symbols:**

```
ffffffff811f1720-ffffffff811f17dc: cgroup_storage_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct bpf_cgroup_storage *cgroup_storage_lookup(struct bpf_cgroup_storage_map *map, struct bpf_cgroup_storage_key *key, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811e4470)
Location: kernel/bpf/local_storage.c:48
Inline: False
Direct callers:
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_lookup_elem
```
**Symbols:**

```
ffffffff811e4470-ffffffff811e452c: cgroup_storage_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct bpf_cgroup_storage *cgroup_storage_lookup(struct bpf_cgroup_storage_map *map, struct bpf_cgroup_storage_key *key, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811ef4f0)
Location: kernel/bpf/local_storage.c:48
Inline: False
Direct callers:
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_lookup_elem
```
**Symbols:**

```
ffffffff811ef4f0-ffffffff811ef5ac: cgroup_storage_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct bpf_cgroup_storage *cgroup_storage_lookup(struct bpf_cgroup_storage_map *map, struct bpf_cgroup_storage_key *key, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811fd9c0)
Location: kernel/bpf/local_storage.c:48
Inline: False
Direct callers:
  - kernel/bpf/local_storage.c:cgroup_storage_seq_show_elem
  - kernel/bpf/local_storage.c:cgroup_storage_get_next_key
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_update
  - kernel/bpf/local_storage.c:bpf_percpu_cgroup_storage_copy
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_update_elem
  - kernel/bpf/local_storage.c:cgroup_storage_lookup_elem
```
**Symbols:**

```
ffffffff811fd9c0-ffffffff811fda7c: cgroup_storage_lookup (STB_LOCAL)
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
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct bpf_cgroup_storage_key *key</code> ➡️ <code>void *key</code>
</li>
</ul>
</details>
</li>
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
