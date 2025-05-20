# Function: <code>hpet_msi_unmask</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void hpet_msi_unmask(struct irq_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81062e20)
Location: arch/x86/kernel/hpet.c:453
Inline: False
```
**Symbols:**

```
ffffffff81062e20-ffffffff81062e63: hpet_msi_unmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void hpet_msi_unmask(struct irq_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81062ab0)
Location: arch/x86/kernel/hpet.c:453
Inline: False
```
**Symbols:**

```
ffffffff81062ab0-ffffffff81062af3: hpet_msi_unmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void hpet_msi_unmask(struct irq_data *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81065c40)
Location: arch/x86/kernel/hpet.c:454
Inline: False
```
**Symbols:**

```
ffffffff81065c40-ffffffff81065c83: hpet_msi_unmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void hpet_msi_unmask(struct irq_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81064140)
Location: arch/x86/kernel/hpet.c:443
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_msi_resume
```
**Symbols:**

```
ffffffff81064d10-ffffffff81064d53: hpet_msi_unmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void hpet_msi_unmask(struct irq_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff810682c0)
Location: arch/x86/kernel/hpet.c:443
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_msi_resume
```
**Symbols:**

```
ffffffff81068ea0-ffffffff81068ee3: hpet_msi_unmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void hpet_msi_unmask(struct irq_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8106ae10)
Location: arch/x86/kernel/hpet.c:444
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_msi_resume
```
**Symbols:**

```
ffffffff8106b940-ffffffff8106b983: hpet_msi_unmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void hpet_msi_unmask(struct irq_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81070ba0)
Location: arch/x86/kernel/hpet.c:440
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_msi_resume
```
**Symbols:**

```
ffffffff810716d0-ffffffff81071713: hpet_msi_unmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void hpet_msi_unmask(struct irq_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81074bf0)
Location: arch/x86/kernel/hpet.c:472
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
```
**Symbols:**

```
ffffffff81075540-ffffffff81075583: hpet_msi_unmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void hpet_msi_unmask(struct irq_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81075bc0)
Location: arch/x86/kernel/hpet.c:472
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
```
**Symbols:**

```
ffffffff81076510-ffffffff81076553: hpet_msi_unmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void hpet_msi_unmask(struct irq_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8107d340)
Location: arch/x86/kernel/hpet.c:472
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
```
**Symbols:**

```
ffffffff8107d7d0-ffffffff8107d813: hpet_msi_unmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void hpet_msi_unmask(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8107d2b0)
Location: arch/x86/kernel/hpet.c:472
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
```
**Symbols:**

```
ffffffff8107ca10-ffffffff8107ca53: hpet_msi_unmask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void hpet_msi_unmask(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8107e3b0)
Location: arch/x86/kernel/hpet.c:472
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
```
**Symbols:**

```
ffffffff8107db00-ffffffff8107db43: hpet_msi_unmask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void hpet_msi_unmask(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8108cef0)
Location: arch/x86/kernel/hpet.c:473
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
```
**Symbols:**

```
ffffffff8108c500-ffffffff8108c543: hpet_msi_unmask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void hpet_msi_unmask(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8109db4f)
Location: arch/x86/kernel/hpet.c:473
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
```
**Symbols:**

```
ffffffff8109ce90-ffffffff8109cedf: hpet_msi_unmask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void hpet_msi_unmask(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff810b4d1f)
Location: arch/x86/kernel/hpet.c:473
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
```
**Symbols:**

```
ffffffff810b3d80-ffffffff810b3dcf: hpet_msi_unmask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void hpet_msi_unmask(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff810b7def)
Location: arch/x86/kernel/hpet.c:473
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
```
**Symbols:**

```
ffffffff810b6e80-ffffffff810b6ecf: hpet_msi_unmask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void hpet_msi_unmask(struct irq_data *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff810bf22f)
Location: arch/x86/kernel/hpet.c:473
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
```
**Symbols:**

```
ffffffff810be2c0-ffffffff810be30f: hpet_msi_unmask (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void hpet_msi_unmask(struct irq_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81074bc0)
Location: arch/x86/kernel/hpet.c:472
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
```
**Symbols:**

```
ffffffff81075510-ffffffff81075553: hpet_msi_unmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void hpet_msi_unmask(struct irq_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81064bf0)
Location: arch/x86/kernel/hpet.c:472
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
```
**Symbols:**

```
ffffffff81065500-ffffffff81065543: hpet_msi_unmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void hpet_msi_unmask(struct irq_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81074b70)
Location: arch/x86/kernel/hpet.c:472
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
```
**Symbols:**

```
ffffffff810754c0-ffffffff81075503: hpet_msi_unmask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void hpet_msi_unmask(struct irq_data *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81076bd0)
Location: arch/x86/kernel/hpet.c:472
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_clkevt_msi_resume
```
**Symbols:**

```
ffffffff81077520-ffffffff81077563: hpet_msi_unmask (STB_GLOBAL)
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
