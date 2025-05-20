# Function: <code>mpi_ec_dup_point</code>

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
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mpi_ec_dup_point(MPI_POINT result, MPI_POINT point, struct mpi_ec_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/mpi/ec.c (ffffffff81bf47a6)
Location: lib/mpi/ec.c:915
Inline: True
Direct callers:
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:add_points_weierstrass
```
**Symbols:**

```
ffffffff815ffb40-ffffffff815ffb68: mpi_ec_dup_point (STB_LOCAL)
ffffffff81bf47a6-ffffffff81bf47c5: mpi_ec_dup_point.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mpi_ec_dup_point(MPI_POINT result, MPI_POINT point, struct mpi_ec_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/mpi/ec.c (ffffffff81be6699)
Location: lib/mpi/ec.c:915
Inline: True
Direct callers:
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:add_points_weierstrass
```
**Symbols:**

```
ffffffff815e2870-ffffffff815e2898: mpi_ec_dup_point (STB_LOCAL)
ffffffff81be6699-ffffffff81be66b8: mpi_ec_dup_point.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mpi_ec_dup_point(MPI_POINT result, MPI_POINT point, struct mpi_ec_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/mpi/ec.c (ffffffff81cde0af)
Location: lib/mpi/ec.c:915
Inline: True
Direct callers:
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:add_points_weierstrass
```
**Symbols:**

```
ffffffff8164eaa0-ffffffff8164eac8: mpi_ec_dup_point (STB_LOCAL)
ffffffff81cde0af-ffffffff81cde0ce: mpi_ec_dup_point.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mpi_ec_dup_point(MPI_POINT result, MPI_POINT point, struct mpi_ec_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/mpi/ec.c (ffffffff81ea4416)
Location: lib/mpi/ec.c:915
Inline: True
Direct callers:
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:add_points_weierstrass
```
**Symbols:**

```
ffffffff817659a0-ffffffff817659e0: mpi_ec_dup_point (STB_LOCAL)
ffffffff81ea4416-ffffffff81ea4435: mpi_ec_dup_point.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void mpi_ec_dup_point(MPI_POINT result, MPI_POINT point, struct mpi_ec_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/mpi/ec.c (ffffffff81894b80)
Location: lib/mpi/ec.c:915
Inline: True
Direct callers:
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:add_points_weierstrass
```
**Symbols:**

```
ffffffff81894b80-ffffffff81894bf5: mpi_ec_dup_point (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void mpi_ec_dup_point(MPI_POINT result, MPI_POINT point, struct mpi_ec_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/mpi/ec.c (ffffffff818d7040)
Location: lib/mpi/ec.c:915
Inline: True
Direct callers:
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:add_points_weierstrass
```
**Symbols:**

```
ffffffff818d7040-ffffffff818d70a7: mpi_ec_dup_point (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void mpi_ec_dup_point(MPI_POINT result, MPI_POINT point, struct mpi_ec_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/crypto/mpi/ec.c (ffffffff8186dba0)
Location: lib/crypto/mpi/ec.c:918
Inline: True
Direct callers:
  - lib/crypto/mpi/ec.c:mpi_ec_mul_point
  - lib/crypto/mpi/ec.c:mpi_ec_mul_point
  - lib/crypto/mpi/ec.c:add_points_weierstrass
```
**Symbols:**

```
ffffffff8186dba0-ffffffff8186dc07: mpi_ec_dup_point (STB_LOCAL)
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
