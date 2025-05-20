# Function: <code>eafnosupport_ipv6_dev_find</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct net_device *eafnosupport_ipv6_dev_find(struct net *net, const struct in6_addr *addr, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf_core.c (ffffffff81b80340)
Location: net/ipv6/addrconf_core.c:201
Inline: False
```
**Symbols:**

```
ffffffff81b80340-ffffffff81b80352: eafnosupport_ipv6_dev_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct net_device *eafnosupport_ipv6_dev_find(struct net *net, const struct in6_addr *addr, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf_core.c (ffffffff81c4c360)
Location: net/ipv6/addrconf_core.c:201
Inline: False
```
**Symbols:**

```
ffffffff81c4c360-ffffffff81c4c372: eafnosupport_ipv6_dev_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct net_device *eafnosupport_ipv6_dev_find(struct net *net, const struct in6_addr *addr, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf_core.c (ffffffff81dec670)
Location: net/ipv6/addrconf_core.c:201
Inline: False
```
**Symbols:**

```
ffffffff81dec670-ffffffff81dec686: eafnosupport_ipv6_dev_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct net_device *eafnosupport_ipv6_dev_find(struct net *net, const struct in6_addr *addr, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf_core.c (ffffffff81fc0370)
Location: net/ipv6/addrconf_core.c:201
Inline: False
```
**Symbols:**

```
ffffffff81fc0370-ffffffff81fc0386: eafnosupport_ipv6_dev_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct net_device *eafnosupport_ipv6_dev_find(struct net *net, const struct in6_addr *addr, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf_core.c (ffffffff820212f0)
Location: net/ipv6/addrconf_core.c:201
Inline: False
```
**Symbols:**

```
ffffffff820212f0-ffffffff82021306: eafnosupport_ipv6_dev_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct net_device *eafnosupport_ipv6_dev_find(struct net *net, const struct in6_addr *addr, struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf_core.c (ffffffff820f0420)
Location: net/ipv6/addrconf_core.c:201
Inline: False
```
**Symbols:**

```
ffffffff820f0420-ffffffff820f0436: eafnosupport_ipv6_dev_find (STB_LOCAL)
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
