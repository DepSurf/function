# Function: <code>rng_is_initialized</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
bool rng_is_initialized();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81662a60)
Location: drivers/char/random.c:1679
Inline: False
```
**Symbols:**

```
ffffffff81662a60-ffffffff81662a75: rng_is_initialized (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool rng_is_initialized();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81698660)
Location: drivers/char/random.c:1761
Inline: False
```
**Symbols:**

```
ffffffff81698660-ffffffff81698675: rng_is_initialized (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool rng_is_initialized();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816bb270)
Location: drivers/char/random.c:1822
Inline: False
```
**Symbols:**

```
ffffffff816bb270-ffffffff816bb285: rng_is_initialized (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool rng_is_initialized();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8176f6d0)
Location: drivers/char/random.c:1667
Inline: False
```
**Symbols:**

```
ffffffff8176f6d0-ffffffff8176f6e5: rng_is_initialized (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool rng_is_initialized();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8178a630)
Location: drivers/char/random.c:1666
Inline: False
```
**Symbols:**

```
ffffffff8178a630-ffffffff8178a645: rng_is_initialized (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool rng_is_initialized();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8176dce0)
Location: drivers/char/random.c:1642
Inline: False
```
**Symbols:**

```
ffffffff8176dce0-ffffffff8176dcf5: rng_is_initialized (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool rng_is_initialized();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff817f34b0)
Location: drivers/char/random.c:1662
Inline: False
```
**Symbols:**

```
ffffffff817f34b0-ffffffff817f34c5: rng_is_initialized (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool rng_is_initialized();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81933b40)
Location: drivers/char/random.c:105
Inline: False
Direct callers:
  - crypto/drbg.c:drbg_generate
  - crypto/drbg.c:drbg_seed
  - lib/vsprintf.c:__ptr_to_hashval
```
**Symbols:**

```
ffffffff81933b40-ffffffff81933b66: rng_is_initialized (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool rng_is_initialized();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81a92970)
Location: drivers/char/random.c:108
Inline: False
Direct callers:
  - arch/x86/kernel/kexec-bzimage64.c:setup_boot_parameters
  - crypto/drbg.c:drbg_generate
  - crypto/drbg.c:drbg_seed
```
**Symbols:**

```
ffffffff81a92970-ffffffff81a92996: rng_is_initialized (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool rng_is_initialized();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81ade1f0)
Location: drivers/char/random.c:108
Inline: False
Direct callers:
  - arch/x86/kernel/kexec-bzimage64.c:setup_boot_parameters
  - crypto/drbg.c:drbg_generate
  - crypto/drbg.c:drbg_seed
```
**Symbols:**

```
ffffffff81ade1f0-ffffffff81ade216: rng_is_initialized (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool rng_is_initialized();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81b31610)
Location: drivers/char/random.c:108
Inline: False
Direct callers:
  - arch/x86/kernel/kexec-bzimage64.c:setup_boot_parameters
  - crypto/drbg.c:drbg_generate
  - crypto/drbg.c:drbg_seed
```
**Symbols:**

```
ffffffff81b31610-ffffffff81b31636: rng_is_initialized (STB_GLOBAL)
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
bool rng_is_initialized();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffff8000108abd38)
Location: drivers/char/random.c:1822
Inline: False
```
**Symbols:**

```
ffff8000108abd38-ffff8000108abd60: rng_is_initialized (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool rng_is_initialized();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (c09a7b20)
Location: drivers/char/random.c:1822
Inline: False
```
**Symbols:**

```
c09a7b20-c09a7b50: rng_is_initialized (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool rng_is_initialized();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (c0000000009435a0)
Location: drivers/char/random.c:1822
Inline: False
```
**Symbols:**

```
c0000000009435a0-c0000000009435c4: rng_is_initialized (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool rng_is_initialized();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffe000560498)
Location: drivers/char/random.c:1822
Inline: False
```
**Symbols:**

```
ffffffe000560498-ffffffe0005604c0: rng_is_initialized (STB_GLOBAL)
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
bool rng_is_initialized();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81680cd0)
Location: drivers/char/random.c:1822
Inline: False
```
**Symbols:**

```
ffffffff81680cd0-ffffffff81680ce5: rng_is_initialized (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool rng_is_initialized();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8165e9a0)
Location: drivers/char/random.c:1822
Inline: False
```
**Symbols:**

```
ffffffff8165e9a0-ffffffff8165e9b5: rng_is_initialized (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool rng_is_initialized();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816af0b0)
Location: drivers/char/random.c:1822
Inline: False
```
**Symbols:**

```
ffffffff816af0b0-ffffffff816af0c5: rng_is_initialized (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool rng_is_initialized();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff816c94d0)
Location: drivers/char/random.c:1822
Inline: False
```
**Symbols:**

```
ffffffff816c94d0-ffffffff816c94e5: rng_is_initialized (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
