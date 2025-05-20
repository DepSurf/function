# Function: <code>kthread_cancel_delayed_work_sync</code>

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
bool kthread_cancel_delayed_work_sync(struct kthread_delayed_work *dwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a93d0)
Location: kernel/kthread.c:1117
Inline: False
```
**Symbols:**

```
ffffffff810a93d0-ffffffff810a93e5: kthread_cancel_delayed_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool kthread_cancel_delayed_work_sync(struct kthread_delayed_work *dwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a60d0)
Location: kernel/kthread.c:1122
Inline: False
```
**Symbols:**

```
ffffffff810a60d0-ffffffff810a60e5: kthread_cancel_delayed_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool kthread_cancel_delayed_work_sync(struct kthread_delayed_work *dwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810ac5e0)
Location: kernel/kthread.c:1127
Inline: False
```
**Symbols:**

```
ffffffff810ac5e0-ffffffff810ac5f5: kthread_cancel_delayed_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool kthread_cancel_delayed_work_sync(struct kthread_delayed_work *dwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b3110)
Location: kernel/kthread.c:1145
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_unregister
```
**Symbols:**

```
ffffffff810b3110-ffffffff810b3125: kthread_cancel_delayed_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool kthread_cancel_delayed_work_sync(struct kthread_delayed_work *dwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810bc1a0)
Location: kernel/kthread.c:1147
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_unregister
```
**Symbols:**

```
ffffffff810bc1a0-ffffffff810bc1b5: kthread_cancel_delayed_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool kthread_cancel_delayed_work_sync(struct kthread_delayed_work *dwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c2390)
Location: kernel/kthread.c:1157
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_trigger_destroy
  - drivers/ptp/ptp_clock.c:ptp_clock_unregister
```
**Symbols:**

```
ffffffff810c2390-ffffffff810c23a5: kthread_cancel_delayed_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool kthread_cancel_delayed_work_sync(struct kthread_delayed_work *dwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c88f0)
Location: kernel/kthread.c:1157
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_trigger_destroy
  - drivers/ptp/ptp_clock.c:ptp_clock_unregister
```
**Symbols:**

```
ffffffff810c88f0-ffffffff810c8905: kthread_cancel_delayed_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool kthread_cancel_delayed_work_sync(struct kthread_delayed_work *dwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810d1300)
Location: kernel/kthread.c:1193
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_trigger_destroy
  - drivers/ptp/ptp_clock.c:ptp_cancel_worker_sync
  - drivers/ptp/ptp_clock.c:ptp_clock_unregister
```
**Symbols:**

```
ffffffff810d1300-ffffffff810d1315: kthread_cancel_delayed_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool kthread_cancel_delayed_work_sync(struct kthread_delayed_work *dwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cbdd0)
Location: kernel/kthread.c:1247
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_cancel_worker_sync
  - drivers/ptp/ptp_clock.c:ptp_clock_unregister
```
**Symbols:**

```
ffffffff810cbdd0-ffffffff810cbde5: kthread_cancel_delayed_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool kthread_cancel_delayed_work_sync(struct kthread_delayed_work *dwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cd720)
Location: kernel/kthread.c:1305
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_cancel_worker_sync
  - drivers/ptp/ptp_clock.c:ptp_clock_unregister
```
**Symbols:**

```
ffffffff810cd720-ffffffff810cd735: kthread_cancel_delayed_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool kthread_cancel_delayed_work_sync(struct kthread_delayed_work *dwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810e0910)
Location: kernel/kthread.c:1305
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_cancel_worker_sync
  - drivers/ptp/ptp_clock.c:ptp_clock_unregister
```
**Symbols:**

```
ffffffff810e0910-ffffffff810e0925: kthread_cancel_delayed_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool kthread_cancel_delayed_work_sync(struct kthread_delayed_work *dwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810fa6f0)
Location: kernel/kthread.c:1365
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_cancel_worker_sync
  - drivers/ptp/ptp_clock.c:ptp_clock_unregister
```
**Symbols:**

```
ffffffff810fa6f0-ffffffff810fa70d: kthread_cancel_delayed_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool kthread_cancel_delayed_work_sync(struct kthread_delayed_work *dwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff8111d500)
Location: kernel/kthread.c:1365
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_cancel_worker_sync
  - drivers/ptp/ptp_clock.c:ptp_clock_unregister
```
**Symbols:**

```
ffffffff8111d500-ffffffff8111d51d: kthread_cancel_delayed_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool kthread_cancel_delayed_work_sync(struct kthread_delayed_work *dwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff8112a620)
Location: kernel/kthread.c:1366
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_cancel_worker_sync
  - drivers/ptp/ptp_clock.c:ptp_clock_unregister
```
**Symbols:**

```
ffffffff8112a620-ffffffff8112a63d: kthread_cancel_delayed_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool kthread_cancel_delayed_work_sync(struct kthread_delayed_work *dwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff81134cb0)
Location: kernel/kthread.c:1383
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_cancel_worker_sync
  - drivers/ptp/ptp_clock.c:ptp_clock_unregister
```
**Symbols:**

```
ffffffff81134cb0-ffffffff81134ccd: kthread_cancel_delayed_work_sync (STB_GLOBAL)
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
bool kthread_cancel_delayed_work_sync(struct kthread_delayed_work *dwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffff800010128dc0)
Location: kernel/kthread.c:1157
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_trigger_destroy
  - drivers/ptp/ptp_clock.c:ptp_clock_unregister
```
**Symbols:**

```
ffff800010128dc0-ffff800010128df0: kthread_cancel_delayed_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool kthread_cancel_delayed_work_sync(struct kthread_delayed_work *dwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c037a69c)
Location: kernel/kthread.c:1157
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_trigger_destroy
  - drivers/ptp/ptp_clock.c:ptp_clock_unregister
```
**Symbols:**

```
c037a69c-c037a6bc: kthread_cancel_delayed_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool kthread_cancel_delayed_work_sync(struct kthread_delayed_work *dwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c0000000001723c0)
Location: kernel/kthread.c:1157
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_trigger_destroy
  - drivers/ptp/ptp_clock.c:ptp_clock_unregister
```
**Symbols:**

```
c0000000001723c0-c0000000001723d8: kthread_cancel_delayed_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool kthread_cancel_delayed_work_sync(struct kthread_delayed_work *dwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffe0000dfcfa)
Location: kernel/kthread.c:1157
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_trigger_destroy
  - drivers/ptp/ptp_clock.c:ptp_clock_unregister
```
**Symbols:**

```
ffffffe0000dfcfa-ffffffe0000dfd26: kthread_cancel_delayed_work_sync (STB_GLOBAL)
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
bool kthread_cancel_delayed_work_sync(struct kthread_delayed_work *dwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c2c70)
Location: kernel/kthread.c:1157
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_trigger_destroy
  - drivers/ptp/ptp_clock.c:ptp_clock_unregister
```
**Symbols:**

```
ffffffff810c2c70-ffffffff810c2c85: kthread_cancel_delayed_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool kthread_cancel_delayed_work_sync(struct kthread_delayed_work *dwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b14b0)
Location: kernel/kthread.c:1157
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_trigger_destroy
  - drivers/ptp/ptp_clock.c:ptp_clock_unregister
```
**Symbols:**

```
ffffffff810b14b0-ffffffff810b14c5: kthread_cancel_delayed_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool kthread_cancel_delayed_work_sync(struct kthread_delayed_work *dwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c21c0)
Location: kernel/kthread.c:1157
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_trigger_destroy
  - drivers/ptp/ptp_clock.c:ptp_clock_unregister
```
**Symbols:**

```
ffffffff810c21c0-ffffffff810c21d5: kthread_cancel_delayed_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool kthread_cancel_delayed_work_sync(struct kthread_delayed_work *dwork);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810ca780)
Location: kernel/kthread.c:1157
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_trigger_destroy
  - drivers/ptp/ptp_clock.c:ptp_clock_unregister
```
**Symbols:**

```
ffffffff810ca780-ffffffff810ca795: kthread_cancel_delayed_work_sync (STB_GLOBAL)
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
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
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
