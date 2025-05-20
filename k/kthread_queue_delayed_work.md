# Function: <code>kthread_queue_delayed_work</code>

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
bool kthread_queue_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810aa070)
Location: kernel/kthread.c:885
Inline: False
```
**Symbols:**

```
ffffffff810aa070-ffffffff810aa0e5: kthread_queue_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool kthread_queue_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a6c50)
Location: kernel/kthread.c:890
Inline: False
```
**Symbols:**

```
ffffffff810a6c50-ffffffff810a6cc8: kthread_queue_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool kthread_queue_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810ad3c0)
Location: kernel/kthread.c:895
Inline: False
```
**Symbols:**

```
ffffffff810ad3c0-ffffffff810ad438: kthread_queue_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool kthread_queue_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b4130)
Location: kernel/kthread.c:913
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_aux_kworker
```
**Symbols:**

```
ffffffff810b4130-ffffffff810b41a8: kthread_queue_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool kthread_queue_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810bd280)
Location: kernel/kthread.c:915
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_aux_kworker
```
**Symbols:**

```
ffffffff810bd280-ffffffff810bd2f8: kthread_queue_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool kthread_queue_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c3140)
Location: kernel/kthread.c:925
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_aux_kworker
```
**Symbols:**

```
ffffffff810c3140-ffffffff810c31b8: kthread_queue_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool kthread_queue_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c89a0)
Location: kernel/kthread.c:925
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_aux_kworker
```
**Symbols:**

```
ffffffff810c89a0-ffffffff810c8a18: kthread_queue_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool kthread_queue_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810d0490)
Location: kernel/kthread.c:961
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_aux_kworker
```
**Symbols:**

```
ffffffff810d0490-ffffffff810d0502: kthread_queue_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool kthread_queue_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810caeb0)
Location: kernel/kthread.c:1015
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_aux_kworker
```
**Symbols:**

```
ffffffff810caeb0-ffffffff810caf22: kthread_queue_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool kthread_queue_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cc7c0)
Location: kernel/kthread.c:1043
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_aux_kworker
```
**Symbols:**

```
ffffffff810cc7c0-ffffffff810cc832: kthread_queue_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool kthread_queue_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810dfcb0)
Location: kernel/kthread.c:1043
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_aux_kworker
```
**Symbols:**

```
ffffffff810dfcb0-ffffffff810dfd22: kthread_queue_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool kthread_queue_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810fa7a0)
Location: kernel/kthread.c:1103
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_aux_kworker
```
**Symbols:**

```
ffffffff810fa7a0-ffffffff810fa81f: kthread_queue_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool kthread_queue_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff8111d5d0)
Location: kernel/kthread.c:1103
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_aux_kworker
```
**Symbols:**

```
ffffffff8111d5d0-ffffffff8111d64f: kthread_queue_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool kthread_queue_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff8112a6f0)
Location: kernel/kthread.c:1104
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_aux_kworker
```
**Symbols:**

```
ffffffff8112a6f0-ffffffff8112a76f: kthread_queue_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool kthread_queue_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff81134d80)
Location: kernel/kthread.c:1121
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_aux_kworker
```
**Symbols:**

```
ffffffff81134d80-ffffffff81134dff: kthread_queue_delayed_work (STB_GLOBAL)
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
bool kthread_queue_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffff800010127e38)
Location: kernel/kthread.c:925
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_aux_kworker
```
**Symbols:**

```
ffff800010127e38-ffff800010127f24: kthread_queue_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool kthread_queue_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c037a780)
Location: kernel/kthread.c:925
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_aux_kworker
```
**Symbols:**

```
c037a780-c037a7f8: kthread_queue_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool kthread_queue_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c0000000001724d0)
Location: kernel/kthread.c:925
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_aux_kworker
```
**Symbols:**

```
c0000000001724d0-c0000000001725cc: kthread_queue_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool kthread_queue_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffe0000df0fe)
Location: kernel/kthread.c:925
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_aux_kworker
```
**Symbols:**

```
ffffffe0000df0fe-ffffffe0000df172: kthread_queue_delayed_work (STB_GLOBAL)
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
bool kthread_queue_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c2d20)
Location: kernel/kthread.c:925
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_aux_kworker
```
**Symbols:**

```
ffffffff810c2d20-ffffffff810c2d98: kthread_queue_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool kthread_queue_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b1560)
Location: kernel/kthread.c:925
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_aux_kworker
```
**Symbols:**

```
ffffffff810b1560-ffffffff810b15d8: kthread_queue_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool kthread_queue_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c2270)
Location: kernel/kthread.c:925
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_aux_kworker
```
**Symbols:**

```
ffffffff810c2270-ffffffff810c22e8: kthread_queue_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool kthread_queue_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810ca830)
Location: kernel/kthread.c:925
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_aux_kworker
```
**Symbols:**

```
ffffffff810ca830-ffffffff810ca8a8: kthread_queue_delayed_work (STB_GLOBAL)
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
