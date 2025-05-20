# Function: <code>do_sysinfo</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int do_sysinfo(struct sysinfo *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff81092bb0)
Location: kernel/sys.c:2308
Inline: False
Direct callers:
  - kernel/sys.c:SYSC_sysinfo
  - kernel/sys.c:C_SYSC_sysinfo
```
**Symbols:**

```
ffffffff81092bb0-ffffffff81092c8d: do_sysinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int do_sysinfo(struct sysinfo *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff81095d40)
Location: kernel/sys.c:2312
Inline: False
Direct callers:
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:SYSC_sysinfo
```
**Symbols:**

```
ffffffff81095d40-ffffffff81095e23: do_sysinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int do_sysinfo(struct sysinfo *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff8109ad10)
Location: kernel/sys.c:2303
Inline: False
Direct callers:
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:SYSC_sysinfo
```
**Symbols:**

```
ffffffff8109ad10-ffffffff8109adf3: do_sysinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int do_sysinfo(struct sysinfo *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff81097b10)
Location: kernel/sys.c:2431
Inline: False
Direct callers:
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:SYSC_sysinfo
```
**Symbols:**

```
ffffffff81097b10-ffffffff81097bfe: do_sysinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_sysinfo(struct sysinfo *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff8109e800)
Location: kernel/sys.c:2440
Inline: False
Direct callers:
  - kernel/sys.c:C_SYSC_sysinfo
  - kernel/sys.c:SYSC_sysinfo
```
**Symbols:**

```
ffffffff8109e800-ffffffff8109e8ee: do_sysinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int do_sysinfo(struct sysinfo *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810a4070)
Location: kernel/sys.c:2521
Inline: False
Direct callers:
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_sys_sysinfo
```
**Symbols:**

```
ffffffff810a4070-ffffffff810a4153: do_sysinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int do_sysinfo(struct sysinfo *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810ace40)
Location: kernel/sys.c:2527
Inline: False
Direct callers:
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_sys_sysinfo
```
**Symbols:**

```
ffffffff810ace40-ffffffff810acf23: do_sysinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int do_sysinfo(struct sysinfo *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b2670)
Location: kernel/sys.c:2534
Inline: False
Direct callers:
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_sys_sysinfo
```
**Symbols:**

```
ffffffff810b2670-ffffffff810b2762: do_sysinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int do_sysinfo(struct sysinfo *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b8d40)
Location: kernel/sys.c:2528
Inline: False
Direct callers:
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_sys_sysinfo
```
**Symbols:**

```
ffffffff810b8d40-ffffffff810b8e32: do_sysinfo (STB_LOCAL)
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
In kernel/sys.c (ffffffff810c0ec0)
Location: kernel/sys.c:2569
Inline: True
Direct callers:
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_sys_sysinfo
```
**Symbols:**

```
ffffffff810c0ec0-ffffffff810c0ff3: do_sysinfo.isra.0 (STB_LOCAL)
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
In kernel/sys.c (ffffffff810bc020)
Location: kernel/sys.c:2577
Inline: True
Direct callers:
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_sys_sysinfo
```
**Symbols:**

```
ffffffff810bc020-ffffffff810bc153: do_sysinfo.isra.0 (STB_LOCAL)
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
In kernel/sys.c (ffffffff810bd8a0)
Location: kernel/sys.c:2604
Inline: True
Direct callers:
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_sys_sysinfo
```
**Symbols:**

```
ffffffff810bd8a0-ffffffff810bd9d3: do_sysinfo.isra.0 (STB_LOCAL)
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
In kernel/sys.c (0)
Location: kernel/sys.c:2580
Inline: True
Direct callers:
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_sys_sysinfo
```
**Symbols:**

```
ffffffff810d0370-ffffffff810d04c5: do_sysinfo.isra.0 (STB_LOCAL)
ffffffff81ca49b0-ffffffff81ca4ac0: do_sysinfo.isra.0.cold (STB_LOCAL)
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
In kernel/sys.c (0)
Location: kernel/sys.c:2665
Inline: True
Direct callers:
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_sys_sysinfo
```
**Symbols:**

```
ffffffff810e92b0-ffffffff810e9415: do_sysinfo.isra.0 (STB_LOCAL)
ffffffff81e54284-ffffffff81e54386: do_sysinfo.isra.0.cold (STB_LOCAL)
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
In kernel/sys.c (0)
Location: kernel/sys.c:2670
Inline: True
Direct callers:
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_sys_sysinfo
```
**Symbols:**

```
ffffffff8110a180-ffffffff8110a2e5: do_sysinfo.isra.0 (STB_LOCAL)
ffffffff820562c3-ffffffff820563c5: do_sysinfo.isra.0.cold (STB_LOCAL)
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
In kernel/sys.c (0)
Location: kernel/sys.c:2762
Inline: True
Direct callers:
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_sys_sysinfo
```
**Symbols:**

```
ffffffff81116450-ffffffff811165b5: do_sysinfo.isra.0 (STB_LOCAL)
ffffffff820d4821-ffffffff820d48f4: do_sysinfo.isra.0.cold (STB_LOCAL)
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
In kernel/sys.c (0)
Location: kernel/sys.c:2799
Inline: True
Direct callers:
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_sys_sysinfo
```
**Symbols:**

```
ffffffff8111fe40-ffffffff8111ffa5: do_sysinfo.isra.0 (STB_LOCAL)
ffffffff821af70a-ffffffff821af7dd: do_sysinfo.isra.0.cold (STB_LOCAL)
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
int do_sysinfo(struct sysinfo *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffff8000101144a0)
Location: kernel/sys.c:2528
Inline: False
Direct callers:
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_sys_sysinfo
```
**Symbols:**

```
ffff8000101144a0-ffff8000101145c8: do_sysinfo (STB_LOCAL)
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
In kernel/sys.c (c036ea5c)
Location: kernel/sys.c:2528
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_sysinfo
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_sysinfo(struct sysinfo *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (c00000000015d130)
Location: kernel/sys.c:2528
Inline: False
Direct callers:
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_sys_sysinfo
```
**Symbols:**

```
c00000000015d130-c00000000015d28c: do_sysinfo (STB_LOCAL)
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
In kernel/sys.c (ffffffe0000d2170)
Location: kernel/sys.c:2528
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_sysinfo
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
int do_sysinfo(struct sysinfo *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b30b0)
Location: kernel/sys.c:2528
Inline: False
Direct callers:
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_sys_sysinfo
```
**Symbols:**

```
ffffffff810b30b0-ffffffff810b31a2: do_sysinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int do_sysinfo(struct sysinfo *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810a19e0)
Location: kernel/sys.c:2528
Inline: False
Direct callers:
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_sys_sysinfo
```
**Symbols:**

```
ffffffff810a19e0-ffffffff810a1ad2: do_sysinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int do_sysinfo(struct sysinfo *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b2610)
Location: kernel/sys.c:2528
Inline: False
Direct callers:
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_sys_sysinfo
```
**Symbols:**

```
ffffffff810b2610-ffffffff810b2702: do_sysinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int do_sysinfo(struct sysinfo *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810bac10)
Location: kernel/sys.c:2528
Inline: False
Direct callers:
  - kernel/sys.c:__do_compat_sys_sysinfo
  - kernel/sys.c:__do_sys_sysinfo
```
**Symbols:**

```
ffffffff810bac10-ffffffff810bad02: do_sysinfo (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
