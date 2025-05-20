# Function: <code>scsi_prep_state_check</code>

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
In drivers/scsi/scsi_lib.c (ffffffff815ae990)
Location: drivers/scsi/scsi_lib.c:1284
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_prep_fn
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
**Symbols:**

```
ffffffff815ae990-ffffffff815aea09: scsi_prep_state_check.isra.24 (STB_LOCAL)
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
In drivers/scsi/scsi_lib.c (ffffffff81606c00)
Location: drivers/scsi/scsi_lib.c:1199
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_prep_fn
```
**Symbols:**

```
ffffffff81606c00-ffffffff81606c79: scsi_prep_state_check.isra.22 (STB_LOCAL)
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
In drivers/scsi/scsi_lib.c (ffffffff81636380)
Location: drivers/scsi/scsi_lib.c:1209
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_prep_fn
```
**Symbols:**

```
ffffffff81636380-ffffffff816363f3: scsi_prep_state_check.isra.27 (STB_LOCAL)
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
In drivers/scsi/scsi_lib.c (ffffffff8164b380)
Location: drivers/scsi/scsi_lib.c:1236
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_prep_fn
```
**Symbols:**

```
ffffffff8164b380-ffffffff8164b3f1: scsi_prep_state_check.isra.29 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int scsi_prep_state_check(struct scsi_device *sdev, struct request *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816b46b0)
Location: drivers/scsi/scsi_lib.c:1285
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_prep_fn
```
**Symbols:**

```
ffffffff816b46b0-ffffffff816b4732: scsi_prep_state_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int scsi_prep_state_check(struct scsi_device *sdev, struct request *req);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816f07f0)
Location: drivers/scsi/scsi_lib.c:1321
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_prep_fn
```
**Symbols:**

```
ffffffff816f07f0-ffffffff816f0871: scsi_prep_state_check (STB_LOCAL)
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
In drivers/scsi/scsi_lib.c (ffffffff817155df)
Location: drivers/scsi/scsi_lib.c:1255
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
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
In drivers/scsi/scsi_lib.c (ffffffff81750c35)
Location: drivers/scsi/scsi_lib.c:1220
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
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
In drivers/scsi/scsi_lib.c (ffffffff81774e80)
Location: drivers/scsi/scsi_lib.c:1232
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
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
In drivers/scsi/scsi_lib.c (ffffffff818381ca)
Location: drivers/scsi/scsi_lib.c:1219
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In drivers/scsi/scsi_lib.c (ffff800010978e1c)
Location: drivers/scsi/scsi_lib.c:1232
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
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
In drivers/scsi/scsi_lib.c (c0a4ca68)
Location: drivers/scsi/scsi_lib.c:1232
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
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
In drivers/scsi/scsi_lib.c (c000000000a337b0)
Location: drivers/scsi/scsi_lib.c:1232
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
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
In drivers/scsi/scsi_lib.c (ffffffe0005e082e)
Location: drivers/scsi/scsi_lib.c:1232
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
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
In drivers/scsi/scsi_lib.c (ffffffff81729570)
Location: drivers/scsi/scsi_lib.c:1232
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
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
In drivers/scsi/scsi_lib.c (ffffffff81702982)
Location: drivers/scsi/scsi_lib.c:1232
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
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
In drivers/scsi/scsi_lib.c (ffffffff81768340)
Location: drivers/scsi/scsi_lib.c:1232
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
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
In drivers/scsi/scsi_lib.c (ffffffff81783a5e)
Location: drivers/scsi/scsi_lib.c:1232
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
