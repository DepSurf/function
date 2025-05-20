# Function: <code>net_dm_hw_packet_report_size</code>

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
In net/core/drop_monitor.c (ffffffff81975c9b)
Location: net/core/drop_monitor.c:704
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
size_t net_dm_hw_packet_report_size(size_t payload_len, const struct net_dm_hw_metadata *hw_metadata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81a491d0)
Location: net/core/drop_monitor.c:715
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_report
```
**Symbols:**

```
ffffffff81a491d0-ffffffff81a4924c: net_dm_hw_packet_report_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t net_dm_hw_packet_report_size(size_t payload_len, const struct devlink_trap_metadata *hw_metadata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81a4e9c0)
Location: net/core/drop_monitor.c:721
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_report
```
**Symbols:**

```
ffffffff81a4e9c0-ffffffff81a4ea3d: net_dm_hw_packet_report_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
size_t net_dm_hw_packet_report_size(size_t payload_len, const struct devlink_trap_metadata *hw_metadata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81a339e0)
Location: net/core/drop_monitor.c:721
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
```
**Symbols:**

```
ffffffff81a339e0-ffffffff81a33a5f: net_dm_hw_packet_report_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
size_t net_dm_hw_packet_report_size(size_t payload_len, const struct devlink_trap_metadata *hw_metadata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81ae93d0)
Location: net/core/drop_monitor.c:725
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
```
**Symbols:**

```
ffffffff81ae93d0-ffffffff81ae944f: net_dm_hw_packet_report_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
size_t net_dm_hw_packet_report_size(size_t payload_len, const struct devlink_trap_metadata *hw_metadata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81c6bb90)
Location: net/core/drop_monitor.c:748
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
```
**Symbols:**

```
ffffffff81c6bb90-ffffffff81c6bc1b: net_dm_hw_packet_report_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t net_dm_hw_packet_report_size(size_t payload_len, const struct devlink_trap_metadata *hw_metadata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81e23640)
Location: net/core/drop_monitor.c:735
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
```
**Symbols:**

```
ffffffff81e23640-ffffffff81e236cb: net_dm_hw_packet_report_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t net_dm_hw_packet_report_size(size_t payload_len, const struct devlink_trap_metadata *hw_metadata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81e98b80)
Location: net/core/drop_monitor.c:750
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
```
**Symbols:**

```
ffffffff81e98b80-ffffffff81e98c0b: net_dm_hw_packet_report_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t net_dm_hw_packet_report_size(size_t payload_len, const struct devlink_trap_metadata *hw_metadata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81f5b210)
Location: net/core/drop_monitor.c:750
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
```
**Symbols:**

```
ffffffff81f5b210-ffffffff81f5b29b: net_dm_hw_packet_report_size (STB_LOCAL)
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
In net/core/drop_monitor.c (ffff800010c1c148)
Location: net/core/drop_monitor.c:704
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
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
In net/core/drop_monitor.c (c0d33f84)
Location: net/core/drop_monitor.c:704
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
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
In net/core/drop_monitor.c (c000000000d0ce90)
Location: net/core/drop_monitor.c:704
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
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
In net/core/drop_monitor.c (ffffffe000796182)
Location: net/core/drop_monitor.c:704
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
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
In net/core/drop_monitor.c (ffffffff81915c6b)
Location: net/core/drop_monitor.c:704
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
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
In net/core/drop_monitor.c (ffffffff818cfa1b)
Location: net/core/drop_monitor.c:704
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
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
In net/core/drop_monitor.c (ffffffff81966c9b)
Location: net/core/drop_monitor.c:704
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
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
In net/core/drop_monitor.c (ffffffff81988f2b)
Location: net/core/drop_monitor.c:704
Inline: True
Inline callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const struct net_dm_hw_metadata *hw_metadata</code> ➡️ <code>const struct devlink_trap_metadata *hw_metadata</code>
</li>
</ul>
</details>
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
