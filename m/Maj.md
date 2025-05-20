# Function: <code>Maj</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/sha256_generic.c (0)
Location: crypto/sha256_generic.c:35
Inline: True
```
```
In crypto/sha512_generic.c (0)
Location: crypto/sha512_generic.c:31
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/sha256_generic.c (ffffffff813e353f)
Location: crypto/sha256_generic.c:51
Inline: True
Inline callers:
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
```
```
In crypto/sha512_generic.c (ffffffff813e57a3)
Location: crypto/sha512_generic.c:31
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/sha256_generic.c (ffffffff813fc55f)
Location: crypto/sha256_generic.c:51
Inline: True
Inline callers:
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
```
```
In crypto/sha512_generic.c (ffffffff813fe7c3)
Location: crypto/sha512_generic.c:31
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/sha256_generic.c (ffffffff8140984f)
Location: crypto/sha256_generic.c:51
Inline: True
Inline callers:
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
```
```
In crypto/sha512_generic.c (ffffffff8140baa1)
Location: crypto/sha512_generic.c:31
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/sha256_generic.c (ffffffff8143226f)
Location: crypto/sha256_generic.c:51
Inline: True
Inline callers:
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
```
```
In crypto/sha512_generic.c (ffffffff814344c1)
Location: crypto/sha512_generic.c:31
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/sha256_generic.c (ffffffff81464e26)
Location: crypto/sha256_generic.c:51
Inline: True
Inline callers:
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
```
```
In crypto/sha512_generic.c (ffffffff81467048)
Location: crypto/sha512_generic.c:31
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/sha256_generic.c (ffffffff81482a96)
Location: crypto/sha256_generic.c:51
Inline: True
Inline callers:
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
```
```
In crypto/sha512_generic.c (ffffffff81484cb8)
Location: crypto/sha512_generic.c:53
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/sha256_generic.c (ffffffff814b0cc3)
Location: crypto/sha256_generic.c:46
Inline: True
Inline callers:
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
  - crypto/sha256_generic.c:sha256_transform
```
```
In crypto/sha512_generic.c (ffffffff814b2ee0)
Location: crypto/sha512_generic.c:48
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/sha512_generic.c (ffffffff814cbc50)
Location: crypto/sha512_generic.c:48
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
```
```
In lib/crypto/sha256.c (ffffffff8152f807)
Location: lib/crypto/sha256.c:26
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/sha512_generic.c (ffffffff8152b0e8)
Location: crypto/sha512_generic.c:48
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
```
```
In lib/crypto/sha256.c (ffffffff81593b00)
Location: lib/crypto/sha256.c:26
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/sha512_generic.c (ffffffff815480b8)
Location: crypto/sha512_generic.c:48
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
```
```
In lib/crypto/sha256.c (ffffffff815b09e4)
Location: lib/crypto/sha256.c:45
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/sha512_generic.c (ffffffff8155076b)
Location: crypto/sha512_generic.c:48
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
```
```
In lib/crypto/sha256.c (ffffffff815bb7da)
Location: lib/crypto/sha256.c:45
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/sha512_generic.c (ffffffff815b1054)
Location: crypto/sha512_generic.c:48
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
```
```
In lib/crypto/sha256.c (ffffffff81622368)
Location: lib/crypto/sha256.c:45
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/sha512_generic.c (ffffffff81659abe)
Location: crypto/sha512_generic.c:48
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
```
```
In lib/crypto/sha256.c (ffffffff816f1fc7)
Location: lib/crypto/sha256.c:45
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/sha512_generic.c (ffffffff81713e0e)
Location: crypto/sha512_generic.c:48
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
```
```
In lib/crypto/sha256.c (ffffffff817e3da7)
Location: lib/crypto/sha256.c:45
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/sha512_generic.c (ffffffff8174ec2c)
Location: crypto/sha512_generic.c:48
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
```
```
In lib/crypto/sha256.c (ffffffff81823cf7)
Location: lib/crypto/sha256.c:44
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/sha512_generic.c (ffffffff8179087c)
Location: crypto/sha512_generic.c:48
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
```
```
In lib/crypto/sha256.c (ffffffff81869d37)
Location: lib/crypto/sha256.c:44
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/sha512_generic.c (ffff8000105c7bf8)
Location: crypto/sha512_generic.c:48
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
```
```
In lib/crypto/sha256.c (ffff80001063bbc8)
Location: lib/crypto/sha256.c:26
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/sha512_generic.c (c077487c)
Location: crypto/sha512_generic.c:48
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
```
```
In lib/crypto/sha256.c (c07e2018)
Location: lib/crypto/sha256.c:26
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/sha512_generic.c (c000000000751968)
Location: crypto/sha512_generic.c:48
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
```
```
In lib/crypto/sha256.c (c0000000007e3234)
Location: lib/crypto/sha256.c:26
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/sha512_generic.c (ffffffe00040bac6)
Location: crypto/sha512_generic.c:48
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
```
```
In lib/crypto/sha256.c (ffffffe000468a08)
Location: lib/crypto/sha256.c:26
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/sha512_generic.c (ffffffff814c4230)
Location: crypto/sha512_generic.c:48
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
```
```
In lib/crypto/sha256.c (ffffffff81527de7)
Location: lib/crypto/sha256.c:26
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/sha512_generic.c (ffffffff814b4c50)
Location: crypto/sha512_generic.c:48
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
```
```
In lib/crypto/sha256.c (ffffffff815180c7)
Location: lib/crypto/sha256.c:26
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/sha512_generic.c (ffffffff814c02c0)
Location: crypto/sha512_generic.c:48
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
```
```
In lib/crypto/sha256.c (ffffffff81523e77)
Location: lib/crypto/sha256.c:26
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/sha512_generic.c (ffffffff814d8d90)
Location: crypto/sha512_generic.c:48
Inline: True
Inline callers:
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
  - crypto/sha512_generic.c:sha512_transform
```
```
In lib/crypto/sha256.c (ffffffff8153d7f7)
Location: lib/crypto/sha256.c:26
Inline: True
Inline callers:
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
  - lib/crypto/sha256.c:sha256_transform
```
</details>
</li>
</ul>

## Differences
