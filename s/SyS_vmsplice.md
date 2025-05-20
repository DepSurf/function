# Function: <code>SyS_vmsplice</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
long int SyS_vmsplice(long int fd, long int iov, long int nr_segs, long int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8123f6b0)
Location: fs/splice.c:1642
Inline: True
Inline callers:
  - fs/splice.c:compat_SyS_vmsplice
```
**Symbols:**

```
ffffffff8123f6b0-ffffffff8123f786: SyS_vmsplice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long int SyS_vmsplice(long int fd, long int iov, long int nr_segs, long int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81267bb6)
Location: fs/splice.c:1646
Inline: True
Inline callers:
  - fs/splice.c:compat_SyS_vmsplice
```
**Symbols:**

```
ffffffff812679f0-ffffffff81267ac6: SyS_vmsplice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
long int SyS_vmsplice(long int fd, long int iov, long int nr_segs, long int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8127ab26)
Location: fs/splice.c:1356
Inline: True
Inline callers:
  - fs/splice.c:compat_SyS_vmsplice
```
**Symbols:**

```
ffffffff8127a960-ffffffff8127aa36: SyS_vmsplice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long int SyS_vmsplice(long int fd, long int iov, long int nr_segs, long int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81287f66)
Location: fs/splice.c:1352
Inline: True
Inline callers:
  - fs/splice.c:compat_SyS_vmsplice
```
**Symbols:**

```
ffffffff81287db0-ffffffff81287e76: SyS_vmsplice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long int SyS_vmsplice(long int fd, long int iov, long int nr_segs, long int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff812aaa96)
Location: fs/splice.c:1336
Inline: True
Inline callers:
  - fs/splice.c:compat_SyS_vmsplice
```
**Symbols:**

```
ffffffff812aa8e0-ffffffff812aa9a6: SyS_vmsplice (STB_GLOBAL)
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
