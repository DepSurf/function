# Function: <code>SyS_fchownat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
long int SyS_fchownat(long int dfd, long int filename, long int user, long int group, long int flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8120b060)
Location: fs/open.c:613
Inline: True
Inline callers:
  - fs/open.c:SyS_chown
  - fs/open.c:SyS_lchown
```
**Symbols:**

```
ffffffff8120b060-ffffffff8120b162: SyS_fchownat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long int SyS_fchownat(long int dfd, long int filename, long int user, long int group, long int flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81230f4e)
Location: fs/open.c:613
Inline: True
Inline callers:
  - fs/open.c:SyS_lchown
  - fs/open.c:SyS_chown
```
**Symbols:**

```
ffffffff81230d30-ffffffff81230e32: SyS_fchownat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
long int SyS_fchownat(long int dfd, long int filename, long int user, long int group, long int flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff812434fe)
Location: fs/open.c:630
Inline: True
Inline callers:
  - fs/open.c:SyS_lchown
  - fs/open.c:SyS_chown
```
**Symbols:**

```
ffffffff812432e0-ffffffff812433e2: SyS_fchownat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long int SyS_fchownat(long int dfd, long int filename, long int user, long int group, long int flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8124ec51)
Location: fs/open.c:626
Inline: True
Inline callers:
  - fs/open.c:SyS_lchown
  - fs/open.c:SyS_chown
```
**Symbols:**

```
ffffffff8124ea50-ffffffff8124eb3e: SyS_fchownat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long int SyS_fchownat(long int dfd, long int filename, long int user, long int group, long int flag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81270bd1)
Location: fs/open.c:626
Inline: True
Inline callers:
  - fs/open.c:SyS_lchown
  - fs/open.c:SyS_chown
```
**Symbols:**

```
ffffffff812709d0-ffffffff81270abe: SyS_fchownat (STB_GLOBAL)
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
