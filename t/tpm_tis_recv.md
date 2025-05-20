# Function: <code>tpm_tis_recv</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tpm_tis_recv(struct tpm_chip *chip, u8 *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis.c (ffffffff81528ea0)
Location: drivers/char/tpm/tpm_tis.c:250
Inline: False
```
**Symbols:**

```
ffffffff81528ea0-ffffffff81528fc9: tpm_tis_recv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tpm_tis_recv(struct tpm_chip *chip, u8 *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8157b800)
Location: drivers/char/tpm/tpm_tis_core.c:200
Inline: False
```
**Symbols:**

```
ffffffff8157b800-ffffffff8157b9b9: tpm_tis_recv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tpm_tis_recv(struct tpm_chip *chip, u8 *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff815a7c60)
Location: drivers/char/tpm/tpm_tis_core.c:207
Inline: False
```
**Symbols:**

```
ffffffff815a7c60-ffffffff815a7e30: tpm_tis_recv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tpm_tis_recv(struct tpm_chip *chip, u8 *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff815bdd70)
Location: drivers/char/tpm/tpm_tis_core.c:201
Inline: False
```
**Symbols:**

```
ffffffff815bdd70-ffffffff815bdf3d: tpm_tis_recv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tpm_tis_recv(struct tpm_chip *chip, u8 *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81624400)
Location: drivers/char/tpm/tpm_tis_core.c:203
Inline: False
```
**Symbols:**

```
ffffffff81624400-ffffffff816245e3: tpm_tis_recv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tpm_tis_recv(struct tpm_chip *chip, u8 *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8165e610)
Location: drivers/char/tpm/tpm_tis_core.c:311
Inline: False
```
**Symbols:**

```
ffffffff8165e610-ffffffff8165e7f4: tpm_tis_recv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tpm_tis_recv(struct tpm_chip *chip, u8 *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8167cad0)
Location: drivers/char/tpm/tpm_tis_core.c:311
Inline: False
```
**Symbols:**

```
ffffffff8167cad0-ffffffff8167ccb4: tpm_tis_recv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int tpm_tis_recv(struct tpm_chip *chip, u8 *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: drivers/char/tpm/tpm_tis_core.c:307
Inline: False
```
**Symbols:**

```
ffffffff816b3850-ffffffff816b39bb: tpm_tis_recv (STB_LOCAL)
ffffffff816b42ec-ffffffff816b4348: tpm_tis_recv.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int tpm_tis_recv(struct tpm_chip *chip, u8 *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: drivers/char/tpm/tpm_tis_core.c:307
Inline: False
```
**Symbols:**

```
ffffffff816d6530-ffffffff816d669b: tpm_tis_recv (STB_LOCAL)
ffffffff816d6fcc-ffffffff816d7028: tpm_tis_recv.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int tpm_tis_recv(struct tpm_chip *chip, u8 *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: drivers/char/tpm/tpm_tis_core.c:307
Inline: False
```
**Symbols:**

```
ffffffff8178a9e0-ffffffff8178ab48: tpm_tis_recv (STB_LOCAL)
ffffffff8178b518-ffffffff8178b574: tpm_tis_recv.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int tpm_tis_recv(struct tpm_chip *chip, u8 *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: drivers/char/tpm/tpm_tis_core.c:274
Inline: False
```
**Symbols:**

```
ffffffff817a1740-ffffffff817a1870: tpm_tis_recv (STB_LOCAL)
ffffffff81c0ac46-ffffffff81c0ac9a: tpm_tis_recv.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int tpm_tis_recv(struct tpm_chip *chip, u8 *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: drivers/char/tpm/tpm_tis_core.c:285
Inline: False
```
**Symbols:**

```
ffffffff817842d0-ffffffff81784400: tpm_tis_recv (STB_LOCAL)
ffffffff81bfc698-ffffffff81bfc6ec: tpm_tis_recv.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int tpm_tis_recv(struct tpm_chip *chip, u8 *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: drivers/char/tpm/tpm_tis_core.c:286
Inline: False
```
**Symbols:**

```
ffffffff8180ad20-ffffffff8180ae50: tpm_tis_recv (STB_LOCAL)
ffffffff81cfd3dc-ffffffff81cfd430: tpm_tis_recv.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tpm_tis_recv(struct tpm_chip *chip, u8 *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: drivers/char/tpm/tpm_tis_core.c:286
Inline: False
```
**Symbols:**

```
ffffffff8194ac70-ffffffff8194adb6: tpm_tis_recv (STB_LOCAL)
ffffffff81ec5c89-ffffffff81ec5cdd: tpm_tis_recv.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tpm_tis_recv(struct tpm_chip *chip, u8 *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81aae490)
Location: drivers/char/tpm/tpm_tis_core.c:286
Inline: False
```
**Symbols:**

```
ffffffff81aae490-ffffffff81aae663: tpm_tis_recv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tpm_tis_recv(struct tpm_chip *chip, u8 *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81afa280)
Location: drivers/char/tpm/tpm_tis_core.c:343
Inline: False
```
**Symbols:**

```
ffffffff81afa280-ffffffff81afa46a: tpm_tis_recv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tpm_tis_recv(struct tpm_chip *chip, u8 *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81b4d8a0)
Location: drivers/char/tpm/tpm_tis_core.c:400
Inline: False
```
**Symbols:**

```
ffffffff81b4d8a0-ffffffff81b4dacd: tpm_tis_recv (STB_LOCAL)
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
int tpm_tis_recv(struct tpm_chip *chip, u8 *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffff8000108c1fc0)
Location: drivers/char/tpm/tpm_tis_core.c:307
Inline: False
```
**Symbols:**

```
ffff8000108c1fc0-ffff8000108c2188: tpm_tis_recv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tpm_tis_recv(struct tpm_chip *chip, u8 *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (c09b9e9c)
Location: drivers/char/tpm/tpm_tis_core.c:307
Inline: False
```
**Symbols:**

```
c09b9e9c-c09ba058: tpm_tis_recv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tpm_tis_recv(struct tpm_chip *chip, u8 *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (c000000000963a90)
Location: drivers/char/tpm/tpm_tis_core.c:307
Inline: False
```
**Symbols:**

```
c000000000963a90-c000000000963cf8: tpm_tis_recv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tpm_tis_recv(struct tpm_chip *chip, u8 *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (ffffffe000572b9c)
Location: drivers/char/tpm/tpm_tis_core.c:307
Inline: False
```
**Symbols:**

```
ffffffe000572b9c-ffffffe000572d34: tpm_tis_recv (STB_LOCAL)
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
int tpm_tis_recv(struct tpm_chip *chip, u8 *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: drivers/char/tpm/tpm_tis_core.c:307
Inline: False
```
**Symbols:**

```
ffffffff8169bf80-ffffffff8169c0eb: tpm_tis_recv (STB_LOCAL)
ffffffff8169ca1c-ffffffff8169ca78: tpm_tis_recv.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int tpm_tis_recv(struct tpm_chip *chip, u8 *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: drivers/char/tpm/tpm_tis_core.c:307
Inline: False
```
**Symbols:**

```
ffffffff81679970-ffffffff81679adb: tpm_tis_recv (STB_LOCAL)
ffffffff8167a40c-ffffffff8167a468: tpm_tis_recv.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int tpm_tis_recv(struct tpm_chip *chip, u8 *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: drivers/char/tpm/tpm_tis_core.c:307
Inline: False
```
**Symbols:**

```
ffffffff816ca1f0-ffffffff816ca35b: tpm_tis_recv (STB_LOCAL)
ffffffff816cac8c-ffffffff816cace8: tpm_tis_recv.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int tpm_tis_recv(struct tpm_chip *chip, u8 *buf, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_tis_core.c (0)
Location: drivers/char/tpm/tpm_tis_core.c:307
Inline: False
```
**Symbols:**

```
ffffffff816e46c0-ffffffff816e482b: tpm_tis_recv (STB_LOCAL)
ffffffff816e515c-ffffffff816e51b8: tpm_tis_recv.cold (STB_LOCAL)
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
