# Function: <code>__do_compat_sys_mq_open</code>

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
In ipc/mqueue.c (ffffffff813e0da4)
Location: ipc/mqueue.c:1410
Inline: True
Inline callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_open
  - ipc/mqueue.c:__ia32_compat_sys_mq_open
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
In ipc/mqueue.c (ffffffff813fb594)
Location: ipc/mqueue.c:1410
Inline: True
Inline callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_open
  - ipc/mqueue.c:__ia32_compat_sys_mq_open
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
In ipc/mqueue.c (ffffffff81427904)
Location: ipc/mqueue.c:1465
Inline: True
Inline callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_open
  - ipc/mqueue.c:__ia32_compat_sys_mq_open
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
In ipc/mqueue.c (ffffffff81441634)
Location: ipc/mqueue.c:1460
Inline: True
Inline callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_open
  - ipc/mqueue.c:__ia32_compat_sys_mq_open
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
In ipc/mqueue.c (ffffffff81492284)
Location: ipc/mqueue.c:1546
Inline: True
Inline callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_open
  - ipc/mqueue.c:__ia32_compat_sys_mq_open
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
In ipc/mqueue.c (ffffffff814afad4)
Location: ipc/mqueue.c:1546
Inline: True
Inline callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_open
  - ipc/mqueue.c:__ia32_compat_sys_mq_open
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
In ipc/mqueue.c (ffffffff814b5915)
Location: ipc/mqueue.c:1549
Inline: True
Inline callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_open
  - ipc/mqueue.c:__ia32_compat_sys_mq_open
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
In ipc/mqueue.c (ffffffff8150e005)
Location: ipc/mqueue.c:1551
Inline: True
Inline callers:
  - ipc/mqueue.c:__x64_compat_sys_mq_open
  - ipc/mqueue.c:__ia32_compat_sys_mq_open
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
In ipc/mqueue.c (ffffffff815a06fc)
Location: ipc/mqueue.c:1563
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_compat_sys_mq_open
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
In ipc/mqueue.c (ffffffff8164a07c)
Location: ipc/mqueue.c:1562
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_compat_sys_mq_open
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
In ipc/mqueue.c (ffffffff816825ca)
Location: ipc/mqueue.c:1562
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_compat_sys_mq_open
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
In ipc/mqueue.c (ffffffff816be9ca)
Location: ipc/mqueue.c:1562
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_compat_sys_mq_open
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
In ipc/mqueue.c (ffff80001052a008)
Location: ipc/mqueue.c:1460
Inline: True
Inline callers:
  - ipc/mqueue.c:__arm64_compat_sys_mq_open
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
In ipc/mqueue.c (c000000000676250)
Location: ipc/mqueue.c:1460
Inline: True
Inline callers:
  - ipc/mqueue.c:__se_compat_sys_mq_open
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
In ipc/mqueue.c (ffffffff81439c14)
Location: ipc/mqueue.c:1460
Inline: True
Inline callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_open
  - ipc/mqueue.c:__ia32_compat_sys_mq_open
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
In ipc/mqueue.c (ffffffff8142a684)
Location: ipc/mqueue.c:1460
Inline: True
Inline callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_open
  - ipc/mqueue.c:__ia32_compat_sys_mq_open
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
In ipc/mqueue.c (ffffffff81435db4)
Location: ipc/mqueue.c:1460
Inline: True
Inline callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_open
  - ipc/mqueue.c:__ia32_compat_sys_mq_open
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
In ipc/mqueue.c (ffffffff8144e884)
Location: ipc/mqueue.c:1460
Inline: True
Inline callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_open
  - ipc/mqueue.c:__ia32_compat_sys_mq_open
```
</details>
</li>
</ul>

## Differences
