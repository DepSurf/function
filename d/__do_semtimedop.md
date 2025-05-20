# Function: <code>__do_semtimedop</code>

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
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long int __do_semtimedop(int semid, struct sembuf *sops, unsigned int nsops, const struct timespec64 *timeout, struct ipc_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/sem.c (0)
Location: ipc/sem.c:1987
Inline: False
Direct callers:
  - ipc/sem.c:do_semtimedop
```
**Symbols:**

```
ffffffff81cd2b79-ffffffff81cd2bb3: __do_semtimedop.cold (STB_LOCAL)
ffffffff81508e80-ffffffff815099d4: __do_semtimedop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long int __do_semtimedop(int semid, struct sembuf *sops, unsigned int nsops, const struct timespec64 *timeout, struct ipc_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/sem.c (0)
Location: ipc/sem.c:1985
Inline: False
Direct callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
```
**Symbols:**

```
ffffffff81e85cf0-ffffffff81e85d8b: __do_semtimedop.cold (STB_LOCAL)
ffffffff8159aa90-ffffffff8159b683: __do_semtimedop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
long int __do_semtimedop(int semid, struct sembuf *sops, unsigned int nsops, const struct timespec64 *timeout, struct ipc_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/sem.c (0)
Location: ipc/sem.c:1985
Inline: False
Direct callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
```
**Symbols:**

```
ffffffff82072e69-ffffffff82072f04: __do_semtimedop.cold (STB_LOCAL)
ffffffff81643de0-ffffffff816449d8: __do_semtimedop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
long int __do_semtimedop(int semid, struct sembuf *sops, unsigned int nsops, const struct timespec64 *timeout, struct ipc_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/sem.c (0)
Location: ipc/sem.c:1985
Inline: False
Direct callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
```
**Symbols:**

```
ffffffff820f2abd-ffffffff820f2b4c: __do_semtimedop.cold (STB_LOCAL)
ffffffff8167c320-ffffffff8167ceb1: __do_semtimedop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
long int __do_semtimedop(int semid, struct sembuf *sops, unsigned int nsops, const struct timespec64 *timeout, struct ipc_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/sem.c (0)
Location: ipc/sem.c:1983
Inline: False
Direct callers:
  - ipc/sem.c:do_semtimedop
  - ipc/sem.c:do_semtimedop
```
**Symbols:**

```
ffffffff821cfd55-ffffffff821cfde4: __do_semtimedop.cold (STB_LOCAL)
ffffffff816b86f0-ffffffff816b9281: __do_semtimedop (STB_GLOBAL)
```
</details>
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
