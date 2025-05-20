# Function: <code>userfaultfd_must_wait</code>

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
In fs/userfaultfd.c (ffffffff8125addf)
Location: fs/userfaultfd.c:191
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
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
In fs/userfaultfd.c (ffffffff812839a9)
Location: fs/userfaultfd.c:191
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff812974cd)
Location: fs/userfaultfd.c:198
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff812a4d01)
Location: fs/userfaultfd.c:263
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
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
In fs/userfaultfd.c (ffffffff812c8199)
Location: fs/userfaultfd.c:263
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
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
In fs/userfaultfd.c (ffffffff812f1544)
Location: fs/userfaultfd.c:267
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
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
In fs/userfaultfd.c (ffffffff81305f04)
Location: fs/userfaultfd.c:266
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
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
In fs/userfaultfd.c (ffffffff81327497)
Location: fs/userfaultfd.c:276
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff8133a277)
Location: fs/userfaultfd.c:276
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
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
In fs/userfaultfd.c (ffffffff81372270)
Location: fs/userfaultfd.c:276
Inline: True
Direct callers:
  - fs/userfaultfd.c:handle_userfault
```
**Symbols:**

```
ffffffff81372270-ffffffff8137249b: userfaultfd_must_wait.constprop.0.isra.0 (STB_LOCAL)
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
In fs/userfaultfd.c (ffffffff813800c0)
Location: fs/userfaultfd.c:276
Inline: True
Direct callers:
  - fs/userfaultfd.c:handle_userfault
```
**Symbols:**

```
ffffffff813800c0-ffffffff813802eb: userfaultfd_must_wait.constprop.0.isra.0 (STB_LOCAL)
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
In fs/userfaultfd.c (ffffffff81387470)
Location: fs/userfaultfd.c:274
Inline: True
Direct callers:
  - fs/userfaultfd.c:handle_userfault
```
**Symbols:**

```
ffffffff81387470-ffffffff81387674: userfaultfd_must_wait.constprop.0.isra.0 (STB_LOCAL)
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
In fs/userfaultfd.c (0)
Location: fs/userfaultfd.c:275
Inline: True
Direct callers:
  - fs/userfaultfd.c:handle_userfault
```
**Symbols:**

```
ffffffff813d4730-ffffffff813d494b: userfaultfd_must_wait.constprop.0.isra.0 (STB_LOCAL)
ffffffff81cc5686-ffffffff81cc569f: userfaultfd_must_wait.constprop.0.isra.0.cold (STB_LOCAL)
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
In fs/userfaultfd.c (0)
Location: fs/userfaultfd.c:283
Inline: True
Direct callers:
  - fs/userfaultfd.c:handle_userfault
```
**Symbols:**

```
ffffffff8145fbd0-ffffffff8145fdf1: userfaultfd_must_wait.constprop.0.isra.0 (STB_LOCAL)
ffffffff81e7808c-ffffffff81e780a5: userfaultfd_must_wait.constprop.0.isra.0.cold (STB_LOCAL)
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
In fs/userfaultfd.c (0)
Location: fs/userfaultfd.c:299
Inline: True
Direct callers:
  - fs/userfaultfd.c:handle_userfault
```
**Symbols:**

```
ffffffff814ef4b0-ffffffff814ef6e4: userfaultfd_must_wait.constprop.0.isra.0 (STB_LOCAL)
ffffffff82069fee-ffffffff8206a007: userfaultfd_must_wait.constprop.0.isra.0.cold (STB_LOCAL)
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
In fs/userfaultfd.c (0)
Location: fs/userfaultfd.c:327
Inline: True
Direct callers:
  - fs/userfaultfd.c:handle_userfault
```
**Symbols:**

```
ffffffff81524c70-ffffffff81524e82: userfaultfd_must_wait.isra.0 (STB_LOCAL)
ffffffff820e9f7c-ffffffff820e9f95: userfaultfd_must_wait.isra.0.cold (STB_LOCAL)
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
In fs/userfaultfd.c (0)
Location: fs/userfaultfd.c:328
Inline: True
Direct callers:
  - fs/userfaultfd.c:handle_userfault
```
**Symbols:**

```
ffffffff815588f0-ffffffff81558b59: userfaultfd_must_wait.isra.0 (STB_LOCAL)
ffffffff821c6a4e-ffffffff821c6a6a: userfaultfd_must_wait.isra.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffff8000103f93c8)
Location: fs/userfaultfd.c:276
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
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
In fs/userfaultfd.c (c05cd300)
Location: fs/userfaultfd.c:276
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (c00000000050186c)
Location: fs/userfaultfd.c:276
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffe0002a875e)
Location: fs/userfaultfd.c:276
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81332857)
Location: fs/userfaultfd.c:276
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81323411)
Location: fs/userfaultfd.c:276
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81330327)
Location: fs/userfaultfd.c:276
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81342c7e)
Location: fs/userfaultfd.c:276
Inline: True
Inline callers:
  - fs/userfaultfd.c:handle_userfault
```
</details>
</li>
</ul>

## Differences
