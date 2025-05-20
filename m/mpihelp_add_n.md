# Function: <code>mpihelp_add_n</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
mpi_limb_t mpihelp_add_n(mpi_ptr_t res_ptr, mpi_ptr_t s1_ptr, mpi_ptr_t s2_ptr, mpi_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/generic_mpih-add1.c (ffffffff81416880)
Location: lib/mpi/generic_mpih-add1.c:34
Inline: False
Direct callers:
  - lib/mpi/mpih-div.c:mpihelp_divrem
  - lib/mpi/mpih-mul.c:mul_n_basecase
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n_basecase
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpihelp_mul
  - lib/mpi/mpih-mul.c:mpihelp_mul_karatsuba_case
  - lib/mpi/mpih-mul.c:mpihelp_mul_karatsuba_case
```
**Symbols:**

```
ffffffff81416880-ffffffff814168ca: mpihelp_add_n (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
mpi_limb_t mpihelp_add_n(mpi_ptr_t res_ptr, mpi_ptr_t s1_ptr, mpi_ptr_t s2_ptr, mpi_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/generic_mpih-add1.c (ffffffff8145e6f0)
Location: lib/mpi/generic_mpih-add1.c:34
Inline: False
Direct callers:
  - lib/mpi/mpih-div.c:mpihelp_divrem
  - lib/mpi/mpih-mul.c:mpihelp_mul
  - lib/mpi/mpih-mul.c:mpihelp_mul_karatsuba_case
  - lib/mpi/mpih-mul.c:mpihelp_mul_karatsuba_case
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n_basecase
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n_basecase
```
**Symbols:**

```
ffffffff8145e6f0-ffffffff8145e73a: mpihelp_add_n (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
mpi_limb_t mpihelp_add_n(mpi_ptr_t res_ptr, mpi_ptr_t s1_ptr, mpi_ptr_t s2_ptr, mpi_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/generic_mpih-add1.c (ffffffff8147d1c0)
Location: lib/mpi/generic_mpih-add1.c:34
Inline: False
Direct callers:
  - lib/mpi/mpih-div.c:mpihelp_divrem
  - lib/mpi/mpih-mul.c:mpihelp_mul
  - lib/mpi/mpih-mul.c:mpihelp_mul_karatsuba_case
  - lib/mpi/mpih-mul.c:mpihelp_mul_karatsuba_case
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n_basecase
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n_basecase
```
**Symbols:**

```
ffffffff8147d1c0-ffffffff8147d20a: mpihelp_add_n (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
mpi_limb_t mpihelp_add_n(mpi_ptr_t res_ptr, mpi_ptr_t s1_ptr, mpi_ptr_t s2_ptr, mpi_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/generic_mpih-add1.c (ffffffff814864a0)
Location: lib/mpi/generic_mpih-add1.c:34
Inline: False
Direct callers:
  - lib/mpi/mpih-div.c:mpihelp_divrem
  - lib/mpi/mpih-mul.c:mpihelp_mul
  - lib/mpi/mpih-mul.c:mpihelp_mul_karatsuba_case
  - lib/mpi/mpih-mul.c:mpihelp_mul_karatsuba_case
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n_basecase
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n_basecase
```
**Symbols:**

```
ffffffff814864a0-ffffffff814864ea: mpihelp_add_n (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
mpi_limb_t mpihelp_add_n(mpi_ptr_t res_ptr, mpi_ptr_t s1_ptr, mpi_ptr_t s2_ptr, mpi_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/generic_mpih-add1.c (ffffffff814c2620)
Location: lib/mpi/generic_mpih-add1.c:34
Inline: False
Direct callers:
  - lib/mpi/mpih-div.c:mpihelp_divrem
  - lib/mpi/mpih-mul.c:mpihelp_mul
  - lib/mpi/mpih-mul.c:mpihelp_mul_karatsuba_case
  - lib/mpi/mpih-mul.c:mpihelp_mul_karatsuba_case
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n_basecase
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n_basecase
```
**Symbols:**

```
ffffffff814c2620-ffffffff814c266a: mpihelp_add_n (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
mpi_limb_t mpihelp_add_n(mpi_ptr_t res_ptr, mpi_ptr_t s1_ptr, mpi_ptr_t s2_ptr, mpi_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/generic_mpih-add1.c (ffffffff814f3570)
Location: lib/mpi/generic_mpih-add1.c:34
Inline: False
Direct callers:
  - lib/mpi/mpih-div.c:mpihelp_divrem
  - lib/mpi/mpih-mul.c:mpihelp_mul
  - lib/mpi/mpih-mul.c:mpihelp_mul_karatsuba_case
  - lib/mpi/mpih-mul.c:mpihelp_mul_karatsuba_case
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n_basecase
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n_basecase
```
**Symbols:**

```
ffffffff814f3570-ffffffff814f35a5: mpihelp_add_n (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
mpi_limb_t mpihelp_add_n(mpi_ptr_t res_ptr, mpi_ptr_t s1_ptr, mpi_ptr_t s2_ptr, mpi_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/generic_mpih-add1.c (ffffffff815078a0)
Location: lib/mpi/generic_mpih-add1.c:34
Inline: False
Direct callers:
  - lib/mpi/mpih-div.c:mpihelp_divrem
  - lib/mpi/mpih-mul.c:mpihelp_mul
  - lib/mpi/mpih-mul.c:mpihelp_mul_karatsuba_case
  - lib/mpi/mpih-mul.c:mpihelp_mul_karatsuba_case
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n_basecase
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n_basecase
```
**Symbols:**

```
ffffffff815078a0-ffffffff815078d5: mpihelp_add_n (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
mpi_limb_t mpihelp_add_n(mpi_ptr_t res_ptr, mpi_ptr_t s1_ptr, mpi_ptr_t s2_ptr, mpi_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/generic_mpih-add1.c (ffffffff81535a90)
Location: lib/mpi/generic_mpih-add1.c:21
Inline: False
Direct callers:
  - lib/mpi/mpih-div.c:mpihelp_divrem
  - lib/mpi/mpih-mul.c:mpihelp_mul
  - lib/mpi/mpih-mul.c:mpihelp_mul_karatsuba_case
  - lib/mpi/mpih-mul.c:mpihelp_mul_karatsuba_case
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n_basecase
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n_basecase
```
**Symbols:**

```
ffffffff81535a90-ffffffff81535ac5: mpihelp_add_n (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
mpi_limb_t mpihelp_add_n(mpi_ptr_t res_ptr, mpi_ptr_t s1_ptr, mpi_ptr_t s2_ptr, mpi_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/generic_mpih-add1.c (ffffffff815568a0)
Location: lib/mpi/generic_mpih-add1.c:21
Inline: False
Direct callers:
  - lib/mpi/mpih-div.c:mpihelp_divrem
  - lib/mpi/mpih-mul.c:mpihelp_mul
  - lib/mpi/mpih-mul.c:mpihelp_mul_karatsuba_case
  - lib/mpi/mpih-mul.c:mpihelp_mul_karatsuba_case
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n_basecase
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n_basecase
```
**Symbols:**

```
ffffffff815568a0-ffffffff815568d5: mpihelp_add_n (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
mpi_limb_t mpihelp_add_n(mpi_ptr_t res_ptr, mpi_ptr_t s1_ptr, mpi_ptr_t s2_ptr, mpi_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/generic_mpih-add1.c (ffffffff815e0140)
Location: lib/mpi/generic_mpih-add1.c:21
Inline: False
Direct callers:
  - lib/mpi/mpih-div.c:mpihelp_divrem
  - lib/mpi/mpih-mul.c:mpihelp_mul
  - lib/mpi/mpih-mul.c:mpihelp_mul_karatsuba_case
  - lib/mpi/mpih-mul.c:mpihelp_mul_karatsuba_case
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n_basecase
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
```
**Symbols:**

```
ffffffff815e0140-ffffffff815e017e: mpihelp_add_n (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
mpi_limb_t mpihelp_add_n(mpi_ptr_t res_ptr, mpi_ptr_t s1_ptr, mpi_ptr_t s2_ptr, mpi_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/generic_mpih-add1.c (ffffffff815fd8d0)
Location: lib/mpi/generic_mpih-add1.c:21
Inline: False
Direct callers:
  - lib/mpi/ec.c:ec_mulm_448
  - lib/mpi/ec.c:ec_mulm_448
  - lib/mpi/ec.c:ec_mulm_448
  - lib/mpi/ec.c:ec_mulm_448
  - lib/mpi/ec.c:ec_mulm_448
  - lib/mpi/ec.c:ec_mulm_448
  - lib/mpi/ec.c:ec_mulm_448
  - lib/mpi/ec.c:ec_subm_448
  - lib/mpi/ec.c:ec_addm_448
  - lib/mpi/ec.c:ec_mulm_25519
  - lib/mpi/ec.c:ec_mulm_25519
  - lib/mpi/ec.c:ec_mulm_25519
  - lib/mpi/ec.c:ec_mulm_25519
  - lib/mpi/ec.c:ec_mulm_25519
  - lib/mpi/ec.c:ec_mulm_25519
  - lib/mpi/ec.c:ec_subm_25519
  - lib/mpi/ec.c:ec_addm_25519
  - lib/mpi/ec.c:ec_addm_25519
  - lib/mpi/mpi-add.c:mpi_add
  - lib/mpi/mpih-div.c:mpihelp_divrem
  - lib/mpi/mpih-mul.c:mpihelp_mul
  - lib/mpi/mpih-mul.c:mpihelp_mul_karatsuba_case
  - lib/mpi/mpih-mul.c:mpihelp_mul_karatsuba_case
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n_basecase
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
```
**Symbols:**

```
ffffffff815fd8d0-ffffffff815fd918: mpihelp_add_n (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
mpi_limb_t mpihelp_add_n(mpi_ptr_t res_ptr, mpi_ptr_t s1_ptr, mpi_ptr_t s2_ptr, mpi_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/generic_mpih-add1.c (ffffffff815e0640)
Location: lib/mpi/generic_mpih-add1.c:21
Inline: False
Direct callers:
  - lib/mpi/ec.c:ec_mulm_448
  - lib/mpi/ec.c:ec_mulm_448
  - lib/mpi/ec.c:ec_mulm_448
  - lib/mpi/ec.c:ec_mulm_448
  - lib/mpi/ec.c:ec_mulm_448
  - lib/mpi/ec.c:ec_mulm_448
  - lib/mpi/ec.c:ec_mulm_448
  - lib/mpi/ec.c:ec_subm_448
  - lib/mpi/ec.c:ec_addm_448
  - lib/mpi/ec.c:ec_mulm_25519
  - lib/mpi/ec.c:ec_mulm_25519
  - lib/mpi/ec.c:ec_mulm_25519
  - lib/mpi/ec.c:ec_mulm_25519
  - lib/mpi/ec.c:ec_mulm_25519
  - lib/mpi/ec.c:ec_mulm_25519
  - lib/mpi/ec.c:ec_subm_25519
  - lib/mpi/ec.c:ec_addm_25519
  - lib/mpi/ec.c:ec_addm_25519
  - lib/mpi/mpi-add.c:mpi_add
  - lib/mpi/mpih-div.c:mpihelp_divrem
  - lib/mpi/mpih-mul.c:mpihelp_mul
  - lib/mpi/mpih-mul.c:mpihelp_mul_karatsuba_case
  - lib/mpi/mpih-mul.c:mpihelp_mul_karatsuba_case
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n_basecase
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
```
**Symbols:**

```
ffffffff815e0640-ffffffff815e0685: mpihelp_add_n (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
mpi_limb_t mpihelp_add_n(mpi_ptr_t res_ptr, mpi_ptr_t s1_ptr, mpi_ptr_t s2_ptr, mpi_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/generic_mpih-add1.c (ffffffff8164c3f0)
Location: lib/mpi/generic_mpih-add1.c:21
Inline: False
Direct callers:
  - lib/mpi/ec.c:ec_mulm_448
  - lib/mpi/ec.c:ec_mulm_448
  - lib/mpi/ec.c:ec_mulm_448
  - lib/mpi/ec.c:ec_mulm_448
  - lib/mpi/ec.c:ec_mulm_448
  - lib/mpi/ec.c:ec_mulm_448
  - lib/mpi/ec.c:ec_mulm_448
  - lib/mpi/ec.c:ec_subm_448
  - lib/mpi/ec.c:ec_addm_448
  - lib/mpi/ec.c:ec_mulm_25519
  - lib/mpi/ec.c:ec_mulm_25519
  - lib/mpi/ec.c:ec_mulm_25519
  - lib/mpi/ec.c:ec_mulm_25519
  - lib/mpi/ec.c:ec_mulm_25519
  - lib/mpi/ec.c:ec_mulm_25519
  - lib/mpi/ec.c:ec_subm_25519
  - lib/mpi/ec.c:ec_addm_25519
  - lib/mpi/ec.c:ec_addm_25519
  - lib/mpi/mpi-add.c:mpi_add
  - lib/mpi/mpih-div.c:mpihelp_divrem
  - lib/mpi/mpih-mul.c:mpihelp_mul
  - lib/mpi/mpih-mul.c:mpihelp_mul_karatsuba_case
  - lib/mpi/mpih-mul.c:mpihelp_mul_karatsuba_case
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n_basecase
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
```
**Symbols:**

```
ffffffff8164c3f0-ffffffff8164c435: mpihelp_add_n (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
mpi_limb_t mpihelp_add_n(mpi_ptr_t res_ptr, mpi_ptr_t s1_ptr, mpi_ptr_t s2_ptr, mpi_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/generic_mpih-add1.c (ffffffff81763040)
Location: lib/mpi/generic_mpih-add1.c:21
Inline: False
Direct callers:
  - lib/mpi/ec.c:ec_mulm_448
  - lib/mpi/ec.c:ec_mulm_448
  - lib/mpi/ec.c:ec_mulm_448
  - lib/mpi/ec.c:ec_mulm_448
  - lib/mpi/ec.c:ec_mulm_448
  - lib/mpi/ec.c:ec_mulm_448
  - lib/mpi/ec.c:ec_mulm_448
  - lib/mpi/ec.c:ec_subm_448
  - lib/mpi/ec.c:ec_addm_448
  - lib/mpi/ec.c:ec_mulm_25519
  - lib/mpi/ec.c:ec_mulm_25519
  - lib/mpi/ec.c:ec_mulm_25519
  - lib/mpi/ec.c:ec_mulm_25519
  - lib/mpi/ec.c:ec_mulm_25519
  - lib/mpi/ec.c:ec_mulm_25519
  - lib/mpi/ec.c:ec_subm_25519
  - lib/mpi/ec.c:ec_addm_25519
  - lib/mpi/ec.c:ec_addm_25519
  - lib/mpi/mpi-add.c:mpi_add
  - lib/mpi/mpih-div.c:mpihelp_divrem
  - lib/mpi/mpih-mul.c:mpihelp_mul
  - lib/mpi/mpih-mul.c:mpihelp_mul_karatsuba_case
  - lib/mpi/mpih-mul.c:mpihelp_mul_karatsuba_case
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n_basecase
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
```
**Symbols:**

```
ffffffff81763040-ffffffff8176309d: mpihelp_add_n (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
mpi_limb_t mpihelp_add_n(mpi_ptr_t res_ptr, mpi_ptr_t s1_ptr, mpi_ptr_t s2_ptr, mpi_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/generic_mpih-add1.c (ffffffff81891f70)
Location: lib/mpi/generic_mpih-add1.c:21
Inline: False
Direct callers:
  - lib/mpi/ec.c:ec_mulm_448
  - lib/mpi/ec.c:ec_mulm_448
  - lib/mpi/ec.c:ec_mulm_448
  - lib/mpi/ec.c:ec_mulm_448
  - lib/mpi/ec.c:ec_mulm_448
  - lib/mpi/ec.c:ec_mulm_448
  - lib/mpi/ec.c:ec_mulm_448
  - lib/mpi/ec.c:ec_subm_448
  - lib/mpi/ec.c:ec_addm_448
  - lib/mpi/ec.c:ec_mulm_25519
  - lib/mpi/ec.c:ec_mulm_25519
  - lib/mpi/ec.c:ec_mulm_25519
  - lib/mpi/ec.c:ec_mulm_25519
  - lib/mpi/ec.c:ec_mulm_25519
  - lib/mpi/ec.c:ec_mulm_25519
  - lib/mpi/ec.c:ec_subm_25519
  - lib/mpi/ec.c:ec_addm_25519
  - lib/mpi/ec.c:ec_addm_25519
  - lib/mpi/mpi-add.c:mpi_add
  - lib/mpi/mpih-div.c:mpihelp_divrem
  - lib/mpi/mpih-mul.c:mpihelp_mul
  - lib/mpi/mpih-mul.c:mpihelp_mul_karatsuba_case
  - lib/mpi/mpih-mul.c:mpihelp_mul_karatsuba_case
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n_basecase
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
```
**Symbols:**

```
ffffffff81891f70-ffffffff81891fcd: mpihelp_add_n (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
mpi_limb_t mpihelp_add_n(mpi_ptr_t res_ptr, mpi_ptr_t s1_ptr, mpi_ptr_t s2_ptr, mpi_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/generic_mpih-add1.c (ffffffff818d43f0)
Location: lib/mpi/generic_mpih-add1.c:21
Inline: False
Direct callers:
  - lib/mpi/ec.c:ec_mulm_448
  - lib/mpi/ec.c:ec_mulm_448
  - lib/mpi/ec.c:ec_mulm_448
  - lib/mpi/ec.c:ec_mulm_448
  - lib/mpi/ec.c:ec_mulm_448
  - lib/mpi/ec.c:ec_mulm_448
  - lib/mpi/ec.c:ec_mulm_448
  - lib/mpi/ec.c:ec_subm_448
  - lib/mpi/ec.c:ec_addm_448
  - lib/mpi/ec.c:ec_mulm_25519
  - lib/mpi/ec.c:ec_mulm_25519
  - lib/mpi/ec.c:ec_mulm_25519
  - lib/mpi/ec.c:ec_mulm_25519
  - lib/mpi/ec.c:ec_mulm_25519
  - lib/mpi/ec.c:ec_mulm_25519
  - lib/mpi/ec.c:ec_subm_25519
  - lib/mpi/ec.c:ec_addm_25519
  - lib/mpi/ec.c:ec_addm_25519
  - lib/mpi/mpi-add.c:mpi_add
  - lib/mpi/mpih-div.c:mpihelp_divrem
  - lib/mpi/mpih-mul.c:mpihelp_mul
  - lib/mpi/mpih-mul.c:mpihelp_mul_karatsuba_case
  - lib/mpi/mpih-mul.c:mpihelp_mul_karatsuba_case
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n_basecase
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
```
**Symbols:**

```
ffffffff818d43f0-ffffffff818d444d: mpihelp_add_n (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
mpi_limb_t mpihelp_add_n(mpi_ptr_t res_ptr, mpi_ptr_t s1_ptr, mpi_ptr_t s2_ptr, mpi_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/mpi/generic_mpih-add1.c (ffffffff8186af10)
Location: lib/crypto/mpi/generic_mpih-add1.c:21
Inline: False
Direct callers:
  - lib/crypto/mpi/ec.c:ec_mulm_448
  - lib/crypto/mpi/ec.c:ec_mulm_448
  - lib/crypto/mpi/ec.c:ec_mulm_448
  - lib/crypto/mpi/ec.c:ec_mulm_448
  - lib/crypto/mpi/ec.c:ec_mulm_448
  - lib/crypto/mpi/ec.c:ec_mulm_448
  - lib/crypto/mpi/ec.c:ec_mulm_448
  - lib/crypto/mpi/ec.c:ec_subm_448
  - lib/crypto/mpi/ec.c:ec_addm_448
  - lib/crypto/mpi/ec.c:ec_mulm_25519
  - lib/crypto/mpi/ec.c:ec_mulm_25519
  - lib/crypto/mpi/ec.c:ec_mulm_25519
  - lib/crypto/mpi/ec.c:ec_mulm_25519
  - lib/crypto/mpi/ec.c:ec_mulm_25519
  - lib/crypto/mpi/ec.c:ec_mulm_25519
  - lib/crypto/mpi/ec.c:ec_subm_25519
  - lib/crypto/mpi/ec.c:ec_addm_25519
  - lib/crypto/mpi/ec.c:ec_addm_25519
  - lib/crypto/mpi/mpi-add.c:mpi_add
  - lib/crypto/mpi/mpih-div.c:mpihelp_divrem
  - lib/crypto/mpi/mpih-mul.c:mpihelp_mul
  - lib/crypto/mpi/mpih-mul.c:mpihelp_mul_karatsuba_case
  - lib/crypto/mpi/mpih-mul.c:mpihelp_mul_karatsuba_case
  - lib/crypto/mpi/mpih-mul.c:mpih_sqr_n
  - lib/crypto/mpi/mpih-mul.c:mpih_sqr_n
  - lib/crypto/mpi/mpih-mul.c:mpih_sqr_n
  - lib/crypto/mpi/mpih-mul.c:mpih_sqr_n
  - lib/crypto/mpi/mpih-mul.c:mpih_sqr_n
  - lib/crypto/mpi/mpih-mul.c:mpih_sqr_n_basecase
  - lib/crypto/mpi/mpih-mul.c:mul_n
  - lib/crypto/mpi/mpih-mul.c:mul_n
  - lib/crypto/mpi/mpih-mul.c:mul_n
  - lib/crypto/mpi/mpih-mul.c:mul_n
  - lib/crypto/mpi/mpih-mul.c:mul_n
```
**Symbols:**

```
ffffffff8186af10-ffffffff8186af6d: mpihelp_add_n (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
mpi_limb_t mpihelp_add_n(mpi_ptr_t res_ptr, mpi_ptr_t s1_ptr, mpi_ptr_t s2_ptr, mpi_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/generic_mpih-add1.c (ffff8000106630a8)
Location: lib/mpi/generic_mpih-add1.c:21
Inline: False
Direct callers:
  - lib/mpi/mpih-div.c:mpihelp_divrem
  - lib/mpi/mpih-mul.c:mpihelp_mul
  - lib/mpi/mpih-mul.c:mpihelp_mul_karatsuba_case
  - lib/mpi/mpih-mul.c:mpihelp_mul_karatsuba_case
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n_basecase
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n_basecase
```
**Symbols:**

```
ffff8000106630a8-ffff8000106630f0: mpihelp_add_n (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
mpi_limb_t mpihelp_add_n(mpi_ptr_t res_ptr, mpi_ptr_t s1_ptr, mpi_ptr_t s2_ptr, mpi_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/generic_mpih-add1.c (c080bc70)
Location: lib/mpi/generic_mpih-add1.c:21
Inline: False
Direct callers:
  - lib/mpi/mpih-div.c:mpihelp_divrem
  - lib/mpi/mpih-mul.c:mpihelp_mul
  - lib/mpi/mpih-mul.c:mpihelp_mul_karatsuba_case
  - lib/mpi/mpih-mul.c:mpihelp_mul_karatsuba_case
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n_basecase
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n_basecase
```
**Symbols:**

```
c080bc70-c080bcc4: mpihelp_add_n (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
mpi_limb_t mpihelp_add_n(mpi_ptr_t res_ptr, mpi_ptr_t s1_ptr, mpi_ptr_t s2_ptr, mpi_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/generic_mpih-add1.c (c000000000817700)
Location: lib/mpi/generic_mpih-add1.c:21
Inline: False
Direct callers:
  - lib/mpi/mpih-div.c:mpihelp_divrem
  - lib/mpi/mpih-mul.c:mpihelp_mul
  - lib/mpi/mpih-mul.c:mpihelp_mul_karatsuba_case
  - lib/mpi/mpih-mul.c:mpihelp_mul_karatsuba_case
  - lib/mpi/mpih-mul.c:mpihelp_mul_karatsuba_case
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n_basecase
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n_basecase
```
**Symbols:**

```
c000000000817700-c00000000081776c: mpihelp_add_n (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
mpi_limb_t mpihelp_add_n(mpi_ptr_t res_ptr, mpi_ptr_t s1_ptr, mpi_ptr_t s2_ptr, mpi_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/generic_mpih-add1.c (ffffffe00048f78a)
Location: lib/mpi/generic_mpih-add1.c:21
Inline: False
Direct callers:
  - lib/mpi/mpih-div.c:mpihelp_divrem
  - lib/mpi/mpih-mul.c:mpihelp_mul
  - lib/mpi/mpih-mul.c:mpihelp_mul_karatsuba_case
  - lib/mpi/mpih-mul.c:mpihelp_mul_karatsuba_case
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n_basecase
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n_basecase
```
**Symbols:**

```
ffffffe00048f78a-ffffffe00048f7ce: mpihelp_add_n (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
mpi_limb_t mpihelp_add_n(mpi_ptr_t res_ptr, mpi_ptr_t s1_ptr, mpi_ptr_t s2_ptr, mpi_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/generic_mpih-add1.c (ffffffff8154ee80)
Location: lib/mpi/generic_mpih-add1.c:21
Inline: False
Direct callers:
  - lib/mpi/mpih-div.c:mpihelp_divrem
  - lib/mpi/mpih-mul.c:mpihelp_mul
  - lib/mpi/mpih-mul.c:mpihelp_mul_karatsuba_case
  - lib/mpi/mpih-mul.c:mpihelp_mul_karatsuba_case
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n_basecase
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n_basecase
```
**Symbols:**

```
ffffffff8154ee80-ffffffff8154eeb5: mpihelp_add_n (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
mpi_limb_t mpihelp_add_n(mpi_ptr_t res_ptr, mpi_ptr_t s1_ptr, mpi_ptr_t s2_ptr, mpi_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/generic_mpih-add1.c (ffffffff8153f160)
Location: lib/mpi/generic_mpih-add1.c:21
Inline: False
Direct callers:
  - lib/mpi/mpih-div.c:mpihelp_divrem
  - lib/mpi/mpih-mul.c:mpihelp_mul
  - lib/mpi/mpih-mul.c:mpihelp_mul_karatsuba_case
  - lib/mpi/mpih-mul.c:mpihelp_mul_karatsuba_case
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n_basecase
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n_basecase
```
**Symbols:**

```
ffffffff8153f160-ffffffff8153f195: mpihelp_add_n (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
mpi_limb_t mpihelp_add_n(mpi_ptr_t res_ptr, mpi_ptr_t s1_ptr, mpi_ptr_t s2_ptr, mpi_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/generic_mpih-add1.c (ffffffff8154abc0)
Location: lib/mpi/generic_mpih-add1.c:21
Inline: False
Direct callers:
  - lib/mpi/mpih-div.c:mpihelp_divrem
  - lib/mpi/mpih-mul.c:mpihelp_mul
  - lib/mpi/mpih-mul.c:mpihelp_mul_karatsuba_case
  - lib/mpi/mpih-mul.c:mpihelp_mul_karatsuba_case
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n_basecase
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n_basecase
```
**Symbols:**

```
ffffffff8154abc0-ffffffff8154abf5: mpihelp_add_n (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
mpi_limb_t mpihelp_add_n(mpi_ptr_t res_ptr, mpi_ptr_t s1_ptr, mpi_ptr_t s2_ptr, mpi_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/generic_mpih-add1.c (ffffffff81564a10)
Location: lib/mpi/generic_mpih-add1.c:21
Inline: False
Direct callers:
  - lib/mpi/mpih-div.c:mpihelp_divrem
  - lib/mpi/mpih-mul.c:mpihelp_mul
  - lib/mpi/mpih-mul.c:mpihelp_mul_karatsuba_case
  - lib/mpi/mpih-mul.c:mpihelp_mul_karatsuba_case
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n
  - lib/mpi/mpih-mul.c:mpih_sqr_n_basecase
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n
  - lib/mpi/mpih-mul.c:mul_n_basecase
```
**Symbols:**

```
ffffffff81564a10-ffffffff81564a45: mpihelp_add_n (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
