# Function: <code>bpf_setsockopt</code>

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
u64 bpf_setsockopt(u64 bpf_sock, u64 level, u64 optname, u64 optval, u64 optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817e9670)
Location: net/core/filter.c:2790
Inline: False
```
**Symbols:**

```
ffffffff817e9670-ffffffff817e985f: bpf_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 bpf_setsockopt(u64 bpf_sock, u64 level, u64 optname, u64 optval, u64 optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81864b70)
Location: net/core/filter.c:3189
Inline: False
```
**Symbols:**

```
ffffffff81864b70-ffffffff81864d65: bpf_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
u64 bpf_setsockopt(u64 bpf_sock, u64 level, u64 optname, u64 optval, u64 optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:3835
Inline: False
```
**Symbols:**

```
ffffffff818b8790-ffffffff818b879c: bpf_setsockopt.cold.93 (STB_LOCAL)
ffffffff818b1d40-ffffffff818b1fe4: bpf_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
u64 bpf_setsockopt(u64 bpf_sock, u64 level, u64 optname, u64 optval, u64 optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:4093
Inline: False
```
**Symbols:**

```
ffffffff818df3e8-ffffffff818df3f4: bpf_setsockopt.cold.100 (STB_LOCAL)
ffffffff818d67c0-ffffffff818d6b30: bpf_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
u64 bpf_setsockopt(u64 bpf_sock, u64 level, u64 optname, u64 optval, u64 optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:4230
Inline: False
```
**Symbols:**

```
ffffffff8192d9b2-ffffffff8192d9be: bpf_setsockopt.cold (STB_LOCAL)
ffffffff81923ff0-ffffffff8192439d: bpf_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
u64 bpf_setsockopt(u64 bpf_sock, u64 level, u64 optname, u64 optval, u64 optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:4237
Inline: False
```
**Symbols:**

```
ffffffff8195fcb2-ffffffff8195fcbe: bpf_setsockopt.cold (STB_LOCAL)
ffffffff81956300-ffffffff819566ad: bpf_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
u64 bpf_setsockopt(u64 bpf_sock, u64 level, u64 optname, u64 optval, u64 optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010bfdc80)
Location: net/core/filter.c:4237
Inline: False
```
**Symbols:**

```
ffff800010bfdc80-ffff800010bfe078: bpf_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 bpf_setsockopt(u64 bpf_sock, u64 level, u64 optname, u64 optval, u64 optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d14b6c)
Location: net/core/filter.c:4237
Inline: False
```
**Symbols:**

```
c0d14b6c-c0d14fc8: bpf_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 bpf_setsockopt(u64 bpf_sock, u64 level, u64 optname, u64 optval, u64 optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000cde360)
Location: net/core/filter.c:4237
Inline: False
```
**Symbols:**

```
c000000000cde360-c000000000cde880: bpf_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 bpf_setsockopt(u64 bpf_sock, u64 level, u64 optname, u64 optval, u64 optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe000779a8e)
Location: net/core/filter.c:4237
Inline: False
```
**Symbols:**

```
ffffffe000779a8e-ffffffe000779d7a: bpf_setsockopt (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
u64 bpf_setsockopt(u64 bpf_sock, u64 level, u64 optname, u64 optval, u64 optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:4237
Inline: False
```
**Symbols:**

```
ffffffff818ffc82-ffffffff818ffc8e: bpf_setsockopt.cold (STB_LOCAL)
ffffffff818f62d0-ffffffff818f667d: bpf_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
u64 bpf_setsockopt(u64 bpf_sock, u64 level, u64 optname, u64 optval, u64 optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:4237
Inline: False
```
**Symbols:**

```
ffffffff818b9ab2-ffffffff818b9abe: bpf_setsockopt.cold (STB_LOCAL)
ffffffff818b0100-ffffffff818b04ad: bpf_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
u64 bpf_setsockopt(u64 bpf_sock, u64 level, u64 optname, u64 optval, u64 optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:4237
Inline: False
```
**Symbols:**

```
ffffffff81950cb2-ffffffff81950cbe: bpf_setsockopt.cold (STB_LOCAL)
ffffffff81947300-ffffffff819476ad: bpf_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
u64 bpf_setsockopt(u64 bpf_sock, u64 level, u64 optname, u64 optval, u64 optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:4237
Inline: False
```
**Symbols:**

```
ffffffff81972682-ffffffff8197268e: bpf_setsockopt.cold (STB_LOCAL)
ffffffff81968c10-ffffffff81968fbd: bpf_setsockopt (STB_GLOBAL)
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
