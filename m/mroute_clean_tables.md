# Function: <code>mroute_clean_tables</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision ⚠️</summary>

```c
void mroute_clean_tables(struct mr_table *mrt, bool all);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff817a8960)
Location: net/ipv4/ipmr.c:1203
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:ipmr_net_exit
```
```
In net/ipv6/ip6mr.c (ffffffff817f96d0)
Location: net/ipv6/ip6mr.c:1541
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
  - net/ipv6/ip6mr.c:ip6mr_sk_done
```
**Symbols:**

```
ffffffff817a8960-ffffffff817a8b10: mroute_clean_tables (STB_LOCAL)
ffffffff817f96d0-ffffffff817f98a6: mroute_clean_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision ⚠️</summary>

```c
void mroute_clean_tables(struct mr_table *mrt, bool all);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81816130)
Location: net/ipv4/ipmr.c:1187
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:mrtsock_destruct
```
```
In net/ipv6/ip6mr.c (ffffffff81868f10)
Location: net/ipv6/ip6mr.c:1543
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
```
**Symbols:**

```
ffffffff81816130-ffffffff818162f5: mroute_clean_tables (STB_LOCAL)
ffffffff81868f10-ffffffff818690fc: mroute_clean_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision ⚠️</summary>

```c
void mroute_clean_tables(struct mr_table *mrt, bool all);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff818478e0)
Location: net/ipv4/ipmr.c:1192
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:mrtsock_destruct
```
```
In net/ipv6/ip6mr.c (ffffffff8189bd60)
Location: net/ipv6/ip6mr.c:1543
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
```
**Symbols:**

```
ffffffff818478e0-ffffffff81847aa5: mroute_clean_tables (STB_LOCAL)
ffffffff8189bd60-ffffffff8189bf4c: mroute_clean_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision ⚠️</summary>

```c
void mroute_clean_tables(struct mr_table *mrt, bool all);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff8186b170)
Location: net/ipv4/ipmr.c:1246
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:ipmr_free_table
```
```
In net/ipv6/ip6mr.c (ffffffff818c2120)
Location: net/ipv6/ip6mr.c:1546
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
```
**Symbols:**

```
ffffffff8186b170-ffffffff8186b4c7: mroute_clean_tables (STB_LOCAL)
ffffffff818c2120-ffffffff818c2310: mroute_clean_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision ⚠️</summary>

```c
void mroute_clean_tables(struct mr_table *mrt, bool all);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff818eb910)
Location: net/ipv4/ipmr.c:1377
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:ipmr_free_table
```
```
In net/ipv6/ip6mr.c (ffffffff81945a60)
Location: net/ipv6/ip6mr.c:1546
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
```
**Symbols:**

```
ffffffff818eb910-ffffffff818ebca6: mroute_clean_tables (STB_LOCAL)
ffffffff81945a60-ffffffff81945c50: mroute_clean_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision ⚠️</summary>

```c
void mroute_clean_tables(struct mr_table *mrt, bool all);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff819420d0)
Location: net/ipv4/ipmr.c:1296
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:ipmr_free_table
```
```
In net/ipv6/ip6mr.c (ffffffff8199e820)
Location: net/ipv6/ip6mr.c:1481
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_free_table
```
**Symbols:**

```
ffffffff819420d0-ffffffff819424d1: mroute_clean_tables (STB_LOCAL)
ffffffff8199e820-ffffffff8199ec20: mroute_clean_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision ⚠️</summary>

```c
void mroute_clean_tables(struct mr_table *mrt, bool all);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81971ed0)
Location: net/ipv4/ipmr.c:1302
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:ipmr_free_table
```
```
In net/ipv6/ip6mr.c (ffffffff819d51d0)
Location: net/ipv6/ip6mr.c:1499
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_free_table
```
**Symbols:**

```
ffffffff81971ed0-ffffffff819722ce: mroute_clean_tables (STB_LOCAL)
ffffffff819d51d0-ffffffff819d55c0: mroute_clean_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision ⚠️</summary>

```c
void mroute_clean_tables(struct mr_table *mrt, int flags);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff819db7d0)
Location: net/ipv4/ipmr.c:1294
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:ipmr_free_table
```
```
In net/ipv6/ip6mr.c (ffffffff81a43ff0)
Location: net/ipv6/ip6mr.c:1494
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_free_table
```
**Symbols:**

```
ffffffff819db7d0-ffffffff819dbcc8: mroute_clean_tables (STB_LOCAL)
ffffffff81a43ff0-ffffffff81a444d4: mroute_clean_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision ⚠️</summary>

```c
void mroute_clean_tables(struct mr_table *mrt, int flags);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81a12700)
Location: net/ipv4/ipmr.c:1294
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:ipmr_free_table
```
```
In net/ipv6/ip6mr.c (ffffffff81a7abe0)
Location: net/ipv6/ip6mr.c:1494
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_free_table
```
**Symbols:**

```
ffffffff81a12700-ffffffff81a12bf8: mroute_clean_tables (STB_LOCAL)
ffffffff81a7abe0-ffffffff81a7b0c4: mroute_clean_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision ⚠️</summary>

```c
void mroute_clean_tables(struct mr_table *mrt, int flags);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81b03d20)
Location: net/ipv4/ipmr.c:1262
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:ipmr_rules_exit
```
```
In net/ipv6/ip6mr.c (ffffffff81b75400)
Location: net/ipv6/ip6mr.c:1499
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
```
**Symbols:**

```
ffffffff81b03d20-ffffffff81b04086: mroute_clean_tables (STB_LOCAL)
ffffffff81b75400-ffffffff81b75776: mroute_clean_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision ⚠️</summary>

```c
void mroute_clean_tables(struct mr_table *mrt, int flags);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81b11e90)
Location: net/ipv4/ipmr.c:1269
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:ipmr_rules_exit
```
```
In net/ipv6/ip6mr.c (ffffffff81b84170)
Location: net/ipv6/ip6mr.c:1499
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
```
**Symbols:**

```
ffffffff81b11e90-ffffffff81b121fb: mroute_clean_tables (STB_LOCAL)
ffffffff81b84170-ffffffff81b844eb: mroute_clean_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision ⚠️</summary>

```c
void mroute_clean_tables(struct mr_table *mrt, int flags);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81aff5c0)
Location: net/ipv4/ipmr.c:1269
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:ipmr_rules_exit
```
```
In net/ipv6/ip6mr.c (ffffffff81b72df0)
Location: net/ipv6/ip6mr.c:1499
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
```
**Symbols:**

```
ffffffff81aff5c0-ffffffff81aff94a: mroute_clean_tables (STB_LOCAL)
ffffffff81b72df0-ffffffff81b73186: mroute_clean_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Transformation ⚠️</summary>

```c
void mroute_clean_tables(struct mr_table *mrt, int flags);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:1271
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:ipmr_rules_exit
```
```
In net/ipv6/ip6mr.c (0)
Location: net/ipv6/ip6mr.c:1500
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
```
**Symbols:**

```
ffffffff81bc1360-ffffffff81bc1749: mroute_clean_tables (STB_LOCAL)
ffffffff81d3eab6-ffffffff81d3ead7: mroute_clean_tables.cold (STB_LOCAL)
ffffffff81c3d340-ffffffff81c3d73c: mroute_clean_tables (STB_LOCAL)
ffffffff81d41320-ffffffff81d41349: mroute_clean_tables.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Transformation ⚠️</summary>

```c
void mroute_clean_tables(struct mr_table *mrt, int flags);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:1265
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:ipmr_rules_exit
```
```
In net/ipv6/ip6mr.c (0)
Location: net/ipv6/ip6mr.c:1509
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
```
**Symbols:**

```
ffffffff81d568e0-ffffffff81d56c94: mroute_clean_tables (STB_LOCAL)
ffffffff81f0b40d-ffffffff81f0b422: mroute_clean_tables.cold (STB_LOCAL)
ffffffff81ddbd10-ffffffff81ddc0bc: mroute_clean_tables (STB_LOCAL)
ffffffff81f0dc6c-ffffffff81f0dc89: mroute_clean_tables.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Transformation ⚠️</summary>

```c
void mroute_clean_tables(struct mr_table *mrt, int flags);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:1279
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:ipmr_rules_exit
```
```
In net/ipv6/ip6mr.c (0)
Location: net/ipv6/ip6mr.c:1518
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
```
**Symbols:**

```
ffffffff81f211b0-ffffffff81f21564: mroute_clean_tables (STB_LOCAL)
ffffffff820b2ce4-ffffffff820b2cf9: mroute_clean_tables.cold (STB_LOCAL)
ffffffff81faef20-ffffffff81faf2cc: mroute_clean_tables (STB_LOCAL)
ffffffff820b50f3-ffffffff820b5110: mroute_clean_tables.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Transformation ⚠️</summary>

```c
void mroute_clean_tables(struct mr_table *mrt, int flags);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:1279
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:ipmr_rules_exit
```
```
In net/ipv6/ip6mr.c (0)
Location: net/ipv6/ip6mr.c:1518
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
```
**Symbols:**

```
ffffffff81f80450-ffffffff81f807ff: mroute_clean_tables (STB_LOCAL)
ffffffff82133e74-ffffffff82133e89: mroute_clean_tables.cold (STB_LOCAL)
ffffffff8200ecf0-ffffffff8200f099: mroute_clean_tables (STB_LOCAL)
ffffffff82135fa3-ffffffff82135fc0: mroute_clean_tables.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Transformation ⚠️</summary>

```c
void mroute_clean_tables(struct mr_table *mrt, int flags);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:1278
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:ipmr_rules_exit
```
```
In net/ipv6/ip6mr.c (0)
Location: net/ipv6/ip6mr.c:1518
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_rules_exit
```
**Symbols:**

```
ffffffff82046ad0-ffffffff82046e7f: mroute_clean_tables (STB_LOCAL)
ffffffff82215880-ffffffff82215895: mroute_clean_tables.cold (STB_LOCAL)
ffffffff820ddc80-ffffffff820de029: mroute_clean_tables (STB_LOCAL)
ffffffff82217bd8-ffffffff82217bf5: mroute_clean_tables.cold (STB_LOCAL)
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
void mroute_clean_tables(struct mr_table *mrt, int flags);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffff800010ccbdd0)
Location: net/ipv4/ipmr.c:1294
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:ipmr_free_table
```
```
In net/ipv6/ip6mr.c (ffff800010d44978)
Location: net/ipv6/ip6mr.c:1494
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_free_table
```
**Symbols:**

```
ffff800010ccbdd0-ffff800010ccc374: mroute_clean_tables (STB_LOCAL)
ffff800010d44978-ffff800010d44fa8: mroute_clean_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
void mroute_clean_tables(struct mr_table *mrt, int flags);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (c0dd7b68)
Location: net/ipv4/ipmr.c:1294
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:ipmr_free_table
```
```
In net/ipv6/ip6mr.c (c0e46e30)
Location: net/ipv6/ip6mr.c:1494
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_free_table
```
**Symbols:**

```
c0dd7b68-c0dd8174: mroute_clean_tables (STB_LOCAL)
c0e46e30-c0e47428: mroute_clean_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision ⚠️</summary>

```c
void mroute_clean_tables(struct mr_table *mrt, int flags);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (c000000000deb0b0)
Location: net/ipv4/ipmr.c:1294
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:ipmr_free_table
```
```
In net/ipv6/ip6mr.c (c000000000e79240)
Location: net/ipv6/ip6mr.c:1494
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_free_table
```
**Symbols:**

```
c000000000deb0b0-c000000000deb804: mroute_clean_tables (STB_LOCAL)
c000000000e79240-c000000000e79a34: mroute_clean_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision ⚠️</summary>

```c
void mroute_clean_tables(struct mr_table *mrt, int flags);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffe000820720)
Location: net/ipv4/ipmr.c:1294
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:ipmr_free_table
```
```
In net/ipv6/ip6mr.c (ffffffe00087f2e6)
Location: net/ipv6/ip6mr.c:1494
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_free_table
```
**Symbols:**

```
ffffffe000820720-ffffffe000820bfe: mroute_clean_tables (STB_LOCAL)
ffffffe00087f2e6-ffffffe00087f886: mroute_clean_tables (STB_LOCAL)
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
void mroute_clean_tables(struct mr_table *mrt, int flags);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff819b1fc0)
Location: net/ipv4/ipmr.c:1294
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:ipmr_free_table
```
```
In net/ipv6/ip6mr.c (ffffffff81a1a270)
Location: net/ipv6/ip6mr.c:1494
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_free_table
```
**Symbols:**

```
ffffffff819b1fc0-ffffffff819b24b8: mroute_clean_tables (STB_LOCAL)
ffffffff81a1a270-ffffffff81a1a754: mroute_clean_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision ⚠️</summary>

```c
void mroute_clean_tables(struct mr_table *mrt, int flags);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff8196e5f0)
Location: net/ipv4/ipmr.c:1294
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:ipmr_free_table
```
```
In net/ipv6/ip6mr.c (ffffffff819d7030)
Location: net/ipv6/ip6mr.c:1494
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_free_table
```
**Symbols:**

```
ffffffff8196e5f0-ffffffff8196eae8: mroute_clean_tables (STB_LOCAL)
ffffffff819d7030-ffffffff819d7514: mroute_clean_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision ⚠️</summary>

```c
void mroute_clean_tables(struct mr_table *mrt, int flags);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81a1c860)
Location: net/ipv4/ipmr.c:1294
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:ipmr_free_table
```
```
In net/ipv6/ip6mr.c (ffffffff81a84cf0)
Location: net/ipv6/ip6mr.c:1494
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_free_table
```
**Symbols:**

```
ffffffff81a1c860-ffffffff81a1cd58: mroute_clean_tables (STB_LOCAL)
ffffffff81a84cf0-ffffffff81a851d4: mroute_clean_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision ⚠️</summary>

```c
void mroute_clean_tables(struct mr_table *mrt, int flags);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81a27820)
Location: net/ipv4/ipmr.c:1294
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
  - net/ipv4/ipmr.c:mrtsock_destruct
  - net/ipv4/ipmr.c:ipmr_free_table
```
```
In net/ipv6/ip6mr.c (ffffffff81a91670)
Location: net/ipv6/ip6mr.c:1494
Inline: False
Direct callers:
  - net/ipv6/ip6mr.c:ip6_mroute_setsockopt
  - net/ipv6/ip6mr.c:ip6mr_sk_done
  - net/ipv6/ip6mr.c:ip6mr_free_table
```
**Symbols:**

```
ffffffff81a27820-ffffffff81a27d7b: mroute_clean_tables (STB_LOCAL)
ffffffff81a91670-ffffffff81a91bbd: mroute_clean_tables (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int flags</code>
</li>
<li>
<b>Param removed. </b>
<code>bool all</code>
</li>
</ul>
</details>
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
