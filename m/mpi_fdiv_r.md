# Function: <code>mpi_fdiv_r</code>

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
void mpi_fdiv_r(MPI rem, MPI dividend, MPI divisor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-div.c (ffffffff816038c0)
Location: lib/mpi/mpi-div.c:20
Inline: False
Direct callers:
  - lib/mpi/mpi-mod.c:mpi_mod_barrett
```
**Symbols:**

```
ffffffff816038c0-ffffffff81603985: mpi_fdiv_r (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mpi_fdiv_r(MPI rem, MPI dividend, MPI divisor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-div.c (ffffffff815e6640)
Location: lib/mpi/mpi-div.c:20
Inline: False
Direct callers:
  - lib/mpi/mpi-mod.c:mpi_mod_barrett
```
**Symbols:**

```
ffffffff815e6640-ffffffff815e6705: mpi_fdiv_r (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mpi_fdiv_r(MPI rem, MPI dividend, MPI divisor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-div.c (ffffffff81652890)
Location: lib/mpi/mpi-div.c:20
Inline: False
Direct callers:
  - lib/mpi/mpi-mod.c:mpi_mod_barrett
```
**Symbols:**

```
ffffffff81652890-ffffffff81652955: mpi_fdiv_r (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mpi_fdiv_r(MPI rem, MPI dividend, MPI divisor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-div.c (ffffffff81769b90)
Location: lib/mpi/mpi-div.c:20
Inline: False
Direct callers:
  - lib/mpi/mpi-mod.c:mpi_mod_barrett
```
**Symbols:**

```
ffffffff81769b90-ffffffff81769c89: mpi_fdiv_r (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mpi_fdiv_r(MPI rem, MPI dividend, MPI divisor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-div.c (ffffffff81899110)
Location: lib/mpi/mpi-div.c:20
Inline: False
Direct callers:
  - lib/mpi/mpi-mod.c:mpi_mod_barrett
```
**Symbols:**

```
ffffffff81899110-ffffffff81899209: mpi_fdiv_r (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mpi_fdiv_r(MPI rem, MPI dividend, MPI divisor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-div.c (ffffffff818db690)
Location: lib/mpi/mpi-div.c:20
Inline: False
Direct callers:
  - lib/mpi/mpi-mod.c:mpi_mod_barrett
```
**Symbols:**

```
ffffffff818db690-ffffffff818db789: mpi_fdiv_r (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mpi_fdiv_r(MPI rem, MPI dividend, MPI divisor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/mpi/mpi-div.c (ffffffff81872250)
Location: lib/crypto/mpi/mpi-div.c:20
Inline: False
Direct callers:
  - lib/crypto/mpi/mpi-mod.c:mpi_mod_barrett
```
**Symbols:**

```
ffffffff81872250-ffffffff81872349: mpi_fdiv_r (STB_GLOBAL)
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
