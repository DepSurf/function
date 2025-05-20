# Function: <code>mtrr_del</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mtrr_del(int reg, long unsigned int base, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/main.c (ffffffff8104aae0)
Location: arch/x86/kernel/cpu/mtrr/main.c:531
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/main.c:arch_phys_wc_del
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_close
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
```
**Symbols:**

```
ffffffff8104aae0-ffffffff8104ab46: mtrr_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mtrr_del(int reg, long unsigned int base, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/main.c (ffffffff8104ac30)
Location: arch/x86/kernel/cpu/mtrr/main.c:531
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/main.c:arch_phys_wc_del
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_close
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
```
**Symbols:**

```
ffffffff8104ac30-ffffffff8104ac96: mtrr_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mtrr_del(int reg, long unsigned int base, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/main.c (ffffffff8104d090)
Location: arch/x86/kernel/cpu/mtrr/main.c:531
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/main.c:arch_phys_wc_del
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_close
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
```
**Symbols:**

```
ffffffff8104d090-ffffffff8104d0f6: mtrr_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mtrr_del(int reg, long unsigned int base, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/main.c (ffffffff8104d050)
Location: arch/x86/kernel/cpu/mtrr/main.c:543
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_close
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
```
**Symbols:**

```
ffffffff8104d050-ffffffff8104d0b6: mtrr_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mtrr_del(int reg, long unsigned int base, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/main.c (ffffffff81050950)
Location: arch/x86/kernel/cpu/mtrr/main.c:543
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_close
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
```
**Symbols:**

```
ffffffff81050950-ffffffff810509b6: mtrr_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int mtrr_del(int reg, long unsigned int base, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:543
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_close
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
```
**Symbols:**

```
ffffffff81053969-ffffffff8105398e: mtrr_del.cold.10 (STB_LOCAL)
ffffffff81053550-ffffffff810535a2: mtrr_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int mtrr_del(int reg, long unsigned int base, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:543
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_close
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
```
**Symbols:**

```
ffffffff81050fe9-ffffffff8105100e: mtrr_del.cold.11 (STB_LOCAL)
ffffffff81050bd0-ffffffff81050c22: mtrr_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int mtrr_del(int reg, long unsigned int base, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:543
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_close
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
```
**Symbols:**

```
ffffffff810540fe-ffffffff81054123: mtrr_del.cold (STB_LOCAL)
ffffffff81053ca0-ffffffff81053cf2: mtrr_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int mtrr_del(int reg, long unsigned int base, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:543
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_close
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
```
**Symbols:**

```
ffffffff810549ee-ffffffff81054a13: mtrr_del.cold (STB_LOCAL)
ffffffff81054590-ffffffff810545e2: mtrr_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mtrr_del(int reg, long unsigned int base, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81059637)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:543
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_close
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
```
**Symbols:**

```
ffffffff81059a8d-ffffffff81059ab2: mtrr_del.cold (STB_LOCAL)
ffffffff81059660-ffffffff810596b2: mtrr_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mtrr_del(int reg, long unsigned int base, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81058407)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:543
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_close
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
```
**Symbols:**

```
ffffffff81bd5d46-ffffffff81bd5d6b: mtrr_del.cold (STB_LOCAL)
ffffffff81058430-ffffffff81058482: mtrr_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mtrr_del(int reg, long unsigned int base, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81058d57)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:541
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_close
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
```
**Symbols:**

```
ffffffff81bc80fa-ffffffff81bc811f: mtrr_del.cold (STB_LOCAL)
ffffffff81058d80-ffffffff81058dd2: mtrr_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mtrr_del(int reg, long unsigned int base, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81061ed6)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:541
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_close
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
```
**Symbols:**

```
ffffffff81c9be96-ffffffff81c9bed8: mtrr_del.cold (STB_LOCAL)
ffffffff81061f00-ffffffff81061f66: mtrr_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mtrr_del(int reg, long unsigned int base, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff8106e8d6)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:541
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_close
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
```
**Symbols:**

```
ffffffff81e4b2cc-ffffffff81e4b30e: mtrr_del.cold (STB_LOCAL)
ffffffff8106e920-ffffffff8106e990: mtrr_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int mtrr_del(int reg, long unsigned int base, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff8107ec57)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:498
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_close
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
```
**Symbols:**

```
ffffffff8107eca0-ffffffff8107ed3f: mtrr_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mtrr_del(int reg, long unsigned int base, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81080dd7)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:466
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_close
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
```
**Symbols:**

```
ffffffff820d14bf-ffffffff820d14d4: mtrr_del.cold (STB_LOCAL)
ffffffff81080e20-ffffffff81080ec0: mtrr_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mtrr_del(int reg, long unsigned int base, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff810888e7)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:466
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_close
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
```
**Symbols:**

```
ffffffff821ac087-ffffffff821ac09c: mtrr_del.cold (STB_LOCAL)
ffffffff81088930-ffffffff810889d0: mtrr_del (STB_GLOBAL)
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
int mtrr_del(int reg, long unsigned int base, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:543
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_close
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
```
**Symbols:**

```
ffffffff8105456e-ffffffff81054593: mtrr_del.cold (STB_LOCAL)
ffffffff81054110-ffffffff81054162: mtrr_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int mtrr_del(int reg, long unsigned int base, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:543
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_close
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
```
**Symbols:**

```
ffffffff810445ed-ffffffff81044612: mtrr_del.cold (STB_LOCAL)
ffffffff810441e0-ffffffff81044232: mtrr_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int mtrr_del(int reg, long unsigned int base, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:543
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_close
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
```
**Symbols:**

```
ffffffff8105499e-ffffffff810549c3: mtrr_del.cold (STB_LOCAL)
ffffffff81054540-ffffffff81054592: mtrr_del (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int mtrr_del(int reg, long unsigned int base, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:543
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_close
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
```
**Symbols:**

```
ffffffff81055e1e-ffffffff81055e43: mtrr_del.cold (STB_LOCAL)
ffffffff810559c0-ffffffff81055a12: mtrr_del (STB_GLOBAL)
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
