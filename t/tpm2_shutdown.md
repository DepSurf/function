# Function: <code>tpm2_shutdown</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tpm2_shutdown(struct tpm_chip *chip, u16 shutdown_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81525c30)
Location: drivers/char/tpm/tpm2-cmd.c:759
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
  - drivers/char/tpm/tpm_tis.c:tpm_tis_remove
```
**Symbols:**

```
ffffffff81525c30-ffffffff81525ccb: tpm2_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tpm2_shutdown(struct tpm_chip *chip, u16 shutdown_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff8157a290)
Location: drivers/char/tpm/tpm2-cmd.c:758
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
```
**Symbols:**

```
ffffffff8157a290-ffffffff8157a32b: tpm2_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tpm2_shutdown(struct tpm_chip *chip, u16 shutdown_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff815a66f0)
Location: drivers/char/tpm/tpm2-cmd.c:788
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
```
**Symbols:**

```
ffffffff815a66f0-ffffffff815a678d: tpm2_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tpm2_shutdown(struct tpm_chip *chip, u16 shutdown_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff815baaf0)
Location: drivers/char/tpm/tpm2-cmd.c:781
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
```
**Symbols:**

```
ffffffff815baaf0-ffffffff815bab8e: tpm2_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tpm2_shutdown(struct tpm_chip *chip, u16 shutdown_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816211c0)
Location: drivers/char/tpm/tpm2-cmd.c:785
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
```
**Symbols:**

```
ffffffff816211c0-ffffffff8162125e: tpm2_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tpm2_shutdown(struct tpm_chip *chip, u16 shutdown_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff8165af80)
Location: drivers/char/tpm/tpm2-cmd.c:782
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
```
**Symbols:**

```
ffffffff8165af80-ffffffff8165b020: tpm2_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tpm2_shutdown(struct tpm_chip *chip, u16 shutdown_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81678f00)
Location: drivers/char/tpm/tpm2-cmd.c:727
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
```
**Symbols:**

```
ffffffff81678f00-ffffffff81678f96: tpm2_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tpm2_shutdown(struct tpm_chip *chip, u16 shutdown_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816af340)
Location: drivers/char/tpm/tpm2-cmd.c:726
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/char/tpm/tpm-chip.c:tpm_class_shutdown
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
```
**Symbols:**

```
ffffffff816af340-ffffffff816af43d: tpm2_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tpm2_shutdown(struct tpm_chip *chip, u16 shutdown_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816d2030)
Location: drivers/char/tpm/tpm2-cmd.c:726
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/char/tpm/tpm-chip.c:tpm_class_shutdown
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
```
**Symbols:**

```
ffffffff816d2030-ffffffff816d212d: tpm2_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tpm2_shutdown(struct tpm_chip *chip, u16 shutdown_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81786440)
Location: drivers/char/tpm/tpm2-cmd.c:420
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/char/tpm/tpm-chip.c:tpm_class_shutdown
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
```
**Symbols:**

```
ffffffff81786440-ffffffff81786510: tpm2_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tpm2_shutdown(struct tpm_chip *chip, u16 shutdown_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff8179d640)
Location: drivers/char/tpm/tpm2-cmd.c:420
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/char/tpm/tpm-chip.c:tpm_class_shutdown
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
```
**Symbols:**

```
ffffffff8179d640-ffffffff8179d710: tpm2_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tpm2_shutdown(struct tpm_chip *chip, u16 shutdown_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81780130)
Location: drivers/char/tpm/tpm2-cmd.c:420
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/char/tpm/tpm-chip.c:tpm_class_shutdown
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
```
**Symbols:**

```
ffffffff81780130-ffffffff81780200: tpm2_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tpm2_shutdown(struct tpm_chip *chip, u16 shutdown_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81806500)
Location: drivers/char/tpm/tpm2-cmd.c:420
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/char/tpm/tpm-chip.c:tpm_class_shutdown
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
```
**Symbols:**

```
ffffffff81806500-ffffffff818065d0: tpm2_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tpm2_shutdown(struct tpm_chip *chip, u16 shutdown_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81946020)
Location: drivers/char/tpm/tpm2-cmd.c:429
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/char/tpm/tpm-chip.c:tpm_class_shutdown
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
```
**Symbols:**

```
ffffffff81946020-ffffffff8194610e: tpm2_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tpm2_shutdown(struct tpm_chip *chip, u16 shutdown_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81aa90b0)
Location: drivers/char/tpm/tpm2-cmd.c:429
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/char/tpm/tpm-chip.c:tpm_class_shutdown
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
```
**Symbols:**

```
ffffffff81aa90b0-ffffffff81aa919e: tpm2_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tpm2_shutdown(struct tpm_chip *chip, u16 shutdown_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81af48e0)
Location: drivers/char/tpm/tpm2-cmd.c:429
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/char/tpm/tpm-chip.c:tpm_class_shutdown
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
```
**Symbols:**

```
ffffffff81af48e0-ffffffff81af49ce: tpm2_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tpm2_shutdown(struct tpm_chip *chip, u16 shutdown_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81b47ea0)
Location: drivers/char/tpm/tpm2-cmd.c:429
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/char/tpm/tpm-chip.c:tpm_class_shutdown
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
```
**Symbols:**

```
ffffffff81b47ea0-ffffffff81b47f8e: tpm2_shutdown (STB_GLOBAL)
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
void tpm2_shutdown(struct tpm_chip *chip, u16 shutdown_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffff8000108bca50)
Location: drivers/char/tpm/tpm2-cmd.c:726
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/char/tpm/tpm-chip.c:tpm_class_shutdown
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
```
**Symbols:**

```
ffff8000108bca50-ffff8000108bcb7c: tpm2_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tpm2_shutdown(struct tpm_chip *chip, u16 shutdown_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (c09b5dcc)
Location: drivers/char/tpm/tpm2-cmd.c:726
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/char/tpm/tpm-chip.c:tpm_class_shutdown
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
```
**Symbols:**

```
c09b5dcc-c09b5f1c: tpm2_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tpm2_shutdown(struct tpm_chip *chip, u16 shutdown_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (c00000000095e670)
Location: drivers/char/tpm/tpm2-cmd.c:726
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/char/tpm/tpm-chip.c:tpm_class_shutdown
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
```
**Symbols:**

```
c00000000095e670-c00000000095e7f0: tpm2_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tpm2_shutdown(struct tpm_chip *chip, u16 shutdown_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffe00056e9b2)
Location: drivers/char/tpm/tpm2-cmd.c:726
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/char/tpm/tpm-chip.c:tpm_class_shutdown
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
```
**Symbols:**

```
ffffffe00056e9b2-ffffffe00056eb40: tpm2_shutdown (STB_GLOBAL)
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
void tpm2_shutdown(struct tpm_chip *chip, u16 shutdown_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81697a80)
Location: drivers/char/tpm/tpm2-cmd.c:726
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/char/tpm/tpm-chip.c:tpm_class_shutdown
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
```
**Symbols:**

```
ffffffff81697a80-ffffffff81697b7d: tpm2_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tpm2_shutdown(struct tpm_chip *chip, u16 shutdown_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff81675470)
Location: drivers/char/tpm/tpm2-cmd.c:726
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/char/tpm/tpm-chip.c:tpm_class_shutdown
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
```
**Symbols:**

```
ffffffff81675470-ffffffff8167556d: tpm2_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tpm2_shutdown(struct tpm_chip *chip, u16 shutdown_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816c5cf0)
Location: drivers/char/tpm/tpm2-cmd.c:726
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/char/tpm/tpm-chip.c:tpm_class_shutdown
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
```
**Symbols:**

```
ffffffff816c5cf0-ffffffff816c5ded: tpm2_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tpm2_shutdown(struct tpm_chip *chip, u16 shutdown_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-cmd.c (ffffffff816e0200)
Location: drivers/char/tpm/tpm2-cmd.c:726
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/char/tpm/tpm-chip.c:tpm_class_shutdown
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
```
**Symbols:**

```
ffffffff816e0200-ffffffff816e02ee: tpm2_shutdown (STB_GLOBAL)
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
