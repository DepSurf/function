# Function: <code>cpu_map_update_elem</code>

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
int cpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff811b0150)
Location: kernel/bpf/cpumap.c:467
Inline: False
```
**Symbols:**

```
ffffffff811b0150-ffffffff811b01da: cpu_map_update_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int cpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff811ca6a0)
Location: kernel/bpf/cpumap.c:430
Inline: False
```
**Symbols:**

```
ffffffff811ca6a0-ffffffff811ca8d0: cpu_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff811ddfc0)
Location: kernel/bpf/cpumap.c:430
Inline: False
```
**Symbols:**

```
ffffffff811ddfc0-ffffffff811de1c8: cpu_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff811f3680)
Location: kernel/bpf/cpumap.c:468
Inline: False
```
**Symbols:**

```
ffffffff811f3680-ffffffff811f38f6: cpu_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff81200420)
Location: kernel/bpf/cpumap.c:468
Inline: False
```
**Symbols:**

```
ffffffff81200420-ffffffff81200696: cpu_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff812280d0)
Location: kernel/bpf/cpumap.c:436
Inline: False
```
**Symbols:**

```
ffffffff812280d0-ffffffff81228176: cpu_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int cpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/cpumap.c (0)
Location: kernel/bpf/cpumap.c:535
Inline: False
```
**Symbols:**

```
ffffffff8122f4e0-ffffffff8122f5f4: cpu_map_update_elem (STB_LOCAL)
ffffffff81be6606-ffffffff81be6612: cpu_map_update_elem.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int cpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/cpumap.c (0)
Location: kernel/bpf/cpumap.c:493
Inline: False
```
**Symbols:**

```
ffffffff81233a30-ffffffff81233b44: cpu_map_update_elem (STB_LOCAL)
ffffffff81bd8306-ffffffff81bd8312: cpu_map_update_elem.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int cpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/cpumap.c (0)
Location: kernel/bpf/cpumap.c:554
Inline: False
```
**Symbols:**

```
ffffffff8126d9f0-ffffffff8126db04: cpu_map_update_elem (STB_LOCAL)
ffffffff81cb9603-ffffffff81cb960f: cpu_map_update_elem.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int cpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/cpumap.c (0)
Location: kernel/bpf/cpumap.c:557
Inline: False
```
**Symbols:**

```
ffffffff812bc880-ffffffff812bc9af: cpu_map_update_elem (STB_LOCAL)
ffffffff81e6aa27-ffffffff81e6aa33: cpu_map_update_elem.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff8131fc20)
Location: kernel/bpf/cpumap.c:556
Inline: False
```
**Symbols:**

```
ffffffff8131fc20-ffffffff8131fd5b: cpu_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int cpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff8134fc40)
Location: kernel/bpf/cpumap.c:567
Inline: False
```
**Symbols:**

```
ffffffff8134fc40-ffffffff8134fd87: cpu_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int cpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff813770c0)
Location: kernel/bpf/cpumap.c:523
Inline: False
```
**Symbols:**

```
ffffffff813770c0-ffffffff81377243: cpu_map_update_elem (STB_LOCAL)
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
int cpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffff8000102886d8)
Location: kernel/bpf/cpumap.c:468
Inline: False
```
**Symbols:**

```
ffff8000102886d8-ffff80001028899c: cpu_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (c04b7c88)
Location: kernel/bpf/cpumap.c:468
Inline: False
```
**Symbols:**

```
c04b7c88-c04b7f0c: cpu_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (c000000000333ba0)
Location: kernel/bpf/cpumap.c:468
Inline: False
```
**Symbols:**

```
c000000000333ba0-c000000000333f04: cpu_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffe0001bc898)
Location: kernel/bpf/cpumap.c:468
Inline: False
```
**Symbols:**

```
ffffffe0001bc898-ffffffe0001bcac4: cpu_map_update_elem (STB_LOCAL)
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
int cpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff811f8a40)
Location: kernel/bpf/cpumap.c:468
Inline: False
```
**Symbols:**

```
ffffffff811f8a40-ffffffff811f8cb6: cpu_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff811eb790)
Location: kernel/bpf/cpumap.c:468
Inline: False
```
**Symbols:**

```
ffffffff811eb790-ffffffff811eba06: cpu_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff811f6810)
Location: kernel/bpf/cpumap.c:468
Inline: False
```
**Symbols:**

```
ffffffff811f6810-ffffffff811f6a86: cpu_map_update_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cpu_map_update_elem(struct bpf_map *map, void *key, void *value, u64 map_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff81205440)
Location: kernel/bpf/cpumap.c:468
Inline: False
```
**Symbols:**

```
ffffffff81205440-ffffffff812056c0: cpu_map_update_elem (STB_LOCAL)
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
