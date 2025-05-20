# Function: <code>sock_map_update_elem_sys</code>

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
<summary>In <code>5.11</code>: ✅</summary>

```c
int sock_map_update_elem_sys(struct bpf_map *map, void *key, void *value, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81a55a10)
Location: net/core/sock_map.c:568
Inline: False
```
**Symbols:**

```
ffffffff81a55a10-ffffffff81a55ba9: sock_map_update_elem_sys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sock_map_update_elem_sys(struct bpf_map *map, void *key, void *value, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81a517d0)
Location: net/core/sock_map.c:562
Inline: False
```
**Symbols:**

```
ffffffff81a517d0-ffffffff81a51948: sock_map_update_elem_sys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int sock_map_update_elem_sys(struct bpf_map *map, void *key, void *value, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock_map.c (0)
Location: net/core/sock_map.c:553
Inline: False
```
**Symbols:**

```
ffffffff81d38b91-ffffffff81d38bb1: sock_map_update_elem_sys.cold (STB_LOCAL)
ffffffff81b0a390-ffffffff81b0a4e8: sock_map_update_elem_sys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int sock_map_update_elem_sys(struct bpf_map *map, void *key, void *value, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock_map.c (0)
Location: net/core/sock_map.c:547
Inline: False
```
**Symbols:**

```
ffffffff81f053eb-ffffffff81f0540b: sock_map_update_elem_sys.cold (STB_LOCAL)
ffffffff81c90700-ffffffff81c908a7: sock_map_update_elem_sys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int sock_map_update_elem_sys(struct bpf_map *map, void *key, void *value, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock_map.c (0)
Location: net/core/sock_map.c:549
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_update_value
```
**Symbols:**

```
ffffffff820ad3f8-ffffffff820ad418: sock_map_update_elem_sys.cold (STB_LOCAL)
ffffffff81e4bb60-ffffffff81e4bd07: sock_map_update_elem_sys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int sock_map_update_elem_sys(struct bpf_map *map, void *key, void *value, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock_map.c (0)
Location: net/core/sock_map.c:545
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_update_value
```
**Symbols:**

```
ffffffff8212e592-ffffffff8212e5ab: sock_map_update_elem_sys.cold (STB_LOCAL)
ffffffff81ea7280-ffffffff81ea7408: sock_map_update_elem_sys (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sock_map_update_elem_sys(struct bpf_map *map, void *key, void *value, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81f69d70)
Location: net/core/sock_map.c:547
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_update_value
```
**Symbols:**

```
ffffffff81f69d70-ffffffff81f69eb2: sock_map_update_elem_sys (STB_GLOBAL)
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
