# Function: <code>jiffies_to_timeval</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void jiffies_to_timeval(const long unsigned int jiffies, struct timeval *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810eae40)
Location: kernel/time/time.c:612
Inline: False
Direct callers:
  - kernel/sys.c:k_getrusage
  - kernel/sys.c:k_getrusage
  - kernel/sys.c:k_getrusage
  - kernel/sys.c:k_getrusage
  - kernel/sys.c:k_getrusage
  - kernel/sys.c:k_getrusage
  - kernel/time/itimer.c:get_cpu_itimer
  - kernel/time/itimer.c:get_cpu_itimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/tsacct.c:__acct_update_integrals
  - fs/compat_binfmt_elf.c:fill_prstatus
  - fs/compat_binfmt_elf.c:fill_prstatus
  - fs/compat_binfmt_elf.c:fill_prstatus
  - fs/compat_binfmt_elf.c:fill_prstatus
  - fs/compat_binfmt_elf.c:fill_prstatus
  - fs/compat_binfmt_elf.c:fill_prstatus
```
**Symbols:**

```
ffffffff810eae40-ffffffff810eae8e: jiffies_to_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void jiffies_to_timeval(const long unsigned int jiffies, struct timeval *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810f1ae0)
Location: kernel/time/time.c:619
Inline: False
Direct callers:
  - kernel/sys.c:k_getrusage
  - kernel/sys.c:k_getrusage
  - kernel/sys.c:k_getrusage
  - kernel/sys.c:k_getrusage
  - kernel/sys.c:k_getrusage
  - kernel/sys.c:k_getrusage
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:get_cpu_itimer
  - kernel/time/itimer.c:get_cpu_itimer
  - fs/compat_binfmt_elf.c:fill_prstatus
  - fs/compat_binfmt_elf.c:fill_prstatus
  - fs/compat_binfmt_elf.c:fill_prstatus
  - fs/compat_binfmt_elf.c:fill_prstatus
  - fs/compat_binfmt_elf.c:fill_prstatus
  - fs/compat_binfmt_elf.c:fill_prstatus
```
**Symbols:**

```
ffffffff810f1ae0-ffffffff810f1b2c: jiffies_to_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void jiffies_to_timeval(const long unsigned int jiffies, struct timeval *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810f8c60)
Location: kernel/time/time.c:619
Inline: False
Direct callers:
  - kernel/sys.c:k_getrusage
  - kernel/sys.c:k_getrusage
  - kernel/sys.c:k_getrusage
  - kernel/sys.c:k_getrusage
  - kernel/sys.c:k_getrusage
  - kernel/sys.c:k_getrusage
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:set_cpu_itimer
  - kernel/time/itimer.c:get_cpu_itimer
  - kernel/time/itimer.c:get_cpu_itimer
  - fs/compat_binfmt_elf.c:fill_prstatus
  - fs/compat_binfmt_elf.c:fill_prstatus
  - fs/compat_binfmt_elf.c:fill_prstatus
  - fs/compat_binfmt_elf.c:fill_prstatus
  - fs/compat_binfmt_elf.c:fill_prstatus
  - fs/compat_binfmt_elf.c:fill_prstatus
```
**Symbols:**

```
ffffffff810f8c60-ffffffff810f8cac: jiffies_to_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void jiffies_to_timeval(const long unsigned int jiffies, struct timeval *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810fac80)
Location: kernel/time/time.c:709
Inline: False
```
**Symbols:**

```
ffffffff810fac80-ffffffff810faccc: jiffies_to_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void jiffies_to_timeval(const long unsigned int jiffies, struct timeval *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81105610)
Location: kernel/time/time.c:676
Inline: False
```
**Symbols:**

```
ffffffff81105610-ffffffff8110565c: jiffies_to_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void jiffies_to_timeval(const long unsigned int jiffies, struct timeval *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81110470)
Location: kernel/time/time.c:688
Inline: False
```
**Symbols:**

```
ffffffff81110470-ffffffff811104bc: jiffies_to_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void jiffies_to_timeval(const long unsigned int jiffies, struct timeval *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8111ba60)
Location: kernel/time/time.c:626
Inline: False
```
**Symbols:**

```
ffffffff8111ba60-ffffffff8111baac: jiffies_to_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void jiffies_to_timeval(const long unsigned int jiffies, struct timeval *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81126480)
Location: kernel/time/time.c:694
Inline: False
```
**Symbols:**

```
ffffffff81126480-ffffffff811264cd: jiffies_to_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void jiffies_to_timeval(const long unsigned int jiffies, struct timeval *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81132420)
Location: kernel/time/time.c:694
Inline: False
```
**Symbols:**

```
ffffffff81132420-ffffffff8113246d: jiffies_to_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
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
void jiffies_to_timeval(const long unsigned int jiffies, struct timeval *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffff800010199ee8)
Location: kernel/time/time.c:694
Inline: False
```
**Symbols:**

```
ffff800010199ee8-ffff800010199f5c: jiffies_to_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void jiffies_to_timeval(const long unsigned int jiffies, struct timeval *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (c03e5430)
Location: kernel/time/time.c:694
Inline: False
```
**Symbols:**

```
c03e5430-c03e54c0: jiffies_to_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void jiffies_to_timeval(const long unsigned int jiffies, struct timeval *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (c0000000001fa180)
Location: kernel/time/time.c:694
Inline: False
```
**Symbols:**

```
c0000000001fa180-c0000000001fa1e0: jiffies_to_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void jiffies_to_timeval(const long unsigned int jiffies, struct timeval *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffe00012a3a6)
Location: kernel/time/time.c:694
Inline: False
```
**Symbols:**

```
ffffffe00012a3a6-ffffffe00012a3fc: jiffies_to_timeval (STB_GLOBAL)
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
void jiffies_to_timeval(const long unsigned int jiffies, struct timeval *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8112abd0)
Location: kernel/time/time.c:694
Inline: False
```
**Symbols:**

```
ffffffff8112abd0-ffffffff8112ac1d: jiffies_to_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void jiffies_to_timeval(const long unsigned int jiffies, struct timeval *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff8111d440)
Location: kernel/time/time.c:694
Inline: False
```
**Symbols:**

```
ffffffff8111d440-ffffffff8111d48d: jiffies_to_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void jiffies_to_timeval(const long unsigned int jiffies, struct timeval *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811288f0)
Location: kernel/time/time.c:694
Inline: False
```
**Symbols:**

```
ffffffff811288f0-ffffffff8112893d: jiffies_to_timeval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void jiffies_to_timeval(const long unsigned int jiffies, struct timeval *value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81134f70)
Location: kernel/time/time.c:694
Inline: False
```
**Symbols:**

```
ffffffff81134f70-ffffffff81134fbd: jiffies_to_timeval (STB_GLOBAL)
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
