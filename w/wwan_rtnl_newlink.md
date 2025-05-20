# Function: <code>wwan_rtnl_newlink</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int wwan_rtnl_newlink(struct net *src_net, struct net_device *dev, struct nlattr **tb, struct nlattr **data, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/wwan/wwan_core.c (ffffffff8191a7f0)
Location: drivers/net/wwan/wwan_core.c:851
Inline: False
Direct callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
**Symbols:**

```
ffffffff8191a7f0-ffffffff8191a8bd: wwan_rtnl_newlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int wwan_rtnl_newlink(struct net *src_net, struct net_device *dev, struct nlattr **tb, struct nlattr **data, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/wwan/wwan_core.c (ffffffff81a6fbe0)
Location: drivers/net/wwan/wwan_core.c:917
Inline: False
Direct callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
**Symbols:**

```
ffffffff81a6fbe0-ffffffff81a6fccb: wwan_rtnl_newlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int wwan_rtnl_newlink(struct net *src_net, struct net_device *dev, struct nlattr **tb, struct nlattr **data, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/wwan/wwan_core.c (ffffffff81c02a60)
Location: drivers/net/wwan/wwan_core.c:922
Inline: False
Direct callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
**Symbols:**

```
ffffffff81c02a60-ffffffff81c02b4b: wwan_rtnl_newlink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int wwan_rtnl_newlink(struct net *src_net, struct net_device *dev, struct nlattr **tb, struct nlattr **data, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/wwan/wwan_core.c (ffffffff81c68110)
Location: drivers/net/wwan/wwan_core.c:955
Inline: False
Direct callers:
  - drivers/net/wwan/wwan_core.c:wwan_create_default_link
```
**Symbols:**

```
ffffffff81c68110-ffffffff81c681fb: wwan_rtnl_newlink (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>
