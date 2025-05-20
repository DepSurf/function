# Function: <code>xfrm_decode_session</code>

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
In net/ipv4/netfilter.c (ffffffff817ac2ef)
Location: include/net/xfrm.h:1111
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff817b5e82)
Location: include/net/xfrm.h:1111
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
```
```
In net/ipv6/netfilter.c (ffffffff817fdcfb)
Location: include/net/xfrm.h:1111
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
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
In net/ipv4/netfilter.c (ffffffff81819637)
Location: include/net/xfrm.h:1107
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff818231c9)
Location: include/net/xfrm.h:1107
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/ipv6/netfilter.c (ffffffff8186d636)
Location: include/net/xfrm.h:1107
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
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
In net/ipv4/netfilter.c (ffffffff8184af02)
Location: include/net/xfrm.h:1107
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff81854b19)
Location: include/net/xfrm.h:1107
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/ipv6/netfilter.c (ffffffff818a0421)
Location: include/net/xfrm.h:1107
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
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
In net/ipv4/netfilter.c (ffffffff8186e989)
Location: include/net/xfrm.h:1166
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff81878659)
Location: include/net/xfrm.h:1166
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/ipv6/netfilter.c (ffffffff818c6a7e)
Location: include/net/xfrm.h:1166
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
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
In net/ipv4/netfilter.c (ffffffff818ef349)
Location: include/net/xfrm.h:1172
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f8f69)
Location: include/net/xfrm.h:1172
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/ipv6/netfilter.c (ffffffff81949f21)
Location: include/net/xfrm.h:1172
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
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
In net/ipv4/netfilter.c (ffffffff81945ce9)
Location: include/net/xfrm.h:1204
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194fa16)
Location: include/net/xfrm.h:1204
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/ipv6/netfilter.c (ffffffff819a2ed7)
Location: include/net/xfrm.h:1204
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
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
In net/ipv4/netfilter.c (ffffffff81976009)
Location: include/net/xfrm.h:1209
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff81983036)
Location: include/net/xfrm.h:1209
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/ipv6/netfilter.c (ffffffff819d9baa)
Location: include/net/xfrm.h:1209
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
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
In net/ipv4/netfilter.c (ffffffff819dfb69)
Location: include/net/xfrm.h:1134
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff819ecc46)
Location: include/net/xfrm.h:1134
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/ipv6/netfilter.c (ffffffff81a48414)
Location: include/net/xfrm.h:1134
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
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
In net/ipv4/netfilter.c (ffffffff81a16b99)
Location: include/net/xfrm.h:1134
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a23c56)
Location: include/net/xfrm.h:1134
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/ipv6/netfilter.c (ffffffff81a7efc4)
Location: include/net/xfrm.h:1134
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
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
In net/ipv4/netfilter.c (ffffffff81b07be4)
Location: include/net/xfrm.h:1133
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b15c3d)
Location: include/net/xfrm.h:1133
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/ipv6/netfilter.c (ffffffff81b79c0e)
Location: include/net/xfrm.h:1133
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
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
In net/ipv4/netfilter.c (ffffffff81b15fc8)
Location: include/net/xfrm.h:1136
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b240ad)
Location: include/net/xfrm.h:1136
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/ipv6/netfilter.c (ffffffff81b88b5c)
Location: include/net/xfrm.h:1136
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
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
In net/ipv4/netfilter.c (ffffffff81b03e53)
Location: include/net/xfrm.h:1136
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b11cdd)
Location: include/net/xfrm.h:1136
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/ipv6/netfilter.c (ffffffff81b77857)
Location: include/net/xfrm.h:1136
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
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
In net/ipv4/netfilter.c (ffffffff81bc612c)
Location: include/net/xfrm.h:1153
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bd582d)
Location: include/net/xfrm.h:1153
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/ipv6/netfilter.c (ffffffff81c42351)
Location: include/net/xfrm.h:1153
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
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
In net/ipv4/netfilter.c (ffffffff81d5b429)
Location: include/net/xfrm.h:1157
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d6c06e)
Location: include/net/xfrm.h:1157
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/ipv6/netfilter.c (ffffffff81de0e0a)
Location: include/net/xfrm.h:1157
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
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
In net/ipv4/netfilter.c (ffffffff81f258b9)
Location: include/net/xfrm.h:1207
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f373ce)
Location: include/net/xfrm.h:1207
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/ipv6/netfilter.c (ffffffff81fb324a)
Location: include/net/xfrm.h:1207
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
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
In net/ipv4/netfilter.c (ffffffff81f85449)
Location: include/net/xfrm.h:1213
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f96d8e)
Location: include/net/xfrm.h:1213
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/ipv6/netfilter.c (ffffffff8201393a)
Location: include/net/xfrm.h:1213
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
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
In net/ipv4/netfilter.c (ffffffff8204bb1f)
Location: include/net/xfrm.h:1213
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff82064144)
Location: include/net/xfrm.h:1213
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/ipv6/netfilter.c (ffffffff820e2a97)
Location: include/net/xfrm.h:1213
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
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
In net/ipv4/netfilter.c (ffff800010cd27d0)
Location: include/net/xfrm.h:1134
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffff800010ce0eb8)
Location: include/net/xfrm.h:1134
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/ipv6/netfilter.c (ffff800010d4a8c8)
Location: include/net/xfrm.h:1134
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
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
In net/ipv4/netfilter.c (c0ddc6ec)
Location: include/net/xfrm.h:1134
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (c0dea1e8)
Location: include/net/xfrm.h:1134
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/ipv6/netfilter.c (c0e4b894)
Location: include/net/xfrm.h:1134
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
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
In net/ipv4/netfilter.c (c000000000df0e50)
Location: include/net/xfrm.h:1134
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (c000000000e03338)
Location: include/net/xfrm.h:1134
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/ipv6/netfilter.c (c000000000e80210)
Location: include/net/xfrm.h:1134
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
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
In net/ipv4/netfilter.c (ffffffe000823afe)
Location: include/net/xfrm.h:1134
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffe00082fab0)
Location: include/net/xfrm.h:1134
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/ipv6/netfilter.c (ffffffe0008837c4)
Location: include/net/xfrm.h:1134
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
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
In net/ipv4/netfilter.c (ffffffff819b6229)
Location: include/net/xfrm.h:1134
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff819c32e6)
Location: include/net/xfrm.h:1134
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/ipv6/netfilter.c (ffffffff81a1e654)
Location: include/net/xfrm.h:1134
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
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
In net/ipv4/netfilter.c (ffffffff81973019)
Location: include/net/xfrm.h:1134
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff819800d6)
Location: include/net/xfrm.h:1134
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/ipv6/netfilter.c (ffffffff819db414)
Location: include/net/xfrm.h:1134
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
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
In net/ipv4/netfilter.c (ffffffff81a20ac9)
Location: include/net/xfrm.h:1134
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a2dd66)
Location: include/net/xfrm.h:1134
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/ipv6/netfilter.c (ffffffff81a890d4)
Location: include/net/xfrm.h:1134
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
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
In net/ipv4/netfilter.c (ffffffff81a2bffd)
Location: include/net/xfrm.h:1134
Inline: True
Inline callers:
  - net/ipv4/netfilter.c:ip_route_me_harder
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a39546)
Location: include/net/xfrm.h:1134
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:__xfrm_route_forward
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
  - net/xfrm/xfrm_policy.c:xfrm_policy_queue_process
```
```
In net/ipv6/netfilter.c (ffffffff81a95d34)
Location: include/net/xfrm.h:1134
Inline: True
Inline callers:
  - net/ipv6/netfilter.c:ip6_route_me_harder
```
</details>
</li>
</ul>

## Differences
