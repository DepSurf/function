# Function: <code>vcap_keyfields</code>

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
const struct vcap_field *vcap_keyfields(struct vcap_control *vctrl, enum vcap_type vt, enum vcap_keyfield_set keyset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (ffffffff81bf4ece)
Location: drivers/net/ethernet/microchip/vcap/vcap_api.c:394
Inline: True
Inline callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_filter_rule_keys
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_rule_add_key
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_lookup_keyfield
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_val_rule
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:_vcap_rule_find_keysets
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_decode_keyset
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_encode_rule_keyset
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_find_keystream_keysets
```
**Symbols:**

```
ffffffff81bf7180-ffffffff81bf71c8: vcap_keyfields (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
const struct vcap_field *vcap_keyfields(struct vcap_control *vctrl, enum vcap_type vt, enum vcap_keyfield_set keyset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (ffffffff81c584ce)
Location: drivers/net/ethernet/microchip/vcap/vcap_api.c:396
Inline: True
Inline callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_filter_rule_keys
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_rule_add_key
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_lookup_keyfield
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_val_rule
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:_vcap_rule_find_keysets
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_decode_keyset
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_encode_rule_keyset
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_find_keystream_keysets
```
**Symbols:**

```
ffffffff81c5b1a0-ffffffff81c5b1e8: vcap_keyfields (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
const struct vcap_field *vcap_keyfields(struct vcap_control *vctrl, enum vcap_type vt, enum vcap_keyfield_set keyset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (ffffffff81d0ec6e)
Location: drivers/net/ethernet/microchip/vcap/vcap_api.c:396
Inline: True
Inline callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_filter_rule_keys
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_rule_add_key
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_lookup_keyfield
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_val_rule
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:_vcap_rule_find_keysets
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_decode_keyset
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_encode_rule_keyset
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_find_keystream_keysets
```
**Symbols:**

```
ffffffff81d11a80-ffffffff81d11ac8: vcap_keyfields (STB_GLOBAL)
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
