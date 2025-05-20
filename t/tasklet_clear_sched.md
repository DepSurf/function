# Function: <code>tasklet_clear_sched</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool tasklet_clear_sched(struct tasklet_struct *t);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810ab750)
Location: kernel/softirq.c:749
Inline: True
Direct callers:
  - kernel/softirq.c:tasklet_kill
```
**Symbols:**

```
ffffffff810ab750-ffffffff810ab7c0: tasklet_clear_sched (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool tasklet_clear_sched(struct tasklet_struct *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/softirq.c (0)
Location: kernel/softirq.c:748
Inline: False
Direct callers:
  - kernel/softirq.c:tasklet_kill
```
**Symbols:**

```
ffffffff810bd0d0-ffffffff810bd16e: tasklet_clear_sched (STB_LOCAL)
ffffffff81ca4226-ffffffff81ca4294: tasklet_clear_sched.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool tasklet_clear_sched(struct tasklet_struct *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/softirq.c (0)
Location: kernel/softirq.c:762
Inline: False
Direct callers:
  - kernel/softirq.c:tasklet_kill
```
**Symbols:**

```
ffffffff810d41d0-ffffffff810d4286: tasklet_clear_sched (STB_LOCAL)
ffffffff81e53abf-ffffffff81e53b26: tasklet_clear_sched.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool tasklet_clear_sched(struct tasklet_struct *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/softirq.c (0)
Location: kernel/softirq.c:762
Inline: False
Direct callers:
  - kernel/softirq.c:tasklet_kill
```
**Symbols:**

```
ffffffff810f3110-ffffffff810f31c6: tasklet_clear_sched (STB_LOCAL)
ffffffff82055cbb-ffffffff82055d22: tasklet_clear_sched.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool tasklet_clear_sched(struct tasklet_struct *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/softirq.c (0)
Location: kernel/softirq.c:744
Inline: False
Direct callers:
  - kernel/softirq.c:tasklet_kill
```
**Symbols:**

```
ffffffff810ff450-ffffffff810ff506: tasklet_clear_sched (STB_LOCAL)
ffffffff820d42ab-ffffffff820d4312: tasklet_clear_sched.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool tasklet_clear_sched(struct tasklet_struct *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/softirq.c (0)
Location: kernel/softirq.c:744
Inline: False
Direct callers:
  - kernel/softirq.c:tasklet_kill
```
**Symbols:**

```
ffffffff81108b00-ffffffff81108bb6: tasklet_clear_sched (STB_LOCAL)
ffffffff821af17b-ffffffff821af1e2: tasklet_clear_sched.cold (STB_LOCAL)
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
