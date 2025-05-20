# Function: <code>vcap_encode_typegroups</code>

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
void vcap_encode_typegroups(u32 *stream, int sw_width, const struct vcap_typegroup *tg, bool mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (0)
Location: drivers/net/ethernet/microchip/vcap/vcap_api.c:140
Inline: False
Direct callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_encode_rule_actionset
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_encode_rule_keyset
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_encode_rule_keyset
```
**Symbols:**

```
ffffffff81bf5ab0-ffffffff81bf5c0e: vcap_encode_typegroups (STB_LOCAL)
ffffffff8209d927-ffffffff8209d95d: vcap_encode_typegroups.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void vcap_encode_typegroups(u32 *stream, int sw_width, const struct vcap_typegroup *tg, bool mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (0)
Location: drivers/net/ethernet/microchip/vcap/vcap_api.c:142
Inline: False
Direct callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_encode_rule_actionset
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_encode_rule_keyset
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_encode_rule_keyset
```
**Symbols:**

```
ffffffff81c5ae90-ffffffff81c5b006: vcap_encode_typegroups (STB_LOCAL)
ffffffff8211ef9f-ffffffff8211efd5: vcap_encode_typegroups.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void vcap_encode_typegroups(u32 *stream, int sw_width, const struct vcap_typegroup *tg, bool mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (0)
Location: drivers/net/ethernet/microchip/vcap/vcap_api.c:142
Inline: False
Direct callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_encode_rule_actionset
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_encode_rule_keyset
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_encode_rule_keyset
```
**Symbols:**

```
ffffffff81d11770-ffffffff81d118e6: vcap_encode_typegroups (STB_LOCAL)
ffffffff82200775-ffffffff822007ab: vcap_encode_typegroups.cold (STB_LOCAL)
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
