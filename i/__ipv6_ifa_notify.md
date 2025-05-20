# Function: <code>__ipv6_ifa_notify</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __ipv6_ifa_notify(int event, struct inet6_ifaddr *ifp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff817cc3c0)
Location: net/ipv6/addrconf.c:5128
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_ifdown
```
**Symbols:**

```
ffffffff817cc3c0-ffffffff817cc650: __ipv6_ifa_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __ipv6_ifa_notify(int event, struct inet6_ifaddr *ifp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81838e10)
Location: net/ipv6/addrconf.c:5386
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_ifdown
```
**Symbols:**

```
ffffffff81838e10-ffffffff818390a5: __ipv6_ifa_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __ipv6_ifa_notify(int event, struct inet6_ifaddr *ifp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8186a830)
Location: net/ipv6/addrconf.c:5438
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_ifdown
```
**Symbols:**

```
ffffffff8186a830-ffffffff8186aac5: __ipv6_ifa_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __ipv6_ifa_notify(int event, struct inet6_ifaddr *ifp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8188ed70)
Location: net/ipv6/addrconf.c:5542
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_ifdown
```
**Symbols:**

```
ffffffff8188ed70-ffffffff8188f035: __ipv6_ifa_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __ipv6_ifa_notify(int event, struct inet6_ifaddr *ifp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff819103c0)
Location: net/ipv6/addrconf.c:5548
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_ifdown
```
**Symbols:**

```
ffffffff819103c0-ffffffff8191068f: __ipv6_ifa_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __ipv6_ifa_notify(int event, struct inet6_ifaddr *ifp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81967800)
Location: net/ipv6/addrconf.c:5667
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_ifdown
```
**Symbols:**

```
ffffffff81967800-ffffffff81967aa1: __ipv6_ifa_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __ipv6_ifa_notify(int event, struct inet6_ifaddr *ifp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8199ceb0)
Location: net/ipv6/addrconf.c:5861
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_ifdown
```
**Symbols:**

```
ffffffff8199ceb0-ffffffff8199d195: __ipv6_ifa_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __ipv6_ifa_notify(int event, struct inet6_ifaddr *ifp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:5955
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_ifdown
```
**Symbols:**

```
ffffffff81a09090-ffffffff81a09370: __ipv6_ifa_notify (STB_LOCAL)
ffffffff81a1127f-ffffffff81a11298: __ipv6_ifa_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void __ipv6_ifa_notify(int event, struct inet6_ifaddr *ifp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:5987
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_ifdown
```
**Symbols:**

```
ffffffff81a3fd40-ffffffff81a40054: __ipv6_ifa_notify (STB_LOCAL)
ffffffff81a47fb4-ffffffff81a47fcf: __ipv6_ifa_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __ipv6_ifa_notify(int event, struct inet6_ifaddr *ifp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b3b3fc)
Location: net/ipv6/addrconf.c:6004
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:addrconf_dad_stop
Direct callers:
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
**Symbols:**

```
ffffffff81b358e0-ffffffff81b35c17: __ipv6_ifa_notify (STB_LOCAL)
ffffffff81b3eabb-ffffffff81b3ead7: __ipv6_ifa_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __ipv6_ifa_notify(int event, struct inet6_ifaddr *ifp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b4a10c)
Location: net/ipv6/addrconf.c:6035
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:addrconf_dad_stop
Direct callers:
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:ipv6_del_addr
```
**Symbols:**

```
ffffffff81b443d0-ffffffff81b44707: __ipv6_ifa_notify (STB_LOCAL)
ffffffff81c32b65-ffffffff81c32b81: __ipv6_ifa_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void __ipv6_ifa_notify(int event, struct inet6_ifaddr *ifp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:6063
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_del_addr
```
**Symbols:**

```
ffffffff81b31ea0-ffffffff81b321e7: __ipv6_ifa_notify (STB_LOCAL)
ffffffff81c24e75-ffffffff81c24e90: __ipv6_ifa_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __ipv6_ifa_notify(int event, struct inet6_ifaddr *ifp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:6110
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_del_addr
```
**Symbols:**

```
ffffffff81bf7f70-ffffffff81bf82c6: __ipv6_ifa_notify (STB_LOCAL)
ffffffff81d3f7c4-ffffffff81d3f7f4: __ipv6_ifa_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __ipv6_ifa_notify(int event, struct inet6_ifaddr *ifp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:6129
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_del_addr
```
**Symbols:**

```
ffffffff81d91310-ffffffff81d9174c: __ipv6_ifa_notify (STB_LOCAL)
ffffffff81f0c16a-ffffffff81f0c19a: __ipv6_ifa_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __ipv6_ifa_notify(int event, struct inet6_ifaddr *ifp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:6142
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_del_addr
```
**Symbols:**

```
ffffffff81f5fa70-ffffffff81f5fe01: __ipv6_ifa_notify (STB_LOCAL)
ffffffff820b3990-ffffffff820b39a5: __ipv6_ifa_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __ipv6_ifa_notify(int event, struct inet6_ifaddr *ifp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:6148
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_del_addr
```
**Symbols:**

```
ffffffff81fbf7a0-ffffffff81fbfc3b: __ipv6_ifa_notify (STB_LOCAL)
ffffffff82134a81-ffffffff82134a96: __ipv6_ifa_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __ipv6_ifa_notify(int event, struct inet6_ifaddr *ifp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:6201
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:inet6_addr_modify
  - net/ipv6/addrconf.c:addrconf_verify_rtnl
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:add_addr
  - net/ipv6/addrconf.c:inet6_addr_add
  - net/ipv6/addrconf.c:addrconf_prefix_rcv_add_addr
  - net/ipv6/addrconf.c:manage_tempaddrs
  - net/ipv6/addrconf.c:addrconf_dad_stop
  - net/ipv6/addrconf.c:ipv6_del_addr
```
**Symbols:**

```
ffffffff8208cc40-ffffffff8208d0e2: __ipv6_ifa_notify (STB_LOCAL)
ffffffff8221653f-ffffffff82216554: __ipv6_ifa_notify.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void __ipv6_ifa_notify(int event, struct inet6_ifaddr *ifp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffff800010d00fe8)
Location: net/ipv6/addrconf.c:5987
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_ifdown
```
**Symbols:**

```
ffff800010d00fe8-ffff800010d012b8: __ipv6_ifa_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __ipv6_ifa_notify(int event, struct inet6_ifaddr *ifp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (c0e08b08)
Location: net/ipv6/addrconf.c:5987
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_ifdown
```
**Symbols:**

```
c0e08b08-c0e08e44: __ipv6_ifa_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __ipv6_ifa_notify(int event, struct inet6_ifaddr *ifp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (c000000000e2ae60)
Location: net/ipv6/addrconf.c:5987
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_ifdown
```
**Symbols:**

```
c000000000e2ae60-c000000000e2b218: __ipv6_ifa_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __ipv6_ifa_notify(int event, struct inet6_ifaddr *ifp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffe00084af88)
Location: net/ipv6/addrconf.c:5987
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_ifdown
```
**Symbols:**

```
ffffffe00084af88-ffffffe00084b1e4: __ipv6_ifa_notify (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void __ipv6_ifa_notify(int event, struct inet6_ifaddr *ifp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:5987
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_ifdown
```
**Symbols:**

```
ffffffff819df3d0-ffffffff819df6e4: __ipv6_ifa_notify (STB_LOCAL)
ffffffff819e7644-ffffffff819e765f: __ipv6_ifa_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void __ipv6_ifa_notify(int event, struct inet6_ifaddr *ifp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:5987
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_ifdown
```
**Symbols:**

```
ffffffff8199c190-ffffffff8199c4a4: __ipv6_ifa_notify (STB_LOCAL)
ffffffff819a4404-ffffffff819a441f: __ipv6_ifa_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void __ipv6_ifa_notify(int event, struct inet6_ifaddr *ifp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:5987
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_ifdown
```
**Symbols:**

```
ffffffff81a49e50-ffffffff81a4a164: __ipv6_ifa_notify (STB_LOCAL)
ffffffff81a520c4-ffffffff81a520df: __ipv6_ifa_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void __ipv6_ifa_notify(int event, struct inet6_ifaddr *ifp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:5987
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_ifdown
```
**Symbols:**

```
ffffffff81a55d90-ffffffff81a560a4: __ipv6_ifa_notify (STB_LOCAL)
ffffffff81a5e014-ffffffff81a5e02f: __ipv6_ifa_notify.cold (STB_LOCAL)
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
