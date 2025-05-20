# Function: <code>vcap_bitarray_zero</code>

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
bool vcap_bitarray_zero(int width, u8 *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (0)
Location: drivers/net/ethernet/microchip/vcap/vcap_api.c:172
Inline: False
Direct callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_decode_keyset
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_decode_actionset
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_find_keystream_keysets
```
**Symbols:**

```
ffffffff81bf4910-ffffffff81bf49a7: vcap_bitarray_zero (STB_LOCAL)
ffffffff8209d830-ffffffff8209d84f: vcap_bitarray_zero.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool vcap_bitarray_zero(int width, u8 *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (0)
Location: drivers/net/ethernet/microchip/vcap/vcap_api.c:174
Inline: False
Direct callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_decode_keyset
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_decode_actionset
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_find_keystream_keysets
```
**Symbols:**

```
ffffffff81c57d90-ffffffff81c57e27: vcap_bitarray_zero (STB_LOCAL)
ffffffff8211ed90-ffffffff8211edaf: vcap_bitarray_zero.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool vcap_bitarray_zero(int width, u8 *value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (0)
Location: drivers/net/ethernet/microchip/vcap/vcap_api.c:174
Inline: False
Direct callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_decode_keyset
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_decode_actionset
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_find_keystream_keysets
```
**Symbols:**

```
ffffffff81d0e530-ffffffff81d0e5c7: vcap_bitarray_zero (STB_LOCAL)
ffffffff82200566-ffffffff82200585: vcap_bitarray_zero.cold (STB_LOCAL)
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
