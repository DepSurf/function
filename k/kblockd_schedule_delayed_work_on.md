# Function: <code>kblockd_schedule_delayed_work_on</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int kblockd_schedule_delayed_work_on(int cpu, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813b5580)
Location: block/blk-core.c:3135
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_delay_queue
```
**Symbols:**

```
ffffffff813b5580-ffffffff813b55a0: kblockd_schedule_delayed_work_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int kblockd_schedule_delayed_work_on(int cpu, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fa400)
Location: block/blk-core.c:3107
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_delay_queue
```
**Symbols:**

```
ffffffff813fa400-ffffffff813fa420: kblockd_schedule_delayed_work_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kblockd_schedule_delayed_work_on(int cpu, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81413d80)
Location: block/blk-core.c:3107
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_delay_queue
```
**Symbols:**

```
ffffffff81413d80-ffffffff81413da0: kblockd_schedule_delayed_work_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kblockd_schedule_delayed_work_on(int cpu, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81421870)
Location: block/blk-core.c:3210
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
```
**Symbols:**

```
ffffffff81421870-ffffffff81421890: kblockd_schedule_delayed_work_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kblockd_schedule_delayed_work_on(int cpu, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8144c350)
Location: block/blk-core.c:3434
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
```
**Symbols:**

```
ffffffff8144c350-ffffffff8144c370: kblockd_schedule_delayed_work_on (STB_GLOBAL)
```
</details>
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
In <code>5.4</code>: Absent ⚠️
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
