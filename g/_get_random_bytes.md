# Function: <code>_get_random_bytes</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void _get_random_bytes(void *buf, int nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff815a7fb0)
Location: drivers/char/random.c:1509
Inline: False
Direct callers:
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:crng_initialize
```
**Symbols:**

```
ffffffff815a7fb0-ffffffff815a815d: _get_random_bytes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void _get_random_bytes(void *buf, int nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8160e8b0)
Location: drivers/char/random.c:1508
Inline: False
Direct callers:
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:crng_initialize
```
**Symbols:**

```
ffffffff8160e8b0-ffffffff8160ea60: _get_random_bytes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void _get_random_bytes(void *buf, int nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81648200)
Location: drivers/char/random.c:1613
Inline: False
Direct callers:
  - drivers/char/random.c:get_random_bytes_arch
  - drivers/char/random.c:crng_initialize
```
**Symbols:**

```
ffffffff81648200-ffffffff816483b9: _get_random_bytes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void _get_random_bytes(void *buf, int nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816666a0)
Location: drivers/char/random.c:1622
Inline: False
Direct callers:
  - drivers/char/random.c:get_random_bytes
  - drivers/char/random.c:crng_initialize
```
**Symbols:**

```
ffffffff816666a0-ffffffff81666859: _get_random_bytes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void _get_random_bytes(void *buf, int nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8169c3e0)
Location: drivers/char/random.c:1704
Inline: False
Direct callers:
  - drivers/char/random.c:get_random_bytes
  - drivers/char/random.c:crng_initialize
```
**Symbols:**

```
ffffffff8169c3e0-ffffffff8169c59d: _get_random_bytes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void _get_random_bytes(void *buf, int nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816bf150)
Location: drivers/char/random.c:1705
Inline: False
Direct callers:
  - drivers/char/random.c:get_random_bytes
  - drivers/char/random.c:crng_initialize
```
**Symbols:**

```
ffffffff816bf150-ffffffff816bf30d: _get_random_bytes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void _get_random_bytes(void *buf, int nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81773380)
Location: drivers/char/random.c:1550
Inline: False
Direct callers:
  - drivers/char/random.c:get_random_bytes
  - drivers/char/random.c:do_numa_crng_init
```
**Symbols:**

```
ffffffff81773380-ffffffff81773627: _get_random_bytes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void _get_random_bytes(void *buf, int nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8178e350)
Location: drivers/char/random.c:1549
Inline: False
Direct callers:
  - drivers/char/random.c:get_random_bytes
  - drivers/char/random.c:do_numa_crng_init
```
**Symbols:**

```
ffffffff8178e350-ffffffff8178e5e2: _get_random_bytes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void _get_random_bytes(void *buf, int nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81770bc0)
Location: drivers/char/random.c:1525
Inline: False
Direct callers:
  - drivers/char/random.c:get_random_bytes
  - drivers/char/random.c:do_numa_crng_init
```
**Symbols:**

```
ffffffff81770bc0-ffffffff81770e4d: _get_random_bytes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void _get_random_bytes(void *buf, int nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff817f66d0)
Location: drivers/char/random.c:1545
Inline: False
Direct callers:
  - drivers/char/random.c:get_random_bytes
  - drivers/char/random.c:do_numa_crng_init
```
**Symbols:**

```
ffffffff817f66d0-ffffffff817f6972: _get_random_bytes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void _get_random_bytes(void *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81935000)
Location: drivers/char/random.c:354
Inline: False
Direct callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:get_random_bytes
```
**Symbols:**

```
ffffffff81935000-ffffffff819351aa: _get_random_bytes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void _get_random_bytes(void *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81a93580)
Location: drivers/char/random.c:375
Inline: False
Direct callers:
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u16
  - drivers/char/random.c:get_random_u16
  - drivers/char/random.c:get_random_u8
  - drivers/char/random.c:get_random_u8
  - drivers/char/random.c:get_random_bytes
```
**Symbols:**

```
ffffffff81a93580-ffffffff81a9372a: _get_random_bytes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void _get_random_bytes(void *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81adf070)
Location: drivers/char/random.c:375
Inline: False
Direct callers:
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u16
  - drivers/char/random.c:get_random_u16
  - drivers/char/random.c:get_random_u8
  - drivers/char/random.c:get_random_u8
  - drivers/char/random.c:get_random_bytes
```
**Symbols:**

```
ffffffff81adf070-ffffffff81adf21a: _get_random_bytes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void _get_random_bytes(void *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81b32490)
Location: drivers/char/random.c:375
Inline: False
Direct callers:
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u16
  - drivers/char/random.c:get_random_u16
  - drivers/char/random.c:get_random_u8
  - drivers/char/random.c:get_random_u8
  - drivers/char/random.c:get_random_bytes
```
**Symbols:**

```
ffffffff81b32490-ffffffff81b3263a: _get_random_bytes (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void _get_random_bytes(void *buf, int nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffff8000108afd58)
Location: drivers/char/random.c:1705
Inline: False
Direct callers:
  - drivers/char/random.c:get_random_bytes
  - drivers/char/random.c:crng_initialize
```
**Symbols:**

```
ffff8000108afd58-ffff8000108afeb8: _get_random_bytes (STB_LOCAL)
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
In drivers/char/random.c (c09aa8a0)
Location: drivers/char/random.c:1705
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_bytes
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void _get_random_bytes(void *buf, int nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (c000000000947f40)
Location: drivers/char/random.c:1705
Inline: False
Direct callers:
  - drivers/char/random.c:get_random_bytes
  - drivers/char/random.c:crng_initialize
```
**Symbols:**

```
c000000000947f40-c0000000009480e8: _get_random_bytes (STB_LOCAL)
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
In drivers/char/random.c (ffffffe00056257a)
Location: drivers/char/random.c:1705
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_bytes
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void _get_random_bytes(void *buf, int nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81684ba0)
Location: drivers/char/random.c:1705
Inline: False
Direct callers:
  - drivers/char/random.c:get_random_bytes
  - drivers/char/random.c:crng_initialize
```
**Symbols:**

```
ffffffff81684ba0-ffffffff81684d5d: _get_random_bytes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void _get_random_bytes(void *buf, int nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81662840)
Location: drivers/char/random.c:1705
Inline: False
Direct callers:
  - drivers/char/random.c:get_random_bytes
  - drivers/char/random.c:crng_initialize
```
**Symbols:**

```
ffffffff81662840-ffffffff816629fd: _get_random_bytes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void _get_random_bytes(void *buf, int nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816b2f90)
Location: drivers/char/random.c:1705
Inline: False
Direct callers:
  - drivers/char/random.c:get_random_bytes
  - drivers/char/random.c:crng_initialize
```
**Symbols:**

```
ffffffff816b2f90-ffffffff816b314d: _get_random_bytes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void _get_random_bytes(void *buf, int nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816cd4f0)
Location: drivers/char/random.c:1705
Inline: False
Direct callers:
  - drivers/char/random.c:get_random_bytes
  - drivers/char/random.c:crng_initialize
```
**Symbols:**

```
ffffffff816cd4f0-ffffffff816cd6c6: _get_random_bytes (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>size_t len</code>
</li>
<li>
<b>Param removed. </b>
<code>int nbytes</code>
</li>
</ul>
</details>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
