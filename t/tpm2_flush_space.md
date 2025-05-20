# Function: <code>tpm2_flush_space</code>

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
void tpm2_flush_space(struct tpm_chip *chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffffffff815bbef0)
Location: drivers/char/tpm/tpm2-space.c:164
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
```
**Symbols:**

```
ffffffff815bbef0-ffffffff815bbf66: tpm2_flush_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tpm2_flush_space(struct tpm_chip *chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffffffff81622440)
Location: drivers/char/tpm/tpm2-space.c:164
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
```
**Symbols:**

```
ffffffff81622440-ffffffff816224b6: tpm2_flush_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tpm2_flush_space(struct tpm_chip *chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffffffff8165c210)
Location: drivers/char/tpm/tpm2-space.c:166
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
```
**Symbols:**

```
ffffffff8165c210-ffffffff8165c286: tpm2_flush_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tpm2_flush_space(struct tpm_chip *chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffffffff81679580)
Location: drivers/char/tpm/tpm2-space.c:165
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
```
**Symbols:**

```
ffffffff81679580-ffffffff816795f6: tpm2_flush_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tpm2_flush_space(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffffffff816b0020)
Location: drivers/char/tpm/tpm2-space.c:161
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
```
**Symbols:**

```
ffffffff816b0020-ffffffff816b008c: tpm2_flush_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tpm2_flush_space(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffffffff816d2d20)
Location: drivers/char/tpm/tpm2-space.c:161
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
```
**Symbols:**

```
ffffffff816d2d20-ffffffff816d2d8c: tpm2_flush_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tpm2_flush_space(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffffffff81787090)
Location: drivers/char/tpm/tpm2-space.c:164
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_save_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_load_space
  - drivers/char/tpm/tpm2-space.c:tpm2_load_space
```
**Symbols:**

```
ffffffff81787090-ffffffff817870fc: tpm2_flush_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tpm2_flush_space(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffffffff8179e1a0)
Location: drivers/char/tpm/tpm2-space.c:164
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_save_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_load_space
  - drivers/char/tpm/tpm2-space.c:tpm2_load_space
```
**Symbols:**

```
ffffffff8179e1a0-ffffffff8179e20c: tpm2_flush_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tpm2_flush_space(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffffffff81780b60)
Location: drivers/char/tpm/tpm2-space.c:164
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
```
**Symbols:**

```
ffffffff81780b60-ffffffff81780bcc: tpm2_flush_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tpm2_flush_space(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffffffff81806fb0)
Location: drivers/char/tpm/tpm2-space.c:164
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
```
**Symbols:**

```
ffffffff81806fb0-ffffffff8180707e: tpm2_flush_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tpm2_flush_space(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffffffff81946bb0)
Location: drivers/char/tpm/tpm2-space.c:164
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
```
**Symbols:**

```
ffffffff81946bb0-ffffffff81946c8b: tpm2_flush_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tpm2_flush_space(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffffffff81aa9eb0)
Location: drivers/char/tpm/tpm2-space.c:164
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
```
**Symbols:**

```
ffffffff81aa9eb0-ffffffff81aa9f8b: tpm2_flush_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tpm2_flush_space(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffffffff81af56d0)
Location: drivers/char/tpm/tpm2-space.c:164
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
```
**Symbols:**

```
ffffffff81af56d0-ffffffff81af57ab: tpm2_flush_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tpm2_flush_space(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffffffff81b48cc0)
Location: drivers/char/tpm/tpm2-space.c:164
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
```
**Symbols:**

```
ffffffff81b48cc0-ffffffff81b48d9b: tpm2_flush_space (STB_GLOBAL)
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
void tpm2_flush_space(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffff8000108bd978)
Location: drivers/char/tpm/tpm2-space.c:161
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
```
**Symbols:**

```
ffff8000108bd978-ffff8000108bd9fc: tpm2_flush_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tpm2_flush_space(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (c09b6db4)
Location: drivers/char/tpm/tpm2-space.c:161
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
```
**Symbols:**

```
c09b6db4-c09b6e3c: tpm2_flush_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tpm2_flush_space(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (c00000000095f900)
Location: drivers/char/tpm/tpm2-space.c:161
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
```
**Symbols:**

```
c00000000095f900-c00000000095f9b0: tpm2_flush_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tpm2_flush_space(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffffffe00056fddc)
Location: drivers/char/tpm/tpm2-space.c:161
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
```
**Symbols:**

```
ffffffe00056fddc-ffffffe00056fe5a: tpm2_flush_space (STB_GLOBAL)
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
void tpm2_flush_space(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffffffff81698770)
Location: drivers/char/tpm/tpm2-space.c:161
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
```
**Symbols:**

```
ffffffff81698770-ffffffff816987dc: tpm2_flush_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tpm2_flush_space(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffffffff81676160)
Location: drivers/char/tpm/tpm2-space.c:161
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
```
**Symbols:**

```
ffffffff81676160-ffffffff816761cc: tpm2_flush_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tpm2_flush_space(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffffffff816c69e0)
Location: drivers/char/tpm/tpm2-space.c:161
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
```
**Symbols:**

```
ffffffff816c69e0-ffffffff816c6a4c: tpm2_flush_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tpm2_flush_space(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffffffff816e0ed0)
Location: drivers/char/tpm/tpm2-space.c:161
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
  - drivers/char/tpm/tpm2-space.c:tpm2_prepare_space
```
**Symbols:**

```
ffffffff816e0ed0-ffffffff816e0f3c: tpm2_flush_space (STB_GLOBAL)
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
