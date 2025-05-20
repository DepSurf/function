# Function: <code>_genl_register_family_with_ops_grps</code>

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
In kernel/taskstats.c (ffffffff81f8319b)
Location: include/net/genetlink.h:163
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff81fbc6ff)
Location: include/net/genetlink.h:163
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_init
```
```
In net/ipv4/tcp_metrics.c (ffffffff81fbcef7)
Location: include/net/genetlink.h:163
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81fbeb29)
Location: include/net/genetlink.h:163
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_genl_init
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81fbeb70)
Location: include/net/genetlink.h:163
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_genl_init
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81fbed0e)
Location: include/net/genetlink.h:163
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_genl_init
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
In kernel/taskstats.c (ffffffff81fac738)
Location: include/net/genetlink.h:163
Inline: True
```
```
In net/netlink/genetlink.c (ffffffff81fea563)
Location: include/net/genetlink.h:163
Inline: True
Inline callers:
  - net/netlink/genetlink.c:genl_init
```
```
In net/ipv4/tcp_metrics.c (ffffffff81fead5a)
Location: include/net/genetlink.h:163
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff81feca24)
Location: include/net/genetlink.h:163
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_genl_init
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff81feca6b)
Location: include/net/genetlink.h:163
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_genl_init
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff81fecc0f)
Location: include/net/genetlink.h:163
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_genl_init
```
```
In net/netlabel/netlabel_calipso.c (ffffffff81fecc56)
Location: include/net/genetlink.h:163
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_genl_init
```
</details>
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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
