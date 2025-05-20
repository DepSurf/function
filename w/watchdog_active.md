# Function: <code>watchdog_active</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff8168aeab)
Location: include/linux/watchdog.h:107
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_stop
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_core.c (ffffffff816eb7a2)
Location: include/linux/watchdog.h:120
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_core.c:watchdog_reboot_notifier
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff816ec4b7)
Location: include/linux/watchdog.h:120
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
  - drivers/watchdog/watchdog_dev.c:watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_core.c (ffffffff8171c6c2)
Location: include/linux/watchdog.h:127
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_core.c:watchdog_reboot_notifier
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8171d4aa)
Location: include/linux/watchdog.h:127
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
  - drivers/watchdog/watchdog_dev.c:watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_core.c (ffffffff81734952)
Location: include/linux/watchdog.h:128
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_core.c:watchdog_reboot_notifier
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81735791)
Location: include/linux/watchdog.h:128
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
  - drivers/watchdog/watchdog_dev.c:watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff817a6b92)
Location: include/linux/watchdog.h:129
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_reboot_notifier
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
  - drivers/watchdog/watchdog_dev.c:watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff817ee612)
Location: include/linux/watchdog.h:129
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_reboot_notifier
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
  - drivers/watchdog/watchdog_dev.c:watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff8181a4e2)
Location: include/linux/watchdog.h:126
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_reboot_notifier
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
  - drivers/watchdog/watchdog_dev.c:watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_dev.c (ffffffff8185c6c2)
Location: include/linux/watchdog.h:126
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_reboot_notifier
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
  - drivers/watchdog/watchdog_dev.c:watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_core.c (ffffffff8188dc62)
Location: include/linux/watchdog.h:126
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_core.c:watchdog_reboot_notifier
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8188edb2)
Location: include/linux/watchdog.h:126
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
  - drivers/watchdog/watchdog_dev.c:watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_core.c (ffffffff8195c812)
Location: include/linux/watchdog.h:126
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_core.c:watchdog_reboot_notifier
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8195da4e)
Location: include/linux/watchdog.h:126
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
  - drivers/watchdog/watchdog_dev.c:watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_core.c (ffffffff819632d2)
Location: include/linux/watchdog.h:126
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_core.c:watchdog_reboot_notifier
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8196444e)
Location: include/linux/watchdog.h:126
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
  - drivers/watchdog/watchdog_dev.c:watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_core.c (ffffffff819476f2)
Location: include/linux/watchdog.h:126
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_core.c:watchdog_reboot_notifier
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8194886e)
Location: include/linux/watchdog.h:126
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
  - drivers/watchdog/watchdog_dev.c:watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_core.c (ffffffff819ec592)
Location: include/linux/watchdog.h:128
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_core.c:watchdog_reboot_notifier
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff819ed86e)
Location: include/linux/watchdog.h:128
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_worker_should_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_core.c (ffffffff81b52c6c)
Location: include/linux/watchdog.h:128
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_core.c:watchdog_reboot_notifier
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81b5418f)
Location: include/linux/watchdog.h:128
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_stop
  - drivers/watchdog/watchdog_dev.c:watchdog_stop
  - drivers/watchdog/watchdog_dev.c:watchdog_stop
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_worker_should_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_core.c (ffffffff81ceb30c)
Location: include/linux/watchdog.h:128
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_core.c:watchdog_reboot_notifier
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81cec5ff)
Location: include/linux/watchdog.h:128
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_stop
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_worker_should_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_update_worker
  - drivers/watchdog/watchdog_dev.c:watchdog_update_worker
  - drivers/watchdog/watchdog_dev.c:watchdog_update_worker
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
In drivers/watchdog/watchdog_dev.c (ffffffff81d5531f)
Location: include/linux/watchdog.h:128
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_stop
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_worker_should_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_update_worker
  - drivers/watchdog/watchdog_dev.c:watchdog_update_worker
  - drivers/watchdog/watchdog_dev.c:watchdog_update_worker
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
In drivers/watchdog/watchdog_dev.c (ffffffff81e0c1ef)
Location: include/linux/watchdog.h:128
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_stop
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_worker_should_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_update_worker
  - drivers/watchdog/watchdog_dev.c:watchdog_update_worker
  - drivers/watchdog/watchdog_dev.c:watchdog_update_worker
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_core.c (ffff800010ade5d8)
Location: include/linux/watchdog.h:126
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_core.c:watchdog_reboot_notifier
```
```
In drivers/watchdog/watchdog_dev.c (ffff800010adfcbc)
Location: include/linux/watchdog.h:126
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
  - drivers/watchdog/watchdog_dev.c:watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_core.c (c0bc01a0)
Location: include/linux/watchdog.h:126
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_core.c:watchdog_reboot_notifier
```
```
In drivers/watchdog/watchdog_dev.c (c0bc1634)
Location: include/linux/watchdog.h:126
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
  - drivers/watchdog/watchdog_dev.c:watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
```
```
In drivers/watchdog/npcm_wdt.c (c0bc26a8)
Location: include/linux/watchdog.h:126
Inline: True
Inline callers:
  - drivers/watchdog/npcm_wdt.c:npcm_wdt_set_timeout
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_core.c (c000000000bc5ef0)
Location: include/linux/watchdog.h:126
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_core.c:watchdog_reboot_notifier
```
```
In drivers/watchdog/watchdog_dev.c (c000000000bc7b88)
Location: include/linux/watchdog.h:126
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
  - drivers/watchdog/watchdog_dev.c:watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_core.c (ffffffe0006d6794)
Location: include/linux/watchdog.h:126
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_core.c:watchdog_reboot_notifier
```
```
In drivers/watchdog/watchdog_dev.c (ffffffe0006d77c6)
Location: include/linux/watchdog.h:126
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
  - drivers/watchdog/watchdog_dev.c:watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_core.c (ffffffff81833ae2)
Location: include/linux/watchdog.h:126
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_core.c:watchdog_reboot_notifier
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81834c32)
Location: include/linux/watchdog.h:126
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
  - drivers/watchdog/watchdog_dev.c:watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_core.c (ffffffff817fb172)
Location: include/linux/watchdog.h:126
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_core.c:watchdog_reboot_notifier
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff817fc2c2)
Location: include/linux/watchdog.h:126
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
  - drivers/watchdog/watchdog_dev.c:watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_core.c (ffffffff81883112)
Location: include/linux/watchdog.h:126
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_core.c:watchdog_reboot_notifier
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81884262)
Location: include/linux/watchdog.h:126
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
  - drivers/watchdog/watchdog_dev.c:watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/watchdog/watchdog_core.c (ffffffff8189ebd2)
Location: include/linux/watchdog.h:126
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_core.c:watchdog_reboot_notifier
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff8189fd22)
Location: include/linux/watchdog.h:126
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_release
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_ioctl
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_start
  - drivers/watchdog/watchdog_dev.c:watchdog_ping_work
  - drivers/watchdog/watchdog_dev.c:watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:__watchdog_ping
  - drivers/watchdog/watchdog_dev.c:watchdog_next_keepalive
```
</details>
</li>
</ul>

## Differences
