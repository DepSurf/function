# Function: <code>mtrr_del_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mtrr_del_page(int reg, long unsigned int base, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/main.c (ffffffff8104a910)
Location: arch/x86/kernel/cpu/mtrr/main.c:466
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_del
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
```
**Symbols:**

```
ffffffff8104a910-ffffffff8104aad8: mtrr_del_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mtrr_del_page(int reg, long unsigned int base, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/main.c (ffffffff8104aa50)
Location: arch/x86/kernel/cpu/mtrr/main.c:466
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_del
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
```
**Symbols:**

```
ffffffff8104aa50-ffffffff8104ac23: mtrr_del_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mtrr_del_page(int reg, long unsigned int base, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/main.c (ffffffff8104ceb0)
Location: arch/x86/kernel/cpu/mtrr/main.c:466
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_del
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
```
**Symbols:**

```
ffffffff8104ceb0-ffffffff8104d083: mtrr_del_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mtrr_del_page(int reg, long unsigned int base, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/main.c (ffffffff8104ce70)
Location: arch/x86/kernel/cpu/mtrr/main.c:478
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_del
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
```
**Symbols:**

```
ffffffff8104ce70-ffffffff8104d048: mtrr_del_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mtrr_del_page(int reg, long unsigned int base, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/main.c (ffffffff81050760)
Location: arch/x86/kernel/cpu/mtrr/main.c:478
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/main.c:mtrr_del
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
```
**Symbols:**

```
ffffffff81050760-ffffffff81050944: mtrr_del_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int mtrr_del_page(int reg, long unsigned int base, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:478
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
```
**Symbols:**

```
ffffffff81053921-ffffffff81053969: mtrr_del_page.cold.9 (STB_LOCAL)
ffffffff810533b0-ffffffff8105354a: mtrr_del_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int mtrr_del_page(int reg, long unsigned int base, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:478
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
```
**Symbols:**

```
ffffffff81050fa1-ffffffff81050fe9: mtrr_del_page.cold.10 (STB_LOCAL)
ffffffff81050a30-ffffffff81050bca: mtrr_del_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int mtrr_del_page(int reg, long unsigned int base, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:478
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
```
**Symbols:**

```
ffffffff810540b0-ffffffff810540fe: mtrr_del_page.cold (STB_LOCAL)
ffffffff81053af0-ffffffff81053c93: mtrr_del_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int mtrr_del_page(int reg, long unsigned int base, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:478
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
```
**Symbols:**

```
ffffffff810549a0-ffffffff810549ee: mtrr_del_page.cold (STB_LOCAL)
ffffffff810543e0-ffffffff81054583: mtrr_del_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int mtrr_del_page(int reg, long unsigned int base, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:478
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
```
**Symbols:**

```
ffffffff81059a3f-ffffffff81059a8d: mtrr_del_page.cold (STB_LOCAL)
ffffffff81059470-ffffffff81059613: mtrr_del_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int mtrr_del_page(int reg, long unsigned int base, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:478
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
```
**Symbols:**

```
ffffffff81bd5cf8-ffffffff81bd5d46: mtrr_del_page.cold (STB_LOCAL)
ffffffff81058240-ffffffff810583e3: mtrr_del_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int mtrr_del_page(int reg, long unsigned int base, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:476
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
```
**Symbols:**

```
ffffffff81bc80ac-ffffffff81bc80fa: mtrr_del_page.cold (STB_LOCAL)
ffffffff81058b90-ffffffff81058d33: mtrr_del_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int mtrr_del_page(int reg, long unsigned int base, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:476
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
```
**Symbols:**

```
ffffffff81c9be20-ffffffff81c9be82: mtrr_del_page.cold (STB_LOCAL)
ffffffff81061cc0-ffffffff81061eb0: mtrr_del_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mtrr_del_page(int reg, long unsigned int base, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:476
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
```
**Symbols:**

```
ffffffff81e4b269-ffffffff81e4b2b7: mtrr_del_page.cold (STB_LOCAL)
ffffffff8106e6a0-ffffffff8106e8a7: mtrr_del_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mtrr_del_page(int reg, long unsigned int base, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff8107ea00)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:433
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
```
**Symbols:**

```
ffffffff8107ea00-ffffffff8107ec29: mtrr_del_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int mtrr_del_page(int reg, long unsigned int base, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:402
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
```
**Symbols:**

```
ffffffff820d14ab-ffffffff820d14bf: mtrr_del_page.cold (STB_LOCAL)
ffffffff81080b70-ffffffff81080dad: mtrr_del_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int mtrr_del_page(int reg, long unsigned int base, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:402
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
```
**Symbols:**

```
ffffffff821ac073-ffffffff821ac087: mtrr_del_page.cold (STB_LOCAL)
ffffffff81088680-ffffffff810888bd: mtrr_del_page (STB_GLOBAL)
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
int mtrr_del_page(int reg, long unsigned int base, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:478
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
```
**Symbols:**

```
ffffffff81054520-ffffffff8105456e: mtrr_del_page.cold (STB_LOCAL)
ffffffff81053f60-ffffffff81054103: mtrr_del_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int mtrr_del_page(int reg, long unsigned int base, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:478
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
```
**Symbols:**

```
ffffffff8104459f-ffffffff810445ed: mtrr_del_page.cold (STB_LOCAL)
ffffffff81044030-ffffffff810441d3: mtrr_del_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int mtrr_del_page(int reg, long unsigned int base, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:478
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
```
**Symbols:**

```
ffffffff81054950-ffffffff8105499e: mtrr_del_page.cold (STB_LOCAL)
ffffffff81054390-ffffffff81054533: mtrr_del_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int mtrr_del_page(int reg, long unsigned int base, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:478
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/mtrr.c:mtrr_del
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_write
```
**Symbols:**

```
ffffffff81055dd0-ffffffff81055e1e: mtrr_del_page.cold (STB_LOCAL)
ffffffff81055810-ffffffff810559b3: mtrr_del_page (STB_GLOBAL)
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
