# Function: <code>seg6_pernet</code>

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
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6.c (0)
Location: include/net/seg6.h:50
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/net/seg6.h:50
Inline: True
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/net/seg6.h:50
Inline: True
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
In net/ipv6/seg6.c (0)
Location: include/net/seg6.h:50
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/net/seg6.h:50
Inline: True
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/net/seg6.h:50
Inline: True
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
In net/ipv6/seg6.c (0)
Location: include/net/seg6.h:50
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/net/seg6.h:50
Inline: True
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/net/seg6.h:50
Inline: True
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
In net/ipv6/seg6.c (0)
Location: include/net/seg6.h:50
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/net/seg6.h:50
Inline: True
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/net/seg6.h:50
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
In net/ipv6/seg6.c (0)
Location: include/net/seg6.h:49
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/net/seg6.h:49
Inline: True
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/net/seg6.h:49
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
In net/ipv6/seg6.c (0)
Location: include/net/seg6.h:44
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/net/seg6.h:44
Inline: True
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/net/seg6.h:44
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
In net/ipv6/seg6.c (0)
Location: include/net/seg6.h:44
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/net/seg6.h:44
Inline: True
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/net/seg6.h:44
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
In net/ipv6/seg6.c (ffffffff81b71ec5)
Location: include/net/seg6.h:44
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_net_exit
  - net/ipv6/seg6.c:seg6_genl_dumphmac_start
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7e5d3)
Location: include/net/seg6.h:44
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b80a85)
Location: include/net/seg6.h:44
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
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
In net/ipv6/seg6.c (ffffffff81b80c25)
Location: include/net/seg6.h:44
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_net_exit
  - net/ipv6/seg6.c:seg6_genl_dumphmac_start
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b8d5f9)
Location: include/net/seg6.h:44
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b902f5)
Location: include/net/seg6.h:44
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
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
In net/ipv6/seg6.c (ffffffff81b6f845)
Location: include/net/seg6.h:44
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_net_exit
  - net/ipv6/seg6.c:seg6_genl_dumphmac_start
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7c4a9)
Location: include/net/seg6.h:44
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b7f535)
Location: include/net/seg6.h:44
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
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
In net/ipv6/seg6.c (ffffffff81c378f5)
Location: include/net/seg6.h:44
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_net_exit
  - net/ipv6/seg6.c:seg6_genl_dumphmac_start
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81c473a9)
Location: include/net/seg6.h:44
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_hmac.c (ffffffff81c4ade5)
Location: include/net/seg6.h:44
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
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
In net/ipv6/seg6.c (ffffffff81dd5485)
Location: include/net/seg6.h:44
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_net_exit
  - net/ipv6/seg6.c:seg6_genl_dumphmac_start
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81de6716)
Location: include/net/seg6.h:44
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_hmac.c (ffffffff81dea645)
Location: include/net/seg6.h:44
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
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
In net/ipv6/seg6.c (ffffffff81fa6bc5)
Location: include/net/seg6.h:44
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_net_exit
  - net/ipv6/seg6.c:seg6_genl_dumphmac_start
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81fb86f5)
Location: include/net/seg6.h:44
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:set_tun_src
```
```
In net/ipv6/seg6_hmac.c (ffffffff81fbde75)
Location: include/net/seg6.h:44
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
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
In net/ipv6/seg6.c (ffffffff82007435)
Location: include/net/seg6.h:44
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_net_exit
  - net/ipv6/seg6.c:seg6_genl_dumphmac_start
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff82018e65)
Location: include/net/seg6.h:44
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:set_tun_src
```
```
In net/ipv6/seg6_hmac.c (ffffffff8201ed05)
Location: include/net/seg6.h:44
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
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
In net/ipv6/seg6.c (ffffffff820d6425)
Location: include/net/seg6.h:44
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_net_exit
  - net/ipv6/seg6.c:seg6_genl_dumphmac_start
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff820e7e35)
Location: include/net/seg6.h:44
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:set_tun_src
```
```
In net/ipv6/seg6_hmac.c (ffffffff820ede35)
Location: include/net/seg6.h:44
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
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
In net/ipv6/seg6.c (0)
Location: include/net/seg6.h:44
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/net/seg6.h:44
Inline: True
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/net/seg6.h:44
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
In net/ipv6/seg6.c (c0e43be0)
Location: include/net/seg6.h:44
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_net_exit
  - net/ipv6/seg6.c:seg6_genl_dumphmac_start
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/ipv6/seg6_iptunnel.c (c0e502c8)
Location: include/net/seg6.h:44
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_hmac.c (c0e52748)
Location: include/net/seg6.h:44
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_init
  - net/ipv6/seg6_hmac.c:seg6_push_hmac
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_validate_skb
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
In net/ipv6/seg6.c (c000000000e75b10)
Location: include/net/seg6.h:44
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_net_exit
  - net/ipv6/seg6.c:seg6_genl_dumphmac_start
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/ipv6/seg6_iptunnel.c (c000000000e86768)
Location: include/net/seg6.h:44
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_hmac.c (c000000000e89f8c)
Location: include/net/seg6.h:44
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
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
In net/ipv6/seg6.c (ffffffe00087c914)
Location: include/net/seg6.h:44
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_net_exit
  - net/ipv6/seg6.c:seg6_genl_dumphmac_start
  - net/ipv6/seg6.c:seg6_genl_get_tunsrc
  - net/ipv6/seg6.c:seg6_genl_set_tunsrc
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/ipv6/seg6_iptunnel.c (ffffffe000887aec)
Location: include/net/seg6.h:44
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/ipv6/seg6_hmac.c (ffffffe000889d8c)
Location: include/net/seg6.h:44
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_exit
  - net/ipv6/seg6_hmac.c:seg6_hmac_net_init
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_del
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_add
  - net/ipv6/seg6_hmac.c:seg6_hmac_info_lookup
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
In net/ipv6/seg6.c (0)
Location: include/net/seg6.h:44
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/net/seg6.h:44
Inline: True
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/net/seg6.h:44
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
In net/ipv6/seg6.c (0)
Location: include/net/seg6.h:44
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/net/seg6.h:44
Inline: True
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/net/seg6.h:44
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
In net/ipv6/seg6.c (0)
Location: include/net/seg6.h:44
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/net/seg6.h:44
Inline: True
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/net/seg6.h:44
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
In net/ipv6/seg6.c (0)
Location: include/net/seg6.h:44
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/net/seg6.h:44
Inline: True
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/net/seg6.h:44
Inline: True
```
</details>
</li>
</ul>

## Differences
