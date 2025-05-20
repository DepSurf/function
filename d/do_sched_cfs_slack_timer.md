# Function: <code>do_sched_cfs_slack_timer</code>

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
In kernel/sched/fair.c (ffffffff810bc280)
Location: kernel/sched/fair.c:3867
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
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
In kernel/sched/fair.c (ffffffff810bf940)
Location: kernel/sched/fair.c:4205
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
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
In kernel/sched/fair.c (ffffffff810c5800)
Location: kernel/sched/fair.c:4422
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
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
In kernel/sched/fair.c (ffffffff810bf3b0)
Location: kernel/sched/fair.c:4545
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
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
In kernel/sched/fair.c (ffffffff810c6bd0)
Location: kernel/sched/fair.c:4884
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
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
In kernel/sched/fair.c (ffffffff810ceac5)
Location: kernel/sched/fair.c:5057
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
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
In kernel/sched/fair.c (ffffffff810d8045)
Location: kernel/sched/fair.c:4753
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
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
In kernel/sched/fair.c (ffffffff810df375)
Location: kernel/sched/fair.c:4867
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
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
In kernel/sched/fair.c (ffffffff810e9aa5)
Location: kernel/sched/fair.c:4802
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void do_sched_cfs_slack_timer(struct cfs_bandwidth *cfs_b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f4120)
Location: kernel/sched/fair.c:5073
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
```
**Symbols:**

```
ffffffff810f4120-ffffffff810f41d1: do_sched_cfs_slack_timer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void do_sched_cfs_slack_timer(struct cfs_bandwidth *cfs_b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f23c0)
Location: kernel/sched/fair.c:5119
Inline: False
Direct callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
```
**Symbols:**

```
ffffffff810f23c0-ffffffff810f2465: do_sched_cfs_slack_timer (STB_LOCAL)
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
In kernel/sched/fair.c (ffffffff810f46a5)
Location: kernel/sched/fair.c:5182
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
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
In kernel/sched/fair.c (ffffffff8110e065)
Location: kernel/sched/fair.c:5214
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
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
In kernel/sched/fair.c (ffffffff81129d65)
Location: kernel/sched/fair.c:5261
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
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
In kernel/sched/fair.c (ffffffff81153775)
Location: kernel/sched/fair.c:5655
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
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
In kernel/sched/fair.c (ffffffff8116332a)
Location: kernel/sched/fair.c:5865
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
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
In kernel/sched/fair.c (ffffffff8117006a)
Location: kernel/sched/fair.c:6226
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
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
In kernel/sched/fair.c (ffff8000101499f0)
Location: kernel/sched/fair.c:4802
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
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
In kernel/sched/fair.c (c0397790)
Location: kernel/sched/fair.c:4802
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
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
In kernel/sched/fair.c (c00000000019ba48)
Location: kernel/sched/fair.c:4802
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
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
In kernel/sched/fair.c (ffffffe0000f387e)
Location: kernel/sched/fair.c:4802
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
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
In kernel/sched/fair.c (ffffffff810e3c05)
Location: kernel/sched/fair.c:4802
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
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
In kernel/sched/fair.c (ffffffff810d2db5)
Location: kernel/sched/fair.c:4802
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
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
In kernel/sched/fair.c (ffffffff810dffd5)
Location: kernel/sched/fair.c:4802
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
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
In kernel/sched/fair.c (ffffffff810ebb55)
Location: kernel/sched/fair.c:4802
Inline: True
Inline callers:
  - kernel/sched/fair.c:sched_cfs_slack_timer
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
