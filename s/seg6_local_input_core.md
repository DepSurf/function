# Function: <code>seg6_local_input_core</code>

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
<summary>In <code>5.15</code>: ✅</summary>

```c
int seg6_local_input_core(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81c48100)
Location: net/ipv6/seg6_local.c:1085
Inline: False
Direct callers:
  - net/ipv6/seg6_local.c:seg6_local_input
  - net/ipv6/seg6_local.c:seg6_local_input
```
**Symbols:**

```
ffffffff81c48100-ffffffff81c48165: seg6_local_input_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int seg6_local_input_core(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81de7600)
Location: net/ipv6/seg6_local.c:1085
Inline: False
Direct callers:
  - net/ipv6/seg6_local.c:seg6_local_input
  - net/ipv6/seg6_local.c:seg6_local_input
```
**Symbols:**

```
ffffffff81de7600-ffffffff81de766f: seg6_local_input_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int seg6_local_input_core(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81fba580)
Location: net/ipv6/seg6_local.c:1211
Inline: False
Direct callers:
  - net/ipv6/seg6_local.c:seg6_local_input
  - net/ipv6/seg6_local.c:seg6_local_input
```
**Symbols:**

```
ffffffff81fba580-ffffffff81fba5ef: seg6_local_input_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int seg6_local_input_core(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff8201acb0)
Location: net/ipv6/seg6_local.c:1538
Inline: False
Direct callers:
  - net/ipv6/seg6_local.c:seg6_local_input
  - net/ipv6/seg6_local.c:seg6_local_input
```
**Symbols:**

```
ffffffff8201acb0-ffffffff8201ad22: seg6_local_input_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int seg6_local_input_core(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff820e9c70)
Location: net/ipv6/seg6_local.c:1599
Inline: False
Direct callers:
  - net/ipv6/seg6_local.c:seg6_local_input
  - net/ipv6/seg6_local.c:seg6_local_input
```
**Symbols:**

```
ffffffff820e9c70-ffffffff820e9ce2: seg6_local_input_core (STB_LOCAL)
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
