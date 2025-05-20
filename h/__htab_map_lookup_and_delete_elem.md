# Function: <code>__htab_map_lookup_and_delete_elem</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __htab_map_lookup_and_delete_elem(struct bpf_map *map, void *key, void *value, bool is_lru_map, bool is_percpu, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81255f20)
Location: kernel/bpf/hashtab.c:1490
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_map_lookup_and_delete_elem
```
**Symbols:**

```
ffffffff81255f20-ffffffff81256242: __htab_map_lookup_and_delete_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __htab_map_lookup_and_delete_elem(struct bpf_map *map, void *key, void *value, bool is_lru_map, bool is_percpu, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8129d7f0)
Location: kernel/bpf/hashtab.c:1519
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_map_lookup_and_delete_elem
```
**Symbols:**

```
ffffffff8129d7f0-ffffffff8129db3c: __htab_map_lookup_and_delete_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __htab_map_lookup_and_delete_elem(struct bpf_map *map, void *key, void *value, bool is_lru_map, bool is_percpu, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff812faa70)
Location: kernel/bpf/hashtab.c:1545
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_map_lookup_and_delete_elem
```
**Symbols:**

```
ffffffff812faa70-ffffffff812faef0: __htab_map_lookup_and_delete_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __htab_map_lookup_and_delete_elem(struct bpf_map *map, void *key, void *value, bool is_lru_map, bool is_percpu, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff813295e0)
Location: kernel/bpf/hashtab.c:1559
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_map_lookup_and_delete_elem
```
**Symbols:**

```
ffffffff813295e0-ffffffff81329b42: __htab_map_lookup_and_delete_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __htab_map_lookup_and_delete_elem(struct bpf_map *map, void *key, void *value, bool is_lru_map, bool is_percpu, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8134e250)
Location: kernel/bpf/hashtab.c:1581
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_map_lookup_and_delete_elem
```
**Symbols:**

```
ffffffff8134e250-ffffffff8134e778: __htab_map_lookup_and_delete_elem (STB_LOCAL)
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
