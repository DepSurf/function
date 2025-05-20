# Function: <code>reuseport_attach_prog</code>

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
struct bpf_prog *reuseport_attach_prog(struct sock *sk, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff8179fea0)
Location: net/core/sock_reuseport.c:243
Inline: False
Direct callers:
  - net/core/filter.c:__reuseport_attach_prog
```
**Symbols:**

```
ffffffff8179fea0-ffffffff8179fee1: reuseport_attach_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct bpf_prog *reuseport_attach_prog(struct sock *sk, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff817ce870)
Location: net/core/sock_reuseport.c:242
Inline: False
Direct callers:
  - net/core/filter.c:__reuseport_attach_prog
```
**Symbols:**

```
ffffffff817ce870-ffffffff817ce8b1: reuseport_attach_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct bpf_prog *reuseport_attach_prog(struct sock *sk, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff817edd10)
Location: net/core/sock_reuseport.c:242
Inline: False
Direct callers:
  - net/core/filter.c:__reuseport_attach_prog
```
**Symbols:**

```
ffffffff817edd10-ffffffff817edd51: reuseport_attach_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct bpf_prog *reuseport_attach_prog(struct sock *sk, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81869f50)
Location: net/core/sock_reuseport.c:254
Inline: False
Direct callers:
  - net/core/filter.c:__reuseport_attach_prog
```
**Symbols:**

```
ffffffff81869f50-ffffffff81869f91: reuseport_attach_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct bpf_prog *reuseport_attach_prog(struct sock *sk, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff818b9c30)
Location: net/core/sock_reuseport.c:256
Inline: False
Direct callers:
  - net/core/filter.c:__reuseport_attach_prog
```
**Symbols:**

```
ffffffff818b9c30-ffffffff818b9c71: reuseport_attach_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int reuseport_attach_prog(struct sock *sk, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff818e0da0)
Location: net/core/sock_reuseport.c:306
Inline: False
Direct callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_filter
```
**Symbols:**

```
ffffffff818e0da0-ffffffff818e0e15: reuseport_attach_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int reuseport_attach_prog(struct sock *sk, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff8192f570)
Location: net/core/sock_reuseport.c:319
Inline: False
Direct callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_filter
```
**Symbols:**

```
ffffffff8192f570-ffffffff8192f5e9: reuseport_attach_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int reuseport_attach_prog(struct sock *sk, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff819617e0)
Location: net/core/sock_reuseport.c:319
Inline: False
Direct callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_filter
```
**Symbols:**

```
ffffffff819617e0-ffffffff81961859: reuseport_attach_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int reuseport_attach_prog(struct sock *sk, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81a34e10)
Location: net/core/sock_reuseport.c:311
Inline: False
Direct callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_filter
```
**Symbols:**

```
ffffffff81a34e10-ffffffff81a34e89: reuseport_attach_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int reuseport_attach_prog(struct sock *sk, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81a37150)
Location: net/core/sock_reuseport.c:311
Inline: False
Direct callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_filter
```
**Symbols:**

```
ffffffff81a37150-ffffffff81a371c9: reuseport_attach_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int reuseport_attach_prog(struct sock *sk, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81a1e2b0)
Location: net/core/sock_reuseport.c:311
Inline: False
Direct callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_filter
```
**Symbols:**

```
ffffffff81a1e2b0-ffffffff81a1e329: reuseport_attach_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int reuseport_attach_prog(struct sock *sk, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81ad23d0)
Location: net/core/sock_reuseport.c:584
Inline: False
Direct callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_filter
```
**Symbols:**

```
ffffffff81ad23d0-ffffffff81ad2449: reuseport_attach_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int reuseport_attach_prog(struct sock *sk, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81c4fdc0)
Location: net/core/sock_reuseport.c:584
Inline: False
Direct callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_filter
```
**Symbols:**

```
ffffffff81c4fdc0-ffffffff81c4fe3d: reuseport_attach_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int reuseport_attach_prog(struct sock *sk, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81e05020)
Location: net/core/sock_reuseport.c:684
Inline: False
Direct callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_filter
```
**Symbols:**

```
ffffffff81e05020-ffffffff81e0509d: reuseport_attach_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int reuseport_attach_prog(struct sock *sk, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81e77870)
Location: net/core/sock_reuseport.c:684
Inline: False
Direct callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_filter
```
**Symbols:**

```
ffffffff81e77870-ffffffff81e778ed: reuseport_attach_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int reuseport_attach_prog(struct sock *sk, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81f37830)
Location: net/core/sock_reuseport.c:684
Inline: False
Direct callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_filter
```
**Symbols:**

```
ffffffff81f37830-ffffffff81f378ad: reuseport_attach_prog (STB_GLOBAL)
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
int reuseport_attach_prog(struct sock *sk, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffff800010c05268)
Location: net/core/sock_reuseport.c:319
Inline: False
Direct callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_filter
```
**Symbols:**

```
ffff800010c05268-ffff800010c05364: reuseport_attach_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int reuseport_attach_prog(struct sock *sk, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (c0d1e574)
Location: net/core/sock_reuseport.c:319
Inline: False
Direct callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_filter
```
**Symbols:**

```
c0d1e574-c0d1e604: reuseport_attach_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int reuseport_attach_prog(struct sock *sk, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (c000000000cef430)
Location: net/core/sock_reuseport.c:319
Inline: False
Direct callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_filter
```
**Symbols:**

```
c000000000cef430-c000000000cef4f8: reuseport_attach_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int reuseport_attach_prog(struct sock *sk, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffe000783c5e)
Location: net/core/sock_reuseport.c:319
Inline: False
Direct callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_filter
```
**Symbols:**

```
ffffffe000783c5e-ffffffe000783ce4: reuseport_attach_prog (STB_GLOBAL)
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
int reuseport_attach_prog(struct sock *sk, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff819017b0)
Location: net/core/sock_reuseport.c:319
Inline: False
Direct callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_filter
```
**Symbols:**

```
ffffffff819017b0-ffffffff81901829: reuseport_attach_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int reuseport_attach_prog(struct sock *sk, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff818bb5e0)
Location: net/core/sock_reuseport.c:319
Inline: False
Direct callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_filter
```
**Symbols:**

```
ffffffff818bb5e0-ffffffff818bb659: reuseport_attach_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int reuseport_attach_prog(struct sock *sk, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff819527e0)
Location: net/core/sock_reuseport.c:319
Inline: False
Direct callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_filter
```
**Symbols:**

```
ffffffff819527e0-ffffffff81952859: reuseport_attach_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int reuseport_attach_prog(struct sock *sk, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81974250)
Location: net/core/sock_reuseport.c:319
Inline: False
Direct callers:
  - net/core/filter.c:sk_reuseport_attach_bpf
  - net/core/filter.c:sk_reuseport_attach_filter
```
**Symbols:**

```
ffffffff81974250-ffffffff819742c9: reuseport_attach_prog (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>struct bpf_prog *</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
