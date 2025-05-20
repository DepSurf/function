# Function: <code>compat_SyS_futimesat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
long int compat_SyS_futimesat(long int dfd, long int filename, long int t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/compat.c (ffffffff81264260)
Location: fs/compat.c:105
Inline: True
Inline callers:
  - fs/compat.c:compat_SyS_utimes
```
**Symbols:**

```
ffffffff81264260-ffffffff81264343: compat_SyS_futimesat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long int compat_SyS_futimesat(long int dfd, long int filename, long int t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/compat.c (ffffffff812906a1)
Location: fs/compat.c:105
Inline: True
Inline callers:
  - fs/compat.c:compat_SyS_utimes
```
**Symbols:**

```
ffffffff81290590-ffffffff81290673: compat_SyS_futimesat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
long int compat_SyS_futimesat(long int dfd, long int filename, long int t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/compat.c (ffffffff812a5651)
Location: fs/compat.c:91
Inline: True
Inline callers:
  - fs/compat.c:compat_SyS_utimes
```
**Symbols:**

```
ffffffff812a5540-ffffffff812a5623: compat_SyS_futimesat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long int compat_SyS_futimesat(long int dfd, long int filename, long int t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff81289b2b)
Location: fs/utimes.c:254
Inline: True
Inline callers:
  - fs/utimes.c:compat_SyS_utimes
```
**Symbols:**

```
ffffffff81289a00-ffffffff81289af2: compat_SyS_futimesat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long int compat_SyS_futimesat(long int dfd, long int filename, long int t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff812ac66b)
Location: fs/utimes.c:256
Inline: True
Inline callers:
  - fs/utimes.c:compat_SyS_utimes
```
**Symbols:**

```
ffffffff812ac540-ffffffff812ac632: compat_SyS_futimesat (STB_GLOBAL)
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
