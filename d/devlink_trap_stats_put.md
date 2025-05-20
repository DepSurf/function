# Function: <code>devlink_trap_stats_put</code>

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
int devlink_trap_stats_put(struct sk_buff *msg, struct devlink_stats *trap_stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81983340)
Location: net/core/devlink.c:5351
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_trap_fill
```
**Symbols:**

```
ffffffff81983340-ffffffff81983486: devlink_trap_stats_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int devlink_trap_stats_put(struct sk_buff *msg, struct devlink_stats *trap_stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a5afe0)
Location: net/core/devlink.c:5943
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
```
**Symbols:**

```
ffffffff81a5afe0-ffffffff81a5b136: devlink_trap_stats_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int devlink_trap_stats_put(struct sk_buff *msg, struct devlink_stats *trap_stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a62560)
Location: net/core/devlink.c:6794
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
```
**Symbols:**

```
ffffffff81a62560-ffffffff81a626b6: devlink_trap_stats_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int devlink_trap_stats_put(struct sk_buff *msg, struct devlink_stats *trap_stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81a44d00)
Location: net/core/devlink.c:6997
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
```
**Symbols:**

```
ffffffff81a44d00-ffffffff81a44e47: devlink_trap_stats_put (STB_LOCAL)
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
In net/core/devlink.c (ffffffff81b0359d)
Location: net/core/devlink.c:7653
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
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
In net/core/devlink.c (ffffffff81c84c0f)
Location: net/core/devlink.c:8146
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
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
In net/core/devlink.c (ffffffff81e3ed6f)
Location: net/core/devlink.c:8683
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_nl_trap_fill
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
In net/devlink/leftover.c (ffffffff8203f44f)
Location: net/devlink/leftover.c:5539
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_nl_trap_fill
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
In net/devlink/trap.c (ffffffff82115ffd)
Location: net/devlink/trap.c:211
Inline: True
Inline callers:
  - net/devlink/trap.c:devlink_nl_trap_fill
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
int devlink_trap_stats_put(struct sk_buff *msg, struct devlink_stats *trap_stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffff800010c2b950)
Location: net/core/devlink.c:5351
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_trap_fill
```
**Symbols:**

```
ffff800010c2b950-ffff800010c2bac4: devlink_trap_stats_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int devlink_trap_stats_put(struct sk_buff *msg, struct devlink_stats *trap_stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d42474)
Location: net/core/devlink.c:5351
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_trap_group_fill
  - net/core/devlink.c:devlink_nl_trap_fill
```
**Symbols:**

```
c0d42474-c0d4267c: devlink_trap_stats_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int devlink_trap_stats_put(struct sk_buff *msg, struct devlink_stats *trap_stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c000000000d22150)
Location: net/core/devlink.c:5351
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_trap_fill
```
**Symbols:**

```
c000000000d22150-c000000000d22334: devlink_trap_stats_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int devlink_trap_stats_put(struct sk_buff *msg, struct devlink_stats *trap_stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffe0007a30aa)
Location: net/core/devlink.c:5351
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_trap_fill
```
**Symbols:**

```
ffffffe0007a30aa-ffffffe0007a31d4: devlink_trap_stats_put (STB_LOCAL)
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
int devlink_trap_stats_put(struct sk_buff *msg, struct devlink_stats *trap_stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff819231b0)
Location: net/core/devlink.c:5351
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_trap_fill
```
**Symbols:**

```
ffffffff819231b0-ffffffff819232f6: devlink_trap_stats_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int devlink_trap_stats_put(struct sk_buff *msg, struct devlink_stats *trap_stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff818dcf60)
Location: net/core/devlink.c:5351
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_trap_fill
```
**Symbols:**

```
ffffffff818dcf60-ffffffff818dd0a6: devlink_trap_stats_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int devlink_trap_stats_put(struct sk_buff *msg, struct devlink_stats *trap_stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81974340)
Location: net/core/devlink.c:5351
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_trap_fill
```
**Symbols:**

```
ffffffff81974340-ffffffff81974486: devlink_trap_stats_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int devlink_trap_stats_put(struct sk_buff *msg, struct devlink_stats *trap_stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (ffffffff81996830)
Location: net/core/devlink.c:5351
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_nl_trap_fill
```
**Symbols:**

```
ffffffff81996830-ffffffff81996976: devlink_trap_stats_put (STB_LOCAL)
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
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
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
