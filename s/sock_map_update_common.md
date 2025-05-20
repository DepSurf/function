# Function: <code>sock_map_update_common</code>

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
int sock_map_update_common(struct bpf_map *map, u32 idx, struct sock *sk, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff818f2200)
Location: net/core/sock_map.c:332
Inline: False
Direct callers:
  - net/core/sock_map.c:bpf_sock_map_update
  - net/core/sock_map.c:sock_map_update_elem
```
**Symbols:**

```
ffffffff818f2200-ffffffff818f242f: sock_map_update_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sock_map_update_common(struct bpf_map *map, u32 idx, struct sock *sk, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81944c50)
Location: net/core/sock_map.c:333
Inline: False
Direct callers:
  - net/core/sock_map.c:bpf_sock_map_update
  - net/core/sock_map.c:sock_map_update_elem
```
**Symbols:**

```
ffffffff81944c50-ffffffff81944ebb: sock_map_update_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sock_map_update_common(struct bpf_map *map, u32 idx, struct sock *sk, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81979c60)
Location: net/core/sock_map.c:339
Inline: False
Direct callers:
  - net/core/sock_map.c:bpf_sock_map_update
  - net/core/sock_map.c:sock_map_update_elem
```
**Symbols:**

```
ffffffff81979c60-ffffffff81979ecd: sock_map_update_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sock_map_update_common(struct bpf_map *map, u32 idx, struct sock *sk, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81a4f1e0)
Location: net/core/sock_map.c:467
Inline: False
Direct callers:
  - net/core/sock_map.c:bpf_sock_map_update
  - net/core/sock_map.c:sock_map_update_elem
```
**Symbols:**

```
ffffffff81a4f1e0-ffffffff81a4f4a6: sock_map_update_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sock_map_update_common(struct bpf_map *map, u32 idx, struct sock *sk, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81a55220)
Location: net/core/sock_map.c:468
Inline: False
Direct callers:
  - net/core/sock_map.c:bpf_sock_map_update
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/sock_map.c:sock_map_update_elem_sys
```
**Symbols:**

```
ffffffff81a55220-ffffffff81a554ba: sock_map_update_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sock_map_update_common(struct bpf_map *map, u32 idx, struct sock *sk, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81a510c0)
Location: net/core/sock_map.c:466
Inline: False
Direct callers:
  - net/core/sock_map.c:bpf_sock_map_update
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/sock_map.c:sock_map_update_elem_sys
```
**Symbols:**

```
ffffffff81a510c0-ffffffff81a512f4: sock_map_update_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sock_map_update_common(struct bpf_map *map, u32 idx, struct sock *sk, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81b09ac0)
Location: net/core/sock_map.c:466
Inline: False
Direct callers:
  - net/core/sock_map.c:bpf_sock_map_update
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/sock_map.c:sock_map_update_elem_sys
```
**Symbols:**

```
ffffffff81b09ac0-ffffffff81b09cf4: sock_map_update_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sock_map_update_common(struct bpf_map *map, u32 idx, struct sock *sk, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81c8fca0)
Location: net/core/sock_map.c:466
Inline: False
Direct callers:
  - net/core/sock_map.c:bpf_sock_map_update
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/sock_map.c:sock_map_update_elem_sys
```
**Symbols:**

```
ffffffff81c8fca0-ffffffff81c8ff3f: sock_map_update_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sock_map_update_common(struct bpf_map *map, u32 idx, struct sock *sk, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81e4b100)
Location: net/core/sock_map.c:468
Inline: False
Direct callers:
  - net/core/sock_map.c:bpf_sock_map_update
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/sock_map.c:sock_map_update_elem_sys
```
**Symbols:**

```
ffffffff81e4b100-ffffffff81e4b39f: sock_map_update_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sock_map_update_common(struct bpf_map *map, u32 idx, struct sock *sk, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81ea6800)
Location: net/core/sock_map.c:464
Inline: False
Direct callers:
  - net/core/sock_map.c:bpf_sock_map_update
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/sock_map.c:sock_map_update_elem_sys
```
**Symbols:**

```
ffffffff81ea6800-ffffffff81ea6ab4: sock_map_update_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sock_map_update_common(struct bpf_map *map, u32 idx, struct sock *sk, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81f692c0)
Location: net/core/sock_map.c:464
Inline: False
Direct callers:
  - net/core/sock_map.c:bpf_sock_map_update
  - net/core/sock_map.c:sock_map_update_elem
  - net/core/sock_map.c:sock_map_update_elem_sys
```
**Symbols:**

```
ffffffff81f692c0-ffffffff81f695a3: sock_map_update_common (STB_LOCAL)
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
int sock_map_update_common(struct bpf_map *map, u32 idx, struct sock *sk, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffff800010c20658)
Location: net/core/sock_map.c:339
Inline: False
Direct callers:
  - net/core/sock_map.c:bpf_sock_map_update
  - net/core/sock_map.c:sock_map_update_elem
```
**Symbols:**

```
ffff800010c20658-ffff800010c20918: sock_map_update_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sock_map_update_common(struct bpf_map *map, u32 idx, struct sock *sk, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (c0d38000)
Location: net/core/sock_map.c:339
Inline: False
Direct callers:
  - net/core/sock_map.c:bpf_sock_map_update
  - net/core/sock_map.c:sock_map_update_elem
```
**Symbols:**

```
c0d38000-c0d38288: sock_map_update_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sock_map_update_common(struct bpf_map *map, u32 idx, struct sock *sk, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (c000000000d125d0)
Location: net/core/sock_map.c:339
Inline: False
Direct callers:
  - net/core/sock_map.c:bpf_sock_map_update
  - net/core/sock_map.c:sock_map_update_elem
```
**Symbols:**

```
c000000000d125d0-c000000000d1288c: sock_map_update_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sock_map_update_common(struct bpf_map *map, u32 idx, struct sock *sk, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffe0007993e8)
Location: net/core/sock_map.c:339
Inline: False
Direct callers:
  - net/core/sock_map.c:bpf_sock_map_update
  - net/core/sock_map.c:sock_map_update_elem
```
**Symbols:**

```
ffffffe0007993e8-ffffffe000799558: sock_map_update_common (STB_LOCAL)
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
int sock_map_update_common(struct bpf_map *map, u32 idx, struct sock *sk, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81919ad0)
Location: net/core/sock_map.c:339
Inline: False
Direct callers:
  - net/core/sock_map.c:bpf_sock_map_update
  - net/core/sock_map.c:sock_map_update_elem
```
**Symbols:**

```
ffffffff81919ad0-ffffffff81919d3d: sock_map_update_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sock_map_update_common(struct bpf_map *map, u32 idx, struct sock *sk, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff818d3880)
Location: net/core/sock_map.c:339
Inline: False
Direct callers:
  - net/core/sock_map.c:bpf_sock_map_update
  - net/core/sock_map.c:sock_map_update_elem
```
**Symbols:**

```
ffffffff818d3880-ffffffff818d3aed: sock_map_update_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sock_map_update_common(struct bpf_map *map, u32 idx, struct sock *sk, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff8196ac60)
Location: net/core/sock_map.c:339
Inline: False
Direct callers:
  - net/core/sock_map.c:bpf_sock_map_update
  - net/core/sock_map.c:sock_map_update_elem
```
**Symbols:**

```
ffffffff8196ac60-ffffffff8196aecd: sock_map_update_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sock_map_update_common(struct bpf_map *map, u32 idx, struct sock *sk, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff8198d0d0)
Location: net/core/sock_map.c:339
Inline: False
Direct callers:
  - net/core/sock_map.c:bpf_sock_map_update
  - net/core/sock_map.c:sock_map_update_elem
```
**Symbols:**

```
ffffffff8198d0d0-ffffffff8198d33d: sock_map_update_common (STB_LOCAL)
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
