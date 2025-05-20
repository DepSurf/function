# Function: <code>parse_nla_counters</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int parse_nla_counters(struct nlattr **attrs, struct seg6_local_lwt *slwt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81b7da20)
Location: net/ipv6/seg6_local.c:1381
Inline: False
```
**Symbols:**

```
ffffffff81b7da20-ffffffff81b7daf2: parse_nla_counters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int parse_nla_counters(struct nlattr **attrs, struct seg6_local_lwt *slwt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81c491a0)
Location: net/ipv6/seg6_local.c:1446
Inline: False
```
**Symbols:**

```
ffffffff81c491a0-ffffffff81c49299: parse_nla_counters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int parse_nla_counters(struct nlattr **attrs, struct seg6_local_lwt *slwt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81de87e0)
Location: net/ipv6/seg6_local.c:1446
Inline: False
```
**Symbols:**

```
ffffffff81de87e0-ffffffff81de8918: parse_nla_counters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int parse_nla_counters(struct nlattr **attrs, struct seg6_local_lwt *slwt, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81fbb5c0)
Location: net/ipv6/seg6_local.c:1581
Inline: False
```
**Symbols:**

```
ffffffff81fbb5c0-ffffffff81fbb70e: parse_nla_counters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int parse_nla_counters(struct nlattr **attrs, struct seg6_local_lwt *slwt, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff8201bc80)
Location: net/ipv6/seg6_local.c:1908
Inline: False
```
**Symbols:**

```
ffffffff8201bc80-ffffffff8201bdce: parse_nla_counters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int parse_nla_counters(struct nlattr **attrs, struct seg6_local_lwt *slwt, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff820eac40)
Location: net/ipv6/seg6_local.c:1969
Inline: False
```
**Symbols:**

```
ffffffff820eac40-ffffffff820ead91: parse_nla_counters (STB_LOCAL)
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct netlink_ext_ack *extack</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
