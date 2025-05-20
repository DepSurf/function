# Function: <code>ipv4_devconf_set</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffff8178c74c)
Location: include/linux/inetdevice.h:59
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
```
```
In net/ipv4/devinet.c (ffffffff8178f8ad)
Location: include/linux/inetdevice.h:59
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:devinet_sysctl_forward
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffff817f9d47)
Location: include/linux/inetdevice.h:59
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
```
```
In net/ipv4/devinet.c (ffffffff8180057f)
Location: include/linux/inetdevice.h:59
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffff8182ac17)
Location: include/linux/inetdevice.h:59
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
```
```
In net/ipv4/devinet.c (ffffffff818314df)
Location: include/linux/inetdevice.h:59
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffff8184bea9)
Location: include/linux/inetdevice.h:60
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
```
```
In net/ipv4/devinet.c (ffffffff81852a83)
Location: include/linux/inetdevice.h:60
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffff818cbb4f)
Location: include/linux/inetdevice.h:61
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
```
```
In net/ipv4/devinet.c (ffffffff818d2893)
Location: include/linux/inetdevice.h:61
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffff8192202f)
Location: include/linux/inetdevice.h:61
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
```
```
In net/ipv4/devinet.c (ffffffff81928e3c)
Location: include/linux/inetdevice.h:61
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffff81950e5f)
Location: include/linux/inetdevice.h:63
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
```
```
In net/ipv4/devinet.c (ffffffff8195812c)
Location: include/linux/inetdevice.h:63
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffff819b572c)
Location: include/linux/inetdevice.h:63
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
```
```
In net/ipv4/devinet.c (ffffffff819bcb7c)
Location: include/linux/inetdevice.h:63
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffff819ec44c)
Location: include/linux/inetdevice.h:63
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
```
```
In net/ipv4/devinet.c (ffffffff819f386c)
Location: include/linux/inetdevice.h:63
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffff81ada3a1)
Location: include/linux/inetdevice.h:63
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
```
```
In net/ipv4/devinet.c (ffffffff81ae1172)
Location: include/linux/inetdevice.h:63
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_forward_change
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffff81ae6e41)
Location: include/linux/inetdevice.h:63
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
```
```
In net/ipv4/devinet.c (ffffffff81aee012)
Location: include/linux/inetdevice.h:63
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_forward_change
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffff81ad210e)
Location: include/linux/inetdevice.h:63
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
```
```
In net/ipv4/devinet.c (ffffffff81ad987c)
Location: include/linux/inetdevice.h:63
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffff81b90d5e)
Location: include/linux/inetdevice.h:63
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
```
```
In net/ipv4/devinet.c (ffffffff81b989ac)
Location: include/linux/inetdevice.h:63
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffff81d23716)
Location: include/linux/inetdevice.h:65
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
```
```
In net/ipv4/devinet.c (ffffffff81d2a82b)
Location: include/linux/inetdevice.h:65
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffff81eead26)
Location: include/linux/inetdevice.h:65
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
```
```
In net/ipv4/devinet.c (ffffffff81ef233b)
Location: include/linux/inetdevice.h:65
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffff81f4a686)
Location: include/linux/inetdevice.h:65
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
```
```
In net/ipv4/devinet.c (ffffffff81f51e0b)
Location: include/linux/inetdevice.h:65
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffff82010796)
Location: include/linux/inetdevice.h:65
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
```
```
In net/ipv4/devinet.c (ffffffff820180de)
Location: include/linux/inetdevice.h:65
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffff800010ca1f94)
Location: include/linux/inetdevice.h:63
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
```
```
In net/ipv4/devinet.c (ffff800010ca9b78)
Location: include/linux/inetdevice.h:63
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (c0daed84)
Location: include/linux/inetdevice.h:63
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
```
```
In net/ipv4/devinet.c (c0db62f0)
Location: include/linux/inetdevice.h:63
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (c000000000db530c)
Location: include/linux/inetdevice.h:63
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
```
```
In net/ipv4/devinet.c (c000000000dbf0e0)
Location: include/linux/inetdevice.h:63
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffe0007fdbea)
Location: include/linux/inetdevice.h:63
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
```
```
In net/ipv4/devinet.c (ffffffe00080464c)
Location: include/linux/inetdevice.h:63
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffff8198c27c)
Location: include/linux/inetdevice.h:63
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
```
```
In net/ipv4/devinet.c (ffffffff8199360c)
Location: include/linux/inetdevice.h:63
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffff81945d3c)
Location: include/linux/inetdevice.h:63
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
```
```
In net/ipv4/devinet.c (ffffffff8194d0cc)
Location: include/linux/inetdevice.h:63
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffff819f6a8c)
Location: include/linux/inetdevice.h:63
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
```
```
In net/ipv4/devinet.c (ffffffff819fdeac)
Location: include/linux/inetdevice.h:63
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffff81a00cac)
Location: include/linux/inetdevice.h:63
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_req_delete
  - net/ipv4/arp.c:arp_req_set
```
```
In net/ipv4/devinet.c (ffffffff81a0823c)
Location: include/linux/inetdevice.h:63
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:inet_set_link_af
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
```
</details>
</li>
</ul>

## Differences
