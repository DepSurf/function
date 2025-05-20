# Function: <code>rt_genid_bump_ipv4</code>

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
In security/selinux/ss/services.c (ffffffff813593bc)
Location: include/net/net_namespace.h:343
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_set_bools
```
```
In net/ipv4/route.c (ffffffff817530f1)
Location: include/net/net_namespace.h:343
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ip_rt_multicast_event
```
```
In net/xfrm/xfrm_policy.c (ffffffff817b44ce)
Location: include/net/net_namespace.h:343
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
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
In security/selinux/ss/services.c (ffffffff8138f994)
Location: include/net/net_namespace.h:346
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
```
In net/ipv4/route.c (ffffffff817bf271)
Location: include/net/net_namespace.h:346
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ip_rt_multicast_event
```
```
In net/xfrm/xfrm_policy.c (ffffffff81821682)
Location: include/net/net_namespace.h:346
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
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
In security/selinux/ss/services.c (ffffffff813a65b4)
Location: include/net/net_namespace.h:347
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
```
In net/ipv4/route.c (ffffffff817eebc1)
Location: include/net/net_namespace.h:347
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ip_rt_multicast_event
```
```
In net/xfrm/xfrm_policy.c (ffffffff81852e92)
Location: include/net/net_namespace.h:347
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
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
In security/selinux/ss/services.c (ffffffff813bd008)
Location: include/net/net_namespace.h:355
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
```
In net/ipv4/route.c (ffffffff8180ec81)
Location: include/net/net_namespace.h:355
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ip_rt_multicast_event
```
```
In net/xfrm/xfrm_policy.c (ffffffff81876ae1)
Location: include/net/net_namespace.h:355
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
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
In security/selinux/ss/services.c (ffffffff813e3174)
Location: include/net/net_namespace.h:367
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
```
In net/ipv4/route.c (ffffffff8188e241)
Location: include/net/net_namespace.h:367
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ip_rt_multicast_event
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f68d2)
Location: include/net/net_namespace.h:367
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
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
In security/selinux/ss/services.c (ffffffff81413904)
Location: include/net/net_namespace.h:405
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
```
In net/ipv4/route.c (ffffffff818e1f5d)
Location: include/net/net_namespace.h:405
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ip_rt_multicast_event
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194db6f)
Location: include/net/net_namespace.h:405
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
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
In security/selinux/ss/services.c (ffffffff8142fe31)
Location: include/net/net_namespace.h:408
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
```
In net/ipv4/route.c (ffffffff8190edfd)
Location: include/net/net_namespace.h:408
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ip_rt_multicast_event
```
```
In net/xfrm/xfrm_policy.c (ffffffff81980eca)
Location: include/net/net_namespace.h:408
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
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
In security/selinux/ss/services.c (ffffffff8145d7c6)
Location: include/net/net_namespace.h:422
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
```
In net/ipv4/route.c (ffffffff81970911)
Location: include/net/net_namespace.h:422
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ip_rt_multicast_event
```
```
In net/xfrm/xfrm_policy.c (ffffffff819eacc4)
Location: include/net/net_namespace.h:422
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
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
In security/selinux/ss/services.c (ffffffff81477576)
Location: include/net/net_namespace.h:431
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
```
In net/ipv4/route.c (ffffffff819a7311)
Location: include/net/net_namespace.h:431
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ip_rt_multicast_event
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a21cc4)
Location: include/net/net_namespace.h:431
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
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
In security/selinux/ss/services.c (ffffffff814cc9b0)
Location: include/net/net_namespace.h:449
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
```
In net/ipv4/route.c (ffffffff81a90661)
Location: include/net/net_namespace.h:449
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ip_rt_multicast_event
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b13607)
Location: include/net/net_namespace.h:449
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
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
In security/selinux/ss/services.c (ffffffff814e5a34)
Location: include/net/net_namespace.h:443
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_notify_policy_change
```
```
In net/ipv4/route.c (ffffffff81a9a4d1)
Location: include/net/net_namespace.h:443
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ip_rt_multicast_event
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b219c4)
Location: include/net/net_namespace.h:443
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
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
In security/selinux/ss/services.c (ffffffff814ec314)
Location: include/net/net_namespace.h:443
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_notify_policy_change
```
```
In net/ipv4/route.c (ffffffff81a857c1)
Location: include/net/net_namespace.h:443
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ip_rt_multicast_event
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0f5e4)
Location: include/net/net_namespace.h:443
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
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
In security/selinux/ss/services.c (ffffffff815460b4)
Location: include/net/net_namespace.h:445
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_notify_policy_change
```
```
In net/ipv4/route.c (ffffffff81b3ff91)
Location: include/net/net_namespace.h:445
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ip_rt_multicast_event
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd2a2b)
Location: include/net/net_namespace.h:445
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
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
In security/selinux/ss/services.c (ffffffff815de9ef)
Location: include/net/net_namespace.h:479
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_notify_policy_change
```
```
In net/ipv4/route.c (ffffffff81ccc861)
Location: include/net/net_namespace.h:479
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ip_rt_multicast_event
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d69784)
Location: include/net/net_namespace.h:479
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
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
In security/selinux/ss/services.c (ffffffff8168d70f)
Location: include/net/net_namespace.h:501
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_notify_policy_change
```
```
In net/ipv4/route.c (ffffffff81e8c801)
Location: include/net/net_namespace.h:501
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ip_rt_multicast_event
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f34a84)
Location: include/net/net_namespace.h:501
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
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
In security/selinux/ss/services.c (ffffffff816c59e3)
Location: include/net/net_namespace.h:501
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_notify_policy_change
```
```
In net/ipv4/route.c (ffffffff81eeaf51)
Location: include/net/net_namespace.h:501
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ip_rt_multicast_event
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f946a4)
Location: include/net/net_namespace.h:501
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
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
In security/selinux/ss/services.c (ffffffff81702633)
Location: include/net/net_namespace.h:514
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_notify_policy_change
```
```
In net/ipv4/route.c (ffffffff81faef71)
Location: include/net/net_namespace.h:514
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ip_rt_multicast_event
```
```
In net/xfrm/xfrm_policy.c (ffffffff82061a94)
Location: include/net/net_namespace.h:514
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
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
In security/selinux/ss/services.c (ffff800010567218)
Location: include/net/net_namespace.h:431
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
```
In net/ipv4/route.c (ffff800010c5877c)
Location: include/net/net_namespace.h:431
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ip_rt_multicast_event
```
```
In net/xfrm/xfrm_policy.c (ffff800010cde0a8)
Location: include/net/net_namespace.h:431
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
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
In security/selinux/ss/services.c (c071b78c)
Location: include/net/net_namespace.h:431
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
```
In net/ipv4/route.c (c0d66768)
Location: include/net/net_namespace.h:431
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ip_rt_multicast_event
```
```
In net/xfrm/xfrm_policy.c (c0de8250)
Location: include/net/net_namespace.h:431
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
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
In security/selinux/ss/services.c (c0000000006ca540)
Location: include/net/net_namespace.h:431
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
```
In net/ipv4/route.c (c000000000d57db4)
Location: include/net/net_namespace.h:431
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ip_rt_multicast_event
```
```
In net/xfrm/xfrm_policy.c (c000000000dff490)
Location: include/net/net_namespace.h:431
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
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
In security/selinux/ss/services.c (ffffffe0003bcf92)
Location: include/net/net_namespace.h:431
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
```
In net/ipv4/route.c (ffffffe0007c0f4e)
Location: include/net/net_namespace.h:431
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ip_rt_multicast_event
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082dac8)
Location: include/net/net_namespace.h:431
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
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
In security/selinux/ss/services.c (ffffffff8146fb56)
Location: include/net/net_namespace.h:431
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
```
In net/ipv4/route.c (ffffffff81947181)
Location: include/net/net_namespace.h:431
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ip_rt_multicast_event
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c1354)
Location: include/net/net_namespace.h:431
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
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
In security/selinux/ss/services.c (ffffffff81460560)
Location: include/net/net_namespace.h:431
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
```
In net/ipv4/route.c (ffffffff81900c71)
Location: include/net/net_namespace.h:431
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ip_rt_multicast_event
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197e144)
Location: include/net/net_namespace.h:431
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
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
In security/selinux/ss/services.c (ffffffff8146bbf6)
Location: include/net/net_namespace.h:431
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
```
In net/ipv4/route.c (ffffffff819b1951)
Location: include/net/net_namespace.h:431
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ip_rt_multicast_event
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2bdd4)
Location: include/net/net_namespace.h:431
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
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
In security/selinux/ss/services.c (ffffffff81483392)
Location: include/net/net_namespace.h:431
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
```
In net/ipv4/route.c (ffffffff819baff1)
Location: include/net/net_namespace.h:431
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ip_rt_multicast_event
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a374a4)
Location: include/net/net_namespace.h:431
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
```
</details>
</li>
</ul>

## Differences
