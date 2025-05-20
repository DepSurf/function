# Function: <code>mpi_ec_mul_point</code>

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
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void mpi_ec_mul_point(MPI_POINT result, MPI scalar, MPI_POINT point, struct mpi_ec_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/mpi/ec.c (0)
Location: lib/mpi/ec.c:1210
Inline: False
```
**Symbols:**

```
ffffffff81bf47f5-ffffffff81bf4839: mpi_ec_mul_point.cold (STB_LOCAL)
ffffffff816003f0-ffffffff81600edc: mpi_ec_mul_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void mpi_ec_mul_point(MPI_POINT result, MPI scalar, MPI_POINT point, struct mpi_ec_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/mpi/ec.c (0)
Location: lib/mpi/ec.c:1210
Inline: False
```
**Symbols:**

```
ffffffff81be66ed-ffffffff81be6731: mpi_ec_mul_point.cold (STB_LOCAL)
ffffffff815e3120-ffffffff815e3c64: mpi_ec_mul_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void mpi_ec_mul_point(MPI_POINT result, MPI scalar, MPI_POINT point, struct mpi_ec_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/mpi/ec.c (0)
Location: lib/mpi/ec.c:1210
Inline: False
```
**Symbols:**

```
ffffffff81cde103-ffffffff81cde147: mpi_ec_mul_point.cold (STB_LOCAL)
ffffffff8164f350-ffffffff8164fe94: mpi_ec_mul_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void mpi_ec_mul_point(MPI_POINT result, MPI scalar, MPI_POINT point, struct mpi_ec_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/mpi/ec.c (0)
Location: lib/mpi/ec.c:1210
Inline: False
```
**Symbols:**

```
ffffffff81ea4469-ffffffff81ea44ad: mpi_ec_mul_point.cold (STB_LOCAL)
ffffffff81766280-ffffffff81766e26: mpi_ec_mul_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mpi_ec_mul_point(MPI_POINT result, MPI scalar, MPI_POINT point, struct mpi_ec_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/ec.c (ffffffff81895510)
Location: lib/mpi/ec.c:1210
Inline: False
```
**Symbols:**

```
ffffffff81895510-ffffffff818960ee: mpi_ec_mul_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mpi_ec_mul_point(MPI_POINT result, MPI scalar, MPI_POINT point, struct mpi_ec_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/ec.c (ffffffff818d79b0)
Location: lib/mpi/ec.c:1210
Inline: False
```
**Symbols:**

```
ffffffff818d79b0-ffffffff818d858e: mpi_ec_mul_point (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mpi_ec_mul_point(MPI_POINT result, MPI scalar, MPI_POINT point, struct mpi_ec_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/mpi/ec.c (ffffffff8186e510)
Location: lib/crypto/mpi/ec.c:1213
Inline: False
```
**Symbols:**

```
ffffffff8186e510-ffffffff8186f0ee: mpi_ec_mul_point (STB_GLOBAL)
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
