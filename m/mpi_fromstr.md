# Function: <code>mpi_fromstr</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mpi_fromstr(MPI val, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffffffff81601720)
Location: lib/mpi/mpicoder.c:116
Inline: False
Direct callers:
  - lib/mpi/mpicoder.c:mpi_scanval
```
**Symbols:**

```
ffffffff81601720-ffffffff81601902: mpi_fromstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mpi_fromstr(MPI val, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffffffff815e44b0)
Location: lib/mpi/mpicoder.c:116
Inline: False
Direct callers:
  - lib/mpi/mpicoder.c:mpi_scanval
```
**Symbols:**

```
ffffffff815e44b0-ffffffff815e4692: mpi_fromstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int mpi_fromstr(MPI val, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffffffff816506e0)
Location: lib/mpi/mpicoder.c:116
Inline: False
Direct callers:
  - lib/mpi/mpicoder.c:mpi_scanval
```
**Symbols:**

```
ffffffff816506e0-ffffffff816508c2: mpi_fromstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mpi_fromstr(MPI val, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffffffff81767660)
Location: lib/mpi/mpicoder.c:116
Inline: False
Direct callers:
  - lib/mpi/mpicoder.c:mpi_scanval
```
**Symbols:**

```
ffffffff81767660-ffffffff81767867: mpi_fromstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mpi_fromstr(MPI val, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffffffff818969b0)
Location: lib/mpi/mpicoder.c:116
Inline: False
Direct callers:
  - lib/mpi/mpicoder.c:mpi_scanval
```
**Symbols:**

```
ffffffff818969b0-ffffffff81896bb7: mpi_fromstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mpi_fromstr(MPI val, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffffffff818d8e70)
Location: lib/mpi/mpicoder.c:116
Inline: False
Direct callers:
  - lib/mpi/mpicoder.c:mpi_scanval
```
**Symbols:**

```
ffffffff818d8e70-ffffffff818d9077: mpi_fromstr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mpi_fromstr(MPI val, const char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/mpi/mpicoder.c (ffffffff8186f9d0)
Location: lib/crypto/mpi/mpicoder.c:116
Inline: False
Direct callers:
  - lib/crypto/mpi/mpicoder.c:mpi_scanval
```
**Symbols:**

```
ffffffff8186f9d0-ffffffff8186fbd7: mpi_fromstr (STB_GLOBAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
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
