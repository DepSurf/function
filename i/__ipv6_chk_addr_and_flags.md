# Function: <code>__ipv6_chk_addr_and_flags</code>

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
struct net_device *__ipv6_chk_addr_and_flags(struct net *net, const struct in6_addr *addr, const struct net_device *dev, bool skip_dev_check, int strict, u32 banned_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b42b90)
Location: net/ipv6/addrconf.c:1897
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:ipv6_dev_find
  - net/ipv6/addrconf.c:ipv6_chk_addr
```
**Symbols:**

```
ffffffff81b42b90-ffffffff81b42d20: __ipv6_chk_addr_and_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct net_device *__ipv6_chk_addr_and_flags(struct net *net, const struct in6_addr *addr, const struct net_device *dev, bool skip_dev_check, int strict, u32 banned_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b30b20)
Location: net/ipv6/addrconf.c:1899
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:ipv6_dev_find
  - net/ipv6/addrconf.c:ipv6_chk_addr
```
**Symbols:**

```
ffffffff81b30b20-ffffffff81b30cad: __ipv6_chk_addr_and_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct net_device *__ipv6_chk_addr_and_flags(struct net *net, const struct in6_addr *addr, const struct net_device *dev, bool skip_dev_check, int strict, u32 banned_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81bf7040)
Location: net/ipv6/addrconf.c:1906
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:ipv6_dev_find
  - net/ipv6/addrconf.c:ipv6_chk_addr
```
**Symbols:**

```
ffffffff81bf7040-ffffffff81bf71cd: __ipv6_chk_addr_and_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct net_device *__ipv6_chk_addr_and_flags(struct net *net, const struct in6_addr *addr, const struct net_device *dev, bool skip_dev_check, int strict, u32 banned_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81d90300)
Location: net/ipv6/addrconf.c:1913
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:ipv6_dev_find
  - net/ipv6/addrconf.c:ipv6_chk_addr
```
**Symbols:**

```
ffffffff81d90300-ffffffff81d90489: __ipv6_chk_addr_and_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct net_device *__ipv6_chk_addr_and_flags(struct net *net, const struct in6_addr *addr, const struct net_device *dev, bool skip_dev_check, int strict, u32 banned_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81f5e8c0)
Location: net/ipv6/addrconf.c:1913
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:ipv6_dev_find
  - net/ipv6/addrconf.c:ipv6_chk_addr
```
**Symbols:**

```
ffffffff81f5e8c0-ffffffff81f5ea49: __ipv6_chk_addr_and_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct net_device *__ipv6_chk_addr_and_flags(struct net *net, const struct in6_addr *addr, const struct net_device *dev, bool skip_dev_check, int strict, u32 banned_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81fbe5a0)
Location: net/ipv6/addrconf.c:1912
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:ipv6_dev_find
  - net/ipv6/addrconf.c:ipv6_chk_addr
```
**Symbols:**

```
ffffffff81fbe5a0-ffffffff81fbe729: __ipv6_chk_addr_and_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct net_device *__ipv6_chk_addr_and_flags(struct net *net, const struct in6_addr *addr, const struct net_device *dev, bool skip_dev_check, int strict, u32 banned_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8208ba30)
Location: net/ipv6/addrconf.c:1940
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:ipv6_dev_find
  - net/ipv6/addrconf.c:ipv6_chk_addr
```
**Symbols:**

```
ffffffff8208ba30-ffffffff8208bbb2: __ipv6_chk_addr_and_flags (STB_LOCAL)
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
