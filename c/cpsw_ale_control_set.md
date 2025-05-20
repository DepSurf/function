# Function: <code>cpsw_ale_control_set</code>

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
<summary>In <code>armhf</code>: ✅</summary>

```c
int cpsw_ale_control_set(struct cpsw_ale *ale, int port, int control, int value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ethernet/ti/cpsw_ale.c (c0ad9940)
Location: drivers/net/ethernet/ti/cpsw_ale.c:701
Inline: False
Direct callers:
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_open
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_open
  - drivers/net/ethernet/ti/cpsw.c:cpsw_slave_stop
  - drivers/net/ethernet/ti/cpsw.c:cpsw_slave_open
  - drivers/net/ethernet/ti/cpsw.c:_cpsw_adjust_link
  - drivers/net/ethernet/ti/cpsw.c:_cpsw_adjust_link
  - drivers/net/ethernet/ti/cpsw.c:cpsw_set_promiscious
  - drivers/net/ethernet/ti/cpsw.c:cpsw_set_promiscious
  - drivers/net/ethernet/ti/cpsw.c:cpsw_set_promiscious
  - drivers/net/ethernet/ti/cpsw.c:cpsw_set_promiscious
  - drivers/net/ethernet/ti/cpsw.c:cpsw_set_promiscious
  - drivers/net/ethernet/ti/cpsw.c:cpsw_set_promiscious
  - drivers/net/ethernet/ti/cpsw.c:cpsw_set_promiscious
  - drivers/net/ethernet/ti/cpsw.c:cpsw_set_promiscious
  - drivers/net/ethernet/ti/cpsw.c:cpsw_set_promiscious
  - drivers/net/ethernet/ti/cpsw.c:cpsw_set_promiscious
  - drivers/net/ethernet/ti/cpsw_ale.c:cpsw_ale_create
  - drivers/net/ethernet/ti/cpsw_ale.c:cpsw_ale_stop
  - drivers/net/ethernet/ti/cpsw_ale.c:cpsw_ale_stop
  - drivers/net/ethernet/ti/cpsw_ale.c:cpsw_ale_start
  - drivers/net/ethernet/ti/cpsw_ale.c:cpsw_ale_start
  - drivers/net/ethernet/ti/cpsw_ale.c:cpsw_ale_timer
```
**Symbols:**

```
c0ad9940-c0ad9a08: cpsw_ale_control_set (STB_GLOBAL)
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
