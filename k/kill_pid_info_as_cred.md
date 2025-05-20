# Function: <code>kill_pid_info_as_cred</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int kill_pid_info_as_cred(int sig, struct siginfo *info, struct pid *pid, const struct cred *cred, u32 secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8108f630)
Location: kernel/signal.c:1330
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_remove
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffff8108f630-ffffffff8108f757: kill_pid_info_as_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int kill_pid_info_as_cred(int sig, struct siginfo *info, struct pid *pid, const struct cred *cred, u32 secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810926b0)
Location: kernel/signal.c:1330
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_remove
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffff810926b0-ffffffff810927d9: kill_pid_info_as_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kill_pid_info_as_cred(int sig, struct siginfo *info, struct pid *pid, const struct cred *cred, u32 secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81097640)
Location: kernel/signal.c:1336
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_remove
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffff81097640-ffffffff81097769: kill_pid_info_as_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kill_pid_info_as_cred(int sig, struct siginfo *info, struct pid *pid, const struct cred *cred, u32 secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81094950)
Location: kernel/signal.c:1354
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_remove
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffff81094950-ffffffff81094a82: kill_pid_info_as_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kill_pid_info_as_cred(int sig, struct siginfo *info, struct pid *pid, const struct cred *cred, u32 secid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109b7f0)
Location: kernel/signal.c:1355
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_remove
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffff8109b7f0-ffffffff8109b922: kill_pid_info_as_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int kill_pid_info_as_cred(int sig, struct siginfo *info, struct pid *pid, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109f850)
Location: kernel/signal.c:1353
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_remove
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffff8109f850-ffffffff8109f97b: kill_pid_info_as_cred (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kill_pid_info_as_cred(int sig, struct kernel_siginfo *info, struct pid *pid, const struct cred *cred);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a7b00)
Location: kernel/signal.c:1438
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:usbdev_notify
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffff810a7b00-ffffffff810a7c2b: kill_pid_info_as_cred (STB_GLOBAL)
```
</details>
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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>u32 secid</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct siginfo *info</code> ➡️ <code>struct kernel_siginfo *info</code>
</li>
</ul>
</details>
</li>
</ul>
