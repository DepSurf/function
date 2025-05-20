# Function: <code>add_grec</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision ⚠️</summary>

```c
struct sk_buff *add_grec(struct sk_buff *skb, struct ip_mc_list *pmc, int type, int gdeleted, int sdeleted);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81796400)
Location: net/ipv4/igmp.c:432
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
```
```
In net/ipv6/mcast.c (ffffffff817ea580)
Location: net/ipv6/mcast.c:1695
Inline: False
Direct callers:
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
```
**Symbols:**

```
ffffffff81796400-ffffffff8179685c: add_grec (STB_LOCAL)
ffffffff817ea580-ffffffff817eaa28: add_grec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision ⚠️</summary>

```c
struct sk_buff *add_grec(struct sk_buff *skb, struct ip_mc_list *pmc, int type, int gdeleted, int sdeleted);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81804190)
Location: net/ipv4/igmp.c:425
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
```
```
In net/ipv6/mcast.c (ffffffff81858e50)
Location: net/ipv6/mcast.c:1694
Inline: False
Direct callers:
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
```
**Symbols:**

```
ffffffff81804190-ffffffff818045f4: add_grec (STB_LOCAL)
ffffffff81858e50-ffffffff818592f8: add_grec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision ⚠️</summary>

```c
struct sk_buff *add_grec(struct sk_buff *skb, struct ip_mc_list *pmc, int type, int gdeleted, int sdeleted);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81835110)
Location: net/ipv4/igmp.c:430
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
```
```
In net/ipv6/mcast.c (ffffffff8188ac30)
Location: net/ipv6/mcast.c:1708
Inline: False
Direct callers:
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
```
**Symbols:**

```
ffffffff81835110-ffffffff818355bf: add_grec (STB_LOCAL)
ffffffff8188ac30-ffffffff8188b126: add_grec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision ⚠️</summary>

```c
struct sk_buff *add_grec(struct sk_buff *skb, struct ip_mc_list *pmc, int type, int gdeleted, int sdeleted);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81856650)
Location: net/ipv4/igmp.c:430
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
```
```
In net/ipv6/mcast.c (ffffffff818b1970)
Location: net/ipv6/mcast.c:1708
Inline: False
Direct callers:
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
```
**Symbols:**

```
ffffffff81856650-ffffffff81856b09: add_grec (STB_LOCAL)
ffffffff818b1970-ffffffff818b1e15: add_grec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision ⚠️</summary>

```c
struct sk_buff *add_grec(struct sk_buff *skb, struct ip_mc_list *pmc, int type, int gdeleted, int sdeleted);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff818d6510)
Location: net/ipv4/igmp.c:453
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
```
```
In net/ipv6/mcast.c (ffffffff81933cf0)
Location: net/ipv6/mcast.c:1708
Inline: False
Direct callers:
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
```
**Symbols:**

```
ffffffff818d6510-ffffffff818d69be: add_grec (STB_LOCAL)
ffffffff81933cf0-ffffffff8193418f: add_grec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision ⚠️</summary>

```c
struct sk_buff *add_grec(struct sk_buff *skb, struct ip_mc_list *pmc, int type, int gdeleted, int sdeleted);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff8192ce50)
Location: net/ipv4/igmp.c:453
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
```
```
In net/ipv6/mcast.c (ffffffff8198c880)
Location: net/ipv6/mcast.c:1731
Inline: False
Direct callers:
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
```
**Symbols:**

```
ffffffff8192ce50-ffffffff8192d31b: add_grec (STB_LOCAL)
ffffffff8198c880-ffffffff8198cd84: add_grec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision ⚠️</summary>

```c
struct sk_buff *add_grec(struct sk_buff *skb, struct ip_mc_list *pmc, int type, int gdeleted, int sdeleted);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff8195c2f0)
Location: net/ipv4/igmp.c:450
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
```
```
In net/ipv6/mcast.c (ffffffff819c3100)
Location: net/ipv6/mcast.c:1731
Inline: False
Direct callers:
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
```
**Symbols:**

```
ffffffff8195c2f0-ffffffff8195c7b2: add_grec (STB_LOCAL)
ffffffff819c3100-ffffffff819c35fb: add_grec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision ⚠️</summary>

```c
struct sk_buff *add_grec(struct sk_buff *skb, struct ip_mc_list *pmc, int type, int gdeleted, int sdeleted);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff819c0ff0)
Location: net/ipv4/igmp.c:459
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
```
```
In net/ipv6/mcast.c (ffffffff81a31f40)
Location: net/ipv6/mcast.c:1730
Inline: False
Direct callers:
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
```
**Symbols:**

```
ffffffff819c0ff0-ffffffff819c14bf: add_grec (STB_LOCAL)
ffffffff81a31f40-ffffffff81a32441: add_grec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision ⚠️</summary>

```c
struct sk_buff *add_grec(struct sk_buff *skb, struct ip_mc_list *pmc, int type, int gdeleted, int sdeleted);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff819f7b90)
Location: net/ipv4/igmp.c:459
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
```
```
In net/ipv6/mcast.c (ffffffff81a68a90)
Location: net/ipv6/mcast.c:1730
Inline: False
Direct callers:
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
```
**Symbols:**

```
ffffffff819f7b90-ffffffff819f805f: add_grec (STB_LOCAL)
ffffffff81a68a90-ffffffff81a68f91: add_grec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision ⚠️</summary>

```c
struct sk_buff *add_grec(struct sk_buff *skb, struct ip_mc_list *pmc, int type, int gdeleted, int sdeleted);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81ae56e0)
Location: net/ipv4/igmp.c:457
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmpv3_send_cr
  - net/ipv4/igmp.c:igmpv3_send_cr
  - net/ipv4/igmp.c:igmpv3_send_cr
  - net/ipv4/igmp.c:igmpv3_send_cr
  - net/ipv4/igmp.c:igmpv3_send_cr
  - net/ipv4/igmp.c:igmpv3_send_cr
```
```
In net/ipv6/mcast.c (ffffffff81b61060)
Location: net/ipv6/mcast.c:1727
Inline: False
Direct callers:
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
```
**Symbols:**

```
ffffffff81ae56e0-ffffffff81ae5b9b: add_grec (STB_LOCAL)
ffffffff81b61060-ffffffff81b6154d: add_grec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision ⚠️</summary>

```c
struct sk_buff *add_grec(struct sk_buff *skb, struct ip_mc_list *pmc, int type, int gdeleted, int sdeleted);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81af25a0)
Location: net/ipv4/igmp.c:457
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmpv3_send_cr
  - net/ipv4/igmp.c:igmpv3_send_cr
  - net/ipv4/igmp.c:igmpv3_send_cr
  - net/ipv4/igmp.c:igmpv3_send_cr
  - net/ipv4/igmp.c:igmpv3_send_cr
  - net/ipv4/igmp.c:igmpv3_send_cr
```
```
In net/ipv6/mcast.c (ffffffff81b6f7e0)
Location: net/ipv6/mcast.c:1727
Inline: False
Direct callers:
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
```
**Symbols:**

```
ffffffff81af25a0-ffffffff81af2a5b: add_grec (STB_LOCAL)
ffffffff81b6f7e0-ffffffff81b6fccd: add_grec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision ⚠️</summary>

```c
struct sk_buff *add_grec(struct sk_buff *skb, struct ip_mc_list *pmc, int type, int gdeleted, int sdeleted);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81addd80)
Location: net/ipv4/igmp.c:457
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmpv3_send_cr
  - net/ipv4/igmp.c:igmpv3_send_cr
  - net/ipv4/igmp.c:igmpv3_send_cr
  - net/ipv4/igmp.c:igmpv3_send_cr
  - net/ipv4/igmp.c:igmpv3_send_cr
  - net/ipv4/igmp.c:igmpv3_send_cr
```
```
In net/ipv6/mcast.c (ffffffff81b5db30)
Location: net/ipv6/mcast.c:1869
Inline: False
Direct callers:
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
```
**Symbols:**

```
ffffffff81addd80-ffffffff81ade23a: add_grec (STB_LOCAL)
ffffffff81b5db30-ffffffff81b5e018: add_grec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision ⚠️</summary>

```c
struct sk_buff *add_grec(struct sk_buff *skb, struct ip_mc_list *pmc, int type, int gdeleted, int sdeleted);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81b9d220)
Location: net/ipv4/igmp.c:457
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmpv3_send_cr
  - net/ipv4/igmp.c:igmpv3_send_cr
  - net/ipv4/igmp.c:igmpv3_send_cr
  - net/ipv4/igmp.c:igmpv3_send_cr
  - net/ipv4/igmp.c:igmpv3_send_cr
  - net/ipv4/igmp.c:igmpv3_send_cr
```
```
In net/ipv6/mcast.c (ffffffff81c24fe0)
Location: net/ipv6/mcast.c:1867
Inline: False
Direct callers:
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
```
**Symbols:**

```
ffffffff81b9d220-ffffffff81b9d6da: add_grec (STB_LOCAL)
ffffffff81c24fe0-ffffffff81c254ce: add_grec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision ⚠️</summary>

```c
struct sk_buff *add_grec(struct sk_buff *skb, struct ip_mc_list *pmc, int type, int gdeleted, int sdeleted);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81d2f390)
Location: net/ipv4/igmp.c:457
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmpv3_send_cr
  - net/ipv4/igmp.c:igmpv3_send_cr
  - net/ipv4/igmp.c:igmpv3_send_cr
  - net/ipv4/igmp.c:igmpv3_send_cr
  - net/ipv4/igmp.c:igmpv3_send_cr
  - net/ipv4/igmp.c:igmpv3_send_cr
```
```
In net/ipv6/mcast.c (ffffffff81dc22f0)
Location: net/ipv6/mcast.c:1869
Inline: False
Direct callers:
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
```
**Symbols:**

```
ffffffff81d2f390-ffffffff81d2f8b1: add_grec (STB_LOCAL)
ffffffff81dc22f0-ffffffff81dc2881: add_grec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
struct sk_buff *add_grec(struct sk_buff *skb, struct ip_mc_list *pmc, int type, int gdeleted, int sdeleted);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81ef7450)
Location: net/ipv4/igmp.c:457
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmpv3_send_cr
  - net/ipv4/igmp.c:igmpv3_send_cr
  - net/ipv4/igmp.c:igmpv3_send_cr
  - net/ipv4/igmp.c:igmpv3_send_cr
  - net/ipv4/igmp.c:igmpv3_send_cr
  - net/ipv4/igmp.c:igmpv3_send_cr
```
```
In net/ipv6/mcast.c (ffffffff81f92ff0)
Location: net/ipv6/mcast.c:1869
Inline: False
Direct callers:
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
```
**Symbols:**

```
ffffffff81ef7450-ffffffff81ef7971: add_grec (STB_LOCAL)
ffffffff81f92ff0-ffffffff81f93581: add_grec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
struct sk_buff *add_grec(struct sk_buff *skb, struct ip_mc_list *pmc, int type, int gdeleted, int sdeleted);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81f56ed0)
Location: net/ipv4/igmp.c:458
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmpv3_send_cr
  - net/ipv4/igmp.c:igmpv3_send_cr
  - net/ipv4/igmp.c:igmpv3_send_cr
  - net/ipv4/igmp.c:igmpv3_send_cr
  - net/ipv4/igmp.c:igmpv3_send_cr
  - net/ipv4/igmp.c:igmpv3_send_cr
```
```
In net/ipv6/mcast.c (ffffffff81ff35f0)
Location: net/ipv6/mcast.c:1869
Inline: False
Direct callers:
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
```
**Symbols:**

```
ffffffff81f56ed0-ffffffff81f57402: add_grec (STB_LOCAL)
ffffffff81ff35f0-ffffffff81ff3bac: add_grec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
struct sk_buff *add_grec(struct sk_buff *skb, struct ip_mc_list *pmc, int type, int gdeleted, int sdeleted);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff8201d380)
Location: net/ipv4/igmp.c:460
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmpv3_send_cr
  - net/ipv4/igmp.c:igmpv3_send_cr
  - net/ipv4/igmp.c:igmpv3_send_cr
  - net/ipv4/igmp.c:igmpv3_send_cr
  - net/ipv4/igmp.c:igmpv3_send_cr
  - net/ipv4/igmp.c:igmpv3_send_cr
```
```
In net/ipv6/mcast.c (ffffffff820c1670)
Location: net/ipv6/mcast.c:1867
Inline: False
Direct callers:
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_cr
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
```
**Symbols:**

```
ffffffff8201d380-ffffffff8201d8af: add_grec (STB_LOCAL)
ffffffff820c1670-ffffffff820c1c29: add_grec (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision ⚠️</summary>

```c
struct sk_buff *add_grec(struct sk_buff *skb, struct ip_mc_list *pmc, int type, int gdeleted, int sdeleted);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffff800010cadd28)
Location: net/ipv4/igmp.c:459
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
```
```
In net/ipv6/mcast.c (ffff800010d2f090)
Location: net/ipv6/mcast.c:1730
Inline: False
Direct callers:
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
```
**Symbols:**

```
ffff800010cadd28-ffff800010cae188: add_grec (STB_LOCAL)
ffff800010d2f090-ffff800010d2f50c: add_grec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
struct sk_buff *add_grec(struct sk_buff *skb, struct ip_mc_list *pmc, int type, int gdeleted, int sdeleted);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (c0dbb110)
Location: net/ipv4/igmp.c:459
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
```
```
In net/ipv6/mcast.c (c0e32eec)
Location: net/ipv6/mcast.c:1730
Inline: False
Direct callers:
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
```
**Symbols:**

```
c0dbb110-c0dbb600: add_grec (STB_LOCAL)
c0e32eec-c0e333d4: add_grec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision ⚠️</summary>

```c
struct sk_buff *add_grec(struct sk_buff *skb, struct ip_mc_list *pmc, int type, int gdeleted, int sdeleted);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (c000000000dc4ff0)
Location: net/ipv4/igmp.c:459
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
```
```
In net/ipv6/mcast.c (c000000000e61de0)
Location: net/ipv6/mcast.c:1730
Inline: False
Direct callers:
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
```
**Symbols:**

```
c000000000dc4ff0-c000000000dc5644: add_grec (STB_LOCAL)
c000000000e61de0-c000000000e6246c: add_grec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision ⚠️</summary>

```c
struct sk_buff *add_grec(struct sk_buff *skb, struct ip_mc_list *pmc, int type, int gdeleted, int sdeleted);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffe00080876e)
Location: net/ipv4/igmp.c:459
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
```
```
In net/ipv6/mcast.c (ffffffe00086ef38)
Location: net/ipv6/mcast.c:1730
Inline: False
Direct callers:
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
```
**Symbols:**

```
ffffffe00080876e-ffffffe000808afc: add_grec (STB_LOCAL)
ffffffe00086ef38-ffffffe00086f2d0: add_grec (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision ⚠️</summary>

```c
struct sk_buff *add_grec(struct sk_buff *skb, struct ip_mc_list *pmc, int type, int gdeleted, int sdeleted);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81997930)
Location: net/ipv4/igmp.c:459
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
```
```
In net/ipv6/mcast.c (ffffffff81a08120)
Location: net/ipv6/mcast.c:1730
Inline: False
Direct callers:
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
```
**Symbols:**

```
ffffffff81997930-ffffffff81997dff: add_grec (STB_LOCAL)
ffffffff81a08120-ffffffff81a08621: add_grec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision ⚠️</summary>

```c
struct sk_buff *add_grec(struct sk_buff *skb, struct ip_mc_list *pmc, int type, int gdeleted, int sdeleted);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff819513f0)
Location: net/ipv4/igmp.c:459
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
```
```
In net/ipv6/mcast.c (ffffffff819c4ee0)
Location: net/ipv6/mcast.c:1730
Inline: False
Direct callers:
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
```
**Symbols:**

```
ffffffff819513f0-ffffffff819518bf: add_grec (STB_LOCAL)
ffffffff819c4ee0-ffffffff819c53e1: add_grec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision ⚠️</summary>

```c
struct sk_buff *add_grec(struct sk_buff *skb, struct ip_mc_list *pmc, int type, int gdeleted, int sdeleted);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81a021d0)
Location: net/ipv4/igmp.c:459
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
```
```
In net/ipv6/mcast.c (ffffffff81a72ba0)
Location: net/ipv6/mcast.c:1730
Inline: False
Direct callers:
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
```
**Symbols:**

```
ffffffff81a021d0-ffffffff81a0269f: add_grec (STB_LOCAL)
ffffffff81a72ba0-ffffffff81a730a1: add_grec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision ⚠️</summary>

```c
struct sk_buff *add_grec(struct sk_buff *skb, struct ip_mc_list *pmc, int type, int gdeleted, int sdeleted);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81a0c6f0)
Location: net/ipv4/igmp.c:459
Inline: False
Direct callers:
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_report
  - net/ipv4/igmp.c:igmpv3_send_report
```
```
In net/ipv6/mcast.c (ffffffff81a7f220)
Location: net/ipv6/mcast.c:1730
Inline: False
Direct callers:
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_ifc_timer_expire
  - net/ipv6/mcast.c:mld_send_report
  - net/ipv6/mcast.c:mld_send_report
```
**Symbols:**

```
ffffffff81a0c6f0-ffffffff81a0cbbf: add_grec (STB_LOCAL)
ffffffff81a7f220-ffffffff81a7f721: add_grec (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
