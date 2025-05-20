# Function: <code>mptcp_nl_cmd_add_addr</code>

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
int mptcp_nl_cmd_add_addr(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81bb3b60)
Location: net/mptcp/pm_netlink.c:480
Inline: False
```
**Symbols:**

```
ffffffff81bb3b60-ffffffff81bb3c88: mptcp_nl_cmd_add_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mptcp_nl_cmd_add_addr(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81bc84d0)
Location: net/mptcp/pm_netlink.c:744
Inline: False
```
**Symbols:**

```
ffffffff81bc84d0-ffffffff81bc8603: mptcp_nl_cmd_add_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mptcp_nl_cmd_add_addr(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81bba840)
Location: net/mptcp/pm_netlink.c:1018
Inline: False
```
**Symbols:**

```
ffffffff81bba840-ffffffff81bbaacf: mptcp_nl_cmd_add_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int mptcp_nl_cmd_add_addr(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/pm_netlink.c (0)
Location: net/mptcp/pm_netlink.c:1185
Inline: False
```
**Symbols:**

```
ffffffff81c8a190-ffffffff81c8a40b: mptcp_nl_cmd_add_addr (STB_LOCAL)
ffffffff81d44050-ffffffff81d44065: mptcp_nl_cmd_add_addr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mptcp_nl_cmd_add_addr(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/pm_netlink.c (0)
Location: net/mptcp/pm_netlink.c:1286
Inline: False
```
**Symbols:**

```
ffffffff81e31e90-ffffffff81e321c5: mptcp_nl_cmd_add_addr (STB_LOCAL)
ffffffff81f10b84-ffffffff81f10b99: mptcp_nl_cmd_add_addr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int mptcp_nl_cmd_add_addr(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/pm_netlink.c (0)
Location: net/mptcp/pm_netlink.c:1301
Inline: False
```
**Symbols:**

```
ffffffff8200b1b0-ffffffff8200b51a: mptcp_nl_cmd_add_addr (STB_LOCAL)
ffffffff820b6e82-ffffffff820b6e97: mptcp_nl_cmd_add_addr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int mptcp_nl_cmd_add_addr(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/pm_netlink.c (0)
Location: net/mptcp/pm_netlink.c:1305
Inline: False
```
**Symbols:**

```
ffffffff82087640-ffffffff820879a9: mptcp_nl_cmd_add_addr (STB_LOCAL)
ffffffff821381d4-ffffffff821381e9: mptcp_nl_cmd_add_addr.cold (STB_LOCAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
</ul>
