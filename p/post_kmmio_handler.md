# Function: <code>post_kmmio_handler</code>

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
In arch/x86/mm/kmmio.c (ffffffff81073393)
Location: arch/x86/mm/kmmio.c:310
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_die_notifier
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
In arch/x86/mm/kmmio.c (ffffffff81074957)
Location: arch/x86/mm/kmmio.c:327
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_die_notifier
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
In arch/x86/mm/kmmio.c (ffffffff810784d7)
Location: arch/x86/mm/kmmio.c:327
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_die_notifier
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
In arch/x86/mm/kmmio.c (ffffffff81076ba6)
Location: arch/x86/mm/kmmio.c:327
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_die_notifier
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
In arch/x86/mm/kmmio.c (ffffffff8107d126)
Location: arch/x86/mm/kmmio.c:328
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_die_notifier
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
In arch/x86/mm/kmmio.c (ffffffff81080396)
Location: arch/x86/mm/kmmio.c:333
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_die_notifier
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
In arch/x86/mm/kmmio.c (ffffffff81086ed6)
Location: arch/x86/mm/kmmio.c:333
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_die_notifier
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
In arch/x86/mm/kmmio.c (ffffffff8108aab8)
Location: arch/x86/mm/kmmio.c:333
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_die_notifier
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
In arch/x86/mm/kmmio.c (ffffffff8108b728)
Location: arch/x86/mm/kmmio.c:333
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_die_notifier
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int post_kmmio_handler(long unsigned int condition, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/kmmio.c (0)
Location: arch/x86/mm/kmmio.c:330
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:kmmio_die_notifier
```
**Symbols:**

```
ffffffff81092b10-ffffffff81092bc9: post_kmmio_handler (STB_LOCAL)
ffffffff81092ee1-ffffffff81092ef9: post_kmmio_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int post_kmmio_handler(long unsigned int condition, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/kmmio.c (0)
Location: arch/x86/mm/kmmio.c:330
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:kmmio_die_notifier
```
**Symbols:**

```
ffffffff810921a0-ffffffff8109225e: post_kmmio_handler (STB_LOCAL)
ffffffff81bd9f69-ffffffff81bd9f81: post_kmmio_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int post_kmmio_handler(long unsigned int condition, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/kmmio.c (0)
Location: arch/x86/mm/kmmio.c:330
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:kmmio_die_notifier
```
**Symbols:**

```
ffffffff81092c70-ffffffff81092d2e: post_kmmio_handler (STB_LOCAL)
ffffffff81bcbfc4-ffffffff81bcbfdc: post_kmmio_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int post_kmmio_handler(long unsigned int condition, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/kmmio.c (0)
Location: arch/x86/mm/kmmio.c:330
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:kmmio_die_notifier
```
**Symbols:**

```
ffffffff810a2990-ffffffff810a2a4e: post_kmmio_handler (STB_LOCAL)
ffffffff81ca1efb-ffffffff81ca1f13: post_kmmio_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff810b7009)
Location: arch/x86/mm/kmmio.c:330
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_die_notifier
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff810d1f3b)
Location: arch/x86/mm/kmmio.c:334
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_die_notifier
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff810d53ab)
Location: arch/x86/mm/kmmio.c:334
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_die_notifier
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff810ddb7b)
Location: arch/x86/mm/kmmio.c:334
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_die_notifier
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff8108a6e8)
Location: arch/x86/mm/kmmio.c:333
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_die_notifier
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
In arch/x86/mm/kmmio.c (ffffffff81079258)
Location: arch/x86/mm/kmmio.c:333
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_die_notifier
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
In arch/x86/mm/kmmio.c (ffffffff8108a698)
Location: arch/x86/mm/kmmio.c:333
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_die_notifier
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
In arch/x86/mm/kmmio.c (ffffffff8108c937)
Location: arch/x86/mm/kmmio.c:333
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_die_notifier
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
