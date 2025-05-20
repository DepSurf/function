# Function: <code>ec_subm_448</code>

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
void ec_subm_448(MPI w, MPI u, MPI v, struct mpi_ec_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/mpi/ec.c (0)
Location: lib/mpi/ec.c:326
Inline: False
```
**Symbols:**

```
ffffffff815fe960-ffffffff815fea36: ec_subm_448 (STB_LOCAL)
ffffffff81bf46d1-ffffffff81bf46f2: ec_subm_448.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void ec_subm_448(MPI w, MPI u, MPI v, struct mpi_ec_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/mpi/ec.c (0)
Location: lib/mpi/ec.c:326
Inline: False
```
**Symbols:**

```
ffffffff815e16b0-ffffffff815e1782: ec_subm_448 (STB_LOCAL)
ffffffff81be65c4-ffffffff81be65e5: ec_subm_448.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ec_subm_448(MPI w, MPI u, MPI v, struct mpi_ec_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/mpi/ec.c (0)
Location: lib/mpi/ec.c:326
Inline: False
```
**Symbols:**

```
ffffffff8164d8d0-ffffffff8164d9a2: ec_subm_448 (STB_LOCAL)
ffffffff81cddfda-ffffffff81cddffb: ec_subm_448.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ec_subm_448(MPI w, MPI u, MPI v, struct mpi_ec_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/mpi/ec.c (0)
Location: lib/mpi/ec.c:326
Inline: False
```
**Symbols:**

```
ffffffff81764690-ffffffff8176477a: ec_subm_448 (STB_LOCAL)
ffffffff81ea4342-ffffffff81ea4363: ec_subm_448.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ec_subm_448(MPI w, MPI u, MPI v, struct mpi_ec_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/ec.c (ffffffff81893560)
Location: lib/mpi/ec.c:326
Inline: False
```
**Symbols:**

```
ffffffff81893560-ffffffff81893667: ec_subm_448 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ec_subm_448(MPI w, MPI u, MPI v, struct mpi_ec_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/ec.c (ffffffff818d59f0)
Location: lib/mpi/ec.c:326
Inline: False
```
**Symbols:**

```
ffffffff818d59f0-ffffffff818d5b01: ec_subm_448 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ec_subm_448(MPI w, MPI u, MPI v, struct mpi_ec_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/mpi/ec.c (ffffffff8186c520)
Location: lib/crypto/mpi/ec.c:326
Inline: False
```
**Symbols:**

```
ffffffff8186c520-ffffffff8186c631: ec_subm_448 (STB_LOCAL)
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
