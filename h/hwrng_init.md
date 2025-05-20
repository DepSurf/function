# Function: <code>hwrng_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/hw_random/core.c (ffffffff8151aa8b)
Location: drivers/char/hw_random/core.c:162
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/hw_random/core.c (ffffffff8156d7bb)
Location: drivers/char/hw_random/core.c:162
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/hw_random/core.c (ffffffff81599f1f)
Location: drivers/char/hw_random/core.c:162
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/hw_random/core.c (ffffffff815adeff)
Location: drivers/char/hw_random/core.c:138
Inline: True
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
In drivers/char/hw_random/core.c (ffffffff816148ff)
Location: drivers/char/hw_random/core.c:141
Inline: True
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
In drivers/char/hw_random/core.c (ffffffff8164e525)
Location: drivers/char/hw_random/core.c:141
Inline: True
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
In drivers/char/hw_random/core.c (ffffffff8166c7b5)
Location: drivers/char/hw_random/core.c:141
Inline: True
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
In drivers/char/hw_random/core.c (ffffffff816a23a9)
Location: drivers/char/hw_random/core.c:141
Inline: True
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
In drivers/char/hw_random/core.c (ffffffff816c5143)
Location: drivers/char/hw_random/core.c:141
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int hwrng_init(struct hwrng *rng);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/hw_random/core.c (0)
Location: drivers/char/hw_random/core.c:147
Inline: False
```
**Symbols:**

```
ffffffff817791a0-ffffffff817792cc: hwrng_init (STB_LOCAL)
ffffffff81779fa3-ffffffff81779fc8: hwrng_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int hwrng_init(struct hwrng *rng);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/hw_random/core.c (0)
Location: drivers/char/hw_random/core.c:147
Inline: False
```
**Symbols:**

```
ffffffff817939b0-ffffffff81793acd: hwrng_init (STB_LOCAL)
ffffffff81c08c16-ffffffff81c08c3b: hwrng_init.cold (STB_LOCAL)
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
In drivers/char/hw_random/core.c (ffffffff81776b73)
Location: drivers/char/hw_random/core.c:147
Inline: True
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
In drivers/char/hw_random/core.c (ffffffff817fc543)
Location: drivers/char/hw_random/core.c:147
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:set_current_rng
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/hw_random/core.c (ffffffff8193b1a1)
Location: drivers/char/hw_random/core.c:147
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:set_current_rng
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/hw_random/core.c (ffffffff81a9b861)
Location: drivers/char/hw_random/core.c:158
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/hw_random/core.c (ffffffff81ae71c1)
Location: drivers/char/hw_random/core.c:158
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/hw_random/core.c (ffffffff81b3a591)
Location: drivers/char/hw_random/core.c:160
Inline: True
```
</details>
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
In drivers/char/hw_random/core.c (ffff8000108b71a4)
Location: drivers/char/hw_random/core.c:141
Inline: True
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
In drivers/char/hw_random/core.c (c09b0e58)
Location: drivers/char/hw_random/core.c:141
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
In drivers/char/hw_random/core.c (c0000000009514d4)
Location: drivers/char/hw_random/core.c:141
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:set_current_rng
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
In drivers/char/hw_random/core.c (ffffffe000567f02)
Location: drivers/char/hw_random/core.c:141
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
In drivers/char/hw_random/core.c (ffffffff8168ab93)
Location: drivers/char/hw_random/core.c:141
Inline: True
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
In drivers/char/hw_random/core.c (ffffffff81668593)
Location: drivers/char/hw_random/core.c:141
Inline: True
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
In drivers/char/hw_random/core.c (ffffffff816b8e03)
Location: drivers/char/hw_random/core.c:141
Inline: True
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
In drivers/char/hw_random/core.c (ffffffff816d33d3)
Location: drivers/char/hw_random/core.c:141
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
