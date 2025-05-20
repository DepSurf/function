# Function: <code>__do_compat_sys_msgsnd</code>

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
In ipc/msg.c (ffffffff813d84b6)
Location: ipc/msg.c:928
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_msgsnd
  - ipc/msg.c:__ia32_compat_sys_msgsnd
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
In ipc/msg.c (ffffffff813f3126)
Location: ipc/msg.c:938
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_msgsnd
  - ipc/msg.c:__ia32_compat_sys_msgsnd
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
In ipc/msg.c (ffffffff8141ec89)
Location: ipc/msg.c:963
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_msgsnd
  - ipc/msg.c:__ia32_compat_sys_msgsnd
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
In ipc/msg.c (ffffffff81438ad9)
Location: ipc/msg.c:964
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_msgsnd
  - ipc/msg.c:__ia32_compat_sys_msgsnd
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
In ipc/msg.c (ffffffff81488ce8)
Location: ipc/msg.c:987
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_msgsnd
  - ipc/msg.c:__ia32_compat_sys_msgsnd
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
In ipc/msg.c (ffffffff814a62d8)
Location: ipc/msg.c:987
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_msgsnd
  - ipc/msg.c:__ia32_compat_sys_msgsnd
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
In ipc/msg.c (ffffffff814ac262)
Location: ipc/msg.c:989
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_msgsnd
  - ipc/msg.c:__ia32_compat_sys_msgsnd
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
In ipc/msg.c (ffffffff815047d2)
Location: ipc/msg.c:989
Inline: True
Inline callers:
  - ipc/msg.c:__x64_compat_sys_msgsnd
  - ipc/msg.c:__ia32_compat_sys_msgsnd
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
In ipc/msg.c (ffffffff81596602)
Location: ipc/msg.c:989
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_compat_sys_msgsnd
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
In ipc/msg.c (ffffffff8163f4d2)
Location: ipc/msg.c:995
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_compat_sys_msgsnd
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
In ipc/msg.c (ffffffff81677a02)
Location: ipc/msg.c:995
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_compat_sys_msgsnd
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
In ipc/msg.c (ffffffff816b3dc2)
Location: ipc/msg.c:995
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_compat_sys_msgsnd
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
In ipc/msg.c (ffff800010521240)
Location: ipc/msg.c:964
Inline: True
Inline callers:
  - ipc/msg.c:__arm64_compat_sys_msgsnd
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
In ipc/msg.c (c00000000066a670)
Location: ipc/msg.c:964
Inline: True
Inline callers:
  - ipc/msg.c:__se_compat_sys_msgsnd
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
In ipc/msg.c (ffffffff814310b9)
Location: ipc/msg.c:964
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_msgsnd
  - ipc/msg.c:__ia32_compat_sys_msgsnd
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
In ipc/msg.c (ffffffff81421b39)
Location: ipc/msg.c:964
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_msgsnd
  - ipc/msg.c:__ia32_compat_sys_msgsnd
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
In ipc/msg.c (ffffffff8142d259)
Location: ipc/msg.c:964
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_msgsnd
  - ipc/msg.c:__ia32_compat_sys_msgsnd
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
In ipc/msg.c (ffffffff81445109)
Location: ipc/msg.c:964
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_msgsnd
  - ipc/msg.c:__ia32_compat_sys_msgsnd
```
</details>
</li>
</ul>

## Differences
