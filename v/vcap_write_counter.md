# Function: <code>vcap_write_counter</code>

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
int vcap_write_counter(struct vcap_rule_internal *ri, struct vcap_counter *ctr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (0)
Location: drivers/net/ethernet/microchip/vcap/vcap_api.c:1380
Inline: False
Direct callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_mod_rule
```
**Symbols:**

```
ffffffff81bf50e0-ffffffff81bf517a: vcap_write_counter (STB_LOCAL)
ffffffff8209d86d-ffffffff8209d882: vcap_write_counter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int vcap_write_counter(struct vcap_rule_internal *ri, struct vcap_counter *ctr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (0)
Location: drivers/net/ethernet/microchip/vcap/vcap_api.c:1576
Inline: False
Direct callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_get_rule_count_by_cookie
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_mod_rule
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_add_rule
```
**Symbols:**

```
ffffffff81c586e0-ffffffff81c5877a: vcap_write_counter (STB_LOCAL)
ffffffff8211edcd-ffffffff8211ede2: vcap_write_counter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int vcap_write_counter(struct vcap_rule_internal *ri, struct vcap_counter *ctr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (0)
Location: drivers/net/ethernet/microchip/vcap/vcap_api.c:1590
Inline: False
Direct callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_get_rule_count_by_cookie
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_mod_rule
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_add_rule
```
**Symbols:**

```
ffffffff81d0ee80-ffffffff81d0ef1a: vcap_write_counter (STB_LOCAL)
ffffffff822005a3-ffffffff822005b8: vcap_write_counter.cold (STB_LOCAL)
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
