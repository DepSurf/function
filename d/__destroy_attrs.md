# Function: <code>__destroy_attrs</code>

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
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81b8ec87)
Location: net/ipv6/seg6_local.c:1353
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_destroy_state
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_action
  - net/ipv6/seg6_local.c:parse_nla_action
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81b7dd6f)
Location: net/ipv6/seg6_local.c:1537
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_destroy_state
  - net/ipv6/seg6_local.c:seg6_local_build_state
  - net/ipv6/seg6_local.c:parse_nla_action
  - net/ipv6/seg6_local.c:parse_nla_action
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __destroy_attrs(long unsigned int parsed_attrs, int max_parsed, struct seg6_local_lwt *slwt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81c4987f)
Location: net/ipv6/seg6_local.c:1602
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_destroy_state
  - net/ipv6/seg6_local.c:seg6_local_build_state
Direct callers:
  - net/ipv6/seg6_local.c:parse_nla_action
  - net/ipv6/seg6_local.c:parse_nla_action
```
**Symbols:**

```
ffffffff81c48170-ffffffff81c481da: __destroy_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __destroy_attrs(long unsigned int parsed_attrs, int max_parsed, struct seg6_local_lwt *slwt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81de907f)
Location: net/ipv6/seg6_local.c:1602
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_destroy_state
  - net/ipv6/seg6_local.c:seg6_local_build_state
Direct callers:
  - net/ipv6/seg6_local.c:parse_nla_action
  - net/ipv6/seg6_local.c:parse_nla_action
```
**Symbols:**

```
ffffffff81de7670-ffffffff81de76f2: __destroy_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __destroy_attrs(long unsigned int parsed_attrs, int max_parsed, struct seg6_local_lwt *slwt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81fbc54f)
Location: net/ipv6/seg6_local.c:1929
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_destroy_state
  - net/ipv6/seg6_local.c:seg6_local_build_state
Direct callers:
  - net/ipv6/seg6_local.c:parse_nla_action
  - net/ipv6/seg6_local.c:parse_nla_action
```
**Symbols:**

```
ffffffff81fba600-ffffffff81fba686: __destroy_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __destroy_attrs(long unsigned int parsed_attrs, int max_parsed, struct seg6_local_lwt *slwt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff8201ce3f)
Location: net/ipv6/seg6_local.c:2256
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_destroy_state
  - net/ipv6/seg6_local.c:seg6_local_build_state
Direct callers:
  - net/ipv6/seg6_local.c:parse_nla_action
  - net/ipv6/seg6_local.c:parse_nla_action
```
**Symbols:**

```
ffffffff8201ad40-ffffffff8201adc6: __destroy_attrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __destroy_attrs(long unsigned int parsed_attrs, int max_parsed, struct seg6_local_lwt *slwt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff820ebe1f)
Location: net/ipv6/seg6_local.c:2319
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_local_destroy_state
  - net/ipv6/seg6_local.c:seg6_local_build_state
Direct callers:
  - net/ipv6/seg6_local.c:parse_nla_action
  - net/ipv6/seg6_local.c:parse_nla_action
```
**Symbols:**

```
ffffffff820e9d00-ffffffff820e9d86: __destroy_attrs (STB_LOCAL)
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
