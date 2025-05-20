# Function: <code>mpi_mod</code>

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
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void mpi_mod(MPI rem, MPI dividend, MPI divisor);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-mod.c (ffffffff8160413f)
Location: lib/mpi/mpi-mod.c:25
Inline: True
Inline callers:
  - lib/mpi/mpi-mod.c:mpi_mod_barrett
Direct callers:
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
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
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/mpi-add.c:mpi_subm
  - lib/mpi/mpi-add.c:mpi_addm
```
**Symbols:**

```
ffffffff81603eb0-ffffffff81603ec0: mpi_mod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void mpi_mod(MPI rem, MPI dividend, MPI divisor);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-mod.c (ffffffff815e6ebf)
Location: lib/mpi/mpi-mod.c:25
Inline: True
Inline callers:
  - lib/mpi/mpi-mod.c:mpi_mod_barrett
Direct callers:
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
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
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/mpi-add.c:mpi_subm
  - lib/mpi/mpi-add.c:mpi_addm
```
**Symbols:**

```
ffffffff815e6c30-ffffffff815e6c40: mpi_mod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void mpi_mod(MPI rem, MPI dividend, MPI divisor);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-mod.c (ffffffff8165310f)
Location: lib/mpi/mpi-mod.c:25
Inline: True
Inline callers:
  - lib/mpi/mpi-mod.c:mpi_mod_barrett
Direct callers:
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
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
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/mpi-add.c:mpi_subm
  - lib/mpi/mpi-add.c:mpi_addm
```
**Symbols:**

```
ffffffff81652e80-ffffffff81652e90: mpi_mod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void mpi_mod(MPI rem, MPI dividend, MPI divisor);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-mod.c (ffffffff8176a521)
Location: lib/mpi/mpi-mod.c:25
Inline: True
Inline callers:
  - lib/mpi/mpi-mod.c:mpi_mod_barrett
Direct callers:
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
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
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/mpi-add.c:mpi_subm
  - lib/mpi/mpi-add.c:mpi_addm
```
**Symbols:**

```
ffffffff8176a260-ffffffff8176a27a: mpi_mod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void mpi_mod(MPI rem, MPI dividend, MPI divisor);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-mod.c (ffffffff81899b01)
Location: lib/mpi/mpi-mod.c:25
Inline: True
Inline callers:
  - lib/mpi/mpi-mod.c:mpi_mod_barrett
Direct callers:
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
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
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/mpi-add.c:mpi_subm
  - lib/mpi/mpi-add.c:mpi_addm
```
**Symbols:**

```
ffffffff81899810-ffffffff8189982a: mpi_mod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void mpi_mod(MPI rem, MPI dividend, MPI divisor);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-mod.c (ffffffff818dc081)
Location: lib/mpi/mpi-mod.c:25
Inline: True
Inline callers:
  - lib/mpi/mpi-mod.c:mpi_mod_barrett
Direct callers:
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
  - lib/mpi/ec.c:mpi_ec_curve_point
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
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/mpi-add.c:mpi_subm
  - lib/mpi/mpi-add.c:mpi_addm
```
**Symbols:**

```
ffffffff818dbd90-ffffffff818dbdaa: mpi_mod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void mpi_mod(MPI rem, MPI dividend, MPI divisor);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/crypto/mpi/mpi-mod.c (ffffffff81872c71)
Location: lib/crypto/mpi/mpi-mod.c:25
Inline: True
Inline callers:
  - lib/crypto/mpi/mpi-mod.c:mpi_mod_barrett
Direct callers:
  - lib/crypto/mpi/ec.c:mpi_ec_curve_point
  - lib/crypto/mpi/ec.c:mpi_ec_curve_point
  - lib/crypto/mpi/ec.c:mpi_ec_curve_point
  - lib/crypto/mpi/ec.c:mpi_ec_curve_point
  - lib/crypto/mpi/ec.c:mpi_ec_curve_point
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
  - lib/crypto/mpi/ec.c:dup_point_weierstrass
  - lib/crypto/mpi/ec.c:dup_point_weierstrass
  - lib/crypto/mpi/ec.c:dup_point_weierstrass
  - lib/crypto/mpi/ec.c:mpi_ec_get_affine
  - lib/crypto/mpi/ec.c:mpi_ec_get_affine
  - lib/crypto/mpi/ec.c:mpi_ec_get_affine
  - lib/crypto/mpi/ec.c:mpi_ec_get_affine
  - lib/crypto/mpi/mpi-add.c:mpi_subm
  - lib/crypto/mpi/mpi-add.c:mpi_addm
```
**Symbols:**

```
ffffffff81872950-ffffffff8187296a: mpi_mod (STB_GLOBAL)
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
