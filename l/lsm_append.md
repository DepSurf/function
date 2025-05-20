# Function: <code>lsm_append</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff820e2fb3)
Location: security/security.c:168
Inline: True
Inline callers:
  - security/security.c:security_add_hooks
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff826ebc6c)
Location: security/security.c:183
Inline: True
Inline callers:
  - security/security.c:security_add_hooks
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff82715fba)
Location: security/security.c:115
Inline: True
Inline callers:
  - security/security.c:security_add_hooks
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff828cdaef)
Location: security/security.c:401
Inline: True
Inline callers:
  - security/security.c:security_add_hooks
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff828e7523)
Location: security/security.c:397
Inline: True
Inline callers:
  - security/security.c:security_add_hooks
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
In security/security.c (ffffffff81459954)
Location: security/security.c:424
Inline: True
Direct callers:
  - security/security.c:security_add_hooks
  - security/security.c:security_init
```
**Symbols:**

```
ffffffff81459954-ffffffff814599f5: lsm_append.constprop.0 (STB_LOCAL)
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
In security/security.c (ffffffff814acbba)
Location: security/security.c:457
Inline: True
Direct callers:
  - security/security.c:security_add_hooks
  - security/security.c:security_init
```
**Symbols:**

```
ffffffff814acbba-ffffffff814acc5b: lsm_append.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/security.c (ffffffff81bf007d)
Location: security/security.c:459
Inline: True
Direct callers:
  - security/security.c:security_add_hooks
  - security/security.c:security_init
```
**Symbols:**

```
ffffffff81bf007d-ffffffff81bf011e: lsm_append.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/security.c (ffffffff81be20e9)
Location: security/security.c:462
Inline: True
Direct callers:
  - security/security.c:security_add_hooks
  - security/security.c:security_init
```
**Symbols:**

```
ffffffff81be20e9-ffffffff81be218a: lsm_append.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/security.c (ffffffff81cd3486)
Location: security/security.c:462
Inline: True
Direct callers:
  - security/security.c:security_add_hooks
  - security/security.c:security_init
```
**Symbols:**

```
ffffffff81cd3486-ffffffff81cd3527: lsm_append.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/security.c (ffffffff81e8658f)
Location: security/security.c:465
Inline: True
Direct callers:
  - security/security.c:security_add_hooks
  - security/security.c:security_init
```
**Symbols:**

```
ffffffff81e8658f-ffffffff81e8663a: lsm_append.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/security.c (ffffffff81664f70)
Location: security/security.c:504
Inline: True
Direct callers:
  - security/security.c:security_add_hooks
  - security/security.c:security_init
```
**Symbols:**

```
ffffffff81664f70-ffffffff8166501a: lsm_append.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/security.c (ffffffff8169d480)
Location: security/security.c:512
Inline: True
Direct callers:
  - security/security.c:security_add_hooks
  - security/security.c:security_init
```
**Symbols:**

```
ffffffff8169d480-ffffffff8169d52a: lsm_append.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/security.c (ffffffff816d9c60)
Location: security/security.c:580
Inline: True
Direct callers:
  - security/security.c:security_add_hooks
  - security/security.c:security_init
```
**Symbols:**

```
ffffffff816d9c60-ffffffff816d9d0a: lsm_append.constprop.0 (STB_LOCAL)
```
</details>
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
In security/security.c (ffff800010545ba0)
Location: security/security.c:424
Inline: True
Direct callers:
  - security/security.c:security_add_hooks
  - security/security.c:security_init
```
**Symbols:**

```
ffff800010545ba0-ffff800010545c60: lsm_append.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/security.c (c06fba04)
Location: security/security.c:424
Inline: True
Direct callers:
  - security/security.c:security_add_hooks
  - security/security.c:security_init
```
**Symbols:**

```
c06fba04-c06fbad0: lsm_append.constprop.0 (STB_LOCAL)
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
In security/security.c (c00000000069c468)
Location: security/security.c:424
Inline: True
Direct callers:
  - security/security.c:security_add_hooks
  - security/security.c:security_init
```
**Symbols:**

```
c00000000069c468-c00000000069c56c: lsm_append.constprop.0 (STB_LOCAL)
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
In security/security.c (ffffffe0003a176c)
Location: security/security.c:424
Inline: True
Direct callers:
  - security/security.c:security_add_hooks
  - security/security.c:security_init
```
**Symbols:**

```
ffffffe0003a176c-ffffffe0003a1820: lsm_append.constprop.0 (STB_LOCAL)
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
In security/security.c (ffffffff81451f34)
Location: security/security.c:424
Inline: True
Direct callers:
  - security/security.c:security_add_hooks
  - security/security.c:security_init
```
**Symbols:**

```
ffffffff81451f34-ffffffff81451fd5: lsm_append.constprop.0 (STB_LOCAL)
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
In security/security.c (ffffffff81442984)
Location: security/security.c:424
Inline: True
Direct callers:
  - security/security.c:security_add_hooks
  - security/security.c:security_init
```
**Symbols:**

```
ffffffff81442984-ffffffff81442a25: lsm_append.constprop.0 (STB_LOCAL)
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
In security/security.c (ffffffff8144dfd4)
Location: security/security.c:424
Inline: True
Direct callers:
  - security/security.c:security_add_hooks
  - security/security.c:security_init
```
**Symbols:**

```
ffffffff8144dfd4-ffffffff8144e075: lsm_append.constprop.0 (STB_LOCAL)
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
In security/security.c (ffffffff814653a4)
Location: security/security.c:424
Inline: True
Direct callers:
  - security/security.c:security_add_hooks
  - security/security.c:security_init
```
**Symbols:**

```
ffffffff814653a4-ffffffff81465445: lsm_append.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
