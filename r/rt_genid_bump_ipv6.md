# Function: <code>rt_genid_bump_ipv6</code>

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
In security/selinux/ss/services.c (ffffffff813593c3)
Location: include/net/net_namespace.h:349
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_set_bools
```
```
In net/xfrm/xfrm_policy.c (ffffffff817b42b1)
Location: include/net/net_namespace.h:349
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
```
```
In net/ipv6/addrconf.c (ffffffff817cc4cb)
Location: include/net/net_namespace.h:349
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
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
In security/selinux/ss/services.c (ffffffff8138f99b)
Location: include/net/net_namespace.h:352
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
```
In net/xfrm/xfrm_policy.c (ffffffff81821461)
Location: include/net/net_namespace.h:352
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
```
```
In net/ipv6/addrconf.c (ffffffff81838f20)
Location: include/net/net_namespace.h:352
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
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
In security/selinux/ss/services.c (ffffffff813a65bb)
Location: include/net/net_namespace.h:353
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
```
In net/xfrm/xfrm_policy.c (ffffffff81852c71)
Location: include/net/net_namespace.h:353
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
```
```
In net/ipv6/addrconf.c (ffffffff8186a940)
Location: include/net/net_namespace.h:353
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:add_addr
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
In security/selinux/ss/services.c (ffffffff813bd00f)
Location: include/net/net_namespace.h:361
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
```
In net/xfrm/xfrm_policy.c (ffffffff8187690e)
Location: include/net/net_namespace.h:361
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
```
```
In net/ipv6/addrconf.c (ffffffff8188ee9f)
Location: include/net/net_namespace.h:361
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:add_addr
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
In security/selinux/ss/services.c (ffffffff813e317b)
Location: include/net/net_namespace.h:373
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f66e9)
Location: include/net/net_namespace.h:373
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
```
```
In net/ipv6/addrconf.c (ffffffff819104ef)
Location: include/net/net_namespace.h:373
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:add_addr
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
In security/selinux/ss/services.c (ffffffff8141390b)
Location: include/net/net_namespace.h:411
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194d963)
Location: include/net/net_namespace.h:411
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
```
```
In net/ipv6/addrconf.c (ffffffff81967909)
Location: include/net/net_namespace.h:411
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:add_addr
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
In security/selinux/ss/services.c (ffffffff8142fe38)
Location: include/net/net_namespace.h:414
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
```
In net/xfrm/xfrm_policy.c (ffffffff81980df2)
Location: include/net/net_namespace.h:414
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
```
```
In net/ipv6/addrconf.c (ffffffff8199cfe5)
Location: include/net/net_namespace.h:414
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:add_addr
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
In security/selinux/ss/services.c (ffffffff8145d7cd)
Location: include/net/net_namespace.h:428
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
```
In net/xfrm/xfrm_policy.c (ffffffff819eaba3)
Location: include/net/net_namespace.h:428
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
```
```
In net/ipv6/addrconf.c (ffffffff81a091c7)
Location: include/net/net_namespace.h:428
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:add_addr
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
In security/selinux/ss/services.c (ffffffff8147757d)
Location: include/net/net_namespace.h:437
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a21ba3)
Location: include/net/net_namespace.h:437
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
```
```
In net/ipv6/addrconf.c (ffffffff81a3fe77)
Location: include/net/net_namespace.h:437
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:add_addr
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
In security/selinux/ss/services.c (ffffffff814cc9b7)
Location: include/net/net_namespace.h:455
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b134de)
Location: include/net/net_namespace.h:455
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
```
```
In net/ipv6/addrconf.c (ffffffff81b3bddd)
Location: include/net/net_namespace.h:455
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:add_addr
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
In security/selinux/ss/services.c (ffffffff814e5a3b)
Location: include/net/net_namespace.h:449
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_notify_policy_change
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b21898)
Location: include/net/net_namespace.h:449
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
```
```
In net/ipv6/addrconf.c (ffffffff81b4aaed)
Location: include/net/net_namespace.h:449
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:add_addr
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
In security/selinux/ss/services.c (ffffffff814ec31b)
Location: include/net/net_namespace.h:449
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_notify_policy_change
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0f4b8)
Location: include/net/net_namespace.h:449
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
```
```
In net/ipv6/addrconf.c (ffffffff81b32002)
Location: include/net/net_namespace.h:449
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:add_addr
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
In security/selinux/ss/services.c (ffffffff815460bb)
Location: include/net/net_namespace.h:451
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_notify_policy_change
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd28e8)
Location: include/net/net_namespace.h:451
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
```
```
In net/ipv6/addrconf.c (ffffffff81bf80d2)
Location: include/net/net_namespace.h:451
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:add_addr
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
In security/selinux/ss/services.c (ffffffff815de9f6)
Location: include/net/net_namespace.h:485
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_notify_policy_change
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d69628)
Location: include/net/net_namespace.h:485
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
```
```
In net/ipv6/addrconf.c (ffffffff81d91482)
Location: include/net/net_namespace.h:485
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:add_addr
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
In security/selinux/ss/services.c (ffffffff8168d716)
Location: include/net/net_namespace.h:507
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_notify_policy_change
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f34928)
Location: include/net/net_namespace.h:507
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
```
```
In net/ipv6/addrconf.c (ffffffff81f5fbe2)
Location: include/net/net_namespace.h:507
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:add_addr
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
In security/selinux/ss/services.c (ffffffff816c59ea)
Location: include/net/net_namespace.h:507
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_notify_policy_change
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f94548)
Location: include/net/net_namespace.h:507
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
```
```
In net/ipv6/addrconf.c (ffffffff81fbf912)
Location: include/net/net_namespace.h:507
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:add_addr
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
In security/selinux/ss/services.c (ffffffff8170263a)
Location: include/net/net_namespace.h:520
Inline: True
Inline callers:
  - security/selinux/ss/services.c:selinux_notify_policy_change
```
```
In net/xfrm/xfrm_policy.c (ffffffff82061938)
Location: include/net/net_namespace.h:520
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
```
```
In net/ipv6/addrconf.c (ffffffff8208cdb2)
Location: include/net/net_namespace.h:520
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:add_addr
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
In security/selinux/ss/services.c (ffff80001056722c)
Location: include/net/net_namespace.h:437
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
```
In net/xfrm/xfrm_policy.c (ffff800010cddee0)
Location: include/net/net_namespace.h:437
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
```
```
In net/ipv6/addrconf.c (ffff800010d010f4)
Location: include/net/net_namespace.h:437
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:add_addr
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
In security/selinux/ss/services.c (c071b7a8)
Location: include/net/net_namespace.h:437
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
```
In net/xfrm/xfrm_policy.c (c0de8114)
Location: include/net/net_namespace.h:437
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
```
```
In net/ipv6/addrconf.c (c0e08c30)
Location: include/net/net_namespace.h:437
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:add_addr
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
In security/selinux/ss/services.c (c0000000006ca554)
Location: include/net/net_namespace.h:437
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
```
In net/xfrm/xfrm_policy.c (c000000000dff2f8)
Location: include/net/net_namespace.h:437
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
```
```
In net/ipv6/addrconf.c (c000000000e2af9c)
Location: include/net/net_namespace.h:437
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:add_addr
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
In security/selinux/ss/services.c (ffffffe0003bcfa4)
Location: include/net/net_namespace.h:437
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082d9c6)
Location: include/net/net_namespace.h:437
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
```
```
In net/ipv6/addrconf.c (ffffffe00084b06a)
Location: include/net/net_namespace.h:437
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:add_addr
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
In security/selinux/ss/services.c (ffffffff8146fb5d)
Location: include/net/net_namespace.h:437
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c1233)
Location: include/net/net_namespace.h:437
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
```
```
In net/ipv6/addrconf.c (ffffffff819df507)
Location: include/net/net_namespace.h:437
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:add_addr
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
In security/selinux/ss/services.c (ffffffff81460567)
Location: include/net/net_namespace.h:437
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197e023)
Location: include/net/net_namespace.h:437
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
```
```
In net/ipv6/addrconf.c (ffffffff8199c2c7)
Location: include/net/net_namespace.h:437
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:add_addr
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
In security/selinux/ss/services.c (ffffffff8146bbfd)
Location: include/net/net_namespace.h:437
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2bcb3)
Location: include/net/net_namespace.h:437
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
```
```
In net/ipv6/addrconf.c (ffffffff81a49f87)
Location: include/net/net_namespace.h:437
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:add_addr
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
In security/selinux/ss/services.c (ffffffff81483399)
Location: include/net/net_namespace.h:437
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_set_bools
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a37383)
Location: include/net/net_namespace.h:437
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_insert
```
```
In net/ipv6/addrconf.c (ffffffff81a55ec7)
Location: include/net/net_namespace.h:437
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:add_addr
```
</details>
</li>
</ul>

## Differences
