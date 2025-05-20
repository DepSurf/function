# Function: <code>be128_xor</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/gf128mul.c (ffffffff813e677c)
Location: include/crypto/b128ops.h:70
Inline: True
Inline callers:
  - crypto/gf128mul.c:gf128mul_4k_bbe
  - crypto/gf128mul.c:gf128mul_4k_lle
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_64k_bbe
  - crypto/gf128mul.c:gf128mul_64k_lle
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_init_64k_lle
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
```
```
In crypto/xts.c (ffffffff813e8251)
Location: include/crypto/b128ops.h:70
Inline: True
Inline callers:
  - crypto/xts.c:xts_crypt
  - crypto/xts.c:xts_crypt
  - crypto/xts.c:crypt
  - crypto/xts.c:crypt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/gf128mul.c (ffffffff813ff74c)
Location: include/crypto/b128ops.h:70
Inline: True
Inline callers:
  - crypto/gf128mul.c:gf128mul_4k_bbe
  - crypto/gf128mul.c:gf128mul_4k_lle
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_64k_bbe
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
```
```
In crypto/xts.c (ffffffff81400fd1)
Location: include/crypto/b128ops.h:70
Inline: True
Inline callers:
  - crypto/xts.c:xts_crypt
  - crypto/xts.c:xts_crypt
  - crypto/xts.c:pre_crypt
  - crypto/xts.c:post_crypt
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
In crypto/gf128mul.c (ffffffff8140c596)
Location: include/crypto/b128ops.h:70
Inline: True
Inline callers:
  - crypto/gf128mul.c:gf128mul_4k_bbe
  - crypto/gf128mul.c:gf128mul_4k_lle
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_64k_bbe
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
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
In crypto/gf128mul.c (ffffffff81434ff6)
Location: include/crypto/b128ops.h:70
Inline: True
Inline callers:
  - crypto/gf128mul.c:gf128mul_4k_bbe
  - crypto/gf128mul.c:gf128mul_4k_lle
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_64k_bbe
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
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
In crypto/gf128mul.c (ffffffff81467b99)
Location: include/crypto/b128ops.h:70
Inline: True
Inline callers:
  - crypto/gf128mul.c:gf128mul_4k_bbe
  - crypto/gf128mul.c:gf128mul_4k_lle
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_64k_bbe
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
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
In crypto/gf128mul.c (ffffffff81485809)
Location: include/crypto/b128ops.h:70
Inline: True
Inline callers:
  - crypto/gf128mul.c:gf128mul_4k_bbe
  - crypto/gf128mul.c:gf128mul_4k_lle
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_64k_bbe
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
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
In crypto/gf128mul.c (ffffffff814b3a15)
Location: include/crypto/b128ops.h:70
Inline: True
Inline callers:
  - crypto/gf128mul.c:gf128mul_4k_bbe
  - crypto/gf128mul.c:gf128mul_4k_lle
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_64k_bbe
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
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
In crypto/gf128mul.c (ffffffff814cc785)
Location: include/crypto/b128ops.h:70
Inline: True
Inline callers:
  - crypto/gf128mul.c:gf128mul_4k_bbe
  - crypto/gf128mul.c:gf128mul_4k_lle
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_64k_bbe
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
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
In crypto/gf128mul.c (ffffffff8152c31b)
Location: include/crypto/b128ops.h:70
Inline: True
Inline callers:
  - crypto/gf128mul.c:gf128mul_4k_bbe
  - crypto/gf128mul.c:gf128mul_4k_lle
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_64k_bbe
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
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
In crypto/gf128mul.c (ffffffff8154930b)
Location: include/crypto/b128ops.h:70
Inline: True
Inline callers:
  - crypto/gf128mul.c:gf128mul_4k_bbe
  - crypto/gf128mul.c:gf128mul_4k_lle
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_64k_bbe
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
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
In crypto/gf128mul.c (ffffffff815519f8)
Location: include/crypto/b128ops.h:70
Inline: True
Inline callers:
  - crypto/gf128mul.c:gf128mul_4k_bbe
  - crypto/gf128mul.c:gf128mul_4k_lle
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_64k_bbe
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
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
In crypto/gf128mul.c (ffffffff815b2a02)
Location: include/crypto/b128ops.h:70
Inline: True
Inline callers:
  - crypto/gf128mul.c:gf128mul_4k_bbe
  - crypto/gf128mul.c:gf128mul_4k_lle
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_64k_bbe
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
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
In crypto/gf128mul.c (ffffffff8165b518)
Location: include/crypto/b128ops.h:70
Inline: True
Inline callers:
  - crypto/gf128mul.c:gf128mul_4k_bbe
  - crypto/gf128mul.c:gf128mul_4k_lle
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_64k_bbe
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
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
In lib/crypto/gf128mul.c (ffffffff817e1b28)
Location: include/crypto/b128ops.h:70
Inline: True
Inline callers:
  - lib/crypto/gf128mul.c:gf128mul_4k_bbe
  - lib/crypto/gf128mul.c:gf128mul_4k_lle
  - lib/crypto/gf128mul.c:gf128mul_init_4k_bbe
  - lib/crypto/gf128mul.c:gf128mul_init_4k_lle
  - lib/crypto/gf128mul.c:gf128mul_64k_bbe
  - lib/crypto/gf128mul.c:gf128mul_init_64k_bbe
  - lib/crypto/gf128mul.c:gf128mul_bbe
  - lib/crypto/gf128mul.c:gf128mul_bbe
  - lib/crypto/gf128mul.c:gf128mul_bbe
  - lib/crypto/gf128mul.c:gf128mul_bbe
  - lib/crypto/gf128mul.c:gf128mul_bbe
  - lib/crypto/gf128mul.c:gf128mul_bbe
  - lib/crypto/gf128mul.c:gf128mul_bbe
  - lib/crypto/gf128mul.c:gf128mul_bbe
  - lib/crypto/gf128mul.c:gf128mul_lle
  - lib/crypto/gf128mul.c:gf128mul_lle
  - lib/crypto/gf128mul.c:gf128mul_lle
  - lib/crypto/gf128mul.c:gf128mul_lle
  - lib/crypto/gf128mul.c:gf128mul_lle
  - lib/crypto/gf128mul.c:gf128mul_lle
  - lib/crypto/gf128mul.c:gf128mul_lle
  - lib/crypto/gf128mul.c:gf128mul_lle
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
In lib/crypto/gf128mul.c (ffffffff818214d1)
Location: include/crypto/b128ops.h:60
Inline: True
Inline callers:
  - lib/crypto/gf128mul.c:gf128mul_4k_bbe
  - lib/crypto/gf128mul.c:gf128mul_4k_lle
  - lib/crypto/gf128mul.c:gf128mul_init_4k_bbe
  - lib/crypto/gf128mul.c:gf128mul_init_4k_lle
  - lib/crypto/gf128mul.c:gf128mul_64k_bbe
  - lib/crypto/gf128mul.c:gf128mul_init_64k_bbe
  - lib/crypto/gf128mul.c:gf128mul_bbe
  - lib/crypto/gf128mul.c:gf128mul_bbe
  - lib/crypto/gf128mul.c:gf128mul_bbe
  - lib/crypto/gf128mul.c:gf128mul_bbe
  - lib/crypto/gf128mul.c:gf128mul_bbe
  - lib/crypto/gf128mul.c:gf128mul_bbe
  - lib/crypto/gf128mul.c:gf128mul_bbe
  - lib/crypto/gf128mul.c:gf128mul_bbe
  - lib/crypto/gf128mul.c:gf128mul_lle
  - lib/crypto/gf128mul.c:gf128mul_lle
  - lib/crypto/gf128mul.c:gf128mul_lle
  - lib/crypto/gf128mul.c:gf128mul_lle
  - lib/crypto/gf128mul.c:gf128mul_lle
  - lib/crypto/gf128mul.c:gf128mul_lle
  - lib/crypto/gf128mul.c:gf128mul_lle
  - lib/crypto/gf128mul.c:gf128mul_lle
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
In lib/crypto/gf128mul.c (ffffffff818674b1)
Location: include/crypto/b128ops.h:60
Inline: True
Inline callers:
  - lib/crypto/gf128mul.c:gf128mul_4k_bbe
  - lib/crypto/gf128mul.c:gf128mul_4k_lle
  - lib/crypto/gf128mul.c:gf128mul_init_4k_bbe
  - lib/crypto/gf128mul.c:gf128mul_init_4k_lle
  - lib/crypto/gf128mul.c:gf128mul_64k_bbe
  - lib/crypto/gf128mul.c:gf128mul_init_64k_bbe
  - lib/crypto/gf128mul.c:gf128mul_bbe
  - lib/crypto/gf128mul.c:gf128mul_bbe
  - lib/crypto/gf128mul.c:gf128mul_bbe
  - lib/crypto/gf128mul.c:gf128mul_bbe
  - lib/crypto/gf128mul.c:gf128mul_bbe
  - lib/crypto/gf128mul.c:gf128mul_bbe
  - lib/crypto/gf128mul.c:gf128mul_bbe
  - lib/crypto/gf128mul.c:gf128mul_bbe
  - lib/crypto/gf128mul.c:gf128mul_lle
  - lib/crypto/gf128mul.c:gf128mul_lle
  - lib/crypto/gf128mul.c:gf128mul_lle
  - lib/crypto/gf128mul.c:gf128mul_lle
  - lib/crypto/gf128mul.c:gf128mul_lle
  - lib/crypto/gf128mul.c:gf128mul_lle
  - lib/crypto/gf128mul.c:gf128mul_lle
  - lib/crypto/gf128mul.c:gf128mul_lle
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
In crypto/gf128mul.c (ffff8000105c89f0)
Location: include/crypto/b128ops.h:70
Inline: True
Inline callers:
  - crypto/gf128mul.c:gf128mul_4k_bbe
  - crypto/gf128mul.c:gf128mul_4k_lle
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_64k_bbe
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
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
In crypto/gf128mul.c (c0775d84)
Location: include/crypto/b128ops.h:70
Inline: True
Inline callers:
  - crypto/gf128mul.c:gf128mul_4k_bbe
  - crypto/gf128mul.c:gf128mul_4k_lle
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_64k_bbe
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
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
In crypto/gf128mul.c (c0000000007525d4)
Location: include/crypto/b128ops.h:70
Inline: True
Inline callers:
  - crypto/gf128mul.c:gf128mul_4k_bbe
  - crypto/gf128mul.c:gf128mul_4k_lle
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_64k_bbe
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
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
In crypto/gf128mul.c (ffffffe00040d08a)
Location: include/crypto/b128ops.h:70
Inline: True
Inline callers:
  - crypto/gf128mul.c:gf128mul_4k_bbe
  - crypto/gf128mul.c:gf128mul_4k_lle
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_64k_bbe
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
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
In crypto/gf128mul.c (ffffffff814c4d65)
Location: include/crypto/b128ops.h:70
Inline: True
Inline callers:
  - crypto/gf128mul.c:gf128mul_4k_bbe
  - crypto/gf128mul.c:gf128mul_4k_lle
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_64k_bbe
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
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
In crypto/gf128mul.c (ffffffff814b5785)
Location: include/crypto/b128ops.h:70
Inline: True
Inline callers:
  - crypto/gf128mul.c:gf128mul_4k_bbe
  - crypto/gf128mul.c:gf128mul_4k_lle
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_64k_bbe
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
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
In crypto/gf128mul.c (ffffffff814c0df5)
Location: include/crypto/b128ops.h:70
Inline: True
Inline callers:
  - crypto/gf128mul.c:gf128mul_4k_bbe
  - crypto/gf128mul.c:gf128mul_4k_lle
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_64k_bbe
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
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
In crypto/gf128mul.c (ffffffff814d98c5)
Location: include/crypto/b128ops.h:70
Inline: True
Inline callers:
  - crypto/gf128mul.c:gf128mul_4k_bbe
  - crypto/gf128mul.c:gf128mul_4k_lle
  - crypto/gf128mul.c:gf128mul_init_4k_bbe
  - crypto/gf128mul.c:gf128mul_init_4k_lle
  - crypto/gf128mul.c:gf128mul_64k_bbe
  - crypto/gf128mul.c:gf128mul_init_64k_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_bbe
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
  - crypto/gf128mul.c:gf128mul_lle
```
</details>
</li>
</ul>

## Differences
