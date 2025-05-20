# Function: <code>xsk_rcv</code>

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
int xsk_rcv(struct xdp_sock *xs, struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff819cc600)
Location: net/xdp/xsk.c:93
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:__xsk_map_redirect
```
**Symbols:**

```
ffffffff819cc600-ffffffff819cc83d: xsk_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xsk_rcv(struct xdp_sock *xs, struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81a05670)
Location: net/xdp/xsk.c:103
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:__xsk_map_redirect
```
**Symbols:**

```
ffffffff81a05670-ffffffff81a058cd: xsk_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int xsk_rcv(struct xdp_sock *xs, struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81a74f80)
Location: net/xdp/xsk.c:105
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:__xsk_map_redirect
```
**Symbols:**

```
ffffffff81a74f80-ffffffff81a751a2: xsk_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int xsk_rcv(struct xdp_sock *xs, struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81aabc30)
Location: net/xdp/xsk.c:199
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:__xsk_map_redirect
```
**Symbols:**

```
ffffffff81aabc30-ffffffff81aabfa4: xsk_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ba812b)
Location: net/xdp/xsk.c:190
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_map_redirect
  - net/xdp/xsk.c:xsk_generic_rcv
Direct callers:
  - net/xdp/xsk.c:__xsk_map_redirect
  - net/xdp/xsk.c:xsk_generic_rcv
```
**Symbols:**

```
ffffffff81ba7580-ffffffff81ba75cf: xsk_rcv.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int xsk_rcv(struct xdp_sock *xs, struct xdp_buff *xdp, bool explicit_free);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81bb7e0b)
Location: net/xdp/xsk.c:233
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_map_redirect
  - net/xdp/xsk.c:__xsk_map_redirect
Direct callers:
  - net/xdp/xsk.c:xsk_generic_rcv
```
**Symbols:**

```
ffffffff81bb6ce0-ffffffff81bb6d51: xsk_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ba6fcf)
Location: net/xdp/xsk.c:265
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_map_redirect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81c74c4f)
Location: net/xdp/xsk.c:265
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_map_redirect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81e18cfa)
Location: net/xdp/xsk.c:250
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_map_redirect
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81feff9a)
Location: net/xdp/xsk.c:250
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_map_redirect
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff8206c13a)
Location: net/xdp/xsk.c:251
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_map_redirect
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff8213fd45)
Location: net/xdp/xsk.c:353
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_map_redirect
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
int xsk_rcv(struct xdp_sock *xs, struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffff800010d80340)
Location: net/xdp/xsk.c:199
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:__xsk_map_redirect
```
**Symbols:**

```
ffff800010d80340-ffff800010d806c4: xsk_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int xsk_rcv(struct xdp_sock *xs, struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (c0e7a714)
Location: net/xdp/xsk.c:199
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:__xsk_map_redirect
```
**Symbols:**

```
c0e7a714-c0e7ac18: xsk_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int xsk_rcv(struct xdp_sock *xs, struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (c000000000ebfec0)
Location: net/xdp/xsk.c:199
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:__xsk_map_redirect
```
**Symbols:**

```
c000000000ebfec0-c000000000ec0358: xsk_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int xsk_rcv(struct xdp_sock *xs, struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffe0008acbd4)
Location: net/xdp/xsk.c:199
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:__xsk_map_redirect
```
**Symbols:**

```
ffffffe0008acbd4-ffffffe0008acea0: xsk_rcv (STB_GLOBAL)
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
int xsk_rcv(struct xdp_sock *xs, struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81a4afc0)
Location: net/xdp/xsk.c:199
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:__xsk_map_redirect
```
**Symbols:**

```
ffffffff81a4afc0-ffffffff81a4b334: xsk_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int xsk_rcv(struct xdp_sock *xs, struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81a07bb0)
Location: net/xdp/xsk.c:199
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:__xsk_map_redirect
```
**Symbols:**

```
ffffffff81a07bb0-ffffffff81a07f24: xsk_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int xsk_rcv(struct xdp_sock *xs, struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ab6e70)
Location: net/xdp/xsk.c:199
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:__xsk_map_redirect
```
**Symbols:**

```
ffffffff81ab6e70-ffffffff81ab71e4: xsk_rcv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int xsk_rcv(struct xdp_sock *xs, struct xdp_buff *xdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ac3290)
Location: net/xdp/xsk.c:199
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:__xsk_map_redirect
```
**Symbols:**

```
ffffffff81ac3290-ffffffff81ac3604: xsk_rcv (STB_GLOBAL)
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
