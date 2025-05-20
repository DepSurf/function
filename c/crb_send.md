# Function: <code>crb_send</code>

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
int crb_send(struct tpm_chip *chip, u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (ffffffff81660530)
Location: drivers/char/tpm/tpm_crb.c:352
Inline: False
```
**Symbols:**

```
ffffffff81660530-ffffffff81660625: crb_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int crb_send(struct tpm_chip *chip, u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (ffffffff8167e210)
Location: drivers/char/tpm/tpm_crb.c:362
Inline: False
```
**Symbols:**

```
ffffffff8167e210-ffffffff8167e305: crb_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int crb_send(struct tpm_chip *chip, u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (0)
Location: drivers/char/tpm/tpm_crb.c:358
Inline: False
```
**Symbols:**

```
ffffffff816b4f10-ffffffff816b4fc6: crb_send (STB_LOCAL)
ffffffff816b575f-ffffffff816b57a9: crb_send.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int crb_send(struct tpm_chip *chip, u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (0)
Location: drivers/char/tpm/tpm_crb.c:358
Inline: False
```
**Symbols:**

```
ffffffff816d7bf0-ffffffff816d7ca6: crb_send (STB_LOCAL)
ffffffff816d843f-ffffffff816d8489: crb_send.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int crb_send(struct tpm_chip *chip, u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (0)
Location: drivers/char/tpm/tpm_crb.c:358
Inline: False
```
**Symbols:**

```
ffffffff8178c210-ffffffff8178c305: crb_send (STB_LOCAL)
ffffffff8178cb48-ffffffff8178cb94: crb_send.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int crb_send(struct tpm_chip *chip, u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (0)
Location: drivers/char/tpm/tpm_crb.c:358
Inline: False
```
**Symbols:**

```
ffffffff817a27a0-ffffffff817a2895: crb_send (STB_LOCAL)
ffffffff81c0b10c-ffffffff81c0b158: crb_send.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int crb_send(struct tpm_chip *chip, u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (0)
Location: drivers/char/tpm/tpm_crb.c:358
Inline: False
```
**Symbols:**

```
ffffffff817854a0-ffffffff81785596: crb_send (STB_LOCAL)
ffffffff81bfcb8b-ffffffff81bfcbd7: crb_send.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int crb_send(struct tpm_chip *chip, u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (0)
Location: drivers/char/tpm/tpm_crb.c:358
Inline: False
```
**Symbols:**

```
ffffffff8180bfe0-ffffffff8180c0d6: crb_send (STB_LOCAL)
ffffffff81cfd941-ffffffff81cfd98d: crb_send.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int crb_send(struct tpm_chip *chip, u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (0)
Location: drivers/char/tpm/tpm_crb.c:358
Inline: False
```
**Symbols:**

```
ffffffff8194c620-ffffffff8194c728: crb_send (STB_LOCAL)
ffffffff81ec625e-ffffffff81ec62aa: crb_send.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int crb_send(struct tpm_chip *chip, u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (ffffffff81ab0840)
Location: drivers/char/tpm/tpm_crb.c:358
Inline: False
```
**Symbols:**

```
ffffffff81ab0840-ffffffff81ab0994: crb_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int crb_send(struct tpm_chip *chip, u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (ffffffff81afc720)
Location: drivers/char/tpm/tpm_crb.c:397
Inline: False
```
**Symbols:**

```
ffffffff81afc720-ffffffff81afc89e: crb_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int crb_send(struct tpm_chip *chip, u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (ffffffff81b4fd30)
Location: drivers/char/tpm/tpm_crb.c:397
Inline: False
```
**Symbols:**

```
ffffffff81b4fd30-ffffffff81b4feae: crb_send (STB_LOCAL)
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
int crb_send(struct tpm_chip *chip, u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (ffff8000108c2e38)
Location: drivers/char/tpm/tpm_crb.c:358
Inline: False
```
**Symbols:**

```
ffff8000108c2e38-ffff8000108c2fd0: crb_send (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int crb_send(struct tpm_chip *chip, u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (0)
Location: drivers/char/tpm/tpm_crb.c:358
Inline: False
```
**Symbols:**

```
ffffffff8169d640-ffffffff8169d6f6: crb_send (STB_LOCAL)
ffffffff8169de8f-ffffffff8169ded9: crb_send.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int crb_send(struct tpm_chip *chip, u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (0)
Location: drivers/char/tpm/tpm_crb.c:358
Inline: False
```
**Symbols:**

```
ffffffff8167b030-ffffffff8167b0e6: crb_send (STB_LOCAL)
ffffffff8167b87f-ffffffff8167b8c9: crb_send.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int crb_send(struct tpm_chip *chip, u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (0)
Location: drivers/char/tpm/tpm_crb.c:358
Inline: False
```
**Symbols:**

```
ffffffff816cb8b0-ffffffff816cb966: crb_send (STB_LOCAL)
ffffffff816cc0ff-ffffffff816cc149: crb_send.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int crb_send(struct tpm_chip *chip, u8 *buf, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm_crb.c (0)
Location: drivers/char/tpm/tpm_crb.c:358
Inline: False
```
**Symbols:**

```
ffffffff816e5d80-ffffffff816e5e36: crb_send (STB_LOCAL)
ffffffff816e65cf-ffffffff816e6619: crb_send.cold (STB_LOCAL)
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
