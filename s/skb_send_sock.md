# Function: <code>skb_send_sock</code>

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
int skb_send_sock(struct sock *sk, struct sk_buff *skb, int offset, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818309f0)
Location: net/core/skbuff.c:2352
Inline: False
```
**Symbols:**

```
ffffffff818309f0-ffffffff81830a3b: skb_send_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int skb_send_sock(struct sock *sk, struct sk_buff *skb, int offset, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8187aec0)
Location: net/core/skbuff.c:2368
Inline: False
```
**Symbols:**

```
ffffffff8187aec0-ffffffff8187af0b: skb_send_sock (STB_GLOBAL)
```
</details>
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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int skb_send_sock(struct sock *sk, struct sk_buff *skb, int offset, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d8510)
Location: net/core/skbuff.c:2631
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_backlog
```
**Symbols:**

```
ffffffff819d8510-ffffffff819d852e: skb_send_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int skb_send_sock(struct sock *sk, struct sk_buff *skb, int offset, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a883a0)
Location: net/core/skbuff.c:2703
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_backlog
```
**Symbols:**

```
ffffffff81a883a0-ffffffff81a883be: skb_send_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int skb_send_sock(struct sock *sk, struct sk_buff *skb, int offset, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bfdab0)
Location: net/core/skbuff.c:2752
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_backlog
```
**Symbols:**

```
ffffffff81bfdab0-ffffffff81bfdae0: skb_send_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int skb_send_sock(struct sock *sk, struct sk_buff *skb, int offset, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81dae800)
Location: net/core/skbuff.c:2958
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_backlog
```
**Symbols:**

```
ffffffff81dae800-ffffffff81dae830: skb_send_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int skb_send_sock(struct sock *sk, struct sk_buff *skb, int offset, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e1e740)
Location: net/core/skbuff.c:3129
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_backlog
```
**Symbols:**

```
ffffffff81e1e740-ffffffff81e1e766: skb_send_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int skb_send_sock(struct sock *sk, struct sk_buff *skb, int offset, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81edbda0)
Location: net/core/skbuff.c:3217
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_backlog
```
**Symbols:**

```
ffffffff81edbda0-ffffffff81edbdc6: skb_send_sock (STB_GLOBAL)
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
No changes between <code>4.15</code> and <code>4.18</code> ✅
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
