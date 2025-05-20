# Function: <code>compat_SyS_process_vm_writev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int compat_SyS_process_vm_writev(long int pid, long int lvec, long int liovcnt, long int rvec, long int riovcnt, long int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/process_vm_access.c (ffffffff811d0f00)
Location: mm/process_vm_access.c:354
Inline: False
```
**Symbols:**

```
ffffffff811d0f00-ffffffff811d0f23: compat_SyS_process_vm_writev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int compat_SyS_process_vm_writev(long int pid, long int lvec, long int liovcnt, long int rvec, long int riovcnt, long int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/process_vm_access.c (ffffffff811ee080)
Location: mm/process_vm_access.c:359
Inline: False
```
**Symbols:**

```
ffffffff811ee080-ffffffff811ee0a3: compat_SyS_process_vm_writev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int compat_SyS_process_vm_writev(long int pid, long int lvec, long int liovcnt, long int rvec, long int riovcnt, long int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/process_vm_access.c (ffffffff811fe9c0)
Location: mm/process_vm_access.c:366
Inline: False
```
**Symbols:**

```
ffffffff811fe9c0-ffffffff811fe9e3: compat_SyS_process_vm_writev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int compat_SyS_process_vm_writev(long int pid, long int lvec, long int liovcnt, long int rvec, long int riovcnt, long int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/process_vm_access.c (ffffffff812095a0)
Location: mm/process_vm_access.c:367
Inline: False
```
**Symbols:**

```
ffffffff812095a0-ffffffff812095ba: compat_SyS_process_vm_writev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int compat_SyS_process_vm_writev(long int pid, long int lvec, long int liovcnt, long int rvec, long int riovcnt, long int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/process_vm_access.c (ffffffff812226f0)
Location: mm/process_vm_access.c:367
Inline: False
```
**Symbols:**

```
ffffffff812226f0-ffffffff8122270a: compat_SyS_process_vm_writev (STB_GLOBAL)
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
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
