# Function: <code>mpi_rshift</code>

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
void mpi_rshift(MPI x, MPI a, unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-bit.c (ffffffff81602c20)
Location: lib/mpi/mpi-bit.c:178
Inline: False
Direct callers:
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/mpi-bit.c:mpi_lshift
```
**Symbols:**

```
ffffffff81602c20-ffffffff81602e0b: mpi_rshift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mpi_rshift(MPI x, MPI a, unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-bit.c (ffffffff815e59b0)
Location: lib/mpi/mpi-bit.c:178
Inline: False
Direct callers:
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/mpi-bit.c:mpi_lshift
```
**Symbols:**

```
ffffffff815e59b0-ffffffff815e5ba7: mpi_rshift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mpi_rshift(MPI x, MPI a, unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-bit.c (ffffffff81651be0)
Location: lib/mpi/mpi-bit.c:178
Inline: False
Direct callers:
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/mpi-bit.c:mpi_lshift
```
**Symbols:**

```
ffffffff81651be0-ffffffff81651dd7: mpi_rshift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mpi_rshift(MPI x, MPI a, unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-bit.c (ffffffff81768b90)
Location: lib/mpi/mpi-bit.c:178
Inline: False
Direct callers:
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/mpi-bit.c:mpi_lshift
```
**Symbols:**

```
ffffffff81768b90-ffffffff81768d84: mpi_rshift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mpi_rshift(MPI x, MPI a, unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-bit.c (ffffffff81898010)
Location: lib/mpi/mpi-bit.c:178
Inline: False
Direct callers:
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/mpi-bit.c:mpi_lshift
```
**Symbols:**

```
ffffffff81898010-ffffffff81898204: mpi_rshift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mpi_rshift(MPI x, MPI a, unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-bit.c (ffffffff818da540)
Location: lib/mpi/mpi-bit.c:178
Inline: False
Direct callers:
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/mpi-bit.c:mpi_lshift
```
**Symbols:**

```
ffffffff818da540-ffffffff818da75b: mpi_rshift (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mpi_rshift(MPI x, MPI a, unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/mpi/mpi-bit.c (ffffffff818710a0)
Location: lib/crypto/mpi/mpi-bit.c:178
Inline: False
Direct callers:
  - lib/crypto/mpi/ec.c:mpi_ec_curve_point
  - lib/crypto/mpi/mpi-bit.c:mpi_lshift
```
**Symbols:**

```
ffffffff818710a0-ffffffff818712bb: mpi_rshift (STB_GLOBAL)
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
