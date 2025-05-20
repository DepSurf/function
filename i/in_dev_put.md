# Function: <code>in_dev_put</code>

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
In net/ipv4/devinet.c (ffffffff8179090a)
Location: include/linux/inetdevice.h:234
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:in_dev_rcu_put
  - net/ipv4/devinet.c:inet_rcu_free_ifa
```
```
In net/ipv4/igmp.c (ffffffff81796df7)
Location: include/linux/inetdevice.h:234
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_inc_group
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmp_gq_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
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
In net/ipv4/devinet.c (ffffffff817fef35)
Location: include/linux/inetdevice.h:234
Inline: True
Inline callers:
  - net/ipv4/devinet.c:in_dev_rcu_put
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_rcu_free_ifa
```
```
In net/ipv4/igmp.c (ffffffff81805c5b)
Location: include/linux/inetdevice.h:234
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_inc_group
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_gq_timer_expire
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
In net/ipv4/devinet.c (ffffffff8182fe95)
Location: include/linux/inetdevice.h:234
Inline: True
Inline callers:
  - net/ipv4/devinet.c:in_dev_rcu_put
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_rcu_free_ifa
```
```
In net/ipv4/igmp.c (ffffffff81835f55)
Location: include/linux/inetdevice.h:234
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_gq_timer_expire
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
In net/ipv4/devinet.c (ffffffff81850075)
Location: include/linux/inetdevice.h:242
Inline: True
Inline callers:
  - net/ipv4/devinet.c:in_dev_rcu_put
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_rcu_free_ifa
```
```
In net/ipv4/igmp.c (ffffffff81857455)
Location: include/linux/inetdevice.h:242
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_gq_timer_expire
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
In net/ipv4/devinet.c (ffffffff818cfca9)
Location: include/linux/inetdevice.h:245
Inline: True
Inline callers:
  - net/ipv4/devinet.c:in_dev_rcu_put
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_rcu_free_ifa
```
```
In net/ipv4/igmp.c (ffffffff818d7745)
Location: include/linux/inetdevice.h:245
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_gq_timer_expire
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
In net/ipv4/devinet.c (ffffffff81926175)
Location: include/linux/inetdevice.h:246
Inline: True
Inline callers:
  - net/ipv4/devinet.c:in_dev_rcu_put
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_rcu_free_ifa
```
```
In net/ipv4/igmp.c (ffffffff8192e927)
Location: include/linux/inetdevice.h:246
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_gq_timer_expire
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
In net/ipv4/devinet.c (ffffffff819551a5)
Location: include/linux/inetdevice.h:249
Inline: True
Inline callers:
  - net/ipv4/devinet.c:in_dev_rcu_put
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_rcu_free_ifa
```
```
In net/ipv4/igmp.c (ffffffff8195d577)
Location: include/linux/inetdevice.h:249
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_gq_timer_expire
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
In net/ipv4/devinet.c (ffffffff819b9a45)
Location: include/linux/inetdevice.h:262
Inline: True
Inline callers:
  - net/ipv4/devinet.c:in_dev_rcu_put
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_rcu_free_ifa
```
```
In net/ipv4/igmp.c (ffffffff819c2639)
Location: include/linux/inetdevice.h:262
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_gq_timer_expire
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
In net/ipv4/devinet.c (ffffffff819f1d45)
Location: include/linux/inetdevice.h:262
Inline: True
Inline callers:
  - net/ipv4/devinet.c:in_dev_rcu_put
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_rcu_free_ifa
```
```
In net/ipv4/igmp.c (ffffffff819f91d9)
Location: include/linux/inetdevice.h:262
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_gq_timer_expire
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
In net/ipv4/devinet.c (ffffffff81ade255)
Location: include/linux/inetdevice.h:262
Inline: True
Inline callers:
  - net/ipv4/devinet.c:in_dev_rcu_put
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_rcu_free_ifa
```
```
In net/ipv4/igmp.c (ffffffff81ae8f60)
Location: include/linux/inetdevice.h:262
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_destroy_dev
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_gq_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_cr
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
In net/ipv4/devinet.c (ffffffff81aeaea5)
Location: include/linux/inetdevice.h:262
Inline: True
Inline callers:
  - net/ipv4/devinet.c:in_dev_rcu_put
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_rcu_free_ifa
```
```
In net/ipv4/igmp.c (ffffffff81af34b3)
Location: include/linux/inetdevice.h:262
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_gq_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_cr
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
In net/ipv4/devinet.c (ffffffff81ad6615)
Location: include/linux/inetdevice.h:262
Inline: True
Inline callers:
  - net/ipv4/devinet.c:in_dev_rcu_put
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_rcu_free_ifa
```
```
In net/ipv4/igmp.c (ffffffff81adec73)
Location: include/linux/inetdevice.h:262
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_gq_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_cr
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
In net/ipv4/devinet.c (ffffffff81b95355)
Location: include/linux/inetdevice.h:271
Inline: True
Inline callers:
  - net/ipv4/devinet.c:in_dev_rcu_put
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_rcu_free_ifa
```
```
In net/ipv4/igmp.c (ffffffff81b9e153)
Location: include/linux/inetdevice.h:271
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_gq_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_cr
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
In net/ipv4/devinet.c (ffffffff81d26fd5)
Location: include/linux/inetdevice.h:276
Inline: True
Inline callers:
  - net/ipv4/devinet.c:in_dev_rcu_put
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_rcu_free_ifa
```
```
In net/ipv4/igmp.c (ffffffff81d30403)
Location: include/linux/inetdevice.h:276
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_gq_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_cr
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
In net/ipv4/devinet.c (ffffffff81ef25b6)
Location: include/linux/inetdevice.h:276
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_destroy
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_rcu_free_ifa
```
```
In net/ipv4/igmp.c (ffffffff81ef8533)
Location: include/linux/inetdevice.h:276
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_gq_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_cr
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
In net/ipv4/devinet.c (ffffffff81f52086)
Location: include/linux/inetdevice.h:276
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_destroy
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_rcu_free_ifa
```
```
In net/ipv4/igmp.c (ffffffff81f57fa3)
Location: include/linux/inetdevice.h:276
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_gq_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_cr
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
In net/ipv4/devinet.c (ffffffff82018366)
Location: include/linux/inetdevice.h:276
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_destroy
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_rcu_free_ifa
```
```
In net/ipv4/igmp.c (ffffffff8201e453)
Location: include/linux/inetdevice.h:276
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_gq_timer_expire
  - net/ipv4/igmp.c:igmpv3_send_cr
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
In net/ipv4/devinet.c (ffff800010ca666c)
Location: include/linux/inetdevice.h:262
Inline: True
Inline callers:
  - net/ipv4/devinet.c:in_dev_rcu_put
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_rcu_free_ifa
```
```
In net/ipv4/igmp.c (ffff800010caeefc)
Location: include/linux/inetdevice.h:262
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_gq_timer_expire
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
In net/ipv4/devinet.c (c0db2db8)
Location: include/linux/inetdevice.h:262
Inline: True
Inline callers:
  - net/ipv4/devinet.c:in_dev_rcu_put
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_rcu_free_ifa
```
```
In net/ipv4/igmp.c (c0dbbed8)
Location: include/linux/inetdevice.h:262
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_gq_timer_expire
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
In net/ipv4/devinet.c (c000000000dba780)
Location: include/linux/inetdevice.h:262
Inline: True
Inline callers:
  - net/ipv4/devinet.c:in_dev_rcu_put
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_rcu_free_ifa
```
```
In net/ipv4/igmp.c (c000000000dc59c4)
Location: include/linux/inetdevice.h:262
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_gq_timer_expire
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
In net/ipv4/devinet.c (ffffffe000800e40)
Location: include/linux/inetdevice.h:262
Inline: True
Inline callers:
  - net/ipv4/devinet.c:in_dev_rcu_put
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_rcu_free_ifa
```
```
In net/ipv4/igmp.c (ffffffe000807038)
Location: include/linux/inetdevice.h:262
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_gq_timer_expire
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
In net/ipv4/devinet.c (ffffffff81991ae5)
Location: include/linux/inetdevice.h:262
Inline: True
Inline callers:
  - net/ipv4/devinet.c:in_dev_rcu_put
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_rcu_free_ifa
```
```
In net/ipv4/igmp.c (ffffffff81998f79)
Location: include/linux/inetdevice.h:262
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_gq_timer_expire
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
In net/ipv4/devinet.c (ffffffff8194b5a5)
Location: include/linux/inetdevice.h:262
Inline: True
Inline callers:
  - net/ipv4/devinet.c:in_dev_rcu_put
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_rcu_free_ifa
```
```
In net/ipv4/igmp.c (ffffffff81952a39)
Location: include/linux/inetdevice.h:262
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_gq_timer_expire
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
In net/ipv4/devinet.c (ffffffff819fc385)
Location: include/linux/inetdevice.h:262
Inline: True
Inline callers:
  - net/ipv4/devinet.c:in_dev_rcu_put
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_rcu_free_ifa
```
```
In net/ipv4/igmp.c (ffffffff81a03819)
Location: include/linux/inetdevice.h:262
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_gq_timer_expire
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
In net/ipv4/devinet.c (ffffffff81a066f5)
Location: include/linux/inetdevice.h:262
Inline: True
Inline callers:
  - net/ipv4/devinet.c:in_dev_rcu_put
  - net/ipv4/devinet.c:inetdev_init
  - net/ipv4/devinet.c:inet_rcu_free_ifa
```
```
In net/ipv4/igmp.c (ffffffff81a0dd69)
Location: include/linux/inetdevice.h:262
Inline: True
Inline callers:
  - net/ipv4/igmp.c:igmpv3_clear_delrec
  - net/ipv4/igmp.c:igmpv3_del_delrec
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_ifc_timer_expire
  - net/ipv4/igmp.c:igmp_gq_timer_expire
```
</details>
</li>
</ul>

## Differences
