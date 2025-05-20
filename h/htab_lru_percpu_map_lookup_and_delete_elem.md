# Function: <code>htab_lru_percpu_map_lookup_and_delete_elem</code>

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
int htab_lru_percpu_map_lookup_and_delete_elem(struct bpf_map *map, void *key, void *value, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff812562b0)
Location: kernel/bpf/hashtab.c:1576
Inline: False
```
**Symbols:**

```
ffffffff812562b0-ffffffff812562ce: htab_lru_percpu_map_lookup_and_delete_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int htab_lru_percpu_map_lookup_and_delete_elem(struct bpf_map *map, void *key, void *value, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8129dbd0)
Location: kernel/bpf/hashtab.c:1605
Inline: False
```
**Symbols:**

```
ffffffff8129dbd0-ffffffff8129dc00: htab_lru_percpu_map_lookup_and_delete_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int htab_lru_percpu_map_lookup_and_delete_elem(struct bpf_map *map, void *key, void *value, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff812fafc0)
Location: kernel/bpf/hashtab.c:1632
Inline: False
```
**Symbols:**

```
ffffffff812fafc0-ffffffff812faff0: htab_lru_percpu_map_lookup_and_delete_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int htab_lru_percpu_map_lookup_and_delete_elem(struct bpf_map *map, void *key, void *value, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81329c20)
Location: kernel/bpf/hashtab.c:1645
Inline: False
```
**Symbols:**

```
ffffffff81329c20-ffffffff81329c50: htab_lru_percpu_map_lookup_and_delete_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int htab_lru_percpu_map_lookup_and_delete_elem(struct bpf_map *map, void *key, void *value, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8134e850)
Location: kernel/bpf/hashtab.c:1667
Inline: False
```
**Symbols:**

```
ffffffff8134e850-ffffffff8134e880: htab_lru_percpu_map_lookup_and_delete_elem (STB_LOCAL)
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
