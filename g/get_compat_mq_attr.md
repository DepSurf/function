# Function: <code>get_compat_mq_attr</code>

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
In ipc/compat_mq.c (ffffffff8132e513)
Location: ipc/compat_mq.c:25
Inline: True
Inline callers:
  - ipc/compat_mq.c:compat_SyS_mq_open
  - ipc/compat_mq.c:compat_SyS_mq_getsetattr
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/compat_mq.c (ffffffff81363445)
Location: ipc/compat_mq.c:25
Inline: True
Inline callers:
  - ipc/compat_mq.c:compat_SyS_mq_getsetattr
  - ipc/compat_mq.c:compat_SyS_mq_open
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/compat_mq.c (ffffffff81379c15)
Location: ipc/compat_mq.c:25
Inline: True
Inline callers:
  - ipc/compat_mq.c:compat_SyS_mq_getsetattr
  - ipc/compat_mq.c:compat_SyS_mq_open
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8138ceac)
Location: ipc/mqueue.c:1433
Inline: True
Inline callers:
  - ipc/mqueue.c:C_SYSC_mq_getsetattr
  - ipc/mqueue.c:compat_SyS_mq_open
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
In ipc/mqueue.c (ffffffff813b225c)
Location: ipc/mqueue.c:1433
Inline: True
Inline callers:
  - ipc/mqueue.c:C_SYSC_mq_getsetattr
  - ipc/mqueue.c:compat_SyS_mq_open
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
In ipc/mqueue.c (ffffffff813e14dc)
Location: ipc/mqueue.c:1379
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_compat_sys_mq_getsetattr
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
In ipc/mqueue.c (ffffffff813fc0b8)
Location: ipc/mqueue.c:1379
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_compat_sys_mq_getsetattr
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
In ipc/mqueue.c (ffffffff81428389)
Location: ipc/mqueue.c:1434
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_compat_sys_mq_getsetattr
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
In ipc/mqueue.c (ffffffff814420b9)
Location: ipc/mqueue.c:1429
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_compat_sys_mq_getsetattr
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
In ipc/mqueue.c (ffffffff81492c99)
Location: ipc/mqueue.c:1515
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_compat_sys_mq_getsetattr
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
In ipc/mqueue.c (ffffffff814b0599)
Location: ipc/mqueue.c:1515
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_compat_sys_mq_getsetattr
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
In ipc/mqueue.c (ffffffff814b63e9)
Location: ipc/mqueue.c:1518
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_compat_sys_mq_getsetattr
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
In ipc/mqueue.c (ffffffff8150ed29)
Location: ipc/mqueue.c:1520
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_compat_sys_mq_getsetattr
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
In ipc/mqueue.c (ffffffff815a0d51)
Location: ipc/mqueue.c:1532
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_compat_sys_mq_getsetattr
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
In ipc/mqueue.c (ffffffff8164a721)
Location: ipc/mqueue.c:1531
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_compat_sys_mq_getsetattr
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
In ipc/mqueue.c (ffffffff81683171)
Location: ipc/mqueue.c:1531
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_compat_sys_mq_getsetattr
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
In ipc/mqueue.c (ffffffff816bf571)
Location: ipc/mqueue.c:1531
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_compat_sys_mq_getsetattr
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
In ipc/mqueue.c (ffff80001052aca4)
Location: ipc/mqueue.c:1429
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_compat_sys_mq_getsetattr
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
In ipc/mqueue.c (c0000000006776b8)
Location: ipc/mqueue.c:1429
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_compat_sys_mq_getsetattr
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
In ipc/mqueue.c (ffffffff8143a699)
Location: ipc/mqueue.c:1429
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_compat_sys_mq_getsetattr
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
In ipc/mqueue.c (ffffffff8142b109)
Location: ipc/mqueue.c:1429
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_compat_sys_mq_getsetattr
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
In ipc/mqueue.c (ffffffff81436839)
Location: ipc/mqueue.c:1429
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_compat_sys_mq_getsetattr
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
In ipc/mqueue.c (ffffffff8144e6f9)
Location: ipc/mqueue.c:1429
Inline: True
Inline callers:
  - ipc/mqueue.c:__do_compat_sys_mq_getsetattr
  - ipc/mqueue.c:__x32_compat_sys_mq_open
  - ipc/mqueue.c:__ia32_compat_sys_mq_open
```
</details>
</li>
</ul>

## Differences
