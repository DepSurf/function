# Function: <code>cpu_stop_signal_done</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void cpu_stop_signal_done(struct cpu_stop_done *done, bool executed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff8111fed0)
Location: kernel/stop_machine.c:66
Inline: False
Direct callers:
  - kernel/stop_machine.c:cpu_stop_queue_work
  - kernel/stop_machine.c:cpu_stopper_thread
```
**Symbols:**

```
ffffffff8111fed0-ffffffff8111fef9: cpu_stop_signal_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void cpu_stop_signal_done(struct cpu_stop_done *done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81127e30)
Location: kernel/stop_machine.c:66
Inline: False
Direct callers:
  - kernel/stop_machine.c:cpu_stopper_thread
  - kernel/stop_machine.c:cpu_stop_queue_work
```
**Symbols:**

```
ffffffff81127e30-ffffffff81127e4a: cpu_stop_signal_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cpu_stop_signal_done(struct cpu_stop_done *done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81131ac0)
Location: kernel/stop_machine.c:61
Inline: False
Direct callers:
  - kernel/stop_machine.c:cpu_stopper_thread
  - kernel/stop_machine.c:cpu_stop_queue_work
```
**Symbols:**

```
ffffffff81131ac0-ffffffff81131ada: cpu_stop_signal_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void cpu_stop_signal_done(struct cpu_stop_done *done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81133090)
Location: kernel/stop_machine.c:61
Inline: False
Direct callers:
  - kernel/stop_machine.c:cpu_stopper_thread
  - kernel/stop_machine.c:cpu_stop_queue_work
```
**Symbols:**

```
ffffffff81133090-ffffffff811330ab: cpu_stop_signal_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cpu_stop_signal_done(struct cpu_stop_done *done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff8113fe40)
Location: kernel/stop_machine.c:61
Inline: False
Direct callers:
  - kernel/stop_machine.c:cpu_stopper_thread
  - kernel/stop_machine.c:cpu_stop_queue_work
```
**Symbols:**

```
ffffffff8113fe40-ffffffff8113fe5b: cpu_stop_signal_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void cpu_stop_signal_done(struct cpu_stop_done *done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff8114e730)
Location: kernel/stop_machine.c:62
Inline: False
Direct callers:
  - kernel/stop_machine.c:cpu_stopper_thread
  - kernel/stop_machine.c:cpu_stop_queue_work
```
**Symbols:**

```
ffffffff8114e730-ffffffff8114e74b: cpu_stop_signal_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cpu_stop_signal_done(struct cpu_stop_done *done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff8115b420)
Location: kernel/stop_machine.c:62
Inline: False
Direct callers:
  - kernel/stop_machine.c:cpu_stopper_thread
  - kernel/stop_machine.c:cpu_stop_queue_work
```
**Symbols:**

```
ffffffff8115b420-ffffffff8115b43b: cpu_stop_signal_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void cpu_stop_signal_done(struct cpu_stop_done *done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81167ab0)
Location: kernel/stop_machine.c:61
Inline: False
Direct callers:
  - kernel/stop_machine.c:cpu_stopper_thread
  - kernel/stop_machine.c:cpu_stop_queue_work
```
**Symbols:**

```
ffffffff81167ab0-ffffffff81167aca: cpu_stop_signal_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cpu_stop_signal_done(struct cpu_stop_done *done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81173970)
Location: kernel/stop_machine.c:62
Inline: False
Direct callers:
  - kernel/stop_machine.c:cpu_stopper_thread
  - kernel/stop_machine.c:cpu_stop_queue_work
```
**Symbols:**

```
ffffffff81173970-ffffffff8117398a: cpu_stop_signal_done (STB_LOCAL)
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
In kernel/stop_machine.c (ffffffff81185b09)
Location: kernel/stop_machine.c:62
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
  - kernel/stop_machine.c:cpu_stop_queue_work
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
In kernel/stop_machine.c (ffffffff81182c3a)
Location: kernel/stop_machine.c:78
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
  - kernel/stop_machine.c:cpu_stop_queue_work
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
In kernel/stop_machine.c (ffffffff81183d8a)
Location: kernel/stop_machine.c:78
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
  - kernel/stop_machine.c:cpu_stop_queue_work
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
In kernel/stop_machine.c (ffffffff811abf17)
Location: kernel/stop_machine.c:78
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
  - kernel/stop_machine.c:cpu_stop_queue_work
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
In kernel/stop_machine.c (ffffffff811dd929)
Location: kernel/stop_machine.c:78
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
  - kernel/stop_machine.c:cpu_stop_queue_work
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
In kernel/stop_machine.c (ffffffff81223399)
Location: kernel/stop_machine.c:78
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
  - kernel/stop_machine.c:cpu_stop_queue_work
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
In kernel/stop_machine.c (ffffffff81239bc9)
Location: kernel/stop_machine.c:78
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
  - kernel/stop_machine.c:cpu_stop_queue_work
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
In kernel/stop_machine.c (ffffffff81253899)
Location: kernel/stop_machine.c:78
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
  - kernel/stop_machine.c:cpu_stop_queue_work
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void cpu_stop_signal_done(struct cpu_stop_done *done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffff8000101e7f28)
Location: kernel/stop_machine.c:62
Inline: False
Direct callers:
  - kernel/stop_machine.c:cpu_stopper_thread
  - kernel/stop_machine.c:cpu_stop_queue_work
```
**Symbols:**

```
ffff8000101e7f28-ffff8000101e7f88: cpu_stop_signal_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cpu_stop_signal_done(struct cpu_stop_done *done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (c0428104)
Location: kernel/stop_machine.c:62
Inline: False
Direct callers:
  - kernel/stop_machine.c:cpu_stopper_thread
  - kernel/stop_machine.c:cpu_stop_queue_work
```
**Symbols:**

```
c0428104-c042814c: cpu_stop_signal_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cpu_stop_signal_done(struct cpu_stop_done *done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (c0000000002587d0)
Location: kernel/stop_machine.c:62
Inline: False
Direct callers:
  - kernel/stop_machine.c:cpu_stopper_thread
  - kernel/stop_machine.c:cpu_stop_queue_work
```
**Symbols:**

```
c0000000002587d0-c00000000025882c: cpu_stop_signal_done (STB_LOCAL)
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
In kernel/stop_machine.c (ffffffe00015d38c)
Location: kernel/stop_machine.c:62
Inline: True
Inline callers:
  - kernel/stop_machine.c:cpu_stopper_thread
  - kernel/stop_machine.c:cpu_stop_queue_work
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
void cpu_stop_signal_done(struct cpu_stop_done *done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff8116bf90)
Location: kernel/stop_machine.c:62
Inline: False
Direct callers:
  - kernel/stop_machine.c:cpu_stopper_thread
  - kernel/stop_machine.c:cpu_stop_queue_work
```
**Symbols:**

```
ffffffff8116bf90-ffffffff8116bfaa: cpu_stop_signal_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cpu_stop_signal_done(struct cpu_stop_done *done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff8115f190)
Location: kernel/stop_machine.c:62
Inline: False
Direct callers:
  - kernel/stop_machine.c:cpu_stopper_thread
  - kernel/stop_machine.c:cpu_stop_queue_work
```
**Symbols:**

```
ffffffff8115f190-ffffffff8115f1aa: cpu_stop_signal_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cpu_stop_signal_done(struct cpu_stop_done *done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81169d60)
Location: kernel/stop_machine.c:62
Inline: False
Direct callers:
  - kernel/stop_machine.c:cpu_stopper_thread
  - kernel/stop_machine.c:cpu_stop_queue_work
```
**Symbols:**

```
ffffffff81169d60-ffffffff81169d7a: cpu_stop_signal_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cpu_stop_signal_done(struct cpu_stop_done *done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stop_machine.c (ffffffff81177480)
Location: kernel/stop_machine.c:62
Inline: False
Direct callers:
  - kernel/stop_machine.c:cpu_stopper_thread
  - kernel/stop_machine.c:cpu_stop_queue_work
```
**Symbols:**

```
ffffffff81177480-ffffffff8117749a: cpu_stop_signal_done (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool executed</code>
</li>
</ul>
</details>
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
