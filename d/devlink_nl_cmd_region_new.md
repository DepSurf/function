# Function: <code>devlink_nl_cmd_region_new</code>

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
int devlink_nl_cmd_region_new(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a586b0)
Location: net/core/devlink.c:4096
Inline: False
```
**Symbols:**

```
ffffffff81a586b0-ffffffff81a58a44: devlink_nl_cmd_region_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int devlink_nl_cmd_region_new(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a60650)
Location: net/core/devlink.c:4733
Inline: False
```
**Symbols:**

```
ffffffff81a60650-ffffffff81a60a90: devlink_nl_cmd_region_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int devlink_nl_cmd_region_new(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a426a0)
Location: net/core/devlink.c:4936
Inline: False
```
**Symbols:**

```
ffffffff81a426a0-ffffffff81a42b27: devlink_nl_cmd_region_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int devlink_nl_cmd_region_new(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81afad40)
Location: net/core/devlink.c:5544
Inline: False
```
**Symbols:**

```
ffffffff81afad40-ffffffff81afb1c7: devlink_nl_cmd_region_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int devlink_nl_cmd_region_new(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c7f8a0)
Location: net/core/devlink.c:6039
Inline: False
```
**Symbols:**

```
ffffffff81c7f8a0-ffffffff81c7fd20: devlink_nl_cmd_region_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int devlink_nl_cmd_region_new(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e388d0)
Location: net/core/devlink.c:6482
Inline: False
```
**Symbols:**

```
ffffffff81e388d0-ffffffff81e38d9c: devlink_nl_cmd_region_new (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int devlink_nl_cmd_region_new(struct sk_buff *skb, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/leftover.c (ffffffff82039a20)
Location: net/devlink/leftover.c:4938
Inline: False
```
**Symbols:**

```
ffffffff82039a20-ffffffff82039ee4: devlink_nl_cmd_region_new (STB_LOCAL)
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
