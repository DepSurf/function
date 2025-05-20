# Function: <code>kthread_mod_delayed_work</code>

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
bool kthread_mod_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810aa0f0)
Location: kernel/kthread.c:1022
Inline: False
```
**Symbols:**

```
ffffffff810aa0f0-ffffffff810aa1c8: kthread_mod_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool kthread_mod_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a6cd0)
Location: kernel/kthread.c:1027
Inline: False
```
**Symbols:**

```
ffffffff810a6cd0-ffffffff810a6d88: kthread_mod_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool kthread_mod_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810ad440)
Location: kernel/kthread.c:1032
Inline: False
```
**Symbols:**

```
ffffffff810ad440-ffffffff810ad4f8: kthread_mod_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool kthread_mod_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b41b0)
Location: kernel/kthread.c:1050
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_schedule_worker
```
**Symbols:**

```
ffffffff810b41b0-ffffffff810b4268: kthread_mod_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool kthread_mod_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810bd300)
Location: kernel/kthread.c:1052
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_schedule_worker
```
**Symbols:**

```
ffffffff810bd300-ffffffff810bd3b8: kthread_mod_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool kthread_mod_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c31c0)
Location: kernel/kthread.c:1062
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_schedule_worker
```
**Symbols:**

```
ffffffff810c31c0-ffffffff810c327b: kthread_mod_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool kthread_mod_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c8a20)
Location: kernel/kthread.c:1062
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_schedule_worker
```
**Symbols:**

```
ffffffff810c8a20-ffffffff810c8adb: kthread_mod_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool kthread_mod_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810d0510)
Location: kernel/kthread.c:1098
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_schedule_worker
```
**Symbols:**

```
ffffffff810d0510-ffffffff810d05cb: kthread_mod_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool kthread_mod_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810caf30)
Location: kernel/kthread.c:1152
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_schedule_worker
```
**Symbols:**

```
ffffffff810caf30-ffffffff810cafeb: kthread_mod_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool kthread_mod_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cc840)
Location: kernel/kthread.c:1190
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_schedule_worker
```
**Symbols:**

```
ffffffff810cc840-ffffffff810cc91c: kthread_mod_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool kthread_mod_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810dfd30)
Location: kernel/kthread.c:1190
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_schedule_worker
```
**Symbols:**

```
ffffffff810dfd30-ffffffff810dfe0c: kthread_mod_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool kthread_mod_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810fa820)
Location: kernel/kthread.c:1250
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_schedule_worker
```
**Symbols:**

```
ffffffff810fa820-ffffffff810fa909: kthread_mod_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool kthread_mod_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff8111d660)
Location: kernel/kthread.c:1250
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_schedule_worker
```
**Symbols:**

```
ffffffff8111d660-ffffffff8111d749: kthread_mod_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool kthread_mod_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff8112a780)
Location: kernel/kthread.c:1251
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_schedule_worker
```
**Symbols:**

```
ffffffff8112a780-ffffffff8112a869: kthread_mod_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool kthread_mod_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff81134e10)
Location: kernel/kthread.c:1268
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_schedule_worker
```
**Symbols:**

```
ffffffff81134e10-ffffffff81134ef9: kthread_mod_delayed_work (STB_GLOBAL)
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
bool kthread_mod_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffff800010128a70)
Location: kernel/kthread.c:1062
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_schedule_worker
```
**Symbols:**

```
ffff800010128a70-ffff800010128bb0: kthread_mod_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool kthread_mod_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c037a7f8)
Location: kernel/kthread.c:1062
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_schedule_worker
```
**Symbols:**

```
c037a7f8-c037a8fc: kthread_mod_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool kthread_mod_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c0000000001725d0)
Location: kernel/kthread.c:1062
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_schedule_worker
```
**Symbols:**

```
c0000000001725d0-c0000000001726f0: kthread_mod_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool kthread_mod_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffe0000df172)
Location: kernel/kthread.c:1062
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_schedule_worker
```
**Symbols:**

```
ffffffe0000df172-ffffffe0000df202: kthread_mod_delayed_work (STB_GLOBAL)
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
bool kthread_mod_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c2da0)
Location: kernel/kthread.c:1062
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_schedule_worker
```
**Symbols:**

```
ffffffff810c2da0-ffffffff810c2e5b: kthread_mod_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool kthread_mod_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b15e0)
Location: kernel/kthread.c:1062
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_schedule_worker
```
**Symbols:**

```
ffffffff810b15e0-ffffffff810b169b: kthread_mod_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool kthread_mod_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c22f0)
Location: kernel/kthread.c:1062
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_schedule_worker
```
**Symbols:**

```
ffffffff810c22f0-ffffffff810c23ab: kthread_mod_delayed_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool kthread_mod_delayed_work(struct kthread_worker *worker, struct kthread_delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810ca8b0)
Location: kernel/kthread.c:1062
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_schedule_worker
```
**Symbols:**

```
ffffffff810ca8b0-ffffffff810ca96b: kthread_mod_delayed_work (STB_GLOBAL)
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
