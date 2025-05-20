# Function: <code>xfrm_trans_queue_net</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int xfrm_trans_queue_net(struct net *net, struct sk_buff *skb, int (*finish)(struct net *, struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81b1d910)
Location: net/xfrm/xfrm_input.c:775
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
**Symbols:**

```
ffffffff81b1d790-ffffffff81b1d808: xfrm_trans_queue_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int xfrm_trans_queue_net(struct net *net, struct sk_buff *skb, int (*finish)(struct net *, struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81b2c1e0)
Location: net/xfrm/xfrm_input.c:777
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
**Symbols:**

```
ffffffff81b2c060-ffffffff81b2c0d8: xfrm_trans_queue_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int xfrm_trans_queue_net(struct net *net, struct sk_buff *skb, int (*finish)(struct net *, struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81b19e40)
Location: net/xfrm/xfrm_input.c:777
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
**Symbols:**

```
ffffffff81b19cc0-ffffffff81b19d38: xfrm_trans_queue_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int xfrm_trans_queue_net(struct net *net, struct sk_buff *skb, int (*finish)(struct net *, struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81bde460)
Location: net/xfrm/xfrm_input.c:777
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
**Symbols:**

```
ffffffff81bddfd0-ffffffff81bde04d: xfrm_trans_queue_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int xfrm_trans_queue_net(struct net *net, struct sk_buff *skb, int (*finish)(struct net *, struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81d75282)
Location: net/xfrm/xfrm_input.c:777
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
**Symbols:**

```
ffffffff81d74bf0-ffffffff81d74c7c: xfrm_trans_queue_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xfrm_trans_queue_net(struct net *net, struct sk_buff *skb, int (*finish)(struct net *, struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81f41770)
Location: net/xfrm/xfrm_input.c:785
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
**Symbols:**

```
ffffffff81f41770-ffffffff81f41806: xfrm_trans_queue_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xfrm_trans_queue_net(struct net *net, struct sk_buff *skb, int (*finish)(struct net *, struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81fa1010)
Location: net/xfrm/xfrm_input.c:761
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
**Symbols:**

```
ffffffff81fa1010-ffffffff81fa10a6: xfrm_trans_queue_net (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xfrm_trans_queue_net(struct net *net, struct sk_buff *skb, int (*finish)(struct net *, struct sock *, struct sk_buff *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff8206e330)
Location: net/xfrm/xfrm_input.c:759
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
**Symbols:**

```
ffffffff8206e330-ffffffff8206e3c6: xfrm_trans_queue_net (STB_GLOBAL)
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
