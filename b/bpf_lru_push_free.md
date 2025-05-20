# Function: <code>bpf_lru_push_free</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void bpf_lru_push_free(struct bpf_lru *lru, struct bpf_lru_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff81196aa0)
Location: kernel/bpf/bpf_lru_list.c:553
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
```
**Symbols:**

```
ffffffff81196aa0-ffffffff81196c15: bpf_lru_push_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void bpf_lru_push_free(struct bpf_lru *lru, struct bpf_lru_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff8119df00)
Location: kernel/bpf/bpf_lru_list.c:553
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
```
**Symbols:**

```
ffffffff8119df00-ffffffff8119e015: bpf_lru_push_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void bpf_lru_push_free(struct bpf_lru *lru, struct bpf_lru_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811adb10)
Location: kernel/bpf/bpf_lru_list.c:553
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
```
**Symbols:**

```
ffffffff811adb10-ffffffff811adc25: bpf_lru_push_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void bpf_lru_push_free(struct bpf_lru *lru, struct bpf_lru_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811c5090)
Location: kernel/bpf/bpf_lru_list.c:553
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
```
**Symbols:**

```
ffffffff811c5090-ffffffff811c519b: bpf_lru_push_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void bpf_lru_push_free(struct bpf_lru *lru, struct bpf_lru_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811d6c90)
Location: kernel/bpf/bpf_lru_list.c:553
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
```
**Symbols:**

```
ffffffff811d6c90-ffffffff811d6d9b: bpf_lru_push_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void bpf_lru_push_free(struct bpf_lru *lru, struct bpf_lru_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811eb680)
Location: kernel/bpf/bpf_lru_list.c:550
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
```
**Symbols:**

```
ffffffff811eb680-ffffffff811eb786: bpf_lru_push_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bpf_lru_push_free(struct bpf_lru *lru, struct bpf_lru_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811f7de0)
Location: kernel/bpf/bpf_lru_list.c:550
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
```
**Symbols:**

```
ffffffff811f7de0-ffffffff811f7ee6: bpf_lru_push_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bpf_lru_push_free(struct bpf_lru *lru, struct bpf_lru_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff8121bbf0)
Location: kernel/bpf/bpf_lru_list.c:550
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
```
**Symbols:**

```
ffffffff8121bbf0-ffffffff8121bc62: bpf_lru_push_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bpf_lru_push_free(struct bpf_lru *lru, struct bpf_lru_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff8121eb70)
Location: kernel/bpf/bpf_lru_list.c:551
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
```
**Symbols:**

```
ffffffff8121eb70-ffffffff8121ebe2: bpf_lru_push_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bpf_lru_push_free(struct bpf_lru *lru, struct bpf_lru_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff81222560)
Location: kernel/bpf/bpf_lru_list.c:551
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
```
**Symbols:**

```
ffffffff81222560-ffffffff8122266f: bpf_lru_push_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void bpf_lru_push_free(struct bpf_lru *lru, struct bpf_lru_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (0)
Location: kernel/bpf/bpf_lru_list.c:551
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
```
**Symbols:**

```
ffffffff81cb927a-ffffffff81cb928e: bpf_lru_push_free.cold (STB_LOCAL)
ffffffff8125a1e0-ffffffff8125a344: bpf_lru_push_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void bpf_lru_push_free(struct bpf_lru *lru, struct bpf_lru_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (0)
Location: kernel/bpf/bpf_lru_list.c:551
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
```
**Symbols:**

```
ffffffff81e6a557-ffffffff81e6a56c: bpf_lru_push_free.cold (STB_LOCAL)
ffffffff812a3270-ffffffff812a33e1: bpf_lru_push_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void bpf_lru_push_free(struct bpf_lru *lru, struct bpf_lru_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (0)
Location: kernel/bpf/bpf_lru_list.c:551
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
```
**Symbols:**

```
ffffffff820616aa-ffffffff820616bf: bpf_lru_push_free.cold (STB_LOCAL)
ffffffff81300dd0-ffffffff81300f41: bpf_lru_push_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void bpf_lru_push_free(struct bpf_lru *lru, struct bpf_lru_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (0)
Location: kernel/bpf/bpf_lru_list.c:556
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
```
**Symbols:**

```
ffffffff820e0c45-ffffffff820e0c5a: bpf_lru_push_free.cold (STB_LOCAL)
ffffffff8132f930-ffffffff8132fa9e: bpf_lru_push_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void bpf_lru_push_free(struct bpf_lru *lru, struct bpf_lru_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (0)
Location: kernel/bpf/bpf_lru_list.c:556
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
```
**Symbols:**

```
ffffffff821bd3fa-ffffffff821bd40f: bpf_lru_push_free.cold (STB_LOCAL)
ffffffff81353e50-ffffffff81353fbe: bpf_lru_push_free (STB_GLOBAL)
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
void bpf_lru_push_free(struct bpf_lru *lru, struct bpf_lru_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffff80001027ce80)
Location: kernel/bpf/bpf_lru_list.c:550
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
```
**Symbols:**

```
ffff80001027ce80-ffff80001027d0ac: bpf_lru_push_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bpf_lru_push_free(struct bpf_lru *lru, struct bpf_lru_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (c04ae8cc)
Location: kernel/bpf/bpf_lru_list.c:550
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
```
**Symbols:**

```
c04ae8cc-c04aea90: bpf_lru_push_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bpf_lru_push_free(struct bpf_lru *lru, struct bpf_lru_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (c000000000326910)
Location: kernel/bpf/bpf_lru_list.c:550
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
```
**Symbols:**

```
c000000000326910-c000000000326b1c: bpf_lru_push_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void bpf_lru_push_free(struct bpf_lru *lru, struct bpf_lru_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffe0001b4484)
Location: kernel/bpf/bpf_lru_list.c:550
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
```
**Symbols:**

```
ffffffe0001b4484-ffffffe0001b4598: bpf_lru_push_free (STB_GLOBAL)
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
void bpf_lru_push_free(struct bpf_lru *lru, struct bpf_lru_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811f0400)
Location: kernel/bpf/bpf_lru_list.c:550
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
```
**Symbols:**

```
ffffffff811f0400-ffffffff811f0506: bpf_lru_push_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bpf_lru_push_free(struct bpf_lru *lru, struct bpf_lru_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811e3150)
Location: kernel/bpf/bpf_lru_list.c:550
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
```
**Symbols:**

```
ffffffff811e3150-ffffffff811e3256: bpf_lru_push_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bpf_lru_push_free(struct bpf_lru *lru, struct bpf_lru_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811ee1d0)
Location: kernel/bpf/bpf_lru_list.c:550
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
```
**Symbols:**

```
ffffffff811ee1d0-ffffffff811ee2d6: bpf_lru_push_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bpf_lru_push_free(struct bpf_lru *lru, struct bpf_lru_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811fc6a0)
Location: kernel/bpf/bpf_lru_list.c:550
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
```
**Symbols:**

```
ffffffff811fc6a0-ffffffff811fc7a6: bpf_lru_push_free (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
