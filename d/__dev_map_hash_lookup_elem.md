# Function: <code>__dev_map_hash_lookup_elem</code>

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
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct bpf_dtab_netdev *__dev_map_hash_lookup_elem(struct bpf_map *map, u32 key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff811ff5ab)
Location: kernel/bpf/devmap.c:290
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
  - kernel/bpf/devmap.c:dev_map_hash_lookup_elem
  - kernel/bpf/devmap.c:dev_map_hash_get_next_key
Direct callers:
  - net/core/filter.c:bpf_xdp_redirect_map
```
**Symbols:**

```
ffffffff811ffc30-ffffffff811ffc78: __dev_map_hash_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct bpf_dtab_netdev *__dev_map_hash_lookup_elem(struct bpf_map *map, u32 key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff812273d1)
Location: kernel/bpf/devmap.c:275
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
  - kernel/bpf/devmap.c:dev_map_hash_lookup_elem
  - kernel/bpf/devmap.c:dev_map_hash_get_next_key
Direct callers:
  - net/core/filter.c:bpf_xdp_redirect_map
```
**Symbols:**

```
ffffffff812275c0-ffffffff812275ff: __dev_map_hash_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct bpf_dtab_netdev *__dev_map_hash_lookup_elem(struct bpf_map *map, u32 key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff8122df21)
Location: kernel/bpf/devmap.c:261
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
  - kernel/bpf/devmap.c:dev_map_hash_lookup_elem
  - kernel/bpf/devmap.c:dev_map_hash_get_next_key
Direct callers:
  - net/core/filter.c:bpf_xdp_redirect_map
```
**Symbols:**

```
ffffffff8122e110-ffffffff8122e14f: __dev_map_hash_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff81232e01)
Location: kernel/bpf/devmap.c:260
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_hash_map_redirect
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
  - kernel/bpf/devmap.c:dev_map_hash_lookup_elem
  - kernel/bpf/devmap.c:dev_map_hash_get_next_key
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff8126c3c8)
Location: kernel/bpf/devmap.c:266
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_hash_map_redirect
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
  - kernel/bpf/devmap.c:dev_map_hash_lookup_elem
  - kernel/bpf/devmap.c:dev_map_hash_get_next_key
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff812bb0ee)
Location: kernel/bpf/devmap.c:267
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_hash_map_redirect
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
  - kernel/bpf/devmap.c:dev_map_hash_lookup_elem
  - kernel/bpf/devmap.c:dev_map_hash_get_next_key
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff8131e537)
Location: kernel/bpf/devmap.c:267
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_hash_map_redirect
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
  - kernel/bpf/devmap.c:dev_map_hash_lookup_elem
  - kernel/bpf/devmap.c:dev_map_hash_get_next_key
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff8134e33b)
Location: kernel/bpf/devmap.c:264
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_hash_map_redirect
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
  - kernel/bpf/devmap.c:dev_map_hash_lookup_elem
  - kernel/bpf/devmap.c:dev_map_hash_get_next_key
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff8137583b)
Location: kernel/bpf/devmap.c:263
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_hash_map_redirect
  - kernel/bpf/devmap.c:__dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
  - kernel/bpf/devmap.c:dev_map_hash_lookup_elem
  - kernel/bpf/devmap.c:dev_map_hash_get_next_key
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct bpf_dtab_netdev *__dev_map_hash_lookup_elem(struct bpf_map *map, u32 key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffff80001028737c)
Location: kernel/bpf/devmap.c:290
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
  - kernel/bpf/devmap.c:dev_map_hash_lookup_elem
  - kernel/bpf/devmap.c:dev_map_hash_get_next_key
Direct callers:
  - net/core/filter.c:bpf_xdp_redirect_map
```
**Symbols:**

```
ffff800010287558-ffff8000102875bc: __dev_map_hash_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct bpf_dtab_netdev *__dev_map_hash_lookup_elem(struct bpf_map *map, u32 key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (c04b6bbc)
Location: kernel/bpf/devmap.c:290
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
  - kernel/bpf/devmap.c:dev_map_hash_lookup_elem
  - kernel/bpf/devmap.c:dev_map_hash_get_next_key
Direct callers:
  - net/core/filter.c:bpf_xdp_redirect_map
```
**Symbols:**

```
c04b750c-c04b7568: __dev_map_hash_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct bpf_dtab_netdev *__dev_map_hash_lookup_elem(struct bpf_map *map, u32 key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (c000000000331bfc)
Location: kernel/bpf/devmap.c:290
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
  - kernel/bpf/devmap.c:dev_map_hash_lookup_elem
  - kernel/bpf/devmap.c:dev_map_hash_get_next_key
Direct callers:
  - net/core/filter.c:bpf_xdp_redirect_map
```
**Symbols:**

```
c000000000332640-c0000000003326bc: __dev_map_hash_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct bpf_dtab_netdev *__dev_map_hash_lookup_elem(struct bpf_map *map, u32 key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffe0001bb89a)
Location: kernel/bpf/devmap.c:290
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
  - kernel/bpf/devmap.c:dev_map_hash_lookup_elem
  - kernel/bpf/devmap.c:dev_map_hash_get_next_key
Direct callers:
  - net/core/filter.c:bpf_xdp_redirect_map
```
**Symbols:**

```
ffffffe0001bc042-ffffffe0001bc092: __dev_map_hash_lookup_elem (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct bpf_dtab_netdev *__dev_map_hash_lookup_elem(struct bpf_map *map, u32 key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff811f7bcb)
Location: kernel/bpf/devmap.c:290
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
  - kernel/bpf/devmap.c:dev_map_hash_lookup_elem
  - kernel/bpf/devmap.c:dev_map_hash_get_next_key
Direct callers:
  - net/core/filter.c:bpf_xdp_redirect_map
```
**Symbols:**

```
ffffffff811f8250-ffffffff811f8298: __dev_map_hash_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct bpf_dtab_netdev *__dev_map_hash_lookup_elem(struct bpf_map *map, u32 key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff811ea91b)
Location: kernel/bpf/devmap.c:290
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
  - kernel/bpf/devmap.c:dev_map_hash_lookup_elem
  - kernel/bpf/devmap.c:dev_map_hash_get_next_key
Direct callers:
  - net/core/filter.c:bpf_xdp_redirect_map
```
**Symbols:**

```
ffffffff811eafa0-ffffffff811eafe8: __dev_map_hash_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct bpf_dtab_netdev *__dev_map_hash_lookup_elem(struct bpf_map *map, u32 key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff811f599b)
Location: kernel/bpf/devmap.c:290
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
  - kernel/bpf/devmap.c:dev_map_hash_lookup_elem
  - kernel/bpf/devmap.c:dev_map_hash_get_next_key
Direct callers:
  - net/core/filter.c:bpf_xdp_redirect_map
```
**Symbols:**

```
ffffffff811f6020-ffffffff811f6068: __dev_map_hash_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct bpf_dtab_netdev *__dev_map_hash_lookup_elem(struct bpf_map *map, u32 key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff81203efb)
Location: kernel/bpf/devmap.c:290
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_map_hash_update_elem
  - kernel/bpf/devmap.c:dev_map_hash_delete_elem
  - kernel/bpf/devmap.c:dev_map_hash_lookup_elem
  - kernel/bpf/devmap.c:dev_map_hash_get_next_key
Direct callers:
  - net/core/filter.c:bpf_xdp_redirect_map
```
**Symbols:**

```
ffffffff81204580-ffffffff812045c8: __dev_map_hash_lookup_elem (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
