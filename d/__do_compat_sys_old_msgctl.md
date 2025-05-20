# Function: <code>__do_compat_sys_old_msgctl</code>

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
In ipc/msg.c (ffffffff8141f2ba)
Location: ipc/msg.c:759
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_old_msgctl
  - ipc/msg.c:__ia32_compat_sys_old_msgctl
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
In ipc/msg.c (ffffffff814390da)
Location: ipc/msg.c:760
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_old_msgctl
  - ipc/msg.c:__ia32_compat_sys_old_msgctl
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
In ipc/msg.c (ffffffff8148919a)
Location: ipc/msg.c:779
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_old_msgctl
  - ipc/msg.c:__ia32_compat_sys_old_msgctl
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
In ipc/msg.c (ffffffff814a67ba)
Location: ipc/msg.c:779
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_old_msgctl
  - ipc/msg.c:__ia32_compat_sys_old_msgctl
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
In ipc/msg.c (ffffffff814ac72a)
Location: ipc/msg.c:781
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_old_msgctl
  - ipc/msg.c:__ia32_compat_sys_old_msgctl
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
In ipc/msg.c (ffffffff81504c0a)
Location: ipc/msg.c:781
Inline: True
Inline callers:
  - ipc/msg.c:__x64_compat_sys_old_msgctl
  - ipc/msg.c:__ia32_compat_sys_old_msgctl
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
In ipc/msg.c (ffffffff81595d7a)
Location: ipc/msg.c:781
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_compat_sys_old_msgctl
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
In ipc/msg.c (ffffffff8163ebba)
Location: ipc/msg.c:787
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_compat_sys_old_msgctl
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
In ipc/msg.c (ffffffff816770da)
Location: ipc/msg.c:787
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_compat_sys_old_msgctl
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
In ipc/msg.c (ffffffff816b349a)
Location: ipc/msg.c:787
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_compat_sys_old_msgctl
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
In ipc/msg.c (ffff800010520ac0)
Location: ipc/msg.c:760
Inline: True
Inline callers:
  - ipc/msg.c:__arm64_compat_sys_old_msgctl
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
In ipc/msg.c (c000000000669bd0)
Location: ipc/msg.c:760
Inline: True
Inline callers:
  - ipc/msg.c:__se_compat_sys_old_msgctl
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
In ipc/msg.c (ffffffff814316ba)
Location: ipc/msg.c:760
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_old_msgctl
  - ipc/msg.c:__ia32_compat_sys_old_msgctl
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
In ipc/msg.c (ffffffff8142213a)
Location: ipc/msg.c:760
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_old_msgctl
  - ipc/msg.c:__ia32_compat_sys_old_msgctl
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
In ipc/msg.c (ffffffff8142d85a)
Location: ipc/msg.c:760
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_old_msgctl
  - ipc/msg.c:__ia32_compat_sys_old_msgctl
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
In ipc/msg.c (ffffffff8144428a)
Location: ipc/msg.c:760
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_old_msgctl
  - ipc/msg.c:__ia32_compat_sys_old_msgctl
```
</details>
</li>
</ul>

## Differences
