# Function: <code>devlink_dpipe_send_and_alloc_skb</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int devlink_dpipe_send_and_alloc_skb(struct sk_buff **pskb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81947680)
Location: net/core/devlink.c:1820
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
```
**Symbols:**

```
ffffffff81947680-ffffffff819476d9: devlink_dpipe_send_and_alloc_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int devlink_dpipe_send_and_alloc_skb(struct sk_buff **pskb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8197bf50)
Location: net/core/devlink.c:1822
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
```
**Symbols:**

```
ffffffff8197bf50-ffffffff8197bfa9: devlink_dpipe_send_and_alloc_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int devlink_dpipe_send_and_alloc_skb(struct sk_buff **pskb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a53840)
Location: net/core/devlink.c:1854
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
```
**Symbols:**

```
ffffffff81a53840-ffffffff81a5389c: devlink_dpipe_send_and_alloc_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int devlink_dpipe_send_and_alloc_skb(struct sk_buff **pskb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a5a3d0)
Location: net/core/devlink.c:2186
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
```
**Symbols:**

```
ffffffff81a5a3d0-ffffffff81a5a42c: devlink_dpipe_send_and_alloc_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int devlink_dpipe_send_and_alloc_skb(struct sk_buff **pskb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a3d4a0)
Location: net/core/devlink.c:2389
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
```
**Symbols:**

```
ffffffff81a3d4a0-ffffffff81a3d4fc: devlink_dpipe_send_and_alloc_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int devlink_dpipe_send_and_alloc_skb(struct sk_buff **pskb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81af3aa0)
Location: net/core/devlink.c:2951
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
```
**Symbols:**

```
ffffffff81af3aa0-ffffffff81af3afc: devlink_dpipe_send_and_alloc_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int devlink_dpipe_send_and_alloc_skb(struct sk_buff **pskb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c78050)
Location: net/core/devlink.c:3466
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
```
**Symbols:**

```
ffffffff81c78050-ffffffff81c780b8: devlink_dpipe_send_and_alloc_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int devlink_dpipe_send_and_alloc_skb(struct sk_buff **pskb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e30af0)
Location: net/core/devlink.c:3730
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
```
**Symbols:**

```
ffffffff81e30af0-ffffffff81e30b58: devlink_dpipe_send_and_alloc_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int devlink_dpipe_send_and_alloc_skb(struct sk_buff **pskb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/leftover.c (ffffffff820332e0)
Location: net/devlink/leftover.c:2948
Inline: False
Direct callers:
  - net/devlink/leftover.c:devlink_nl_cmd_dpipe_entries_get
```
**Symbols:**

```
ffffffff820332e0-ffffffff82033348: devlink_dpipe_send_and_alloc_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int devlink_dpipe_send_and_alloc_skb(struct sk_buff **pskb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/dpipe.c (ffffffff8210a6d0)
Location: net/devlink/dpipe.c:196
Inline: False
Direct callers:
  - net/devlink/dpipe.c:devlink_nl_dpipe_entries_get_doit
```
**Symbols:**

```
ffffffff8210a6d0-ffffffff8210a738: devlink_dpipe_send_and_alloc_skb (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int devlink_dpipe_send_and_alloc_skb(struct sk_buff **pskb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c23998)
Location: net/core/devlink.c:1822
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
```
**Symbols:**

```
ffff800010c23998-ffff800010c23a04: devlink_dpipe_send_and_alloc_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int devlink_dpipe_send_and_alloc_skb(struct sk_buff **pskb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d3aee0)
Location: net/core/devlink.c:1822
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
```
**Symbols:**

```
c0d3aee0-c0d3af4c: devlink_dpipe_send_and_alloc_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int devlink_dpipe_send_and_alloc_skb(struct sk_buff **pskb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d17440)
Location: net/core/devlink.c:1822
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
```
**Symbols:**

```
c000000000d17440-c000000000d174d4: devlink_dpipe_send_and_alloc_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int devlink_dpipe_send_and_alloc_skb(struct sk_buff **pskb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe00079c146)
Location: net/core/devlink.c:1822
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
```
**Symbols:**

```
ffffffe00079c146-ffffffe00079c1ae: devlink_dpipe_send_and_alloc_skb (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int devlink_dpipe_send_and_alloc_skb(struct sk_buff **pskb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8191bdc0)
Location: net/core/devlink.c:1822
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
```
**Symbols:**

```
ffffffff8191bdc0-ffffffff8191be19: devlink_dpipe_send_and_alloc_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int devlink_dpipe_send_and_alloc_skb(struct sk_buff **pskb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818d5b70)
Location: net/core/devlink.c:1822
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
```
**Symbols:**

```
ffffffff818d5b70-ffffffff818d5bc9: devlink_dpipe_send_and_alloc_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int devlink_dpipe_send_and_alloc_skb(struct sk_buff **pskb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8196cf50)
Location: net/core/devlink.c:1822
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
```
**Symbols:**

```
ffffffff8196cf50-ffffffff8196cfa9: devlink_dpipe_send_and_alloc_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int devlink_dpipe_send_and_alloc_skb(struct sk_buff **pskb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8198f3a0)
Location: net/core/devlink.c:1822
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_nl_cmd_dpipe_entries_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
```
**Symbols:**

```
ffffffff8198f3a0-ffffffff8198f3f9: devlink_dpipe_send_and_alloc_skb (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
