# Function: <code>mpi_barrett_free</code>

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
void mpi_barrett_free(mpi_barrett_t ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-mod.c (ffffffff81603f90)
Location: lib/mpi/mpi-mod.c:65
Inline: False
Direct callers:
  - lib/mpi/ec.c:mpi_ec_deinit
```
**Symbols:**

```
ffffffff81603f90-ffffffff81603ffe: mpi_barrett_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mpi_barrett_free(mpi_barrett_t ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-mod.c (ffffffff815e6d10)
Location: lib/mpi/mpi-mod.c:65
Inline: False
Direct callers:
  - lib/mpi/ec.c:mpi_ec_deinit
```
**Symbols:**

```
ffffffff815e6d10-ffffffff815e6d7e: mpi_barrett_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mpi_barrett_free(mpi_barrett_t ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-mod.c (ffffffff81652f60)
Location: lib/mpi/mpi-mod.c:67
Inline: False
Direct callers:
  - lib/mpi/ec.c:mpi_ec_deinit
```
**Symbols:**

```
ffffffff81652f60-ffffffff81652fce: mpi_barrett_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mpi_barrett_free(mpi_barrett_t ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-mod.c (ffffffff8176a350)
Location: lib/mpi/mpi-mod.c:67
Inline: False
Direct callers:
  - lib/mpi/ec.c:mpi_ec_deinit
```
**Symbols:**

```
ffffffff8176a350-ffffffff8176a3cf: mpi_barrett_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mpi_barrett_free(mpi_barrett_t ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-mod.c (ffffffff81899920)
Location: lib/mpi/mpi-mod.c:67
Inline: False
Direct callers:
  - lib/mpi/ec.c:mpi_ec_deinit
```
**Symbols:**

```
ffffffff81899920-ffffffff8189999f: mpi_barrett_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mpi_barrett_free(mpi_barrett_t ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-mod.c (ffffffff818dbea0)
Location: lib/mpi/mpi-mod.c:67
Inline: False
Direct callers:
  - lib/mpi/ec.c:mpi_ec_deinit
```
**Symbols:**

```
ffffffff818dbea0-ffffffff818dbf1f: mpi_barrett_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mpi_barrett_free(mpi_barrett_t ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/mpi/mpi-mod.c (ffffffff81872a90)
Location: lib/crypto/mpi/mpi-mod.c:67
Inline: False
Direct callers:
  - lib/crypto/mpi/ec.c:mpi_ec_deinit
```
**Symbols:**

```
ffffffff81872a90-ffffffff81872b0f: mpi_barrett_free (STB_GLOBAL)
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
