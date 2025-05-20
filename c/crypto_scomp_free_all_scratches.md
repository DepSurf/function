# Function: <code>crypto_scomp_free_all_scratches</code>

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
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/scompress.c (ffffffff813faa24)
Location: crypto/scompress.c:110
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_unregister_scomp
  - crypto/scompress.c:crypto_register_scomp
Direct callers:
  - crypto/scompress.c:crypto_unregister_scomp
  - crypto/scompress.c:crypto_register_scomp
```
**Symbols:**

```
ffffffff813fa910-ffffffff813fa949: crypto_scomp_free_all_scratches.part.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/scompress.c (ffffffff81407332)
Location: crypto/scompress.c:111
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_unregister_scomp
  - crypto/scompress.c:crypto_register_scomp
Direct callers:
  - crypto/scompress.c:crypto_unregister_scomp
  - crypto/scompress.c:crypto_register_scomp
```
**Symbols:**

```
ffffffff81407220-ffffffff81407263: crypto_scomp_free_all_scratches.part.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (ffffffff8142fc41)
Location: crypto/scompress.c:106
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_exit_scomp_ops_async
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (ffffffff814629b1)
Location: crypto/scompress.c:106
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_exit_scomp_ops_async
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/scompress.c (ffffffff81480631)
Location: crypto/scompress.c:103
Inline: True
Inline callers:
  - crypto/scompress.c:crypto_exit_scomp_ops_async
```
</details>
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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
