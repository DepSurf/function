# Function: <code>mpi_mulm</code>

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
void mpi_mulm(MPI w, MPI u, MPI v, MPI m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-mul.c (ffffffff81604420)
Location: lib/mpi/mpi-mul.c:86
Inline: False
```
**Symbols:**

```
ffffffff81604420-ffffffff8160444c: mpi_mulm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mpi_mulm(MPI w, MPI u, MPI v, MPI m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-mul.c (ffffffff815e71a0)
Location: lib/mpi/mpi-mul.c:86
Inline: False
```
**Symbols:**

```
ffffffff815e71a0-ffffffff815e71cc: mpi_mulm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mpi_mulm(MPI w, MPI u, MPI v, MPI m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-mul.c (ffffffff816533f0)
Location: lib/mpi/mpi-mul.c:86
Inline: False
```
**Symbols:**

```
ffffffff816533f0-ffffffff8165341c: mpi_mulm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mpi_mulm(MPI w, MPI u, MPI v, MPI m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-mul.c (ffffffff8176a850)
Location: lib/mpi/mpi-mul.c:86
Inline: False
```
**Symbols:**

```
ffffffff8176a850-ffffffff8176a886: mpi_mulm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mpi_mulm(MPI w, MPI u, MPI v, MPI m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-mul.c (ffffffff81899e60)
Location: lib/mpi/mpi-mul.c:87
Inline: False
Direct callers:
  - crypto/rsa.c:rsa_dec
```
**Symbols:**

```
ffffffff81899e60-ffffffff81899e96: mpi_mulm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mpi_mulm(MPI w, MPI u, MPI v, MPI m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-mul.c (ffffffff818dc3e0)
Location: lib/mpi/mpi-mul.c:87
Inline: False
Direct callers:
  - crypto/rsa.c:rsa_dec
```
**Symbols:**

```
ffffffff818dc3e0-ffffffff818dc416: mpi_mulm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mpi_mulm(MPI w, MPI u, MPI v, MPI m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/mpi/mpi-mul.c (ffffffff81872fd0)
Location: lib/crypto/mpi/mpi-mul.c:87
Inline: False
Direct callers:
  - crypto/rsa.c:rsa_dec
```
**Symbols:**

```
ffffffff81872fd0-ffffffff81873006: mpi_mulm (STB_GLOBAL)
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
