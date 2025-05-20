# Function: <code>scsi_eh_host_reset</code>

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
In drivers/scsi/scsi_error.c (ffffffff815ab5f8)
Location: drivers/scsi/scsi_error.c:1658
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
In drivers/scsi/scsi_error.c (ffffffff81603579)
Location: drivers/scsi/scsi_error.c:1658
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
In drivers/scsi/scsi_error.c (ffffffff81632c69)
Location: drivers/scsi/scsi_error.c:1658
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
In drivers/scsi/scsi_error.c (ffffffff8164767e)
Location: drivers/scsi/scsi_error.c:1588
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
In drivers/scsi/scsi_error.c (ffffffff816b06cf)
Location: drivers/scsi/scsi_error.c:1614
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
In drivers/scsi/scsi_error.c (ffffffff816ec682)
Location: drivers/scsi/scsi_error.c:1642
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
In drivers/scsi/scsi_error.c (ffffffff817101c2)
Location: drivers/scsi/scsi_error.c:1639
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
In drivers/scsi/scsi_error.c (ffffffff8174ba54)
Location: drivers/scsi/scsi_error.c:1659
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
In drivers/scsi/scsi_error.c (ffffffff8176fbd4)
Location: drivers/scsi/scsi_error.c:1662
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int scsi_eh_host_reset(struct Scsi_Host *shost, struct list_head *work_q, struct list_head *done_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_error.c (0)
Location: drivers/scsi/scsi_error.c:1664
Inline: False
```
**Symbols:**

```
ffffffff81832770-ffffffff818328a3: scsi_eh_host_reset (STB_LOCAL)
ffffffff818340d3-ffffffff81834131: scsi_eh_host_reset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int scsi_eh_host_reset(struct Scsi_Host *shost, struct list_head *work_q, struct list_head *done_q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_error.c (0)
Location: drivers/scsi/scsi_error.c:1679
Inline: False
```
**Symbols:**

```
ffffffff81843380-ffffffff818434b3: scsi_eh_host_reset (STB_LOCAL)
ffffffff81c1679b-ffffffff81c167f9: scsi_eh_host_reset.cold (STB_LOCAL)
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
In drivers/scsi/scsi_error.c (ffffffff8182684f)
Location: drivers/scsi/scsi_error.c:1694
Inline: True
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
In drivers/scsi/scsi_error.c (ffffffff818b219f)
Location: drivers/scsi/scsi_error.c:1713
Inline: True
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
In drivers/scsi/scsi_error.c (ffffffff819fd21d)
Location: drivers/scsi/scsi_error.c:1719
Inline: True
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
In drivers/scsi/scsi_error.c (ffffffff81b7b55d)
Location: drivers/scsi/scsi_error.c:1726
Inline: True
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
In drivers/scsi/scsi_error.c (ffffffff81bcf26d)
Location: drivers/scsi/scsi_error.c:1759
Inline: True
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
In drivers/scsi/scsi_error.c (ffffffff81c23e8d)
Location: drivers/scsi/scsi_error.c:1762
Inline: True
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
In drivers/scsi/scsi_error.c (ffff800010972dfc)
Location: drivers/scsi/scsi_error.c:1662
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
In drivers/scsi/scsi_error.c (c0a47714)
Location: drivers/scsi/scsi_error.c:1662
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
In drivers/scsi/scsi_error.c (c000000000a2ca20)
Location: drivers/scsi/scsi_error.c:1662
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
In drivers/scsi/scsi_error.c (ffffffe0005dbd6a)
Location: drivers/scsi/scsi_error.c:1662
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
In drivers/scsi/scsi_error.c (ffffffff817242c4)
Location: drivers/scsi/scsi_error.c:1662
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
In drivers/scsi/scsi_error.c (ffffffff816fd6f4)
Location: drivers/scsi/scsi_error.c:1662
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
In drivers/scsi/scsi_error.c (ffffffff81763094)
Location: drivers/scsi/scsi_error.c:1662
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
In drivers/scsi/scsi_error.c (ffffffff8177e6f4)
Location: drivers/scsi/scsi_error.c:1662
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
</ul>
