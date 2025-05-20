# Function: <code>handle_nonesp</code>

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
void handle_nonesp(struct espintcp_ctx *ctx, struct sk_buff *skb, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/espintcp.c (ffffffff81b22640)
Location: net/xfrm/espintcp.c:13
Inline: False
Direct callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
**Symbols:**

```
ffffffff81b22640-ffffffff81b22772: handle_nonesp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void handle_nonesp(struct espintcp_ctx *ctx, struct sk_buff *skb, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/espintcp.c (ffffffff81b31040)
Location: net/xfrm/espintcp.c:13
Inline: False
Direct callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
**Symbols:**

```
ffffffff81b31040-ffffffff81b31172: handle_nonesp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void handle_nonesp(struct espintcp_ctx *ctx, struct sk_buff *skb, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/espintcp.c (ffffffff81b1ed70)
Location: net/xfrm/espintcp.c:13
Inline: False
Direct callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
**Symbols:**

```
ffffffff81b1ed70-ffffffff81b1eea2: handle_nonesp (STB_LOCAL)
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
In net/xfrm/espintcp.c (ffffffff81be3d68)
Location: net/xfrm/espintcp.c:13
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void handle_nonesp(struct espintcp_ctx *ctx, struct sk_buff *skb, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/espintcp.c (ffffffff81d7ab30)
Location: net/xfrm/espintcp.c:13
Inline: False
Direct callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
**Symbols:**

```
ffffffff81d7ab30-ffffffff81d7ac89: handle_nonesp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void handle_nonesp(struct espintcp_ctx *ctx, struct sk_buff *skb, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/espintcp.c (ffffffff81f47b00)
Location: net/xfrm/espintcp.c:13
Inline: False
Direct callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
**Symbols:**

```
ffffffff81f47b00-ffffffff81f47c59: handle_nonesp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void handle_nonesp(struct espintcp_ctx *ctx, struct sk_buff *skb, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/espintcp.c (ffffffff81fa7600)
Location: net/xfrm/espintcp.c:14
Inline: False
Direct callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
**Symbols:**

```
ffffffff81fa7600-ffffffff81fa7759: handle_nonesp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void handle_nonesp(struct espintcp_ctx *ctx, struct sk_buff *skb, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/espintcp.c (ffffffff820748b0)
Location: net/xfrm/espintcp.c:14
Inline: False
Direct callers:
  - net/xfrm/espintcp.c:espintcp_rcv
```
**Symbols:**

```
ffffffff820748b0-ffffffff82074a11: handle_nonesp (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
