# Function: <code>vcap_rule_add_key_u128</code>

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
int vcap_rule_add_key_u128(struct vcap_rule *rule, enum vcap_key_field key, struct vcap_u128_key *fieldval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (ffffffff81bf6e70)
Location: drivers/net/ethernet/microchip/vcap/vcap_api.c:2331
Inline: False
```
**Symbols:**

```
ffffffff81bf6e70-ffffffff81bf6ed9: vcap_rule_add_key_u128 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vcap_rule_add_key_u128(struct vcap_rule *rule, enum vcap_key_field key, struct vcap_u128_key *fieldval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (ffffffff81c59750)
Location: drivers/net/ethernet/microchip/vcap/vcap_api.c:2752
Inline: False
Direct callers:
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_ipv6_usage
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_ipv6_usage
```
**Symbols:**

```
ffffffff81c59750-ffffffff81c597b9: vcap_rule_add_key_u128 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vcap_rule_add_key_u128(struct vcap_rule *rule, enum vcap_key_field key, struct vcap_u128_key *fieldval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (ffffffff81d10030)
Location: drivers/net/ethernet/microchip/vcap/vcap_api.c:2766
Inline: False
Direct callers:
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_ipv6_usage
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_ipv6_usage
```
**Symbols:**

```
ffffffff81d10030-ffffffff81d10099: vcap_rule_add_key_u128 (STB_GLOBAL)
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
