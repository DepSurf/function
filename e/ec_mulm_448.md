# Function: <code>ec_mulm_448</code>

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
void ec_mulm_448(MPI w, MPI u, MPI v, struct mpi_ec_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/mpi/ec.c (0)
Location: lib/mpi/ec.c:346
Inline: False
Direct callers:
  - lib/mpi/ec.c:ec_pow2_448
```
**Symbols:**

```
ffffffff815fe160-ffffffff815fe4e9: ec_mulm_448 (STB_LOCAL)
ffffffff81bf4683-ffffffff81bf46b0: ec_mulm_448.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void ec_mulm_448(MPI w, MPI u, MPI v, struct mpi_ec_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/mpi/ec.c (0)
Location: lib/mpi/ec.c:346
Inline: False
Direct callers:
  - lib/mpi/ec.c:ec_pow2_448
```
**Symbols:**

```
ffffffff815e0ed0-ffffffff815e124c: ec_mulm_448 (STB_LOCAL)
ffffffff81be6576-ffffffff81be65a3: ec_mulm_448.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ec_mulm_448(MPI w, MPI u, MPI v, struct mpi_ec_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/mpi/ec.c (0)
Location: lib/mpi/ec.c:346
Inline: False
Direct callers:
  - lib/mpi/ec.c:ec_pow2_448
```
**Symbols:**

```
ffffffff8164cc80-ffffffff8164d305: ec_mulm_448 (STB_LOCAL)
ffffffff81cddf8c-ffffffff81cddfb9: ec_mulm_448.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ec_mulm_448(MPI w, MPI u, MPI v, struct mpi_ec_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/mpi/ec.c (0)
Location: lib/mpi/ec.c:346
Inline: False
Direct callers:
  - lib/mpi/ec.c:ec_pow2_448
```
**Symbols:**

```
ffffffff817638f0-ffffffff81764041: ec_mulm_448 (STB_LOCAL)
ffffffff81ea42f4-ffffffff81ea4321: ec_mulm_448.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ec_mulm_448(MPI w, MPI u, MPI v, struct mpi_ec_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/ec.c (ffffffff818928a0)
Location: lib/mpi/ec.c:346
Inline: False
Direct callers:
  - lib/mpi/ec.c:ec_pow2_448
```
**Symbols:**

```
ffffffff818928a0-ffffffff8189300e: ec_mulm_448 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ec_mulm_448(MPI w, MPI u, MPI v, struct mpi_ec_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/ec.c (ffffffff818d4d20)
Location: lib/mpi/ec.c:346
Inline: False
Direct callers:
  - lib/mpi/ec.c:ec_pow2_448
```
**Symbols:**

```
ffffffff818d4d20-ffffffff818d5499: ec_mulm_448 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ec_mulm_448(MPI w, MPI u, MPI v, struct mpi_ec_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/mpi/ec.c (ffffffff8186b840)
Location: lib/crypto/mpi/ec.c:346
Inline: False
Direct callers:
  - lib/crypto/mpi/ec.c:ec_pow2_448
```
**Symbols:**

```
ffffffff8186b840-ffffffff8186bfb9: ec_mulm_448 (STB_LOCAL)
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
