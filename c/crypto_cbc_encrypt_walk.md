# Function: <code>crypto_cbc_encrypt_walk</code>

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
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/cbc.c (ffffffff814001d0)
Location: include/crypto/cbc.h:64
Inline: True
Direct callers:
  - crypto/cbc.c:crypto_cbc_encrypt
```
**Symbols:**

```
ffffffff814001d0-ffffffff8140033b: crypto_cbc_encrypt_walk.constprop.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/cbc.c (ffffffff8140d4f0)
Location: include/crypto/cbc.h:64
Inline: True
Direct callers:
  - crypto/cbc.c:crypto_cbc_encrypt
```
**Symbols:**

```
ffffffff8140d4f0-ffffffff8140d675: crypto_cbc_encrypt_walk.constprop.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/cbc.c (ffffffff81435f60)
Location: include/crypto/cbc.h:64
Inline: True
Direct callers:
  - crypto/cbc.c:crypto_cbc_encrypt
```
**Symbols:**

```
ffffffff81435f60-ffffffff814360fc: crypto_cbc_encrypt_walk.constprop.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/cbc.c (ffffffff81468cc0)
Location: include/crypto/cbc.h:64
Inline: True
Direct callers:
  - crypto/cbc.c:crypto_cbc_encrypt
```
**Symbols:**

```
ffffffff81468cc0-ffffffff81468e27: crypto_cbc_encrypt_walk.constprop.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/cbc.c (ffffffff81486930)
Location: include/crypto/cbc.h:64
Inline: True
Direct callers:
  - crypto/cbc.c:crypto_cbc_encrypt
```
**Symbols:**

```
ffffffff81486930-ffffffff81486a97: crypto_cbc_encrypt_walk.constprop.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/cbc.c (ffffffff814b47a0)
Location: include/crypto/cbc.h:59
Inline: True
Direct callers:
  - crypto/cbc.c:crypto_cbc_encrypt
```
**Symbols:**

```
ffffffff814b47a0-ffffffff814b4904: crypto_cbc_encrypt_walk.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/cbc.c (ffffffff814cd510)
Location: include/crypto/cbc.h:59
Inline: True
Direct callers:
  - crypto/cbc.c:crypto_cbc_encrypt
```
**Symbols:**

```
ffffffff814cd510-ffffffff814cd674: crypto_cbc_encrypt_walk.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/cbc.c (ffffffff8152c790)
Location: include/crypto/cbc.h:59
Inline: True
Direct callers:
  - crypto/cbc.c:crypto_cbc_encrypt
```
**Symbols:**

```
ffffffff8152c790-ffffffff8152c901: crypto_cbc_encrypt_walk.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
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
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/cbc.c (ffff8000105c93a8)
Location: include/crypto/cbc.h:59
Inline: True
Direct callers:
  - crypto/cbc.c:crypto_cbc_encrypt
```
**Symbols:**

```
ffff8000105c93a8-ffff8000105c9508: crypto_cbc_encrypt_walk.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/cbc.c (c0776e70)
Location: include/crypto/cbc.h:59
Inline: True
Inline callers:
  - crypto/cbc.c:crypto_cbc_encrypt
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/cbc.c (c000000000753970)
Location: include/crypto/cbc.h:59
Inline: True
Direct callers:
  - crypto/cbc.c:crypto_cbc_encrypt
```
**Symbols:**

```
c000000000753970-c000000000753b34: crypto_cbc_encrypt_walk.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/cbc.c (ffffffe00040dc2e)
Location: include/crypto/cbc.h:59
Inline: True
Direct callers:
  - crypto/cbc.c:crypto_cbc_encrypt
```
**Symbols:**

```
ffffffe00040dc2e-ffffffe00040dd26: crypto_cbc_encrypt_walk.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/cbc.c (ffffffff814c5af0)
Location: include/crypto/cbc.h:59
Inline: True
Direct callers:
  - crypto/cbc.c:crypto_cbc_encrypt
```
**Symbols:**

```
ffffffff814c5af0-ffffffff814c5c54: crypto_cbc_encrypt_walk.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/cbc.c (ffffffff814b6510)
Location: include/crypto/cbc.h:59
Inline: True
Direct callers:
  - crypto/cbc.c:crypto_cbc_encrypt
```
**Symbols:**

```
ffffffff814b6510-ffffffff814b6674: crypto_cbc_encrypt_walk.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/cbc.c (ffffffff814c1b80)
Location: include/crypto/cbc.h:59
Inline: True
Direct callers:
  - crypto/cbc.c:crypto_cbc_encrypt
```
**Symbols:**

```
ffffffff814c1b80-ffffffff814c1ce4: crypto_cbc_encrypt_walk.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/cbc.c (ffffffff814da650)
Location: include/crypto/cbc.h:59
Inline: True
Direct callers:
  - crypto/cbc.c:crypto_cbc_encrypt
```
**Symbols:**

```
ffffffff814da650-ffffffff814da7b4: crypto_cbc_encrypt_walk.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
