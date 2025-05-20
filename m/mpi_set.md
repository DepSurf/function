# Function: <code>mpi_set</code>

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
MPI mpi_set(MPI w, MPI u);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpiutil.c (ffffffff81606de0)
Location: lib/mpi/mpiutil.c:250
Inline: False
Direct callers:
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/mpi-mod.c:mpi_mod_barrett
  - lib/mpi/mpi-mod.c:mpi_mod_barrett
```
**Symbols:**

```
ffffffff81606de0-ffffffff81606e70: mpi_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
MPI mpi_set(MPI w, MPI u);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpiutil.c (ffffffff815e9b40)
Location: lib/mpi/mpiutil.c:250
Inline: False
Direct callers:
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/mpi-mod.c:mpi_mod_barrett
  - lib/mpi/mpi-mod.c:mpi_mod_barrett
```
**Symbols:**

```
ffffffff815e9b40-ffffffff815e9bd0: mpi_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
MPI mpi_set(MPI w, MPI u);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpiutil.c (ffffffff81655f20)
Location: lib/mpi/mpiutil.c:250
Inline: False
Direct callers:
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/mpi-mod.c:mpi_mod_barrett
  - lib/mpi/mpi-mod.c:mpi_mod_barrett
```
**Symbols:**

```
ffffffff81655f20-ffffffff81655fb0: mpi_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
MPI mpi_set(MPI w, MPI u);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpiutil.c (ffffffff8176d650)
Location: lib/mpi/mpiutil.c:250
Inline: False
Direct callers:
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/mpi-mod.c:mpi_mod_barrett
  - lib/mpi/mpi-mod.c:mpi_mod_barrett
```
**Symbols:**

```
ffffffff8176d650-ffffffff8176d6e5: mpi_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
MPI mpi_set(MPI w, MPI u);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpiutil.c (ffffffff8189cdf0)
Location: lib/mpi/mpiutil.c:250
Inline: False
Direct callers:
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/mpi-mod.c:mpi_mod_barrett
  - lib/mpi/mpi-mod.c:mpi_mod_barrett
```
**Symbols:**

```
ffffffff8189cdf0-ffffffff8189ce85: mpi_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
MPI mpi_set(MPI w, MPI u);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpiutil.c (ffffffff818df3b0)
Location: lib/mpi/mpiutil.c:250
Inline: False
Direct callers:
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:mpi_ec_mul_point
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:add_points_weierstrass
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/mpi-mod.c:mpi_mod_barrett
  - lib/mpi/mpi-mod.c:mpi_mod_barrett
```
**Symbols:**

```
ffffffff818df3b0-ffffffff818df445: mpi_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
MPI mpi_set(MPI w, MPI u);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/mpi/mpiutil.c (ffffffff81875fe0)
Location: lib/crypto/mpi/mpiutil.c:250
Inline: False
Direct callers:
  - lib/crypto/mpi/ec.c:mpi_ec_mul_point
  - lib/crypto/mpi/ec.c:mpi_ec_mul_point
  - lib/crypto/mpi/ec.c:mpi_ec_mul_point
  - lib/crypto/mpi/ec.c:mpi_ec_mul_point
  - lib/crypto/mpi/ec.c:mpi_ec_mul_point
  - lib/crypto/mpi/ec.c:mpi_ec_mul_point
  - lib/crypto/mpi/ec.c:mpi_ec_mul_point
  - lib/crypto/mpi/ec.c:mpi_ec_mul_point
  - lib/crypto/mpi/ec.c:mpi_ec_mul_point
  - lib/crypto/mpi/ec.c:mpi_ec_mul_point
  - lib/crypto/mpi/ec.c:mpi_ec_mul_point
  - lib/crypto/mpi/ec.c:mpi_ec_mul_point
  - lib/crypto/mpi/ec.c:mpi_ec_mul_point
  - lib/crypto/mpi/ec.c:mpi_ec_mul_point
  - lib/crypto/mpi/ec.c:add_points_weierstrass
  - lib/crypto/mpi/ec.c:add_points_weierstrass
  - lib/crypto/mpi/ec.c:add_points_weierstrass
  - lib/crypto/mpi/ec.c:add_points_weierstrass
  - lib/crypto/mpi/ec.c:add_points_weierstrass
  - lib/crypto/mpi/ec.c:add_points_weierstrass
  - lib/crypto/mpi/ec.c:add_points_weierstrass
  - lib/crypto/mpi/ec.c:add_points_weierstrass
  - lib/crypto/mpi/ec.c:mpi_ec_get_affine
  - lib/crypto/mpi/mpi-mod.c:mpi_mod_barrett
  - lib/crypto/mpi/mpi-mod.c:mpi_mod_barrett
```
**Symbols:**

```
ffffffff81875fe0-ffffffff81876075: mpi_set (STB_GLOBAL)
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
