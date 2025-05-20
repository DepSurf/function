# Function: <code>devlink_dpipe_entry_put</code>

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
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8194da25)
Location: net/core/devlink.c:2021
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff819818f5)
Location: net/core/devlink.c:2023
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int devlink_dpipe_entry_put(struct sk_buff *skb, struct devlink_dpipe_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a5c530)
Location: net/core/devlink.c:2055
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
```
**Symbols:**

```
ffffffff81a5c530-ffffffff81a5c91a: devlink_dpipe_entry_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int devlink_dpipe_entry_put(struct sk_buff *skb, struct devlink_dpipe_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a63920)
Location: net/core/devlink.c:2387
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
```
**Symbols:**

```
ffffffff81a63920-ffffffff81a63d0a: devlink_dpipe_entry_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int devlink_dpipe_entry_put(struct sk_buff *skb, struct devlink_dpipe_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a47960)
Location: net/core/devlink.c:2590
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
```
**Symbols:**

```
ffffffff81a47960-ffffffff81a47d40: devlink_dpipe_entry_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int devlink_dpipe_entry_put(struct sk_buff *skb, struct devlink_dpipe_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:3152
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
```
**Symbols:**

```
ffffffff81afe840-ffffffff81afec2c: devlink_dpipe_entry_put (STB_LOCAL)
ffffffff81d3884a-ffffffff81d3885e: devlink_dpipe_entry_put.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int devlink_dpipe_entry_put(struct sk_buff *skb, struct devlink_dpipe_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:3667
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
```
**Symbols:**

```
ffffffff81c81c50-ffffffff81c8204f: devlink_dpipe_entry_put (STB_LOCAL)
ffffffff81f051c5-ffffffff81f051d9: devlink_dpipe_entry_put.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int devlink_dpipe_entry_put(struct sk_buff *skb, struct devlink_dpipe_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/devlink.c (0)
Location: net/core/devlink.c:3931
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
```
**Symbols:**

```
ffffffff81e39fa0-ffffffff81e3a39f: devlink_dpipe_entry_put (STB_LOCAL)
ffffffff820ad1a6-ffffffff820ad1ba: devlink_dpipe_entry_put.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int devlink_dpipe_entry_put(struct sk_buff *skb, struct devlink_dpipe_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/devlink/leftover.c (0)
Location: net/devlink/leftover.c:3149
Inline: False
Direct callers:
  - net/devlink/leftover.c:devlink_dpipe_entry_ctx_append
```
**Symbols:**

```
ffffffff82039f00-ffffffff8203a2ff: devlink_dpipe_entry_put (STB_LOCAL)
ffffffff821364ac-ffffffff821364c0: devlink_dpipe_entry_put.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int devlink_dpipe_entry_put(struct sk_buff *skb, struct devlink_dpipe_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/devlink/dpipe.c (0)
Location: net/devlink/dpipe.c:396
Inline: False
Direct callers:
  - net/devlink/dpipe.c:devlink_dpipe_entry_ctx_append
```
**Symbols:**

```
ffffffff8210b4a0-ffffffff8210b89f: devlink_dpipe_entry_put (STB_LOCAL)
ffffffff8221812e-ffffffff82218142: devlink_dpipe_entry_put.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c2b584)
Location: net/core/devlink.c:2023
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d408ec)
Location: net/core/devlink.c:2023
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d21494)
Location: net/core/devlink.c:2023
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe0007a2a58)
Location: net/core/devlink.c:2023
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81921765)
Location: net/core/devlink.c:2023
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818db515)
Location: net/core/devlink.c:2023
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff819728f5)
Location: net/core/devlink.c:2023
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81994de5)
Location: net/core/devlink.c:2023
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_dpipe_entry_ctx_append
```
</details>
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
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
