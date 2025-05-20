# Function: <code>kill_pid_usb_asyncio</code>

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
int kill_pid_usb_asyncio(int sig, int errno, sigval_t addr, struct pid *pid, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aba10)
Location: kernel/signal.c:1500
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_notify
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffff810aba10-ffffffff810abb40: kill_pid_usb_asyncio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int kill_pid_usb_asyncio(int sig, int errno, sigval_t addr, struct pid *pid, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b2020)
Location: kernel/signal.c:1505
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_notify
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffff810b2020-ffffffff810b2150: kill_pid_usb_asyncio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kill_pid_usb_asyncio(int sig, int errno, sigval_t addr, struct pid *pid, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ba510)
Location: kernel/signal.c:1505
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_remove
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffff810ba510-ffffffff810ba680: kill_pid_usb_asyncio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kill_pid_usb_asyncio(int sig, int errno, sigval_t addr, struct pid *pid, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b57b0)
Location: kernel/signal.c:1506
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_remove
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffff810b57b0-ffffffff810b593e: kill_pid_usb_asyncio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kill_pid_usb_asyncio(int sig, int errno, sigval_t addr, struct pid *pid, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b73b0)
Location: kernel/signal.c:1508
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_notify
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffff810b73b0-ffffffff810b753e: kill_pid_usb_asyncio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kill_pid_usb_asyncio(int sig, int errno, sigval_t addr, struct pid *pid, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810c8a70)
Location: kernel/signal.c:1534
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_notify
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffff810c8a70-ffffffff810c8bfe: kill_pid_usb_asyncio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kill_pid_usb_asyncio(int sig, int errno, sigval_t addr, struct pid *pid, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810e0ed0)
Location: kernel/signal.c:1535
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_notify
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffff810e0ed0-ffffffff810e1085: kill_pid_usb_asyncio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kill_pid_usb_asyncio(int sig, int errno, sigval_t addr, struct pid *pid, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff811010c0)
Location: kernel/signal.c:1536
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_notify
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffff811010c0-ffffffff81101275: kill_pid_usb_asyncio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kill_pid_usb_asyncio(int sig, int errno, sigval_t addr, struct pid *pid, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8110d220)
Location: kernel/signal.c:1542
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_notify
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffff8110d220-ffffffff8110d3dd: kill_pid_usb_asyncio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kill_pid_usb_asyncio(int sig, int errno, sigval_t addr, struct pid *pid, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81116c00)
Location: kernel/signal.c:1548
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_notify
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffff81116c00-ffffffff81116dbd: kill_pid_usb_asyncio (STB_GLOBAL)
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
int kill_pid_usb_asyncio(int sig, int errno, sigval_t addr, struct pid *pid, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff80001010dc98)
Location: kernel/signal.c:1505
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_notify
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffff80001010dc98-ffff80001010ddf0: kill_pid_usb_asyncio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kill_pid_usb_asyncio(int sig, int errno, sigval_t addr, struct pid *pid, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0366014)
Location: kernel/signal.c:1505
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_notify
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
c0366014-c0366158: kill_pid_usb_asyncio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kill_pid_usb_asyncio(int sig, int errno, sigval_t addr, struct pid *pid, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000155070)
Location: kernel/signal.c:1505
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_notify
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
c000000000155070-c0000000001551fc: kill_pid_usb_asyncio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int kill_pid_usb_asyncio(int sig, int errno, sigval_t addr, struct pid *pid, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000ced70)
Location: kernel/signal.c:1505
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_notify
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffe0000ced70-ffffffe0000cee5e: kill_pid_usb_asyncio (STB_GLOBAL)
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
int kill_pid_usb_asyncio(int sig, int errno, sigval_t addr, struct pid *pid, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ac390)
Location: kernel/signal.c:1505
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_notify
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffff810ac390-ffffffff810ac4c0: kill_pid_usb_asyncio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int kill_pid_usb_asyncio(int sig, int errno, sigval_t addr, struct pid *pid, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109ad20)
Location: kernel/signal.c:1505
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_notify
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffff8109ad20-ffffffff8109ae50: kill_pid_usb_asyncio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int kill_pid_usb_asyncio(int sig, int errno, sigval_t addr, struct pid *pid, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ab8f0)
Location: kernel/signal.c:1505
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_notify
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffff810ab8f0-ffffffff810aba20: kill_pid_usb_asyncio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int kill_pid_usb_asyncio(int sig, int errno, sigval_t addr, struct pid *pid, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b3a20)
Location: kernel/signal.c:1505
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_notify
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffff810b3a20-ffffffff810b3b71: kill_pid_usb_asyncio (STB_GLOBAL)
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
