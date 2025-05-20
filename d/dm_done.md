# Function: <code>dm_done</code>

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
In drivers/md/dm.c (ffffffff816a1c01)
Location: drivers/md/dm.c:1268
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_softirq_done
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
In drivers/md/dm-rq.c (ffffffff8170f221)
Location: drivers/md/dm-rq.c:350
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_softirq_done
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
In drivers/md/dm-rq.c (ffffffff81741231)
Location: drivers/md/dm-rq.c:359
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_softirq_done
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
In drivers/md/dm-rq.c (ffffffff8175b1d2)
Location: drivers/md/dm-rq.c:288
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
In drivers/md/dm-rq.c (ffffffff817cd422)
Location: drivers/md/dm-rq.c:284
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
In drivers/md/dm-rq.c (ffffffff81816222)
Location: drivers/md/dm-rq.c:284
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
In drivers/md/dm-rq.c (ffffffff81841fc2)
Location: drivers/md/dm-rq.c:195
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
In drivers/md/dm-rq.c (ffffffff81884e0d)
Location: drivers/md/dm-rq.c:211
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
In drivers/md/dm-rq.c (ffffffff818b6d8d)
Location: drivers/md/dm-rq.c:211
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void dm_done(struct request *clone, blk_status_t error, bool mapped);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-rq.c (0)
Location: drivers/md/dm-rq.c:204
Inline: False
```
**Symbols:**

```
ffffffff81987640-ffffffff81987834: dm_done (STB_LOCAL)
ffffffff81987b51-ffffffff81987b62: dm_done.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void dm_done(struct request *clone, blk_status_t error, bool mapped);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-rq.c (0)
Location: drivers/md/dm-rq.c:204
Inline: False
```
**Symbols:**

```
ffffffff8198b5d0-ffffffff8198b7c4: dm_done (STB_LOCAL)
ffffffff81c28705-ffffffff81c28716: dm_done.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void dm_done(struct request *clone, blk_status_t error, bool mapped);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-rq.c (0)
Location: drivers/md/dm-rq.c:204
Inline: False
```
**Symbols:**

```
ffffffff8196fcc0-ffffffff8196feb4: dm_done (STB_LOCAL)
ffffffff81c1a8e4-ffffffff81c1a8f5: dm_done.cold (STB_LOCAL)
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
In drivers/md/dm-rq.c (ffffffff81a1863d)
Location: drivers/md/dm-rq.c:204
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
In drivers/md/dm-rq.c (ffffffff81b81383)
Location: drivers/md/dm-rq.c:203
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
In drivers/md/dm-rq.c (ffffffff81d1f6c3)
Location: drivers/md/dm-rq.c:202
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
In drivers/md/dm-rq.c (ffffffff81d8889c)
Location: drivers/md/dm-rq.c:204
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
In drivers/md/dm-rq.c (ffffffff81e3ffac)
Location: drivers/md/dm-rq.c:204
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
In drivers/md/dm-rq.c (ffff800010b0ed88)
Location: drivers/md/dm-rq.c:211
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
In drivers/md/dm-rq.c (c0bed174)
Location: drivers/md/dm-rq.c:211
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
In drivers/md/dm-rq.c (c000000000c01fec)
Location: drivers/md/dm-rq.c:211
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
In drivers/md/dm-rq.c (ffffffe0006fbfc2)
Location: drivers/md/dm-rq.c:211
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
In drivers/md/dm-rq.c (ffffffff8185cc0d)
Location: drivers/md/dm-rq.c:211
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
In drivers/md/dm-rq.c (ffffffff818241dd)
Location: drivers/md/dm-rq.c:211
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
In drivers/md/dm-rq.c (ffffffff818ac23d)
Location: drivers/md/dm-rq.c:211
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
In drivers/md/dm-rq.c (ffffffff818c848d)
Location: drivers/md/dm-rq.c:211
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
</ul>
