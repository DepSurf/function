# Function: <code>vcap_keyset_list_add</code>

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
bool vcap_keyset_list_add(struct vcap_keyset_list *keysetlist, enum vcap_keyfield_set keyset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (ffffffff81bf4690)
Location: drivers/net/ethernet/microchip/vcap/vcap_api.c:1508
Inline: False
Direct callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:_vcap_rule_find_keysets
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_find_keystream_keysets
```
**Symbols:**

```
ffffffff81bf4690-ffffffff81bf4707: vcap_keyset_list_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool vcap_keyset_list_add(struct vcap_keyset_list *keysetlist, enum vcap_keyfield_set keyset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (ffffffff81c57ac0)
Location: drivers/net/ethernet/microchip/vcap/vcap_api.c:1763
Inline: False
Direct callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_rule_get_keysets
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_rule_get_keysets
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_rule_get_keysets
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:_vcap_rule_find_keysets
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_find_keystream_keysets
```
**Symbols:**

```
ffffffff81c57ac0-ffffffff81c57b37: vcap_keyset_list_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool vcap_keyset_list_add(struct vcap_keyset_list *keysetlist, enum vcap_keyfield_set keyset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (ffffffff81d0e260)
Location: drivers/net/ethernet/microchip/vcap/vcap_api.c:1777
Inline: False
Direct callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_rule_get_keysets
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_rule_get_keysets
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_rule_get_keysets
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:_vcap_rule_find_keysets
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_find_keystream_keysets
```
**Symbols:**

```
ffffffff81d0e260-ffffffff81d0e2d7: vcap_keyset_list_add (STB_GLOBAL)
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
