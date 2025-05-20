# Function: <code>devlink_trap_stats_update</code>

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
In net/core/devlink.c (ffffffff8197d223)
Location: net/core/devlink.c:7939
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_report
  - net/core/devlink.c:devlink_trap_report
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
In net/core/devlink.c (ffffffff81a533b8)
Location: net/core/devlink.c:8876
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_report
  - net/core/devlink.c:devlink_trap_report
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
In net/core/devlink.c (ffffffff81a5b0ab)
Location: net/core/devlink.c:9835
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_report
  - net/core/devlink.c:devlink_trap_report
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
In net/core/devlink.c (ffffffff81a3dfab)
Location: net/core/devlink.c:10099
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_report
  - net/core/devlink.c:devlink_trap_report
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
In net/core/devlink.c (ffffffff81af620b)
Location: net/core/devlink.c:11041
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_report
  - net/core/devlink.c:devlink_trap_report
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
In net/core/devlink.c (ffffffff81c726da)
Location: net/core/devlink.c:11637
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_report
  - net/core/devlink.c:devlink_trap_report
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
In net/core/devlink.c (ffffffff81e2aac7)
Location: net/core/devlink.c:12492
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_report
  - net/core/devlink.c:devlink_trap_report
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
In net/devlink/leftover.c (ffffffff8202e9e7)
Location: net/devlink/leftover.c:9087
Inline: True
Inline callers:
  - net/devlink/leftover.c:devlink_trap_report
  - net/devlink/leftover.c:devlink_trap_report
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
In net/devlink/trap.c (ffffffff82114817)
Location: net/devlink/trap.c:1454
Inline: True
Inline callers:
  - net/devlink/trap.c:devlink_trap_report
  - net/devlink/trap.c:devlink_trap_report
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
In net/core/devlink.c (ffff800010c2660c)
Location: net/core/devlink.c:7939
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_report
  - net/core/devlink.c:devlink_trap_report
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void devlink_trap_stats_update(struct devlink_stats *trap_stats, size_t skb_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/devlink.c (c0d39d24)
Location: net/core/devlink.c:7939
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_trap_report
  - net/core/devlink.c:devlink_trap_report
```
**Symbols:**

```
c0d39d24-c0d39d8c: devlink_trap_stats_update (STB_LOCAL)
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
In net/core/devlink.c (c000000000d188b0)
Location: net/core/devlink.c:7939
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_report
  - net/core/devlink.c:devlink_trap_report
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
In net/core/devlink.c (ffffffe00079cfb2)
Location: net/core/devlink.c:7939
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_report
  - net/core/devlink.c:devlink_trap_report
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
In net/core/devlink.c (ffffffff8191d093)
Location: net/core/devlink.c:7939
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_report
  - net/core/devlink.c:devlink_trap_report
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
In net/core/devlink.c (ffffffff818d6e43)
Location: net/core/devlink.c:7939
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_report
  - net/core/devlink.c:devlink_trap_report
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
In net/core/devlink.c (ffffffff8196e223)
Location: net/core/devlink.c:7939
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_report
  - net/core/devlink.c:devlink_trap_report
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
In net/core/devlink.c (ffffffff819906b3)
Location: net/core/devlink.c:7939
Inline: True
Inline callers:
  - net/core/devlink.c:devlink_trap_report
  - net/core/devlink.c:devlink_trap_report
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
