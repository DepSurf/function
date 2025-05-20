# Function: <code>vcap_rule_add_key_bit</code>

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
int vcap_rule_add_key_bit(struct vcap_rule *rule, enum vcap_key_field key, enum vcap_bit val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (ffffffff81bf8bf2)
Location: drivers/net/ethernet/microchip/vcap/vcap_api.c:2286
Inline: True
Inline callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_val_rule
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_val_rule
```
**Symbols:**

```
ffffffff81bf6c20-ffffffff81bf6cbe: vcap_rule_add_key_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int vcap_rule_add_key_bit(struct vcap_rule *rule, enum vcap_key_field key, enum vcap_bit val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (ffffffff81c5d865)
Location: drivers/net/ethernet/microchip/vcap/vcap_api.c:2707
Inline: True
Inline callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_val_rule
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_val_rule
Direct callers:
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_tcp_usage
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_tcp_usage
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_tcp_usage
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_tcp_usage
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_tcp_usage
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_tcp_usage
```
**Symbols:**

```
ffffffff81c59500-ffffffff81c59593: vcap_rule_add_key_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int vcap_rule_add_key_bit(struct vcap_rule *rule, enum vcap_key_field key, enum vcap_bit val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (ffffffff81d14195)
Location: drivers/net/ethernet/microchip/vcap/vcap_api.c:2721
Inline: True
Inline callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_val_rule
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_val_rule
Direct callers:
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_tcp_usage
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_tcp_usage
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_tcp_usage
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_tcp_usage
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_tcp_usage
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_tcp_usage
```
**Symbols:**

```
ffffffff81d0fde0-ffffffff81d0fe73: vcap_rule_add_key_bit (STB_GLOBAL)
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
