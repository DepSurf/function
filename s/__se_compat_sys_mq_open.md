# Function: <code>__se_compat_sys_mq_open</code>

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
In ipc/mqueue.c (ffffffff813e0d9c)
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
In ipc/mqueue.c (ffffffff813fb58c)
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
In ipc/mqueue.c (ffffffff814278fc)
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
In ipc/mqueue.c (ffffffff8144162c)
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
In ipc/mqueue.c (ffffffff8149227c)
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
In ipc/mqueue.c (ffffffff814afacc)
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
In ipc/mqueue.c (ffffffff814b590d)
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
In ipc/mqueue.c (ffffffff8150dffd)
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
In ipc/mqueue.c (ffffffff815a06f3)
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
In ipc/mqueue.c (ffffffff8164a073)
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
In ipc/mqueue.c (ffffffff816825c3)
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
In ipc/mqueue.c (ffffffff816be9c3)
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
In ipc/mqueue.c (ffff80001052a004)
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
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __se_compat_sys_mq_open(long int u_name, long int oflag, long int mode, long int u_attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (c000000000676210)
Location: ipc/mqueue.c:1460
Inline: False
```
**Symbols:**

```
c000000000676210-c000000000676328: __se_compat_sys_mq_open (STB_GLOBAL)
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
In ipc/mqueue.c (ffffffff81439c0c)
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
In ipc/mqueue.c (ffffffff8142a67c)
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
In ipc/mqueue.c (ffffffff81435dac)
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
In ipc/mqueue.c (ffffffff8144e87c)
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
<b>Arch</b>
<ul>
</ul>
