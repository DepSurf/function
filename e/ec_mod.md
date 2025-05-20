# Function: <code>ec_mod</code>

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
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/mpi/ec.c (ffffffff81600fcc)
Location: lib/mpi/ec.c:114
Inline: True
Inline callers:
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
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/mpi/ec.c (ffffffff815e3d5c)
Location: lib/mpi/ec.c:114
Inline: True
Inline callers:
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
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/mpi/ec.c (ffffffff8164ff8c)
Location: lib/mpi/ec.c:114
Inline: True
Inline callers:
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
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/mpi/ec.c (ffffffff81766f1f)
Location: lib/mpi/ec.c:114
Inline: True
Inline callers:
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
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/mpi/ec.c (ffffffff818961ef)
Location: lib/mpi/ec.c:114
Inline: True
Inline callers:
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
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/mpi/ec.c (ffffffff818d868f)
Location: lib/mpi/ec.c:114
Inline: True
Inline callers:
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
  - lib/mpi/ec.c:dup_point_weierstrass
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
  - lib/mpi/ec.c:mpi_ec_get_affine
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/crypto/mpi/ec.c (ffffffff8186f1ef)
Location: lib/crypto/mpi/ec.c:114
Inline: True
Inline callers:
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
  - lib/crypto/mpi/ec.c:dup_point_weierstrass
  - lib/crypto/mpi/ec.c:mpi_ec_get_affine
  - lib/crypto/mpi/ec.c:mpi_ec_get_affine
  - lib/crypto/mpi/ec.c:mpi_ec_get_affine
  - lib/crypto/mpi/ec.c:mpi_ec_get_affine
  - lib/crypto/mpi/ec.c:mpi_ec_get_affine
  - lib/crypto/mpi/ec.c:mpi_ec_get_affine
  - lib/crypto/mpi/ec.c:mpi_ec_get_affine
  - lib/crypto/mpi/ec.c:mpi_ec_get_affine
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
