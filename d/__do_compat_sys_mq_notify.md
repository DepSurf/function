# Function: <code>__do_compat_sys_mq_notify</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff813e1c35)
Location: ipc/mqueue.c:1423
Inline: True
Inline callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
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
In ipc/mqueue.c (ffffffff813fc805)
Location: ipc/mqueue.c:1423
Inline: True
Inline callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
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
In ipc/mqueue.c (ffffffff81429495)
Location: ipc/mqueue.c:1478
Inline: True
Inline callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff814431c5)
Location: ipc/mqueue.c:1473
Inline: True
Inline callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
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
In ipc/mqueue.c (ffffffff81493af5)
Location: ipc/mqueue.c:1559
Inline: True
Inline callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
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
In ipc/mqueue.c (ffffffff814b1455)
Location: ipc/mqueue.c:1559
Inline: True
Inline callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
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
In ipc/mqueue.c (ffffffff814b72d6)
Location: ipc/mqueue.c:1562
Inline: True
Inline callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
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
In ipc/mqueue.c (ffffffff8150fc16)
Location: ipc/mqueue.c:1564
Inline: True
Inline callers:
  - ipc/mqueue.c:__x64_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
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
In ipc/mqueue.c (ffffffff815a2d82)
Location: ipc/mqueue.c:1576
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
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
In ipc/mqueue.c (ffffffff8164c8c2)
Location: ipc/mqueue.c:1575
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
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
In ipc/mqueue.c (ffffffff81685022)
Location: ipc/mqueue.c:1575
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
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
In ipc/mqueue.c (ffffffff816c1442)
Location: ipc/mqueue.c:1575
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffff80001052c3c8)
Location: ipc/mqueue.c:1473
Inline: True
Inline callers:
  - ipc/mqueue.c:__arm64_compat_sys_mq_notify
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (c000000000677f94)
Location: ipc/mqueue.c:1473
Inline: True
Inline callers:
  - ipc/mqueue.c:__se_compat_sys_mq_notify
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8143b7a5)
Location: ipc/mqueue.c:1473
Inline: True
Inline callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8142c215)
Location: ipc/mqueue.c:1473
Inline: True
Inline callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff81437945)
Location: ipc/mqueue.c:1473
Inline: True
Inline callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8144f045)
Location: ipc/mqueue.c:1473
Inline: True
Inline callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_notify
  - ipc/mqueue.c:__ia32_compat_sys_mq_notify
```
</details>
</li>
</ul>

## Differences
