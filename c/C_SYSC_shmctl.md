# Function: <code>C_SYSC_shmctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int C_SYSC_shmctl(int first, int second, void *uptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffffffff813236b0)
Location: ipc/compat.c:668
Inline: False
Direct callers:
  - ipc/compat.c:compat_SyS_ipc
```
**Symbols:**

```
ffffffff813236b0-ffffffff81323db0: C_SYSC_shmctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int C_SYSC_shmctl(int first, int second, void *uptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffffffff81358430)
Location: ipc/compat.c:668
Inline: False
Direct callers:
  - ipc/compat.c:compat_SyS_ipc
```
**Symbols:**

```
ffffffff81358430-ffffffff81358a17: C_SYSC_shmctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int C_SYSC_shmctl(int first, int second, void *uptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffffffff8136e920)
Location: ipc/compat.c:668
Inline: False
Direct callers:
  - ipc/compat.c:compat_SyS_ipc
```
**Symbols:**

```
ffffffff8136e920-ffffffff8136ef07: C_SYSC_shmctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int C_SYSC_shmctl(int first, int second, void *uptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffffffff81381ea0)
Location: ipc/compat.c:668
Inline: False
Direct callers:
  - ipc/compat.c:compat_SyS_ipc
```
**Symbols:**

```
ffffffff81381ea0-ffffffff81382487: C_SYSC_shmctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int C_SYSC_shmctl(int shmid, int cmd, void *uptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff813aed30)
Location: ipc/shm.c:1218
Inline: False
Direct callers:
  - ipc/shm.c:compat_SyS_shmctl
```
**Symbols:**

```
ffffffff813aed30-ffffffff813aeffa: C_SYSC_shmctl (STB_LOCAL)
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
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int shmid</code>
</li>
<li>
<b>Param added. </b>
<code>int cmd</code>
</li>
<li>
<b>Param removed. </b>
<code>int first</code>
</li>
<li>
<b>Param removed. </b>
<code>int second</code>
</li>
</ul>
</details>
</li>
</ul>
