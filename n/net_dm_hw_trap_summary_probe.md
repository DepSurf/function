# Function: <code>net_dm_hw_trap_summary_probe</code>

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
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void net_dm_hw_trap_summary_probe(void *ignore, const struct devlink *devlink, struct sk_buff *skb, const struct devlink_trap_metadata *metadata);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81a4eab0)
Location: net/core/drop_monitor.c:437
Inline: True
```
**Symbols:**

```
ffffffff81a4eab0-ffffffff81a4ec7a: net_dm_hw_trap_summary_probe.part.0 (STB_LOCAL)
ffffffff81a4ec80-ffffffff81a4ec9a: net_dm_hw_trap_summary_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void net_dm_hw_trap_summary_probe(void *ignore, const struct devlink *devlink, struct sk_buff *skb, const struct devlink_trap_metadata *metadata);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81a33ad0)
Location: net/core/drop_monitor.c:437
Inline: True
```
**Symbols:**

```
ffffffff81a33ad0-ffffffff81a33c99: net_dm_hw_trap_summary_probe.part.0 (STB_LOCAL)
ffffffff81a33ca0-ffffffff81a33cba: net_dm_hw_trap_summary_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void net_dm_hw_trap_summary_probe(void *ignore, const struct devlink *devlink, struct sk_buff *skb, const struct devlink_trap_metadata *metadata);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81ae94c0)
Location: net/core/drop_monitor.c:441
Inline: True
```
**Symbols:**

```
ffffffff81ae94c0-ffffffff81ae9689: net_dm_hw_trap_summary_probe.part.0 (STB_LOCAL)
ffffffff81ae9690-ffffffff81ae96aa: net_dm_hw_trap_summary_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void net_dm_hw_trap_summary_probe(void *ignore, const struct devlink *devlink, struct sk_buff *skb, const struct devlink_trap_metadata *metadata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81c6bc20)
Location: net/core/drop_monitor.c:448
Inline: False
```
**Symbols:**

```
ffffffff81c6bc20-ffffffff81c6be14: net_dm_hw_trap_summary_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void net_dm_hw_trap_summary_probe(void *ignore, const struct devlink *devlink, struct sk_buff *skb, const struct devlink_trap_metadata *metadata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81e236e0)
Location: net/core/drop_monitor.c:435
Inline: False
```
**Symbols:**

```
ffffffff81e236e0-ffffffff81e23878: net_dm_hw_trap_summary_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void net_dm_hw_trap_summary_probe(void *ignore, const struct devlink *devlink, struct sk_buff *skb, const struct devlink_trap_metadata *metadata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81e98c20)
Location: net/core/drop_monitor.c:437
Inline: False
```
**Symbols:**

```
ffffffff81e98c20-ffffffff81e98db8: net_dm_hw_trap_summary_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void net_dm_hw_trap_summary_probe(void *ignore, const struct devlink *devlink, struct sk_buff *skb, const struct devlink_trap_metadata *metadata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81f5b2b0)
Location: net/core/drop_monitor.c:437
Inline: False
```
**Symbols:**

```
ffffffff81f5b2b0-ffffffff81f5b448: net_dm_hw_trap_summary_probe (STB_LOCAL)
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
