# Function: <code>bpf_getsockopt</code>

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
u64 bpf_getsockopt(u64 bpf_sock, u64 level, u64 optname, u64 optval, u64 optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81864d70)
Location: net/core/filter.c:3289
Inline: False
```
**Symbols:**

```
ffffffff81864d70-ffffffff81864df1: bpf_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 bpf_getsockopt(u64 bpf_sock, u64 level, u64 optname, u64 optval, u64 optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b1ff0)
Location: net/core/filter.c:3980
Inline: False
```
**Symbols:**

```
ffffffff818b1ff0-ffffffff818b20e7: bpf_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 bpf_getsockopt(u64 bpf_sock, u64 level, u64 optname, u64 optval, u64 optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818d6b30)
Location: net/core/filter.c:4253
Inline: False
```
**Symbols:**

```
ffffffff818d6b30-ffffffff818d6c60: bpf_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 bpf_getsockopt(u64 bpf_sock, u64 level, u64 optname, u64 optval, u64 optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff819243a0)
Location: net/core/filter.c:4390
Inline: False
```
**Symbols:**

```
ffffffff819243a0-ffffffff819244c0: bpf_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 bpf_getsockopt(u64 bpf_sock, u64 level, u64 optname, u64 optval, u64 optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff819566b0)
Location: net/core/filter.c:4399
Inline: False
```
**Symbols:**

```
ffffffff819566b0-ffffffff819567d0: bpf_getsockopt (STB_GLOBAL)
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
u64 bpf_getsockopt(u64 bpf_sock, u64 level, u64 optname, u64 optval, u64 optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010bf7ec8)
Location: net/core/filter.c:4399
Inline: False
```
**Symbols:**

```
ffff800010bf7ec8-ffff800010bf8058: bpf_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 bpf_getsockopt(u64 bpf_sock, u64 level, u64 optname, u64 optval, u64 optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d119a0)
Location: net/core/filter.c:4399
Inline: False
```
**Symbols:**

```
c0d119a0-c0d11b1c: bpf_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 bpf_getsockopt(u64 bpf_sock, u64 level, u64 optname, u64 optval, u64 optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000cde880)
Location: net/core/filter.c:4399
Inline: False
```
**Symbols:**

```
c000000000cde880-c000000000cdea70: bpf_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 bpf_getsockopt(u64 bpf_sock, u64 level, u64 optname, u64 optval, u64 optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe00077994e)
Location: net/core/filter.c:4399
Inline: False
```
**Symbols:**

```
ffffffe00077994e-ffffffe000779a8e: bpf_getsockopt (STB_GLOBAL)
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
u64 bpf_getsockopt(u64 bpf_sock, u64 level, u64 optname, u64 optval, u64 optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818f6680)
Location: net/core/filter.c:4399
Inline: False
```
**Symbols:**

```
ffffffff818f6680-ffffffff818f67a0: bpf_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 bpf_getsockopt(u64 bpf_sock, u64 level, u64 optname, u64 optval, u64 optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b04b0)
Location: net/core/filter.c:4399
Inline: False
```
**Symbols:**

```
ffffffff818b04b0-ffffffff818b05d0: bpf_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 bpf_getsockopt(u64 bpf_sock, u64 level, u64 optname, u64 optval, u64 optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff819476b0)
Location: net/core/filter.c:4399
Inline: False
```
**Symbols:**

```
ffffffff819476b0-ffffffff819477d0: bpf_getsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 bpf_getsockopt(u64 bpf_sock, u64 level, u64 optname, u64 optval, u64 optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81968fc0)
Location: net/core/filter.c:4399
Inline: False
```
**Symbols:**

```
ffffffff81968fc0-ffffffff819690e0: bpf_getsockopt (STB_GLOBAL)
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
