# Function: <code>xfrm_dst_path</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81874a76)
Location: include/net/xfrm.h:1000
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
```
```
In net/ipv4/route.c (ffffffff818e6823)
Location: include/net/xfrm.h:1000
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194a5b5)
Location: include/net/xfrm.h:1000
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_confirm_neigh
  - net/xfrm/xfrm_policy.c:xfrm_neigh_lookup
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_device.c (ffffffff81958143)
Location: include/net/xfrm.h:1000
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
```
```
In net/ipv6/ip6_output.c (ffffffff819613ac)
Location: include/net/xfrm.h:1000
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
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
In net/core/sock.c (ffffffff81895288)
Location: include/net/xfrm.h:1018
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
```
```
In net/ipv4/route.c (ffffffff8191367c)
Location: include/net/xfrm.h:1018
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197c575)
Location: include/net/xfrm.h:1018
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_confirm_neigh
  - net/xfrm/xfrm_policy.c:xfrm_neigh_lookup
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_device.c (ffffffff8198ca99)
Location: include/net/xfrm.h:1018
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
```
```
In net/ipv6/ip6_output.c (ffffffff81995c86)
Location: include/net/xfrm.h:1018
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
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
In net/core/sock.c (ffffffff818df825)
Location: include/net/xfrm.h:945
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
```
```
In net/ipv4/route.c (ffffffff81975cc7)
Location: include/net/xfrm.h:945
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e5885)
Location: include/net/xfrm.h:945
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_confirm_neigh
  - net/xfrm/xfrm_policy.c:xfrm_neigh_lookup
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_device.c (ffffffff819f80a9)
Location: include/net/xfrm.h:945
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
```
```
In net/ipv6/ip6_output.c (ffffffff81a019ca)
Location: include/net/xfrm.h:945
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
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
In net/core/sock.c (ffffffff819119f5)
Location: include/net/xfrm.h:945
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
```
```
In net/ipv4/route.c (ffffffff819ac6d7)
Location: include/net/xfrm.h:945
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a1c8b5)
Location: include/net/xfrm.h:945
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_confirm_neigh
  - net/xfrm/xfrm_policy.c:xfrm_neigh_lookup
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_device.c (ffffffff81a2ecf9)
Location: include/net/xfrm.h:945
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
```
```
In net/ipv6/ip6_output.c (ffffffff81a3858b)
Location: include/net/xfrm.h:945
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
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
In net/core/sock.c (ffffffff819e37c8)
Location: include/net/xfrm.h:943
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
```
```
In net/ipv4/route.c (ffffffff81a96bb6)
Location: include/net/xfrm.h:943
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0f6e5)
Location: include/net/xfrm.h:943
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_confirm_neigh
  - net/xfrm/xfrm_policy.c:xfrm_neigh_lookup
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_device.c (ffffffff81b217e9)
Location: include/net/xfrm.h:943
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
```
```
In net/ipv6/ip6_output.c (ffffffff81b2e41f)
Location: include/net/xfrm.h:943
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
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
In net/core/sock.c (ffffffff819e331d)
Location: include/net/xfrm.h:946
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
```
```
In net/ipv4/route.c (ffffffff81aa0c90)
Location: include/net/xfrm.h:946
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1d9d5)
Location: include/net/xfrm.h:946
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_confirm_neigh
  - net/xfrm/xfrm_policy.c:xfrm_neigh_lookup
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_device.c (ffffffff81b301b9)
Location: include/net/xfrm.h:946
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
```
```
In net/ipv6/ip6_output.c (ffffffff81b3ce6f)
Location: include/net/xfrm.h:946
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
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
In net/core/sock.c (ffffffff819c936a)
Location: include/net/xfrm.h:946
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
```
```
In net/ipv4/route.c (ffffffff81a8bbc0)
Location: include/net/xfrm.h:946
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0b225)
Location: include/net/xfrm.h:946
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_confirm_neigh
  - net/xfrm/xfrm_policy.c:xfrm_neigh_lookup
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_device.c (ffffffff81b1def5)
Location: include/net/xfrm.h:946
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
```
```
In net/ipv6/ip6_output.c (ffffffff81b2a2cf)
Location: include/net/xfrm.h:946
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
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
In net/core/sock.c (ffffffff81a7870a)
Location: include/net/xfrm.h:942
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
```
```
In net/ipv4/route.c (ffffffff81b46b50)
Location: include/net/xfrm.h:942
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bce0f5)
Location: include/net/xfrm.h:942
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_confirm_neigh
  - net/xfrm/xfrm_policy.c:xfrm_neigh_lookup
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_device.c (ffffffff81be29e5)
Location: include/net/xfrm.h:942
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
```
```
In net/ipv6/ip6_output.c (ffffffff81befeaa)
Location: include/net/xfrm.h:942
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
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
In net/core/sock.c (ffffffff81bec076)
Location: include/net/xfrm.h:945
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
```
```
In net/ipv4/route.c (ffffffff81cd3c06)
Location: include/net/xfrm.h:945
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d641d5)
Location: include/net/xfrm.h:945
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_confirm_neigh
  - net/xfrm/xfrm_policy.c:xfrm_neigh_lookup
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_device.c (ffffffff81d79b3f)
Location: include/net/xfrm.h:945
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
```
```
In net/ipv6/ip6_output.c (ffffffff81d87f3f)
Location: include/net/xfrm.h:945
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
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
In net/core/sock.c (ffffffff81d98a46)
Location: include/net/xfrm.h:962
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
```
```
In net/ipv4/route.c (ffffffff81e93e36)
Location: include/net/xfrm.h:962
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f2ef65)
Location: include/net/xfrm.h:962
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_confirm_neigh
  - net/xfrm/xfrm_policy.c:xfrm_neigh_lookup
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_device.c (ffffffff81f4693e)
Location: include/net/xfrm.h:962
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
```
```
In net/ipv6/ip6_output.c (ffffffff81f55cdb)
Location: include/net/xfrm.h:962
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
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
In net/core/sock.c (ffffffff81e08232)
Location: include/net/xfrm.h:967
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
```
```
In net/ipv4/route.c (ffffffff81ef25cc)
Location: include/net/xfrm.h:967
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f8f4a5)
Location: include/net/xfrm.h:967
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_confirm_neigh
  - net/xfrm/xfrm_policy.c:xfrm_neigh_lookup
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_device.c (ffffffff81fa627e)
Location: include/net/xfrm.h:967
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
```
```
In net/ipv6/ip6_output.c (ffffffff81fb56b3)
Location: include/net/xfrm.h:967
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
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
In net/core/sock.c (ffffffff81ec4c85)
Location: include/net/xfrm.h:967
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
```
```
In net/ipv4/route.c (ffffffff81fb66e9)
Location: include/net/xfrm.h:967
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/xfrm/xfrm_policy.c (ffffffff8205d205)
Location: include/net/xfrm.h:967
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_confirm_neigh
  - net/xfrm/xfrm_policy.c:xfrm_neigh_lookup
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_device.c (ffffffff82073571)
Location: include/net/xfrm.h:967
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
```
```
In net/ipv6/ip6_output.c (ffffffff82082de0)
Location: include/net/xfrm.h:967
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
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
In net/core/sock.c (ffff800010ba9610)
Location: include/net/xfrm.h:945
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
```
```
In net/ipv4/route.c (ffff800010c5c8a8)
Location: include/net/xfrm.h:945
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/xfrm/xfrm_policy.c (ffff800010cd8afc)
Location: include/net/xfrm.h:945
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_confirm_neigh
  - net/xfrm/xfrm_policy.c:xfrm_neigh_lookup
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_device.c (ffff800010cedb40)
Location: include/net/xfrm.h:945
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
```
```
In net/ipv6/ip6_output.c (ffff800010cf8b04)
Location: include/net/xfrm.h:945
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
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
In net/core/sock.c (c0cca650)
Location: include/net/xfrm.h:945
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
```
```
In net/ipv4/route.c (c0d6bf40)
Location: include/net/xfrm.h:945
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/xfrm/xfrm_policy.c (c0de2754)
Location: include/net/xfrm.h:945
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_confirm_neigh
  - net/xfrm/xfrm_policy.c:xfrm_neigh_lookup
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_device.c (c0df5c0c)
Location: include/net/xfrm.h:945
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
```
```
In net/ipv6/ip6_output.c (c0e001c8)
Location: include/net/xfrm.h:945
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
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
In net/core/sock.c (c000000000c7e6e0)
Location: include/net/xfrm.h:945
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
```
```
In net/ipv4/route.c (c000000000d5eca8)
Location: include/net/xfrm.h:945
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/xfrm/xfrm_policy.c (c000000000df938c)
Location: include/net/xfrm.h:945
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_confirm_neigh
  - net/xfrm/xfrm_policy.c:xfrm_neigh_lookup
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_device.c (c000000000e124d0)
Location: include/net/xfrm.h:945
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
```
```
In net/ipv6/ip6_output.c (c000000000e21cec)
Location: include/net/xfrm.h:945
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
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
In net/core/sock.c (ffffffe00073c99a)
Location: include/net/xfrm.h:945
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
```
```
In net/ipv4/route.c (ffffffe0007c56e0)
Location: include/net/xfrm.h:945
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/xfrm/xfrm_policy.c (ffffffe000829046)
Location: include/net/xfrm.h:945
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_confirm_neigh
  - net/xfrm/xfrm_policy.c:xfrm_neigh_lookup
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_device.c (ffffffe00083b0ee)
Location: include/net/xfrm.h:945
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
```
```
In net/ipv6/ip6_output.c (ffffffe000844826)
Location: include/net/xfrm.h:945
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
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
In net/core/sock.c (ffffffff818b19f5)
Location: include/net/xfrm.h:945
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
```
```
In net/ipv4/route.c (ffffffff8194c547)
Location: include/net/xfrm.h:945
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/xfrm/xfrm_policy.c (ffffffff819bbf45)
Location: include/net/xfrm.h:945
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_confirm_neigh
  - net/xfrm/xfrm_policy.c:xfrm_neigh_lookup
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_device.c (ffffffff819ce389)
Location: include/net/xfrm.h:945
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
```
```
In net/ipv6/ip6_output.c (ffffffff819d7c1b)
Location: include/net/xfrm.h:945
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
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
In net/core/sock.c (ffffffff8186b945)
Location: include/net/xfrm.h:945
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
```
```
In net/ipv4/route.c (ffffffff81906037)
Location: include/net/xfrm.h:945
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/xfrm/xfrm_policy.c (ffffffff81978d35)
Location: include/net/xfrm.h:945
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_confirm_neigh
  - net/xfrm/xfrm_policy.c:xfrm_neigh_lookup
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_device.c (ffffffff8198b179)
Location: include/net/xfrm.h:945
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
```
```
In net/ipv6/ip6_output.c (ffffffff819949db)
Location: include/net/xfrm.h:945
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
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
In net/core/sock.c (ffffffff819029f5)
Location: include/net/xfrm.h:945
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
```
```
In net/ipv4/route.c (ffffffff819b6d17)
Location: include/net/xfrm.h:945
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a269c5)
Location: include/net/xfrm.h:945
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_confirm_neigh
  - net/xfrm/xfrm_policy.c:xfrm_neigh_lookup
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_device.c (ffffffff81a38e09)
Location: include/net/xfrm.h:945
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
```
```
In net/ipv6/ip6_output.c (ffffffff81a4269b)
Location: include/net/xfrm.h:945
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
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
In net/core/sock.c (ffffffff81923995)
Location: include/net/xfrm.h:945
Inline: True
Inline callers:
  - net/core/sock.c:sk_setup_caps
```
```
In net/ipv4/route.c (ffffffff819c059a)
Location: include/net/xfrm.h:945
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a31e75)
Location: include/net/xfrm.h:945
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_confirm_neigh
  - net/xfrm/xfrm_policy.c:xfrm_neigh_lookup
  - net/xfrm/xfrm_policy.c:xfrm_default_advmss
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/xfrm/xfrm_device.c (ffffffff81a44829)
Location: include/net/xfrm.h:945
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
```
```
In net/ipv6/ip6_output.c (ffffffff81a4e32b)
Location: include/net/xfrm.h:945
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_setup_cork
```
</details>
</li>
</ul>

## Differences
