# Function: <code>SyS_readlinkat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
long int SyS_readlinkat(long int dfd, long int pathname, long int buf, long int bufsiz);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81211d00)
Location: fs/stat.c:315
Inline: True
Inline callers:
  - fs/stat.c:SyS_readlink
```
**Symbols:**

```
ffffffff81211d00-ffffffff81211e19: SyS_readlinkat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long int SyS_readlinkat(long int dfd, long int pathname, long int buf, long int bufsiz);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812388f6)
Location: fs/stat.c:315
Inline: True
Inline callers:
  - fs/stat.c:SyS_readlink
```
**Symbols:**

```
ffffffff812387b0-ffffffff812388d9: SyS_readlinkat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
long int SyS_readlinkat(long int dfd, long int pathname, long int buf, long int bufsiz);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff8124b5b6)
Location: fs/stat.c:315
Inline: True
Inline callers:
  - fs/stat.c:SyS_readlink
```
**Symbols:**

```
ffffffff8124b470-ffffffff8124b599: SyS_readlinkat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long int SyS_readlinkat(long int dfd, long int pathname, long int buf, long int bufsiz);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff812576e6)
Location: fs/stat.c:381
Inline: True
Inline callers:
  - fs/stat.c:SyS_readlink
```
**Symbols:**

```
ffffffff812575a0-ffffffff812576cb: SyS_readlinkat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long int SyS_readlinkat(long int dfd, long int pathname, long int buf, long int bufsiz);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/stat.c (ffffffff81279936)
Location: fs/stat.c:382
Inline: True
Inline callers:
  - fs/stat.c:SyS_readlink
```
**Symbols:**

```
ffffffff812797f0-ffffffff8127991b: SyS_readlinkat (STB_GLOBAL)
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
