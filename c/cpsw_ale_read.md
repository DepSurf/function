# Function: <code>cpsw_ale_read</code>

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
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int cpsw_ale_read(struct cpsw_ale *ale, int idx, u32 *ale_entry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/ethernet/ti/cpsw_ale.c (c0ad8bf4)
Location: drivers/net/ethernet/ti/cpsw_ale.c:140
Inline: True
Direct callers:
  - drivers/net/ethernet/ti/cpsw_ale.c:cpsw_ale_dump
  - drivers/net/ethernet/ti/cpsw_ale.c:cpsw_ale_set_allmulti
  - drivers/net/ethernet/ti/cpsw_ale.c:cpsw_ale_del_vlan
  - drivers/net/ethernet/ti/cpsw_ale.c:cpsw_ale_add_vlan
  - drivers/net/ethernet/ti/cpsw_ale.c:cpsw_ale_del_mcast
  - drivers/net/ethernet/ti/cpsw_ale.c:cpsw_ale_add_mcast
  - drivers/net/ethernet/ti/cpsw_ale.c:cpsw_ale_add_mcast
  - drivers/net/ethernet/ti/cpsw_ale.c:cpsw_ale_flush_multicast
  - drivers/net/ethernet/ti/cpsw_ale.c:cpsw_ale_find_ageable
  - drivers/net/ethernet/ti/cpsw_ale.c:cpsw_ale_match_free
  - drivers/net/ethernet/ti/cpsw_ale.c:cpsw_ale_match_vlan
  - drivers/net/ethernet/ti/cpsw_ale.c:cpsw_ale_match_addr
```
**Symbols:**

```
c0ad8bf4-c0ad8c6c: cpsw_ale_read (STB_LOCAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
