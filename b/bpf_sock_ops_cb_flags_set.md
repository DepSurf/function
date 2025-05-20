# Function: <code>bpf_sock_ops_cb_flags_set</code>

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
u64 bpf_sock_ops_cb_flags_set(u64 bpf_sock, u64 argval, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818aeaa0)
Location: net/core/filter.c:4051
Inline: False
```
**Symbols:**

```
ffffffff818aeaa0-ffffffff818aeae3: bpf_sock_ops_cb_flags_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 bpf_sock_ops_cb_flags_set(u64 bpf_sock, u64 argval, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818d2de0)
Location: net/core/filter.c:4336
Inline: False
```
**Symbols:**

```
ffffffff818d2de0-ffffffff818d2e23: bpf_sock_ops_cb_flags_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 bpf_sock_ops_cb_flags_set(u64 bpf_sock, u64 argval, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8191fed0)
Location: net/core/filter.c:4473
Inline: False
```
**Symbols:**

```
ffffffff8191fed0-ffffffff8191ff0b: bpf_sock_ops_cb_flags_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 bpf_sock_ops_cb_flags_set(u64 bpf_sock, u64 argval, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81952100)
Location: net/core/filter.c:4482
Inline: False
```
**Symbols:**

```
ffffffff81952100-ffffffff8195213b: bpf_sock_ops_cb_flags_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 bpf_sock_ops_cb_flags_set(u64 bpf_sock, u64 argval, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a23330)
Location: net/core/filter.c:4610
Inline: False
```
**Symbols:**

```
ffffffff81a23330-ffffffff81a2336c: bpf_sock_ops_cb_flags_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 bpf_sock_ops_cb_flags_set(u64 bpf_sock, u64 argval, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a236c0)
Location: net/core/filter.c:5154
Inline: False
```
**Symbols:**

```
ffffffff81a236c0-ffffffff81a236fc: bpf_sock_ops_cb_flags_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 bpf_sock_ops_cb_flags_set(u64 bpf_sock, u64 argval, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a0aa80)
Location: net/core/filter.c:5130
Inline: False
```
**Symbols:**

```
ffffffff81a0aa80-ffffffff81a0aabc: bpf_sock_ops_cb_flags_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u64 bpf_sock_ops_cb_flags_set(u64 bpf_sock, u64 argval, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:5254
Inline: False
```
**Symbols:**

```
ffffffff81d371f1-ffffffff81d37211: bpf_sock_ops_cb_flags_set.cold (STB_LOCAL)
ffffffff81ac8dc0-ffffffff81ac8e1f: bpf_sock_ops_cb_flags_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u64 bpf_sock_ops_cb_flags_set(u64 bpf_sock, u64 argval, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:5563
Inline: False
```
**Symbols:**

```
ffffffff81f03b41-ffffffff81f03b61: bpf_sock_ops_cb_flags_set.cold (STB_LOCAL)
ffffffff81c45fa0-ffffffff81c4600b: bpf_sock_ops_cb_flags_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
u64 bpf_sock_ops_cb_flags_set(u64 bpf_sock, u64 argval, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:5568
Inline: False
```
**Symbols:**

```
ffffffff820ac1cf-ffffffff820ac1ef: bpf_sock_ops_cb_flags_set.cold (STB_LOCAL)
ffffffff81dfa2f0-ffffffff81dfa35b: bpf_sock_ops_cb_flags_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
u64 bpf_sock_ops_cb_flags_set(u64 bpf_sock, u64 argval, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:5622
Inline: False
```
**Symbols:**

```
ffffffff8212d928-ffffffff8212d955: bpf_sock_ops_cb_flags_set.cold (STB_LOCAL)
ffffffff81e6ba70-ffffffff81e6bac6: bpf_sock_ops_cb_flags_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u64 bpf_sock_ops_cb_flags_set(u64 bpf_sock, u64 argval, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:5696
Inline: False
```
**Symbols:**

```
ffffffff8220f686-ffffffff8220f6b3: bpf_sock_ops_cb_flags_set.cold (STB_LOCAL)
ffffffff81f2a850-ffffffff81f2a8a6: bpf_sock_ops_cb_flags_set (STB_GLOBAL)
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
u64 bpf_sock_ops_cb_flags_set(u64 bpf_sock, u64 argval, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010bf4310)
Location: net/core/filter.c:4482
Inline: False
```
**Symbols:**

```
ffff800010bf4310-ffff800010bf4374: bpf_sock_ops_cb_flags_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 bpf_sock_ops_cb_flags_set(u64 bpf_sock, u64 argval, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d0cac0)
Location: net/core/filter.c:4482
Inline: False
```
**Symbols:**

```
c0d0cac0-c0d0cb04: bpf_sock_ops_cb_flags_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 bpf_sock_ops_cb_flags_set(u64 bpf_sock, u64 argval, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000cd9470)
Location: net/core/filter.c:4482
Inline: False
```
**Symbols:**

```
c000000000cd9470-c000000000cd94b8: bpf_sock_ops_cb_flags_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 bpf_sock_ops_cb_flags_set(u64 bpf_sock, u64 argval, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe000775780)
Location: net/core/filter.c:4482
Inline: False
```
**Symbols:**

```
ffffffe000775780-ffffffe0007757de: bpf_sock_ops_cb_flags_set (STB_GLOBAL)
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
u64 bpf_sock_ops_cb_flags_set(u64 bpf_sock, u64 argval, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818f20d0)
Location: net/core/filter.c:4482
Inline: False
```
**Symbols:**

```
ffffffff818f20d0-ffffffff818f210b: bpf_sock_ops_cb_flags_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 bpf_sock_ops_cb_flags_set(u64 bpf_sock, u64 argval, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818abf00)
Location: net/core/filter.c:4482
Inline: False
```
**Symbols:**

```
ffffffff818abf00-ffffffff818abf3b: bpf_sock_ops_cb_flags_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 bpf_sock_ops_cb_flags_set(u64 bpf_sock, u64 argval, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81943100)
Location: net/core/filter.c:4482
Inline: False
```
**Symbols:**

```
ffffffff81943100-ffffffff8194313b: bpf_sock_ops_cb_flags_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 bpf_sock_ops_cb_flags_set(u64 bpf_sock, u64 argval, u64 __ur_1, u64 __ur_2, u64 __ur_3);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff819649f0)
Location: net/core/filter.c:4482
Inline: False
```
**Symbols:**

```
ffffffff819649f0-ffffffff81964a2b: bpf_sock_ops_cb_flags_set (STB_GLOBAL)
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
