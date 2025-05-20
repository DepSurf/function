# Function: <code>bpf_set_hash</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 bpf_set_hash(u64 skb, u64 hash, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817e7b70)
Location: net/core/filter.c:1878
Inline: False
```
**Symbols:**

```
ffffffff817e7b70-ffffffff817e7b8a: bpf_set_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 bpf_set_hash(u64 skb, u64 hash, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81862ab0)
Location: net/core/filter.c:1943
Inline: False
```
**Symbols:**

```
ffffffff81862ab0-ffffffff81862aca: bpf_set_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 bpf_set_hash(u64 skb, u64 hash, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818ae7f0)
Location: net/core/filter.c:2462
Inline: False
```
**Symbols:**

```
ffffffff818ae7f0-ffffffff818ae80a: bpf_set_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 bpf_set_hash(u64 skb, u64 hash, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818d2a90)
Location: net/core/filter.c:2654
Inline: False
```
**Symbols:**

```
ffffffff818d2a90-ffffffff818d2aaa: bpf_set_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 bpf_set_hash(u64 skb, u64 hash, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8191fd90)
Location: net/core/filter.c:2700
Inline: False
```
**Symbols:**

```
ffffffff8191fd90-ffffffff8191fdaa: bpf_set_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 bpf_set_hash(u64 skb, u64 hash, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81951fd0)
Location: net/core/filter.c:2702
Inline: False
```
**Symbols:**

```
ffffffff81951fd0-ffffffff81951fea: bpf_set_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 bpf_set_hash(u64 skb, u64 hash, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a231d0)
Location: net/core/filter.c:2740
Inline: False
```
**Symbols:**

```
ffffffff81a231d0-ffffffff81a231ea: bpf_set_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 bpf_set_hash(u64 skb, u64 hash, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a23590)
Location: net/core/filter.c:3109
Inline: False
```
**Symbols:**

```
ffffffff81a23590-ffffffff81a235aa: bpf_set_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 bpf_set_hash(u64 skb, u64 hash, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a0a8c0)
Location: net/core/filter.c:3106
Inline: False
```
**Symbols:**

```
ffffffff81a0a8c0-ffffffff81a0a8da: bpf_set_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 bpf_set_hash(u64 skb, u64 hash, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81abcd40)
Location: net/core/filter.c:3093
Inline: False
```
**Symbols:**

```
ffffffff81abcd40-ffffffff81abcd5a: bpf_set_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 bpf_set_hash(u64 skb, u64 hash, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c37850)
Location: net/core/filter.c:3094
Inline: False
```
**Symbols:**

```
ffffffff81c37850-ffffffff81c37872: bpf_set_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 bpf_set_hash(u64 skb, u64 hash, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81deb0f0)
Location: net/core/filter.c:3101
Inline: False
```
**Symbols:**

```
ffffffff81deb0f0-ffffffff81deb112: bpf_set_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 bpf_set_hash(u64 skb, u64 hash, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e5c8f0)
Location: net/core/filter.c:3117
Inline: False
```
**Symbols:**

```
ffffffff81e5c8f0-ffffffff81e5c912: bpf_set_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 bpf_set_hash(u64 skb, u64 hash, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f1bce0)
Location: net/core/filter.c:3151
Inline: False
```
**Symbols:**

```
ffffffff81f1bce0-ffffffff81f1bd02: bpf_set_hash (STB_GLOBAL)
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
u64 bpf_set_hash(u64 skb, u64 hash, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010bf4130)
Location: net/core/filter.c:2702
Inline: False
```
**Symbols:**

```
ffff800010bf4130-ffff800010bf416c: bpf_set_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 bpf_set_hash(u64 skb, u64 hash, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d0c92c)
Location: net/core/filter.c:2702
Inline: False
```
**Symbols:**

```
c0d0c92c-c0d0c964: bpf_set_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 bpf_set_hash(u64 skb, u64 hash, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000cd92a0)
Location: net/core/filter.c:2702
Inline: False
```
**Symbols:**

```
c000000000cd92a0-c000000000cd92c4: bpf_set_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 bpf_set_hash(u64 skb, u64 hash, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe000775622)
Location: net/core/filter.c:2702
Inline: False
```
**Symbols:**

```
ffffffe000775622-ffffffe00077565a: bpf_set_hash (STB_GLOBAL)
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
u64 bpf_set_hash(u64 skb, u64 hash, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818f1fa0)
Location: net/core/filter.c:2702
Inline: False
```
**Symbols:**

```
ffffffff818f1fa0-ffffffff818f1fba: bpf_set_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 bpf_set_hash(u64 skb, u64 hash, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818abdd0)
Location: net/core/filter.c:2702
Inline: False
```
**Symbols:**

```
ffffffff818abdd0-ffffffff818abdea: bpf_set_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 bpf_set_hash(u64 skb, u64 hash, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81942fd0)
Location: net/core/filter.c:2702
Inline: False
```
**Symbols:**

```
ffffffff81942fd0-ffffffff81942fea: bpf_set_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 bpf_set_hash(u64 skb, u64 hash, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff819648c0)
Location: net/core/filter.c:2702
Inline: False
```
**Symbols:**

```
ffffffff819648c0-ffffffff819648da: bpf_set_hash (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
