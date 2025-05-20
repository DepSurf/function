# Function: <code>oops_exit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void oops_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff810810b0)
Location: kernel/panic.c:422
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
```
**Symbols:**

```
ffffffff810810b0-ffffffff810810d9: oops_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void oops_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff81082d60)
Location: kernel/panic.c:471
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
```
**Symbols:**

```
ffffffff81082d60-ffffffff81082d89: oops_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void oops_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff810877f0)
Location: kernel/panic.c:501
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
```
**Symbols:**

```
ffffffff810877f0-ffffffff81087819: oops_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void oops_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff81084680)
Location: kernel/panic.c:503
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
```
**Symbols:**

```
ffffffff81084680-ffffffff810846a9: oops_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void oops_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff8108b060)
Location: kernel/panic.c:508
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
```
**Symbols:**

```
ffffffff8108b060-ffffffff8108b089: oops_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void oops_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff8108e820)
Location: kernel/panic.c:497
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
```
**Symbols:**

```
ffffffff8108e820-ffffffff8108e849: oops_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void oops_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff81096ab0)
Location: kernel/panic.c:532
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
```
**Symbols:**

```
ffffffff81096ab0-ffffffff81096ad9: oops_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void oops_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff8109b030)
Location: kernel/panic.c:537
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
```
**Symbols:**

```
ffffffff8109b030-ffffffff8109b059: oops_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void oops_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff810a1550)
Location: kernel/panic.c:546
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
```
**Symbols:**

```
ffffffff810a1550-ffffffff810a1579: oops_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void oops_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/panic.c (0)
Location: kernel/panic.c:564
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
```
**Symbols:**

```
ffffffff810a88e5-ffffffff810a88f5: oops_exit.cold (STB_LOCAL)
ffffffff810a83d0-ffffffff810a8428: oops_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void oops_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/panic.c (0)
Location: kernel/panic.c:564
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
```
**Symbols:**

```
ffffffff81bdb48d-ffffffff81bdb49d: oops_exit.cold (STB_LOCAL)
ffffffff810a40e0-ffffffff810a4138: oops_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void oops_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/panic.c (0)
Location: kernel/panic.c:564
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
```
**Symbols:**

```
ffffffff81bcd57f-ffffffff81bcd58f: oops_exit.cold (STB_LOCAL)
ffffffff810a4d30-ffffffff810a4d88: oops_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void oops_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/panic.c (0)
Location: kernel/panic.c:562
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
```
**Symbols:**

```
ffffffff81ca3d46-ffffffff81ca3d56: oops_exit.cold (STB_LOCAL)
ffffffff810b6570-ffffffff810b65c8: oops_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void oops_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/panic.c (0)
Location: kernel/panic.c:589
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
```
**Symbols:**

```
ffffffff81e534f4-ffffffff81e53518: oops_exit.cold (STB_LOCAL)
ffffffff810ccb20-ffffffff810ccb41: oops_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void oops_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff810ea9f0)
Location: kernel/panic.c:640
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
```
**Symbols:**

```
ffffffff810ea9f0-ffffffff810eaa2c: oops_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void oops_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff810f65d0)
Location: kernel/panic.c:640
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
```
**Symbols:**

```
ffffffff810f65d0-ffffffff810f660c: oops_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void oops_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff810ff980)
Location: kernel/panic.c:644
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
```
**Symbols:**

```
ffffffff810ff980-ffffffff810ff9bc: oops_exit (STB_GLOBAL)
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
void oops_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffff8000100f66e8)
Location: kernel/panic.c:546
Inline: False
Direct callers:
  - arch/arm64/kernel/traps.c:die
```
**Symbols:**

```
ffff8000100f66e8-ffff8000100f671c: oops_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void oops_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (c035483c)
Location: kernel/panic.c:546
Inline: False
Direct callers:
  - arch/arm/kernel/traps.c:die
```
**Symbols:**

```
c035483c-c0354878: oops_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void oops_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (c00000000013c590)
Location: kernel/panic.c:546
Inline: False
```
**Symbols:**

```
c00000000013c590-c00000000013c5e0: oops_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void oops_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffe0000c23d6)
Location: kernel/panic.c:546
Inline: False
Direct callers:
  - arch/riscv/kernel/traps.c:die
```
**Symbols:**

```
ffffffe0000c23d6-ffffffe0000c2414: oops_exit (STB_GLOBAL)
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
void oops_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff8109ae70)
Location: kernel/panic.c:546
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
```
**Symbols:**

```
ffffffff8109ae70-ffffffff8109ae99: oops_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void oops_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff810898b0)
Location: kernel/panic.c:546
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
```
**Symbols:**

```
ffffffff810898b0-ffffffff810898d9: oops_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void oops_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff8109ae20)
Location: kernel/panic.c:546
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
```
**Symbols:**

```
ffffffff8109ae20-ffffffff8109ae49: oops_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void oops_exit();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff810a2a90)
Location: kernel/panic.c:546
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:oops_end
```
**Symbols:**

```
ffffffff810a2a90-ffffffff810a2ab9: oops_exit (STB_GLOBAL)
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
