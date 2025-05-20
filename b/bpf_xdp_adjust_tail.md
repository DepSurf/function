# Function: <code>bpf_xdp_adjust_tail</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 bpf_xdp_adjust_tail(u64 xdp, u64 offset, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818ae850)
Location: net/core/filter.c:3085
Inline: False
```
**Symbols:**

```
ffffffff818ae850-ffffffff818ae87f: bpf_xdp_adjust_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 bpf_xdp_adjust_tail(u64 xdp, u64 offset, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818d2af0)
Location: net/core/filter.c:3273
Inline: False
```
**Symbols:**

```
ffffffff818d2af0-ffffffff818d2b1f: bpf_xdp_adjust_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 bpf_xdp_adjust_tail(u64 xdp, u64 offset, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81922e80)
Location: net/core/filter.c:3408
Inline: False
```
**Symbols:**

```
ffffffff81922e80-ffffffff81922eb1: bpf_xdp_adjust_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 bpf_xdp_adjust_tail(u64 xdp, u64 offset, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff819550b0)
Location: net/core/filter.c:3410
Inline: False
```
**Symbols:**

```
ffffffff819550b0-ffffffff819550e1: bpf_xdp_adjust_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 bpf_xdp_adjust_tail(u64 xdp, u64 offset, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a295a0)
Location: net/core/filter.c:3452
Inline: False
```
**Symbols:**

```
ffffffff81a295a0-ffffffff81a29646: bpf_xdp_adjust_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 bpf_xdp_adjust_tail(u64 xdp, u64 offset, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a287b0)
Location: net/core/filter.c:3859
Inline: False
```
**Symbols:**

```
ffffffff81a287b0-ffffffff81a28856: bpf_xdp_adjust_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 bpf_xdp_adjust_tail(u64 xdp, u64 offset, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a0fb90)
Location: net/core/filter.c:3855
Inline: False
```
**Symbols:**

```
ffffffff81a0fb90-ffffffff81a0fc36: bpf_xdp_adjust_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u64 bpf_xdp_adjust_tail(u64 xdp, u64 offset, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:3824
Inline: False
```
**Symbols:**

```
ffffffff81d36f9d-ffffffff81d36fb2: bpf_xdp_adjust_tail.cold (STB_LOCAL)
ffffffff81ac41d0-ffffffff81ac4268: bpf_xdp_adjust_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u64 bpf_xdp_adjust_tail(u64 xdp, u64 offset, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:4037
Inline: False
```
**Symbols:**

```
ffffffff81f038e1-ffffffff81f038f6: bpf_xdp_adjust_tail.cold (STB_LOCAL)
ffffffff81c3f540-ffffffff81c3f778: bpf_xdp_adjust_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
u64 bpf_xdp_adjust_tail(u64 xdp, u64 offset, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:4047
Inline: False
```
**Symbols:**

```
ffffffff820abfd4-ffffffff820abfe9: bpf_xdp_adjust_tail.cold (STB_LOCAL)
ffffffff81df3a50-ffffffff81df3c88: bpf_xdp_adjust_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 bpf_xdp_adjust_tail(u64 xdp, u64 offset, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e63460)
Location: net/core/filter.c:4103
Inline: False
```
**Symbols:**

```
ffffffff81e63460-ffffffff81e63698: bpf_xdp_adjust_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 bpf_xdp_adjust_tail(u64 xdp, u64 offset, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f27b80)
Location: net/core/filter.c:4168
Inline: False
```
**Symbols:**

```
ffffffff81f27b80-ffffffff81f27d03: bpf_xdp_adjust_tail (STB_GLOBAL)
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
u64 bpf_xdp_adjust_tail(u64 xdp, u64 offset, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010bf6ba8)
Location: net/core/filter.c:3410
Inline: False
```
**Symbols:**

```
ffff800010bf6ba8-ffff800010bf6c04: bpf_xdp_adjust_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 bpf_xdp_adjust_tail(u64 xdp, u64 offset, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d0fdf4)
Location: net/core/filter.c:3410
Inline: False
```
**Symbols:**

```
c0d0fdf4-c0d0fe44: bpf_xdp_adjust_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 bpf_xdp_adjust_tail(u64 xdp, u64 offset, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000cdc6a0)
Location: net/core/filter.c:3410
Inline: False
```
**Symbols:**

```
c000000000cdc6a0-c000000000cdc6e8: bpf_xdp_adjust_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 bpf_xdp_adjust_tail(u64 xdp, u64 offset, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe000778284)
Location: net/core/filter.c:3410
Inline: False
```
**Symbols:**

```
ffffffe000778284-ffffffe0007782d6: bpf_xdp_adjust_tail (STB_GLOBAL)
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
u64 bpf_xdp_adjust_tail(u64 xdp, u64 offset, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818f5080)
Location: net/core/filter.c:3410
Inline: False
```
**Symbols:**

```
ffffffff818f5080-ffffffff818f50b1: bpf_xdp_adjust_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 bpf_xdp_adjust_tail(u64 xdp, u64 offset, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818aeeb0)
Location: net/core/filter.c:3410
Inline: False
```
**Symbols:**

```
ffffffff818aeeb0-ffffffff818aeee1: bpf_xdp_adjust_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 bpf_xdp_adjust_tail(u64 xdp, u64 offset, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff819460b0)
Location: net/core/filter.c:3410
Inline: False
```
**Symbols:**

```
ffffffff819460b0-ffffffff819460e1: bpf_xdp_adjust_tail (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 bpf_xdp_adjust_tail(u64 xdp, u64 offset, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff819679a0)
Location: net/core/filter.c:3410
Inline: False
```
**Symbols:**

```
ffffffff819679a0-ffffffff819679d1: bpf_xdp_adjust_tail (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
