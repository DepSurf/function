# Function: <code>strp_done</code>

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
void strp_done(struct strparser *strp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffff8195ad50)
Location: net/strparser/strparser.c:530
Inline: False
Direct callers:
  - kernel/bpf/sockmap.c:smap_gc_work
```
**Symbols:**

```
ffffffff8195ad50-ffffffff8195ad95: strp_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void strp_done(struct strparser *strp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffff819b4400)
Location: net/strparser/strparser.c:524
Inline: False
Direct callers:
  - kernel/bpf/sockmap.c:smap_gc_work
```
**Symbols:**

```
ffffffff819b4400-ffffffff819b4445: strp_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void strp_done(struct strparser *strp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffff819eb430)
Location: net/strparser/strparser.c:524
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
**Symbols:**

```
ffffffff819eb430-ffffffff819eb475: strp_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void strp_done(struct strparser *strp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/strparser/strparser.c (0)
Location: net/strparser/strparser.c:516
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
**Symbols:**

```
ffffffff81a5ad95-ffffffff81a5ada8: strp_done.cold (STB_LOCAL)
ffffffff81a5a600-ffffffff81a5a645: strp_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void strp_done(struct strparser *strp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffff81a91250)
Location: net/strparser/strparser.c:516
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
**Symbols:**

```
ffffffff81a91250-ffffffff81a91295: strp_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void strp_done(struct strparser *strp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffff81b8c660)
Location: net/strparser/strparser.c:516
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/xfrm/espintcp.c:espintcp_close
```
**Symbols:**

```
ffffffff81b8c660-ffffffff81b8c6a8: strp_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void strp_done(struct strparser *strp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffff81b9c2b0)
Location: net/strparser/strparser.c:516
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_destroy_deferred
  - net/xfrm/espintcp.c:espintcp_close
```
**Symbols:**

```
ffffffff81b9c2b0-ffffffff81b9c2f8: strp_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void strp_done(struct strparser *strp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffff81b8b370)
Location: net/strparser/strparser.c:516
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_destroy
  - net/xfrm/espintcp.c:espintcp_close
```
**Symbols:**

```
ffffffff81b8b370-ffffffff81b8b3b8: strp_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void strp_done(struct strparser *strp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffff81c57610)
Location: net/strparser/strparser.c:508
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_destroy
  - net/xfrm/espintcp.c:espintcp_close
```
**Symbols:**

```
ffffffff81c57610-ffffffff81c57658: strp_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void strp_done(struct strparser *strp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffff81df8c00)
Location: net/strparser/strparser.c:508
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_destroy
  - net/xfrm/espintcp.c:espintcp_close
```
**Symbols:**

```
ffffffff81df8c00-ffffffff81df8c57: strp_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void strp_done(struct strparser *strp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffff81fcd1b0)
Location: net/strparser/strparser.c:508
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_destroy
  - net/xfrm/espintcp.c:espintcp_close
```
**Symbols:**

```
ffffffff81fcd1b0-ffffffff81fcd207: strp_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void strp_done(struct strparser *strp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffff82048ae0)
Location: net/strparser/strparser.c:508
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_destroy
  - net/xfrm/espintcp.c:espintcp_close
```
**Symbols:**

```
ffffffff82048ae0-ffffffff82048b37: strp_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void strp_done(struct strparser *strp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffff8211ae60)
Location: net/strparser/strparser.c:508
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_destroy
  - net/xfrm/espintcp.c:espintcp_close
```
**Symbols:**

```
ffffffff8211ae60-ffffffff8211aeb7: strp_done (STB_GLOBAL)
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
void strp_done(struct strparser *strp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffff800010d5ee00)
Location: net/strparser/strparser.c:516
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
**Symbols:**

```
ffff800010d5ee00-ffff800010d5ee54: strp_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void strp_done(struct strparser *strp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (c0e5e9d4)
Location: net/strparser/strparser.c:516
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
**Symbols:**

```
c0e5e9d4-c0e5ea40: strp_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void strp_done(struct strparser *strp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (c000000000e997a0)
Location: net/strparser/strparser.c:516
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
**Symbols:**

```
c000000000e997a0-c000000000e9981c: strp_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void strp_done(struct strparser *strp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffe0008945a2)
Location: net/strparser/strparser.c:516
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
**Symbols:**

```
ffffffe0008945a2-ffffffe0008945f6: strp_done (STB_GLOBAL)
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
void strp_done(struct strparser *strp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffff81a308e0)
Location: net/strparser/strparser.c:516
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
**Symbols:**

```
ffffffff81a308e0-ffffffff81a30925: strp_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void strp_done(struct strparser *strp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffff819edad0)
Location: net/strparser/strparser.c:516
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
**Symbols:**

```
ffffffff819edad0-ffffffff819edb15: strp_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void strp_done(struct strparser *strp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffff81a9c490)
Location: net/strparser/strparser.c:516
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
**Symbols:**

```
ffffffff81a9c490-ffffffff81a9c4d5: strp_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void strp_done(struct strparser *strp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffff81aa8670)
Location: net/strparser/strparser.c:516
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_destroy_deferred
```
**Symbols:**

```
ffffffff81aa8670-ffffffff81aa86b5: strp_done (STB_GLOBAL)
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
