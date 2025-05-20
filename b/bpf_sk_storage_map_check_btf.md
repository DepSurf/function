# Function: <code>bpf_sk_storage_map_check_btf</code>

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
int bpf_sk_storage_map_check_btf(const struct bpf_map *map, const struct btf *btf, const struct btf_type *key_type, const struct btf_type *value_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81952ae0)
Location: net/core/bpf_sk_storage.c:674
Inline: False
```
**Symbols:**

```
ffffffff81952ae0-ffffffff81952b15: bpf_sk_storage_map_check_btf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bpf_sk_storage_map_check_btf(const struct bpf_map *map, const struct btf *btf, const struct btf_type *key_type, const struct btf_type *value_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81988e30)
Location: net/core/bpf_sk_storage.c:684
Inline: False
```
**Symbols:**

```
ffffffff81988e30-ffffffff81988e65: bpf_sk_storage_map_check_btf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpf_sk_storage_map_check_btf(const struct bpf_map *map, const struct btf *btf, const struct btf_type *key_type, const struct btf_type *value_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81a60ad0)
Location: net/core/bpf_sk_storage.c:688
Inline: False
```
**Symbols:**

```
ffffffff81a60ad0-ffffffff81a60b05: bpf_sk_storage_map_check_btf (STB_LOCAL)
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
int bpf_sk_storage_map_check_btf(const struct bpf_map *map, const struct btf *btf, const struct btf_type *key_type, const struct btf_type *value_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffff800010c30eb0)
Location: net/core/bpf_sk_storage.c:684
Inline: False
```
**Symbols:**

```
ffff800010c30eb0-ffff800010c30f08: bpf_sk_storage_map_check_btf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bpf_sk_storage_map_check_btf(const struct bpf_map *map, const struct btf *btf, const struct btf_type *key_type, const struct btf_type *value_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (c0d47efc)
Location: net/core/bpf_sk_storage.c:684
Inline: False
```
**Symbols:**

```
c0d47efc-c0d47f48: bpf_sk_storage_map_check_btf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bpf_sk_storage_map_check_btf(const struct bpf_map *map, const struct btf *btf, const struct btf_type *key_type, const struct btf_type *value_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (c000000000d2a0a0)
Location: net/core/bpf_sk_storage.c:684
Inline: False
```
**Symbols:**

```
c000000000d2a0a0-c000000000d2a0e8: bpf_sk_storage_map_check_btf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bpf_sk_storage_map_check_btf(const struct bpf_map *map, const struct btf *btf, const struct btf_type *key_type, const struct btf_type *value_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffe0007a6f4a)
Location: net/core/bpf_sk_storage.c:684
Inline: False
```
**Symbols:**

```
ffffffe0007a6f4a-ffffffe0007a6f94: bpf_sk_storage_map_check_btf (STB_LOCAL)
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
int bpf_sk_storage_map_check_btf(const struct bpf_map *map, const struct btf *btf, const struct btf_type *key_type, const struct btf_type *value_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81928ca0)
Location: net/core/bpf_sk_storage.c:684
Inline: False
```
**Symbols:**

```
ffffffff81928ca0-ffffffff81928cd5: bpf_sk_storage_map_check_btf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bpf_sk_storage_map_check_btf(const struct bpf_map *map, const struct btf *btf, const struct btf_type *key_type, const struct btf_type *value_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff818e2a50)
Location: net/core/bpf_sk_storage.c:684
Inline: False
```
**Symbols:**

```
ffffffff818e2a50-ffffffff818e2a85: bpf_sk_storage_map_check_btf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bpf_sk_storage_map_check_btf(const struct bpf_map *map, const struct btf *btf, const struct btf_type *key_type, const struct btf_type *value_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81979e30)
Location: net/core/bpf_sk_storage.c:684
Inline: False
```
**Symbols:**

```
ffffffff81979e30-ffffffff81979e65: bpf_sk_storage_map_check_btf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bpf_sk_storage_map_check_btf(const struct bpf_map *map, const struct btf *btf, const struct btf_type *key_type, const struct btf_type *value_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff8199c360)
Location: net/core/bpf_sk_storage.c:684
Inline: False
```
**Symbols:**

```
ffffffff8199c360-ffffffff8199c395: bpf_sk_storage_map_check_btf (STB_LOCAL)
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
