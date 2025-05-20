# Function: <code>SyS_renameat2</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
long int SyS_renameat2(long int olddfd, long int oldname, long int newdfd, long int newname, long int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8121dda0)
Location: fs/namei.c:4320
Inline: True
Inline callers:
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_rename
```
**Symbols:**

```
ffffffff8121dda0-ffffffff8121e369: SyS_renameat2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long int SyS_renameat2(long int olddfd, long int oldname, long int newdfd, long int newname, long int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81245dd5)
Location: fs/namei.c:4474
Inline: True
Inline callers:
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
```
**Symbols:**

```
ffffffff812453b0-ffffffff8124599e: SyS_renameat2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
long int SyS_renameat2(long int olddfd, long int oldname, long int newdfd, long int newname, long int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81258d35)
Location: fs/namei.c:4418
Inline: True
Inline callers:
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
```
**Symbols:**

```
ffffffff81258320-ffffffff81258909: SyS_renameat2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long int SyS_renameat2(long int olddfd, long int oldname, long int newdfd, long int newname, long int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81264e68)
Location: fs/namei.c:4484
Inline: True
Inline callers:
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
```
**Symbols:**

```
ffffffff812644c0-ffffffff81264a74: SyS_renameat2 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long int SyS_renameat2(long int olddfd, long int oldname, long int newdfd, long int newname, long int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812876f8)
Location: fs/namei.c:4480
Inline: True
Inline callers:
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
```
**Symbols:**

```
ffffffff81286d50-ffffffff81287307: SyS_renameat2 (STB_GLOBAL)
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
