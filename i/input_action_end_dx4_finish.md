# Function: <code>input_action_end_dx4_finish</code>

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
int input_action_end_dx4_finish(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81c49bb0)
Location: net/ipv6/seg6_local.c:439
Inline: False
Direct callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx4
```
**Symbols:**

```
ffffffff81c49bb0-ffffffff81c49cf8: input_action_end_dx4_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int input_action_end_dx4_finish(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81de9420)
Location: net/ipv6/seg6_local.c:441
Inline: False
Direct callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx4
```
**Symbols:**

```
ffffffff81de9420-ffffffff81de956b: input_action_end_dx4_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int input_action_end_dx4_finish(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81fbccf0)
Location: net/ipv6/seg6_local.c:566
Inline: False
Direct callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx4
```
**Symbols:**

```
ffffffff81fbccf0-ffffffff81fbce3b: input_action_end_dx4_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int input_action_end_dx4_finish(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff8201d8b0)
Location: net/ipv6/seg6_local.c:893
Inline: False
Direct callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx4
```
**Symbols:**

```
ffffffff8201d8b0-ffffffff8201d9fe: input_action_end_dx4_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int input_action_end_dx4_finish(struct net *net, struct sock *sk, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff820ec890)
Location: net/ipv6/seg6_local.c:953
Inline: False
Direct callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
  - net/ipv6/seg6_local.c:input_action_end_dx4
```
**Symbols:**

```
ffffffff820ec890-ffffffff820ec9de: input_action_end_dx4_finish (STB_LOCAL)
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
