# Function: <code>mpi_addm</code>

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
void mpi_addm(MPI w, MPI u, MPI v, MPI m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-add.c (ffffffff816026e0)
Location: lib/mpi/mpi-add.c:143
Inline: False
```
**Symbols:**

```
ffffffff816026e0-ffffffff8160270c: mpi_addm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mpi_addm(MPI w, MPI u, MPI v, MPI m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-add.c (ffffffff815e5470)
Location: lib/mpi/mpi-add.c:143
Inline: False
```
**Symbols:**

```
ffffffff815e5470-ffffffff815e549c: mpi_addm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mpi_addm(MPI w, MPI u, MPI v, MPI m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-add.c (ffffffff816516a0)
Location: lib/mpi/mpi-add.c:143
Inline: False
```
**Symbols:**

```
ffffffff816516a0-ffffffff816516cc: mpi_addm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mpi_addm(MPI w, MPI u, MPI v, MPI m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-add.c (ffffffff81768760)
Location: lib/mpi/mpi-add.c:143
Inline: False
```
**Symbols:**

```
ffffffff81768760-ffffffff81768796: mpi_addm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mpi_addm(MPI w, MPI u, MPI v, MPI m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-add.c (ffffffff81897bd0)
Location: lib/mpi/mpi-add.c:143
Inline: False
Direct callers:
  - crypto/rsa.c:rsa_dec
```
**Symbols:**

```
ffffffff81897bd0-ffffffff81897c06: mpi_addm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mpi_addm(MPI w, MPI u, MPI v, MPI m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-add.c (ffffffff818da0f0)
Location: lib/mpi/mpi-add.c:143
Inline: False
Direct callers:
  - crypto/rsa.c:rsa_dec
```
**Symbols:**

```
ffffffff818da0f0-ffffffff818da126: mpi_addm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mpi_addm(MPI w, MPI u, MPI v, MPI m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/mpi/mpi-add.c (ffffffff81870c50)
Location: lib/crypto/mpi/mpi-add.c:143
Inline: False
Direct callers:
  - crypto/rsa.c:rsa_dec
```
**Symbols:**

```
ffffffff81870c50-ffffffff81870c86: mpi_addm (STB_GLOBAL)
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
