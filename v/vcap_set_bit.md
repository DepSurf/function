# Function: <code>vcap_set_bit</code>

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
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void vcap_set_bit(u32 *stream, struct vcap_stream_iter *itr, bool value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (ffffffff81bf5ba8)
Location: drivers/net/ethernet/microchip/vcap/vcap_api.c:95
Inline: True
Inline callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_encode_typegroups
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_encode_field
Direct callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_encode_typegroups
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_encode_field
```
**Symbols:**

```
ffffffff81bf49c0-ffffffff81bf4a22: vcap_set_bit (STB_LOCAL)
ffffffff8209d84f-ffffffff8209d86d: vcap_set_bit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void vcap_set_bit(u32 *stream, struct vcap_stream_iter *itr, bool value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (ffffffff81c5af9f)
Location: drivers/net/ethernet/microchip/vcap/vcap_api.c:97
Inline: True
Inline callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_encode_typegroups
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_encode_field
Direct callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_encode_typegroups
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_encode_field
```
**Symbols:**

```
ffffffff81c57e40-ffffffff81c57ea2: vcap_set_bit (STB_LOCAL)
ffffffff8211edaf-ffffffff8211edcd: vcap_set_bit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void vcap_set_bit(u32 *stream, struct vcap_stream_iter *itr, bool value);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (ffffffff81d1187f)
Location: drivers/net/ethernet/microchip/vcap/vcap_api.c:97
Inline: True
Inline callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_encode_typegroups
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_encode_field
Direct callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_encode_typegroups
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_encode_field
```
**Symbols:**

```
ffffffff81d0e5e0-ffffffff81d0e642: vcap_set_bit (STB_LOCAL)
ffffffff82200585-ffffffff822005a3: vcap_set_bit.cold (STB_LOCAL)
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
