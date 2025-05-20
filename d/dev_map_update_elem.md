# Function: <code>dev_map_update_elem</code>

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
int dev_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff811af1f0)
Location: kernel/bpf/devmap.c:317
Inline: False
```
**Symbols:**

```
ffffffff811af1f0-ffffffff811af2ce: dev_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dev_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff811c9b00)
Location: kernel/bpf/devmap.c:431
Inline: False
```
**Symbols:**

```
ffffffff811c9b00-ffffffff811c9c1c: dev_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dev_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff811dd400)
Location: kernel/bpf/devmap.c:432
Inline: False
```
**Symbols:**

```
ffffffff811dd400-ffffffff811dd51c: dev_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int dev_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff811f29c0)
Location: kernel/bpf/devmap.c:415
Inline: False
```
**Symbols:**

```
ffffffff811f29c0-ffffffff811f2b43: dev_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dev_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff811ff490)
Location: kernel/bpf/devmap.c:657
Inline: False
```
**Symbols:**

```
ffffffff811ff490-ffffffff811ff531: dev_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int dev_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/devmap.c (0)
Location: kernel/bpf/devmap.c:685
Inline: False
```
**Symbols:**

```
ffffffff812267d0-ffffffff812268d4: dev_map_update_elem (STB_LOCAL)
ffffffff812279b1-ffffffff812279bd: dev_map_update_elem.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int dev_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/devmap.c (0)
Location: kernel/bpf/devmap.c:671
Inline: False
```
**Symbols:**

```
ffffffff8122d3c0-ffffffff8122d4c4: dev_map_update_elem (STB_LOCAL)
ffffffff81be65ee-ffffffff81be65fa: dev_map_update_elem.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int dev_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/devmap.c (0)
Location: kernel/bpf/devmap.c:664
Inline: False
```
**Symbols:**

```
ffffffff81232190-ffffffff81232294: dev_map_update_elem (STB_LOCAL)
ffffffff81bd82ee-ffffffff81bd82fa: dev_map_update_elem.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dev_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/devmap.c (0)
Location: kernel/bpf/devmap.c:936
Inline: False
```
**Symbols:**

```
ffffffff8126b3e0-ffffffff8126b4e4: dev_map_update_elem (STB_LOCAL)
ffffffff81cb95cd-ffffffff81cb95d9: dev_map_update_elem.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dev_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/devmap.c (0)
Location: kernel/bpf/devmap.c:928
Inline: False
```
**Symbols:**

```
ffffffff812ba020-ffffffff812ba129: dev_map_update_elem (STB_LOCAL)
ffffffff81e6a9f1-ffffffff81e6a9fd: dev_map_update_elem.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dev_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff8131d380)
Location: kernel/bpf/devmap.c:928
Inline: False
```
**Symbols:**

```
ffffffff8131d380-ffffffff8131d495: dev_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int dev_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff8134d260)
Location: kernel/bpf/devmap.c:939
Inline: False
```
**Symbols:**

```
ffffffff8134d260-ffffffff8134d2a2: dev_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int dev_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff81374780)
Location: kernel/bpf/devmap.c:947
Inline: False
```
**Symbols:**

```
ffffffff81374780-ffffffff813747c2: dev_map_update_elem (STB_LOCAL)
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
int dev_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffff800010286770)
Location: kernel/bpf/devmap.c:657
Inline: False
```
**Symbols:**

```
ffff800010286770-ffff800010286878: dev_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dev_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (c04b73b8)
Location: kernel/bpf/devmap.c:657
Inline: False
```
**Symbols:**

```
c04b73b8-c04b7498: dev_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dev_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (c0000000003319e0)
Location: kernel/bpf/devmap.c:657
Inline: False
```
**Symbols:**

```
c0000000003319e0-c000000000331b70: dev_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dev_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffe0001bb7a4)
Location: kernel/bpf/devmap.c:657
Inline: False
```
**Symbols:**

```
ffffffe0001bb7a4-ffffffe0001bb848: dev_map_update_elem (STB_LOCAL)
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
int dev_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff811f7ab0)
Location: kernel/bpf/devmap.c:657
Inline: False
```
**Symbols:**

```
ffffffff811f7ab0-ffffffff811f7b51: dev_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int dev_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff811ea800)
Location: kernel/bpf/devmap.c:657
Inline: False
```
**Symbols:**

```
ffffffff811ea800-ffffffff811ea8a1: dev_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int dev_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff811f5880)
Location: kernel/bpf/devmap.c:657
Inline: False
```
**Symbols:**

```
ffffffff811f5880-ffffffff811f5921: dev_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dev_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff81203de0)
Location: kernel/bpf/devmap.c:657
Inline: False
```
**Symbols:**

```
ffffffff81203de0-ffffffff81203e81: dev_map_update_elem (STB_LOCAL)
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
