# Function: <code>vcap_set_rule_set_actionset</code>

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
int vcap_set_rule_set_actionset(struct vcap_rule *rule, enum vcap_actionfield_set actionset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (ffffffff81bf5720)
Location: drivers/net/ethernet/microchip/vcap/vcap_api.c:775
Inline: False
Direct callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_decode_actionset
```
**Symbols:**

```
ffffffff81bf5720-ffffffff81bf57d3: vcap_set_rule_set_actionset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vcap_set_rule_set_actionset(struct vcap_rule *rule, enum vcap_actionfield_set actionset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (ffffffff81c59e70)
Location: drivers/net/ethernet/microchip/vcap/vcap_api.c:904
Inline: False
Direct callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_val_rule
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_decode_actionset
```
**Symbols:**

```
ffffffff81c59e70-ffffffff81c59f23: vcap_set_rule_set_actionset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vcap_set_rule_set_actionset(struct vcap_rule *rule, enum vcap_actionfield_set actionset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (ffffffff81d10750)
Location: drivers/net/ethernet/microchip/vcap/vcap_api.c:904
Inline: False
Direct callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_val_rule
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_decode_actionset
```
**Symbols:**

```
ffffffff81d10750-ffffffff81d10803: vcap_set_rule_set_actionset (STB_GLOBAL)
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
