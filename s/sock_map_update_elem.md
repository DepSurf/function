# Function: <code>sock_map_update_elem</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sock_map_update_elem(struct bpf_map *map, void *key, void *value, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/sockmap.c (ffffffff811b1620)
Location: kernel/bpf/sockmap.c:854
Inline: False
```
**Symbols:**

```
ffffffff811b1620-ffffffff811b16dd: sock_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sock_map_update_elem(struct bpf_map *map, void *key, void *value, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/sockmap.c (ffffffff811cd7c0)
Location: kernel/bpf/sockmap.c:2077
Inline: False
```
**Symbols:**

```
ffffffff811cd7c0-ffffffff811cd890: sock_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sock_map_update_elem(struct bpf_map *map, void *key, void *value, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff818f2480)
Location: net/core/sock_map.c:395
Inline: False
```
**Symbols:**

```
ffffffff818f2480-ffffffff818f254c: sock_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sock_map_update_elem(struct bpf_map *map, void *key, void *value, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81944f10)
Location: net/core/sock_map.c:399
Inline: False
```
**Symbols:**

```
ffffffff81944f10-ffffffff81944fda: sock_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sock_map_update_elem(struct bpf_map *map, void *key, void *value, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81979f20)
Location: net/core/sock_map.c:405
Inline: False
```
**Symbols:**

```
ffffffff81979f20-ffffffff81979ff3: sock_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sock_map_update_elem(struct bpf_map *map, void *key, void *value, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81a4f520)
Location: net/core/sock_map.c:566
Inline: False
```
**Symbols:**

```
ffffffff81a4f520-ffffffff81a4f688: sock_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sock_map_update_elem(struct bpf_map *map, void *key, void *value, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81a558a0)
Location: net/core/sock_map.c:609
Inline: False
```
**Symbols:**

```
ffffffff81a558a0-ffffffff81a55a04: sock_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sock_map_update_elem(struct bpf_map *map, void *key, void *value, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81a51350)
Location: net/core/sock_map.c:603
Inline: False
```
**Symbols:**

```
ffffffff81a51350-ffffffff81a51487: sock_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int sock_map_update_elem(struct bpf_map *map, void *key, void *value, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock_map.c (0)
Location: net/core/sock_map.c:594
Inline: False
```
**Symbols:**

```
ffffffff81b0a0e0-ffffffff81b0a210: sock_map_update_elem (STB_LOCAL)
ffffffff81d38b51-ffffffff81d38b91: sock_map_update_elem.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int sock_map_update_elem(struct bpf_map *map, void *key, void *value, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock_map.c (0)
Location: net/core/sock_map.c:588
Inline: False
```
**Symbols:**

```
ffffffff81c90360-ffffffff81c90491: sock_map_update_elem (STB_LOCAL)
ffffffff81f053ab-ffffffff81f053eb: sock_map_update_elem.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int sock_map_update_elem(struct bpf_map *map, void *key, void *value, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock_map.c (0)
Location: net/core/sock_map.c:590
Inline: False
```
**Symbols:**

```
ffffffff81e4b790-ffffffff81e4b8c1: sock_map_update_elem (STB_LOCAL)
ffffffff820ad3b8-ffffffff820ad3f8: sock_map_update_elem.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
long int sock_map_update_elem(struct bpf_map *map, void *key, void *value, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock_map.c (0)
Location: net/core/sock_map.c:586
Inline: False
```
**Symbols:**

```
ffffffff81ea6eb0-ffffffff81ea6fe7: sock_map_update_elem (STB_LOCAL)
ffffffff8212e559-ffffffff8212e592: sock_map_update_elem.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
long int sock_map_update_elem(struct bpf_map *map, void *key, void *value, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock_map.c (0)
Location: net/core/sock_map.c:588
Inline: False
```
**Symbols:**

```
ffffffff81f699d0-ffffffff81f69ad3: sock_map_update_elem (STB_LOCAL)
ffffffff8221033e-ffffffff8221035e: sock_map_update_elem.cold (STB_LOCAL)
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
int sock_map_update_elem(struct bpf_map *map, void *key, void *value, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffff800010c209a0)
Location: net/core/sock_map.c:405
Inline: False
```
**Symbols:**

```
ffff800010c209a0-ffff800010c20aac: sock_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sock_map_update_elem(struct bpf_map *map, void *key, void *value, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (c0d38308)
Location: net/core/sock_map.c:405
Inline: False
```
**Symbols:**

```
c0d38308-c0d3840c: sock_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sock_map_update_elem(struct bpf_map *map, void *key, void *value, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (c000000000d12910)
Location: net/core/sock_map.c:405
Inline: False
```
**Symbols:**

```
c000000000d12910-c000000000d12a78: sock_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sock_map_update_elem(struct bpf_map *map, void *key, void *value, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffe0007995d2)
Location: net/core/sock_map.c:405
Inline: False
```
**Symbols:**

```
ffffffe0007995d2-ffffffe0007996a6: sock_map_update_elem (STB_LOCAL)
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
int sock_map_update_elem(struct bpf_map *map, void *key, void *value, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81919d90)
Location: net/core/sock_map.c:405
Inline: False
```
**Symbols:**

```
ffffffff81919d90-ffffffff81919e63: sock_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sock_map_update_elem(struct bpf_map *map, void *key, void *value, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff818d3b40)
Location: net/core/sock_map.c:405
Inline: False
```
**Symbols:**

```
ffffffff818d3b40-ffffffff818d3c13: sock_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sock_map_update_elem(struct bpf_map *map, void *key, void *value, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff8196af20)
Location: net/core/sock_map.c:405
Inline: False
```
**Symbols:**

```
ffffffff8196af20-ffffffff8196aff3: sock_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sock_map_update_elem(struct bpf_map *map, void *key, void *value, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff8198d390)
Location: net/core/sock_map.c:405
Inline: False
```
**Symbols:**

```
ffffffff8198d390-ffffffff8198d46f: sock_map_update_elem (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>long int</code>
</li>
</ul>
</details>
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
