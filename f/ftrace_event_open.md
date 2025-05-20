# Function: <code>ftrace_event_open</code>

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
In kernel/trace/trace_events.c (ffffffff8115e10d)
Location: kernel/trace/trace_events.c:1874
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:ftrace_event_avail_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
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
In kernel/trace/trace_events.c (ffffffff81169ae0)
Location: kernel/trace/trace_events.c:1770
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_avail_open
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
In kernel/trace/trace_events.c (ffffffff81174fa0)
Location: kernel/trace/trace_events.c:1739
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_avail_open
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
In kernel/trace/trace_events.c (ffffffff81177bf0)
Location: kernel/trace/trace_events.c:1779
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_avail_open
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
In kernel/trace/trace_events.c (ffffffff81185280)
Location: kernel/trace/trace_events.c:1779
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_avail_open
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
In kernel/trace/trace_events.c (ffffffff81194300)
Location: kernel/trace/trace_events.c:1777
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_avail_open
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
In kernel/trace/trace_events.c (ffffffff811a2620)
Location: kernel/trace/trace_events.c:1778
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_avail_open
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
In kernel/trace/trace_events.c (ffffffff811b0530)
Location: kernel/trace/trace_events.c:1768
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_avail_open
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
In kernel/trace/trace_events.c (ffffffff811bc930)
Location: kernel/trace/trace_events.c:1760
Inline: True
Direct callers:
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_avail_open
```
**Symbols:**

```
ffffffff811bc930-ffffffff811bc97c: ftrace_event_open.isra.0 (STB_LOCAL)
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
In kernel/trace/trace_events.c (ffffffff811d4ccd)
Location: kernel/trace/trace_events.c:1917
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:ftrace_event_set_npid_open
  - kernel/trace/trace_events.c:ftrace_event_set_npid_open
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_avail_open
  - kernel/trace/trace_events.c:ftrace_event_avail_open
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
In kernel/trace/trace_events.c (ffffffff811d1f2d)
Location: kernel/trace/trace_events.c:1919
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:ftrace_event_set_npid_open
  - kernel/trace/trace_events.c:ftrace_event_set_npid_open
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_avail_open
  - kernel/trace/trace_events.c:ftrace_event_avail_open
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
In kernel/trace/trace_events.c (ffffffff811d338d)
Location: kernel/trace/trace_events.c:2126
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:ftrace_event_set_npid_open
  - kernel/trace/trace_events.c:ftrace_event_set_npid_open
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_avail_open
  - kernel/trace/trace_events.c:ftrace_event_avail_open
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
In kernel/trace/trace_events.c (ffffffff812001cd)
Location: kernel/trace/trace_events.c:2127
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:ftrace_event_set_npid_open
  - kernel/trace/trace_events.c:ftrace_event_set_npid_open
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_avail_open
  - kernel/trace/trace_events.c:ftrace_event_avail_open
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
In kernel/trace/trace_events.c (ffffffff8123b731)
Location: kernel/trace/trace_events.c:2146
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:ftrace_event_set_npid_open
  - kernel/trace/trace_events.c:ftrace_event_set_npid_open
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_avail_open
  - kernel/trace/trace_events.c:ftrace_event_avail_open
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
In kernel/trace/trace_events.c (ffffffff81288371)
Location: kernel/trace/trace_events.c:2166
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:ftrace_event_set_npid_open
  - kernel/trace/trace_events.c:ftrace_event_set_npid_open
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_avail_open
  - kernel/trace/trace_events.c:ftrace_event_avail_open
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
In kernel/trace/trace_events.c (ffffffff812a4f76)
Location: kernel/trace/trace_events.c:2162
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:ftrace_event_set_npid_open
  - kernel/trace/trace_events.c:ftrace_event_set_npid_open
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_avail_open
  - kernel/trace/trace_events.c:ftrace_event_avail_open
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
In kernel/trace/trace_events.c (ffffffff812c0aa6)
Location: kernel/trace/trace_events.c:2207
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:ftrace_event_set_npid_open
  - kernel/trace/trace_events.c:ftrace_event_set_npid_open
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_avail_open
  - kernel/trace/trace_events.c:ftrace_event_avail_open
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
In kernel/trace/trace_events.c (ffff80001023a8d0)
Location: kernel/trace/trace_events.c:1760
Inline: True
Direct callers:
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_avail_open
```
**Symbols:**

```
ffff80001023a8d0-ffff80001023a934: ftrace_event_open.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int ftrace_event_open(struct inode *inode, struct file *file, const struct seq_operations *seq_ops);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (c0476714)
Location: kernel/trace/trace_events.c:1760
Inline: True
Direct callers:
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_avail_open
```
**Symbols:**

```
c0476714-c047675c: ftrace_event_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int ftrace_event_open(struct inode *inode, struct file *file, const struct seq_operations *seq_ops);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (c0000000002c92f0)
Location: kernel/trace/trace_events.c:1760
Inline: True
Direct callers:
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_avail_open
```
**Symbols:**

```
c0000000002c92f0-c0000000002c9390: ftrace_event_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int ftrace_event_open(struct inode *inode, struct file *file, const struct seq_operations *seq_ops);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffe000191e1a)
Location: kernel/trace/trace_events.c:1760
Inline: True
Direct callers:
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_avail_open
```
**Symbols:**

```
ffffffe000191e1a-ffffffe000191e6e: ftrace_event_open (STB_LOCAL)
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
In kernel/trace/trace_events.c (ffffffff811b4f50)
Location: kernel/trace/trace_events.c:1760
Inline: True
Direct callers:
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_avail_open
```
**Symbols:**

```
ffffffff811b4f50-ffffffff811b4f9c: ftrace_event_open.isra.0 (STB_LOCAL)
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
In kernel/trace/trace_events.c (ffffffff811a7d50)
Location: kernel/trace/trace_events.c:1760
Inline: True
Direct callers:
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_avail_open
```
**Symbols:**

```
ffffffff811a7d50-ffffffff811a7d9c: ftrace_event_open.isra.0 (STB_LOCAL)
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
In kernel/trace/trace_events.c (ffffffff811b2d20)
Location: kernel/trace/trace_events.c:1760
Inline: True
Direct callers:
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_avail_open
```
**Symbols:**

```
ffffffff811b2d20-ffffffff811b2d6c: ftrace_event_open.isra.0 (STB_LOCAL)
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
In kernel/trace/trace_events.c (ffffffff811c0dc0)
Location: kernel/trace/trace_events.c:1760
Inline: True
Direct callers:
  - kernel/trace/trace_events.c:ftrace_event_set_pid_open
  - kernel/trace/trace_events.c:ftrace_event_set_open
  - kernel/trace/trace_events.c:ftrace_event_avail_open
```
**Symbols:**

```
ffffffff811c0dc0-ffffffff811c0e0c: ftrace_event_open.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
