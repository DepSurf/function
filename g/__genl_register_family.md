# Function: <code>__genl_register_family</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int __genl_register_family(struct genl_family *family);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff81750550)
Location: net/netlink/genetlink.c:360
Inline: True
Direct callers:
  - fs/quota/netlink.c:quota_init
  - net/netlink/genetlink.c:genl_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_genl_init
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_genl_init
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_genl_init
```
**Symbols:**

```
ffffffff81750550-ffffffff81750bc8: __genl_register_family (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int __genl_register_family(struct genl_family *family);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/netlink/genetlink.c (ffffffff817bc610)
Location: net/netlink/genetlink.c:360
Inline: True
Direct callers:
  - fs/quota/netlink.c:quota_init
  - net/netlink/genetlink.c:genl_init
  - net/ipv4/tcp_metrics.c:tcp_metrics_init
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_genl_init
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_genl_init
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_genl_init
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_genl_init
```
**Symbols:**

```
ffffffff817bc610-ffffffff817bcd08: __genl_register_family (STB_GLOBAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
</ul>
