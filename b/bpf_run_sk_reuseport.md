# Function: <code>bpf_run_sk_reuseport</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sock *bpf_run_sk_reuseport(struct sock_reuseport *reuse, struct sock *sk, struct bpf_prog *prog, struct sk_buff *skb, u32 hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818df360)
Location: net/core/filter.c:7790
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
**Symbols:**

```
ffffffff818df360-ffffffff818df3e8: bpf_run_sk_reuseport (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sock *bpf_run_sk_reuseport(struct sock_reuseport *reuse, struct sock *sk, struct bpf_prog *prog, struct sk_buff *skb, u32 hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8192d8d0)
Location: net/core/filter.c:8612
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
**Symbols:**

```
ffffffff8192d8d0-ffffffff8192d9b2: bpf_run_sk_reuseport (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sock *bpf_run_sk_reuseport(struct sock_reuseport *reuse, struct sock *sk, struct bpf_prog *prog, struct sk_buff *skb, u32 hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8195fbd0)
Location: net/core/filter.c:8699
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
**Symbols:**

```
ffffffff8195fbd0-ffffffff8195fcb2: bpf_run_sk_reuseport (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sock *bpf_run_sk_reuseport(struct sock_reuseport *reuse, struct sock *sk, struct bpf_prog *prog, struct sk_buff *skb, u32 hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a330f0)
Location: net/core/filter.c:9009
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
**Symbols:**

```
ffffffff81a330f0-ffffffff81a331d2: bpf_run_sk_reuseport (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sock *bpf_run_sk_reuseport(struct sock_reuseport *reuse, struct sock *sk, struct bpf_prog *prog, struct sk_buff *skb, u32 hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a354b0)
Location: net/core/filter.c:9877
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
**Symbols:**

```
ffffffff81a354b0-ffffffff81a35592: bpf_run_sk_reuseport (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sock *bpf_run_sk_reuseport(struct sock_reuseport *reuse, struct sock *sk, struct bpf_prog *prog, struct sk_buff *skb, u32 hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a1c610)
Location: net/core/filter.c:10018
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
**Symbols:**

```
ffffffff81a1c610-ffffffff81a1c6eb: bpf_run_sk_reuseport (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sock *bpf_run_sk_reuseport(struct sock_reuseport *reuse, struct sock *sk, struct bpf_prog *prog, struct sk_buff *skb, struct sock *migrating_sk, u32 hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81acfdd0)
Location: net/core/filter.c:10196
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_migrate_sock
  - net/core/sock_reuseport.c:reuseport_migrate_sock
  - net/core/sock_reuseport.c:reuseport_select_sock
```
**Symbols:**

```
ffffffff81acfdd0-ffffffff81acfeab: bpf_run_sk_reuseport (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sock *bpf_run_sk_reuseport(struct sock_reuseport *reuse, struct sock *sk, struct bpf_prog *prog, struct sk_buff *skb, struct sock *migrating_sk, u32 hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c4d560)
Location: net/core/filter.c:10702
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_migrate_sock
  - net/core/sock_reuseport.c:reuseport_migrate_sock
  - net/core/sock_reuseport.c:reuseport_select_sock
```
**Symbols:**

```
ffffffff81c4d560-ffffffff81c4d665: bpf_run_sk_reuseport (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sock *bpf_run_sk_reuseport(struct sock_reuseport *reuse, struct sock *sk, struct bpf_prog *prog, struct sk_buff *skb, struct sock *migrating_sk, u32 hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e02470)
Location: net/core/filter.c:10908
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_migrate_sock
  - net/core/sock_reuseport.c:reuseport_migrate_sock
  - net/core/sock_reuseport.c:reuseport_select_sock
```
**Symbols:**

```
ffffffff81e02470-ffffffff81e02575: bpf_run_sk_reuseport (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sock *bpf_run_sk_reuseport(struct sock_reuseport *reuse, struct sock *sk, struct bpf_prog *prog, struct sk_buff *skb, struct sock *migrating_sk, u32 hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e74820)
Location: net/core/filter.c:11057
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_migrate_sock
  - net/core/sock_reuseport.c:reuseport_migrate_sock
  - net/core/sock_reuseport.c:reuseport_select_sock
```
**Symbols:**

```
ffffffff81e74820-ffffffff81e74925: bpf_run_sk_reuseport (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sock *bpf_run_sk_reuseport(struct sock_reuseport *reuse, struct sock *sk, struct bpf_prog *prog, struct sk_buff *skb, struct sock *migrating_sk, u32 hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f33fe0)
Location: net/core/filter.c:11148
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_migrate_sock
  - net/core/sock_reuseport.c:reuseport_migrate_sock
  - net/core/sock_reuseport.c:reuseport_select_sock
```
**Symbols:**

```
ffffffff81f33fe0-ffffffff81f340e5: bpf_run_sk_reuseport (STB_GLOBAL)
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
struct sock *bpf_run_sk_reuseport(struct sock_reuseport *reuse, struct sock *sk, struct bpf_prog *prog, struct sk_buff *skb, u32 hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010c03208)
Location: net/core/filter.c:8699
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
**Symbols:**

```
ffff800010c03208-ffff800010c03318: bpf_run_sk_reuseport (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sock *bpf_run_sk_reuseport(struct sock_reuseport *reuse, struct sock *sk, struct bpf_prog *prog, struct sk_buff *skb, u32 hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d1c710)
Location: net/core/filter.c:8699
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
**Symbols:**

```
c0d1c710-c0d1c870: bpf_run_sk_reuseport (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sock *bpf_run_sk_reuseport(struct sock_reuseport *reuse, struct sock *sk, struct bpf_prog *prog, struct sk_buff *skb, u32 hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000cec970)
Location: net/core/filter.c:8699
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
**Symbols:**

```
c000000000cec970-c000000000cecac0: bpf_run_sk_reuseport (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sock *bpf_run_sk_reuseport(struct sock_reuseport *reuse, struct sock *sk, struct bpf_prog *prog, struct sk_buff *skb, u32 hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe00078242a)
Location: net/core/filter.c:8699
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
**Symbols:**

```
ffffffe00078242a-ffffffe000782522: bpf_run_sk_reuseport (STB_GLOBAL)
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
struct sock *bpf_run_sk_reuseport(struct sock_reuseport *reuse, struct sock *sk, struct bpf_prog *prog, struct sk_buff *skb, u32 hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818ffba0)
Location: net/core/filter.c:8699
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
**Symbols:**

```
ffffffff818ffba0-ffffffff818ffc82: bpf_run_sk_reuseport (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sock *bpf_run_sk_reuseport(struct sock_reuseport *reuse, struct sock *sk, struct bpf_prog *prog, struct sk_buff *skb, u32 hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b99d0)
Location: net/core/filter.c:8699
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
**Symbols:**

```
ffffffff818b99d0-ffffffff818b9ab2: bpf_run_sk_reuseport (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sock *bpf_run_sk_reuseport(struct sock_reuseport *reuse, struct sock *sk, struct bpf_prog *prog, struct sk_buff *skb, u32 hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81950bd0)
Location: net/core/filter.c:8699
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
**Symbols:**

```
ffffffff81950bd0-ffffffff81950cb2: bpf_run_sk_reuseport (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sock *bpf_run_sk_reuseport(struct sock_reuseport *reuse, struct sock *sk, struct bpf_prog *prog, struct sk_buff *skb, u32 hash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff819725a0)
Location: net/core/filter.c:8699
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_select_sock
```
**Symbols:**

```
ffffffff819725a0-ffffffff81972682: bpf_run_sk_reuseport (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct sock *migrating_sk</code>
</li>
<li>
<b>Param reordered. </b>
<code>reuse, sk, prog, skb, hash</code> ➡️ <code>reuse, sk, prog, skb, migrating_sk, hash</code>
</li>
</ul>
</details>
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
