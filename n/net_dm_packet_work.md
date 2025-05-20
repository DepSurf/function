# Function: <code>net_dm_packet_work</code>

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
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void net_dm_packet_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/drop_monitor.c (0)
Location: net/core/drop_monitor.c:684
Inline: False
```
**Symbols:**

```
ffffffff81975fb0-ffffffff8197637f: net_dm_packet_work (STB_LOCAL)
ffffffff81976618-ffffffff81976630: net_dm_packet_work.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void net_dm_packet_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81a4b060)
Location: net/core/drop_monitor.c:688
Inline: False
```
**Symbols:**

```
ffffffff81a4b060-ffffffff81a4b152: net_dm_packet_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void net_dm_packet_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81a50c90)
Location: net/core/drop_monitor.c:694
Inline: False
```
**Symbols:**

```
ffffffff81a50c90-ffffffff81a50d82: net_dm_packet_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void net_dm_packet_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81a35aa0)
Location: net/core/drop_monitor.c:694
Inline: False
```
**Symbols:**

```
ffffffff81a35aa0-ffffffff81a35c94: net_dm_packet_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void net_dm_packet_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81aeb670)
Location: net/core/drop_monitor.c:698
Inline: False
```
**Symbols:**

```
ffffffff81aeb670-ffffffff81aeb864: net_dm_packet_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void net_dm_packet_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81c6df60)
Location: net/core/drop_monitor.c:721
Inline: False
```
**Symbols:**

```
ffffffff81c6df60-ffffffff81c6e1a8: net_dm_packet_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void net_dm_packet_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81e25bf0)
Location: net/core/drop_monitor.c:708
Inline: False
```
**Symbols:**

```
ffffffff81e25bf0-ffffffff81e25e13: net_dm_packet_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void net_dm_packet_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81e9b1b0)
Location: net/core/drop_monitor.c:723
Inline: False
```
**Symbols:**

```
ffffffff81e9b1b0-ffffffff81e9b3b6: net_dm_packet_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void net_dm_packet_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81f5d910)
Location: net/core/drop_monitor.c:723
Inline: False
```
**Symbols:**

```
ffffffff81f5d910-ffffffff81f5db2b: net_dm_packet_work (STB_LOCAL)
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
void net_dm_packet_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffff800010c1c420)
Location: net/core/drop_monitor.c:684
Inline: False
```
**Symbols:**

```
ffff800010c1c420-ffff800010c1c840: net_dm_packet_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void net_dm_packet_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (c0d342b4)
Location: net/core/drop_monitor.c:684
Inline: False
```
**Symbols:**

```
c0d342b4-c0d34710: net_dm_packet_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void net_dm_packet_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (c000000000d0d270)
Location: net/core/drop_monitor.c:684
Inline: False
```
**Symbols:**

```
c000000000d0d270-c000000000d0d7c4: net_dm_packet_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void net_dm_packet_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffe00079644c)
Location: net/core/drop_monitor.c:684
Inline: False
```
**Symbols:**

```
ffffffe00079644c-ffffffe000796766: net_dm_packet_work (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void net_dm_packet_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/drop_monitor.c (0)
Location: net/core/drop_monitor.c:684
Inline: False
```
**Symbols:**

```
ffffffff81915f80-ffffffff8191634f: net_dm_packet_work (STB_LOCAL)
ffffffff819165e8-ffffffff81916600: net_dm_packet_work.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void net_dm_packet_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/drop_monitor.c (0)
Location: net/core/drop_monitor.c:684
Inline: False
```
**Symbols:**

```
ffffffff818cfd30-ffffffff818d00ff: net_dm_packet_work (STB_LOCAL)
ffffffff818d0398-ffffffff818d03b0: net_dm_packet_work.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void net_dm_packet_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/drop_monitor.c (0)
Location: net/core/drop_monitor.c:684
Inline: False
```
**Symbols:**

```
ffffffff81966fb0-ffffffff8196737f: net_dm_packet_work (STB_LOCAL)
ffffffff81967618-ffffffff81967630: net_dm_packet_work.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void net_dm_packet_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/drop_monitor.c (0)
Location: net/core/drop_monitor.c:684
Inline: False
```
**Symbols:**

```
ffffffff81989240-ffffffff8198960f: net_dm_packet_work (STB_LOCAL)
ffffffff819898a8-ffffffff819898c0: net_dm_packet_work.cold (STB_LOCAL)
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
