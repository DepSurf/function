# Function: <code>bpf_map_lookup_elem</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u64 bpf_map_lookup_elem(u64 r1, u64 r2, u64 r3, u64 r4, u64 r5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff811772d0)
Location: kernel/bpf/helpers.c:29
Inline: False
```
**Symbols:**

```
ffffffff811772d0-ffffffff811772e2: bpf_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u64 bpf_map_lookup_elem(u64 r1, u64 r2, u64 r3, u64 r4, u64 r5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81185d80)
Location: kernel/bpf/helpers.c:29
Inline: False
```
**Symbols:**

```
ffffffff81185d80-ffffffff81185d92: bpf_map_lookup_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u64 bpf_map_lookup_elem(u64 map, u64 key, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81193150)
Location: kernel/bpf/helpers.c:31
Inline: False
```
**Symbols:**

```
ffffffff81193150-ffffffff81193162: bpf_map_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 bpf_map_lookup_elem(u64 map, u64 key, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff8119a170)
Location: kernel/bpf/helpers.c:31
Inline: False
```
**Symbols:**

```
ffffffff8119a170-ffffffff8119a182: bpf_map_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 bpf_map_lookup_elem(u64 map, u64 key, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff811a9540)
Location: kernel/bpf/helpers.c:31
Inline: False
```
**Symbols:**

```
ffffffff811a9540-ffffffff811a9557: bpf_map_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 bpf_map_lookup_elem(u64 map, u64 key, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff811c0a20)
Location: kernel/bpf/helpers.c:31
Inline: False
```
**Symbols:**

```
ffffffff811c0a20-ffffffff811c0a37: bpf_map_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 bpf_map_lookup_elem(u64 map, u64 key, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff811d1e80)
Location: kernel/bpf/helpers.c:31
Inline: False
```
**Symbols:**

```
ffffffff811d1e80-ffffffff811d1e97: bpf_map_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 bpf_map_lookup_elem(u64 map, u64 key, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff811e61b0)
Location: kernel/bpf/helpers.c:26
Inline: False
```
**Symbols:**

```
ffffffff811e61b0-ffffffff811e61c7: bpf_map_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 bpf_map_lookup_elem(u64 map, u64 key, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff811f2900)
Location: kernel/bpf/helpers.c:26
Inline: False
```
**Symbols:**

```
ffffffff811f2900-ffffffff811f2917: bpf_map_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 bpf_map_lookup_elem(u64 map, u64 key, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81214740)
Location: kernel/bpf/helpers.c:29
Inline: False
```
**Symbols:**

```
ffffffff81214740-ffffffff81214757: bpf_map_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 bpf_map_lookup_elem(u64 map, u64 key, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81216200)
Location: kernel/bpf/helpers.c:29
Inline: False
```
**Symbols:**

```
ffffffff81216200-ffffffff81216217: bpf_map_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 bpf_map_lookup_elem(u64 map, u64 key, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81218f10)
Location: kernel/bpf/helpers.c:30
Inline: False
```
**Symbols:**

```
ffffffff81218f10-ffffffff81218f27: bpf_map_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 bpf_map_lookup_elem(u64 map, u64 key, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff8124f630)
Location: kernel/bpf/helpers.c:30
Inline: False
```
**Symbols:**

```
ffffffff8124f630-ffffffff8124f647: bpf_map_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 bpf_map_lookup_elem(u64 map, u64 key, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81296790)
Location: kernel/bpf/helpers.c:33
Inline: False
```
**Symbols:**

```
ffffffff81296790-ffffffff812967af: bpf_map_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 bpf_map_lookup_elem(u64 map, u64 key, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff812f16c0)
Location: kernel/bpf/helpers.c:36
Inline: False
```
**Symbols:**

```
ffffffff812f16c0-ffffffff812f16df: bpf_map_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 bpf_map_lookup_elem(u64 map, u64 key, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff8131e2b0)
Location: kernel/bpf/helpers.c:37
Inline: False
```
**Symbols:**

```
ffffffff8131e2b0-ffffffff8131e2cf: bpf_map_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 bpf_map_lookup_elem(u64 map, u64 key, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff813406d0)
Location: kernel/bpf/helpers.c:38
Inline: False
```
**Symbols:**

```
ffffffff813406d0-ffffffff813406ef: bpf_map_lookup_elem (STB_GLOBAL)
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
u64 bpf_map_lookup_elem(u64 map, u64 key, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffff800010276218)
Location: kernel/bpf/helpers.c:26
Inline: False
```
**Symbols:**

```
ffff800010276218-ffff800010276254: bpf_map_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 bpf_map_lookup_elem(u64 map, u64 key, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (c04a8834)
Location: kernel/bpf/helpers.c:26
Inline: False
```
**Symbols:**

```
c04a8834-c04a8860: bpf_map_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 bpf_map_lookup_elem(u64 map, u64 key, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (c00000000031e650)
Location: kernel/bpf/helpers.c:26
Inline: False
```
**Symbols:**

```
c00000000031e650-c00000000031e694: bpf_map_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 bpf_map_lookup_elem(u64 map, u64 key, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffe0001ae712)
Location: kernel/bpf/helpers.c:26
Inline: False
```
**Symbols:**

```
ffffffe0001ae712-ffffffe0001ae742: bpf_map_lookup_elem (STB_GLOBAL)
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
u64 bpf_map_lookup_elem(u64 map, u64 key, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff811eaf20)
Location: kernel/bpf/helpers.c:26
Inline: False
```
**Symbols:**

```
ffffffff811eaf20-ffffffff811eaf37: bpf_map_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 bpf_map_lookup_elem(u64 map, u64 key, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff811ddce0)
Location: kernel/bpf/helpers.c:26
Inline: False
```
**Symbols:**

```
ffffffff811ddce0-ffffffff811ddcf7: bpf_map_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 bpf_map_lookup_elem(u64 map, u64 key, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff811e8cf0)
Location: kernel/bpf/helpers.c:26
Inline: False
```
**Symbols:**

```
ffffffff811e8cf0-ffffffff811e8d07: bpf_map_lookup_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 bpf_map_lookup_elem(u64 map, u64 key, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff811f70a0)
Location: kernel/bpf/helpers.c:26
Inline: False
```
**Symbols:**

```
ffffffff811f70a0-ffffffff811f70b7: bpf_map_lookup_elem (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 map</code>
</li>
<li>
<b>Param added. </b>
<code>u64 key</code>
</li>
<li>
<b>Param added. </b>
<code>u64 __ur_1</code>
</li>
<li>
<b>Param added. </b>
<code>u64 __ur_2</code>
</li>
<li>
<b>Param added. </b>
<code>u64 __ur_3</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r1</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r2</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r3</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r4</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r5</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
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
