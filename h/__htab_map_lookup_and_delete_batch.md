# Function: <code>__htab_map_lookup_and_delete_batch</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __htab_map_lookup_and_delete_batch(struct bpf_map *map, const union bpf_attr *attr, union bpf_attr *uattr, bool do_delete, bool is_lru_map, bool is_percpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81218720)
Location: kernel/bpf/hashtab.c:1342
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_batch
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_batch
  - kernel/bpf/hashtab.c:htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:htab_map_lookup_batch
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_batch
```
**Symbols:**

```
ffffffff81218720-ffffffff81218e78: __htab_map_lookup_and_delete_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __htab_map_lookup_and_delete_batch(struct bpf_map *map, const union bpf_attr *attr, union bpf_attr *uattr, bool do_delete, bool is_lru_map, bool is_percpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8121aa10)
Location: kernel/bpf/hashtab.c:1405
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_batch
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_batch
  - kernel/bpf/hashtab.c:htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:htab_map_lookup_batch
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_batch
```
**Symbols:**

```
ffffffff8121aa10-ffffffff8121b250: __htab_map_lookup_and_delete_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __htab_map_lookup_and_delete_batch(struct bpf_map *map, const union bpf_attr *attr, union bpf_attr *uattr, bool do_delete, bool is_lru_map, bool is_percpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8121e6a0)
Location: kernel/bpf/hashtab.c:1405
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_batch
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_batch
  - kernel/bpf/hashtab.c:htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:htab_map_lookup_batch
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_batch
```
**Symbols:**

```
ffffffff8121e6a0-ffffffff8121eee6: __htab_map_lookup_and_delete_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __htab_map_lookup_and_delete_batch(struct bpf_map *map, const union bpf_attr *attr, union bpf_attr *uattr, bool do_delete, bool is_lru_map, bool is_percpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81254c90)
Location: kernel/bpf/hashtab.c:1585
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_batch
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_batch
  - kernel/bpf/hashtab.c:htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:htab_map_lookup_batch
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_batch
```
**Symbols:**

```
ffffffff81254c90-ffffffff81255518: __htab_map_lookup_and_delete_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __htab_map_lookup_and_delete_batch(struct bpf_map *map, const union bpf_attr *attr, union bpf_attr *uattr, bool do_delete, bool is_lru_map, bool is_percpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8129dec0)
Location: kernel/bpf/hashtab.c:1614
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_batch
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_batch
  - kernel/bpf/hashtab.c:htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:htab_map_lookup_batch
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_batch
```
**Symbols:**

```
ffffffff8129dec0-ffffffff8129e84f: __htab_map_lookup_and_delete_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __htab_map_lookup_and_delete_batch(struct bpf_map *map, const union bpf_attr *attr, union bpf_attr *uattr, bool do_delete, bool is_lru_map, bool is_percpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff812fbb10)
Location: kernel/bpf/hashtab.c:1641
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_batch
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_batch
  - kernel/bpf/hashtab.c:htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:htab_map_lookup_batch
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_batch
```
**Symbols:**

```
ffffffff812fbb10-ffffffff812fc5d7: __htab_map_lookup_and_delete_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __htab_map_lookup_and_delete_batch(struct bpf_map *map, const union bpf_attr *attr, union bpf_attr *uattr, bool do_delete, bool is_lru_map, bool is_percpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8132a3c0)
Location: kernel/bpf/hashtab.c:1654
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_batch
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_batch
  - kernel/bpf/hashtab.c:htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:htab_map_lookup_batch
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_batch
```
**Symbols:**

```
ffffffff8132a3c0-ffffffff8132b15f: __htab_map_lookup_and_delete_batch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __htab_map_lookup_and_delete_batch(struct bpf_map *map, const union bpf_attr *attr, union bpf_attr *uattr, bool do_delete, bool is_lru_map, bool is_percpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8134e890)
Location: kernel/bpf/hashtab.c:1676
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:htab_lru_map_lookup_batch
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:htab_lru_percpu_map_lookup_batch
  - kernel/bpf/hashtab.c:htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:htab_map_lookup_batch
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:htab_percpu_map_lookup_batch
```
**Symbols:**

```
ffffffff8134e890-ffffffff8134f603: __htab_map_lookup_and_delete_batch (STB_LOCAL)
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
