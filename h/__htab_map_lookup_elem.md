# Function: <code>__htab_map_lookup_elem</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *__htab_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81186b70)
Location: kernel/bpf/hashtab.c:295
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_lookup_elem
```
**Symbols:**

```
ffffffff81186b70-ffffffff81186d0b: __htab_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *__htab_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81193c70)
Location: kernel/bpf/hashtab.c:387
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_lookup_elem
```
**Symbols:**

```
ffffffff81193c70-ffffffff81193e0e: __htab_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *__htab_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8119ad60)
Location: kernel/bpf/hashtab.c:440
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem
```
**Symbols:**

```
ffffffff8119ad60-ffffffff8119af00: __htab_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *__htab_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811aa590)
Location: kernel/bpf/hashtab.c:449
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem
```
**Symbols:**

```
ffffffff811aa590-ffffffff811aa738: __htab_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *__htab_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811c1bd0)
Location: kernel/bpf/hashtab.c:459
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem
```
**Symbols:**

```
ffffffff811c1bd0-ffffffff811c1d89: __htab_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *__htab_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811d30f0)
Location: kernel/bpf/hashtab.c:473
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem
```
**Symbols:**

```
ffffffff811d30f0-ffffffff811d330d: __htab_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *__htab_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811e7dd0)
Location: kernel/bpf/hashtab.c:461
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem
```
**Symbols:**

```
ffffffff811e7dd0-ffffffff811e7fc9: __htab_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *__htab_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811f4530)
Location: kernel/bpf/hashtab.c:461
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem
```
**Symbols:**

```
ffffffff811f4530-ffffffff811f4729: __htab_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void *__htab_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff812190e5)
Location: kernel/bpf/hashtab.c:573
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem
```
**Symbols:**

```
ffffffff81216da0-ffffffff81216df5: __htab_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void *__htab_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8121ba00)
Location: kernel/bpf/hashtab.c:592
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem
```
**Symbols:**

```
ffffffff81219160-ffffffff812191b5: __htab_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void *__htab_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8121f480)
Location: kernel/bpf/hashtab.c:592
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem
```
**Symbols:**

```
ffffffff8121cb60-ffffffff8121cbb5: __htab_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void *__htab_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81255db0)
Location: kernel/bpf/hashtab.c:622
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem
```
**Symbols:**

```
ffffffff81253a60-ffffffff81253ab5: __htab_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void *__htab_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8129eb70)
Location: kernel/bpf/hashtab.c:638
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_percpu_elem
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_percpu_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem
```
**Symbols:**

```
ffffffff8129be80-ffffffff8129bee4: __htab_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void *__htab_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff812fb4e0)
Location: kernel/bpf/hashtab.c:653
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_percpu_elem
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_percpu_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem
```
**Symbols:**

```
ffffffff812f8390-ffffffff812f83f4: __htab_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void *__htab_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81329e30)
Location: kernel/bpf/hashtab.c:660
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_percpu_elem
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_percpu_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem
```
**Symbols:**

```
ffffffff813263e0-ffffffff81326444: __htab_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void *__htab_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8134ccd0)
Location: kernel/bpf/hashtab.c:671
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_percpu_elem
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_percpu_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem
```
**Symbols:**

```
ffffffff8134aa20-ffffffff8134aa84: __htab_map_lookup_elem (STB_LOCAL)
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
void *__htab_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffff800010278650)
Location: kernel/bpf/hashtab.c:461
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem
```
**Symbols:**

```
ffff800010278650-ffff80001027885c: __htab_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *__htab_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (c04aad38)
Location: kernel/bpf/hashtab.c:461
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem
```
**Symbols:**

```
c04aad38-c04aaeec: __htab_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *__htab_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (c000000000321260)
Location: kernel/bpf/hashtab.c:461
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem
```
**Symbols:**

```
c000000000321260-c0000000003214c4: __htab_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *__htab_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffe0001b0794)
Location: kernel/bpf/hashtab.c:461
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem
```
**Symbols:**

```
ffffffe0001b0794-ffffffe0001b0a06: __htab_map_lookup_elem (STB_LOCAL)
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
void *__htab_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811ecb50)
Location: kernel/bpf/hashtab.c:461
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem
```
**Symbols:**

```
ffffffff811ecb50-ffffffff811ecd49: __htab_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *__htab_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811df8e0)
Location: kernel/bpf/hashtab.c:461
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem
```
**Symbols:**

```
ffffffff811df8e0-ffffffff811dfad9: __htab_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *__htab_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811ea920)
Location: kernel/bpf/hashtab.c:461
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem
```
**Symbols:**

```
ffffffff811ea920-ffffffff811eab19: __htab_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *__htab_map_lookup_elem(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811f8d00)
Location: kernel/bpf/hashtab.c:461
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_of_map_lookup_elem
  - kernel/bpf/hashtab.c:bpf_fd_htab_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_seq_show_elem
  - kernel/bpf/hashtab.c:bpf_percpu_hash_copy
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_elem
  - kernel/bpf/hashtab.c:htab_map_seq_show_elem
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem_sys
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_elem
```
**Symbols:**

```
ffffffff811f8d00-ffffffff811f8ef9: __htab_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
