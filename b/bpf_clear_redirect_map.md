# Function: <code>bpf_clear_redirect_map</code>

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
void bpf_clear_redirect_map(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818df0d0)
Location: net/core/filter.c:3453
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/xskmap.c:xsk_map_free
```
**Symbols:**

```
ffffffff818df0d0-ffffffff818df12f: bpf_clear_redirect_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void bpf_clear_redirect_map(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8192cfe0)
Location: net/core/filter.c:3586
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/xskmap.c:xsk_map_free
```
**Symbols:**

```
ffffffff8192cfe0-ffffffff8192d041: bpf_clear_redirect_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bpf_clear_redirect_map(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8195f2e0)
Location: net/core/filter.c:3592
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/xskmap.c:xsk_map_free
```
**Symbols:**

```
ffffffff8195f2e0-ffffffff8195f341: bpf_clear_redirect_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bpf_clear_redirect_map(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a326f0)
Location: net/core/filter.c:3556
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - net/xdp/xskmap.c:xsk_map_free
```
**Symbols:**

```
ffffffff81a326f0-ffffffff81a32751: bpf_clear_redirect_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bpf_clear_redirect_map(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a34ac0)
Location: net/core/filter.c:3963
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - net/xdp/xskmap.c:xsk_map_free
```
**Symbols:**

```
ffffffff81a34ac0-ffffffff81a34b21: bpf_clear_redirect_map (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bpf_clear_redirect_map(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81acf210)
Location: net/core/filter.c:3922
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_free
```
**Symbols:**

```
ffffffff81acf210-ffffffff81acf298: bpf_clear_redirect_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bpf_clear_redirect_map(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c4c950)
Location: net/core/filter.c:4142
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_free
```
**Symbols:**

```
ffffffff81c4c950-ffffffff81c4c9de: bpf_clear_redirect_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bpf_clear_redirect_map(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e01760)
Location: net/core/filter.c:4156
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_free
```
**Symbols:**

```
ffffffff81e01760-ffffffff81e01802: bpf_clear_redirect_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bpf_clear_redirect_map(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e73a30)
Location: net/core/filter.c:4210
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_free
```
**Symbols:**

```
ffffffff81e73a30-ffffffff81e73ad2: bpf_clear_redirect_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bpf_clear_redirect_map(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f331f0)
Location: net/core/filter.c:4289
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_free
```
**Symbols:**

```
ffffffff81f331f0-ffffffff81f33292: bpf_clear_redirect_map (STB_GLOBAL)
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
void bpf_clear_redirect_map(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010c027f0)
Location: net/core/filter.c:3592
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/xskmap.c:xsk_map_free
```
**Symbols:**

```
ffff800010c027f0-ffff800010c028b4: bpf_clear_redirect_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bpf_clear_redirect_map(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d1bc8c)
Location: net/core/filter.c:3592
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/xskmap.c:xsk_map_free
```
**Symbols:**

```
c0d1bc8c-c0d1bd20: bpf_clear_redirect_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bpf_clear_redirect_map(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000cebce0)
Location: net/core/filter.c:3592
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/xskmap.c:xsk_map_free
```
**Symbols:**

```
c000000000cebce0-c000000000cebdc4: bpf_clear_redirect_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void bpf_clear_redirect_map(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe000781b86)
Location: net/core/filter.c:3592
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/xskmap.c:xsk_map_free
```
**Symbols:**

```
ffffffe000781b86-ffffffe000781c18: bpf_clear_redirect_map (STB_GLOBAL)
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
void bpf_clear_redirect_map(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818ff2b0)
Location: net/core/filter.c:3592
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/xskmap.c:xsk_map_free
```
**Symbols:**

```
ffffffff818ff2b0-ffffffff818ff311: bpf_clear_redirect_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bpf_clear_redirect_map(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b90e0)
Location: net/core/filter.c:3592
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/xskmap.c:xsk_map_free
```
**Symbols:**

```
ffffffff818b90e0-ffffffff818b9141: bpf_clear_redirect_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bpf_clear_redirect_map(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff819502e0)
Location: net/core/filter.c:3592
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/xskmap.c:xsk_map_free
```
**Symbols:**

```
ffffffff819502e0-ffffffff81950341: bpf_clear_redirect_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bpf_clear_redirect_map(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81971cb0)
Location: net/core/filter.c:3592
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_free
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/xskmap.c:xsk_map_free
```
**Symbols:**

```
ffffffff81971cb0-ffffffff81971d11: bpf_clear_redirect_map (STB_GLOBAL)
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
