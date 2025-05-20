# Function: <code>vcap_copy_from_client_actionfield</code>

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
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void vcap_copy_from_client_actionfield(struct vcap_rule *rule, struct vcap_client_actionfield *field, struct vcap_client_actionfield_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (0)
Location: drivers/net/ethernet/microchip/vcap/vcap_api.c:2370
Inline: False
Direct callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_rule_mod_action_u32
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_rule_add_action
```
**Symbols:**

```
ffffffff81bf6190-ffffffff81bf63c6: vcap_copy_from_client_actionfield (STB_LOCAL)
ffffffff8209da38-ffffffff8209da4d: vcap_copy_from_client_actionfield.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void vcap_copy_from_client_actionfield(struct vcap_rule *rule, struct vcap_client_actionfield *dst, const struct vcap_client_actionfield *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (0)
Location: drivers/net/ethernet/microchip/vcap/vcap_api.c:587
Inline: False
Direct callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_encode_rule_actionset
```
**Symbols:**

```
ffffffff81c5a5d0-ffffffff81c5a814: vcap_copy_from_client_actionfield (STB_LOCAL)
ffffffff8211eed1-ffffffff8211eee6: vcap_copy_from_client_actionfield.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void vcap_copy_from_client_actionfield(struct vcap_rule *rule, struct vcap_client_actionfield *dst, const struct vcap_client_actionfield *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (0)
Location: drivers/net/ethernet/microchip/vcap/vcap_api.c:587
Inline: False
Direct callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_encode_rule_actionset
```
**Symbols:**

```
ffffffff81d10eb0-ffffffff81d110f4: vcap_copy_from_client_actionfield (STB_LOCAL)
ffffffff822006a7-ffffffff822006bc: vcap_copy_from_client_actionfield.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vcap_client_actionfield *dst</code>
</li>
<li>
<b>Param added. </b>
<code>const struct vcap_client_actionfield *src</code>
</li>
<li>
<b>Param removed. </b>
<code>struct vcap_client_actionfield *field</code>
</li>
<li>
<b>Param removed. </b>
<code>struct vcap_client_actionfield_data *data</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
