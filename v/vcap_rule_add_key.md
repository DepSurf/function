# Function: <code>vcap_rule_add_key</code>

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
int vcap_rule_add_key(struct vcap_rule *rule, enum vcap_key_field key, enum vcap_field_type ftype, struct vcap_client_keyfield_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (ffffffff81bf6ac0)
Location: drivers/net/ethernet/microchip/vcap/vcap_api.c:2235
Inline: False
Direct callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_rule_mod_key_u32
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_rule_add_key_u128
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_rule_add_key_u72
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_rule_add_key_u48
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_val_rule
```
**Symbols:**

```
ffffffff81bf6ac0-ffffffff81bf6c07: vcap_rule_add_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vcap_rule_add_key(struct vcap_rule *rule, enum vcap_key_field key, enum vcap_field_type ftype, struct vcap_client_keyfield_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (ffffffff81c593a0)
Location: drivers/net/ethernet/microchip/vcap/vcap_api.c:2656
Inline: False
Direct callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_rule_add_key_u128
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_rule_add_key_u72
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_rule_add_key_u48
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_val_rule
```
**Symbols:**

```
ffffffff81c593a0-ffffffff81c594ee: vcap_rule_add_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vcap_rule_add_key(struct vcap_rule *rule, enum vcap_key_field key, enum vcap_field_type ftype, struct vcap_client_keyfield_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (ffffffff81d0fc40)
Location: drivers/net/ethernet/microchip/vcap/vcap_api.c:2670
Inline: False
Direct callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_rule_add_key_u128
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_rule_add_key_u72
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_rule_add_key_u48
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_val_rule
```
**Symbols:**

```
ffffffff81d0fc40-ffffffff81d0fdc5: vcap_rule_add_key (STB_LOCAL)
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
