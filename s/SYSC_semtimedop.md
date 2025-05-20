# Function: <code>SYSC_semtimedop</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int SYSC_semtimedop(int semid, struct sembuf *tsops, unsigned int nsops, const struct timespec *timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81328160)
Location: ipc/sem.c:1792
Inline: False
Direct callers:
  - ipc/sem.c:SyS_semop
```
**Symbols:**

```
ffffffff81328160-ffffffff81328f3d: SYSC_semtimedop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int SYSC_semtimedop(int semid, struct sembuf *tsops, unsigned int nsops, const struct timespec *timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff8135cdf0)
Location: ipc/sem.c:1790
Inline: False
Direct callers:
  - ipc/sem.c:SyS_semop
```
**Symbols:**

```
ffffffff8135cdf0-ffffffff8135db83: SYSC_semtimedop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int SYSC_semtimedop(int semid, struct sembuf *tsops, unsigned int nsops, const struct timespec *timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff813734d0)
Location: ipc/sem.c:1755
Inline: False
Direct callers:
  - ipc/sem.c:SyS_semop
```
**Symbols:**

```
ffffffff813734d0-ffffffff813742c9: SYSC_semtimedop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int SYSC_semtimedop(int semid, struct sembuf *tsops, unsigned int nsops, const struct timespec *timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/sem.c (ffffffff81386ae0)
Location: ipc/sem.c:1768
Inline: False
Direct callers:
  - ipc/sem.c:SyS_semop
```
**Symbols:**

```
ffffffff81386ae0-ffffffff81387c10: SYSC_semtimedop (STB_LOCAL)
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
In ipc/sem.c (ffffffff813ad47a)
Location: ipc/sem.c:2113
Inline: True
Inline callers:
  - ipc/sem.c:SyS_semtimedop
```
</details>
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
</ul>
