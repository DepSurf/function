# Function: <code>xdp_del_sk_umem</code>

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
void xdp_del_sk_umem(struct xdp_umem *umem, struct xdp_sock *xs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff819ccd40)
Location: net/xdp/xdp_umem.c:29
Inline: False
```
**Symbols:**

```
ffffffff819ccd40-ffffffff819ccdbd: xdp_del_sk_umem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xdp_del_sk_umem(struct xdp_umem *umem, struct xdp_sock *xs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff81a05e60)
Location: net/xdp/xdp_umem.c:31
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffffffff81a05e60-ffffffff81a05eb7: xdp_del_sk_umem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void xdp_del_sk_umem(struct xdp_umem *umem, struct xdp_sock *xs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff81a755d0)
Location: net/xdp/xdp_umem.c:34
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_unbind_dev
```
**Symbols:**

```
ffffffff81a755d0-ffffffff81a75624: xdp_del_sk_umem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void xdp_del_sk_umem(struct xdp_umem *umem, struct xdp_sock *xs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff81aac420)
Location: net/xdp/xdp_umem.c:38
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_unbind_dev
```
**Symbols:**

```
ffffffff81aac420-ffffffff81aac47f: xdp_del_sk_umem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xdp_del_sk_umem(struct xdp_umem *umem, struct xdp_sock *xs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff81ba86e0)
Location: net/xdp/xdp_umem.c:38
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_notifier
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffffffff81ba86e0-ffffffff81ba873c: xdp_del_sk_umem (STB_GLOBAL)
```
</details>
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
void xdp_del_sk_umem(struct xdp_umem *umem, struct xdp_sock *xs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffff800010d80cc0)
Location: net/xdp/xdp_umem.c:38
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_unbind_dev
```
**Symbols:**

```
ffff800010d80cc0-ffff800010d80d94: xdp_del_sk_umem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void xdp_del_sk_umem(struct xdp_umem *umem, struct xdp_sock *xs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (c0e7b23c)
Location: net/xdp/xdp_umem.c:38
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_unbind_dev
```
**Symbols:**

```
c0e7b23c-c0e7b294: xdp_del_sk_umem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void xdp_del_sk_umem(struct xdp_umem *umem, struct xdp_sock *xs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (c000000000ec0980)
Location: net/xdp/xdp_umem.c:38
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_unbind_dev
```
**Symbols:**

```
c000000000ec0980-c000000000ec0a14: xdp_del_sk_umem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void xdp_del_sk_umem(struct xdp_umem *umem, struct xdp_sock *xs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffe0008ad290)
Location: net/xdp/xdp_umem.c:38
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_unbind_dev
```
**Symbols:**

```
ffffffe0008ad290-ffffffe0008ad2ea: xdp_del_sk_umem (STB_GLOBAL)
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
void xdp_del_sk_umem(struct xdp_umem *umem, struct xdp_sock *xs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff81a4b7b0)
Location: net/xdp/xdp_umem.c:38
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_unbind_dev
```
**Symbols:**

```
ffffffff81a4b7b0-ffffffff81a4b80f: xdp_del_sk_umem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void xdp_del_sk_umem(struct xdp_umem *umem, struct xdp_sock *xs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff81a083a0)
Location: net/xdp/xdp_umem.c:38
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_unbind_dev
```
**Symbols:**

```
ffffffff81a083a0-ffffffff81a083ff: xdp_del_sk_umem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void xdp_del_sk_umem(struct xdp_umem *umem, struct xdp_sock *xs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff81ab7660)
Location: net/xdp/xdp_umem.c:38
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_unbind_dev
```
**Symbols:**

```
ffffffff81ab7660-ffffffff81ab76bf: xdp_del_sk_umem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void xdp_del_sk_umem(struct xdp_umem *umem, struct xdp_sock *xs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff81ac3a80)
Location: net/xdp/xdp_umem.c:38
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_unbind_dev
```
**Symbols:**

```
ffffffff81ac3a80-ffffffff81ac3adf: xdp_del_sk_umem (STB_GLOBAL)
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
