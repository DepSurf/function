# Function: <code>vcap_copy_to_client_actionfield</code>

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
void vcap_copy_to_client_actionfield(struct vcap_rule_internal *ri, struct vcap_client_actionfield *field, u8 *value, u16 width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (0)
Location: drivers/net/ethernet/microchip/vcap/vcap_api.c:888
Inline: False
Direct callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_decode_actionset
```
**Symbols:**

```
ffffffff81bf5950-ffffffff81bf5a91: vcap_copy_to_client_actionfield (STB_LOCAL)
ffffffff8209d907-ffffffff8209d927: vcap_copy_to_client_actionfield.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void vcap_copy_to_client_actionfield(struct vcap_rule_internal *ri, struct vcap_client_actionfield *field, u8 *value, u16 width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (0)
Location: drivers/net/ethernet/microchip/vcap/vcap_api.c:1084
Inline: False
Direct callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_decode_actionset
```
**Symbols:**

```
ffffffff81c59fe0-ffffffff81c5a137: vcap_copy_to_client_actionfield (STB_LOCAL)
ffffffff8211ee8b-ffffffff8211eeaa: vcap_copy_to_client_actionfield.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void vcap_copy_to_client_actionfield(struct vcap_rule_internal *ri, struct vcap_client_actionfield *field, u8 *value, u16 width);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (0)
Location: drivers/net/ethernet/microchip/vcap/vcap_api.c:1098
Inline: False
Direct callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_decode_actionset
```
**Symbols:**

```
ffffffff81d108c0-ffffffff81d10a17: vcap_copy_to_client_actionfield (STB_LOCAL)
ffffffff82200661-ffffffff82200680: vcap_copy_to_client_actionfield.cold (STB_LOCAL)
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
