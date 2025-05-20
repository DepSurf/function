# Function: <code>ioam6_do_encap</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ioam6_do_encap(struct net *net, struct sk_buff *skb, struct ioam6_lwt_encap *tuninfo, struct in6_addr *tundst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ioam6_iptunnel.c (ffffffff81debdb0)
Location: net/ipv6/ioam6_iptunnel.c:257
Inline: False
Direct callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
```
**Symbols:**

```
ffffffff81debdb0-ffffffff81dec048: ioam6_do_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ioam6_do_encap(struct net *net, struct sk_buff *skb, struct ioam6_lwt_encap *tuninfo, struct in6_addr *tundst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ioam6_iptunnel.c (ffffffff81fbfa10)
Location: net/ipv6/ioam6_iptunnel.c:257
Inline: False
Direct callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
```
**Symbols:**

```
ffffffff81fbfa10-ffffffff81fbfc8a: ioam6_do_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ioam6_do_encap(struct net *net, struct sk_buff *skb, struct ioam6_lwt_encap *tuninfo, struct in6_addr *tundst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ioam6_iptunnel.c (ffffffff820209a0)
Location: net/ipv6/ioam6_iptunnel.c:257
Inline: False
Direct callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
```
**Symbols:**

```
ffffffff820209a0-ffffffff82020c1a: ioam6_do_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ioam6_do_encap(struct net *net, struct sk_buff *skb, struct ioam6_lwt_encap *tuninfo, struct in6_addr *tundst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ioam6_iptunnel.c (ffffffff820efad0)
Location: net/ipv6/ioam6_iptunnel.c:257
Inline: False
Direct callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
```
**Symbols:**

```
ffffffff820efad0-ffffffff820efd4a: ioam6_do_encap (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
