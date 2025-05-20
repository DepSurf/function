# Function: <code>ethnl_default_parse</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ethnl_default_parse(struct ethnl_req_info *req_info, const struct nlmsghdr *nlhdr, struct net *net, const struct ethnl_request_ops *request_ops, struct netlink_ext_ack *extack, bool require_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/netlink.c (ffffffff81a86000)
Location: net/ethtool/netlink.c:255
Inline: False
Direct callers:
  - net/ethtool/netlink.c:ethnl_default_start
  - net/ethtool/netlink.c:ethnl_default_doit
```
**Symbols:**

```
ffffffff81a86000-ffffffff81a860f5: ethnl_default_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ethnl_default_parse(struct ethnl_req_info *req_info, struct nlattr **tb, struct net *net, const struct ethnl_request_ops *request_ops, struct netlink_ext_ack *extack, bool require_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/netlink.c (ffffffff81a8f960)
Location: net/ethtool/netlink.c:269
Inline: False
Direct callers:
  - net/ethtool/netlink.c:ethnl_default_start
  - net/ethtool/netlink.c:ethnl_default_doit
```
**Symbols:**

```
ffffffff81a8f960-ffffffff81a8f9c7: ethnl_default_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ethnl_default_parse(struct ethnl_req_info *req_info, struct nlattr **tb, struct net *net, const struct ethnl_request_ops *request_ops, struct netlink_ext_ack *extack, bool require_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/netlink.c (ffffffff81a790a0)
Location: net/ethtool/netlink.c:272
Inline: False
Direct callers:
  - net/ethtool/netlink.c:ethnl_default_start
  - net/ethtool/netlink.c:ethnl_default_doit
```
**Symbols:**

```
ffffffff81a790a0-ffffffff81a790fd: ethnl_default_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ethnl_default_parse(struct ethnl_req_info *req_info, struct nlattr **tb, struct net *net, const struct ethnl_request_ops *request_ops, struct netlink_ext_ack *extack, bool require_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/netlink.c (ffffffff81b33340)
Location: net/ethtool/netlink.c:307
Inline: False
Direct callers:
  - net/ethtool/netlink.c:ethnl_default_start
  - net/ethtool/netlink.c:ethnl_default_doit
```
**Symbols:**

```
ffffffff81b33340-ffffffff81b3339d: ethnl_default_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ethnl_default_parse(struct ethnl_req_info *req_info, struct nlattr **tb, struct net *net, const struct ethnl_request_ops *request_ops, struct netlink_ext_ack *extack, bool require_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/netlink.c (ffffffff81cbe520)
Location: net/ethtool/netlink.c:310
Inline: False
Direct callers:
  - net/ethtool/netlink.c:ethnl_default_start
  - net/ethtool/netlink.c:ethnl_default_doit
```
**Symbols:**

```
ffffffff81cbe520-ffffffff81cbe58f: ethnl_default_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ethnl_default_parse(struct ethnl_req_info *req_info, struct nlattr **tb, struct net *net, const struct ethnl_request_ops *request_ops, struct netlink_ext_ack *extack, bool require_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/netlink.c (ffffffff81e7cff0)
Location: net/ethtool/netlink.c:312
Inline: False
Direct callers:
  - net/ethtool/netlink.c:ethnl_default_start
  - net/ethtool/netlink.c:ethnl_default_doit
```
**Symbols:**

```
ffffffff81e7cff0-ffffffff81e7d05f: ethnl_default_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ethnl_default_parse(struct ethnl_req_info *req_info, struct nlattr **tb, struct net *net, const struct ethnl_request_ops *request_ops, struct netlink_ext_ack *extack, bool require_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/netlink.c (ffffffff81ed95d0)
Location: net/ethtool/netlink.c:332
Inline: False
Direct callers:
  - net/ethtool/netlink.c:ethnl_default_start
  - net/ethtool/netlink.c:ethnl_default_doit
```
**Symbols:**

```
ffffffff81ed95d0-ffffffff81ed963f: ethnl_default_parse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ethnl_default_parse(struct ethnl_req_info *req_info, const struct genl_info *info, const struct ethnl_request_ops *request_ops, bool require_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/netlink.c (ffffffff81f9d4a0)
Location: net/ethtool/netlink.c:328
Inline: False
Direct callers:
  - net/ethtool/netlink.c:ethnl_default_start
  - net/ethtool/netlink.c:ethnl_default_doit
```
**Symbols:**

```
ffffffff81f9d4a0-ffffffff81f9d516: ethnl_default_parse (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct nlattr **tb</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct nlmsghdr *nlhdr</code>
</li>
</ul>
</details>
</li>
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct genl_info *info</code>
</li>
<li>
<b>Param removed. </b>
<code>struct nlattr **tb</code>
</li>
<li>
<b>Param removed. </b>
<code>struct net *net</code>
</li>
<li>
<b>Param removed. </b>
<code>struct netlink_ext_ack *extack</code>
</li>
<li>
<b>Param reordered. </b>
<code>req_info, tb, net, request_ops, extack, require_dev</code> ➡️ <code>req_info, info, request_ops, require_dev</code>
</li>
</ul>
</details>
</li>
</ul>
