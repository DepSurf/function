# Function: <code>numa_crng_init</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816470c0)
Location: drivers/char/random.c:827
Inline: True
Inline callers:
  - drivers/char/random.c:crng_reseed
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
In drivers/char/random.c (ffffffff81665560)
Location: drivers/char/random.c:840
Inline: True
Inline callers:
  - drivers/char/random.c:crng_reseed
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8169b196)
Location: drivers/char/random.c:917
Inline: True
Inline callers:
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816bdebf)
Location: drivers/char/random.c:917
Inline: True
Inline callers:
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff817723b2)
Location: drivers/char/random.c:866
Inline: True
Inline callers:
  - drivers/char/random.c:crng_reseed
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8178d422)
Location: drivers/char/random.c:866
Inline: True
Inline callers:
  - drivers/char/random.c:crng_reseed
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff817703d4)
Location: drivers/char/random.c:856
Inline: True
Inline callers:
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:rand_initialize
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff832fb6b0)
Location: drivers/char/random.c:887
Inline: True
Inline callers:
  - drivers/char/random.c:rand_initialize
```
</details>
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
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffff8000108ae928)
Location: drivers/char/random.c:917
Inline: True
Inline callers:
  - drivers/char/random.c:crng_reseed
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:922
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (c000000000946d84)
Location: drivers/char/random.c:917
Inline: True
Inline callers:
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:922
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8168392f)
Location: drivers/char/random.c:917
Inline: True
Inline callers:
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816615af)
Location: drivers/char/random.c:917
Inline: True
Inline callers:
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816b1cff)
Location: drivers/char/random.c:917
Inline: True
Inline callers:
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816cc19f)
Location: drivers/char/random.c:917
Inline: True
Inline callers:
  - drivers/char/random.c:crng_reseed
  - drivers/char/random.c:crng_initialize
```
</details>
</li>
</ul>

## Differences
