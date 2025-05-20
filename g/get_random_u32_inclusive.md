# Function: <code>get_random_u32_inclusive</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/module.c (ffffffff810b194f)
Location: include/linux/random.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/module.c:module_alloc
```
```
In mm/swapfile.c (ffffffff813fcc93)
Location: include/linux/random.h:110
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:set_cluster_next
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/linux/random.h:110
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In net/ipv4/tcp_input.c (ffffffff81eb57d9)
Location: include/linux/random.h:110
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_send_challenge_ack
```
```
In net/xfrm/xfrm_state.c (ffffffff81f3dd47)
Location: include/linux/random.h:110
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
```
```
In net/ipv6/addrconf.c (ffffffff81f6a372)
Location: include/linux/random.h:110
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
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
In arch/x86/kernel/module.c (ffffffff810b498f)
Location: include/linux/random.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/module.c:module_alloc
```
```
In mm/swapfile.c (ffffffff8142ff6f)
Location: include/linux/random.h:110
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:set_cluster_next
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/linux/random.h:110
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In net/ipv4/tcp_input.c (ffffffff81f13c09)
Location: include/linux/random.h:110
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_send_challenge_ack
```
```
In net/xfrm/xfrm_state.c (ffffffff81f9d69d)
Location: include/linux/random.h:110
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
```
```
In net/ipv6/addrconf.c (ffffffff81fca3b2)
Location: include/linux/random.h:110
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
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
In arch/x86/kernel/module.c (ffffffff810bbdef)
Location: include/linux/random.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/module.c:module_alloc
```
```
In mm/swapfile.c (ffffffff81469a10)
Location: include/linux/random.h:110
Inline: True
Inline callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:set_cluster_next
```
```
In crypto/rsa-pkcs1pad.c (0)
Location: include/linux/random.h:110
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_encrypt
```
```
In net/ipv4/tcp_input.c (ffffffff81fd80ea)
Location: include/linux/random.h:110
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_send_challenge_ack
```
```
In net/xfrm/xfrm_state.c (ffffffff8206a9fd)
Location: include/linux/random.h:110
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
```
```
In net/ipv6/addrconf.c (ffffffff82097b52)
Location: include/linux/random.h:110
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:inet6_set_iftoken
  - net/ipv6/addrconf.c:addrconf_dad_completed
  - net/ipv6/addrconf.c:addrconf_rs_timer
  - net/ipv6/addrconf.c:addrconf_rs_timer
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
