# Function: <code>wait_for_completion_interruptible</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int wait_for_completion_interruptible(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff81821410)
Location: kernel/sched/completion.c:188
Inline: False
Direct callers:
  - crypto/algboss.c:cryptomgr_notify
  - drivers/base/firmware_class.c:_request_firmware
```
**Symbols:**

```
ffffffff81821410-ffffffff81821620: wait_for_completion_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int wait_for_completion_interruptible(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff8189ba90)
Location: kernel/sched/completion.c:188
Inline: False
Direct callers:
  - crypto/algboss.c:cryptomgr_notify
  - crypto/drbg.c:drbg_kcapi_sym_ctr
  - drivers/base/firmware_class.c:_request_firmware
```
**Symbols:**

```
ffffffff8189ba90-ffffffff8189bca1: wait_for_completion_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int wait_for_completion_interruptible(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff818d00b0)
Location: kernel/sched/completion.c:188
Inline: False
Direct callers:
  - crypto/algboss.c:cryptomgr_notify
  - crypto/drbg.c:drbg_kcapi_sym_ctr
```
**Symbols:**

```
ffffffff818d00b0-ffffffff818d02bd: wait_for_completion_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int wait_for_completion_interruptible(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff819074a0)
Location: kernel/sched/completion.c:191
Inline: False
Direct callers:
  - crypto/algboss.c:cryptomgr_notify
```
**Symbols:**

```
ffffffff819074a0-ffffffff81907615: wait_for_completion_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int wait_for_completion_interruptible(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff81991580)
Location: kernel/sched/completion.c:205
Inline: False
Direct callers:
  - crypto/algboss.c:cryptomgr_notify
```
**Symbols:**

```
ffffffff81991580-ffffffff819916ff: wait_for_completion_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int wait_for_completion_interruptible(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff819edbb0)
Location: kernel/sched/completion.c:202
Inline: False
Direct callers:
  - crypto/algboss.c:cryptomgr_notify
```
**Symbols:**

```
ffffffff819edbb0-ffffffff819edd45: wait_for_completion_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int wait_for_completion_interruptible(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff81a28de0)
Location: kernel/sched/completion.c:202
Inline: False
Direct callers:
  - crypto/algboss.c:cryptomgr_notify
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff81a28de0-ffffffff81a28f75: wait_for_completion_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int wait_for_completion_interruptible(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff81a99510)
Location: kernel/sched/completion.c:202
Inline: False
Direct callers:
  - crypto/algboss.c:cryptomgr_notify
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff81a99510-ffffffff81a9966c: wait_for_completion_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int wait_for_completion_interruptible(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff81ad0e60)
Location: kernel/sched/completion.c:202
Inline: False
Direct callers:
  - crypto/algboss.c:cryptomgr_notify
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff81ad0e60-ffffffff81ad0fbc: wait_for_completion_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int wait_for_completion_interruptible(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff81bc9300)
Location: kernel/sched/completion.c:204
Inline: False
Direct callers:
  - fs/io_uring.c:__io_uring_register
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff81bc9300-ffffffff81bc9339: wait_for_completion_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int wait_for_completion_interruptible(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff81c42120)
Location: kernel/sched/completion.c:204
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_notify_addfd
  - fs/io_uring.c:__io_uring_register
  - fs/io_uring.c:io_sqe_files_unregister
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff81c42120-ffffffff81c42159: wait_for_completion_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int wait_for_completion_interruptible(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff81c34090)
Location: kernel/sched/completion.c:204
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_notify_addfd
  - fs/io_uring.c:__io_uring_register
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff81c34090-ffffffff81c340c9: wait_for_completion_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int wait_for_completion_interruptible(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff81d52a30)
Location: kernel/sched/completion.c:204
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_notify_addfd
  - fs/io_uring.c:__io_uring_register
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff81d52a30-ffffffff81d52a69: wait_for_completion_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int wait_for_completion_interruptible(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81f230a0)
Location: kernel/sched/completion.c:204
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_notify_addfd
  - io_uring/io_uring.c:io_rsrc_ref_quiesce
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff81f230a0-ffffffff81f230e5: wait_for_completion_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int wait_for_completion_interruptible(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff820ce2b0)
Location: kernel/sched/completion.c:204
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_notify_addfd
  - drivers/spi/spi.c:spi_transfer_wait
```
**Symbols:**

```
ffffffff820ce2b0-ffffffff820ce460: wait_for_completion_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int wait_for_completion_interruptible(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff82152540)
Location: kernel/sched/completion.c:204
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_notify_addfd
  - io_uring/io_uring.c:io_ring_exit_work
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff82152540-ffffffff821526f0: wait_for_completion_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int wait_for_completion_interruptible(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff82235760)
Location: kernel/sched/completion.c:214
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_notify_addfd
  - io_uring/io_uring.c:io_ring_exit_work
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_swap_state
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_swap_state
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_swap_state
  - drivers/spi/spi.c:spi_transfer_wait
```
**Symbols:**

```
ffffffff82235760-ffffffff82235910: wait_for_completion_interruptible (STB_GLOBAL)
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
int wait_for_completion_interruptible(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffff800010da2ab0)
Location: kernel/sched/completion.c:202
Inline: False
Direct callers:
  - crypto/algboss.c:cryptomgr_notify
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffff800010da2ab0-ffff800010da2af8: wait_for_completion_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int wait_for_completion_interruptible(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (c0e9b134)
Location: kernel/sched/completion.c:202
Inline: False
Direct callers:
  - crypto/algboss.c:cryptomgr_notify
  - drivers/spi/spi.c:spi_transfer_wait
```
**Symbols:**

```
c0e9b134-c0e9b2c4: wait_for_completion_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int wait_for_completion_interruptible(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (c000000000ee4ba0)
Location: kernel/sched/completion.c:202
Inline: False
Direct callers:
  - arch/powerpc/kernel/eeh_event.c:eeh_event_handler
  - crypto/algboss.c:cryptomgr_notify
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
c000000000ee4ba0-c000000000ee4e18: wait_for_completion_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int wait_for_completion_interruptible(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffe0008c6606)
Location: kernel/sched/completion.c:202
Inline: False
Direct callers:
  - crypto/algboss.c:cryptomgr_notify
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffe0008c6606-ffffffe0008c67c0: wait_for_completion_interruptible (STB_GLOBAL)
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
int wait_for_completion_interruptible(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff81a6fcd0)
Location: kernel/sched/completion.c:202
Inline: False
Direct callers:
  - crypto/algboss.c:cryptomgr_notify
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff81a6fcd0-ffffffff81a6fe2c: wait_for_completion_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int wait_for_completion_interruptible(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff81a2c0f0)
Location: kernel/sched/completion.c:202
Inline: False
Direct callers:
  - crypto/algboss.c:cryptomgr_notify
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff81a2c0f0-ffffffff81a2c240: wait_for_completion_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int wait_for_completion_interruptible(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff81adc0e0)
Location: kernel/sched/completion.c:202
Inline: False
Direct callers:
  - crypto/algboss.c:cryptomgr_notify
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff81adc0e0-ffffffff81adc23c: wait_for_completion_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int wait_for_completion_interruptible(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff81ae8770)
Location: kernel/sched/completion.c:202
Inline: False
Direct callers:
  - crypto/algboss.c:cryptomgr_notify
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff81ae8770-ffffffff81ae88ab: wait_for_completion_interruptible (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
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
