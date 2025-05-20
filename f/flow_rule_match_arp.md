# Function: <code>flow_rule_match_arp</code>

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
void flow_rule_match_arp(const struct flow_rule *rule, struct flow_match_arp *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81e075a0)
Location: net/core/flow_offload.c:100
Inline: False
```
**Symbols:**

```
ffffffff81e075a0-ffffffff81e075d1: flow_rule_match_arp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void flow_rule_match_arp(const struct flow_rule *rule, struct flow_match_arp *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81e79ec0)
Location: net/core/flow_offload.c:100
Inline: False
Direct callers:
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_arp_usage
```
**Symbols:**

```
ffffffff81e79ec0-ffffffff81e79ef1: flow_rule_match_arp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void flow_rule_match_arp(const struct flow_rule *rule, struct flow_match_arp *out);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_offload.c (ffffffff81f3a010)
Location: net/core/flow_offload.c:100
Inline: False
Direct callers:
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_arp_usage
```
**Symbols:**

```
ffffffff81f3a010-ffffffff81f3a041: flow_rule_match_arp (STB_GLOBAL)
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
