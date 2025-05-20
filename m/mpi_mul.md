# Function: <code>mpi_mul</code>

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
void mpi_mul(MPI w, MPI u, MPI v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-mul.c (ffffffff816041c0)
Location: lib/mpi/mpi-mul.c:16
Inline: False
Direct callers:
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
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
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/mpi-mod.c:mpi_mul_barrett
  - lib/mpi/mpi-mod.c:mpi_mod_barrett
  - lib/mpi/mpi-mod.c:mpi_mod_barrett
  - lib/mpi/mpi-mul.c:mpi_mulm
```
**Symbols:**

```
ffffffff816041c0-ffffffff8160441f: mpi_mul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mpi_mul(MPI w, MPI u, MPI v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-mul.c (ffffffff815e6f40)
Location: lib/mpi/mpi-mul.c:16
Inline: False
Direct callers:
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
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
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/mpi-mod.c:mpi_mul_barrett
  - lib/mpi/mpi-mod.c:mpi_mod_barrett
  - lib/mpi/mpi-mod.c:mpi_mod_barrett
  - lib/mpi/mpi-mul.c:mpi_mulm
```
**Symbols:**

```
ffffffff815e6f40-ffffffff815e719f: mpi_mul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mpi_mul(MPI w, MPI u, MPI v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-mul.c (ffffffff81653190)
Location: lib/mpi/mpi-mul.c:16
Inline: False
Direct callers:
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
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
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/mpi-mod.c:mpi_mul_barrett
  - lib/mpi/mpi-mod.c:mpi_mod_barrett
  - lib/mpi/mpi-mod.c:mpi_mod_barrett
  - lib/mpi/mpi-mul.c:mpi_mulm
```
**Symbols:**

```
ffffffff81653190-ffffffff816533ef: mpi_mul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mpi_mul(MPI w, MPI u, MPI v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-mul.c (ffffffff8176a5c0)
Location: lib/mpi/mpi-mul.c:16
Inline: False
Direct callers:
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
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
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/mpi-mod.c:mpi_mul_barrett
  - lib/mpi/mpi-mod.c:mpi_mod_barrett
  - lib/mpi/mpi-mod.c:mpi_mod_barrett
  - lib/mpi/mpi-mul.c:mpi_mulm
```
**Symbols:**

```
ffffffff8176a5c0-ffffffff8176a84b: mpi_mul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mpi_mul(MPI w, MPI u, MPI v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-mul.c (ffffffff81899bc0)
Location: lib/mpi/mpi-mul.c:16
Inline: False
Direct callers:
  - crypto/rsa.c:rsa_dec
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
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
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/mpi-mod.c:mpi_mul_barrett
  - lib/mpi/mpi-mod.c:mpi_mod_barrett
  - lib/mpi/mpi-mod.c:mpi_mod_barrett
  - lib/mpi/mpi-mul.c:mpi_mulm
```
**Symbols:**

```
ffffffff81899bc0-ffffffff81899e4b: mpi_mul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mpi_mul(MPI w, MPI u, MPI v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-mul.c (ffffffff818dc140)
Location: lib/mpi/mpi-mul.c:16
Inline: False
Direct callers:
  - crypto/rsa.c:rsa_dec
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
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
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/mpi-mod.c:mpi_mul_barrett
  - lib/mpi/mpi-mod.c:mpi_mod_barrett
  - lib/mpi/mpi-mod.c:mpi_mod_barrett
  - lib/mpi/mpi-mul.c:mpi_mulm
```
**Symbols:**

```
ffffffff818dc140-ffffffff818dc3cb: mpi_mul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mpi_mul(MPI w, MPI u, MPI v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/mpi/mpi-mul.c (ffffffff81872d30)
Location: lib/crypto/mpi/mpi-mul.c:16
Inline: False
Direct callers:
  - crypto/rsa.c:rsa_dec
  - lib/crypto/mpi/ec.c:mpi_ec_curve_point
  - lib/crypto/mpi/ec.c:mpi_ec_curve_point
  - lib/crypto/mpi/ec.c:mpi_ec_curve_point
  - lib/crypto/mpi/ec.c:mpi_ec_curve_point
  - lib/crypto/mpi/ec.c:mpi_ec_curve_point
  - lib/crypto/mpi/ec.c:mpi_ec_curve_point
  - lib/crypto/mpi/ec.c:mpi_ec_curve_point
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
  - lib/crypto/mpi/ec.c:dup_point_weierstrass
  - lib/crypto/mpi/ec.c:dup_point_weierstrass
  - lib/crypto/mpi/ec.c:dup_point_weierstrass
  - lib/crypto/mpi/ec.c:dup_point_weierstrass
  - lib/crypto/mpi/ec.c:dup_point_weierstrass
  - lib/crypto/mpi/ec.c:dup_point_weierstrass
  - lib/crypto/mpi/ec.c:dup_point_weierstrass
  - lib/crypto/mpi/ec.c:dup_point_weierstrass
  - lib/crypto/mpi/ec.c:mpi_ec_get_affine
  - lib/crypto/mpi/ec.c:mpi_ec_get_affine
  - lib/crypto/mpi/ec.c:mpi_ec_get_affine
  - lib/crypto/mpi/ec.c:mpi_ec_get_affine
  - lib/crypto/mpi/mpi-mod.c:mpi_mul_barrett
  - lib/crypto/mpi/mpi-mod.c:mpi_mod_barrett
  - lib/crypto/mpi/mpi-mod.c:mpi_mod_barrett
  - lib/crypto/mpi/mpi-mul.c:mpi_mulm
```
**Symbols:**

```
ffffffff81872d30-ffffffff81872fbb: mpi_mul (STB_GLOBAL)
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
