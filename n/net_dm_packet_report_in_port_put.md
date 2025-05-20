# Function: <code>net_dm_packet_report_in_port_put</code>

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
int net_dm_packet_report_in_port_put(struct sk_buff *msg, int ifindex, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81975ab0)
Location: net/core/drop_monitor.c:567
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
**Symbols:**

```
ffffffff81975ab0-ffffffff81975bb2: net_dm_packet_report_in_port_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int net_dm_packet_report_in_port_put(struct sk_buff *msg, int ifindex, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81a4a760)
Location: net/core/drop_monitor.c:571
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
```
**Symbols:**

```
ffffffff81a4a760-ffffffff81a4a862: net_dm_packet_report_in_port_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int net_dm_packet_report_in_port_put(struct sk_buff *msg, int ifindex, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81a503a0)
Location: net/core/drop_monitor.c:577
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
```
**Symbols:**

```
ffffffff81a503a0-ffffffff81a504a2: net_dm_packet_report_in_port_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int net_dm_packet_report_in_port_put(struct sk_buff *msg, int ifindex, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81a352d0)
Location: net/core/drop_monitor.c:577
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
```
**Symbols:**

```
ffffffff81a352d0-ffffffff81a353d0: net_dm_packet_report_in_port_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int net_dm_packet_report_in_port_put(struct sk_buff *msg, int ifindex, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81aeaea0)
Location: net/core/drop_monitor.c:581
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
```
**Symbols:**

```
ffffffff81aeaea0-ffffffff81aeafa0: net_dm_packet_report_in_port_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int net_dm_packet_report_in_port_put(struct sk_buff *msg, int ifindex, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81c6d6e0)
Location: net/core/drop_monitor.c:597
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
```
**Symbols:**

```
ffffffff81c6d6e0-ffffffff81c6d7e5: net_dm_packet_report_in_port_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int net_dm_packet_report_in_port_put(struct sk_buff *msg, int ifindex, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81e25330)
Location: net/core/drop_monitor.c:584
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
```
**Symbols:**

```
ffffffff81e25330-ffffffff81e25435: net_dm_packet_report_in_port_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int net_dm_packet_report_in_port_put(struct sk_buff *msg, int ifindex, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81e9a870)
Location: net/core/drop_monitor.c:584
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
```
**Symbols:**

```
ffffffff81e9a870-ffffffff81e9a975: net_dm_packet_report_in_port_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int net_dm_packet_report_in_port_put(struct sk_buff *msg, int ifindex, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81f5cfb0)
Location: net/core/drop_monitor.c:584
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_report_fill
  - net/core/drop_monitor.c:net_dm_packet_report_fill
```
**Symbols:**

```
ffffffff81f5cfb0-ffffffff81f5d0b5: net_dm_packet_report_in_port_put (STB_LOCAL)
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
int net_dm_packet_report_in_port_put(struct sk_buff *msg, int ifindex, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffff800010c1bec8)
Location: net/core/drop_monitor.c:567
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
**Symbols:**

```
ffff800010c1bec8-ffff800010c1bfec: net_dm_packet_report_in_port_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int net_dm_packet_report_in_port_put(struct sk_buff *msg, int ifindex, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (c0d33d34)
Location: net/core/drop_monitor.c:567
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
**Symbols:**

```
c0d33d34-c0d33e5c: net_dm_packet_report_in_port_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int net_dm_packet_report_in_port_put(struct sk_buff *msg, int ifindex, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (c000000000d0cbc0)
Location: net/core/drop_monitor.c:567
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
**Symbols:**

```
c000000000d0cbc0-c000000000d0cd40: net_dm_packet_report_in_port_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int net_dm_packet_report_in_port_put(struct sk_buff *msg, int ifindex, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffe000796016)
Location: net/core/drop_monitor.c:567
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
**Symbols:**

```
ffffffe000796016-ffffffe0007960ec: net_dm_packet_report_in_port_put (STB_LOCAL)
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
int net_dm_packet_report_in_port_put(struct sk_buff *msg, int ifindex, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81915a80)
Location: net/core/drop_monitor.c:567
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
**Symbols:**

```
ffffffff81915a80-ffffffff81915b82: net_dm_packet_report_in_port_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int net_dm_packet_report_in_port_put(struct sk_buff *msg, int ifindex, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff818cf830)
Location: net/core/drop_monitor.c:567
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
**Symbols:**

```
ffffffff818cf830-ffffffff818cf932: net_dm_packet_report_in_port_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int net_dm_packet_report_in_port_put(struct sk_buff *msg, int ifindex, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81966ab0)
Location: net/core/drop_monitor.c:567
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
**Symbols:**

```
ffffffff81966ab0-ffffffff81966bb2: net_dm_packet_report_in_port_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int net_dm_packet_report_in_port_put(struct sk_buff *msg, int ifindex, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/drop_monitor.c (ffffffff81988d40)
Location: net/core/drop_monitor.c:567
Inline: False
Direct callers:
  - net/core/drop_monitor.c:net_dm_hw_packet_work
  - net/core/drop_monitor.c:net_dm_packet_work
```
**Symbols:**

```
ffffffff81988d40-ffffffff81988e42: net_dm_packet_report_in_port_put (STB_LOCAL)
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
