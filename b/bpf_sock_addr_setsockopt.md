# Function: <code>bpf_sock_addr_setsockopt</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 bpf_sock_addr_setsockopt(u64 ctx, u64 level, u64 optname, u64 optval, u64 optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2a410)
Location: net/core/filter.c:4536
Inline: False
```
**Symbols:**

```
ffffffff81a2a410-ffffffff81a2a428: bpf_sock_addr_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 bpf_sock_addr_setsockopt(u64 ctx, u64 level, u64 optname, u64 optval, u64 optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2af50)
Location: net/core/filter.c:4996
Inline: False
```
**Symbols:**

```
ffffffff81a2af50-ffffffff81a2af65: bpf_sock_addr_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 bpf_sock_addr_setsockopt(u64 ctx, u64 level, u64 optname, u64 optval, u64 optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a12160)
Location: net/core/filter.c:4972
Inline: False
```
**Symbols:**

```
ffffffff81a12160-ffffffff81a12175: bpf_sock_addr_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 bpf_sock_addr_setsockopt(u64 ctx, u64 level, u64 optname, u64 optval, u64 optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81acd530)
Location: net/core/filter.c:5096
Inline: False
```
**Symbols:**

```
ffffffff81acd530-ffffffff81acd545: bpf_sock_addr_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 bpf_sock_addr_setsockopt(u64 ctx, u64 level, u64 optname, u64 optval, u64 optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c4ae40)
Location: net/core/filter.c:5405
Inline: False
```
**Symbols:**

```
ffffffff81c4ae40-ffffffff81c4ae64: bpf_sock_addr_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
u64 bpf_sock_addr_setsockopt(u64 ctx, u64 level, u64 optname, u64 optval, u64 optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:5410
Inline: False
```
**Symbols:**

```
ffffffff820ac581-ffffffff820ac5aa: bpf_sock_addr_setsockopt.cold (STB_LOCAL)
ffffffff81dfcff0-ffffffff81dfd040: bpf_sock_addr_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
u64 bpf_sock_addr_setsockopt(u64 ctx, u64 level, u64 optname, u64 optval, u64 optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:5464
Inline: False
```
**Symbols:**

```
ffffffff8212db41-ffffffff8212db6a: bpf_sock_addr_setsockopt.cold (STB_LOCAL)
ffffffff81e6d6f0-ffffffff81e6d740: bpf_sock_addr_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u64 bpf_sock_addr_setsockopt(u64 ctx, u64 level, u64 optname, u64 optval, u64 optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:5538
Inline: False
```
**Symbols:**

```
ffffffff8220f89f-ffffffff8220f8c8: bpf_sock_addr_setsockopt.cold (STB_LOCAL)
ffffffff81f2cda0-ffffffff81f2cdf0: bpf_sock_addr_setsockopt (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
