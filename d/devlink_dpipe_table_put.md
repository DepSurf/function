# Function: <code>devlink_dpipe_table_put</code>

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
int devlink_dpipe_table_put(struct sk_buff *skb, struct devlink_dpipe_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:1780
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
```
**Symbols:**

```
ffffffff81951320-ffffffff819515ce: devlink_dpipe_table_put (STB_LOCAL)
ffffffff8195261f-ffffffff81952670: devlink_dpipe_table_put.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int devlink_dpipe_table_put(struct sk_buff *skb, struct devlink_dpipe_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81987d70)
Location: net/core/devlink.c:1782
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
```
**Symbols:**

```
ffffffff81987d70-ffffffff8198800c: devlink_dpipe_table_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int devlink_dpipe_table_put(struct sk_buff *skb, struct devlink_dpipe_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a5fe30)
Location: net/core/devlink.c:1814
Inline: False
```
**Symbols:**

```
ffffffff81a5fe30-ffffffff81a600d2: devlink_dpipe_table_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int devlink_dpipe_table_put(struct sk_buff *skb, struct devlink_dpipe_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a68620)
Location: net/core/devlink.c:2146
Inline: False
```
**Symbols:**

```
ffffffff81a68620-ffffffff81a688c2: devlink_dpipe_table_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int devlink_dpipe_table_put(struct sk_buff *skb, struct devlink_dpipe_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a4b8d0)
Location: net/core/devlink.c:2349
Inline: False
```
**Symbols:**

```
ffffffff81a4b8d0-ffffffff81a4bb68: devlink_dpipe_table_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int devlink_dpipe_table_put(struct sk_buff *skb, struct devlink_dpipe_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:2911
Inline: False
```
**Symbols:**

```
ffffffff81b02ec0-ffffffff81b03177: devlink_dpipe_table_put (STB_LOCAL)
ffffffff81d38a8b-ffffffff81d38ab5: devlink_dpipe_table_put.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int devlink_dpipe_table_put(struct sk_buff *skb, struct devlink_dpipe_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:3426
Inline: False
```
**Symbols:**

```
ffffffff81c84510-ffffffff81c847c6: devlink_dpipe_table_put (STB_LOCAL)
ffffffff81f052ba-ffffffff81f052e4: devlink_dpipe_table_put.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int devlink_dpipe_table_put(struct sk_buff *skb, struct devlink_dpipe_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:3690
Inline: False
```
**Symbols:**

```
ffffffff81e3e640-ffffffff81e3e8f6: devlink_dpipe_table_put (STB_LOCAL)
ffffffff820ad2c4-ffffffff820ad2ee: devlink_dpipe_table_put.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int devlink_dpipe_table_put(struct sk_buff *skb, struct devlink_dpipe_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/devlink/leftover.c (0)
Location: net/devlink/leftover.c:2908
Inline: False
```
**Symbols:**

```
ffffffff8203ecc0-ffffffff8203ef76: devlink_dpipe_table_put (STB_LOCAL)
ffffffff821365c6-ffffffff821365f0: devlink_dpipe_table_put.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int devlink_dpipe_table_put(struct sk_buff *skb, struct devlink_dpipe_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/devlink/dpipe.c (0)
Location: net/devlink/dpipe.c:156
Inline: False
```
**Symbols:**

```
ffffffff8210b8e0-ffffffff8210bb96: devlink_dpipe_table_put (STB_LOCAL)
ffffffff82218142-ffffffff8221816c: devlink_dpipe_table_put.cold (STB_LOCAL)
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
int devlink_dpipe_table_put(struct sk_buff *skb, struct devlink_dpipe_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c2ff48)
Location: net/core/devlink.c:1782
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
```
**Symbols:**

```
ffff800010c2ff48-ffff800010c301dc: devlink_dpipe_table_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int devlink_dpipe_table_put(struct sk_buff *skb, struct devlink_dpipe_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d46ec8)
Location: net/core/devlink.c:1782
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
```
**Symbols:**

```
c0d46ec8-c0d471a0: devlink_dpipe_table_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int devlink_dpipe_table_put(struct sk_buff *skb, struct devlink_dpipe_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d285e0)
Location: net/core/devlink.c:1782
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
```
**Symbols:**

```
c000000000d285e0-c000000000d28958: devlink_dpipe_table_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int devlink_dpipe_table_put(struct sk_buff *skb, struct devlink_dpipe_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe0007a6276)
Location: net/core/devlink.c:1782
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
```
**Symbols:**

```
ffffffe0007a6276-ffffffe0007a6456: devlink_dpipe_table_put (STB_LOCAL)
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
int devlink_dpipe_table_put(struct sk_buff *skb, struct devlink_dpipe_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81927be0)
Location: net/core/devlink.c:1782
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
```
**Symbols:**

```
ffffffff81927be0-ffffffff81927e7c: devlink_dpipe_table_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int devlink_dpipe_table_put(struct sk_buff *skb, struct devlink_dpipe_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818e1990)
Location: net/core/devlink.c:1782
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
```
**Symbols:**

```
ffffffff818e1990-ffffffff818e1c2c: devlink_dpipe_table_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int devlink_dpipe_table_put(struct sk_buff *skb, struct devlink_dpipe_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81978d70)
Location: net/core/devlink.c:1782
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
```
**Symbols:**

```
ffffffff81978d70-ffffffff8197900c: devlink_dpipe_table_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int devlink_dpipe_table_put(struct sk_buff *skb, struct devlink_dpipe_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8199b260)
Location: net/core/devlink.c:1782
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
  - net/core/devlink.c:devlink_nl_cmd_dpipe_table_get
```
**Symbols:**

```
ffffffff8199b260-ffffffff8199b4fc: devlink_dpipe_table_put (STB_LOCAL)
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
