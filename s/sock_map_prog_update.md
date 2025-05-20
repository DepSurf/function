# Function: <code>sock_map_prog_update</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sock_map_prog_update(struct bpf_map *map, struct bpf_prog *prog, u32 which);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff818f32a0)
Location: net/core/sock_map.c:966
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_map_get_from_fd
```
**Symbols:**

```
ffffffff818f32a0-ffffffff818f3315: sock_map_prog_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sock_map_prog_update(struct bpf_map *map, struct bpf_prog *prog, u32 which);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81945770)
Location: net/core/sock_map.c:973
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_map_get_from_fd
```
**Symbols:**

```
ffffffff81945770-ffffffff819457eb: sock_map_prog_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sock_map_prog_update(struct bpf_map *map, struct bpf_prog *prog, u32 which);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff8197a790)
Location: net/core/sock_map.c:993
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_map_get_from_fd
```
**Symbols:**

```
ffffffff8197a790-ffffffff8197a80b: sock_map_prog_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sock_map_prog_update(struct bpf_map *map, struct bpf_prog *prog, struct bpf_prog *old, u32 which);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81a4fba0)
Location: net/core/sock_map.c:1243
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_map_prog_detach
  - net/core/sock_map.c:sock_map_get_from_fd
```
**Symbols:**

```
ffffffff81a4fba0-ffffffff81a4fc38: sock_map_prog_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sock_map_prog_update(struct bpf_map *map, struct bpf_prog *prog, struct bpf_prog *old, u32 which);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81a55bb0)
Location: net/core/sock_map.c:1451
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_map_prog_detach
  - net/core/sock_map.c:sock_map_get_from_fd
```
**Symbols:**

```
ffffffff81a55bb0-ffffffff81a55c48: sock_map_prog_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sock_map_prog_update(struct bpf_map *map, struct bpf_prog *prog, struct bpf_prog *old, u32 which);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81a4f360)
Location: net/core/sock_map.c:1434
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_map_prog_detach
  - net/core/sock_map.c:sock_map_get_from_fd
```
**Symbols:**

```
ffffffff81a4f360-ffffffff81a4f42e: sock_map_prog_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sock_map_prog_update(struct bpf_map *map, struct bpf_prog *prog, struct bpf_prog *old, u32 which);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81b07f40)
Location: net/core/sock_map.c:1425
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_map_prog_detach
  - net/core/sock_map.c:sock_map_get_from_fd
```
**Symbols:**

```
ffffffff81b07f40-ffffffff81b0800e: sock_map_prog_update (STB_LOCAL)
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
In net/core/sock_map.c (ffffffff81c9066e)
Location: net/core/sock_map.c:1469
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_prog_detach
  - net/core/sock_map.c:sock_map_get_from_fd
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
In net/core/sock_map.c (ffffffff81e4babe)
Location: net/core/sock_map.c:1471
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_prog_detach
  - net/core/sock_map.c:sock_map_get_from_fd
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
In net/core/sock_map.c (ffffffff81ea71de)
Location: net/core/sock_map.c:1485
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_prog_detach
  - net/core/sock_map.c:sock_map_get_from_fd
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
In net/core/sock_map.c (ffffffff81f69cce)
Location: net/core/sock_map.c:1491
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_prog_detach
  - net/core/sock_map.c:sock_map_get_from_fd
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
int sock_map_prog_update(struct bpf_map *map, struct bpf_prog *prog, u32 which);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffff800010c21aa0)
Location: net/core/sock_map.c:993
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_map_get_from_fd
```
**Symbols:**

```
ffff800010c21aa0-ffff800010c21b8c: sock_map_prog_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sock_map_prog_update(struct bpf_map *map, struct bpf_prog *prog, u32 which);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (c0d390e8)
Location: net/core/sock_map.c:993
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_map_get_from_fd
```
**Symbols:**

```
c0d390e8-c0d39188: sock_map_prog_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sock_map_prog_update(struct bpf_map *map, struct bpf_prog *prog, u32 which);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (c000000000d14070)
Location: net/core/sock_map.c:993
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_map_get_from_fd
```
**Symbols:**

```
c000000000d14070-c000000000d14188: sock_map_prog_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sock_map_prog_update(struct bpf_map *map, struct bpf_prog *prog, u32 which);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffe00079a8e8)
Location: net/core/sock_map.c:993
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_map_get_from_fd
```
**Symbols:**

```
ffffffe00079a8e8-ffffffe00079a96e: sock_map_prog_update (STB_GLOBAL)
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
int sock_map_prog_update(struct bpf_map *map, struct bpf_prog *prog, u32 which);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff8191a600)
Location: net/core/sock_map.c:993
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_map_get_from_fd
```
**Symbols:**

```
ffffffff8191a600-ffffffff8191a67b: sock_map_prog_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sock_map_prog_update(struct bpf_map *map, struct bpf_prog *prog, u32 which);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff818d43b0)
Location: net/core/sock_map.c:993
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_map_get_from_fd
```
**Symbols:**

```
ffffffff818d43b0-ffffffff818d442b: sock_map_prog_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sock_map_prog_update(struct bpf_map *map, struct bpf_prog *prog, u32 which);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff8196b790)
Location: net/core/sock_map.c:993
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_map_get_from_fd
```
**Symbols:**

```
ffffffff8196b790-ffffffff8196b80b: sock_map_prog_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sock_map_prog_update(struct bpf_map *map, struct bpf_prog *prog, u32 which);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff8198dc00)
Location: net/core/sock_map.c:993
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_map_get_from_fd
```
**Symbols:**

```
ffffffff8198dc00-ffffffff8198dc7b: sock_map_prog_update (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bpf_prog *old</code>
</li>
<li>
<b>Param reordered. </b>
<code>map, prog, which</code> ➡️ <code>map, prog, old, which</code>
</li>
</ul>
</details>
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
