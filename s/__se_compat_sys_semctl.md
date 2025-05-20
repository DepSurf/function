# Function: <code>__se_compat_sys_semctl</code>

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
In ipc/sem.c (ffffffff813dce45)
Location: ipc/sem.c:1786
Inline: True
Inline callers:
  - ipc/sem.c:__x32_compat_sys_semctl
  - ipc/sem.c:__ia32_compat_sys_semctl
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
In ipc/sem.c (ffffffff813f74a5)
Location: ipc/sem.c:1793
Inline: True
Inline callers:
  - ipc/sem.c:__x32_compat_sys_semctl
  - ipc/sem.c:__ia32_compat_sys_semctl
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
In ipc/sem.c (ffffffff814235f5)
Location: ipc/sem.c:1801
Inline: True
Inline callers:
  - ipc/sem.c:__x32_compat_sys_semctl
  - ipc/sem.c:__ia32_compat_sys_semctl
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
In ipc/sem.c (ffffffff8143d335)
Location: ipc/sem.c:1801
Inline: True
Inline callers:
  - ipc/sem.c:__x32_compat_sys_semctl
  - ipc/sem.c:__ia32_compat_sys_semctl
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
In ipc/sem.c (ffffffff8148df05)
Location: ipc/sem.c:1817
Inline: True
Inline callers:
  - ipc/sem.c:__x32_compat_sys_semctl
  - ipc/sem.c:__ia32_compat_sys_semctl
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
In ipc/sem.c (ffffffff814ab645)
Location: ipc/sem.c:1816
Inline: True
Inline callers:
  - ipc/sem.c:__x32_compat_sys_semctl
  - ipc/sem.c:__ia32_compat_sys_semctl
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
In ipc/sem.c (ffffffff814b05e5)
Location: ipc/sem.c:1818
Inline: True
Inline callers:
  - ipc/sem.c:__x32_compat_sys_semctl
  - ipc/sem.c:__ia32_compat_sys_semctl
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
In ipc/sem.c (ffffffff815086b5)
Location: ipc/sem.c:1821
Inline: True
Inline callers:
  - ipc/sem.c:__x64_compat_sys_semctl
  - ipc/sem.c:__ia32_compat_sys_semctl
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
In ipc/sem.c (ffffffff8159a6c5)
Location: ipc/sem.c:1819
Inline: True
Inline callers:
  - ipc/sem.c:__ia32_compat_sys_semctl
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
In ipc/sem.c (ffffffff81643985)
Location: ipc/sem.c:1819
Inline: True
Inline callers:
  - ipc/sem.c:__ia32_compat_sys_semctl
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
In ipc/sem.c (ffffffff8167bed5)
Location: ipc/sem.c:1819
Inline: True
Inline callers:
  - ipc/sem.c:__ia32_compat_sys_semctl
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
In ipc/sem.c (ffffffff816b82a5)
Location: ipc/sem.c:1819
Inline: True
Inline callers:
  - ipc/sem.c:__ia32_compat_sys_semctl
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
In ipc/sem.c (ffff800010525190)
Location: ipc/sem.c:1801
Inline: True
Inline callers:
  - ipc/sem.c:__arm64_compat_sys_semctl
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
long int __se_compat_sys_semctl(long int semid, long int semnum, long int cmd, long int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (c00000000066e400)
Location: ipc/sem.c:1801
Inline: False
```
**Symbols:**

```
c00000000066e400-c00000000066e428: __se_compat_sys_semctl (STB_GLOBAL)
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
In ipc/sem.c (ffffffff81435915)
Location: ipc/sem.c:1801
Inline: True
Inline callers:
  - ipc/sem.c:__x32_compat_sys_semctl
  - ipc/sem.c:__ia32_compat_sys_semctl
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
In ipc/sem.c (ffffffff81426395)
Location: ipc/sem.c:1801
Inline: True
Inline callers:
  - ipc/sem.c:__x32_compat_sys_semctl
  - ipc/sem.c:__ia32_compat_sys_semctl
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
In ipc/sem.c (ffffffff81431ab5)
Location: ipc/sem.c:1801
Inline: True
Inline callers:
  - ipc/sem.c:__x32_compat_sys_semctl
  - ipc/sem.c:__ia32_compat_sys_semctl
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
In ipc/sem.c (ffffffff81448b85)
Location: ipc/sem.c:1801
Inline: True
Inline callers:
  - ipc/sem.c:__x32_compat_sys_semctl
  - ipc/sem.c:__ia32_compat_sys_semctl
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
