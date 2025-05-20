# Function: <code>mtrr_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mtrr_add(long unsigned int base, long unsigned int size, unsigned int type, bool increment);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/main.c (ffffffff8104a820)
Location: arch/x86/kernel/cpu/mtrr/main.c:441
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
```
**Symbols:**

```
ffffffff8104a820-ffffffff8104a88b: mtrr_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mtrr_add(long unsigned int base, long unsigned int size, unsigned int type, bool increment);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/main.c (ffffffff8104a960)
Location: arch/x86/kernel/cpu/mtrr/main.c:441
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
```
**Symbols:**

```
ffffffff8104a960-ffffffff8104a9cb: mtrr_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mtrr_add(long unsigned int base, long unsigned int size, unsigned int type, bool increment);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/main.c (ffffffff8104cdc0)
Location: arch/x86/kernel/cpu/mtrr/main.c:441
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
```
**Symbols:**

```
ffffffff8104cdc0-ffffffff8104ce2b: mtrr_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mtrr_add(long unsigned int base, long unsigned int size, unsigned int type, bool increment);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/main.c (ffffffff8104cd80)
Location: arch/x86/kernel/cpu/mtrr/main.c:453
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
```
**Symbols:**

```
ffffffff8104cd80-ffffffff8104cdeb: mtrr_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mtrr_add(long unsigned int base, long unsigned int size, unsigned int type, bool increment);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/main.c (ffffffff81050670)
Location: arch/x86/kernel/cpu/mtrr/main.c:453
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
```
**Symbols:**

```
ffffffff81050670-ffffffff810506db: mtrr_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int mtrr_add(long unsigned int base, long unsigned int size, unsigned int type, bool increment);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:453
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
```
**Symbols:**

```
ffffffff810538e5-ffffffff81053908: mtrr_add.cold.7 (STB_LOCAL)
ffffffff810532f0-ffffffff81053345: mtrr_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int mtrr_add(long unsigned int base, long unsigned int size, unsigned int type, bool increment);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:453
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
```
**Symbols:**

```
ffffffff81050f65-ffffffff81050f88: mtrr_add.cold.8 (STB_LOCAL)
ffffffff81050970-ffffffff810509c5: mtrr_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int mtrr_add(long unsigned int base, long unsigned int size, unsigned int type, bool increment);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:453
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
```
**Symbols:**

```
ffffffff81054064-ffffffff81054097: mtrr_add.cold (STB_LOCAL)
ffffffff81053a40-ffffffff81053a7f: mtrr_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int mtrr_add(long unsigned int base, long unsigned int size, unsigned int type, bool increment);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:453
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
```
**Symbols:**

```
ffffffff81054954-ffffffff81054987: mtrr_add.cold (STB_LOCAL)
ffffffff81054330-ffffffff8105436f: mtrr_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int mtrr_add(long unsigned int base, long unsigned int size, unsigned int type, bool increment);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:453
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
```
**Symbols:**

```
ffffffff810599e6-ffffffff81059a26: mtrr_add.cold (STB_LOCAL)
ffffffff81059380-ffffffff81059400: mtrr_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int mtrr_add(long unsigned int base, long unsigned int size, unsigned int type, bool increment);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:453
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
```
**Symbols:**

```
ffffffff81bd5c9f-ffffffff81bd5cdf: mtrr_add.cold (STB_LOCAL)
ffffffff81058150-ffffffff810581d0: mtrr_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int mtrr_add(long unsigned int base, long unsigned int size, unsigned int type, bool increment);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:451
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
```
**Symbols:**

```
ffffffff81bc8053-ffffffff81bc8093: mtrr_add.cold (STB_LOCAL)
ffffffff81058aa0-ffffffff81058b20: mtrr_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int mtrr_add(long unsigned int base, long unsigned int size, unsigned int type, bool increment);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:451
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
```
**Symbols:**

```
ffffffff81c9bda8-ffffffff81c9bdf2: mtrr_add.cold (STB_LOCAL)
ffffffff81061bd0-ffffffff81061c39: mtrr_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mtrr_add(long unsigned int base, long unsigned int size, unsigned int type, bool increment);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:451
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
```
**Symbols:**

```
ffffffff81e4b1f1-ffffffff81e4b23b: mtrr_add.cold (STB_LOCAL)
ffffffff8106e590-ffffffff8106e605: mtrr_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mtrr_add(long unsigned int base, long unsigned int size, unsigned int type, bool increment);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (ffffffff8107e8c0)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:408
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
```
**Symbols:**

```
ffffffff8107e8c0-ffffffff8107e95c: mtrr_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int mtrr_add(long unsigned int base, long unsigned int size, unsigned int type, bool increment);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:377
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
```
**Symbols:**

```
ffffffff820d1496-ffffffff820d14ab: mtrr_add.cold (STB_LOCAL)
ffffffff81080a20-ffffffff81080ac7: mtrr_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int mtrr_add(long unsigned int base, long unsigned int size, unsigned int type, bool increment);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:377
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
```
**Symbols:**

```
ffffffff821ac05e-ffffffff821ac073: mtrr_add.cold (STB_LOCAL)
ffffffff81088530-ffffffff810885d7: mtrr_add (STB_GLOBAL)
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
int mtrr_add(long unsigned int base, long unsigned int size, unsigned int type, bool increment);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:453
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
```
**Symbols:**

```
ffffffff810544d4-ffffffff81054507: mtrr_add.cold (STB_LOCAL)
ffffffff81053eb0-ffffffff81053eef: mtrr_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int mtrr_add(long unsigned int base, long unsigned int size, unsigned int type, bool increment);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:453
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
```
**Symbols:**

```
ffffffff81044553-ffffffff81044586: mtrr_add.cold (STB_LOCAL)
ffffffff81043f80-ffffffff81043fbf: mtrr_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int mtrr_add(long unsigned int base, long unsigned int size, unsigned int type, bool increment);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:453
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
```
**Symbols:**

```
ffffffff81054904-ffffffff81054937: mtrr_add.cold (STB_LOCAL)
ffffffff810542e0-ffffffff8105431f: mtrr_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int mtrr_add(long unsigned int base, long unsigned int size, unsigned int type, bool increment);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mtrr/mtrr.c (0)
Location: arch/x86/kernel/cpu/mtrr/mtrr.c:453
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mtrr/if.c:mtrr_ioctl
```
**Symbols:**

```
ffffffff81055d84-ffffffff81055db7: mtrr_add.cold (STB_LOCAL)
ffffffff81055760-ffffffff8105579f: mtrr_add (STB_GLOBAL)
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
