# Function: <code>force_sig_pkuerr</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int force_sig_pkuerr(void *addr, u32 pkey);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a0110)
Location: kernel/signal.c:1576
Inline: False
```
**Symbols:**

```
ffffffff810a0110-ffffffff810a0199: force_sig_pkuerr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int force_sig_pkuerr(void *addr, u32 pkey);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a8450)
Location: kernel/signal.c:1662
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff810a8450-ffffffff810a84cd: force_sig_pkuerr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int force_sig_pkuerr(void *addr, u32 pkey);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ae630)
Location: kernel/signal.c:1750
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff810ae630-ffffffff810ae6aa: force_sig_pkuerr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int force_sig_pkuerr(void *addr, u32 pkey);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b4c40)
Location: kernel/signal.c:1755
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff810b4c40-ffffffff810b4cba: force_sig_pkuerr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int force_sig_pkuerr(void *addr, u32 pkey);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810bd900)
Location: kernel/signal.c:1751
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff810bd900-ffffffff810bd96a: force_sig_pkuerr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int force_sig_pkuerr(void *addr, u32 pkey);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b8c10)
Location: kernel/signal.c:1752
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff810b8c10-ffffffff810b8c7a: force_sig_pkuerr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int force_sig_pkuerr(void *addr, u32 pkey);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ba190)
Location: kernel/signal.c:1754
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff810ba190-ffffffff810ba1fa: force_sig_pkuerr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int force_sig_pkuerr(void *addr, u32 pkey);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810cc790)
Location: kernel/signal.c:1791
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:kernelmode_fixup_or_oops
```
**Symbols:**

```
ffffffff810cc790-ffffffff810cc7fc: force_sig_pkuerr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int force_sig_pkuerr(void *addr, u32 pkey);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810e3a80)
Location: kernel/signal.c:1792
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:kernelmode_fixup_or_oops
```
**Symbols:**

```
ffffffff810e3a80-ffffffff810e3b06: force_sig_pkuerr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int force_sig_pkuerr(void *addr, u32 pkey);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81104060)
Location: kernel/signal.c:1793
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:kernelmode_fixup_or_oops
```
**Symbols:**

```
ffffffff81104060-ffffffff811040e6: force_sig_pkuerr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int force_sig_pkuerr(void *addr, u32 pkey);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff811102e0)
Location: kernel/signal.c:1799
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:kernelmode_fixup_or_oops
```
**Symbols:**

```
ffffffff811102e0-ffffffff81110366: force_sig_pkuerr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int force_sig_pkuerr(void *addr, u32 pkey);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81119c30)
Location: kernel/signal.c:1790
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:kernelmode_fixup_or_oops
```
**Symbols:**

```
ffffffff81119c30-ffffffff81119cb6: force_sig_pkuerr (STB_GLOBAL)
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
int force_sig_pkuerr(void *addr, u32 pkey);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff800010110db0)
Location: kernel/signal.c:1755
Inline: False
```
**Symbols:**

```
ffff800010110db0-ffff800010110e38: force_sig_pkuerr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int force_sig_pkuerr(void *addr, u32 pkey);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0368588)
Location: kernel/signal.c:1755
Inline: False
```
**Symbols:**

```
c0368588-c0368624: force_sig_pkuerr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int force_sig_pkuerr(void *addr, u32 pkey);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000158660)
Location: kernel/signal.c:1755
Inline: False
Direct callers:
  - arch/powerpc/kernel/traps.c:_exception_pkey
  - arch/powerpc/kernel/traps.c:_exception_pkey
```
**Symbols:**

```
c000000000158660-c0000000001586f4: force_sig_pkuerr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int force_sig_pkuerr(void *addr, u32 pkey);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000d0890)
Location: kernel/signal.c:1755
Inline: False
```
**Symbols:**

```
ffffffe0000d0890-ffffffe0000d08e8: force_sig_pkuerr (STB_GLOBAL)
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
int force_sig_pkuerr(void *addr, u32 pkey);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aefb0)
Location: kernel/signal.c:1755
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff810aefb0-ffffffff810af02a: force_sig_pkuerr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int force_sig_pkuerr(void *addr, u32 pkey);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109d900)
Location: kernel/signal.c:1755
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff8109d900-ffffffff8109d97a: force_sig_pkuerr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int force_sig_pkuerr(void *addr, u32 pkey);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ae510)
Location: kernel/signal.c:1755
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff810ae510-ffffffff810ae58a: force_sig_pkuerr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int force_sig_pkuerr(void *addr, u32 pkey);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b6780)
Location: kernel/signal.c:1755
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
**Symbols:**

```
ffffffff810b6780-ffffffff810b67fa: force_sig_pkuerr (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
