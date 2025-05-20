# Function: <code>vcap_iter_init</code>

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
void vcap_iter_init(struct vcap_stream_iter *itr, int sw_width, const struct vcap_typegroup *tg, u32 offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (ffffffff81bf7cfd)
Location: drivers/net/ethernet/microchip/vcap/vcap_api.c:80
Inline: True
Inline callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_decode_keyset
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_decode_keyset
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_decode_actionset
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_encode_rule_actionset
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_encode_rule_keyset
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_encode_rule_keyset
Direct callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_find_keystream_keysets
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_find_keystream_keysets
```
**Symbols:**

```
ffffffff81bf7060-ffffffff81bf70de: vcap_iter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void vcap_iter_init(struct vcap_stream_iter *itr, int sw_width, const struct vcap_typegroup *tg, u32 offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (ffffffff81c5bde1)
Location: drivers/net/ethernet/microchip/vcap/vcap_api.c:82
Inline: True
Inline callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_decode_keyset
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_decode_keyset
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_decode_actionset
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_encode_rule_actionset
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_encode_rule_keyset
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_encode_rule_keyset
Direct callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_find_keystream_keysets
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_find_keystream_keysets
```
**Symbols:**

```
ffffffff81c5b080-ffffffff81c5b0fe: vcap_iter_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void vcap_iter_init(struct vcap_stream_iter *itr, int sw_width, const struct vcap_typegroup *tg, u32 offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (ffffffff81d126b4)
Location: drivers/net/ethernet/microchip/vcap/vcap_api.c:82
Inline: True
Inline callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_decode_keyset
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_decode_keyset
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_decode_actionset
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_encode_rule_actionset
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_encode_rule_keyset
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_encode_rule_keyset
Direct callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_find_keystream_keysets
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_find_keystream_keysets
```
**Symbols:**

```
ffffffff81d11960-ffffffff81d119de: vcap_iter_init (STB_GLOBAL)
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
