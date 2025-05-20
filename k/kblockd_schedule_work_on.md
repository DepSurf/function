# Function: <code>kblockd_schedule_work_on</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kblockd_schedule_work_on(int cpu, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814144d0)
Location: block/blk-core.c:3094
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_run_hw_queue
```
**Symbols:**

```
ffffffff814144d0-ffffffff814144ed: kblockd_schedule_work_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kblockd_schedule_work_on(int cpu, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81422050)
Location: block/blk-core.c:3190
Inline: False
```
**Symbols:**

```
ffffffff81422050-ffffffff8142206d: kblockd_schedule_work_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kblockd_schedule_work_on(int cpu, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8144ceb0)
Location: block/blk-core.c:3414
Inline: False
```
**Symbols:**

```
ffffffff8144ceb0-ffffffff8144cecd: kblockd_schedule_work_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int kblockd_schedule_work_on(int cpu, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81480120)
Location: block/blk-core.c:3565
Inline: False
```
**Symbols:**

```
ffffffff81480120-ffffffff8148013d: kblockd_schedule_work_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kblockd_schedule_work_on(int cpu, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8149d1a0)
Location: block/blk-core.c:1671
Inline: False
```
**Symbols:**

```
ffffffff8149d1a0-ffffffff8149d1bd: kblockd_schedule_work_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int kblockd_schedule_work_on(int cpu, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cb340)
Location: block/blk-core.c:1622
Inline: False
```
**Symbols:**

```
ffffffff814cb340-ffffffff814cb35d: kblockd_schedule_work_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int kblockd_schedule_work_on(int cpu, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814e4530)
Location: block/blk-core.c:1663
Inline: False
```
**Symbols:**

```
ffffffff814e4530-ffffffff814e454d: kblockd_schedule_work_on (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
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
<summary>In <code>arm64</code>: ✅</summary>

```c
int kblockd_schedule_work_on(int cpu, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffff8000105e0918)
Location: block/blk-core.c:1663
Inline: False
```
**Symbols:**

```
ffff8000105e0918-ffff8000105e0958: kblockd_schedule_work_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kblockd_schedule_work_on(int cpu, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c078ebb4)
Location: block/blk-core.c:1663
Inline: False
```
**Symbols:**

```
c078ebb4-c078ebe0: kblockd_schedule_work_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kblockd_schedule_work_on(int cpu, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c000000000774dc0)
Location: block/blk-core.c:1663
Inline: False
```
**Symbols:**

```
c000000000774dc0-c000000000774e04: kblockd_schedule_work_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int kblockd_schedule_work_on(int cpu, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffe000423c4e)
Location: block/blk-core.c:1663
Inline: False
```
**Symbols:**

```
ffffffe000423c4e-ffffffe000423c8a: kblockd_schedule_work_on (STB_GLOBAL)
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
int kblockd_schedule_work_on(int cpu, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814dcb10)
Location: block/blk-core.c:1663
Inline: False
```
**Symbols:**

```
ffffffff814dcb10-ffffffff814dcb2d: kblockd_schedule_work_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int kblockd_schedule_work_on(int cpu, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cd4c0)
Location: block/blk-core.c:1663
Inline: False
```
**Symbols:**

```
ffffffff814cd4c0-ffffffff814cd4dd: kblockd_schedule_work_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int kblockd_schedule_work_on(int cpu, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814d8ba0)
Location: block/blk-core.c:1663
Inline: False
```
**Symbols:**

```
ffffffff814d8ba0-ffffffff814d8bbd: kblockd_schedule_work_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int kblockd_schedule_work_on(int cpu, struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814f17b0)
Location: block/blk-core.c:1663
Inline: False
```
**Symbols:**

```
ffffffff814f17b0-ffffffff814f17cd: kblockd_schedule_work_on (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
