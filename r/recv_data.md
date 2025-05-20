# Function: <code>recv_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int recv_data(struct tpm_chip *chip, u8 *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis.c (ffffffff81528540)
Location: drivers/char/tpm/tpm_tis.c:232
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis.c:tpm_tis_recv
  - drivers/char/tpm/tpm_tis.c:tpm_tis_recv
```
**Symbols:**

```
ffffffff81528540-ffffffff815285f1: recv_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int recv_data(struct tpm_chip *chip, u8 *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8157b730)
Location: drivers/char/tpm/tpm_tis_core.c:178
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
```
**Symbols:**

```
ffffffff8157b730-ffffffff8157b7f2: recv_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int recv_data(struct tpm_chip *chip, u8 *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff815a7b60)
Location: drivers/char/tpm/tpm_tis_core.c:178
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
```
**Symbols:**

```
ffffffff815a7b60-ffffffff815a7c53: recv_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int recv_data(struct tpm_chip *chip, u8 *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff815bdc70)
Location: drivers/char/tpm/tpm_tis_core.c:172
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
```
**Symbols:**

```
ffffffff815bdc70-ffffffff815bdd63: recv_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int recv_data(struct tpm_chip *chip, u8 *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81624300)
Location: drivers/char/tpm/tpm_tis_core.c:174
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
```
**Symbols:**

```
ffffffff81624300-ffffffff816243f9: recv_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int recv_data(struct tpm_chip *chip, u8 *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8165e430)
Location: drivers/char/tpm/tpm_tis_core.c:282
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
```
**Symbols:**

```
ffffffff8165e430-ffffffff8165e529: recv_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int recv_data(struct tpm_chip *chip, u8 *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8167c8f0)
Location: drivers/char/tpm/tpm_tis_core.c:282
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
```
**Symbols:**

```
ffffffff8167c8f0-ffffffff8167c9e9: recv_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int recv_data(struct tpm_chip *chip, u8 *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: drivers/char/tpm/tpm_tis_core.c:278
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
```
**Symbols:**

```
ffffffff816b3770-ffffffff816b3849: recv_data (STB_LOCAL)
ffffffff816b42d2-ffffffff816b42ec: recv_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int recv_data(struct tpm_chip *chip, u8 *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: drivers/char/tpm/tpm_tis_core.c:278
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
```
**Symbols:**

```
ffffffff816d6450-ffffffff816d6529: recv_data (STB_LOCAL)
ffffffff816d6fb2-ffffffff816d6fcc: recv_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int recv_data(struct tpm_chip *chip, u8 *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: drivers/char/tpm/tpm_tis_core.c:278
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
```
**Symbols:**

```
ffffffff8178a6e0-ffffffff8178a7b9: recv_data (STB_LOCAL)
ffffffff8178b4fe-ffffffff8178b518: recv_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int recv_data(struct tpm_chip *chip, u8 *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: drivers/char/tpm/tpm_tis_core.c:245
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
```
**Symbols:**

```
ffffffff817a1660-ffffffff817a1739: recv_data (STB_LOCAL)
ffffffff81c0ac2c-ffffffff81c0ac46: recv_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int recv_data(struct tpm_chip *chip, u8 *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: drivers/char/tpm/tpm_tis_core.c:256
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
```
**Symbols:**

```
ffffffff817841f0-ffffffff817842c9: recv_data (STB_LOCAL)
ffffffff81bfc67e-ffffffff81bfc698: recv_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int recv_data(struct tpm_chip *chip, u8 *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: drivers/char/tpm/tpm_tis_core.c:257
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
```
**Symbols:**

```
ffffffff8180ac40-ffffffff8180ad19: recv_data (STB_LOCAL)
ffffffff81cfd3c2-ffffffff81cfd3dc: recv_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int recv_data(struct tpm_chip *chip, u8 *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: drivers/char/tpm/tpm_tis_core.c:257
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
```
**Symbols:**

```
ffffffff8194a970-ffffffff8194aa73: recv_data (STB_LOCAL)
ffffffff81ec5c52-ffffffff81ec5c6c: recv_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int recv_data(struct tpm_chip *chip, u8 *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81aae000)
Location: drivers/char/tpm/tpm_tis_core.c:257
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
```
**Symbols:**

```
ffffffff81aae000-ffffffff81aae139: recv_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int recv_data(struct tpm_chip *chip, u8 *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81af9a70)
Location: drivers/char/tpm/tpm_tis_core.c:314
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
```
**Symbols:**

```
ffffffff81af9a70-ffffffff81af9bb3: recv_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int recv_data(struct tpm_chip *chip, u8 *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81b4d090)
Location: drivers/char/tpm/tpm_tis_core.c:314
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
```
**Symbols:**

```
ffffffff81b4d090-ffffffff81b4d1d3: recv_data (STB_LOCAL)
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
int recv_data(struct tpm_chip *chip, u8 *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffff8000108c1ea0)
Location: drivers/char/tpm/tpm_tis_core.c:278
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
```
**Symbols:**

```
ffff8000108c1ea0-ffff8000108c1fc0: recv_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int recv_data(struct tpm_chip *chip, u8 *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (c09b9c88)
Location: drivers/char/tpm/tpm_tis_core.c:278
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
```
**Symbols:**

```
c09b9c88-c09b9d8c: recv_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision ⚠️</summary>

```c
int recv_data(struct tpm_chip *chip, u8 *buf, size_t count);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (c0000000009637c0)
Location: drivers/char/tpm/tpm_tis_core.c:278
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
```
```
In drivers/char/tpm/tpm_i2c_infineon.c (c000000000965ee0)
Location: drivers/char/tpm/tpm_i2c_infineon.c:436
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_i2c_infineon.c:tpm_tis_i2c_recv
  - drivers/char/tpm/tpm_i2c_infineon.c:tpm_tis_i2c_recv
```
**Symbols:**

```
c0000000009637c0-c000000000963928: recv_data (STB_LOCAL)
c000000000965ee0-c00000000096602c: recv_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int recv_data(struct tpm_chip *chip, u8 *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffe000572a08)
Location: drivers/char/tpm/tpm_tis_core.c:278
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
```
**Symbols:**

```
ffffffe000572a08-ffffffe000572aec: recv_data (STB_LOCAL)
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
int recv_data(struct tpm_chip *chip, u8 *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: drivers/char/tpm/tpm_tis_core.c:278
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
```
**Symbols:**

```
ffffffff8169bea0-ffffffff8169bf79: recv_data (STB_LOCAL)
ffffffff8169ca02-ffffffff8169ca1c: recv_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int recv_data(struct tpm_chip *chip, u8 *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: drivers/char/tpm/tpm_tis_core.c:278
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
```
**Symbols:**

```
ffffffff81679890-ffffffff81679969: recv_data (STB_LOCAL)
ffffffff8167a3f2-ffffffff8167a40c: recv_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int recv_data(struct tpm_chip *chip, u8 *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: drivers/char/tpm/tpm_tis_core.c:278
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
```
**Symbols:**

```
ffffffff816ca110-ffffffff816ca1e9: recv_data (STB_LOCAL)
ffffffff816cac72-ffffffff816cac8c: recv_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int recv_data(struct tpm_chip *chip, u8 *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: drivers/char/tpm/tpm_tis_core.c:278
Inline: False
Direct callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_recv
```
**Symbols:**

```
ffffffff816e45e0-ffffffff816e46b9: recv_data (STB_LOCAL)
ffffffff816e5142-ffffffff816e515c: recv_data.cold (STB_LOCAL)
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
