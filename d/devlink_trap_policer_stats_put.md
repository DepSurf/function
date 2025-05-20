# Function: <code>devlink_trap_policer_stats_put</code>

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
int devlink_trap_policer_stats_put(struct sk_buff *msg, struct devlink *devlink, const struct devlink_trap_policer *policer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a5f4f0)
Location: net/core/devlink.c:6458
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_trap_policer_fill
```
**Symbols:**

```
ffffffff81a5f4f0-ffffffff81a5f602: devlink_trap_policer_stats_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int devlink_trap_policer_stats_put(struct sk_buff *msg, struct devlink *devlink, const struct devlink_trap_policer *policer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a67ce0)
Location: net/core/devlink.c:7323
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_trap_policer_fill
```
**Symbols:**

```
ffffffff81a67ce0-ffffffff81a67df2: devlink_trap_policer_stats_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a42f35)
Location: net/core/devlink.c:7526
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_policer_fill
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81af93a5)
Location: net/core/devlink.c:8213
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_policer_fill
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c7c2ad)
Location: net/core/devlink.c:8706
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_policer_fill
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e40b7d)
Location: net/core/devlink.c:9225
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_policer_fill
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/devlink/leftover.c (ffffffff82037741)
Location: net/devlink/leftover.c:6067
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_nl_trap_policer_fill
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/devlink/trap.c (ffffffff82114b71)
Location: net/devlink/trap.c:735
Inline: True
Inline callers:
  - net/devlink/trap.c:devlink_nl_trap_policer_fill
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
