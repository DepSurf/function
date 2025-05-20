# Function: <code>input_action_end_dx6_finish</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int input_action_end_dx6_finish(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81c4a1b7)
Location: net/ipv6/seg6_local.c:388
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx6
Direct callers:
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
**Symbols:**

```
ffffffff81c498d0-ffffffff81c49944: input_action_end_dx6_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int input_action_end_dx6_finish(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81de9c13)
Location: net/ipv6/seg6_local.c:390
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx6
Direct callers:
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
**Symbols:**

```
ffffffff81de90e0-ffffffff81de915e: input_action_end_dx6_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int input_action_end_dx6_finish(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81fbd363)
Location: net/ipv6/seg6_local.c:515
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx6
Direct callers:
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
**Symbols:**

```
ffffffff81fbc780-ffffffff81fbc7fe: input_action_end_dx6_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int input_action_end_dx6_finish(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff8201e68b)
Location: net/ipv6/seg6_local.c:842
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
**Symbols:**

```
ffffffff8201d350-ffffffff8201d3d1: input_action_end_dx6_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int input_action_end_dx6_finish(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff820ed7bb)
Location: net/ipv6/seg6_local.c:902
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx6
```
**Symbols:**

```
ffffffff820ec330-ffffffff820ec3b1: input_action_end_dx6_finish (STB_LOCAL)
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
