# Function: <code>mpi_print</code>

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
int mpi_print(enum gcry_mpi_format format, unsigned char *buffer, size_t buflen, size_t *nwritten, MPI a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffffffff81601f70)
Location: lib/mpi/mpicoder.c:554
Inline: False
```
**Symbols:**

```
ffffffff81601f70-ffffffff816023ce: mpi_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mpi_print(enum gcry_mpi_format format, unsigned char *buffer, size_t buflen, size_t *nwritten, MPI a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffffffff815e4d10)
Location: lib/mpi/mpicoder.c:554
Inline: False
```
**Symbols:**

```
ffffffff815e4d10-ffffffff815e5168: mpi_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int mpi_print(enum gcry_mpi_format format, unsigned char *buffer, size_t buflen, size_t *nwritten, MPI a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffffffff81650f40)
Location: lib/mpi/mpicoder.c:554
Inline: False
```
**Symbols:**

```
ffffffff81650f40-ffffffff81651398: mpi_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mpi_print(enum gcry_mpi_format format, unsigned char *buffer, size_t buflen, size_t *nwritten, MPI a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffffffff81767f50)
Location: lib/mpi/mpicoder.c:554
Inline: False
```
**Symbols:**

```
ffffffff81767f50-ffffffff8176844d: mpi_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mpi_print(enum gcry_mpi_format format, unsigned char *buffer, size_t buflen, size_t *nwritten, MPI a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffffffff81897340)
Location: lib/mpi/mpicoder.c:555
Inline: False
```
**Symbols:**

```
ffffffff81897340-ffffffff81897823: mpi_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mpi_print(enum gcry_mpi_format format, unsigned char *buffer, size_t buflen, size_t *nwritten, MPI a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpicoder.c (ffffffff818d9860)
Location: lib/mpi/mpicoder.c:555
Inline: False
```
**Symbols:**

```
ffffffff818d9860-ffffffff818d9d41: mpi_print (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mpi_print(enum gcry_mpi_format format, unsigned char *buffer, size_t buflen, size_t *nwritten, MPI a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/mpi/mpicoder.c (ffffffff818703c0)
Location: lib/crypto/mpi/mpicoder.c:555
Inline: False
```
**Symbols:**

```
ffffffff818703c0-ffffffff818708a1: mpi_print (STB_GLOBAL)
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
