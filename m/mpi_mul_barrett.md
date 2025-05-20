# Function: <code>mpi_mul_barrett</code>

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
void mpi_mul_barrett(MPI w, MPI u, MPI v, mpi_barrett_t ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-mod.c (ffffffff81604190)
Location: lib/mpi/mpi-mod.c:151
Inline: False
```
**Symbols:**

```
ffffffff81604190-ffffffff816041bc: mpi_mul_barrett (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mpi_mul_barrett(MPI w, MPI u, MPI v, mpi_barrett_t ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-mod.c (ffffffff815e6f10)
Location: lib/mpi/mpi-mod.c:151
Inline: False
```
**Symbols:**

```
ffffffff815e6f10-ffffffff815e6f3c: mpi_mul_barrett (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mpi_mul_barrett(MPI w, MPI u, MPI v, mpi_barrett_t ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-mod.c (ffffffff81653160)
Location: lib/mpi/mpi-mod.c:153
Inline: False
```
**Symbols:**

```
ffffffff81653160-ffffffff8165318c: mpi_mul_barrett (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mpi_mul_barrett(MPI w, MPI u, MPI v, mpi_barrett_t ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-mod.c (ffffffff8176a580)
Location: lib/mpi/mpi-mod.c:153
Inline: False
```
**Symbols:**

```
ffffffff8176a580-ffffffff8176a5b6: mpi_mul_barrett (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mpi_mul_barrett(MPI w, MPI u, MPI v, mpi_barrett_t ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-mod.c (ffffffff81899b70)
Location: lib/mpi/mpi-mod.c:153
Inline: False
```
**Symbols:**

```
ffffffff81899b70-ffffffff81899ba6: mpi_mul_barrett (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mpi_mul_barrett(MPI w, MPI u, MPI v, mpi_barrett_t ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-mod.c (ffffffff818dc0f0)
Location: lib/mpi/mpi-mod.c:153
Inline: False
```
**Symbols:**

```
ffffffff818dc0f0-ffffffff818dc126: mpi_mul_barrett (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mpi_mul_barrett(MPI w, MPI u, MPI v, mpi_barrett_t ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/mpi/mpi-mod.c (ffffffff81872ce0)
Location: lib/crypto/mpi/mpi-mod.c:153
Inline: False
```
**Symbols:**

```
ffffffff81872ce0-ffffffff81872d16: mpi_mul_barrett (STB_GLOBAL)
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
