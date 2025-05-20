# Function: <code>vcap_keyfield_name</code>

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
const char *vcap_keyfield_name(struct vcap_control *vctrl, enum vcap_key_field key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (ffffffff81bf6afe)
Location: drivers/net/ethernet/microchip/vcap/vcap_api.c:1533
Inline: True
Inline callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_rule_add_key
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_rule_add_key
Direct callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_debugfs_show_rule_keyfield
```
**Symbols:**

```
ffffffff81bf4760-ffffffff81bf4781: vcap_keyfield_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
const char *vcap_keyfield_name(struct vcap_control *vctrl, enum vcap_key_field key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (ffffffff81c593d9)
Location: drivers/net/ethernet/microchip/vcap/vcap_api.c:1804
Inline: True
Inline callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_rule_add_key
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_rule_add_key
Direct callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_debugfs_show_rule_keyfield
```
**Symbols:**

```
ffffffff81c57b90-ffffffff81c57bb1: vcap_keyfield_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
const char *vcap_keyfield_name(struct vcap_control *vctrl, enum vcap_key_field key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (ffffffff81d0fc79)
Location: drivers/net/ethernet/microchip/vcap/vcap_api.c:1818
Inline: True
Inline callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_rule_add_key
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_rule_add_key
Direct callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api_debugfs.c:vcap_debugfs_show_rule_keyfield
```
**Symbols:**

```
ffffffff81d0e330-ffffffff81d0e351: vcap_keyfield_name (STB_GLOBAL)
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
