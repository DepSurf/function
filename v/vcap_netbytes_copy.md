# Function: <code>vcap_netbytes_copy</code>

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
<summary>In <code>6.2</code>: ✅</summary>

```c
void vcap_netbytes_copy(u8 *dst, u8 *src, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (ffffffff81bf4890)
Location: drivers/net/ethernet/microchip/vcap/vcap_api.c:2528
Inline: False
Direct callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_debugfs_show_rule_keyfield
  - drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_debugfs_show_rule_keyfield
```
**Symbols:**

```
ffffffff81bf4890-ffffffff81bf48cd: vcap_netbytes_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void vcap_netbytes_copy(u8 *dst, u8 *src, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (ffffffff81c57d10)
Location: drivers/net/ethernet/microchip/vcap/vcap_api.c:2911
Inline: False
Direct callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_debugfs_show_rule_keyfield
  - drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_debugfs_show_rule_keyfield
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_ipv6_usage
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_ipv6_usage
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_ipv6_usage
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_ipv6_usage
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_ethaddr_usage
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_ethaddr_usage
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_ethaddr_usage
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_ethaddr_usage
```
**Symbols:**

```
ffffffff81c57d10-ffffffff81c57d4d: vcap_netbytes_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void vcap_netbytes_copy(u8 *dst, u8 *src, int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (ffffffff81d0e4b0)
Location: drivers/net/ethernet/microchip/vcap/vcap_api.c:2925
Inline: False
Direct callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_debugfs_show_rule_keyfield
  - drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_debugfs_show_rule_keyfield
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_ipv6_usage
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_ipv6_usage
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_ipv6_usage
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_ipv6_usage
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_ethaddr_usage
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_ethaddr_usage
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_ethaddr_usage
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_ethaddr_usage
```
**Symbols:**

```
ffffffff81d0e4b0-ffffffff81d0e4ed: vcap_netbytes_copy (STB_GLOBAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
