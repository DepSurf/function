# Function: <code>kthread_destroy_worker</code>

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
void kthread_destroy_worker(struct kthread_worker *worker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a9640)
Location: kernel/kthread.c:1150
Inline: False
```
**Symbols:**

```
ffffffff810a9640-ffffffff810a96a8: kthread_destroy_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void kthread_destroy_worker(struct kthread_worker *worker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a6320)
Location: kernel/kthread.c:1155
Inline: False
```
**Symbols:**

```
ffffffff810a6320-ffffffff810a636a: kthread_destroy_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void kthread_destroy_worker(struct kthread_worker *worker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810ac8b0)
Location: kernel/kthread.c:1160
Inline: False
```
**Symbols:**

```
ffffffff810ac8b0-ffffffff810ac8fa: kthread_destroy_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void kthread_destroy_worker(struct kthread_worker *worker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b38c0)
Location: kernel/kthread.c:1178
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_unregister
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
```
**Symbols:**

```
ffffffff810b38c0-ffffffff810b3907: kthread_destroy_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void kthread_destroy_worker(struct kthread_worker *worker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810bcbc0)
Location: kernel/kthread.c:1180
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_unregister
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
```
**Symbols:**

```
ffffffff810bcbc0-ffffffff810bcc07: kthread_destroy_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void kthread_destroy_worker(struct kthread_worker *worker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kthread.c (0)
Location: kernel/kthread.c:1190
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_trigger_destroy
  - drivers/ptp/ptp_clock.c:ptp_clock_unregister
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
```
**Symbols:**

```
ffffffff810c3369-ffffffff810c338f: kthread_destroy_worker.cold (STB_LOCAL)
ffffffff810c2bb0-ffffffff810c2bfc: kthread_destroy_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void kthread_destroy_worker(struct kthread_worker *worker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c8f20)
Location: kernel/kthread.c:1190
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_trigger_destroy
  - drivers/ptp/ptp_clock.c:ptp_clock_unregister
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
```
**Symbols:**

```
ffffffff810c8f20-ffffffff810c8f6f: kthread_destroy_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void kthread_destroy_worker(struct kthread_worker *worker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810d0bb0)
Location: kernel/kthread.c:1226
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_trigger_destroy
  - drivers/ptp/ptp_clock.c:ptp_clock_unregister
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
```
**Symbols:**

```
ffffffff810d0bb0-ffffffff810d0bff: kthread_destroy_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void kthread_destroy_worker(struct kthread_worker *worker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cb410)
Location: kernel/kthread.c:1280
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/ptp/ptp_clock.c:ptp_clock_unregister
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
```
**Symbols:**

```
ffffffff810cb410-ffffffff810cb45f: kthread_destroy_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void kthread_destroy_worker(struct kthread_worker *worker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cce30)
Location: kernel/kthread.c:1338
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/ptp/ptp_clock.c:ptp_clock_unregister
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
```
**Symbols:**

```
ffffffff810cce30-ffffffff810cce7f: kthread_destroy_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void kthread_destroy_worker(struct kthread_worker *worker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810e00b0)
Location: kernel/kthread.c:1338
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/ptp/ptp_clock.c:ptp_clock_unregister
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
```
**Symbols:**

```
ffffffff810e00b0-ffffffff810e00ff: kthread_destroy_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void kthread_destroy_worker(struct kthread_worker *worker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810fae30)
Location: kernel/kthread.c:1398
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/ptp/ptp_clock.c:ptp_clock_unregister
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
```
**Symbols:**

```
ffffffff810fae30-ffffffff810fae8e: kthread_destroy_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void kthread_destroy_worker(struct kthread_worker *worker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff8111dca0)
Location: kernel/kthread.c:1398
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_controller_initialize_queue
  - drivers/ptp/ptp_clock.c:ptp_clock_unregister
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
```
**Symbols:**

```
ffffffff8111dca0-ffffffff8111dcfe: kthread_destroy_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void kthread_destroy_worker(struct kthread_worker *worker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff8112ae90)
Location: kernel/kthread.c:1403
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_controller_initialize_queue
  - drivers/ptp/ptp_clock.c:ptp_clock_unregister
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
```
**Symbols:**

```
ffffffff8112ae90-ffffffff8112aeff: kthread_destroy_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void kthread_destroy_worker(struct kthread_worker *worker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff811355b0)
Location: kernel/kthread.c:1420
Inline: False
Direct callers:
  - drivers/gpu/drm/drm_vblank.c:drm_vblank_init_release
  - drivers/spi/spi.c:spi_unregister_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_controller_initialize_queue
  - drivers/ptp/ptp_clock.c:ptp_clock_unregister
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
```
**Symbols:**

```
ffffffff811355b0-ffffffff8113561f: kthread_destroy_worker (STB_GLOBAL)
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
void kthread_destroy_worker(struct kthread_worker *worker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffff8000101286b8)
Location: kernel/kthread.c:1190
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_trigger_destroy
  - drivers/ptp/ptp_clock.c:ptp_clock_unregister
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
```
**Symbols:**

```
ffff8000101286b8-ffff800010128724: kthread_destroy_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void kthread_destroy_worker(struct kthread_worker *worker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c037abdc)
Location: kernel/kthread.c:1190
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_trigger_destroy
  - drivers/ptp/ptp_clock.c:ptp_clock_unregister
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
```
**Symbols:**

```
c037abdc-c037ac60: kthread_destroy_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void kthread_destroy_worker(struct kthread_worker *worker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c000000000173360)
Location: kernel/kthread.c:1190
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_trigger_destroy
  - drivers/ptp/ptp_clock.c:ptp_clock_unregister
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
```
**Symbols:**

```
c000000000173360-c0000000001733e8: kthread_destroy_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void kthread_destroy_worker(struct kthread_worker *worker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffe0000df484)
Location: kernel/kthread.c:1190
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_trigger_destroy
  - drivers/ptp/ptp_clock.c:ptp_clock_unregister
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
```
**Symbols:**

```
ffffffe0000df484-ffffffe0000df4ea: kthread_destroy_worker (STB_GLOBAL)
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
void kthread_destroy_worker(struct kthread_worker *worker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c32a0)
Location: kernel/kthread.c:1190
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_trigger_destroy
  - drivers/ptp/ptp_clock.c:ptp_clock_unregister
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
```
**Symbols:**

```
ffffffff810c32a0-ffffffff810c32ef: kthread_destroy_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void kthread_destroy_worker(struct kthread_worker *worker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b1ae0)
Location: kernel/kthread.c:1190
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_trigger_destroy
  - drivers/ptp/ptp_clock.c:ptp_clock_unregister
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
```
**Symbols:**

```
ffffffff810b1ae0-ffffffff810b1b2f: kthread_destroy_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void kthread_destroy_worker(struct kthread_worker *worker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c27f0)
Location: kernel/kthread.c:1190
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_trigger_destroy
  - drivers/ptp/ptp_clock.c:ptp_clock_unregister
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
```
**Symbols:**

```
ffffffff810c27f0-ffffffff810c283f: kthread_destroy_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void kthread_destroy_worker(struct kthread_worker *worker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cade0)
Location: kernel/kthread.c:1190
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_trigger_destroy
  - drivers/ptp/ptp_clock.c:ptp_clock_unregister
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_exit
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_init
```
**Symbols:**

```
ffffffff810cade0-ffffffff810cae2f: kthread_destroy_worker (STB_GLOBAL)
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
