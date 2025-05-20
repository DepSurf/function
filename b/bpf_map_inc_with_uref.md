# Function: <code>bpf_map_inc_with_uref</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_inc_with_uref(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811ff06c)
Location: kernel/bpf/syscall.c:917
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_do_get
```
**Symbols:**

```
ffffffff811fb3b0-ffffffff811fb3cb: bpf_map_inc_with_uref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_inc_with_uref(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fe3ac)
Location: kernel/bpf/syscall.c:930
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_do_get
```
**Symbols:**

```
ffffffff811fa510-ffffffff811fa52b: bpf_map_inc_with_uref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_inc_with_uref(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fee3c)
Location: kernel/bpf/syscall.c:931
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
```
**Symbols:**

```
ffffffff811fb450-ffffffff811fb46b: bpf_map_inc_with_uref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_inc_with_uref(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81230a8c)
Location: kernel/bpf/syscall.c:958
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
```
**Symbols:**

```
ffffffff8122cb90-ffffffff8122cbab: bpf_map_inc_with_uref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_inc_with_uref(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81273bc0)
Location: kernel/bpf/syscall.c:1192
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/hashtab.c:bpf_iter_init_hash_map
  - kernel/bpf/arraymap.c:bpf_iter_init_array_map
  - net/core/sock_map.c:sock_hash_init_seq_private
  - net/core/sock_map.c:sock_map_init_seq_private
  - net/core/bpf_sk_storage.c:bpf_iter_init_sk_storage_map
```
**Symbols:**

```
ffffffff8126eea0-ffffffff8126eec1: bpf_map_inc_with_uref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_inc_with_uref(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812cacd0)
Location: kernel/bpf/syscall.c:1235
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/hashtab.c:bpf_iter_init_hash_map
  - kernel/bpf/arraymap.c:bpf_iter_init_array_map
  - net/core/sock_map.c:sock_hash_init_seq_private
  - net/core/sock_map.c:sock_map_init_seq_private
  - net/core/bpf_sk_storage.c:bpf_iter_init_sk_storage_map
```
**Symbols:**

```
ffffffff812c4690-ffffffff812c46b1: bpf_map_inc_with_uref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_inc_with_uref(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812f2413)
Location: kernel/bpf/syscall.c:1310
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/hashtab.c:bpf_iter_init_hash_map
  - kernel/bpf/arraymap.c:bpf_iter_init_array_map
  - net/core/sock_map.c:sock_hash_init_seq_private
  - net/core/sock_map.c:sock_map_init_seq_private
  - net/core/bpf_sk_storage.c:bpf_iter_init_sk_storage_map
```
**Symbols:**

```
ffffffff812eb690-ffffffff812eb6b1: bpf_map_inc_with_uref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void bpf_map_inc_with_uref(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff813112b3)
Location: kernel/bpf/syscall.c:1341
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_get_with_uref
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/hashtab.c:bpf_iter_init_hash_map
  - kernel/bpf/arraymap.c:bpf_iter_init_array_map
  - net/core/sock_map.c:sock_hash_init_seq_private
  - net/core/sock_map.c:sock_map_init_seq_private
  - net/core/bpf_sk_storage.c:bpf_iter_init_sk_storage_map
```
**Symbols:**

```
ffffffff81309be0-ffffffff81309c01: bpf_map_inc_with_uref (STB_GLOBAL)
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
