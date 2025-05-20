# Function: <code>sock_map_get_next_key</code>

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
int sock_map_get_next_key(struct bpf_map *map, void *key, void *next_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/sockmap.c (ffffffff811b0980)
Location: kernel/bpf/sockmap.c:615
Inline: False
```
**Symbols:**

```
ffffffff811b0980-ffffffff811b09b8: sock_map_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sock_map_get_next_key(struct bpf_map *map, void *key, void *next_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/sockmap.c (ffffffff811cc440)
Location: kernel/bpf/sockmap.c:1758
Inline: False
```
**Symbols:**

```
ffffffff811cc440-ffffffff811cc478: sock_map_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sock_map_get_next_key(struct bpf_map *map, void *key, void *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff818f16e0)
Location: net/core/sock_map.c:317
Inline: False
```
**Symbols:**

```
ffffffff818f16e0-ffffffff818f171c: sock_map_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sock_map_get_next_key(struct bpf_map *map, void *key, void *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81943b60)
Location: net/core/sock_map.c:318
Inline: False
```
**Symbols:**

```
ffffffff81943b60-ffffffff81943b9c: sock_map_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sock_map_get_next_key(struct bpf_map *map, void *key, void *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81978b50)
Location: net/core/sock_map.c:324
Inline: False
```
**Symbols:**

```
ffffffff81978b50-ffffffff81978b8c: sock_map_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sock_map_get_next_key(struct bpf_map *map, void *key, void *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81a4d8c0)
Location: net/core/sock_map.c:450
Inline: False
```
**Symbols:**

```
ffffffff81a4d8c0-ffffffff81a4d8fc: sock_map_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sock_map_get_next_key(struct bpf_map *map, void *key, void *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81a53520)
Location: net/core/sock_map.c:451
Inline: False
```
**Symbols:**

```
ffffffff81a53520-ffffffff81a5355c: sock_map_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sock_map_get_next_key(struct bpf_map *map, void *key, void *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81a4f130)
Location: net/core/sock_map.c:451
Inline: False
```
**Symbols:**

```
ffffffff81a4f130-ffffffff81a4f16c: sock_map_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sock_map_get_next_key(struct bpf_map *map, void *key, void *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81b07d10)
Location: net/core/sock_map.c:451
Inline: False
```
**Symbols:**

```
ffffffff81b07d10-ffffffff81b07d4c: sock_map_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sock_map_get_next_key(struct bpf_map *map, void *key, void *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81c8db00)
Location: net/core/sock_map.c:451
Inline: False
```
**Symbols:**

```
ffffffff81c8db00-ffffffff81c8db54: sock_map_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sock_map_get_next_key(struct bpf_map *map, void *key, void *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81e489d0)
Location: net/core/sock_map.c:453
Inline: False
```
**Symbols:**

```
ffffffff81e489d0-ffffffff81e48a24: sock_map_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sock_map_get_next_key(struct bpf_map *map, void *key, void *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81ea4070)
Location: net/core/sock_map.c:449
Inline: False
```
**Symbols:**

```
ffffffff81ea4070-ffffffff81ea40c4: sock_map_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sock_map_get_next_key(struct bpf_map *map, void *key, void *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81f66970)
Location: net/core/sock_map.c:449
Inline: False
```
**Symbols:**

```
ffffffff81f66970-ffffffff81f669c4: sock_map_get_next_key (STB_LOCAL)
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
int sock_map_get_next_key(struct bpf_map *map, void *key, void *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffff800010c1f6e8)
Location: net/core/sock_map.c:324
Inline: False
```
**Symbols:**

```
ffff800010c1f6e8-ffff800010c1f76c: sock_map_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sock_map_get_next_key(struct bpf_map *map, void *key, void *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (c0d3730c)
Location: net/core/sock_map.c:324
Inline: False
```
**Symbols:**

```
c0d3730c-c0d37370: sock_map_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sock_map_get_next_key(struct bpf_map *map, void *key, void *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (c000000000d11670)
Location: net/core/sock_map.c:324
Inline: False
```
**Symbols:**

```
c000000000d11670-c000000000d116d0: sock_map_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sock_map_get_next_key(struct bpf_map *map, void *key, void *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffe000798d80)
Location: net/core/sock_map.c:324
Inline: False
```
**Symbols:**

```
ffffffe000798d80-ffffffe000798de2: sock_map_get_next_key (STB_LOCAL)
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
int sock_map_get_next_key(struct bpf_map *map, void *key, void *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff819189c0)
Location: net/core/sock_map.c:324
Inline: False
```
**Symbols:**

```
ffffffff819189c0-ffffffff819189fc: sock_map_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sock_map_get_next_key(struct bpf_map *map, void *key, void *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff818d2770)
Location: net/core/sock_map.c:324
Inline: False
```
**Symbols:**

```
ffffffff818d2770-ffffffff818d27ac: sock_map_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sock_map_get_next_key(struct bpf_map *map, void *key, void *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81969b50)
Location: net/core/sock_map.c:324
Inline: False
```
**Symbols:**

```
ffffffff81969b50-ffffffff81969b8c: sock_map_get_next_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sock_map_get_next_key(struct bpf_map *map, void *key, void *next);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff8198bf30)
Location: net/core/sock_map.c:324
Inline: False
```
**Symbols:**

```
ffffffff8198bf30-ffffffff8198bf6c: sock_map_get_next_key (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void *next</code>
</li>
<li>
<b>Param removed. </b>
<code>void *next_key</code>
</li>
</ul>
</details>
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
