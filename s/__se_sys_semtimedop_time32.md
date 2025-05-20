# Function: <code>__se_sys_semtimedop_time32</code>

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
In ipc/sem.c (ffffffff81423b45)
Location: ipc/sem.c:2250
Inline: True
Inline callers:
  - ipc/sem.c:__ia32_sys_semtimedop_time32
  - ipc/sem.c:__x64_sys_semtimedop_time32
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
In ipc/sem.c (ffffffff8143d885)
Location: ipc/sem.c:2251
Inline: True
Inline callers:
  - ipc/sem.c:__ia32_sys_semtimedop_time32
  - ipc/sem.c:__x64_sys_semtimedop_time32
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
In ipc/sem.c (ffffffff8148d6e8)
Location: ipc/sem.c:2267
Inline: True
Inline callers:
  - ipc/sem.c:__ia32_sys_semtimedop_time32
  - ipc/sem.c:__x64_sys_semtimedop_time32
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
In ipc/sem.c (ffffffff814aae98)
Location: ipc/sem.c:2266
Inline: True
Inline callers:
  - ipc/sem.c:__ia32_sys_semtimedop_time32
  - ipc/sem.c:__x64_sys_semtimedop_time32
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
In ipc/sem.c (ffffffff814b16d9)
Location: ipc/sem.c:2268
Inline: True
Inline callers:
  - ipc/sem.c:__ia32_sys_semtimedop_time32
  - ipc/sem.c:__x64_sys_semtimedop_time32
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
In ipc/sem.c (ffffffff81509da9)
Location: ipc/sem.c:2292
Inline: True
Inline callers:
  - ipc/sem.c:__ia32_sys_semtimedop_time32
  - ipc/sem.c:__x64_sys_semtimedop_time32
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
In ipc/sem.c (ffffffff8159ba18)
Location: ipc/sem.c:2289
Inline: True
Inline callers:
  - ipc/sem.c:__ia32_sys_semtimedop_time32
  - ipc/sem.c:__x64_sys_semtimedop_time32
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
In ipc/sem.c (ffffffff81644e88)
Location: ipc/sem.c:2290
Inline: True
Inline callers:
  - ipc/sem.c:__ia32_sys_semtimedop_time32
  - ipc/sem.c:__x64_sys_semtimedop_time32
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
In ipc/sem.c (ffffffff8167d2b8)
Location: ipc/sem.c:2290
Inline: True
Inline callers:
  - ipc/sem.c:__ia32_sys_semtimedop_time32
  - ipc/sem.c:__x64_sys_semtimedop_time32
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
In ipc/sem.c (ffffffff816b9688)
Location: ipc/sem.c:2288
Inline: True
Inline callers:
  - ipc/sem.c:__ia32_sys_semtimedop_time32
  - ipc/sem.c:__x64_sys_semtimedop_time32
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
In ipc/sem.c (ffff800010525708)
Location: ipc/sem.c:2251
Inline: True
Inline callers:
  - ipc/sem.c:__arm64_sys_semtimedop_time32
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int __se_sys_semtimedop_time32(long int semid, long int tsems, long int nsops, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (c06dfbb0)
Location: ipc/sem.c:2251
Inline: False
```
**Symbols:**

```
c06dfbb0-c06dfbcc: __se_sys_semtimedop_time32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __se_sys_semtimedop_time32(long int semid, long int tsems, long int nsops, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (c00000000066fb20)
Location: ipc/sem.c:2251
Inline: False
```
**Symbols:**

```
c00000000066fb20-c00000000066fb3c: __se_sys_semtimedop_time32 (STB_GLOBAL)
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
In ipc/sem.c (ffffffff81435e65)
Location: ipc/sem.c:2251
Inline: True
Inline callers:
  - ipc/sem.c:__ia32_sys_semtimedop_time32
  - ipc/sem.c:__x64_sys_semtimedop_time32
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
In ipc/sem.c (ffffffff814268e5)
Location: ipc/sem.c:2251
Inline: True
Inline callers:
  - ipc/sem.c:__ia32_sys_semtimedop_time32
  - ipc/sem.c:__x64_sys_semtimedop_time32
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
In ipc/sem.c (ffffffff81432005)
Location: ipc/sem.c:2251
Inline: True
Inline callers:
  - ipc/sem.c:__ia32_sys_semtimedop_time32
  - ipc/sem.c:__x64_sys_semtimedop_time32
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
In ipc/sem.c (ffffffff814490d5)
Location: ipc/sem.c:2251
Inline: True
Inline callers:
  - ipc/sem.c:__ia32_sys_semtimedop_time32
  - ipc/sem.c:__x64_sys_semtimedop_time32
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
