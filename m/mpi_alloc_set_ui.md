# Function: <code>mpi_alloc_set_ui</code>

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
MPI mpi_alloc_set_ui(long unsigned int u);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpiutil.c (ffffffff81607090)
Location: lib/mpi/mpiutil.c:286
Inline: False
Direct callers:
  - lib/mpi/mpiutil.c:mpi_init
```
**Symbols:**

```
ffffffff81607090-ffffffff81607143: mpi_alloc_set_ui (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
MPI mpi_alloc_set_ui(long unsigned int u);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpiutil.c (ffffffff815e9de0)
Location: lib/mpi/mpiutil.c:286
Inline: False
Direct callers:
  - lib/mpi/mpiutil.c:mpi_init
```
**Symbols:**

```
ffffffff815e9de0-ffffffff815e9e93: mpi_alloc_set_ui (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
MPI mpi_alloc_set_ui(long unsigned int u);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpiutil.c (ffffffff816561c0)
Location: lib/mpi/mpiutil.c:286
Inline: False
Direct callers:
  - lib/mpi/mpiutil.c:mpi_init
```
**Symbols:**

```
ffffffff816561c0-ffffffff81656273: mpi_alloc_set_ui (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
MPI mpi_alloc_set_ui(long unsigned int u);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpiutil.c (ffffffff8176d8b0)
Location: lib/mpi/mpiutil.c:286
Inline: False
Direct callers:
  - lib/mpi/mpiutil.c:mpi_init
  - lib/mpi/mpiutil.c:mpi_init
```
**Symbols:**

```
ffffffff8176d8b0-ffffffff8176d963: mpi_alloc_set_ui (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
MPI mpi_alloc_set_ui(long unsigned int u);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/mpi/mpiutil.c (ffffffff83ed9787)
Location: lib/mpi/mpiutil.c:286
Inline: True
Inline callers:
  - lib/mpi/mpiutil.c:mpi_init
```
**Symbols:**

```
ffffffff8189d0a0-ffffffff8189d153: mpi_alloc_set_ui (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
MPI mpi_alloc_set_ui(long unsigned int u);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/mpi/mpiutil.c (ffffffff836ff227)
Location: lib/mpi/mpiutil.c:286
Inline: True
Inline callers:
  - lib/mpi/mpiutil.c:mpi_init
```
**Symbols:**

```
ffffffff818df650-ffffffff818df703: mpi_alloc_set_ui (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
MPI mpi_alloc_set_ui(long unsigned int u);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/crypto/mpi/mpiutil.c (ffffffff83932477)
Location: lib/crypto/mpi/mpiutil.c:286
Inline: True
Inline callers:
  - lib/crypto/mpi/mpiutil.c:mpi_init
```
**Symbols:**

```
ffffffff81876280-ffffffff818762be: mpi_alloc_set_ui (STB_GLOBAL)
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
