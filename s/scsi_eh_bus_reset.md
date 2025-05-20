# Function: <code>scsi_eh_bus_reset</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff815ab427)
Location: drivers/scsi/scsi_error.c:1586
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff816033b0)
Location: drivers/scsi/scsi_error.c:1586
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81632aa0)
Location: drivers/scsi/scsi_error.c:1586
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81647588)
Location: drivers/scsi/scsi_error.c:1516
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff816b05e4)
Location: drivers/scsi/scsi_error.c:1542
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff816ec5e4)
Location: drivers/scsi/scsi_error.c:1570
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81710124)
Location: drivers/scsi/scsi_error.c:1567
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff8174b9ab)
Location: drivers/scsi/scsi_error.c:1587
Inline: True
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
In drivers/scsi/scsi_error.c (ffffffff8176fb2b)
Location: drivers/scsi/scsi_error.c:1590
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int scsi_eh_bus_reset(struct Scsi_Host *shost, struct list_head *work_q, struct list_head *done_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_error.c (0)
Location: drivers/scsi/scsi_error.c:1592
Inline: False
```
**Symbols:**

```
ffffffff81832580-ffffffff81832768: scsi_eh_bus_reset (STB_LOCAL)
ffffffff81834058-ffffffff818340d3: scsi_eh_bus_reset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int scsi_eh_bus_reset(struct Scsi_Host *shost, struct list_head *work_q, struct list_head *done_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_error.c (0)
Location: drivers/scsi/scsi_error.c:1607
Inline: False
```
**Symbols:**

```
ffffffff81843190-ffffffff81843378: scsi_eh_bus_reset (STB_LOCAL)
ffffffff81c16720-ffffffff81c1679b: scsi_eh_bus_reset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int scsi_eh_bus_reset(struct Scsi_Host *shost, struct list_head *work_q, struct list_head *done_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_error.c (0)
Location: drivers/scsi/scsi_error.c:1622
Inline: False
```
**Symbols:**

```
ffffffff81826370-ffffffff8182655e: scsi_eh_bus_reset (STB_LOCAL)
ffffffff81c083f9-ffffffff81c08474: scsi_eh_bus_reset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int scsi_eh_bus_reset(struct Scsi_Host *shost, struct list_head *work_q, struct list_head *done_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_error.c (0)
Location: drivers/scsi/scsi_error.c:1641
Inline: False
```
**Symbols:**

```
ffffffff818b1c90-ffffffff818b1e7e: scsi_eh_bus_reset (STB_LOCAL)
ffffffff81d0c2b3-ffffffff81d0c32e: scsi_eh_bus_reset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int scsi_eh_bus_reset(struct Scsi_Host *shost, struct list_head *work_q, struct list_head *done_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_error.c (0)
Location: drivers/scsi/scsi_error.c:1647
Inline: False
```
**Symbols:**

```
ffffffff819fcd10-ffffffff819fcf02: scsi_eh_bus_reset (STB_LOCAL)
ffffffff81ed51d9-ffffffff81ed526f: scsi_eh_bus_reset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int scsi_eh_bus_reset(struct Scsi_Host *shost, struct list_head *work_q, struct list_head *done_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81b7afa0)
Location: drivers/scsi/scsi_error.c:1654
Inline: False
```
**Symbols:**

```
ffffffff81b7afa0-ffffffff81b7b228: scsi_eh_bus_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int scsi_eh_bus_reset(struct Scsi_Host *shost, struct list_head *work_q, struct list_head *done_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81bcecb0)
Location: drivers/scsi/scsi_error.c:1687
Inline: False
```
**Symbols:**

```
ffffffff81bcecb0-ffffffff81bcef38: scsi_eh_bus_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int scsi_eh_bus_reset(struct Scsi_Host *shost, struct list_head *work_q, struct list_head *done_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_error.c (ffffffff81c238d0)
Location: drivers/scsi/scsi_error.c:1690
Inline: False
```
**Symbols:**

```
ffffffff81c238d0-ffffffff81c23b58: scsi_eh_bus_reset (STB_LOCAL)
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
In drivers/scsi/scsi_error.c (ffff800010972d70)
Location: drivers/scsi/scsi_error.c:1590
Inline: True
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
In drivers/scsi/scsi_error.c (c0a47660)
Location: drivers/scsi/scsi_error.c:1590
Inline: True
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
In drivers/scsi/scsi_error.c (c000000000a2c960)
Location: drivers/scsi/scsi_error.c:1590
Inline: True
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
In drivers/scsi/scsi_error.c (ffffffe0005dbce0)
Location: drivers/scsi/scsi_error.c:1590
Inline: True
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
In drivers/scsi/scsi_error.c (ffffffff8172421b)
Location: drivers/scsi/scsi_error.c:1590
Inline: True
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
In drivers/scsi/scsi_error.c (ffffffff816fd64b)
Location: drivers/scsi/scsi_error.c:1590
Inline: True
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
In drivers/scsi/scsi_error.c (ffffffff81762feb)
Location: drivers/scsi/scsi_error.c:1590
Inline: True
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
In drivers/scsi/scsi_error.c (ffffffff8177e64b)
Location: drivers/scsi/scsi_error.c:1590
Inline: True
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
