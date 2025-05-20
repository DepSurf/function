# Function: <code>devlink_trap_stats_read</code>

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
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff8198336a)
Location: net/core/devlink.c:5328
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_stats_put
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a5b00a)
Location: net/core/devlink.c:5920
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_stats_put
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a6258a)
Location: net/core/devlink.c:6771
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_stats_put
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
In net/core/devlink.c (ffffffff81a44d33)
Location: net/core/devlink.c:6974
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_stats_put
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void devlink_trap_stats_read(struct devlink_stats *trap_stats, struct devlink_stats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81aefc90)
Location: net/core/devlink.c:7600
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
```
**Symbols:**

```
ffffffff81aefc90-ffffffff81aefd16: devlink_trap_stats_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void devlink_trap_stats_read(struct devlink_stats *trap_stats, struct devlink_stats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81c73110)
Location: net/core/devlink.c:8093
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
```
**Symbols:**

```
ffffffff81c73110-ffffffff81c731b1: devlink_trap_stats_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void devlink_trap_stats_read(struct devlink_stats *trap_stats, struct devlink_stats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81e2c040)
Location: net/core/devlink.c:8628
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
```
**Symbols:**

```
ffffffff81e2c040-ffffffff81e2c0e4: devlink_trap_stats_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void devlink_trap_stats_read(struct devlink_stats *trap_stats, struct devlink_stats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/leftover.c (ffffffff82030960)
Location: net/devlink/leftover.c:5484
Inline: False
Direct callers:
  - net/devlink/leftover.c:devlink_nl_trap_group_fill
  - net/devlink/leftover.c:devlink_nl_trap_fill
```
**Symbols:**

```
ffffffff82030960-ffffffff82030a04: devlink_trap_stats_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void devlink_trap_stats_read(struct devlink_stats *trap_stats, struct devlink_stats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devlink/trap.c (ffffffff82114970)
Location: net/devlink/trap.c:156
Inline: False
Direct callers:
  - net/devlink/trap.c:devlink_nl_trap_group_fill
  - net/devlink/trap.c:devlink_nl_trap_fill
```
**Symbols:**

```
ffffffff82114970-ffffffff82114a14: devlink_trap_stats_read (STB_LOCAL)
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
In net/core/devlink.c (ffff800010c2b988)
Location: net/core/devlink.c:5328
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_stats_put
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
In net/core/devlink.c (c0d424a0)
Location: net/core/devlink.c:5328
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_stats_put
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
In net/core/devlink.c (c000000000d221a8)
Location: net/core/devlink.c:5328
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_stats_put
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
In net/core/devlink.c (ffffffe0007a30ca)
Location: net/core/devlink.c:5328
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_stats_put
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
In net/core/devlink.c (ffffffff819231da)
Location: net/core/devlink.c:5328
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_stats_put
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
In net/core/devlink.c (ffffffff818dcf8a)
Location: net/core/devlink.c:5328
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_stats_put
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
In net/core/devlink.c (ffffffff8197436a)
Location: net/core/devlink.c:5328
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_stats_put
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
In net/core/devlink.c (ffffffff8199685a)
Location: net/core/devlink.c:5328
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_stats_put
```
</details>
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
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
