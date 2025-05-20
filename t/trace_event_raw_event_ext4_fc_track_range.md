# Function: <code>trace_event_raw_event_ext4_fc_track_range</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void trace_event_raw_event_ext4_fc_track_range(void *__data, struct inode *inode, long int start, long int end, int ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81441ac0)
Location: include/trace/events/ext4.h:2989
Inline: False
```
**Symbols:**

```
ffffffff81441ac0-ffffffff81441b8c: trace_event_raw_event_ext4_fc_track_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void trace_event_raw_event_ext4_fc_track_range(void *__data, struct inode *inode, long int start, long int end, int ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81447690)
Location: include/trace/events/ext4.h:2813
Inline: False
```
**Symbols:**

```
ffffffff81447690-ffffffff8144776c: trace_event_raw_event_ext4_fc_track_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void trace_event_raw_event_ext4_fc_track_range(void *__data, struct inode *inode, long int start, long int end, int ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8149b280)
Location: include/trace/events/ext4.h:2813
Inline: False
```
**Symbols:**

```
ffffffff8149b280-ffffffff8149b35c: trace_event_raw_event_ext4_fc_track_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void trace_event_raw_event_ext4_fc_track_range(void *__data, handle_t *handle, struct inode *inode, long int start, long int end, int ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8151d530)
Location: include/trace/events/ext4.h:2855
Inline: False
```
**Symbols:**

```
ffffffff8151d530-ffffffff8151d62e: trace_event_raw_event_ext4_fc_track_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void trace_event_raw_event_ext4_fc_track_range(void *__data, handle_t *handle, struct inode *inode, long int start, long int end, int ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815b97b0)
Location: include/trace/events/ext4.h:2893
Inline: False
```
**Symbols:**

```
ffffffff815b97b0-ffffffff815b98ae: trace_event_raw_event_ext4_fc_track_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void trace_event_raw_event_ext4_fc_track_range(void *__data, handle_t *handle, struct inode *inode, long int start, long int end, int ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815f0500)
Location: include/trace/events/ext4.h:2900
Inline: False
```
**Symbols:**

```
ffffffff815f0500-ffffffff815f05fe: trace_event_raw_event_ext4_fc_track_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void trace_event_raw_event_ext4_fc_track_range(void *__data, handle_t *handle, struct inode *inode, long int start, long int end, int ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81628ee0)
Location: include/trace/events/ext4.h:2897
Inline: False
```
**Symbols:**

```
ffffffff81628ee0-ffffffff81628fde: trace_event_raw_event_ext4_fc_track_range (STB_LOCAL)
```
</details>
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>handle_t *handle</code>
</li>
<li>
<b>Param reordered. </b>
<code>__data, inode, start, end, ret</code> ➡️ <code>__data, handle, inode, start, end, ret</code>
</li>
</ul>
</details>
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
