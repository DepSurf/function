# Function: <code>vcap_keyfield_count</code>

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
int vcap_keyfield_count(struct vcap_control *vctrl, enum vcap_type vt, enum vcap_keyfield_set keyset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (ffffffff81bf5260)
Location: drivers/net/ethernet/microchip/vcap/vcap_api.c:435
Inline: True
Inline callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:_vcap_rule_find_keysets
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_decode_keyset
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_encode_rule_keyset
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_find_keystream_keysets
```
**Symbols:**

```
ffffffff81bf8040-ffffffff81bf8079: vcap_keyfield_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int vcap_keyfield_count(struct vcap_control *vctrl, enum vcap_type vt, enum vcap_keyfield_set keyset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (ffffffff81c58c60)
Location: drivers/net/ethernet/microchip/vcap/vcap_api.c:437
Inline: True
Inline callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:_vcap_rule_find_keysets
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_decode_keyset
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_encode_rule_keyset
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_find_keystream_keysets
```
**Symbols:**

```
ffffffff81c5c120-ffffffff81c5c159: vcap_keyfield_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int vcap_keyfield_count(struct vcap_control *vctrl, enum vcap_type vt, enum vcap_keyfield_set keyset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (ffffffff81d0f400)
Location: drivers/net/ethernet/microchip/vcap/vcap_api.c:437
Inline: True
Inline callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:_vcap_rule_find_keysets
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_decode_keyset
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_encode_rule_keyset
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_find_keystream_keysets
```
**Symbols:**

```
ffffffff81d12a20-ffffffff81d12a59: vcap_keyfield_count (STB_GLOBAL)
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
