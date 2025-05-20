# Function: <code>xsk_map_try_sock_delete</code>

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
<summary>In <code>5.4</code>: ✅</summary>

```c
void xsk_map_try_sock_delete(struct xsk_map *map, struct xdp_sock *xs, struct xdp_sock **map_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (ffffffff81201650)
Location: kernel/bpf/xskmap.c:299
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffffffff81201650-ffffffff812016b0: xsk_map_try_sock_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xsk_map_try_sock_delete(struct xsk_map *map, struct xdp_sock *xs, struct xdp_sock **map_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xskmap.c (ffffffff81ba93e0)
Location: net/xdp/xskmap.c:246
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_delete_from_maps
```
**Symbols:**

```
ffffffff81ba93e0-ffffffff81ba943a: xsk_map_try_sock_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xsk_map_try_sock_delete(struct xsk_map *map, struct xdp_sock *xs, struct xdp_sock **map_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xskmap.c (ffffffff81bb8bb0)
Location: net/xdp/xskmap.c:218
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffffffff81bb8bb0-ffffffff81bb8c0a: xsk_map_try_sock_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xsk_map_try_sock_delete(struct xsk_map *map, struct xdp_sock *xs, struct xdp_sock **map_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xskmap.c (ffffffff81ba7dd0)
Location: net/xdp/xskmap.c:232
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffffffff81ba7dd0-ffffffff81ba7e2a: xsk_map_try_sock_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xsk_map_try_sock_delete(struct xsk_map *map, struct xdp_sock *xs, struct xdp_sock **map_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xskmap.c (ffffffff81c75a60)
Location: net/xdp/xskmap.c:238
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffffffff81c75a60-ffffffff81c75aba: xsk_map_try_sock_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xsk_map_try_sock_delete(struct xsk_map *map, struct xdp_sock *xs, struct xdp_sock **map_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xskmap.c (ffffffff81e19cb0)
Location: net/xdp/xskmap.c:240
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffffffff81e19cb0-ffffffff81e19d1e: xsk_map_try_sock_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xsk_map_try_sock_delete(struct xsk_map *map, struct xdp_sock *xs, struct xdp_sock **map_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xskmap.c (ffffffff81ff1080)
Location: net/xdp/xskmap.c:240
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffffffff81ff1080-ffffffff81ff10ee: xsk_map_try_sock_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xsk_map_try_sock_delete(struct xsk_map *map, struct xdp_sock *xs, struct xdp_sock **map_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xskmap.c (ffffffff8206d2b0)
Location: net/xdp/xskmap.c:248
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffffffff8206d2b0-ffffffff8206d31e: xsk_map_try_sock_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xsk_map_try_sock_delete(struct xsk_map *map, struct xdp_sock *xs, struct xdp_sock **map_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xskmap.c (ffffffff82141150)
Location: net/xdp/xskmap.c:248
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffffffff82141150-ffffffff821411be: xsk_map_try_sock_delete (STB_GLOBAL)
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
void xsk_map_try_sock_delete(struct xsk_map *map, struct xdp_sock *xs, struct xdp_sock **map_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (ffff8000102895f0)
Location: kernel/bpf/xskmap.c:299
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffff8000102895f0-ffff8000102896c4: xsk_map_try_sock_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void xsk_map_try_sock_delete(struct xsk_map *map, struct xdp_sock *xs, struct xdp_sock **map_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (c04b8f94)
Location: kernel/bpf/xskmap.c:299
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
c04b8f94-c04b8fec: xsk_map_try_sock_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void xsk_map_try_sock_delete(struct xsk_map *map, struct xdp_sock *xs, struct xdp_sock **map_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (c000000000334cc0)
Location: kernel/bpf/xskmap.c:299
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
c000000000334cc0-c000000000334d7c: xsk_map_try_sock_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void xsk_map_try_sock_delete(struct xsk_map *map, struct xdp_sock *xs, struct xdp_sock **map_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (ffffffe0001bd9cc)
Location: kernel/bpf/xskmap.c:299
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffffffe0001bd9cc-ffffffe0001bda2a: xsk_map_try_sock_delete (STB_GLOBAL)
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
void xsk_map_try_sock_delete(struct xsk_map *map, struct xdp_sock *xs, struct xdp_sock **map_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (ffffffff811f9c70)
Location: kernel/bpf/xskmap.c:299
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffffffff811f9c70-ffffffff811f9cd0: xsk_map_try_sock_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void xsk_map_try_sock_delete(struct xsk_map *map, struct xdp_sock *xs, struct xdp_sock **map_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (ffffffff811ec9c0)
Location: kernel/bpf/xskmap.c:299
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffffffff811ec9c0-ffffffff811eca20: xsk_map_try_sock_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void xsk_map_try_sock_delete(struct xsk_map *map, struct xdp_sock *xs, struct xdp_sock **map_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (ffffffff811f7a40)
Location: kernel/bpf/xskmap.c:299
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffffffff811f7a40-ffffffff811f7aa0: xsk_map_try_sock_delete (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void xsk_map_try_sock_delete(struct xsk_map *map, struct xdp_sock *xs, struct xdp_sock **map_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/xskmap.c (ffffffff81205fc0)
Location: kernel/bpf/xskmap.c:299
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffffffff81205fc0-ffffffff81206020: xsk_map_try_sock_delete (STB_GLOBAL)
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
