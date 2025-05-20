# Function: <code>__se_compat_sys_old_shmctl</code>

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
In ipc/shm.c (ffffffff81425ff5)
Location: ipc/shm.c:1404
Inline: True
Inline callers:
  - ipc/shm.c:__x32_compat_sys_old_shmctl
  - ipc/shm.c:__ia32_compat_sys_old_shmctl
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
In ipc/shm.c (ffffffff8143fd45)
Location: ipc/shm.c:1404
Inline: True
Inline callers:
  - ipc/shm.c:__x32_compat_sys_old_shmctl
  - ipc/shm.c:__ia32_compat_sys_old_shmctl
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
In ipc/shm.c (ffffffff814903b5)
Location: ipc/shm.c:1404
Inline: True
Inline callers:
  - ipc/shm.c:__x32_compat_sys_old_shmctl
  - ipc/shm.c:__ia32_compat_sys_old_shmctl
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
In ipc/shm.c (ffffffff814adad5)
Location: ipc/shm.c:1402
Inline: True
Inline callers:
  - ipc/shm.c:__x32_compat_sys_old_shmctl
  - ipc/shm.c:__ia32_compat_sys_old_shmctl
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
In ipc/shm.c (ffffffff814b3925)
Location: ipc/shm.c:1402
Inline: True
Inline callers:
  - ipc/shm.c:__x32_compat_sys_old_shmctl
  - ipc/shm.c:__ia32_compat_sys_old_shmctl
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
In ipc/shm.c (ffffffff8150bf95)
Location: ipc/shm.c:1498
Inline: True
Inline callers:
  - ipc/shm.c:__x64_compat_sys_old_shmctl
  - ipc/shm.c:__ia32_compat_sys_old_shmctl
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
In ipc/shm.c (ffffffff8159e085)
Location: ipc/shm.c:1492
Inline: True
Inline callers:
  - ipc/shm.c:__ia32_compat_sys_old_shmctl
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
In ipc/shm.c (ffffffff81647695)
Location: ipc/shm.c:1508
Inline: True
Inline callers:
  - ipc/shm.c:__ia32_compat_sys_old_shmctl
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
In ipc/shm.c (ffffffff8167fbc5)
Location: ipc/shm.c:1508
Inline: True
Inline callers:
  - ipc/shm.c:__ia32_compat_sys_old_shmctl
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
In ipc/shm.c (ffffffff816bbfb5)
Location: ipc/shm.c:1504
Inline: True
Inline callers:
  - ipc/shm.c:__ia32_compat_sys_old_shmctl
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
In ipc/shm.c (ffff8000105284c8)
Location: ipc/shm.c:1404
Inline: True
Inline callers:
  - ipc/shm.c:__arm64_compat_sys_old_shmctl
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
long int __se_compat_sys_old_shmctl(long int shmid, long int cmd, long int uptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (c000000000672f20)
Location: ipc/shm.c:1404
Inline: False
```
**Symbols:**

```
c000000000672f20-c000000000672f48: __se_compat_sys_old_shmctl (STB_GLOBAL)
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
In ipc/shm.c (ffffffff81438325)
Location: ipc/shm.c:1404
Inline: True
Inline callers:
  - ipc/shm.c:__x32_compat_sys_old_shmctl
  - ipc/shm.c:__ia32_compat_sys_old_shmctl
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
In ipc/shm.c (ffffffff81428d95)
Location: ipc/shm.c:1404
Inline: True
Inline callers:
  - ipc/shm.c:__x32_compat_sys_old_shmctl
  - ipc/shm.c:__ia32_compat_sys_old_shmctl
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
In ipc/shm.c (ffffffff814344c5)
Location: ipc/shm.c:1404
Inline: True
Inline callers:
  - ipc/shm.c:__x32_compat_sys_old_shmctl
  - ipc/shm.c:__ia32_compat_sys_old_shmctl
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
In ipc/shm.c (ffffffff8144b5d5)
Location: ipc/shm.c:1404
Inline: True
Inline callers:
  - ipc/shm.c:__x32_compat_sys_old_shmctl
  - ipc/shm.c:__ia32_compat_sys_old_shmctl
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
