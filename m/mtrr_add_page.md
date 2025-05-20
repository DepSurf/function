# Function: <code>mtrr_add_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int mtrr_add_page(long unsigned int base, long unsigned int size, unsigned int type, bool increment);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/main.c (ffffffff8104a3b0)
Location: arch/x86/kernel/cpu/mtrr/main.c:288
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_add
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
```
**Symbols:**

```
ffffffff8104a3b0-ffffffff8104a818: mtrr_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int mtrr_add_page(long unsigned int base, long unsigned int size, unsigned int type, bool increment);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/main.c (ffffffff8104a4f0)
Location: arch/x86/kernel/cpu/mtrr/main.c:288
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_add
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
```
**Symbols:**

```
ffffffff8104a4f0-ffffffff8104a95d: mtrr_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int mtrr_add_page(long unsigned int base, long unsigned int size, unsigned int type, bool increment);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/main.c (ffffffff8104c950)
Location: arch/x86/kernel/cpu/mtrr/main.c:288
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_add
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
```
**Symbols:**

```
ffffffff8104c950-ffffffff8104cdbd: mtrr_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int mtrr_add_page(long unsigned int base, long unsigned int size, unsigned int type, bool increment);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/main.c (ffffffff8104c900)
Location: arch/x86/kernel/cpu/mtrr/main.c:300
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_add
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
```
**Symbols:**

```
ffffffff8104c900-ffffffff8104cd80: mtrr_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int mtrr_add_page(long unsigned int base, long unsigned int size, unsigned int type, bool increment);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/main.c (ffffffff810501c0)
Location: arch/x86/kernel/cpu/mtrr/main.c:300
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_add
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
```
**Symbols:**

```
ffffffff810501c0-ffffffff81050663: mtrr_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mtrr_add_page(long unsigned int base, long unsigned int size, unsigned int type, bool increment);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:301
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
```
**Symbols:**

```
ffffffff8105385a-ffffffff810538e5: mtrr_add_page.cold.6 (STB_LOCAL)
ffffffff81052ee0-ffffffff810532ef: mtrr_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mtrr_add_page(long unsigned int base, long unsigned int size, unsigned int type, bool increment);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff810505c9)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:301
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
```
**Symbols:**

```
ffffffff81050eda-ffffffff81050f65: mtrr_add_page.cold.7 (STB_LOCAL)
ffffffff81050550-ffffffff81050961: mtrr_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mtrr_add_page(long unsigned int base, long unsigned int size, unsigned int type, bool increment);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff810536ba)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:301
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
```
**Symbols:**

```
ffffffff81053fac-ffffffff81054064: mtrr_add_page.cold (STB_LOCAL)
ffffffff81053660-ffffffff81053a3c: mtrr_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mtrr_add_page(long unsigned int base, long unsigned int size, unsigned int type, bool increment);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81053faa)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:301
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
```
**Symbols:**

```
ffffffff8105489c-ffffffff81054954: mtrr_add_page.cold (STB_LOCAL)
ffffffff81053f50-ffffffff8105432c: mtrr_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mtrr_add_page(long unsigned int base, long unsigned int size, unsigned int type, bool increment);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff810593ce)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:301
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
```
**Symbols:**

```
ffffffff81058f60-ffffffff8105931f: mtrr_add_page.part.0 (STB_LOCAL)
ffffffff8105992c-ffffffff810599e6: mtrr_add_page.part.0.cold (STB_LOCAL)
ffffffff81059320-ffffffff81059378: mtrr_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mtrr_add_page(long unsigned int base, long unsigned int size, unsigned int type, bool increment);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff8105819e)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:301
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
```
**Symbols:**

```
ffffffff81057d30-ffffffff810580ef: mtrr_add_page.part.0 (STB_LOCAL)
ffffffff81bd5be5-ffffffff81bd5c9f: mtrr_add_page.part.0.cold (STB_LOCAL)
ffffffff810580f0-ffffffff81058148: mtrr_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mtrr_add_page(long unsigned int base, long unsigned int size, unsigned int type, bool increment);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81058aee)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:299
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
```
**Symbols:**

```
ffffffff81058680-ffffffff81058a3f: mtrr_add_page.part.0 (STB_LOCAL)
ffffffff81bc7f99-ffffffff81bc8053: mtrr_add_page.part.0.cold (STB_LOCAL)
ffffffff81058a40-ffffffff81058a98: mtrr_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mtrr_add_page(long unsigned int base, long unsigned int size, unsigned int type, bool increment);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:299
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
```
**Symbols:**

```
ffffffff810616b0-ffffffff81061b4e: mtrr_add_page.part.0 (STB_LOCAL)
ffffffff81c9bcbf-ffffffff81c9bd93: mtrr_add_page.part.0.cold (STB_LOCAL)
ffffffff81c9bd93-ffffffff81c9bda8: mtrr_add_page.cold (STB_LOCAL)
ffffffff81061b50-ffffffff81061bc5: mtrr_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mtrr_add_page(long unsigned int base, long unsigned int size, unsigned int type, bool increment);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:299
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
```
**Symbols:**

```
ffffffff81e4b11c-ffffffff81e4b1f1: mtrr_add_page.cold (STB_LOCAL)
ffffffff8106e050-ffffffff8106e586: mtrr_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int mtrr_add_page(long unsigned int base, long unsigned int size, unsigned int type, bool increment);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:256
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
```
**Symbols:**

```
ffffffff82052f27-ffffffff82052f44: mtrr_add_page.cold (STB_LOCAL)
ffffffff8107e350-ffffffff8107e8aa: mtrr_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int mtrr_add_page(long unsigned int base, long unsigned int size, unsigned int type, bool increment);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:225
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
```
**Symbols:**

```
ffffffff820d1482-ffffffff820d1496: mtrr_add_page.cold (STB_LOCAL)
ffffffff810804b0-ffffffff81080a0c: mtrr_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int mtrr_add_page(long unsigned int base, long unsigned int size, unsigned int type, bool increment);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:225
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
```
**Symbols:**

```
ffffffff821ac04a-ffffffff821ac05e: mtrr_add_page.cold (STB_LOCAL)
ffffffff81087fc0-ffffffff8108851c: mtrr_add_page (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mtrr_add_page(long unsigned int base, long unsigned int size, unsigned int type, bool increment);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81053b2a)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:301
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
```
**Symbols:**

```
ffffffff8105441c-ffffffff810544d4: mtrr_add_page.cold (STB_LOCAL)
ffffffff81053ad0-ffffffff81053eac: mtrr_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mtrr_add_page(long unsigned int base, long unsigned int size, unsigned int type, bool increment);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81043bfa)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:301
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
```
**Symbols:**

```
ffffffff8104449b-ffffffff81044553: mtrr_add_page.cold (STB_LOCAL)
ffffffff81043ba0-ffffffff81043f7c: mtrr_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mtrr_add_page(long unsigned int base, long unsigned int size, unsigned int type, bool increment);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff81053f5a)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:301
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
```
**Symbols:**

```
ffffffff8105484c-ffffffff81054904: mtrr_add_page.cold (STB_LOCAL)
ffffffff81053f00-ffffffff810542dc: mtrr_add_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mtrr_add_page(long unsigned int base, long unsigned int size, unsigned int type, bool increment);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff810553da)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:301
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_add
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
```
**Symbols:**

```
ffffffff81055ccc-ffffffff81055d84: mtrr_add_page.cold (STB_LOCAL)
ffffffff81055380-ffffffff8105575c: mtrr_add_page (STB_GLOBAL)
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
