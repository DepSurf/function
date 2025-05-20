# Function: <code>bpf_csum_diff</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u64 bpf_csum_diff(u64 r1, u64 from_size, u64 r3, u64 to_size, u64 seed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8179c580)
Location: net/core/filter.c:1547
Inline: False
```
**Symbols:**

```
ffffffff8179c580-ffffffff8179c624: bpf_csum_diff (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u64 bpf_csum_diff(u64 from, u64 from_size, u64 to, u64 to_size, u64 seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817ca2a0)
Location: net/core/filter.c:1572
Inline: False
```
**Symbols:**

```
ffffffff817ca2a0-ffffffff817ca33f: bpf_csum_diff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 bpf_csum_diff(u64 from, u64 from_size, u64 to, u64 to_size, u64 seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817e9230)
Location: net/core/filter.c:1598
Inline: False
```
**Symbols:**

```
ffffffff817e9230-ffffffff817e92d1: bpf_csum_diff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 bpf_csum_diff(u64 from, u64 from_size, u64 to, u64 to_size, u64 seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81864630)
Location: net/core/filter.c:1619
Inline: False
```
**Symbols:**

```
ffffffff81864630-ffffffff818646d1: bpf_csum_diff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 bpf_csum_diff(u64 from, u64 from_size, u64 to, u64 to_size, u64 seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b1690)
Location: net/core/filter.c:1905
Inline: False
```
**Symbols:**

```
ffffffff818b1690-ffffffff818b1730: bpf_csum_diff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 bpf_csum_diff(u64 from, u64 from_size, u64 to, u64 to_size, u64 seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818d61c0)
Location: net/core/filter.c:1924
Inline: False
```
**Symbols:**

```
ffffffff818d61c0-ffffffff818d6260: bpf_csum_diff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 bpf_csum_diff(u64 from, u64 from_size, u64 to, u64 to_size, u64 seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81923980)
Location: net/core/filter.c:1970
Inline: False
```
**Symbols:**

```
ffffffff81923980-ffffffff81923a22: bpf_csum_diff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 bpf_csum_diff(u64 from, u64 from_size, u64 to, u64 to_size, u64 seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81955bb0)
Location: net/core/filter.c:1970
Inline: False
```
**Symbols:**

```
ffffffff81955bb0-ffffffff81955c52: bpf_csum_diff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 bpf_csum_diff(u64 from, u64 from_size, u64 to, u64 to_size, u64 seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a296c0)
Location: net/core/filter.c:1961
Inline: False
```
**Symbols:**

```
ffffffff81a296c0-ffffffff81a29763: bpf_csum_diff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 bpf_csum_diff(u64 from, u64 from_size, u64 to, u64 to_size, u64 seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a29f10)
Location: net/core/filter.c:1991
Inline: False
```
**Symbols:**

```
ffffffff81a29f10-ffffffff81a29fb3: bpf_csum_diff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 bpf_csum_diff(u64 from, u64 from_size, u64 to, u64 to_size, u64 seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a11160)
Location: net/core/filter.c:1988
Inline: False
```
**Symbols:**

```
ffffffff81a11160-ffffffff81a11204: bpf_csum_diff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 bpf_csum_diff(u64 from, u64 from_size, u64 to, u64 to_size, u64 seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81ac2760)
Location: net/core/filter.c:1989
Inline: False
```
**Symbols:**

```
ffffffff81ac2760-ffffffff81ac2804: bpf_csum_diff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 bpf_csum_diff(u64 from, u64 from_size, u64 to, u64 to_size, u64 seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c3d1e0)
Location: net/core/filter.c:1990
Inline: False
```
**Symbols:**

```
ffffffff81c3d1e0-ffffffff81c3d2be: bpf_csum_diff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 bpf_csum_diff(u64 from, u64 from_size, u64 to, u64 to_size, u64 seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81df15a0)
Location: net/core/filter.c:1992
Inline: False
```
**Symbols:**

```
ffffffff81df15a0-ffffffff81df167e: bpf_csum_diff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 bpf_csum_diff(u64 from, u64 from_size, u64 to, u64 to_size, u64 seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e63230)
Location: net/core/filter.c:2003
Inline: False
```
**Symbols:**

```
ffffffff81e63230-ffffffff81e633bc: bpf_csum_diff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 bpf_csum_diff(u64 from, u64 from_size, u64 to, u64 to_size, u64 seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f22670)
Location: net/core/filter.c:2010
Inline: False
```
**Symbols:**

```
ffffffff81f22670-ffffffff81f227fc: bpf_csum_diff (STB_GLOBAL)
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
u64 bpf_csum_diff(u64 from, u64 from_size, u64 to, u64 to_size, u64 seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010c00140)
Location: net/core/filter.c:1970
Inline: False
```
**Symbols:**

```
ffff800010c00140-ffff800010c00244: bpf_csum_diff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 bpf_csum_diff(u64 from, u64 from_size, u64 to, u64 to_size, u64 seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d1116c)
Location: net/core/filter.c:1970
Inline: False
```
**Symbols:**

```
c0d1116c-c0d11238: bpf_csum_diff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 bpf_csum_diff(u64 from, u64 from_size, u64 to, u64 to_size, u64 seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000ce67a0)
Location: net/core/filter.c:1970
Inline: False
```
**Symbols:**

```
c000000000ce67a0-c000000000ce68c0: bpf_csum_diff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 bpf_csum_diff(u64 from, u64 from_size, u64 to, u64 to_size, u64 seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe00077934e)
Location: net/core/filter.c:1970
Inline: False
```
**Symbols:**

```
ffffffe00077934e-ffffffe00077942a: bpf_csum_diff (STB_GLOBAL)
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
u64 bpf_csum_diff(u64 from, u64 from_size, u64 to, u64 to_size, u64 seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818f5b80)
Location: net/core/filter.c:1970
Inline: False
```
**Symbols:**

```
ffffffff818f5b80-ffffffff818f5c22: bpf_csum_diff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 bpf_csum_diff(u64 from, u64 from_size, u64 to, u64 to_size, u64 seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818af9b0)
Location: net/core/filter.c:1970
Inline: False
```
**Symbols:**

```
ffffffff818af9b0-ffffffff818afa52: bpf_csum_diff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 bpf_csum_diff(u64 from, u64 from_size, u64 to, u64 to_size, u64 seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81946bb0)
Location: net/core/filter.c:1970
Inline: False
```
**Symbols:**

```
ffffffff81946bb0-ffffffff81946c52: bpf_csum_diff (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 bpf_csum_diff(u64 from, u64 from_size, u64 to, u64 to_size, u64 seed);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff819684c0)
Location: net/core/filter.c:1970
Inline: False
```
**Symbols:**

```
ffffffff819684c0-ffffffff81968562: bpf_csum_diff (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 from</code>
</li>
<li>
<b>Param added. </b>
<code>u64 to</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r1</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r3</code>
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
