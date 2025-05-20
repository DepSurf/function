# Function: <code>vcap_actionfields</code>

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
const struct vcap_field *vcap_actionfields(struct vcap_control *vctrl, enum vcap_type vt, enum vcap_actionfield_set actionset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (ffffffff81bf6463)
Location: drivers/net/ethernet/microchip/vcap/vcap_api.c:564
Inline: True
Inline callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_rule_add_action
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_decode_actionset
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_decode_actionset
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_encode_rule_actionset
```
**Symbols:**

```
ffffffff81bf8090-ffffffff81bf80d8: vcap_actionfields (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
const struct vcap_field *vcap_actionfields(struct vcap_control *vctrl, enum vcap_type vt, enum vcap_actionfield_set actionset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (ffffffff81c590ee)
Location: drivers/net/ethernet/microchip/vcap/vcap_api.c:691
Inline: True
Inline callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_rule_add_action
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_val_rule
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_decode_actionset
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_decode_actionset
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_encode_rule_actionset
```
**Symbols:**

```
ffffffff81c5c170-ffffffff81c5c1b8: vcap_actionfields (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
const struct vcap_field *vcap_actionfields(struct vcap_control *vctrl, enum vcap_type vt, enum vcap_actionfield_set actionset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (ffffffff81d0f94e)
Location: drivers/net/ethernet/microchip/vcap/vcap_api.c:691
Inline: True
Inline callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_rule_add_action
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_val_rule
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_decode_actionset
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_decode_actionset
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_encode_rule_actionset
```
**Symbols:**

```
ffffffff81d12a70-ffffffff81d12ab8: vcap_actionfields (STB_GLOBAL)
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
