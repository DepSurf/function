# Function: <code>tpm2_load_context</code>

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
int tpm2_load_context(struct tpm_chip *chip, u8 *buf, unsigned int *offset, u32 *handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffffffff815bc160)
Location: drivers/char/tpm/tpm2-space.c:70
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
```
**Symbols:**

```
ffffffff815bc160-ffffffff815bc31f: tpm2_load_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tpm2_load_context(struct tpm_chip *chip, u8 *buf, unsigned int *offset, u32 *handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffffffff81622640)
Location: drivers/char/tpm/tpm2-space.c:70
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
```
**Symbols:**

```
ffffffff81622640-ffffffff816227bf: tpm2_load_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tpm2_load_context(struct tpm_chip *chip, u8 *buf, unsigned int *offset, u32 *handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffffffff8165c410)
Location: drivers/char/tpm/tpm2-space.c:71
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
```
**Symbols:**

```
ffffffff8165c410-ffffffff8165c5b4: tpm2_load_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tpm2_load_context(struct tpm_chip *chip, u8 *buf, unsigned int *offset, u32 *handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffffffff81679780)
Location: drivers/char/tpm/tpm2-space.c:70
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
```
**Symbols:**

```
ffffffff81679780-ffffffff81679924: tpm2_load_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int tpm2_load_context(struct tpm_chip *chip, u8 *buf, unsigned int *offset, u32 *handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (0)
Location: drivers/char/tpm/tpm2-space.c:68
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
```
**Symbols:**

```
ffffffff816afd90-ffffffff816aff1c: tpm2_load_context (STB_LOCAL)
ffffffff816b08bc-ffffffff816b0918: tpm2_load_context.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int tpm2_load_context(struct tpm_chip *chip, u8 *buf, unsigned int *offset, u32 *handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (0)
Location: drivers/char/tpm/tpm2-space.c:68
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
```
**Symbols:**

```
ffffffff816d2a90-ffffffff816d2c1c: tpm2_load_context (STB_LOCAL)
ffffffff816d35bc-ffffffff816d3618: tpm2_load_context.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int tpm2_load_context(struct tpm_chip *chip, u8 *buf, unsigned int *offset, u32 *handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (0)
Location: drivers/char/tpm/tpm2-space.c:71
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_load_space
  - drivers/char/tpm/tpm2-space.c:tpm2_load_space
```
**Symbols:**

```
ffffffff81786cb0-ffffffff81786e16: tpm2_load_context (STB_LOCAL)
ffffffff81787724-ffffffff81787780: tpm2_load_context.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int tpm2_load_context(struct tpm_chip *chip, u8 *buf, unsigned int *offset, u32 *handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (0)
Location: drivers/char/tpm/tpm2-space.c:71
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_load_space
  - drivers/char/tpm/tpm2-space.c:tpm2_load_space
```
**Symbols:**

```
ffffffff8179ddc0-ffffffff8179df26: tpm2_load_context (STB_LOCAL)
ffffffff81c0a76b-ffffffff81c0a7c7: tpm2_load_context.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int tpm2_load_context(struct tpm_chip *chip, u8 *buf, unsigned int *offset, u32 *handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (0)
Location: drivers/char/tpm/tpm2-space.c:71
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
```
**Symbols:**

```
ffffffff81780780-ffffffff817808e6: tpm2_load_context (STB_LOCAL)
ffffffff81bfc203-ffffffff81bfc25f: tpm2_load_context.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int tpm2_load_context(struct tpm_chip *chip, u8 *buf, unsigned int *offset, u32 *handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (0)
Location: drivers/char/tpm/tpm2-space.c:71
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
```
**Symbols:**

```
ffffffff81806b90-ffffffff81806cf6: tpm2_load_context (STB_LOCAL)
ffffffff81cfcf07-ffffffff81cfcf63: tpm2_load_context.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tpm2_load_context(struct tpm_chip *chip, u8 *buf, unsigned int *offset, u32 *handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (0)
Location: drivers/char/tpm/tpm2-space.c:71
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
```
**Symbols:**

```
ffffffff81946770-ffffffff819468f2: tpm2_load_context (STB_LOCAL)
ffffffff81ec57c9-ffffffff81ec5809: tpm2_load_context.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tpm2_load_context(struct tpm_chip *chip, u8 *buf, unsigned int *offset, u32 *handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffffffff81aa99a0)
Location: drivers/char/tpm/tpm2-space.c:71
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
```
**Symbols:**

```
ffffffff81aa99a0-ffffffff81aa9b6a: tpm2_load_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tpm2_load_context(struct tpm_chip *chip, u8 *buf, unsigned int *offset, u32 *handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffffffff81af53b0)
Location: drivers/char/tpm/tpm2-space.c:71
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
```
**Symbols:**

```
ffffffff81af53b0-ffffffff81af5576: tpm2_load_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tpm2_load_context(struct tpm_chip *chip, u8 *buf, unsigned int *offset, u32 *handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffffffff81b489a0)
Location: drivers/char/tpm/tpm2-space.c:71
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
```
**Symbols:**

```
ffffffff81b489a0-ffffffff81b48b66: tpm2_load_context (STB_LOCAL)
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
int tpm2_load_context(struct tpm_chip *chip, u8 *buf, unsigned int *offset, u32 *handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffff8000108bd638)
Location: drivers/char/tpm/tpm2-space.c:68
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
```
**Symbols:**

```
ffff8000108bd638-ffff8000108bd85c: tpm2_load_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tpm2_load_context(struct tpm_chip *chip, u8 *buf, unsigned int *offset, u32 *handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (c09b6a60)
Location: drivers/char/tpm/tpm2-space.c:68
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
```
**Symbols:**

```
c09b6a60-c09b6cb4: tpm2_load_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tpm2_load_context(struct tpm_chip *chip, u8 *buf, unsigned int *offset, u32 *handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (c00000000095f4f0)
Location: drivers/char/tpm/tpm2-space.c:68
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
```
**Symbols:**

```
c00000000095f4f0-c00000000095f770: tpm2_load_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tpm2_load_context(struct tpm_chip *chip, u8 *buf, unsigned int *offset, u32 *handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffffffe00056fa4c)
Location: drivers/char/tpm/tpm2-space.c:68
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
```
**Symbols:**

```
ffffffe00056fa4c-ffffffe00056fcce: tpm2_load_context (STB_LOCAL)
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
int tpm2_load_context(struct tpm_chip *chip, u8 *buf, unsigned int *offset, u32 *handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (0)
Location: drivers/char/tpm/tpm2-space.c:68
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
```
**Symbols:**

```
ffffffff816984e0-ffffffff8169866c: tpm2_load_context (STB_LOCAL)
ffffffff8169900c-ffffffff81699068: tpm2_load_context.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int tpm2_load_context(struct tpm_chip *chip, u8 *buf, unsigned int *offset, u32 *handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (0)
Location: drivers/char/tpm/tpm2-space.c:68
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
```
**Symbols:**

```
ffffffff81675ed0-ffffffff8167605c: tpm2_load_context (STB_LOCAL)
ffffffff816769fc-ffffffff81676a58: tpm2_load_context.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int tpm2_load_context(struct tpm_chip *chip, u8 *buf, unsigned int *offset, u32 *handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (0)
Location: drivers/char/tpm/tpm2-space.c:68
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
```
**Symbols:**

```
ffffffff816c6750-ffffffff816c68dc: tpm2_load_context (STB_LOCAL)
ffffffff816c727c-ffffffff816c72d8: tpm2_load_context.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int tpm2_load_context(struct tpm_chip *chip, u8 *buf, unsigned int *offset, u32 *handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (0)
Location: drivers/char/tpm/tpm2-space.c:68
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
```
**Symbols:**

```
ffffffff816e0c40-ffffffff816e0dc9: tpm2_load_context (STB_LOCAL)
ffffffff816e176c-ffffffff816e17c8: tpm2_load_context.cold (STB_LOCAL)
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
