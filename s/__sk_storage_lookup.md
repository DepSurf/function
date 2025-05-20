# Function: <code>__sk_storage_lookup</code>

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
struct bpf_sk_storage_data *__sk_storage_lookup(struct bpf_sk_storage *sk_storage, struct bpf_sk_storage_map *smap, bool cacheit_lockit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81952a00)
Location: net/core/bpf_sk_storage.c:259
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem
  - net/core/bpf_sk_storage.c:sk_storage_delete
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:sk_storage_update
```
**Symbols:**

```
ffffffff81952a00-ffffffff81952acc: __sk_storage_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct bpf_sk_storage_data *__sk_storage_lookup(struct bpf_sk_storage *sk_storage, struct bpf_sk_storage_map *smap, bool cacheit_lockit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81988d50)
Location: net/core/bpf_sk_storage.c:261
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem
  - net/core/bpf_sk_storage.c:sk_storage_delete
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:sk_storage_update
```
**Symbols:**

```
ffffffff81988d50-ffffffff81988e1c: __sk_storage_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct bpf_sk_storage_data *__sk_storage_lookup(struct bpf_sk_storage *sk_storage, struct bpf_sk_storage_map *smap, bool cacheit_lockit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81a60a10)
Location: net/core/bpf_sk_storage.c:262
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:sk_storage_update
```
**Symbols:**

```
ffffffff81a60a10-ffffffff81a60abd: __sk_storage_lookup (STB_LOCAL)
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
struct bpf_sk_storage_data *__sk_storage_lookup(struct bpf_sk_storage *sk_storage, struct bpf_sk_storage_map *smap, bool cacheit_lockit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffff800010c31388)
Location: net/core/bpf_sk_storage.c:261
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem
  - net/core/bpf_sk_storage.c:sk_storage_delete
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:sk_storage_update
```
**Symbols:**

```
ffff800010c31388-ffff800010c314dc: __sk_storage_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct bpf_sk_storage_data *__sk_storage_lookup(struct bpf_sk_storage *sk_storage, struct bpf_sk_storage_map *smap, bool cacheit_lockit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (c0d47e0c)
Location: net/core/bpf_sk_storage.c:261
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem
  - net/core/bpf_sk_storage.c:sk_storage_delete
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:sk_storage_update
```
**Symbols:**

```
c0d47e0c-c0d47edc: __sk_storage_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct bpf_sk_storage_data *__sk_storage_lookup(struct bpf_sk_storage *sk_storage, struct bpf_sk_storage_map *smap, bool cacheit_lockit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (c000000000d29f40)
Location: net/core/bpf_sk_storage.c:261
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem
  - net/core/bpf_sk_storage.c:sk_storage_delete
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:sk_storage_update
```
**Symbols:**

```
c000000000d29f40-c000000000d2a090: __sk_storage_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct bpf_sk_storage_data *__sk_storage_lookup(struct bpf_sk_storage *sk_storage, struct bpf_sk_storage_map *smap, bool cacheit_lockit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffe0007a6e86)
Location: net/core/bpf_sk_storage.c:261
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem
  - net/core/bpf_sk_storage.c:sk_storage_delete
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:sk_storage_update
```
**Symbols:**

```
ffffffe0007a6e86-ffffffe0007a6f2c: __sk_storage_lookup (STB_LOCAL)
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
struct bpf_sk_storage_data *__sk_storage_lookup(struct bpf_sk_storage *sk_storage, struct bpf_sk_storage_map *smap, bool cacheit_lockit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81928bc0)
Location: net/core/bpf_sk_storage.c:261
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem
  - net/core/bpf_sk_storage.c:sk_storage_delete
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:sk_storage_update
```
**Symbols:**

```
ffffffff81928bc0-ffffffff81928c8c: __sk_storage_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct bpf_sk_storage_data *__sk_storage_lookup(struct bpf_sk_storage *sk_storage, struct bpf_sk_storage_map *smap, bool cacheit_lockit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff818e2970)
Location: net/core/bpf_sk_storage.c:261
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem
  - net/core/bpf_sk_storage.c:sk_storage_delete
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:sk_storage_update
```
**Symbols:**

```
ffffffff818e2970-ffffffff818e2a3c: __sk_storage_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct bpf_sk_storage_data *__sk_storage_lookup(struct bpf_sk_storage *sk_storage, struct bpf_sk_storage_map *smap, bool cacheit_lockit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81979d50)
Location: net/core/bpf_sk_storage.c:261
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem
  - net/core/bpf_sk_storage.c:sk_storage_delete
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:sk_storage_update
```
**Symbols:**

```
ffffffff81979d50-ffffffff81979e1c: __sk_storage_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct bpf_sk_storage_data *__sk_storage_lookup(struct bpf_sk_storage *sk_storage, struct bpf_sk_storage_map *smap, bool cacheit_lockit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff8199c280)
Location: net/core/bpf_sk_storage.c:261
Inline: False
Direct callers:
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem
  - net/core/bpf_sk_storage.c:sk_storage_delete
  - net/core/bpf_sk_storage.c:sk_storage_update
  - net/core/bpf_sk_storage.c:sk_storage_update
```
**Symbols:**

```
ffffffff8199c280-ffffffff8199c34c: __sk_storage_lookup (STB_LOCAL)
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
