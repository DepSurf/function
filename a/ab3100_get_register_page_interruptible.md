# Function: <code>ab3100_get_register_page_interruptible</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ab3100_get_register_page_interruptible(struct ab3100 *ab3100, u8 first_reg, u8 *regvals, u8 numregs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/ab3100-core.c (ffffffff81592300)
Location: drivers/mfd/ab3100-core.c:215
Inline: False
Direct callers:
  - drivers/mfd/ab3100-core.c:get_register_page_interruptible
  - drivers/mfd/ab3100-core.c:ab3100_irq_handler
```
**Symbols:**

```
ffffffff81592300-ffffffff81592414: ab3100_get_register_page_interruptible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ab3100_get_register_page_interruptible(struct ab3100 *ab3100, u8 first_reg, u8 *regvals, u8 numregs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/ab3100-core.c (ffffffff815e7110)
Location: drivers/mfd/ab3100-core.c:215
Inline: False
Direct callers:
  - drivers/mfd/ab3100-core.c:ab3100_irq_handler
  - drivers/mfd/ab3100-core.c:get_register_page_interruptible
```
**Symbols:**

```
ffffffff815e7110-ffffffff815e7228: ab3100_get_register_page_interruptible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ab3100_get_register_page_interruptible(struct ab3100 *ab3100, u8 first_reg, u8 *regvals, u8 numregs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/ab3100-core.c (ffffffff81613f20)
Location: drivers/mfd/ab3100-core.c:215
Inline: False
Direct callers:
  - drivers/mfd/ab3100-core.c:ab3100_irq_handler
  - drivers/mfd/ab3100-core.c:get_register_page_interruptible
```
**Symbols:**

```
ffffffff81613f20-ffffffff81614038: ab3100_get_register_page_interruptible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ab3100_get_register_page_interruptible(struct ab3100 *ab3100, u8 first_reg, u8 *regvals, u8 numregs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/ab3100-core.c (ffffffff81627ef0)
Location: drivers/mfd/ab3100-core.c:215
Inline: False
Direct callers:
  - drivers/mfd/ab3100-core.c:ab3100_irq_handler
  - drivers/mfd/ab3100-core.c:get_register_page_interruptible
```
**Symbols:**

```
ffffffff81627ef0-ffffffff81628008: ab3100_get_register_page_interruptible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ab3100_get_register_page_interruptible(struct ab3100 *ab3100, u8 first_reg, u8 *regvals, u8 numregs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/ab3100-core.c (ffffffff81690800)
Location: drivers/mfd/ab3100-core.c:215
Inline: False
Direct callers:
  - drivers/mfd/ab3100-core.c:ab3100_irq_handler
  - drivers/mfd/ab3100-core.c:get_register_page_interruptible
```
**Symbols:**

```
ffffffff81690800-ffffffff81690918: ab3100_get_register_page_interruptible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ab3100_get_register_page_interruptible(struct ab3100 *ab3100, u8 first_reg, u8 *regvals, u8 numregs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/ab3100-core.c (ffffffff816cc8f0)
Location: drivers/mfd/ab3100-core.c:215
Inline: False
Direct callers:
  - drivers/mfd/ab3100-core.c:ab3100_irq_handler
  - drivers/mfd/ab3100-core.c:get_register_page_interruptible
```
**Symbols:**

```
ffffffff816cc8f0-ffffffff816cca0f: ab3100_get_register_page_interruptible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ab3100_get_register_page_interruptible(struct ab3100 *ab3100, u8 first_reg, u8 *regvals, u8 numregs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/ab3100-core.c (ffffffff816edeb0)
Location: drivers/mfd/ab3100-core.c:215
Inline: False
Direct callers:
  - drivers/mfd/ab3100-core.c:ab3100_irq_handler
  - drivers/mfd/ab3100-core.c:get_register_page_interruptible
```
**Symbols:**

```
ffffffff816edeb0-ffffffff816edfcf: ab3100_get_register_page_interruptible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ab3100_get_register_page_interruptible(struct ab3100 *ab3100, u8 first_reg, u8 *regvals, u8 numregs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/ab3100-core.c (0)
Location: drivers/mfd/ab3100-core.c:215
Inline: False
Direct callers:
  - drivers/mfd/ab3100-core.c:ab3100_irq_handler
  - drivers/mfd/ab3100-core.c:get_register_page_interruptible
```
**Symbols:**

```
ffffffff81727580-ffffffff81727630: ab3100_get_register_page_interruptible (STB_LOCAL)
ffffffff81727d5c-ffffffff81727ddd: ab3100_get_register_page_interruptible.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ab3100_get_register_page_interruptible(struct ab3100 *ab3100, u8 first_reg, u8 *regvals, u8 numregs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/ab3100-core.c (0)
Location: drivers/mfd/ab3100-core.c:215
Inline: False
Direct callers:
  - drivers/mfd/ab3100-core.c:ab3100_irq_handler
  - drivers/mfd/ab3100-core.c:get_register_page_interruptible
```
**Symbols:**

```
ffffffff8174b830-ffffffff8174b8e0: ab3100_get_register_page_interruptible (STB_LOCAL)
ffffffff8174c00f-ffffffff8174c090: ab3100_get_register_page_interruptible.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ab3100_get_register_page_interruptible(struct ab3100 *ab3100, u8 first_reg, u8 *regvals, u8 numregs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/ab3100-core.c (0)
Location: drivers/mfd/ab3100-core.c:215
Inline: False
Direct callers:
  - drivers/mfd/ab3100-core.c:ab3100_irq_handler
  - drivers/mfd/ab3100-core.c:get_register_page_interruptible
```
**Symbols:**

```
ffffffff818098f0-ffffffff818099a0: ab3100_get_register_page_interruptible (STB_LOCAL)
ffffffff8180a118-ffffffff8180a199: ab3100_get_register_page_interruptible.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ab3100_get_register_page_interruptible(struct ab3100 *ab3100, u8 first_reg, u8 *regvals, u8 numregs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/ab3100-core.c (0)
Location: drivers/mfd/ab3100-core.c:215
Inline: False
Direct callers:
  - drivers/mfd/ab3100-core.c:ab3100_irq_handler
  - drivers/mfd/ab3100-core.c:get_register_page_interruptible
```
**Symbols:**

```
ffffffff81819730-ffffffff818197e0: ab3100_get_register_page_interruptible (STB_LOCAL)
ffffffff81c147f8-ffffffff81c14879: ab3100_get_register_page_interruptible.cold (STB_LOCAL)
```
</details>
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
<summary>In <code>arm64</code>: ✅</summary>

```c
int ab3100_get_register_page_interruptible(struct ab3100 *ab3100, u8 first_reg, u8 *regvals, u8 numregs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/ab3100-core.c (ffff800010949ac0)
Location: drivers/mfd/ab3100-core.c:215
Inline: False
Direct callers:
  - drivers/mfd/ab3100-core.c:ab3100_irq_handler
  - drivers/mfd/ab3100-core.c:get_register_page_interruptible
```
**Symbols:**

```
ffff800010949ac0-ffff800010949bf4: ab3100_get_register_page_interruptible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ab3100_get_register_page_interruptible(struct ab3100 *ab3100, u8 first_reg, u8 *regvals, u8 numregs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/ab3100-core.c (c0a3295c)
Location: drivers/mfd/ab3100-core.c:215
Inline: False
Direct callers:
  - drivers/mfd/ab3100-core.c:ab3100_irq_handler
  - drivers/mfd/ab3100-core.c:get_register_page_interruptible
```
**Symbols:**

```
c0a3295c-c0a32a84: ab3100_get_register_page_interruptible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ab3100_get_register_page_interruptible(struct ab3100 *ab3100, u8 first_reg, u8 *regvals, u8 numregs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/ab3100-core.c (c0000000009f50d0)
Location: drivers/mfd/ab3100-core.c:215
Inline: False
Direct callers:
  - drivers/mfd/ab3100-core.c:ab3100_irq_handler
  - drivers/mfd/ab3100-core.c:get_register_page_interruptible
```
**Symbols:**

```
c0000000009f50d0-c0000000009f524c: ab3100_get_register_page_interruptible (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ab3100_get_register_page_interruptible(struct ab3100 *ab3100, u8 first_reg, u8 *regvals, u8 numregs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/ab3100-core.c (ffffffe0005bb738)
Location: drivers/mfd/ab3100-core.c:215
Inline: False
Direct callers:
  - drivers/mfd/ab3100-core.c:ab3100_irq_handler
  - drivers/mfd/ab3100-core.c:get_register_page_interruptible
```
**Symbols:**

```
ffffffe0005bb738-ffffffe0005bb840: ab3100_get_register_page_interruptible (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ab3100_get_register_page_interruptible(struct ab3100 *ab3100, u8 first_reg, u8 *regvals, u8 numregs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/ab3100-core.c (0)
Location: drivers/mfd/ab3100-core.c:215
Inline: False
Direct callers:
  - drivers/mfd/ab3100-core.c:ab3100_irq_handler
  - drivers/mfd/ab3100-core.c:get_register_page_interruptible
```
**Symbols:**

```
ffffffff8173ecf0-ffffffff8173eda0: ab3100_get_register_page_interruptible (STB_LOCAL)
ffffffff8173f4cf-ffffffff8173f550: ab3100_get_register_page_interruptible.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ab3100_get_register_page_interruptible(struct ab3100 *ab3100, u8 first_reg, u8 *regvals, u8 numregs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/ab3100-core.c (0)
Location: drivers/mfd/ab3100-core.c:215
Inline: False
Direct callers:
  - drivers/mfd/ab3100-core.c:ab3100_irq_handler
  - drivers/mfd/ab3100-core.c:get_register_page_interruptible
```
**Symbols:**

```
ffffffff8175a130-ffffffff8175a1e0: ab3100_get_register_page_interruptible (STB_LOCAL)
ffffffff8175a90f-ffffffff8175a990: ab3100_get_register_page_interruptible.cold (STB_LOCAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
