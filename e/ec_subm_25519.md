# Function: <code>ec_subm_25519</code>

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
void ec_subm_25519(MPI w, MPI u, MPI v, struct mpi_ec_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/mpi/ec.c (0)
Location: lib/mpi/ec.c:221
Inline: False
```
**Symbols:**

```
ffffffff815fea40-ffffffff815feb2b: ec_subm_25519 (STB_LOCAL)
ffffffff81bf46f2-ffffffff81bf4713: ec_subm_25519.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void ec_subm_25519(MPI w, MPI u, MPI v, struct mpi_ec_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/mpi/ec.c (0)
Location: lib/mpi/ec.c:221
Inline: False
```
**Symbols:**

```
ffffffff815e1790-ffffffff815e1875: ec_subm_25519 (STB_LOCAL)
ffffffff81be65e5-ffffffff81be6606: ec_subm_25519.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ec_subm_25519(MPI w, MPI u, MPI v, struct mpi_ec_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/mpi/ec.c (0)
Location: lib/mpi/ec.c:221
Inline: False
```
**Symbols:**

```
ffffffff8164d9b0-ffffffff8164da95: ec_subm_25519 (STB_LOCAL)
ffffffff81cddffb-ffffffff81cde01c: ec_subm_25519.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ec_subm_25519(MPI w, MPI u, MPI v, struct mpi_ec_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/mpi/ec.c (0)
Location: lib/mpi/ec.c:221
Inline: False
```
**Symbols:**

```
ffffffff81764780-ffffffff81764893: ec_subm_25519 (STB_LOCAL)
ffffffff81ea4363-ffffffff81ea4384: ec_subm_25519.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ec_subm_25519(MPI w, MPI u, MPI v, struct mpi_ec_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/ec.c (ffffffff818937e0)
Location: lib/mpi/ec.c:221
Inline: False
```
**Symbols:**

```
ffffffff818937e0-ffffffff8189390e: ec_subm_25519 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ec_subm_25519(MPI w, MPI u, MPI v, struct mpi_ec_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/ec.c (ffffffff818d5c90)
Location: lib/mpi/ec.c:221
Inline: False
```
**Symbols:**

```
ffffffff818d5c90-ffffffff818d5dc8: ec_subm_25519 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ec_subm_25519(MPI w, MPI u, MPI v, struct mpi_ec_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/mpi/ec.c (ffffffff8186c7c0)
Location: lib/crypto/mpi/ec.c:221
Inline: False
```
**Symbols:**

```
ffffffff8186c7c0-ffffffff8186c8f8: ec_subm_25519 (STB_LOCAL)
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
