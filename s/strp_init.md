# Function: <code>strp_init</code>

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
int strp_init(struct strparser *strp, struct sock *sk, const struct strp_callbacks *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffff8195aba0)
Location: net/strparser/strparser.c:475
Inline: False
```
**Symbols:**

```
ffffffff8195aba0-ffffffff8195ad01: strp_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int strp_init(struct strparser *strp, struct sock *sk, const struct strp_callbacks *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffff819b4250)
Location: net/strparser/strparser.c:456
Inline: False
```
**Symbols:**

```
ffffffff819b4250-ffffffff819b43b1: strp_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int strp_init(struct strparser *strp, struct sock *sk, const struct strp_callbacks *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffff819eb280)
Location: net/strparser/strparser.c:456
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_init_strp
```
**Symbols:**

```
ffffffff819eb280-ffffffff819eb3e1: strp_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int strp_init(struct strparser *strp, struct sock *sk, const struct strp_callbacks *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffff81a5a450)
Location: net/strparser/strparser.c:448
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_init_strp
```
**Symbols:**

```
ffffffff81a5a450-ffffffff81a5a5b8: strp_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int strp_init(struct strparser *strp, struct sock *sk, const struct strp_callbacks *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffff81a910a0)
Location: net/strparser/strparser.c:448
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_init_strp
```
**Symbols:**

```
ffffffff81a910a0-ffffffff81a91208: strp_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int strp_init(struct strparser *strp, struct sock *sk, const struct strp_callbacks *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffff81b8c4b0)
Location: net/strparser/strparser.c:448
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_init_strp
  - net/xfrm/espintcp.c:espintcp_init_sk
```
**Symbols:**

```
ffffffff81b8c4b0-ffffffff81b8c618: strp_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int strp_init(struct strparser *strp, struct sock *sk, const struct strp_callbacks *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffff81b9c100)
Location: net/strparser/strparser.c:448
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_init_strp
  - net/xfrm/espintcp.c:espintcp_init_sk
```
**Symbols:**

```
ffffffff81b9c100-ffffffff81b9c268: strp_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int strp_init(struct strparser *strp, struct sock *sk, const struct strp_callbacks *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffff81b8b1c0)
Location: net/strparser/strparser.c:448
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_init_strp
  - net/xfrm/espintcp.c:espintcp_init_sk
```
**Symbols:**

```
ffffffff81b8b1c0-ffffffff81b8b328: strp_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int strp_init(struct strparser *strp, struct sock *sk, const struct strp_callbacks *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffff81c57460)
Location: net/strparser/strparser.c:440
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_init_strp
  - net/xfrm/espintcp.c:espintcp_init_sk
```
**Symbols:**

```
ffffffff81c57460-ffffffff81c575c8: strp_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int strp_init(struct strparser *strp, struct sock *sk, const struct strp_callbacks *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffff81df8a30)
Location: net/strparser/strparser.c:440
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_init_strp
  - net/xfrm/espintcp.c:espintcp_init_sk
```
**Symbols:**

```
ffffffff81df8a30-ffffffff81df8bb6: strp_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int strp_init(struct strparser *strp, struct sock *sk, const struct strp_callbacks *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffff81fccfb0)
Location: net/strparser/strparser.c:440
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_init_strp
  - net/xfrm/espintcp.c:espintcp_init_sk
```
**Symbols:**

```
ffffffff81fccfb0-ffffffff81fcd136: strp_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int strp_init(struct strparser *strp, struct sock *sk, const struct strp_callbacks *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffff820488e0)
Location: net/strparser/strparser.c:440
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_init_strp
  - net/xfrm/espintcp.c:espintcp_init_sk
```
**Symbols:**

```
ffffffff820488e0-ffffffff82048a66: strp_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int strp_init(struct strparser *strp, struct sock *sk, const struct strp_callbacks *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffff8211ac60)
Location: net/strparser/strparser.c:440
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_init_strp
  - net/xfrm/espintcp.c:espintcp_init_sk
```
**Symbols:**

```
ffffffff8211ac60-ffffffff8211ade6: strp_init (STB_GLOBAL)
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
int strp_init(struct strparser *strp, struct sock *sk, const struct strp_callbacks *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffff800010d5ec60)
Location: net/strparser/strparser.c:448
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_init_strp
```
**Symbols:**

```
ffff800010d5ec60-ffff800010d5eda0: strp_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int strp_init(struct strparser *strp, struct sock *sk, const struct strp_callbacks *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (c0e5e840)
Location: net/strparser/strparser.c:448
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_init_strp
```
**Symbols:**

```
c0e5e840-c0e5e990: strp_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int strp_init(struct strparser *strp, struct sock *sk, const struct strp_callbacks *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (c000000000e99550)
Location: net/strparser/strparser.c:448
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_init_strp
```
**Symbols:**

```
c000000000e99550-c000000000e99718: strp_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int strp_init(struct strparser *strp, struct sock *sk, const struct strp_callbacks *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffe000894442)
Location: net/strparser/strparser.c:448
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_init_strp
```
**Symbols:**

```
ffffffe000894442-ffffffe00089454c: strp_init (STB_GLOBAL)
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
int strp_init(struct strparser *strp, struct sock *sk, const struct strp_callbacks *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffff81a30730)
Location: net/strparser/strparser.c:448
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_init_strp
```
**Symbols:**

```
ffffffff81a30730-ffffffff81a30898: strp_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int strp_init(struct strparser *strp, struct sock *sk, const struct strp_callbacks *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffff819ed920)
Location: net/strparser/strparser.c:448
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_init_strp
```
**Symbols:**

```
ffffffff819ed920-ffffffff819eda88: strp_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int strp_init(struct strparser *strp, struct sock *sk, const struct strp_callbacks *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffff81a9c2e0)
Location: net/strparser/strparser.c:448
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_init_strp
```
**Symbols:**

```
ffffffff81a9c2e0-ffffffff81a9c448: strp_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int strp_init(struct strparser *strp, struct sock *sk, const struct strp_callbacks *cb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/strparser/strparser.c (ffffffff81aa84c0)
Location: net/strparser/strparser.c:448
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_init_strp
```
**Symbols:**

```
ffffffff81aa84c0-ffffffff81aa8628: strp_init (STB_GLOBAL)
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
