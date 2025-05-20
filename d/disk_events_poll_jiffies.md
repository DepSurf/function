# Function: <code>disk_events_poll_jiffies</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/genhd.c (ffffffff813ca850)
Location: block/genhd.c:1426
Inline: True
Direct callers:
  - block/genhd.c:__disk_unblock_events
  - block/genhd.c:disk_check_events
```
**Symbols:**

```
ffffffff813ca850-ffffffff813ca87d: disk_events_poll_jiffies.isra.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/genhd.c (ffffffff8140eb10)
Location: block/genhd.c:1455
Inline: True
Direct callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:__disk_unblock_events
```
**Symbols:**

```
ffffffff8140eb10-ffffffff8140eb3d: disk_events_poll_jiffies.isra.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/genhd.c (ffffffff81429eb0)
Location: block/genhd.c:1455
Inline: True
Direct callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:__disk_unblock_events
```
**Symbols:**

```
ffffffff81429eb0-ffffffff81429edd: disk_events_poll_jiffies.isra.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/genhd.c (ffffffff814381c0)
Location: block/genhd.c:1478
Inline: True
Direct callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:__disk_unblock_events
```
**Symbols:**

```
ffffffff814381c0-ffffffff814381f9: disk_events_poll_jiffies.isra.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/genhd.c (ffffffff81463d00)
Location: block/genhd.c:1562
Inline: True
Direct callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:__disk_unblock_events
```
**Symbols:**

```
ffffffff81463d00-ffffffff81463d39: disk_events_poll_jiffies.isra.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int disk_events_poll_jiffies(struct gendisk *disk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81496e10)
Location: block/genhd.c:1597
Inline: False
Direct callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:__disk_unblock_events
```
**Symbols:**

```
ffffffff81496e10-ffffffff81496e53: disk_events_poll_jiffies (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int disk_events_poll_jiffies(struct gendisk *disk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814b0d30)
Location: block/genhd.c:1622
Inline: False
Direct callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:__disk_unblock_events
```
**Symbols:**

```
ffffffff814b0d30-ffffffff814b0d73: disk_events_poll_jiffies (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/genhd.c (ffffffff814df690)
Location: block/genhd.c:1643
Inline: True
Direct callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:__disk_unblock_events
```
**Symbols:**

```
ffffffff814df690-ffffffff814df6c7: disk_events_poll_jiffies.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/genhd.c (ffffffff814f8ac0)
Location: block/genhd.c:1652
Inline: True
Direct callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:__disk_unblock_events
```
**Symbols:**

```
ffffffff814f8ac0-ffffffff814f8af7: disk_events_poll_jiffies.isra.0 (STB_LOCAL)
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
In block/genhd.c (ffffffff8155a551)
Location: block/genhd.c:1851
Inline: True
Inline callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:__disk_unblock_events
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
In block/genhd.c (ffffffff81576a7e)
Location: block/genhd.c:1701
Inline: True
Inline callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:__disk_unblock_events
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
In block/genhd.c (ffffffff8157ea34)
Location: block/genhd.c:1406
Inline: True
Inline callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:__disk_unblock_events
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
In block/disk-events.c (ffffffff815eec12)
Location: block/disk-events.c:41
Inline: True
Inline callers:
  - block/disk-events.c:disk_check_events
  - block/disk-events.c:__disk_unblock_events
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
In block/disk-events.c (ffffffff8169f551)
Location: block/disk-events.c:41
Inline: True
Inline callers:
  - block/disk-events.c:disk_check_events
  - block/disk-events.c:__disk_unblock_events
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
In block/disk-events.c (ffffffff8175dea1)
Location: block/disk-events.c:41
Inline: True
Inline callers:
  - block/disk-events.c:disk_check_events
  - block/disk-events.c:__disk_unblock_events
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
In block/disk-events.c (ffffffff8179cdb1)
Location: block/disk-events.c:41
Inline: True
Inline callers:
  - block/disk-events.c:disk_check_events
  - block/disk-events.c:__disk_unblock_events
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
In block/disk-events.c (ffffffff817e0801)
Location: block/disk-events.c:41
Inline: True
Inline callers:
  - block/disk-events.c:disk_check_events
  - block/disk-events.c:__disk_unblock_events
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/genhd.c (ffff8000105f9f88)
Location: block/genhd.c:1652
Inline: True
Direct callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:__disk_unblock_events
```
**Symbols:**

```
ffff8000105f9f88-ffff8000105f9fd0: disk_events_poll_jiffies.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int disk_events_poll_jiffies(struct gendisk *disk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (c07a494c)
Location: block/genhd.c:1652
Inline: False
Direct callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:__disk_unblock_events
```
**Symbols:**

```
c07a494c-c07a4998: disk_events_poll_jiffies (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int disk_events_poll_jiffies(struct gendisk *disk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (c000000000792230)
Location: block/genhd.c:1652
Inline: False
Direct callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:__disk_unblock_events
```
**Symbols:**

```
c000000000792230-c0000000007922c0: disk_events_poll_jiffies (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int disk_events_poll_jiffies(struct gendisk *disk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffe000435fc4)
Location: block/genhd.c:1652
Inline: False
Direct callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:__disk_unblock_events
```
**Symbols:**

```
ffffffe000435fc4-ffffffe00043600c: disk_events_poll_jiffies (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/genhd.c (ffffffff814f10a0)
Location: block/genhd.c:1652
Inline: True
Direct callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:__disk_unblock_events
```
**Symbols:**

```
ffffffff814f10a0-ffffffff814f10d7: disk_events_poll_jiffies.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/genhd.c (ffffffff814e15e0)
Location: block/genhd.c:1652
Inline: True
Direct callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:__disk_unblock_events
```
**Symbols:**

```
ffffffff814e15e0-ffffffff814e1617: disk_events_poll_jiffies.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/genhd.c (ffffffff814ed130)
Location: block/genhd.c:1652
Inline: True
Direct callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:__disk_unblock_events
```
**Symbols:**

```
ffffffff814ed130-ffffffff814ed167: disk_events_poll_jiffies.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/genhd.c (ffffffff815061a0)
Location: block/genhd.c:1652
Inline: True
Direct callers:
  - block/genhd.c:disk_check_events
  - block/genhd.c:__disk_unblock_events
```
**Symbols:**

```
ffffffff815061a0-ffffffff815061d7: disk_events_poll_jiffies.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
