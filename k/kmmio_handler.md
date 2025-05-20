# Function: <code>kmmio_handler</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int kmmio_handler(struct pt_regs *regs, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff810736a0)
Location: arch/x86/mm/kmmio.c:213
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
**Symbols:**

```
ffffffff810736a0-ffffffff81073868: kmmio_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int kmmio_handler(struct pt_regs *regs, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff81074c50)
Location: arch/x86/mm/kmmio.c:224
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
**Symbols:**

```
ffffffff81074c50-ffffffff81074e37: kmmio_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kmmio_handler(struct pt_regs *regs, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff810787d0)
Location: arch/x86/mm/kmmio.c:224
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
**Symbols:**

```
ffffffff810787d0-ffffffff810789b7: kmmio_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kmmio_handler(struct pt_regs *regs, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff81077100)
Location: arch/x86/mm/kmmio.c:224
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
**Symbols:**

```
ffffffff81077100-ffffffff810772e0: kmmio_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kmmio_handler(struct pt_regs *regs, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff8107d440)
Location: arch/x86/mm/kmmio.c:225
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
**Symbols:**

```
ffffffff8107d440-ffffffff8107d626: kmmio_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int kmmio_handler(struct pt_regs *regs, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/kmmio.c (0)
Location: arch/x86/mm/kmmio.c:230
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
**Symbols:**

```
ffffffff810806dd-ffffffff8108072b: kmmio_handler.cold.11 (STB_LOCAL)
ffffffff81080450-ffffffff810805ed: kmmio_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kmmio_handler(struct pt_regs *regs, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff81086fb0)
Location: arch/x86/mm/kmmio.c:230
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
**Symbols:**

```
ffffffff81086fb0-ffffffff8108719e: kmmio_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int kmmio_handler(struct pt_regs *regs, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/kmmio.c (0)
Location: arch/x86/mm/kmmio.c:230
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
**Symbols:**

```
ffffffff8108ae29-ffffffff8108ae77: kmmio_handler.cold (STB_LOCAL)
ffffffff8108ab70-ffffffff8108ad09: kmmio_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int kmmio_handler(struct pt_regs *regs, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/kmmio.c (0)
Location: arch/x86/mm/kmmio.c:230
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
**Symbols:**

```
ffffffff8108ba99-ffffffff8108bae7: kmmio_handler.cold (STB_LOCAL)
ffffffff8108b7e0-ffffffff8108b979: kmmio_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int kmmio_handler(struct pt_regs *regs, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/kmmio.c (0)
Location: arch/x86/mm/kmmio.c:230
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:exc_page_fault
```
**Symbols:**

```
ffffffff81092ef9-ffffffff81092f47: kmmio_handler.cold (STB_LOCAL)
ffffffff81092c20-ffffffff81092db8: kmmio_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int kmmio_handler(struct pt_regs *regs, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/kmmio.c (0)
Location: arch/x86/mm/kmmio.c:230
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:exc_page_fault
```
**Symbols:**

```
ffffffff81bd9f81-ffffffff81bd9fcf: kmmio_handler.cold (STB_LOCAL)
ffffffff810922b0-ffffffff8109244d: kmmio_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int kmmio_handler(struct pt_regs *regs, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/kmmio.c (0)
Location: arch/x86/mm/kmmio.c:230
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:exc_page_fault
```
**Symbols:**

```
ffffffff81bcbfdc-ffffffff81bcc02a: kmmio_handler.cold (STB_LOCAL)
ffffffff81092d80-ffffffff81092f1d: kmmio_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int kmmio_handler(struct pt_regs *regs, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/kmmio.c (0)
Location: arch/x86/mm/kmmio.c:230
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:exc_page_fault
```
**Symbols:**

```
ffffffff81ca1f13-ffffffff81ca1f80: kmmio_handler.cold (STB_LOCAL)
ffffffff810a2aa0-ffffffff810a2c46: kmmio_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int kmmio_handler(struct pt_regs *regs, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/kmmio.c (0)
Location: arch/x86/mm/kmmio.c:230
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:exc_page_fault
```
**Symbols:**

```
ffffffff81e5156e-ffffffff81e515db: kmmio_handler.cold (STB_LOCAL)
ffffffff810b70c0-ffffffff810b7290: kmmio_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int kmmio_handler(struct pt_regs *regs, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/kmmio.c (0)
Location: arch/x86/mm/kmmio.c:236
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:exc_page_fault
```
**Symbols:**

```
ffffffff8205525e-ffffffff8205527d: kmmio_handler.cold (STB_LOCAL)
ffffffff810d2590-ffffffff810d27ba: kmmio_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int kmmio_handler(struct pt_regs *regs, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/kmmio.c (0)
Location: arch/x86/mm/kmmio.c:236
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:exc_page_fault
```
**Symbols:**

```
ffffffff820d382d-ffffffff820d384c: kmmio_handler.cold (STB_LOCAL)
ffffffff810d5a00-ffffffff810d5c2a: kmmio_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int kmmio_handler(struct pt_regs *regs, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/kmmio.c (0)
Location: arch/x86/mm/kmmio.c:236
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:exc_page_fault
```
**Symbols:**

```
ffffffff821ae69b-ffffffff821ae6ba: kmmio_handler.cold (STB_LOCAL)
ffffffff810de230-ffffffff810de45a: kmmio_handler (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int kmmio_handler(struct pt_regs *regs, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/kmmio.c (0)
Location: arch/x86/mm/kmmio.c:230
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
**Symbols:**

```
ffffffff8108aa59-ffffffff8108aaa7: kmmio_handler.cold (STB_LOCAL)
ffffffff8108a7a0-ffffffff8108a939: kmmio_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int kmmio_handler(struct pt_regs *regs, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/kmmio.c (0)
Location: arch/x86/mm/kmmio.c:230
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
**Symbols:**

```
ffffffff810795c9-ffffffff81079617: kmmio_handler.cold (STB_LOCAL)
ffffffff81079310-ffffffff810794a9: kmmio_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int kmmio_handler(struct pt_regs *regs, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/kmmio.c (0)
Location: arch/x86/mm/kmmio.c:230
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
**Symbols:**

```
ffffffff8108aa09-ffffffff8108aa57: kmmio_handler.cold (STB_LOCAL)
ffffffff8108a750-ffffffff8108a8e9: kmmio_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int kmmio_handler(struct pt_regs *regs, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/kmmio.c (0)
Location: arch/x86/mm/kmmio.c:230
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
**Symbols:**

```
ffffffff8108cd09-ffffffff8108cd57: kmmio_handler.cold (STB_LOCAL)
ffffffff8108ca10-ffffffff8108cbee: kmmio_handler (STB_GLOBAL)
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
