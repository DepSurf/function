# Function: <code>get_random_bytes_arch</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void get_random_bytes_arch(void *buf, int nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81513bd0)
Location: drivers/char/random.c:1335
Inline: False
```
**Symbols:**

```
ffffffff81513bd0-ffffffff81513d63: get_random_bytes_arch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void get_random_bytes_arch(void *buf, int nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81567b30)
Location: drivers/char/random.c:1597
Inline: False
```
**Symbols:**

```
ffffffff81567b30-ffffffff81567cb1: get_random_bytes_arch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void get_random_bytes_arch(void *buf, int nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff81594260)
Location: drivers/char/random.c:1597
Inline: False
```
**Symbols:**

```
ffffffff81594260-ffffffff815943e1: get_random_bytes_arch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void get_random_bytes_arch(void *buf, int nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff815a81a0)
Location: drivers/char/random.c:1625
Inline: False
```
**Symbols:**

```
ffffffff815a81a0-ffffffff815a834e: get_random_bytes_arch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void get_random_bytes_arch(void *buf, int nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8160eaa0)
Location: drivers/char/random.c:1624
Inline: False
```
**Symbols:**

```
ffffffff8160eaa0-ffffffff8160ec51: get_random_bytes_arch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void get_random_bytes_arch(void *buf, int nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:1729
Inline: False
```
**Symbols:**

```
ffffffff81649235-ffffffff81649241: get_random_bytes_arch.cold.43 (STB_LOCAL)
ffffffff81648690-ffffffff81648843: get_random_bytes_arch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int get_random_bytes_arch(void *buf, int nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:1755
Inline: False
Direct callers:
  - lib/vsprintf.c:initialize_ptr_random
```
**Symbols:**

```
ffffffff816674b9-ffffffff816674c5: get_random_bytes_arch.cold.40 (STB_LOCAL)
ffffffff81664730-ffffffff816648c6: get_random_bytes_arch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int get_random_bytes_arch(void *buf, int nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:1837
Inline: False
Direct callers:
  - lib/vsprintf.c:initialize_ptr_random
```
**Symbols:**

```
ffffffff8169cf54-ffffffff8169cf60: get_random_bytes_arch.cold (STB_LOCAL)
ffffffff8169a2b0-ffffffff8169a445: get_random_bytes_arch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int get_random_bytes_arch(void *buf, int nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:1898
Inline: False
Direct callers:
  - lib/vsprintf.c:initialize_ptr_random
```
**Symbols:**

```
ffffffff816bfcb8-ffffffff816bfcc4: get_random_bytes_arch.cold (STB_LOCAL)
ffffffff816bcfe0-ffffffff816bd175: get_random_bytes_arch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int get_random_bytes_arch(void *buf, int nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:1743
Inline: False
Direct callers:
  - lib/vsprintf.c:initialize_ptr_random
```
**Symbols:**

```
ffffffff81773b88-ffffffff81773b94: get_random_bytes_arch.cold (STB_LOCAL)
ffffffff817715a0-ffffffff81771734: get_random_bytes_arch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int get_random_bytes_arch(void *buf, int nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:1742
Inline: False
Direct callers:
  - lib/vsprintf.c:initialize_ptr_random
```
**Symbols:**

```
ffffffff81c0851d-ffffffff81c08529: get_random_bytes_arch.cold (STB_LOCAL)
ffffffff8178c5b0-ffffffff8178c72d: get_random_bytes_arch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int get_random_bytes_arch(void *buf, int nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:1718
Inline: False
Direct callers:
  - lib/vsprintf.c:initialize_ptr_random
```
**Symbols:**

```
ffffffff81bfa0e2-ffffffff81bfa0ee: get_random_bytes_arch.cold (STB_LOCAL)
ffffffff8176fcd0-ffffffff8176fe44: get_random_bytes_arch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int get_random_bytes_arch(void *buf, int nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:1738
Inline: False
Direct callers:
  - lib/vsprintf.c:initialize_ptr_random
```
**Symbols:**

```
ffffffff81cfaa0e-ffffffff81cfaa1a: get_random_bytes_arch.cold (STB_LOCAL)
ffffffff817f5690-ffffffff817f5804: get_random_bytes_arch (STB_GLOBAL)
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
<summary>In <code>arm64</code>: ✅</summary>

```c
int get_random_bytes_arch(void *buf, int nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffff8000108ad188)
Location: drivers/char/random.c:1898
Inline: False
Direct callers:
  - lib/vsprintf.c:initialize_ptr_random
```
**Symbols:**

```
ffff8000108ad188-ffff8000108ad23c: get_random_bytes_arch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int get_random_bytes_arch(void *buf, int nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (c09a7cec)
Location: drivers/char/random.c:1898
Inline: False
Direct callers:
  - lib/vsprintf.c:initialize_ptr_random
```
**Symbols:**

```
c09a7cec-c09a7d90: get_random_bytes_arch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int get_random_bytes_arch(void *buf, int nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (c0000000009437f0)
Location: drivers/char/random.c:1898
Inline: False
Direct callers:
  - lib/vsprintf.c:initialize_ptr_random
```
**Symbols:**

```
c0000000009437f0-c0000000009438b8: get_random_bytes_arch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int get_random_bytes_arch(void *buf, int nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffe0005607f6)
Location: drivers/char/random.c:1898
Inline: False
Direct callers:
  - lib/vsprintf.c:initialize_ptr_random
```
**Symbols:**

```
ffffffe0005607f6-ffffffe00056087a: get_random_bytes_arch (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int get_random_bytes_arch(void *buf, int nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:1898
Inline: False
Direct callers:
  - lib/vsprintf.c:initialize_ptr_random
```
**Symbols:**

```
ffffffff81685708-ffffffff81685714: get_random_bytes_arch.cold (STB_LOCAL)
ffffffff81682a50-ffffffff81682be5: get_random_bytes_arch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int get_random_bytes_arch(void *buf, int nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:1898
Inline: False
Direct callers:
  - lib/vsprintf.c:initialize_ptr_random
```
**Symbols:**

```
ffffffff816633a8-ffffffff816633b4: get_random_bytes_arch.cold (STB_LOCAL)
ffffffff816606d0-ffffffff81660865: get_random_bytes_arch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int get_random_bytes_arch(void *buf, int nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:1898
Inline: False
Direct callers:
  - lib/vsprintf.c:initialize_ptr_random
```
**Symbols:**

```
ffffffff816b3af8-ffffffff816b3b04: get_random_bytes_arch.cold (STB_LOCAL)
ffffffff816b0e20-ffffffff816b0fb5: get_random_bytes_arch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int get_random_bytes_arch(void *buf, int nbytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:1898
Inline: False
Direct callers:
  - lib/vsprintf.c:initialize_ptr_random
```
**Symbols:**

```
ffffffff816ce058-ffffffff816ce064: get_random_bytes_arch.cold (STB_LOCAL)
ffffffff816cb2b0-ffffffff816cb45e: get_random_bytes_arch (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
