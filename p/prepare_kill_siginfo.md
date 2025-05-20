# Function: <code>prepare_kill_siginfo</code>

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
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810affc9)
Location: kernel/signal.c:3619
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
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
In kernel/signal.c (ffffffff810b65ce)
Location: kernel/signal.c:3624
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
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
In kernel/signal.c (ffffffff810be80b)
Location: kernel/signal.c:3642
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
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
In kernel/signal.c (ffffffff810b9b0b)
Location: kernel/signal.c:3662
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
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
In kernel/signal.c (ffffffff810bb2fb)
Location: kernel/signal.c:3684
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
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
In kernel/signal.c (ffffffff810cdc0b)
Location: kernel/signal.c:3772
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
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
In kernel/signal.c (ffffffff810e5daa)
Location: kernel/signal.c:3755
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
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
In kernel/signal.c (ffffffff81106966)
Location: kernel/signal.c:3757
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
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
In kernel/signal.c (ffffffff81112c56)
Location: kernel/signal.c:3781
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
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
In kernel/signal.c (ffffffff8111c646)
Location: kernel/signal.c:3792
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_pidfd_send_signal
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
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
In kernel/signal.c (ffff80001011295c)
Location: kernel/signal.c:3624
Inline: True
Inline callers:
  - kernel/signal.c:__arm64_sys_pidfd_send_signal
  - kernel/signal.c:__arm64_sys_kill
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
In kernel/signal.c (c03698c4)
Location: kernel/signal.c:3624
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_pidfd_send_signal
  - kernel/signal.c:__se_sys_kill
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
In kernel/signal.c (c00000000015a3b0)
Location: kernel/signal.c:3624
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_pidfd_send_signal
  - kernel/signal.c:__se_sys_kill
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000d1816)
Location: kernel/signal.c:3624
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_pidfd_send_signal
  - kernel/signal.c:__se_sys_kill
```
</details>
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
In kernel/signal.c (ffffffff810b093e)
Location: kernel/signal.c:3624
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
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
In kernel/signal.c (ffffffff8109f25e)
Location: kernel/signal.c:3624
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
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
In kernel/signal.c (ffffffff810afe9e)
Location: kernel/signal.c:3624
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
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
In kernel/signal.c (ffffffff810b816e)
Location: kernel/signal.c:3624
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_pidfd_send_signal
  - kernel/signal.c:__x64_sys_pidfd_send_signal
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
```
</details>
</li>
</ul>

## Differences
