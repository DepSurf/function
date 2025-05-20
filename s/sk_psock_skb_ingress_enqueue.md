# Function: <code>sk_psock_skb_ingress_enqueue</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sk_psock_skb_ingress_enqueue(struct sk_buff *skb, struct sk_psock *psock, struct sock *sk, struct sk_msg *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81a3e430)
Location: net/core/skmsg.c:421
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_skb_ingress_self
```
**Symbols:**

```
ffffffff81a3e430-ffffffff81a3e538: sk_psock_skb_ingress_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sk_psock_skb_ingress_enqueue(struct sk_buff *skb, struct sk_psock *psock, struct sock *sk, struct sk_msg *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81a4cbf0)
Location: net/core/skmsg.c:519
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_skb_ingress_self
```
**Symbols:**

```
ffffffff81a4cbf0-ffffffff81a4ccd7: sk_psock_skb_ingress_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sk_psock_skb_ingress_enqueue(struct sk_buff *skb, u32 off, u32 len, struct sk_psock *psock, struct sock *sk, struct sk_msg *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81b06af0)
Location: net/core/skmsg.c:510
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_skb_ingress_self
```
**Symbols:**

```
ffffffff81b06af0-ffffffff81b06c48: sk_psock_skb_ingress_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sk_psock_skb_ingress_enqueue(struct sk_buff *skb, u32 off, u32 len, struct sk_psock *psock, struct sock *sk, struct sk_msg *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81c8b660)
Location: net/core/skmsg.c:519
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_skb_ingress_self
```
**Symbols:**

```
ffffffff81c8b660-ffffffff81c8b7ae: sk_psock_skb_ingress_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sk_psock_skb_ingress_enqueue(struct sk_buff *skb, u32 off, u32 len, struct sk_psock *psock, struct sock *sk, struct sk_msg *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81e46dd0)
Location: net/core/skmsg.c:526
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_skb_ingress_self
```
**Symbols:**

```
ffffffff81e46dd0-ffffffff81e46f1e: sk_psock_skb_ingress_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sk_psock_skb_ingress_enqueue(struct sk_buff *skb, u32 off, u32 len, struct sk_psock *psock, struct sock *sk, struct sk_msg *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81ea1d30)
Location: net/core/skmsg.c:525
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_skb_ingress_self
```
**Symbols:**

```
ffffffff81ea1d30-ffffffff81ea1e7e: sk_psock_skb_ingress_enqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sk_psock_skb_ingress_enqueue(struct sk_buff *skb, u32 off, u32 len, struct sk_psock *psock, struct sock *sk, struct sk_msg *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81f64300)
Location: net/core/skmsg.c:525
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_backlog
  - net/core/skmsg.c:sk_psock_skb_ingress_self
```
**Symbols:**

```
ffffffff81f64300-ffffffff81f6444e: sk_psock_skb_ingress_enqueue (STB_LOCAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 off</code>
</li>
<li>
<b>Param added. </b>
<code>u32 len</code>
</li>
<li>
<b>Param reordered. </b>
<code>skb, psock, sk, msg</code> ➡️ <code>skb, off, len, psock, sk, msg</code>
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
