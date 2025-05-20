# Function: <code>compat_prepare_timeout</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8138d7d4)
Location: ipc/mqueue.c:1477
Inline: True
Inline callers:
  - ipc/mqueue.c:compat_SyS_mq_timedreceive
  - ipc/mqueue.c:compat_SyS_mq_timedsend
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
In ipc/mqueue.c (ffffffff813b2bf4)
Location: ipc/mqueue.c:1477
Inline: True
Inline callers:
  - ipc/mqueue.c:compat_SyS_mq_timedreceive
  - ipc/mqueue.c:compat_SyS_mq_timedsend
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
In ipc/mqueue.c (ffffffff813e2bbc)
Location: ipc/mqueue.c:1464
Inline: True
Inline callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_timedreceive
  - ipc/mqueue.c:__ia32_compat_sys_mq_timedreceive
  - ipc/mqueue.c:__x32_compat_sys_mq_timedsend
  - ipc/mqueue.c:__ia32_compat_sys_mq_timedsend
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
In ipc/mqueue.c (ffffffff813fd60c)
Location: ipc/mqueue.c:1464
Inline: True
Inline callers:
  - ipc/mqueue.c:__x32_compat_sys_mq_timedreceive
  - ipc/mqueue.c:__ia32_compat_sys_mq_timedreceive
  - ipc/mqueue.c:__x32_compat_sys_mq_timedsend
  - ipc/mqueue.c:__ia32_compat_sys_mq_timedsend
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
In ipc/mqueue.c (ffffffff81429acb)
Location: ipc/mqueue.c:1519
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__x64_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedsend_time32
  - ipc/mqueue.c:__x64_sys_mq_timedsend_time32
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
In ipc/mqueue.c (ffffffff814437fb)
Location: ipc/mqueue.c:1514
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__x64_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedsend_time32
  - ipc/mqueue.c:__x64_sys_mq_timedsend_time32
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
In ipc/mqueue.c (ffffffff814944cb)
Location: ipc/mqueue.c:1600
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__x64_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedsend_time32
  - ipc/mqueue.c:__x64_sys_mq_timedsend_time32
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
In ipc/mqueue.c (ffffffff814b1e2b)
Location: ipc/mqueue.c:1600
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__x64_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedsend_time32
  - ipc/mqueue.c:__x64_sys_mq_timedsend_time32
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
In ipc/mqueue.c (ffffffff814b7cab)
Location: ipc/mqueue.c:1603
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__x64_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedsend_time32
  - ipc/mqueue.c:__x64_sys_mq_timedsend_time32
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
In ipc/mqueue.c (ffffffff815104bb)
Location: ipc/mqueue.c:1605
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__x64_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedsend_time32
  - ipc/mqueue.c:__x64_sys_mq_timedsend_time32
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
In ipc/mqueue.c (ffffffff815a25eb)
Location: ipc/mqueue.c:1617
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__x64_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedsend_time32
  - ipc/mqueue.c:__x64_sys_mq_timedsend_time32
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
In ipc/mqueue.c (ffffffff8164c0db)
Location: ipc/mqueue.c:1616
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__x64_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedsend_time32
  - ipc/mqueue.c:__x64_sys_mq_timedsend_time32
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
In ipc/mqueue.c (ffffffff8168481b)
Location: ipc/mqueue.c:1616
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__x64_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedsend_time32
  - ipc/mqueue.c:__x64_sys_mq_timedsend_time32
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
In ipc/mqueue.c (ffffffff816c0c5b)
Location: ipc/mqueue.c:1616
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__x64_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedsend_time32
  - ipc/mqueue.c:__x64_sys_mq_timedsend_time32
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
In ipc/mqueue.c (ffff80001052b604)
Location: ipc/mqueue.c:1514
Inline: True
Inline callers:
  - ipc/mqueue.c:__arm64_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__arm64_sys_mq_timedsend_time32
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (c06e51cc)
Location: ipc/mqueue.c:1514
Inline: True
Inline callers:
  - ipc/mqueue.c:__se_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__se_sys_mq_timedsend_time32
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (c000000000676f20)
Location: ipc/mqueue.c:1514
Inline: True
Inline callers:
  - ipc/mqueue.c:__se_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__se_sys_mq_timedsend_time32
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
In ipc/mqueue.c (ffffffff8143bddb)
Location: ipc/mqueue.c:1514
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__x64_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedsend_time32
  - ipc/mqueue.c:__x64_sys_mq_timedsend_time32
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
In ipc/mqueue.c (ffffffff8142c84b)
Location: ipc/mqueue.c:1514
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__x64_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedsend_time32
  - ipc/mqueue.c:__x64_sys_mq_timedsend_time32
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
In ipc/mqueue.c (ffffffff81437f7b)
Location: ipc/mqueue.c:1514
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__x64_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedsend_time32
  - ipc/mqueue.c:__x64_sys_mq_timedsend_time32
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
In ipc/mqueue.c (ffffffff8144e4fb)
Location: ipc/mqueue.c:1514
Inline: True
Inline callers:
  - ipc/mqueue.c:__ia32_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__x64_sys_mq_timedreceive_time32
  - ipc/mqueue.c:__ia32_sys_mq_timedsend_time32
  - ipc/mqueue.c:__x64_sys_mq_timedsend_time32
```
</details>
</li>
</ul>

## Differences
