# Function: <code>tpm2_flush_context</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff815270a8)
Location: drivers/char/tpm/tpm2-cmd.c:593
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81579fb3)
Location: drivers/char/tpm/tpm2-cmd.c:593
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
```
</details>
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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void tpm2_flush_context(struct tpm_chip *chip, u32 handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: drivers/char/tpm/tpm2-cmd.c:362
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_flush_space
  - drivers/char/tpm/tpm2-space.c:tpm2_flush_space
  - drivers/char/tpm/tpm2-space.c:tpm2_del_space
```
**Symbols:**

```
ffffffff816afa29-ffffffff816afa40: tpm2_flush_context.cold (STB_LOCAL)
ffffffff816ae7e0-ffffffff816ae8da: tpm2_flush_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void tpm2_flush_context(struct tpm_chip *chip, u32 handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: drivers/char/tpm/tpm2-cmd.c:362
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_flush_space
  - drivers/char/tpm/tpm2-space.c:tpm2_flush_space
  - drivers/char/tpm/tpm2-space.c:tpm2_del_space
```
**Symbols:**

```
ffffffff816d2729-ffffffff816d2740: tpm2_flush_context.cold (STB_LOCAL)
ffffffff816d14d0-ffffffff816d15ca: tpm2_flush_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void tpm2_flush_context(struct tpm_chip *chip, u32 handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: drivers/char/tpm/tpm2-cmd.c:348
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-space.c:tpm2_save_space
  - drivers/char/tpm/tpm2-space.c:tpm2_flush_space
  - drivers/char/tpm/tpm2-space.c:tpm2_flush_space
  - drivers/char/tpm/tpm2-space.c:tpm2_del_space
```
**Symbols:**

```
ffffffff81786979-ffffffff81786990: tpm2_flush_context.cold (STB_LOCAL)
ffffffff81785690-ffffffff81785766: tpm2_flush_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void tpm2_flush_context(struct tpm_chip *chip, u32 handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: drivers/char/tpm/tpm2-cmd.c:348
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-space.c:tpm2_save_space
  - drivers/char/tpm/tpm2-space.c:tpm2_flush_space
  - drivers/char/tpm/tpm2-space.c:tpm2_flush_space
  - drivers/char/tpm/tpm2-space.c:tpm2_del_space
```
**Symbols:**

```
ffffffff81c0a682-ffffffff81c0a699: tpm2_flush_context.cold (STB_LOCAL)
ffffffff8179c890-ffffffff8179c966: tpm2_flush_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void tpm2_flush_context(struct tpm_chip *chip, u32 handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: drivers/char/tpm/tpm2-cmd.c:348
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_flush_space
  - drivers/char/tpm/tpm2-space.c:tpm2_flush_space
  - drivers/char/tpm/tpm2-space.c:tpm2_del_space
```
**Symbols:**

```
ffffffff81bfc115-ffffffff81bfc12c: tpm2_flush_context.cold (STB_LOCAL)
ffffffff8177f360-ffffffff8177f436: tpm2_flush_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void tpm2_flush_context(struct tpm_chip *chip, u32 handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: drivers/char/tpm/tpm2-cmd.c:348
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_flush_space
  - drivers/char/tpm/tpm2-space.c:tpm2_flush_space
  - drivers/char/tpm/tpm2-space.c:tpm2_del_space
```
**Symbols:**

```
ffffffff81cfce3e-ffffffff81cfce55: tpm2_flush_context.cold (STB_LOCAL)
ffffffff818056f0-ffffffff818057c6: tpm2_flush_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void tpm2_flush_context(struct tpm_chip *chip, u32 handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: drivers/char/tpm/tpm2-cmd.c:348
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_flush_space
  - drivers/char/tpm/tpm2-space.c:tpm2_flush_space
  - drivers/char/tpm/tpm2-space.c:tpm2_del_space
```
**Symbols:**

```
ffffffff81ec5691-ffffffff81ec56a7: tpm2_flush_context.cold (STB_LOCAL)
ffffffff81945130-ffffffff8194521f: tpm2_flush_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tpm2_flush_context(struct tpm_chip *chip, u32 handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81aa8110)
Location: drivers/char/tpm/tpm2-cmd.c:348
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_flush_space
  - drivers/char/tpm/tpm2-space.c:tpm2_flush_space
  - drivers/char/tpm/tpm2-space.c:tpm2_del_space
```
**Symbols:**

```
ffffffff81aa8110-ffffffff81aa8212: tpm2_flush_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tpm2_flush_context(struct tpm_chip *chip, u32 handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81af3940)
Location: drivers/char/tpm/tpm2-cmd.c:348
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_flush_space
  - drivers/char/tpm/tpm2-space.c:tpm2_flush_space
  - drivers/char/tpm/tpm2-space.c:tpm2_del_space
```
**Symbols:**

```
ffffffff81af3940-ffffffff81af3a42: tpm2_flush_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tpm2_flush_context(struct tpm_chip *chip, u32 handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81b46f00)
Location: drivers/char/tpm/tpm2-cmd.c:348
Inline: False
Direct callers:
  - security/keys/trusted-keys/trusted_tpm2.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_flush_space
  - drivers/char/tpm/tpm2-space.c:tpm2_flush_space
  - drivers/char/tpm/tpm2-space.c:tpm2_del_space
```
**Symbols:**

```
ffffffff81b46f00-ffffffff81b47002: tpm2_flush_context (STB_GLOBAL)
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
void tpm2_flush_context(struct tpm_chip *chip, u32 handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffff8000108bbdf0)
Location: drivers/char/tpm/tpm2-cmd.c:362
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_flush_space
  - drivers/char/tpm/tpm2-space.c:tpm2_flush_space
  - drivers/char/tpm/tpm2-space.c:tpm2_del_space
```
**Symbols:**

```
ffff8000108bbdf0-ffff8000108bbf34: tpm2_flush_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tpm2_flush_context(struct tpm_chip *chip, u32 handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (c09b518c)
Location: drivers/char/tpm/tpm2-cmd.c:362
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_flush_space
  - drivers/char/tpm/tpm2-space.c:tpm2_flush_space
  - drivers/char/tpm/tpm2-space.c:tpm2_del_space
```
**Symbols:**

```
c09b518c-c09b52f4: tpm2_flush_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tpm2_flush_context(struct tpm_chip *chip, u32 handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (c00000000095d700)
Location: drivers/char/tpm/tpm2-cmd.c:362
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_flush_space
  - drivers/char/tpm/tpm2-space.c:tpm2_flush_space
  - drivers/char/tpm/tpm2-space.c:tpm2_del_space
```
**Symbols:**

```
c00000000095d700-c00000000095d898: tpm2_flush_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tpm2_flush_context(struct tpm_chip *chip, u32 handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffe00056d302)
Location: drivers/char/tpm/tpm2-cmd.c:362
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_flush_space
  - drivers/char/tpm/tpm2-space.c:tpm2_flush_space
  - drivers/char/tpm/tpm2-space.c:tpm2_del_space
```
**Symbols:**

```
ffffffe00056d302-ffffffe00056d4cc: tpm2_flush_context (STB_GLOBAL)
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
void tpm2_flush_context(struct tpm_chip *chip, u32 handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: drivers/char/tpm/tpm2-cmd.c:362
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_flush_space
  - drivers/char/tpm/tpm2-space.c:tpm2_flush_space
  - drivers/char/tpm/tpm2-space.c:tpm2_del_space
```
**Symbols:**

```
ffffffff81698179-ffffffff81698190: tpm2_flush_context.cold (STB_LOCAL)
ffffffff81696f20-ffffffff8169701a: tpm2_flush_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void tpm2_flush_context(struct tpm_chip *chip, u32 handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: drivers/char/tpm/tpm2-cmd.c:362
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_flush_space
  - drivers/char/tpm/tpm2-space.c:tpm2_flush_space
  - drivers/char/tpm/tpm2-space.c:tpm2_del_space
```
**Symbols:**

```
ffffffff81675b69-ffffffff81675b80: tpm2_flush_context.cold (STB_LOCAL)
ffffffff81674910-ffffffff81674a0a: tpm2_flush_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void tpm2_flush_context(struct tpm_chip *chip, u32 handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: drivers/char/tpm/tpm2-cmd.c:362
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_flush_space
  - drivers/char/tpm/tpm2-space.c:tpm2_flush_space
  - drivers/char/tpm/tpm2-space.c:tpm2_del_space
```
**Symbols:**

```
ffffffff816c63e9-ffffffff816c6400: tpm2_flush_context.cold (STB_LOCAL)
ffffffff816c5190-ffffffff816c528a: tpm2_flush_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void tpm2_flush_context(struct tpm_chip *chip, u32 handle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: drivers/char/tpm/tpm2-cmd.c:362
Inline: False
Direct callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_unseal_trusted
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
  - drivers/char/tpm/tpm2-space.c:tpm2_flush_space
  - drivers/char/tpm/tpm2-space.c:tpm2_flush_space
  - drivers/char/tpm/tpm2-space.c:tpm2_del_space
```
**Symbols:**

```
ffffffff816e08d9-ffffffff816e08f0: tpm2_flush_context.cold (STB_LOCAL)
ffffffff816df6d0-ffffffff816df7c0: tpm2_flush_context (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
