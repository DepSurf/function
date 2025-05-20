# Function: <code>xsk_flush</code>

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
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void xsk_flush(struct xdp_sock *xs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff819cc984)
Location: net/xdp/xsk.c:106
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_generic_rcv
Direct callers:
  - kernel/bpf/xskmap.c:__xsk_map_flush
```
**Symbols:**

```
ffffffff819cc840-ffffffff819cc86a: xsk_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void xsk_flush(struct xdp_sock *xs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81a05a2d)
Location: net/xdp/xsk.c:116
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_generic_rcv
Direct callers:
  - kernel/bpf/xskmap.c:__xsk_map_flush
```
**Symbols:**

```
ffffffff81a058d0-ffffffff81a058fa: xsk_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void xsk_flush(struct xdp_sock *xs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81a751b0)
Location: net/xdp/xsk.c:118
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:__xsk_map_flush
```
**Symbols:**

```
ffffffff81a751b0-ffffffff81a751da: xsk_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void xsk_flush(struct xdp_sock *xs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81aabfb0)
Location: net/xdp/xsk.c:215
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:__xsk_map_flush
```
**Symbols:**

```
ffffffff81aabfb0-ffffffff81aabfda: xsk_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ba81b7)
Location: net/xdp/xsk.c:208
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_map_flush
  - net/xdp/xsk.c:xsk_generic_rcv
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81bb7eeb)
Location: net/xdp/xsk.c:252
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_map_flush
  - net/xdp/xsk.c:xsk_generic_rcv
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
In net/xdp/xsk.c (ffffffff81ba70c7)
Location: net/xdp/xsk.c:244
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_map_flush
  - net/xdp/xsk.c:xsk_generic_rcv
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
In net/xdp/xsk.c (ffffffff81c74d47)
Location: net/xdp/xsk.c:244
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_map_flush
  - net/xdp/xsk.c:xsk_generic_rcv
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
In net/xdp/xsk.c (ffffffff81e18e17)
Location: net/xdp/xsk.c:229
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_map_flush
  - net/xdp/xsk.c:xsk_generic_rcv
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
In net/xdp/xsk.c (ffffffff81ff00c7)
Location: net/xdp/xsk.c:229
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_map_flush
  - net/xdp/xsk.c:xsk_generic_rcv
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
In net/xdp/xsk.c (ffffffff8206c267)
Location: net/xdp/xsk.c:230
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_map_flush
  - net/xdp/xsk.c:xsk_generic_rcv
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
In net/xdp/xsk.c (ffffffff82140047)
Location: net/xdp/xsk.c:331
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_map_flush
  - net/xdp/xsk.c:xsk_generic_rcv
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
void xsk_flush(struct xdp_sock *xs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffff800010d806c8)
Location: net/xdp/xsk.c:215
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:__xsk_map_flush
```
**Symbols:**

```
ffff800010d806c8-ffff800010d80710: xsk_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void xsk_flush(struct xdp_sock *xs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (c0e7ac18)
Location: net/xdp/xsk.c:215
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:__xsk_map_flush
```
**Symbols:**

```
c0e7ac18-c0e7ac50: xsk_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void xsk_flush(struct xdp_sock *xs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (c000000000ec0360)
Location: net/xdp/xsk.c:215
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:__xsk_map_flush
```
**Symbols:**

```
c000000000ec0360-c000000000ec03b8: xsk_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void xsk_flush(struct xdp_sock *xs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffe0008acea0)
Location: net/xdp/xsk.c:215
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:__xsk_map_flush
```
**Symbols:**

```
ffffffe0008acea0-ffffffe0008aced8: xsk_flush (STB_GLOBAL)
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
void xsk_flush(struct xdp_sock *xs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81a4b340)
Location: net/xdp/xsk.c:215
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:__xsk_map_flush
```
**Symbols:**

```
ffffffff81a4b340-ffffffff81a4b36a: xsk_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void xsk_flush(struct xdp_sock *xs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81a07f30)
Location: net/xdp/xsk.c:215
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:__xsk_map_flush
```
**Symbols:**

```
ffffffff81a07f30-ffffffff81a07f5a: xsk_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void xsk_flush(struct xdp_sock *xs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ab71f0)
Location: net/xdp/xsk.c:215
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:__xsk_map_flush
```
**Symbols:**

```
ffffffff81ab71f0-ffffffff81ab721a: xsk_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void xsk_flush(struct xdp_sock *xs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ac3610)
Location: net/xdp/xsk.c:215
Inline: False
Direct callers:
  - kernel/bpf/xskmap.c:__xsk_map_flush
```
**Symbols:**

```
ffffffff81ac3610-ffffffff81ac363a: xsk_flush (STB_GLOBAL)
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
