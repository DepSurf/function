# Function: <code>__se_compat_sys_msgctl</code>

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
In ipc/msg.c (ffffffff813d9145)
Location: ipc/msg.c:725
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_msgctl
  - ipc/msg.c:__ia32_compat_sys_msgctl
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
In ipc/msg.c (ffffffff813f3785)
Location: ipc/msg.c:735
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_msgctl
  - ipc/msg.c:__ia32_compat_sys_msgctl
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
In ipc/msg.c (ffffffff8141f255)
Location: ipc/msg.c:746
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_msgctl
  - ipc/msg.c:__ia32_compat_sys_msgctl
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
In ipc/msg.c (ffffffff81439075)
Location: ipc/msg.c:747
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_msgctl
  - ipc/msg.c:__ia32_compat_sys_msgctl
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
In ipc/msg.c (ffffffff81489135)
Location: ipc/msg.c:766
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_msgctl
  - ipc/msg.c:__ia32_compat_sys_msgctl
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
In ipc/msg.c (ffffffff814a6755)
Location: ipc/msg.c:766
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_msgctl
  - ipc/msg.c:__ia32_compat_sys_msgctl
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
In ipc/msg.c (ffffffff814ac6d5)
Location: ipc/msg.c:768
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_msgctl
  - ipc/msg.c:__ia32_compat_sys_msgctl
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
In ipc/msg.c (ffffffff81504bb5)
Location: ipc/msg.c:768
Inline: True
Inline callers:
  - ipc/msg.c:__x64_compat_sys_msgctl
  - ipc/msg.c:__ia32_compat_sys_msgctl
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
In ipc/msg.c (ffffffff81595d45)
Location: ipc/msg.c:768
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_compat_sys_msgctl
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
In ipc/msg.c (ffffffff8163eb75)
Location: ipc/msg.c:774
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_compat_sys_msgctl
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
In ipc/msg.c (ffffffff81677095)
Location: ipc/msg.c:774
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_compat_sys_msgctl
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
In ipc/msg.c (ffffffff816b3455)
Location: ipc/msg.c:774
Inline: True
Inline callers:
  - ipc/msg.c:__ia32_compat_sys_msgctl
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
In ipc/msg.c (ffff800010520a88)
Location: ipc/msg.c:747
Inline: True
Inline callers:
  - ipc/msg.c:__arm64_compat_sys_msgctl
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
long int __se_compat_sys_msgctl(long int msqid, long int cmd, long int uptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/msg.c (c000000000669ba0)
Location: ipc/msg.c:747
Inline: False
```
**Symbols:**

```
c000000000669ba0-c000000000669bc0: __se_compat_sys_msgctl (STB_GLOBAL)
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
In ipc/msg.c (ffffffff81431655)
Location: ipc/msg.c:747
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_msgctl
  - ipc/msg.c:__ia32_compat_sys_msgctl
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
In ipc/msg.c (ffffffff814220d5)
Location: ipc/msg.c:747
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_msgctl
  - ipc/msg.c:__ia32_compat_sys_msgctl
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
In ipc/msg.c (ffffffff8142d7f5)
Location: ipc/msg.c:747
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_msgctl
  - ipc/msg.c:__ia32_compat_sys_msgctl
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
In ipc/msg.c (ffffffff81444225)
Location: ipc/msg.c:747
Inline: True
Inline callers:
  - ipc/msg.c:__x32_compat_sys_msgctl
  - ipc/msg.c:__ia32_compat_sys_msgctl
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
