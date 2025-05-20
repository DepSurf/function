# Function: <code>compat_SyS_vmsplice</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int compat_SyS_vmsplice(long int fd, long int iov32, long int nr_segs, long int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8123f790)
Location: fs/splice.c:1668
Inline: False
```
**Symbols:**

```
ffffffff8123f790-ffffffff8123f8fa: compat_SyS_vmsplice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int compat_SyS_vmsplice(long int fd, long int iov32, long int nr_segs, long int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81267ad0)
Location: fs/splice.c:1672
Inline: False
```
**Symbols:**

```
ffffffff81267ad0-ffffffff81267c3b: compat_SyS_vmsplice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int compat_SyS_vmsplice(long int fd, long int iov32, long int nr_segs, long int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8127aa40)
Location: fs/splice.c:1382
Inline: False
```
**Symbols:**

```
ffffffff8127aa40-ffffffff8127abab: compat_SyS_vmsplice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int compat_SyS_vmsplice(long int fd, long int iov32, long int nr_segs, long int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81287e80)
Location: fs/splice.c:1380
Inline: False
```
**Symbols:**

```
ffffffff81287e80-ffffffff81287ff4: compat_SyS_vmsplice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int compat_SyS_vmsplice(long int fd, long int iov32, long int nr_segs, long int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff812aa9b0)
Location: fs/splice.c:1364
Inline: False
```
**Symbols:**

```
ffffffff812aa9b0-ffffffff812aab24: compat_SyS_vmsplice (STB_GLOBAL)
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
