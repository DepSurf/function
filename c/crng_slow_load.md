# Function: <code>crng_slow_load</code>

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
In drivers/char/random.c (ffffffff81644a40)
Location: drivers/char/random.c:879
Inline: True
Inline callers:
  - drivers/char/random.c:add_device_randomness
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
In drivers/char/random.c (ffffffff81662c00)
Location: drivers/char/random.c:892
Inline: True
Inline callers:
  - drivers/char/random.c:add_device_randomness
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
In drivers/char/random.c (ffffffff8169a102)
Location: drivers/char/random.c:969
Inline: True
Inline callers:
  - drivers/char/random.c:add_device_randomness
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
In drivers/char/random.c (ffffffff816bce32)
Location: drivers/char/random.c:969
Inline: True
Inline callers:
  - drivers/char/random.c:add_device_randomness
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (ffffffff81770ab0)
Location: drivers/char/random.c:917
Inline: True
Direct callers:
  - drivers/char/random.c:add_device_randomness
```
**Symbols:**

```
ffffffff81770ab0-ffffffff81770b7e: crng_slow_load.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (ffffffff8178bb20)
Location: drivers/char/random.c:917
Inline: True
Direct callers:
  - drivers/char/random.c:add_device_randomness
```
**Symbols:**

```
ffffffff8178bb20-ffffffff8178bbee: crng_slow_load.isra.0 (STB_LOCAL)
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
In drivers/char/random.c (ffffffff8176f2be)
Location: drivers/char/random.c:907
Inline: True
Inline callers:
  - drivers/char/random.c:add_device_randomness
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
In drivers/char/random.c (ffffffff817f4afb)
Location: drivers/char/random.c:958
Inline: True
Inline callers:
  - drivers/char/random.c:add_device_randomness
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
In drivers/char/random.c (ffff8000108b17dc)
Location: drivers/char/random.c:969
Inline: True
Inline callers:
  - drivers/char/random.c:add_device_randomness
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
In drivers/char/random.c (c09a7ef4)
Location: drivers/char/random.c:969
Inline: True
Inline callers:
  - drivers/char/random.c:add_device_randomness
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
In drivers/char/random.c (c0000000009458e8)
Location: drivers/char/random.c:969
Inline: True
Inline callers:
  - drivers/char/random.c:add_device_randomness
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
In drivers/char/random.c (ffffffe0005606e0)
Location: drivers/char/random.c:969
Inline: True
Inline callers:
  - drivers/char/random.c:add_device_randomness
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
In drivers/char/random.c (ffffffff81682892)
Location: drivers/char/random.c:969
Inline: True
Inline callers:
  - drivers/char/random.c:add_device_randomness
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
In drivers/char/random.c (ffffffff8165ec02)
Location: drivers/char/random.c:969
Inline: True
Inline callers:
  - drivers/char/random.c:add_device_randomness
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
In drivers/char/random.c (ffffffff816b0c72)
Location: drivers/char/random.c:969
Inline: True
Inline callers:
  - drivers/char/random.c:add_device_randomness
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
In drivers/char/random.c (ffffffff816cb1eb)
Location: drivers/char/random.c:969
Inline: True
Inline callers:
  - drivers/char/random.c:add_device_randomness
```
</details>
</li>
</ul>

## Differences
