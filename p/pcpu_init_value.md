# Function: <code>pcpu_init_value</code>

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
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8121b4f7)
Location: kernel/bpf/hashtab.c:845
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
Direct callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
**Symbols:**

```
ffffffff81219b50-ffffffff81219c10: pcpu_init_value.part.0.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void pcpu_init_value(struct bpf_htab *htab, void *pptr, void *value, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8121d600)
Location: kernel/bpf/hashtab.c:845
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
**Symbols:**

```
ffffffff8121d600-ffffffff8121d6e2: pcpu_init_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void pcpu_init_value(struct bpf_htab *htab, void *pptr, void *value, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81254600)
Location: kernel/bpf/hashtab.c:887
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
**Symbols:**

```
ffffffff81254600-ffffffff8125473a: pcpu_init_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void pcpu_init_value(struct bpf_htab *htab, void *pptr, void *value, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8129cd10)
Location: kernel/bpf/hashtab.c:906
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
**Symbols:**

```
ffffffff8129cd10-ffffffff8129ce5b: pcpu_init_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void pcpu_init_value(struct bpf_htab *htab, void *pptr, void *value, bool onallcpus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff812f97b0)
Location: kernel/bpf/hashtab.c:934
Inline: True
Direct callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
**Symbols:**

```
ffffffff812f97b0-ffffffff812f98f5: pcpu_init_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81328d93)
Location: kernel/bpf/hashtab.c:948
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
Direct callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
**Symbols:**

```
ffffffff81327b40-ffffffff81327cf1: pcpu_init_value.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8134dbb8)
Location: kernel/bpf/hashtab.c:965
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
Direct callers:
  - kernel/bpf/hashtab.c:__htab_lru_percpu_map_update_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
  - kernel/bpf/hashtab.c:alloc_htab_elem
```
**Symbols:**

```
ffffffff8134c200-ffffffff8134c3b1: pcpu_init_value.part.0 (STB_LOCAL)
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
</ul>
