# Function: <code>ec_mulm_25519</code>

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
void ec_mulm_25519(MPI w, MPI u, MPI v, struct mpi_ec_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/mpi/ec.c (0)
Location: lib/mpi/ec.c:242
Inline: False
Direct callers:
  - lib/mpi/ec.c:ec_pow2_25519
```
**Symbols:**

```
ffffffff815fec60-ffffffff815feee3: ec_mulm_25519 (STB_LOCAL)
ffffffff81bf4734-ffffffff81bf4761: ec_mulm_25519.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void ec_mulm_25519(MPI w, MPI u, MPI v, struct mpi_ec_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/mpi/ec.c (0)
Location: lib/mpi/ec.c:242
Inline: False
Direct callers:
  - lib/mpi/ec.c:ec_pow2_25519
```
**Symbols:**

```
ffffffff815e19a0-ffffffff815e1c1a: ec_mulm_25519 (STB_LOCAL)
ffffffff81be6627-ffffffff81be6654: ec_mulm_25519.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ec_mulm_25519(MPI w, MPI u, MPI v, struct mpi_ec_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/mpi/ec.c (0)
Location: lib/mpi/ec.c:242
Inline: False
Direct callers:
  - lib/mpi/ec.c:ec_pow2_25519
```
**Symbols:**

```
ffffffff8164dbc0-ffffffff8164de3a: ec_mulm_25519 (STB_LOCAL)
ffffffff81cde03d-ffffffff81cde06a: ec_mulm_25519.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ec_mulm_25519(MPI w, MPI u, MPI v, struct mpi_ec_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/mpi/ec.c (0)
Location: lib/mpi/ec.c:242
Inline: False
Direct callers:
  - lib/mpi/ec.c:ec_pow2_25519
```
**Symbols:**

```
ffffffff81764a00-ffffffff81764cc6: ec_mulm_25519 (STB_LOCAL)
ffffffff81ea43a5-ffffffff81ea43d2: ec_mulm_25519.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ec_mulm_25519(MPI w, MPI u, MPI v, struct mpi_ec_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/ec.c (ffffffff81893ac0)
Location: lib/mpi/ec.c:242
Inline: False
Direct callers:
  - lib/mpi/ec.c:ec_pow2_25519
```
**Symbols:**

```
ffffffff81893ac0-ffffffff81893da9: ec_mulm_25519 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ec_mulm_25519(MPI w, MPI u, MPI v, struct mpi_ec_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/ec.c (ffffffff818d5f90)
Location: lib/mpi/ec.c:242
Inline: False
Direct callers:
  - lib/mpi/ec.c:ec_pow2_25519
```
**Symbols:**

```
ffffffff818d5f90-ffffffff818d6283: ec_mulm_25519 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ec_mulm_25519(MPI w, MPI u, MPI v, struct mpi_ec_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/mpi/ec.c (ffffffff8186cac0)
Location: lib/crypto/mpi/ec.c:242
Inline: False
Direct callers:
  - lib/crypto/mpi/ec.c:ec_pow2_25519
```
**Symbols:**

```
ffffffff8186cac0-ffffffff8186cdb3: ec_mulm_25519 (STB_LOCAL)
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
