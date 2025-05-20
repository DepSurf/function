# Function: <code>bpf_sock_ops_setsockopt</code>

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
u64 bpf_sock_ops_setsockopt(u64 bpf_sock, u64 level, u64 optname, u64 optval, u64 optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2a430)
Location: net/core/filter.c:4572
Inline: False
```
**Symbols:**

```
ffffffff81a2a430-ffffffff81a2a450: bpf_sock_ops_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 bpf_sock_ops_setsockopt(u64 bpf_sock, u64 level, u64 optname, u64 optval, u64 optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2af70)
Location: net/core/filter.c:5030
Inline: False
```
**Symbols:**

```
ffffffff81a2af70-ffffffff81a2af85: bpf_sock_ops_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 bpf_sock_ops_setsockopt(u64 bpf_sock, u64 level, u64 optname, u64 optval, u64 optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a12180)
Location: net/core/filter.c:5006
Inline: False
```
**Symbols:**

```
ffffffff81a12180-ffffffff81a12195: bpf_sock_ops_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 bpf_sock_ops_setsockopt(u64 bpf_sock, u64 level, u64 optname, u64 optval, u64 optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81acd550)
Location: net/core/filter.c:5130
Inline: False
```
**Symbols:**

```
ffffffff81acd550-ffffffff81acd565: bpf_sock_ops_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 bpf_sock_ops_setsockopt(u64 bpf_sock, u64 level, u64 optname, u64 optval, u64 optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c4ae70)
Location: net/core/filter.c:5439
Inline: False
```
**Symbols:**

```
ffffffff81c4ae70-ffffffff81c4ae94: bpf_sock_ops_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
u64 bpf_sock_ops_setsockopt(u64 bpf_sock, u64 level, u64 optname, u64 optval, u64 optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:5444
Inline: False
```
**Symbols:**

```
ffffffff820ac52f-ffffffff820ac558: bpf_sock_ops_setsockopt.cold (STB_LOCAL)
ffffffff81dfcf20-ffffffff81dfcf70: bpf_sock_ops_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
u64 bpf_sock_ops_setsockopt(u64 bpf_sock, u64 level, u64 optname, u64 optval, u64 optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:5498
Inline: False
```
**Symbols:**

```
ffffffff8212daef-ffffffff8212db18: bpf_sock_ops_setsockopt.cold (STB_LOCAL)
ffffffff81e6d620-ffffffff81e6d670: bpf_sock_ops_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u64 bpf_sock_ops_setsockopt(u64 bpf_sock, u64 level, u64 optname, u64 optval, u64 optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:5572
Inline: False
```
**Symbols:**

```
ffffffff8220f84d-ffffffff8220f876: bpf_sock_ops_setsockopt.cold (STB_LOCAL)
ffffffff81f2ccd0-ffffffff81f2cd20: bpf_sock_ops_setsockopt (STB_GLOBAL)
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
