# Function: <code>net_dm_hw_report</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void net_dm_hw_report(struct sk_buff *skb, const struct net_dm_hw_metadata *hw_metadata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff819745d0)
Location: net/core/drop_monitor.c:956
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_trap_report
```
**Symbols:**

```
ffffffff819745d0-ffffffff819745fc: net_dm_hw_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void net_dm_hw_report(struct sk_buff *skb, const struct net_dm_hw_metadata *hw_metadata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81a48fd0)
Location: net/core/drop_monitor.c:986
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_trap_report
```
**Symbols:**

```
ffffffff81a48fd0-ffffffff81a48ffc: net_dm_hw_report (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void net_dm_hw_report(struct sk_buff *skb, const struct net_dm_hw_metadata *hw_metadata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffff800010c1a460)
Location: net/core/drop_monitor.c:956
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_trap_report
```
**Symbols:**

```
ffff800010c1a460-ffff800010c1a4b8: net_dm_hw_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void net_dm_hw_report(struct sk_buff *skb, const struct net_dm_hw_metadata *hw_metadata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (c0d32530)
Location: net/core/drop_monitor.c:956
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_trap_report
```
**Symbols:**

```
c0d32530-c0d32574: net_dm_hw_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void net_dm_hw_report(struct sk_buff *skb, const struct net_dm_hw_metadata *hw_metadata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (c000000000d0a860)
Location: net/core/drop_monitor.c:956
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_trap_report
```
**Symbols:**

```
c000000000d0a860-c000000000d0a8d4: net_dm_hw_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void net_dm_hw_report(struct sk_buff *skb, const struct net_dm_hw_metadata *hw_metadata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffe000794a1c)
Location: net/core/drop_monitor.c:956
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_trap_report
```
**Symbols:**

```
ffffffe000794a1c-ffffffe000794a6c: net_dm_hw_report (STB_GLOBAL)
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
void net_dm_hw_report(struct sk_buff *skb, const struct net_dm_hw_metadata *hw_metadata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff819145a0)
Location: net/core/drop_monitor.c:956
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_trap_report
```
**Symbols:**

```
ffffffff819145a0-ffffffff819145cc: net_dm_hw_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void net_dm_hw_report(struct sk_buff *skb, const struct net_dm_hw_metadata *hw_metadata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff818ce360)
Location: net/core/drop_monitor.c:956
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_trap_report
```
**Symbols:**

```
ffffffff818ce360-ffffffff818ce38c: net_dm_hw_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void net_dm_hw_report(struct sk_buff *skb, const struct net_dm_hw_metadata *hw_metadata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff819655d0)
Location: net/core/drop_monitor.c:956
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_trap_report
```
**Symbols:**

```
ffffffff819655d0-ffffffff819655fc: net_dm_hw_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void net_dm_hw_report(struct sk_buff *skb, const struct net_dm_hw_metadata *hw_metadata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff819880a0)
Location: net/core/drop_monitor.c:956
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_trap_report
```
**Symbols:**

```
ffffffff819880a0-ffffffff819880e9: net_dm_hw_report (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
