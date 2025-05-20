# Function: <code>__do_compat_sys_sysinfo</code>

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
long int __do_compat_sys_sysinfo(struct compat_sysinfo *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810a4200)
Location: kernel/sys.c:2613
Inline: False
Direct callers:
  - kernel/sys.c:__x32_compat_sys_sysinfo
  - kernel/sys.c:__ia32_compat_sys_sysinfo
```
**Symbols:**

```
ffffffff810a4200-ffffffff810a43c3: __do_compat_sys_sysinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int __do_compat_sys_sysinfo(struct compat_sysinfo *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810acfd0)
Location: kernel/sys.c:2619
Inline: False
Direct callers:
  - kernel/sys.c:__x32_compat_sys_sysinfo
  - kernel/sys.c:__ia32_compat_sys_sysinfo
```
**Symbols:**

```
ffffffff810acfd0-ffffffff810ad223: __do_compat_sys_sysinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int __do_compat_sys_sysinfo(struct compat_sysinfo *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b2810)
Location: kernel/sys.c:2626
Inline: False
Direct callers:
  - kernel/sys.c:__x32_compat_sys_sysinfo
  - kernel/sys.c:__ia32_compat_sys_sysinfo
```
**Symbols:**

```
ffffffff810b2810-ffffffff810b2a63: __do_compat_sys_sysinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __do_compat_sys_sysinfo(struct compat_sysinfo *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b8ee0)
Location: kernel/sys.c:2620
Inline: False
Direct callers:
  - kernel/sys.c:__x32_compat_sys_sysinfo
  - kernel/sys.c:__ia32_compat_sys_sysinfo
```
**Symbols:**

```
ffffffff810b8ee0-ffffffff810b905d: __do_compat_sys_sysinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __do_compat_sys_sysinfo(struct compat_sysinfo *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810c1000)
Location: kernel/sys.c:2662
Inline: False
Direct callers:
  - kernel/sys.c:__x32_compat_sys_sysinfo
  - kernel/sys.c:__ia32_compat_sys_sysinfo
```
**Symbols:**

```
ffffffff810c1000-ffffffff810c1196: __do_compat_sys_sysinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_compat_sys_sysinfo(struct compat_sysinfo *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810bc160)
Location: kernel/sys.c:2670
Inline: False
Direct callers:
  - kernel/sys.c:__x32_compat_sys_sysinfo
  - kernel/sys.c:__ia32_compat_sys_sysinfo
```
**Symbols:**

```
ffffffff810bc160-ffffffff810bc2f6: __do_compat_sys_sysinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_compat_sys_sysinfo(struct compat_sysinfo *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810bd9e0)
Location: kernel/sys.c:2697
Inline: False
Direct callers:
  - kernel/sys.c:__x32_compat_sys_sysinfo
  - kernel/sys.c:__ia32_compat_sys_sysinfo
```
**Symbols:**

```
ffffffff810bd9e0-ffffffff810bdb72: __do_compat_sys_sysinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long int __do_compat_sys_sysinfo(struct compat_sysinfo *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sys.c (0)
Location: kernel/sys.c:2673
Inline: False
Direct callers:
  - kernel/sys.c:__x64_compat_sys_sysinfo
  - kernel/sys.c:__ia32_compat_sys_sysinfo
```
**Symbols:**

```
ffffffff810d04d0-ffffffff810d0691: __do_compat_sys_sysinfo (STB_LOCAL)
ffffffff81ca4ac0-ffffffff81ca4bf1: __do_compat_sys_sysinfo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long int __do_compat_sys_sysinfo(struct compat_sysinfo *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sys.c (0)
Location: kernel/sys.c:2758
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_compat_sys_sysinfo
```
**Symbols:**

```
ffffffff810e9420-ffffffff810e9616: __do_compat_sys_sysinfo (STB_LOCAL)
ffffffff81e54386-ffffffff81e544b7: __do_compat_sys_sysinfo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
long int __do_compat_sys_sysinfo(struct compat_sysinfo *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sys.c (0)
Location: kernel/sys.c:2763
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_compat_sys_sysinfo
```
**Symbols:**

```
ffffffff8110a300-ffffffff8110a4f6: __do_compat_sys_sysinfo (STB_LOCAL)
ffffffff820563c5-ffffffff820564f6: __do_compat_sys_sysinfo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
long int __do_compat_sys_sysinfo(struct compat_sysinfo *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sys.c (0)
Location: kernel/sys.c:2855
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_compat_sys_sysinfo
```
**Symbols:**

```
ffffffff811165d0-ffffffff811167bf: __do_compat_sys_sysinfo (STB_LOCAL)
ffffffff820d48f4-ffffffff820d49ea: __do_compat_sys_sysinfo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
long int __do_compat_sys_sysinfo(struct compat_sysinfo *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sys.c (0)
Location: kernel/sys.c:2892
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_compat_sys_sysinfo
```
**Symbols:**

```
ffffffff8111ffc0-ffffffff811201af: __do_compat_sys_sysinfo (STB_LOCAL)
ffffffff821af7dd-ffffffff821af8d3: __do_compat_sys_sysinfo.cold (STB_LOCAL)
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
long int __do_compat_sys_sysinfo(struct compat_sysinfo *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffff800010117530)
Location: kernel/sys.c:2620
Inline: False
Direct callers:
  - kernel/sys.c:__arm64_compat_sys_sysinfo
```
**Symbols:**

```
ffff800010117530-ffff800010117e68: __do_compat_sys_sysinfo (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __do_compat_sys_sysinfo(struct compat_sysinfo *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (c00000000015e6f0)
Location: kernel/sys.c:2620
Inline: False
Direct callers:
  - kernel/sys.c:__se_compat_sys_sysinfo
```
**Symbols:**

```
c00000000015e6f0-c00000000015eec0: __do_compat_sys_sysinfo (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
long int __do_compat_sys_sysinfo(struct compat_sysinfo *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b3250)
Location: kernel/sys.c:2620
Inline: False
Direct callers:
  - kernel/sys.c:__x32_compat_sys_sysinfo
  - kernel/sys.c:__ia32_compat_sys_sysinfo
```
**Symbols:**

```
ffffffff810b3250-ffffffff810b33cd: __do_compat_sys_sysinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __do_compat_sys_sysinfo(struct compat_sysinfo *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810a1b80)
Location: kernel/sys.c:2620
Inline: False
Direct callers:
  - kernel/sys.c:__x32_compat_sys_sysinfo
  - kernel/sys.c:__ia32_compat_sys_sysinfo
```
**Symbols:**

```
ffffffff810a1b80-ffffffff810a1cfd: __do_compat_sys_sysinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __do_compat_sys_sysinfo(struct compat_sysinfo *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b27b0)
Location: kernel/sys.c:2620
Inline: False
Direct callers:
  - kernel/sys.c:__x32_compat_sys_sysinfo
  - kernel/sys.c:__ia32_compat_sys_sysinfo
```
**Symbols:**

```
ffffffff810b27b0-ffffffff810b292d: __do_compat_sys_sysinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __do_compat_sys_sysinfo(struct compat_sysinfo *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810badb0)
Location: kernel/sys.c:2620
Inline: False
Direct callers:
  - kernel/sys.c:__x32_compat_sys_sysinfo
  - kernel/sys.c:__ia32_compat_sys_sysinfo
```
**Symbols:**

```
ffffffff810badb0-ffffffff810baf2d: __do_compat_sys_sysinfo (STB_LOCAL)
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
