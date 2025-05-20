# Function: <code>devlink_resource_put</code>

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
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int devlink_resource_put(struct devlink *devlink, struct sk_buff *skb, struct devlink_resource *resource);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:2519
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_resource_put
```
**Symbols:**

```
ffffffff8194a940-ffffffff8194ac87: devlink_resource_put (STB_LOCAL)
ffffffff819521b8-ffffffff819521ec: devlink_resource_put.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int devlink_resource_put(struct devlink *devlink, struct sk_buff *skb, struct devlink_resource *resource);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8197f360)
Location: net/core/devlink.c:2521
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_resource_put
```
**Symbols:**

```
ffffffff8197f360-ffffffff8197f6a7: devlink_resource_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff81a57790)
Location: net/core/devlink.c:2553
Inline: True
```
**Symbols:**

```
ffffffff81a57790-ffffffff81a57a34: devlink_resource_put.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff81a5f4e0)
Location: net/core/devlink.c:2885
Inline: True
```
**Symbols:**

```
ffffffff81a5f4e0-ffffffff81a5f784: devlink_resource_put.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (ffffffff81a40f30)
Location: net/core/devlink.c:3088
Inline: True
```
**Symbols:**

```
ffffffff81a40f30-ffffffff81a4126e: devlink_resource_put.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:3650
Inline: True
```
**Symbols:**

```
ffffffff81af8800-ffffffff81af8b45: devlink_resource_put.isra.0 (STB_LOCAL)
ffffffff81d38755-ffffffff81d3876a: devlink_resource_put.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:4165
Inline: True
```
**Symbols:**

```
ffffffff81c7c9e0-ffffffff81c7cd22: devlink_resource_put.isra.0 (STB_LOCAL)
ffffffff81f050d2-ffffffff81f050e7: devlink_resource_put.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:4430
Inline: True
```
**Symbols:**

```
ffffffff81e35060-ffffffff81e353a2: devlink_resource_put.isra.0 (STB_LOCAL)
ffffffff820ad0a6-ffffffff820ad0c1: devlink_resource_put.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/devlink/leftover.c (0)
Location: net/devlink/leftover.c:3648
Inline: True
```
**Symbols:**

```
ffffffff82037f70-ffffffff820382b2: devlink_resource_put.isra.0 (STB_LOCAL)
ffffffff82136491-ffffffff821364ac: devlink_resource_put.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/devlink/resource.c (0)
Location: net/devlink/resource.c:165
Inline: True
```
**Symbols:**

```
ffffffff8210c3d0-ffffffff8210c712: devlink_resource_put.isra.0 (STB_LOCAL)
ffffffff822181ab-ffffffff822181c6: devlink_resource_put.isra.0.cold (STB_LOCAL)
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
int devlink_resource_put(struct devlink *devlink, struct sk_buff *skb, struct devlink_resource *resource);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c27d60)
Location: net/core/devlink.c:2521
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_resource_put
```
**Symbols:**

```
ffff800010c27d60-ffff800010c28078: devlink_resource_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int devlink_resource_put(struct devlink *devlink, struct sk_buff *skb, struct devlink_resource *resource);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d3dee8)
Location: net/core/devlink.c:2521
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_resource_put
```
**Symbols:**

```
c0d3dee8-c0d3e22c: devlink_resource_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int devlink_resource_put(struct devlink *devlink, struct sk_buff *skb, struct devlink_resource *resource);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d1d110)
Location: net/core/devlink.c:2521
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_resource_put
```
**Symbols:**

```
c000000000d1d110-c000000000d1d550: devlink_resource_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int devlink_resource_put(struct devlink *devlink, struct sk_buff *skb, struct devlink_resource *resource);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe0007a0590)
Location: net/core/devlink.c:2521
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_resource_put
```
**Symbols:**

```
ffffffe0007a0590-ffffffe0007a0816: devlink_resource_put (STB_LOCAL)
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
int devlink_resource_put(struct devlink *devlink, struct sk_buff *skb, struct devlink_resource *resource);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8191f1d0)
Location: net/core/devlink.c:2521
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_resource_put
```
**Symbols:**

```
ffffffff8191f1d0-ffffffff8191f517: devlink_resource_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int devlink_resource_put(struct devlink *devlink, struct sk_buff *skb, struct devlink_resource *resource);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818d8f80)
Location: net/core/devlink.c:2521
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_resource_put
```
**Symbols:**

```
ffffffff818d8f80-ffffffff818d92c7: devlink_resource_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int devlink_resource_put(struct devlink *devlink, struct sk_buff *skb, struct devlink_resource *resource);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81970360)
Location: net/core/devlink.c:2521
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_resource_put
```
**Symbols:**

```
ffffffff81970360-ffffffff819706a7: devlink_resource_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int devlink_resource_put(struct devlink *devlink, struct sk_buff *skb, struct devlink_resource *resource);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81992850)
Location: net/core/devlink.c:2521
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_resource_dump
  - net/core/devlink.c:devlink_resource_put
```
**Symbols:**

```
ffffffff81992850-ffffffff81992b97: devlink_resource_put (STB_LOCAL)
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
