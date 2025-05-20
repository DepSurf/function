# Function: <code>ioam6_build_state</code>

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
int ioam6_build_state(struct net *net, struct nlattr *nla, unsigned int family, const void *cfg, struct lwtunnel_state **ts, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ioam6_iptunnel.c (ffffffff81c4bbd0)
Location: net/ipv6/ioam6_iptunnel.c:96
Inline: False
```
**Symbols:**

```
ffffffff81c4bbd0-ffffffff81c4bda1: ioam6_build_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ioam6_build_state(struct net *net, struct nlattr *nla, unsigned int family, const void *cfg, struct lwtunnel_state **ts, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ioam6_iptunnel.c (ffffffff81deb730)
Location: net/ipv6/ioam6_iptunnel.c:102
Inline: False
```
**Symbols:**

```
ffffffff81deb730-ffffffff81debab6: ioam6_build_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ioam6_build_state(struct net *net, struct nlattr *nla, unsigned int family, const void *cfg, struct lwtunnel_state **ts, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ioam6_iptunnel.c (ffffffff81fbf390)
Location: net/ipv6/ioam6_iptunnel.c:102
Inline: False
```
**Symbols:**

```
ffffffff81fbf390-ffffffff81fbf716: ioam6_build_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ioam6_build_state(struct net *net, struct nlattr *nla, unsigned int family, const void *cfg, struct lwtunnel_state **ts, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ioam6_iptunnel.c (ffffffff82020320)
Location: net/ipv6/ioam6_iptunnel.c:102
Inline: False
```
**Symbols:**

```
ffffffff82020320-ffffffff820206a6: ioam6_build_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ioam6_build_state(struct net *net, struct nlattr *nla, unsigned int family, const void *cfg, struct lwtunnel_state **ts, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ioam6_iptunnel.c (ffffffff820ef450)
Location: net/ipv6/ioam6_iptunnel.c:102
Inline: False
```
**Symbols:**

```
ffffffff820ef450-ffffffff820ef7d9: ioam6_build_state (STB_LOCAL)
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
