# Function: <code>montgomery_ladder</code>

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
void montgomery_ladder(MPI_POINT prd, MPI_POINT sum, MPI_POINT p1, MPI_POINT p2, MPI dif_x, struct mpi_ec_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/ec.c (ffffffff815fdb40)
Location: lib/mpi/ec.c:1163
Inline: False
Direct callers:
  - lib/mpi/ec.c:mpi_ec_mul_point
```
**Symbols:**

```
ffffffff815fdb40-ffffffff815fdd4b: montgomery_ladder (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void montgomery_ladder(MPI_POINT prd, MPI_POINT sum, MPI_POINT p1, MPI_POINT p2, MPI dif_x, struct mpi_ec_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/ec.c (ffffffff815e08b0)
Location: lib/mpi/ec.c:1163
Inline: False
Direct callers:
  - lib/mpi/ec.c:mpi_ec_mul_point
```
**Symbols:**

```
ffffffff815e08b0-ffffffff815e0ab8: montgomery_ladder (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void montgomery_ladder(MPI_POINT prd, MPI_POINT sum, MPI_POINT p1, MPI_POINT p2, MPI dif_x, struct mpi_ec_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/ec.c (ffffffff8164c660)
Location: lib/mpi/ec.c:1163
Inline: False
Direct callers:
  - lib/mpi/ec.c:mpi_ec_mul_point
```
**Symbols:**

```
ffffffff8164c660-ffffffff8164c868: montgomery_ladder (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void montgomery_ladder(MPI_POINT prd, MPI_POINT sum, MPI_POINT p1, MPI_POINT p2, MPI dif_x, struct mpi_ec_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/ec.c (ffffffff817632b0)
Location: lib/mpi/ec.c:1163
Inline: False
Direct callers:
  - lib/mpi/ec.c:mpi_ec_mul_point
```
**Symbols:**

```
ffffffff817632b0-ffffffff817634d2: montgomery_ladder (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void montgomery_ladder(MPI_POINT prd, MPI_POINT sum, MPI_POINT p1, MPI_POINT p2, MPI dif_x, struct mpi_ec_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/ec.c (ffffffff81892200)
Location: lib/mpi/ec.c:1163
Inline: False
Direct callers:
  - lib/mpi/ec.c:mpi_ec_mul_point
```
**Symbols:**

```
ffffffff81892200-ffffffff81892422: montgomery_ladder (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void montgomery_ladder(MPI_POINT prd, MPI_POINT sum, MPI_POINT p1, MPI_POINT p2, MPI dif_x, struct mpi_ec_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/ec.c (ffffffff818d4680)
Location: lib/mpi/ec.c:1163
Inline: False
Direct callers:
  - lib/mpi/ec.c:mpi_ec_mul_point
```
**Symbols:**

```
ffffffff818d4680-ffffffff818d48a2: montgomery_ladder (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void montgomery_ladder(MPI_POINT prd, MPI_POINT sum, MPI_POINT p1, MPI_POINT p2, MPI dif_x, struct mpi_ec_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/mpi/ec.c (ffffffff8186b1a0)
Location: lib/crypto/mpi/ec.c:1166
Inline: False
Direct callers:
  - lib/crypto/mpi/ec.c:mpi_ec_mul_point
```
**Symbols:**

```
ffffffff8186b1a0-ffffffff8186b3c2: montgomery_ladder (STB_LOCAL)
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
