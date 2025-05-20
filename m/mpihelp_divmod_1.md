# Function: <code>mpihelp_divmod_1</code>

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
mpi_limb_t mpihelp_divmod_1(mpi_ptr_t quot_ptr, mpi_ptr_t dividend_ptr, mpi_size_t dividend_size, mpi_limb_t divisor_limb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpih-div.c (ffffffff81604f30)
Location: lib/mpi/mpih-div.c:379
Inline: False
Direct callers:
  - lib/mpi/mpi-div.c:mpi_tdiv_qr
```
**Symbols:**

```
ffffffff81604f30-ffffffff81605245: mpihelp_divmod_1 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
mpi_limb_t mpihelp_divmod_1(mpi_ptr_t quot_ptr, mpi_ptr_t dividend_ptr, mpi_size_t dividend_size, mpi_limb_t divisor_limb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/mpi/mpih-div.c (ffffffff815e7ca0)
Location: lib/mpi/mpih-div.c:379
Inline: False
Direct callers:
  - lib/mpi/mpi-div.c:mpi_tdiv_qr
```
**Symbols:**

```
ffffffff815e7ca0-ffffffff815e7fad: mpihelp_divmod_1 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
mpi_limb_t mpihelp_divmod_1(mpi_ptr_t quot_ptr, mpi_ptr_t dividend_ptr, mpi_size_t dividend_size, mpi_limb_t divisor_limb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/mpi/mpih-div.c (0)
Location: lib/mpi/mpih-div.c:379
Inline: False
Direct callers:
  - lib/mpi/mpi-div.c:mpi_tdiv_qr
```
**Symbols:**

```
ffffffff81cde399-ffffffff81cde584: mpihelp_divmod_1.cold (STB_LOCAL)
ffffffff81653fa0-ffffffff8165434d: mpihelp_divmod_1 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
mpi_limb_t mpihelp_divmod_1(mpi_ptr_t quot_ptr, mpi_ptr_t dividend_ptr, mpi_size_t dividend_size, mpi_limb_t divisor_limb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/mpi/mpih-div.c (0)
Location: lib/mpi/mpih-div.c:379
Inline: False
Direct callers:
  - lib/mpi/mpi-div.c:mpi_tdiv_qr
```
**Symbols:**

```
ffffffff81ea4702-ffffffff81ea48c3: mpihelp_divmod_1.cold (STB_LOCAL)
ffffffff8176b410-ffffffff8176b7bc: mpihelp_divmod_1 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
mpi_limb_t mpihelp_divmod_1(mpi_ptr_t quot_ptr, mpi_ptr_t dividend_ptr, mpi_size_t dividend_size, mpi_limb_t divisor_limb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/mpi/mpih-div.c (0)
Location: lib/mpi/mpih-div.c:379
Inline: False
Direct callers:
  - lib/mpi/mpi-div.c:mpi_tdiv_qr
```
**Symbols:**

```
ffffffff8208d2fd-ffffffff8208d4be: mpihelp_divmod_1.cold (STB_LOCAL)
ffffffff8189aa60-ffffffff8189ae0c: mpihelp_divmod_1 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
mpi_limb_t mpihelp_divmod_1(mpi_ptr_t quot_ptr, mpi_ptr_t dividend_ptr, mpi_size_t dividend_size, mpi_limb_t divisor_limb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/mpi/mpih-div.c (0)
Location: lib/mpi/mpih-div.c:379
Inline: False
Direct callers:
  - lib/mpi/mpi-div.c:mpi_tdiv_qr
```
**Symbols:**

```
ffffffff8210d655-ffffffff8210d85c: mpihelp_divmod_1.cold (STB_LOCAL)
ffffffff818dcff0-ffffffff818dd411: mpihelp_divmod_1 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
mpi_limb_t mpihelp_divmod_1(mpi_ptr_t quot_ptr, mpi_ptr_t dividend_ptr, mpi_size_t dividend_size, mpi_limb_t divisor_limb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/crypto/mpi/mpih-div.c (0)
Location: lib/crypto/mpi/mpih-div.c:379
Inline: False
Direct callers:
  - lib/crypto/mpi/mpi-div.c:mpi_tdiv_qr
```
**Symbols:**

```
ffffffff821d7073-ffffffff821d727a: mpihelp_divmod_1.cold (STB_LOCAL)
ffffffff81873bd0-ffffffff81873fec: mpihelp_divmod_1 (STB_GLOBAL)
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
