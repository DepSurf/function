# Function: <code>mpi_fdiv_q</code>

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
void mpi_fdiv_q(MPI quot, MPI dividend, MPI divisor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-div.c (ffffffff81603850)
Location: lib/mpi/mpi-div.c:43
Inline: False
Direct callers:
  - lib/mpi/mpi-mod.c:mpi_barrett_init
```
**Symbols:**

```
ffffffff81603850-ffffffff81603898: mpi_fdiv_q (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mpi_fdiv_q(MPI quot, MPI dividend, MPI divisor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-div.c (ffffffff815e65d0)
Location: lib/mpi/mpi-div.c:43
Inline: False
Direct callers:
  - lib/mpi/mpi-mod.c:mpi_barrett_init
```
**Symbols:**

```
ffffffff815e65d0-ffffffff815e6618: mpi_fdiv_q (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mpi_fdiv_q(MPI quot, MPI dividend, MPI divisor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-div.c (ffffffff81652820)
Location: lib/mpi/mpi-div.c:43
Inline: False
Direct callers:
  - lib/mpi/mpi-mod.c:mpi_barrett_init
```
**Symbols:**

```
ffffffff81652820-ffffffff81652868: mpi_fdiv_q (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mpi_fdiv_q(MPI quot, MPI dividend, MPI divisor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-div.c (ffffffff81769b00)
Location: lib/mpi/mpi-div.c:43
Inline: False
Direct callers:
  - lib/mpi/mpi-mod.c:mpi_barrett_init
```
**Symbols:**

```
ffffffff81769b00-ffffffff81769b54: mpi_fdiv_q (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mpi_fdiv_q(MPI quot, MPI dividend, MPI divisor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-div.c (ffffffff81899060)
Location: lib/mpi/mpi-div.c:43
Inline: False
Direct callers:
  - lib/mpi/mpi-mod.c:mpi_barrett_init
```
**Symbols:**

```
ffffffff81899060-ffffffff818990b4: mpi_fdiv_q (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mpi_fdiv_q(MPI quot, MPI dividend, MPI divisor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpi-div.c (ffffffff818db5e0)
Location: lib/mpi/mpi-div.c:43
Inline: False
Direct callers:
  - lib/mpi/mpi-mod.c:mpi_barrett_init
```
**Symbols:**

```
ffffffff818db5e0-ffffffff818db634: mpi_fdiv_q (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mpi_fdiv_q(MPI quot, MPI dividend, MPI divisor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/mpi/mpi-div.c (ffffffff818721a0)
Location: lib/crypto/mpi/mpi-div.c:43
Inline: False
Direct callers:
  - lib/crypto/mpi/mpi-mod.c:mpi_barrett_init
```
**Symbols:**

```
ffffffff818721a0-ffffffff818721f4: mpi_fdiv_q (STB_GLOBAL)
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
