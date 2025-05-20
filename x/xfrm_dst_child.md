# Function: <code>xfrm_dst_child</code>

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
In security/selinux/xfrm.c (ffffffff814176e5)
Location: include/net/xfrm.h:1012
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194a5de)
Location: include/net/xfrm.h:1012
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_confirm_neigh
  - net/xfrm/xfrm_policy.c:xfrm_neigh_lookup
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
```
In net/xfrm/xfrm_output.c (ffffffff81956691)
Location: include/net/xfrm.h:1012
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/xfrm6_policy.c (ffffffff819a12a2)
Location: include/net/xfrm.h:1012
Inline: True
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
In security/selinux/xfrm.c (ffffffff81433c15)
Location: include/net/xfrm.h:1030
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197c59e)
Location: include/net/xfrm.h:1030
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_confirm_neigh
  - net/xfrm/xfrm_policy.c:xfrm_neigh_lookup
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_output.c (ffffffff8198b187)
Location: include/net/xfrm.h:1030
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/ipv6/xfrm6_policy.c (ffffffff819d7d82)
Location: include/net/xfrm.h:1030
Inline: True
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
In security/selinux/xfrm.c (ffffffff814616a7)
Location: include/net/xfrm.h:957
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
```
```
In net/xfrm/xfrm_policy.c (ffffffff819e58ae)
Location: include/net/xfrm.h:957
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_confirm_neigh
  - net/xfrm/xfrm_policy.c:xfrm_neigh_lookup
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_output.c (ffffffff819f66b8)
Location: include/net/xfrm.h:957
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a46db3)
Location: include/net/xfrm.h:957
Inline: True
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
In security/selinux/xfrm.c (ffffffff8147b457)
Location: include/net/xfrm.h:957
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a1c8de)
Location: include/net/xfrm.h:957
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_confirm_neigh
  - net/xfrm/xfrm_policy.c:xfrm_neigh_lookup
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_output.c (ffffffff81a2d338)
Location: include/net/xfrm.h:957
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a7d963)
Location: include/net/xfrm.h:957
Inline: True
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
In security/selinux/xfrm.c (ffffffff814d0a40)
Location: include/net/xfrm.h:955
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0f70b)
Location: include/net/xfrm.h:955
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_confirm_neigh
  - net/xfrm/xfrm_policy.c:xfrm_neigh_lookup
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_init_pmtu
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1eea0)
Location: include/net/xfrm.h:955
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_encap_add
  - net/xfrm/xfrm_output.c:xfrm4_tunnel_encap_add
  - net/xfrm/xfrm_output.c:skb_dst_pop
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81b7840b)
Location: include/net/xfrm.h:955
Inline: True
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
In security/selinux/xfrm.c (ffffffff814edf50)
Location: include/net/xfrm.h:958
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b1d9fb)
Location: include/net/xfrm.h:958
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_confirm_neigh
  - net/xfrm/xfrm_policy.c:xfrm_neigh_lookup
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_init_pmtu
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2d750)
Location: include/net/xfrm.h:958
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_encap_add
  - net/xfrm/xfrm_output.c:xfrm4_tunnel_encap_add
  - net/xfrm/xfrm_output.c:skb_dst_pop
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81b87370)
Location: include/net/xfrm.h:958
Inline: True
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
In security/selinux/xfrm.c (ffffffff814f4cc0)
Location: include/net/xfrm.h:958
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
```
```
In net/xfrm/xfrm_policy.c (ffffffff81b0b24b)
Location: include/net/xfrm.h:958
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_confirm_neigh
  - net/xfrm/xfrm_policy.c:xfrm_neigh_lookup
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_init_pmtu
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1c514)
Location: include/net/xfrm.h:958
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81b76042)
Location: include/net/xfrm.h:958
Inline: True
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
In security/selinux/xfrm.c (ffffffff8154f6c0)
Location: include/net/xfrm.h:954
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
```
```
In net/xfrm/xfrm_policy.c (ffffffff81bce11b)
Location: include/net/xfrm.h:954
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_confirm_neigh
  - net/xfrm/xfrm_policy.c:xfrm_neigh_lookup
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_init_pmtu
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_output.c (ffffffff81be0e11)
Location: include/net/xfrm.h:954
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81c40ab2)
Location: include/net/xfrm.h:954
Inline: True
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
In security/selinux/xfrm.c (ffffffff815e89ec)
Location: include/net/xfrm.h:957
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
```
```
In net/xfrm/xfrm_policy.c (ffffffff81d641fb)
Location: include/net/xfrm.h:957
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_confirm_neigh
  - net/xfrm/xfrm_policy.c:xfrm_neigh_lookup
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_init_pmtu
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_output.c (ffffffff81d77cfc)
Location: include/net/xfrm.h:957
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81ddf1d3)
Location: include/net/xfrm.h:957
Inline: True
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
In security/selinux/xfrm.c (ffffffff8169822c)
Location: include/net/xfrm.h:974
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f2ef8b)
Location: include/net/xfrm.h:974
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_confirm_neigh
  - net/xfrm/xfrm_policy.c:xfrm_neigh_lookup
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_output.c (ffffffff81f44493)
Location: include/net/xfrm.h:974
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81fb1413)
Location: include/net/xfrm.h:974
Inline: True
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
In security/selinux/xfrm.c (ffffffff816d06e8)
Location: include/net/xfrm.h:979
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
```
```
In net/xfrm/xfrm_policy.c (ffffffff81f8f4cb)
Location: include/net/xfrm.h:979
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_confirm_neigh
  - net/xfrm/xfrm_policy.c:xfrm_neigh_lookup
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa3c7b)
Location: include/net/xfrm.h:979
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/xfrm6_policy.c (ffffffff82011ac3)
Location: include/net/xfrm.h:979
Inline: True
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
In security/selinux/xfrm.c (ffffffff8170cd08)
Location: include/net/xfrm.h:979
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
```
```
In net/xfrm/xfrm_policy.c (ffffffff8205d22b)
Location: include/net/xfrm.h:979
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_confirm_neigh
  - net/xfrm/xfrm_policy.c:xfrm_neigh_lookup
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_bundle_ok
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_output.c (ffffffff82070fa8)
Location: include/net/xfrm.h:979
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/ipv6/xfrm6_policy.c (ffffffff820e0a5b)
Location: include/net/xfrm.h:979
Inline: True
Inline callers:
  - net/ipv6/xfrm6_policy.c:xfrm6_dst_ifdown
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
In security/selinux/xfrm.c (ffff80001056bd88)
Location: include/net/xfrm.h:957
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
```
```
In net/xfrm/xfrm_policy.c (ffff800010cd8b1c)
Location: include/net/xfrm.h:957
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_confirm_neigh
  - net/xfrm/xfrm_policy.c:xfrm_neigh_lookup
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_output.c (ffff800010cec184)
Location: include/net/xfrm.h:957
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/xfrm6_policy.c (ffff800010d48b3c)
Location: include/net/xfrm.h:957
Inline: True
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
In security/selinux/xfrm.c (c071f6b0)
Location: include/net/xfrm.h:957
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
```
```
In net/xfrm/xfrm_policy.c (c0de2768)
Location: include/net/xfrm.h:957
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_confirm_neigh
  - net/xfrm/xfrm_policy.c:xfrm_neigh_lookup
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_output.c (c0df408c)
Location: include/net/xfrm.h:957
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/xfrm6_policy.c (c0e4a16c)
Location: include/net/xfrm.h:957
Inline: True
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
In security/selinux/xfrm.c (c0000000006cfd64)
Location: include/net/xfrm.h:957
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
```
```
In net/xfrm/xfrm_policy.c (c000000000df93c0)
Location: include/net/xfrm.h:957
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_confirm_neigh
  - net/xfrm/xfrm_policy.c:xfrm_neigh_lookup
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_output.c (c000000000e10290)
Location: include/net/xfrm.h:957
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/xfrm6_policy.c (c000000000e7dfd4)
Location: include/net/xfrm.h:957
Inline: True
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
In security/selinux/xfrm.c (ffffffe0003c09e0)
Location: include/net/xfrm.h:957
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
```
```
In net/xfrm/xfrm_policy.c (ffffffe000829058)
Location: include/net/xfrm.h:957
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_confirm_neigh
  - net/xfrm/xfrm_policy.c:xfrm_neigh_lookup
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_output.c (ffffffe0008399b2)
Location: include/net/xfrm.h:957
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_one
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/xfrm6_policy.c (ffffffe00088221a)
Location: include/net/xfrm.h:957
Inline: True
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
In security/selinux/xfrm.c (ffffffff81473a37)
Location: include/net/xfrm.h:957
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
```
```
In net/xfrm/xfrm_policy.c (ffffffff819bbf6e)
Location: include/net/xfrm.h:957
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_confirm_neigh
  - net/xfrm/xfrm_policy.c:xfrm_neigh_lookup
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_output.c (ffffffff819cc9c8)
Location: include/net/xfrm.h:957
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a1cff3)
Location: include/net/xfrm.h:957
Inline: True
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
In security/selinux/xfrm.c (ffffffff81464457)
Location: include/net/xfrm.h:957
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
```
```
In net/xfrm/xfrm_policy.c (ffffffff81978d5e)
Location: include/net/xfrm.h:957
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_confirm_neigh
  - net/xfrm/xfrm_policy.c:xfrm_neigh_lookup
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_output.c (ffffffff819897b8)
Location: include/net/xfrm.h:957
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/xfrm6_policy.c (ffffffff819d9db3)
Location: include/net/xfrm.h:957
Inline: True
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
In security/selinux/xfrm.c (ffffffff8146fad7)
Location: include/net/xfrm.h:957
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a269ee)
Location: include/net/xfrm.h:957
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_confirm_neigh
  - net/xfrm/xfrm_policy.c:xfrm_neigh_lookup
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_output.c (ffffffff81a37448)
Location: include/net/xfrm.h:957
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a87a73)
Location: include/net/xfrm.h:957
Inline: True
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
In security/selinux/xfrm.c (ffffffff81487347)
Location: include/net/xfrm.h:957
Inline: True
Inline callers:
  - security/selinux/xfrm.c:selinux_xfrm_postroute_last
```
```
In net/xfrm/xfrm_policy.c (ffffffff81a31e9e)
Location: include/net/xfrm.h:957
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_confirm_neigh
  - net/xfrm/xfrm_policy.c:xfrm_neigh_lookup
  - net/xfrm/xfrm_policy.c:xfrm_dst_ifdown
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_output.c (ffffffff81a42dd8)
Location: include/net/xfrm.h:957
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
```
In net/ipv6/xfrm6_policy.c (ffffffff81a9465d)
Location: include/net/xfrm.h:957
Inline: True
```
</details>
</li>
</ul>

## Differences
