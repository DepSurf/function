# Function: <code>do_compat_semctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int do_compat_semctl(int first, int second, int third, u32 pad);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffffffff81323210)
Location: ipc/compat.c:238
Inline: False
Direct callers:
  - ipc/compat.c:compat_SyS_ipc
  - ipc/compat.c:compat_SyS_semctl
```
**Symbols:**

```
ffffffff81323210-ffffffff813236a3: do_compat_semctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int do_compat_semctl(int first, int second, int third, u32 pad);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffffffff81358a20)
Location: ipc/compat.c:238
Inline: False
Direct callers:
  - ipc/compat.c:compat_SyS_semctl
  - ipc/compat.c:compat_SyS_ipc
```
**Symbols:**

```
ffffffff81358a20-ffffffff81358eb2: do_compat_semctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int do_compat_semctl(int first, int second, int third, u32 pad);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffffffff8136ef10)
Location: ipc/compat.c:238
Inline: False
Direct callers:
  - ipc/compat.c:compat_SyS_semctl
  - ipc/compat.c:compat_SyS_ipc
```
**Symbols:**

```
ffffffff8136ef10-ffffffff8136f3a2: do_compat_semctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int do_compat_semctl(int first, int second, int third, u32 pad);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat.c (ffffffff81382490)
Location: ipc/compat.c:238
Inline: False
Direct callers:
  - ipc/compat.c:compat_SyS_semctl
  - ipc/compat.c:compat_SyS_ipc
```
**Symbols:**

```
ffffffff81382490-ffffffff813828f4: do_compat_semctl (STB_LOCAL)
```
</details>
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
