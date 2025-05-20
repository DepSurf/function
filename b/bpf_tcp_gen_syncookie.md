# Function: <code>bpf_tcp_gen_syncookie</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 bpf_tcp_gen_syncookie(u64 sk, u64 iph, u64 iph_len, u64 th, u64 th_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81956cd0)
Location: net/core/filter.c:5861
Inline: False
```
**Symbols:**

```
ffffffff81956cd0-ffffffff81956de4: bpf_tcp_gen_syncookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 bpf_tcp_gen_syncookie(u64 sk, u64 iph, u64 iph_len, u64 th, u64 th_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2a6a0)
Location: net/core/filter.c:5991
Inline: False
```
**Symbols:**

```
ffffffff81a2a6a0-ffffffff81a2a7a5: bpf_tcp_gen_syncookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 bpf_tcp_gen_syncookie(u64 sk, u64 iph, u64 iph_len, u64 th, u64 th_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2b1f0)
Location: net/core/filter.c:6543
Inline: False
```
**Symbols:**

```
ffffffff81a2b1f0-ffffffff81a2b2fe: bpf_tcp_gen_syncookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 bpf_tcp_gen_syncookie(u64 sk, u64 iph, u64 iph_len, u64 th, u64 th_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a12510)
Location: net/core/filter.c:6645
Inline: False
```
**Symbols:**

```
ffffffff81a12510-ffffffff81a1261d: bpf_tcp_gen_syncookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 bpf_tcp_gen_syncookie(u64 sk, u64 iph, u64 iph_len, u64 th, u64 th_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81ac31e0)
Location: net/core/filter.c:6769
Inline: False
```
**Symbols:**

```
ffffffff81ac31e0-ffffffff81ac32ed: bpf_tcp_gen_syncookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 bpf_tcp_gen_syncookie(u64 sk, u64 iph, u64 iph_len, u64 th, u64 th_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c3dfc0)
Location: net/core/filter.c:7108
Inline: False
```
**Symbols:**

```
ffffffff81c3dfc0-ffffffff81c3e0ec: bpf_tcp_gen_syncookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 bpf_tcp_gen_syncookie(u64 sk, u64 iph, u64 iph_len, u64 th, u64 th_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81df21f0)
Location: net/core/filter.c:7120
Inline: False
```
**Symbols:**

```
ffffffff81df21f0-ffffffff81df231c: bpf_tcp_gen_syncookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 bpf_tcp_gen_syncookie(u64 sk, u64 iph, u64 iph_len, u64 th, u64 th_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e64180)
Location: net/core/filter.c:7276
Inline: False
```
**Symbols:**

```
ffffffff81e64180-ffffffff81e642ac: bpf_tcp_gen_syncookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 bpf_tcp_gen_syncookie(u64 sk, u64 iph, u64 iph_len, u64 th, u64 th_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f23330)
Location: net/core/filter.c:7363
Inline: False
```
**Symbols:**

```
ffffffff81f23330-ffffffff81f2345c: bpf_tcp_gen_syncookie (STB_GLOBAL)
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
u64 bpf_tcp_gen_syncookie(u64 sk, u64 iph, u64 iph_len, u64 th, u64 th_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010bf8490)
Location: net/core/filter.c:5861
Inline: False
```
**Symbols:**

```
ffff800010bf8490-ffff800010bf85fc: bpf_tcp_gen_syncookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 bpf_tcp_gen_syncookie(u64 sk, u64 iph, u64 iph_len, u64 th, u64 th_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d120f4)
Location: net/core/filter.c:5861
Inline: False
```
**Symbols:**

```
c0d120f4-c0d12250: bpf_tcp_gen_syncookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 bpf_tcp_gen_syncookie(u64 sk, u64 iph, u64 iph_len, u64 th, u64 th_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000cdf280)
Location: net/core/filter.c:5861
Inline: False
```
**Symbols:**

```
c000000000cdf280-c000000000cdf408: bpf_tcp_gen_syncookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 bpf_tcp_gen_syncookie(u64 sk, u64 iph, u64 iph_len, u64 th, u64 th_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe00077a194)
Location: net/core/filter.c:5861
Inline: False
```
**Symbols:**

```
ffffffe00077a194-ffffffe00077a29a: bpf_tcp_gen_syncookie (STB_GLOBAL)
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
u64 bpf_tcp_gen_syncookie(u64 sk, u64 iph, u64 iph_len, u64 th, u64 th_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818f6ca0)
Location: net/core/filter.c:5861
Inline: False
```
**Symbols:**

```
ffffffff818f6ca0-ffffffff818f6db4: bpf_tcp_gen_syncookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 bpf_tcp_gen_syncookie(u64 sk, u64 iph, u64 iph_len, u64 th, u64 th_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b0ad0)
Location: net/core/filter.c:5861
Inline: False
```
**Symbols:**

```
ffffffff818b0ad0-ffffffff818b0be4: bpf_tcp_gen_syncookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 bpf_tcp_gen_syncookie(u64 sk, u64 iph, u64 iph_len, u64 th, u64 th_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81947cd0)
Location: net/core/filter.c:5861
Inline: False
```
**Symbols:**

```
ffffffff81947cd0-ffffffff81947de4: bpf_tcp_gen_syncookie (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 bpf_tcp_gen_syncookie(u64 sk, u64 iph, u64 iph_len, u64 th, u64 th_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff819695e0)
Location: net/core/filter.c:5861
Inline: False
```
**Symbols:**

```
ffffffff819695e0-ffffffff819696f4: bpf_tcp_gen_syncookie (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
