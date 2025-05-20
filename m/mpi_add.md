# Function: <code>mpi_add</code>

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
void mpi_add(MPI w, MPI u, MPI v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-add.c (ffffffff816023d0)
Location: lib/mpi/mpi-add.c:67
Inline: False
Direct callers:
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/mpi-add.c:mpi_subm
  - lib/mpi/mpi-add.c:mpi_addm
  - lib/mpi/mpi-div.c:mpi_fdiv_qr
  - lib/mpi/mpi-div.c:mpi_fdiv_r
  - lib/mpi/mpi-div.c:mpi_fdiv_r
  - lib/mpi/mpi-mod.c:mpi_mod_barrett
```
**Symbols:**

```
ffffffff816023d0-ffffffff816026d3: mpi_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mpi_add(MPI w, MPI u, MPI v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-add.c (ffffffff815e5170)
Location: lib/mpi/mpi-add.c:67
Inline: False
Direct callers:
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/mpi-add.c:mpi_subm
  - lib/mpi/mpi-add.c:mpi_addm
  - lib/mpi/mpi-div.c:mpi_fdiv_qr
  - lib/mpi/mpi-div.c:mpi_fdiv_r
  - lib/mpi/mpi-div.c:mpi_fdiv_r
  - lib/mpi/mpi-mod.c:mpi_mod_barrett
```
**Symbols:**

```
ffffffff815e5170-ffffffff815e5470: mpi_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mpi_add(MPI w, MPI u, MPI v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-add.c (ffffffff816513a0)
Location: lib/mpi/mpi-add.c:67
Inline: False
Direct callers:
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/mpi-add.c:mpi_subm
  - lib/mpi/mpi-add.c:mpi_addm
  - lib/mpi/mpi-div.c:mpi_fdiv_qr
  - lib/mpi/mpi-div.c:mpi_fdiv_r
  - lib/mpi/mpi-div.c:mpi_fdiv_r
  - lib/mpi/mpi-mod.c:mpi_mod_barrett
```
**Symbols:**

```
ffffffff816513a0-ffffffff816516a0: mpi_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mpi_add(MPI w, MPI u, MPI v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-add.c (ffffffff81768450)
Location: lib/mpi/mpi-add.c:67
Inline: False
Direct callers:
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/mpi-add.c:mpi_subm
  - lib/mpi/mpi-add.c:mpi_addm
  - lib/mpi/mpi-div.c:mpi_fdiv_qr
  - lib/mpi/mpi-div.c:mpi_fdiv_r
  - lib/mpi/mpi-div.c:mpi_fdiv_r
  - lib/mpi/mpi-mod.c:mpi_mod_barrett
```
**Symbols:**

```
ffffffff81768450-ffffffff81768756: mpi_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mpi_add(MPI w, MPI u, MPI v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-add.c (ffffffff81897840)
Location: lib/mpi/mpi-add.c:67
Inline: False
Direct callers:
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/mpi-add.c:mpi_subm
  - lib/mpi/mpi-add.c:mpi_addm
  - lib/mpi/mpi-div.c:mpi_fdiv_qr
  - lib/mpi/mpi-div.c:mpi_fdiv_r
  - lib/mpi/mpi-div.c:mpi_fdiv_r
  - lib/mpi/mpi-mod.c:mpi_mod_barrett
```
**Symbols:**

```
ffffffff81897840-ffffffff81897b46: mpi_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mpi_add(MPI w, MPI u, MPI v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-add.c (ffffffff818d9d60)
Location: lib/mpi/mpi-add.c:67
Inline: False
Direct callers:
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/mpi-add.c:mpi_subm
  - lib/mpi/mpi-add.c:mpi_addm
  - lib/mpi/mpi-div.c:mpi_fdiv_qr
  - lib/mpi/mpi-div.c:mpi_fdiv_r
  - lib/mpi/mpi-div.c:mpi_fdiv_r
  - lib/mpi/mpi-mod.c:mpi_mod_barrett
```
**Symbols:**

```
ffffffff818d9d60-ffffffff818da066: mpi_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mpi_add(MPI w, MPI u, MPI v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/mpi/mpi-add.c (ffffffff818708c0)
Location: lib/crypto/mpi/mpi-add.c:67
Inline: False
Direct callers:
  - lib/crypto/mpi/ec.c:mpi_ec_curve_point
  - lib/crypto/mpi/ec.c:mpi_ec_curve_point
  - lib/crypto/mpi/ec.c:mpi_ec_curve_point
  - lib/crypto/mpi/ec.c:mpi_ec_curve_point
  - lib/crypto/mpi/ec.c:mpi_ec_curve_point
  - lib/crypto/mpi/ec.c:mpi_ec_curve_point
  - lib/crypto/mpi/ec.c:mpi_ec_mul_point
  - lib/crypto/mpi/ec.c:add_points_weierstrass
  - lib/crypto/mpi/ec.c:add_points_weierstrass
  - lib/crypto/mpi/ec.c:add_points_weierstrass
  - lib/crypto/mpi/ec.c:add_points_weierstrass
  - lib/crypto/mpi/ec.c:add_points_weierstrass
  - lib/crypto/mpi/ec.c:add_points_weierstrass
  - lib/crypto/mpi/ec.c:add_points_weierstrass
  - lib/crypto/mpi/ec.c:dup_point_weierstrass
  - lib/crypto/mpi/ec.c:dup_point_weierstrass
  - lib/crypto/mpi/ec.c:dup_point_weierstrass
  - lib/crypto/mpi/ec.c:dup_point_weierstrass
  - lib/crypto/mpi/ec.c:dup_point_weierstrass
  - lib/crypto/mpi/ec.c:dup_point_weierstrass
  - lib/crypto/mpi/mpi-add.c:mpi_subm
  - lib/crypto/mpi/mpi-add.c:mpi_addm
  - lib/crypto/mpi/mpi-div.c:mpi_fdiv_qr
  - lib/crypto/mpi/mpi-div.c:mpi_fdiv_r
  - lib/crypto/mpi/mpi-div.c:mpi_fdiv_r
  - lib/crypto/mpi/mpi-mod.c:mpi_mod_barrett
```
**Symbols:**

```
ffffffff818708c0-ffffffff81870bc6: mpi_add (STB_GLOBAL)
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
