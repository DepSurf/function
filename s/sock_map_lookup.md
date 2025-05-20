# Function: <code>sock_map_lookup</code>

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
void *sock_map_lookup(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/sockmap.c (ffffffff811b09c0)
Location: kernel/bpf/sockmap.c:849
Inline: False
```
**Symbols:**

```
ffffffff811b09c0-ffffffff811b09cd: sock_map_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *sock_map_lookup(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/sockmap.c (ffffffff811cc480)
Location: kernel/bpf/sockmap.c:2072
Inline: False
```
**Symbols:**

```
ffffffff811cc480-ffffffff811cc48d: sock_map_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *sock_map_lookup(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff818f16c0)
Location: net/core/sock_map.c:275
Inline: False
```
**Symbols:**

```
ffffffff818f16c0-ffffffff818f16d2: sock_map_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *sock_map_lookup(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81943b40)
Location: net/core/sock_map.c:272
Inline: False
```
**Symbols:**

```
ffffffff81943b40-ffffffff81943b52: sock_map_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *sock_map_lookup(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81978b30)
Location: net/core/sock_map.c:278
Inline: False
```
**Symbols:**

```
ffffffff81978b30-ffffffff81978b42: sock_map_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *sock_map_lookup(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81a4f030)
Location: net/core/sock_map.c:382
Inline: False
```
**Symbols:**

```
ffffffff81a4f030-ffffffff81a4f0c9: sock_map_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *sock_map_lookup(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81a54c00)
Location: net/core/sock_map.c:383
Inline: False
```
**Symbols:**

```
ffffffff81a54c00-ffffffff81a54c97: sock_map_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *sock_map_lookup(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81a51490)
Location: net/core/sock_map.c:383
Inline: False
```
**Symbols:**

```
ffffffff81a51490-ffffffff81a51523: sock_map_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void *sock_map_lookup(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock_map.c (0)
Location: net/core/sock_map.c:383
Inline: False
```
**Symbols:**

```
ffffffff81b09410-ffffffff81b094b0: sock_map_lookup (STB_LOCAL)
ffffffff81d38b31-ffffffff81d38b51: sock_map_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void *sock_map_lookup(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock_map.c (0)
Location: net/core/sock_map.c:383
Inline: False
```
**Symbols:**

```
ffffffff81c8f4e0-ffffffff81c8f5a4: sock_map_lookup (STB_LOCAL)
ffffffff81f0538b-ffffffff81f053ab: sock_map_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void *sock_map_lookup(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock_map.c (0)
Location: net/core/sock_map.c:385
Inline: False
```
**Symbols:**

```
ffffffff81e4a7b0-ffffffff81e4a870: sock_map_lookup (STB_LOCAL)
ffffffff820ad398-ffffffff820ad3b8: sock_map_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void *sock_map_lookup(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock_map.c (0)
Location: net/core/sock_map.c:381
Inline: False
```
**Symbols:**

```
ffffffff81ea5eb0-ffffffff81ea5f68: sock_map_lookup (STB_LOCAL)
ffffffff8212e540-ffffffff8212e559: sock_map_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void *sock_map_lookup(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock_map.c (0)
Location: net/core/sock_map.c:381
Inline: False
```
**Symbols:**

```
ffffffff81f68970-ffffffff81f68a28: sock_map_lookup (STB_LOCAL)
ffffffff82210325-ffffffff8221033e: sock_map_lookup.cold (STB_LOCAL)
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
void *sock_map_lookup(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffff800010c1f6c8)
Location: net/core/sock_map.c:278
Inline: False
```
**Symbols:**

```
ffff800010c1f6c8-ffff800010c1f6e4: sock_map_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *sock_map_lookup(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (c0d372f0)
Location: net/core/sock_map.c:278
Inline: False
```
**Symbols:**

```
c0d372f0-c0d3730c: sock_map_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *sock_map_lookup(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (c000000000d11660)
Location: net/core/sock_map.c:278
Inline: False
```
**Symbols:**

```
c000000000d11660-c000000000d11670: sock_map_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *sock_map_lookup(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffe000798d62)
Location: net/core/sock_map.c:278
Inline: False
```
**Symbols:**

```
ffffffe000798d62-ffffffe000798d80: sock_map_lookup (STB_LOCAL)
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
void *sock_map_lookup(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff819189a0)
Location: net/core/sock_map.c:278
Inline: False
```
**Symbols:**

```
ffffffff819189a0-ffffffff819189b2: sock_map_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *sock_map_lookup(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff818d2750)
Location: net/core/sock_map.c:278
Inline: False
```
**Symbols:**

```
ffffffff818d2750-ffffffff818d2762: sock_map_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *sock_map_lookup(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81969b30)
Location: net/core/sock_map.c:278
Inline: False
```
**Symbols:**

```
ffffffff81969b30-ffffffff81969b42: sock_map_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *sock_map_lookup(struct bpf_map *map, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff8198bf10)
Location: net/core/sock_map.c:278
Inline: False
```
**Symbols:**

```
ffffffff8198bf10-ffffffff8198bf22: sock_map_lookup (STB_LOCAL)
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
