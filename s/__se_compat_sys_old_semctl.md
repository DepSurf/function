# Function: <code>__se_compat_sys_old_semctl</code>

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
In ipc/sem.c (ffffffff81423655)
Location: ipc/sem.c:1814
Inline: True
Inline callers:
  - ipc/sem.c:__x32_compat_sys_old_semctl
  - ipc/sem.c:__ia32_compat_sys_old_semctl
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
In ipc/sem.c (ffffffff8143d395)
Location: ipc/sem.c:1814
Inline: True
Inline callers:
  - ipc/sem.c:__x32_compat_sys_old_semctl
  - ipc/sem.c:__ia32_compat_sys_old_semctl
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
In ipc/sem.c (ffffffff8148df65)
Location: ipc/sem.c:1830
Inline: True
Inline callers:
  - ipc/sem.c:__x32_compat_sys_old_semctl
  - ipc/sem.c:__ia32_compat_sys_old_semctl
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
In ipc/sem.c (ffffffff814ab6a5)
Location: ipc/sem.c:1829
Inline: True
Inline callers:
  - ipc/sem.c:__x32_compat_sys_old_semctl
  - ipc/sem.c:__ia32_compat_sys_old_semctl
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
In ipc/sem.c (ffffffff814b0645)
Location: ipc/sem.c:1831
Inline: True
Inline callers:
  - ipc/sem.c:__x32_compat_sys_old_semctl
  - ipc/sem.c:__ia32_compat_sys_old_semctl
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
In ipc/sem.c (ffffffff81508715)
Location: ipc/sem.c:1834
Inline: True
Inline callers:
  - ipc/sem.c:__x64_compat_sys_old_semctl
  - ipc/sem.c:__ia32_compat_sys_old_semctl
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
In ipc/sem.c (ffffffff8159a705)
Location: ipc/sem.c:1832
Inline: True
Inline callers:
  - ipc/sem.c:__ia32_compat_sys_old_semctl
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
In ipc/sem.c (ffffffff816439d5)
Location: ipc/sem.c:1832
Inline: True
Inline callers:
  - ipc/sem.c:__ia32_compat_sys_old_semctl
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
In ipc/sem.c (ffffffff8167bf25)
Location: ipc/sem.c:1832
Inline: True
Inline callers:
  - ipc/sem.c:__ia32_compat_sys_old_semctl
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
In ipc/sem.c (ffffffff816b82f5)
Location: ipc/sem.c:1832
Inline: True
Inline callers:
  - ipc/sem.c:__ia32_compat_sys_old_semctl
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
In ipc/sem.c (ffff8000105251d0)
Location: ipc/sem.c:1814
Inline: True
Inline callers:
  - ipc/sem.c:__arm64_compat_sys_old_semctl
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
long int __se_compat_sys_old_semctl(long int semid, long int semnum, long int cmd, long int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (c00000000066e430)
Location: ipc/sem.c:1814
Inline: False
```
**Symbols:**

```
c00000000066e430-c00000000066e460: __se_compat_sys_old_semctl (STB_GLOBAL)
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
In ipc/sem.c (ffffffff81435975)
Location: ipc/sem.c:1814
Inline: True
Inline callers:
  - ipc/sem.c:__x32_compat_sys_old_semctl
  - ipc/sem.c:__ia32_compat_sys_old_semctl
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
In ipc/sem.c (ffffffff814263f5)
Location: ipc/sem.c:1814
Inline: True
Inline callers:
  - ipc/sem.c:__x32_compat_sys_old_semctl
  - ipc/sem.c:__ia32_compat_sys_old_semctl
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
In ipc/sem.c (ffffffff81431b15)
Location: ipc/sem.c:1814
Inline: True
Inline callers:
  - ipc/sem.c:__x32_compat_sys_old_semctl
  - ipc/sem.c:__ia32_compat_sys_old_semctl
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
In ipc/sem.c (ffffffff81448be5)
Location: ipc/sem.c:1814
Inline: True
Inline callers:
  - ipc/sem.c:__x32_compat_sys_old_semctl
  - ipc/sem.c:__ia32_compat_sys_old_semctl
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
