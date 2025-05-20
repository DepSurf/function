# Function: <code>psi_poll_work</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void psi_poll_work(struct kthread_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810f6580)
Location: kernel/sched/psi.c:578
Inline: False
```
**Symbols:**

```
ffffffff810f6580-ffffffff810f6851: psi_poll_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void psi_poll_work(struct kthread_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff81102320)
Location: kernel/sched/psi.c:579
Inline: False
```
**Symbols:**

```
ffffffff81102320-ffffffff811025f0: psi_poll_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void psi_poll_work(struct kthread_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff8110cf50)
Location: kernel/sched/psi.c:579
Inline: False
```
**Symbols:**

```
ffffffff8110cf50-ffffffff8110d0ed: psi_poll_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void psi_poll_work(struct psi_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff8110a650)
Location: kernel/sched/psi.c:576
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_poll_worker
```
**Symbols:**

```
ffffffff8110a650-ffffffff8110a816: psi_poll_work (STB_LOCAL)
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
In kernel/sched/psi.c (ffffffff8110c1fa)
Location: kernel/sched/psi.c:585
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_poll_worker
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
In kernel/sched/psi.c (ffffffff8112afda)
Location: kernel/sched/psi.c:596
Inline: True
Inline callers:
  - kernel/sched/psi.c:psi_poll_worker
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
In kernel/sched/build_utility.c (ffffffff81143bd9)
Location: kernel/sched/psi.c:595
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_poll_worker
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
In kernel/sched/build_utility.c (ffffffff8116f54a)
Location: kernel/sched/psi.c:621
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_poll_worker
```
</details>
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
void psi_poll_work(struct kthread_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffff800010167018)
Location: kernel/sched/psi.c:579
Inline: False
```
**Symbols:**

```
ffff800010167018-ffff8000101672ac: psi_poll_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void psi_poll_work(struct kthread_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (c03b3340)
Location: kernel/sched/psi.c:579
Inline: False
```
**Symbols:**

```
c03b3340-c03b3740: psi_poll_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void psi_poll_work(struct kthread_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (c0000000001bea90)
Location: kernel/sched/psi.c:579
Inline: False
```
**Symbols:**

```
c0000000001bea90-c0000000001bee10: psi_poll_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void psi_poll_work(struct kthread_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffe0001091aa)
Location: kernel/sched/psi.c:579
Inline: False
```
**Symbols:**

```
ffffffe0001091aa-ffffffe0001093a4: psi_poll_work (STB_LOCAL)
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
void psi_poll_work(struct kthread_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810fb630)
Location: kernel/sched/psi.c:579
Inline: False
```
**Symbols:**

```
ffffffff810fb630-ffffffff810fb900: psi_poll_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void psi_poll_work(struct kthread_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810eb850)
Location: kernel/sched/psi.c:579
Inline: False
```
**Symbols:**

```
ffffffff810eb850-ffffffff810ebb20: psi_poll_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void psi_poll_work(struct kthread_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810f87f0)
Location: kernel/sched/psi.c:579
Inline: False
```
**Symbols:**

```
ffffffff810f87f0-ffffffff810f8ac0: psi_poll_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void psi_poll_work(struct kthread_work *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff81103940)
Location: kernel/sched/psi.c:579
Inline: False
```
**Symbols:**

```
ffffffff81103940-ffffffff81103c10: psi_poll_work (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct psi_group *group</code>
</li>
<li>
<b>Param removed. </b>
<code>struct kthread_work *work</code>
</li>
</ul>
</details>
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
