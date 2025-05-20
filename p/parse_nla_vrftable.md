# Function: <code>parse_nla_vrftable</code>

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
<summary>In <code>5.11</code>: ✅</summary>

```c
int parse_nla_vrftable(struct nlattr **attrs, struct seg6_local_lwt *slwt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81b8e0f0)
Location: net/ipv6/seg6_local.c:1088
Inline: False
```
**Symbols:**

```
ffffffff81b8e0f0-ffffffff81b8e113: parse_nla_vrftable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int parse_nla_vrftable(struct nlattr **attrs, struct seg6_local_lwt *slwt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81b7d010)
Location: net/ipv6/seg6_local.c:1162
Inline: False
```
**Symbols:**

```
ffffffff81b7d010-ffffffff81b7d033: parse_nla_vrftable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int parse_nla_vrftable(struct nlattr **attrs, struct seg6_local_lwt *slwt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81c480d0)
Location: net/ipv6/seg6_local.c:1227
Inline: False
```
**Symbols:**

```
ffffffff81c480d0-ffffffff81c480f3: parse_nla_vrftable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int parse_nla_vrftable(struct nlattr **attrs, struct seg6_local_lwt *slwt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81de75d0)
Location: net/ipv6/seg6_local.c:1227
Inline: False
```
**Symbols:**

```
ffffffff81de75d0-ffffffff81de75fb: parse_nla_vrftable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int parse_nla_vrftable(struct nlattr **attrs, struct seg6_local_lwt *slwt, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff81fba540)
Location: net/ipv6/seg6_local.c:1356
Inline: False
```
**Symbols:**

```
ffffffff81fba540-ffffffff81fba56b: parse_nla_vrftable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int parse_nla_vrftable(struct nlattr **attrs, struct seg6_local_lwt *slwt, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff8201ac70)
Location: net/ipv6/seg6_local.c:1683
Inline: False
```
**Symbols:**

```
ffffffff8201ac70-ffffffff8201ac9b: parse_nla_vrftable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int parse_nla_vrftable(struct nlattr **attrs, struct seg6_local_lwt *slwt, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_local.c (ffffffff820e9c30)
Location: net/ipv6/seg6_local.c:1744
Inline: False
```
**Symbols:**

```
ffffffff820e9c30-ffffffff820e9c5b: parse_nla_vrftable (STB_LOCAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
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
