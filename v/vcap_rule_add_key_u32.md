# Function: <code>vcap_rule_add_key_u32</code>

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
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int vcap_rule_add_key_u32(struct vcap_rule *rule, enum vcap_key_field key, u32 value, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (ffffffff81bf8cdc)
Location: drivers/net/ethernet/microchip/vcap/vcap_api.c:2297
Inline: True
Inline callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_val_rule
```
**Symbols:**

```
ffffffff81bf6cd0-ffffffff81bf6d3a: vcap_rule_add_key_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int vcap_rule_add_key_u32(struct vcap_rule *rule, enum vcap_key_field key, u32 value, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (ffffffff81c5d9a3)
Location: drivers/net/ethernet/microchip/vcap/vcap_api.c:2718
Inline: True
Inline callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_val_rule
Direct callers:
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_ip_usage
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_arp_usage
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_arp_usage
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_arp_usage
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_vlan_usage
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_vlan_usage
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_cvlan_usage
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_cvlan_usage
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_portnum_usage
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_portnum_usage
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_ipv4_usage
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_ipv4_usage
```
**Symbols:**

```
ffffffff81c595b0-ffffffff81c5961a: vcap_rule_add_key_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int vcap_rule_add_key_u32(struct vcap_rule *rule, enum vcap_key_field key, u32 value, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (ffffffff81d142d3)
Location: drivers/net/ethernet/microchip/vcap/vcap_api.c:2732
Inline: True
Inline callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_val_rule
Direct callers:
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_ip_usage
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_arp_usage
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_arp_usage
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_arp_usage
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_vlan_usage
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_vlan_usage
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_cvlan_usage
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_cvlan_usage
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_portnum_usage
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_portnum_usage
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_ipv4_usage
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_ipv4_usage
```
**Symbols:**

```
ffffffff81d0fe90-ffffffff81d0fefa: vcap_rule_add_key_u32 (STB_GLOBAL)
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
