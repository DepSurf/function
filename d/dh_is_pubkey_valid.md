# Function: <code>dh_is_pubkey_valid</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/dh.c (ffffffff8147e12e)
Location: crypto/dh.c:113
Inline: True
Inline callers:
  - crypto/dh.c:dh_compute_value
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
In crypto/dh.c (ffffffff814ac44d)
Location: crypto/dh.c:109
Inline: True
Inline callers:
  - crypto/dh.c:dh_compute_value
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
In crypto/dh.c (ffffffff814c70fd)
Location: crypto/dh.c:109
Inline: True
Inline callers:
  - crypto/dh.c:dh_compute_value
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dh_is_pubkey_valid(struct dh_ctx *ctx, MPI y);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/dh.c (ffffffff81526230)
Location: crypto/dh.c:109
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
```
**Symbols:**

```
ffffffff81526230-ffffffff815262fc: dh_is_pubkey_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dh_is_pubkey_valid(struct dh_ctx *ctx, MPI y);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/dh.c (ffffffff815431d0)
Location: crypto/dh.c:110
Inline: False
Direct callers:
  - crypto/dh.c:dh_compute_value
```
**Symbols:**

```
ffffffff815431d0-ffffffff8154329c: dh_is_pubkey_valid (STB_LOCAL)
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
In crypto/dh.c (ffffffff8154b8dd)
Location: crypto/dh.c:110
Inline: True
Inline callers:
  - crypto/dh.c:dh_compute_value
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
In crypto/dh.c (ffffffff815ac0bd)
Location: crypto/dh.c:110
Inline: True
Inline callers:
  - crypto/dh.c:dh_compute_value
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
In crypto/dh.c (ffffffff81653cd2)
Location: crypto/dh.c:107
Inline: True
Inline callers:
  - crypto/dh.c:dh_compute_value
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
In crypto/dh.c (ffffffff8170dac2)
Location: crypto/dh.c:107
Inline: True
Inline callers:
  - crypto/dh.c:dh_compute_value
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
In crypto/dh.c (ffffffff81748332)
Location: crypto/dh.c:107
Inline: True
Inline callers:
  - crypto/dh.c:dh_compute_value
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
In crypto/dh.c (ffffffff8178a1a2)
Location: crypto/dh.c:107
Inline: True
Inline callers:
  - crypto/dh.c:dh_compute_value
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
In crypto/dh.c (ffff8000105c27f8)
Location: crypto/dh.c:109
Inline: True
Inline callers:
  - crypto/dh.c:dh_compute_value
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
In crypto/dh.c (c076fae0)
Location: crypto/dh.c:109
Inline: True
Inline callers:
  - crypto/dh.c:dh_compute_value
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
In crypto/dh.c (c00000000074b0c4)
Location: crypto/dh.c:109
Inline: True
Inline callers:
  - crypto/dh.c:dh_compute_value
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
In crypto/dh.c (ffffffe0004071dc)
Location: crypto/dh.c:109
Inline: True
Inline callers:
  - crypto/dh.c:dh_compute_value
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
In crypto/dh.c (ffffffff814bf6dd)
Location: crypto/dh.c:109
Inline: True
Inline callers:
  - crypto/dh.c:dh_compute_value
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
In crypto/dh.c (ffffffff814b00fd)
Location: crypto/dh.c:109
Inline: True
Inline callers:
  - crypto/dh.c:dh_compute_value
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
In crypto/dh.c (ffffffff814bb76d)
Location: crypto/dh.c:109
Inline: True
Inline callers:
  - crypto/dh.c:dh_compute_value
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
In crypto/dh.c (ffffffff814d423d)
Location: crypto/dh.c:109
Inline: True
Inline callers:
  - crypto/dh.c:dh_compute_value
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
