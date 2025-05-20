# Function: <code>ioam6_do_inline</code>

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
int ioam6_do_inline(struct sk_buff *skb, struct ioam6_lwt_encap *tuninfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ioam6_iptunnel.c (ffffffff81c4bdb0)
Location: net/ipv6/ioam6_iptunnel.c:161
Inline: False
Direct callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
```
**Symbols:**

```
ffffffff81c4bdb0-ffffffff81c4c096: ioam6_do_inline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ioam6_do_inline(struct net *net, struct sk_buff *skb, struct ioam6_lwt_encap *tuninfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ioam6_iptunnel.c (ffffffff81debac0)
Location: net/ipv6/ioam6_iptunnel.c:222
Inline: False
Direct callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
```
**Symbols:**

```
ffffffff81debac0-ffffffff81debda5: ioam6_do_inline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ioam6_do_inline(struct net *net, struct sk_buff *skb, struct ioam6_lwt_encap *tuninfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ioam6_iptunnel.c (ffffffff81fbf730)
Location: net/ipv6/ioam6_iptunnel.c:222
Inline: False
Direct callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
```
**Symbols:**

```
ffffffff81fbf730-ffffffff81fbf9f3: ioam6_do_inline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ioam6_do_inline(struct net *net, struct sk_buff *skb, struct ioam6_lwt_encap *tuninfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ioam6_iptunnel.c (ffffffff820206c0)
Location: net/ipv6/ioam6_iptunnel.c:222
Inline: False
Direct callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
```
**Symbols:**

```
ffffffff820206c0-ffffffff82020983: ioam6_do_inline (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ioam6_do_inline(struct net *net, struct sk_buff *skb, struct ioam6_lwt_encap *tuninfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ioam6_iptunnel.c (ffffffff820ef7f0)
Location: net/ipv6/ioam6_iptunnel.c:222
Inline: False
Direct callers:
  - net/ipv6/ioam6_iptunnel.c:ioam6_output
```
**Symbols:**

```
ffffffff820ef7f0-ffffffff820efab3: ioam6_do_inline (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct net *net</code>
</li>
<li>
<b>Param reordered. </b>
<code>skb, tuninfo</code> ➡️ <code>net, skb, tuninfo</code>
</li>
</ul>
</details>
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
