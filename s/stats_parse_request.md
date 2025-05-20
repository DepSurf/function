# Function: <code>stats_parse_request</code>

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
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int stats_parse_request(struct ethnl_req_info *req_base, struct nlattr **tb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ethtool/stats.c (ffffffff81a82510)
Location: net/ethtool/stats.c:82
Inline: True
```
**Symbols:**

```
ffffffff81a82510-ffffffff81a82597: stats_parse_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int stats_parse_request(struct ethnl_req_info *req_base, struct nlattr **tb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ethtool/stats.c (ffffffff81b3c0f7)
Location: net/ethtool/stats.c:82
Inline: True
```
**Symbols:**

```
ffffffff81b3c080-ffffffff81b3c11b: stats_parse_request (STB_LOCAL)
ffffffff81d39b33-ffffffff81d39b4e: stats_parse_request.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int stats_parse_request(struct ethnl_req_info *req_base, struct nlattr **tb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ethtool/stats.c (ffffffff81cc7f19)
Location: net/ethtool/stats.c:84
Inline: True
```
**Symbols:**

```
ffffffff81cc7e90-ffffffff81cc7f3d: stats_parse_request (STB_LOCAL)
ffffffff81f06276-ffffffff81f06291: stats_parse_request.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int stats_parse_request(struct ethnl_req_info *req_base, struct nlattr **tb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ethtool/stats.c (ffffffff81e87629)
Location: net/ethtool/stats.c:84
Inline: True
```
**Symbols:**

```
ffffffff81e875a0-ffffffff81e8764d: stats_parse_request (STB_LOCAL)
ffffffff820adf4a-ffffffff820adf65: stats_parse_request.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int stats_parse_request(struct ethnl_req_info *req_base, struct nlattr **tb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/stats.c (0)
Location: net/ethtool/stats.c:87
Inline: False
```
**Symbols:**

```
ffffffff81ee4070-ffffffff81ee413e: stats_parse_request (STB_LOCAL)
ffffffff8212f2c4-ffffffff8212f2df: stats_parse_request.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int stats_parse_request(struct ethnl_req_info *req_base, struct nlattr **tb, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ethtool/stats.c (0)
Location: net/ethtool/stats.c:87
Inline: False
```
**Symbols:**

```
ffffffff81fa7e50-ffffffff81fa7f1e: stats_parse_request (STB_LOCAL)
ffffffff82211055-ffffffff82211070: stats_parse_request.cold (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
