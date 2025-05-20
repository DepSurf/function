# Function: <code>sk_psock_skb_ingress_self</code>

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
int sk_psock_skb_ingress_self(struct sk_psock *psock, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81a3f110)
Location: net/core/skmsg.c:483
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_verdict_apply
  - net/core/skmsg.c:sk_psock_backlog
```
**Symbols:**

```
ffffffff81a3f110-ffffffff81a3f17c: sk_psock_skb_ingress_self (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sk_psock_skb_ingress_self(struct sk_psock *psock, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81a4d5d0)
Location: net/core/skmsg.c:583
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_verdict_apply
  - net/core/skmsg.c:sk_psock_backlog
```
**Symbols:**

```
ffffffff81a4d5d0-ffffffff81a4d6d1: sk_psock_skb_ingress_self (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sk_psock_skb_ingress_self(struct sk_psock *psock, struct sk_buff *skb, u32 off, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81b06c50)
Location: net/core/skmsg.c:577
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_verdict_apply
  - net/core/skmsg.c:sk_psock_backlog
```
**Symbols:**

```
ffffffff81b06c50-ffffffff81b06d5f: sk_psock_skb_ingress_self (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sk_psock_skb_ingress_self(struct sk_psock *psock, struct sk_buff *skb, u32 off, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81c8b960)
Location: net/core/skmsg.c:590
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_verdict_apply
  - net/core/skmsg.c:sk_psock_backlog
```
**Symbols:**

```
ffffffff81c8b960-ffffffff81c8baa6: sk_psock_skb_ingress_self (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sk_psock_skb_ingress_self(struct sk_psock *psock, struct sk_buff *skb, u32 off, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81e46f30)
Location: net/core/skmsg.c:597
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_verdict_apply
  - net/core/skmsg.c:sk_psock_backlog
```
**Symbols:**

```
ffffffff81e46f30-ffffffff81e4704f: sk_psock_skb_ingress_self (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sk_psock_skb_ingress_self(struct sk_psock *psock, struct sk_buff *skb, u32 off, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81ea1e90)
Location: net/core/skmsg.c:596
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_verdict_apply
  - net/core/skmsg.c:sk_psock_backlog
```
**Symbols:**

```
ffffffff81ea1e90-ffffffff81ea1faf: sk_psock_skb_ingress_self (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sk_psock_skb_ingress_self(struct sk_psock *psock, struct sk_buff *skb, u32 off, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81f64460)
Location: net/core/skmsg.c:596
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_verdict_apply
  - net/core/skmsg.c:sk_psock_backlog
```
**Symbols:**

```
ffffffff81f64460-ffffffff81f64591: sk_psock_skb_ingress_self (STB_LOCAL)
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
