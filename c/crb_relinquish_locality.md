# Function: <code>crb_relinquish_locality</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
int crb_relinquish_locality(struct tpm_chip *chip, int loc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (ffffffff81660010)
Location: drivers/char/tpm/tpm_crb.c:266
Inline: False
```
**Symbols:**

```
ffffffff81660010-ffffffff8166002b: crb_relinquish_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int crb_relinquish_locality(struct tpm_chip *chip, int loc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (ffffffff8167e660)
Location: drivers/char/tpm/tpm_crb.c:266
Inline: False
```
**Symbols:**

```
ffffffff8167e660-ffffffff8167e67b: crb_relinquish_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int crb_relinquish_locality(struct tpm_chip *chip, int loc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (ffffffff816b52d0)
Location: drivers/char/tpm/tpm_crb.c:262
Inline: False
```
**Symbols:**

```
ffffffff816b52d0-ffffffff816b52e8: crb_relinquish_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int crb_relinquish_locality(struct tpm_chip *chip, int loc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (ffffffff816d7fb0)
Location: drivers/char/tpm/tpm_crb.c:262
Inline: False
```
**Symbols:**

```
ffffffff816d7fb0-ffffffff816d7fc8: crb_relinquish_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int crb_relinquish_locality(struct tpm_chip *chip, int loc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (0)
Location: drivers/char/tpm/tpm_crb.c:262
Inline: False
```
**Symbols:**

```
ffffffff8178c420-ffffffff8178c46c: crb_relinquish_locality (STB_LOCAL)
ffffffff8178cbdf-ffffffff8178cbf8: crb_relinquish_locality.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int crb_relinquish_locality(struct tpm_chip *chip, int loc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (0)
Location: drivers/char/tpm/tpm_crb.c:262
Inline: False
```
**Symbols:**

```
ffffffff817a29b0-ffffffff817a29fc: crb_relinquish_locality (STB_LOCAL)
ffffffff81c0b1a3-ffffffff81c0b1bc: crb_relinquish_locality.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int crb_relinquish_locality(struct tpm_chip *chip, int loc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (0)
Location: drivers/char/tpm/tpm_crb.c:262
Inline: False
```
**Symbols:**

```
ffffffff817856b0-ffffffff817856fc: crb_relinquish_locality (STB_LOCAL)
ffffffff81bfcc22-ffffffff81bfcc3b: crb_relinquish_locality.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int crb_relinquish_locality(struct tpm_chip *chip, int loc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (0)
Location: drivers/char/tpm/tpm_crb.c:262
Inline: False
```
**Symbols:**

```
ffffffff8180c1f0-ffffffff8180c23c: crb_relinquish_locality (STB_LOCAL)
ffffffff81cfd9d8-ffffffff81cfd9f1: crb_relinquish_locality.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int crb_relinquish_locality(struct tpm_chip *chip, int loc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (0)
Location: drivers/char/tpm/tpm_crb.c:262
Inline: False
```
**Symbols:**

```
ffffffff8194c790-ffffffff8194c7e8: crb_relinquish_locality (STB_LOCAL)
ffffffff81ec62c3-ffffffff81ec62dc: crb_relinquish_locality.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int crb_relinquish_locality(struct tpm_chip *chip, int loc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (ffffffff81ab0a30)
Location: drivers/char/tpm/tpm_crb.c:262
Inline: False
```
**Symbols:**

```
ffffffff81ab0a30-ffffffff81ab0a9a: crb_relinquish_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int crb_relinquish_locality(struct tpm_chip *chip, int loc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (ffffffff81afc930)
Location: drivers/char/tpm/tpm_crb.c:301
Inline: False
```
**Symbols:**

```
ffffffff81afc930-ffffffff81afc99a: crb_relinquish_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int crb_relinquish_locality(struct tpm_chip *chip, int loc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (ffffffff81b4ff40)
Location: drivers/char/tpm/tpm_crb.c:301
Inline: False
```
**Symbols:**

```
ffffffff81b4ff40-ffffffff81b4ffaa: crb_relinquish_locality (STB_LOCAL)
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
int crb_relinquish_locality(struct tpm_chip *chip, int loc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (ffff8000108c34f0)
Location: drivers/char/tpm/tpm_crb.c:262
Inline: False
```
**Symbols:**

```
ffff8000108c34f0-ffff8000108c3524: crb_relinquish_locality (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int crb_relinquish_locality(struct tpm_chip *chip, int loc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (ffffffff8169da00)
Location: drivers/char/tpm/tpm_crb.c:262
Inline: False
```
**Symbols:**

```
ffffffff8169da00-ffffffff8169da18: crb_relinquish_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int crb_relinquish_locality(struct tpm_chip *chip, int loc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (ffffffff8167b3f0)
Location: drivers/char/tpm/tpm_crb.c:262
Inline: False
```
**Symbols:**

```
ffffffff8167b3f0-ffffffff8167b408: crb_relinquish_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int crb_relinquish_locality(struct tpm_chip *chip, int loc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (ffffffff816cbc70)
Location: drivers/char/tpm/tpm_crb.c:262
Inline: False
```
**Symbols:**

```
ffffffff816cbc70-ffffffff816cbc88: crb_relinquish_locality (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int crb_relinquish_locality(struct tpm_chip *chip, int loc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (ffffffff816e6140)
Location: drivers/char/tpm/tpm_crb.c:262
Inline: False
```
**Symbols:**

```
ffffffff816e6140-ffffffff816e6158: crb_relinquish_locality (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
