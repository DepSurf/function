# Function: <code>__do_sys_reboot</code>

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
long int __do_sys_reboot(int magic1, int magic2, unsigned int cmd, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810b6160)
Location: kernel/reboot.c:307
Inline: False
Direct callers:
  - kernel/reboot.c:__ia32_sys_reboot
  - kernel/reboot.c:__x64_sys_reboot
```
**Symbols:**

```
ffffffff810b6160-ffffffff810b636a: __do_sys_reboot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int __do_sys_reboot(int magic1, int magic2, unsigned int cmd, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810bf3f0)
Location: kernel/reboot.c:308
Inline: False
Direct callers:
  - kernel/reboot.c:__ia32_sys_reboot
  - kernel/reboot.c:__x64_sys_reboot
```
**Symbols:**

```
ffffffff810bf3f0-ffffffff810bf5fa: __do_sys_reboot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int __do_sys_reboot(int magic1, int magic2, unsigned int cmd, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810c5510)
Location: kernel/reboot.c:310
Inline: False
Direct callers:
  - kernel/reboot.c:__ia32_sys_reboot
  - kernel/reboot.c:__x64_sys_reboot
```
**Symbols:**

```
ffffffff810c5510-ffffffff810c5715: __do_sys_reboot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __do_sys_reboot(int magic1, int magic2, unsigned int cmd, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810ce610)
Location: kernel/reboot.c:310
Inline: False
Direct callers:
  - kernel/reboot.c:__ia32_sys_reboot
  - kernel/reboot.c:__x64_sys_reboot
```
**Symbols:**

```
ffffffff810ce610-ffffffff810ce815: __do_sys_reboot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
long int __do_sys_reboot(int magic1, int magic2, unsigned int cmd, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/reboot.c (0)
Location: kernel/reboot.c:310
Inline: False
Direct callers:
  - kernel/reboot.c:__ia32_sys_reboot
  - kernel/reboot.c:__x64_sys_reboot
```
**Symbols:**

```
ffffffff810d8450-ffffffff810d864a: __do_sys_reboot (STB_LOCAL)
ffffffff810d87a0-ffffffff810d87fb: __do_sys_reboot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
long int __do_sys_reboot(int magic1, int magic2, unsigned int cmd, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/reboot.c (0)
Location: kernel/reboot.c:310
Inline: False
Direct callers:
  - kernel/reboot.c:__ia32_sys_reboot
  - kernel/reboot.c:__x64_sys_reboot
```
**Symbols:**

```
ffffffff810d3710-ffffffff810d390a: __do_sys_reboot (STB_LOCAL)
ffffffff81bdc383-ffffffff81bdc3de: __do_sys_reboot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
long int __do_sys_reboot(int magic1, int magic2, unsigned int cmd, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/reboot.c (0)
Location: kernel/reboot.c:310
Inline: False
Direct callers:
  - kernel/reboot.c:__ia32_sys_reboot
  - kernel/reboot.c:__x64_sys_reboot
```
**Symbols:**

```
ffffffff810d5400-ffffffff810d55fa: __do_sys_reboot (STB_LOCAL)
ffffffff81bce4a6-ffffffff81bce501: __do_sys_reboot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long int __do_sys_reboot(int magic1, int magic2, unsigned int cmd, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/reboot.c (0)
Location: kernel/reboot.c:311
Inline: False
Direct callers:
  - kernel/reboot.c:__ia32_sys_reboot
  - kernel/reboot.c:__x64_sys_reboot
```
**Symbols:**

```
ffffffff810e8620-ffffffff810e881a: __do_sys_reboot (STB_LOCAL)
ffffffff81ca58a8-ffffffff81ca5903: __do_sys_reboot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long int __do_sys_reboot(int magic1, int magic2, unsigned int cmd, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/reboot.c (0)
Location: kernel/reboot.c:683
Inline: False
Direct callers:
  - kernel/reboot.c:__ia32_sys_reboot
  - kernel/reboot.c:__x64_sys_reboot
```
**Symbols:**

```
ffffffff81102fb0-ffffffff811031df: __do_sys_reboot (STB_LOCAL)
ffffffff81e551a4-ffffffff81e551fc: __do_sys_reboot.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_sys_reboot(int magic1, int magic2, unsigned int cmd, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff811284c0)
Location: kernel/reboot.c:700
Inline: False
Direct callers:
  - kernel/reboot.c:__ia32_sys_reboot
  - kernel/reboot.c:__x64_sys_reboot
```
**Symbols:**

```
ffffffff811284c0-ffffffff811286f5: __do_sys_reboot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __do_sys_reboot(int magic1, int magic2, unsigned int cmd, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff81135970)
Location: kernel/reboot.c:700
Inline: False
Direct callers:
  - kernel/reboot.c:__ia32_sys_reboot
  - kernel/reboot.c:__x64_sys_reboot
```
**Symbols:**

```
ffffffff81135970-ffffffff81135bac: __do_sys_reboot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __do_sys_reboot(int magic1, int magic2, unsigned int cmd, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff811409f0)
Location: kernel/reboot.c:715
Inline: False
Direct callers:
  - kernel/reboot.c:__ia32_sys_reboot
  - kernel/reboot.c:__x64_sys_reboot
```
**Symbols:**

```
ffffffff811409f0-ffffffff81140c3a: __do_sys_reboot (STB_LOCAL)
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
long int __do_sys_reboot(int magic1, int magic2, unsigned int cmd, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffff80001012e108)
Location: kernel/reboot.c:310
Inline: False
Direct callers:
  - kernel/reboot.c:__arm64_sys_reboot
```
**Symbols:**

```
ffff80001012e108-ffff80001012e32c: __do_sys_reboot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int __do_sys_reboot(int magic1, int magic2, unsigned int cmd, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (c037df38)
Location: kernel/reboot.c:310
Inline: False
Direct callers:
  - kernel/reboot.c:__se_sys_reboot
```
**Symbols:**

```
c037df38-c037e16c: __do_sys_reboot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __do_sys_reboot(int magic1, int magic2, unsigned int cmd, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (c000000000177120)
Location: kernel/reboot.c:310
Inline: False
Direct callers:
  - kernel/reboot.c:__se_sys_reboot
```
**Symbols:**

```
c000000000177120-c0000000001773c8: __do_sys_reboot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int __do_sys_reboot(int magic1, int magic2, unsigned int cmd, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffe0000e21aa)
Location: kernel/reboot.c:310
Inline: False
Direct callers:
  - kernel/reboot.c:__se_sys_reboot
```
**Symbols:**

```
ffffffe0000e21aa-ffffffe0000e234c: __do_sys_reboot (STB_LOCAL)
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
long int __do_sys_reboot(int magic1, int magic2, unsigned int cmd, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810c8990)
Location: kernel/reboot.c:310
Inline: False
Direct callers:
  - kernel/reboot.c:__ia32_sys_reboot
  - kernel/reboot.c:__x64_sys_reboot
```
**Symbols:**

```
ffffffff810c8990-ffffffff810c8b95: __do_sys_reboot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __do_sys_reboot(int magic1, int magic2, unsigned int cmd, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810b71b0)
Location: kernel/reboot.c:310
Inline: False
Direct callers:
  - kernel/reboot.c:__ia32_sys_reboot
  - kernel/reboot.c:__x64_sys_reboot
```
**Symbols:**

```
ffffffff810b71b0-ffffffff810b73b5: __do_sys_reboot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __do_sys_reboot(int magic1, int magic2, unsigned int cmd, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810c7ec0)
Location: kernel/reboot.c:310
Inline: False
Direct callers:
  - kernel/reboot.c:__ia32_sys_reboot
  - kernel/reboot.c:__x64_sys_reboot
```
**Symbols:**

```
ffffffff810c7ec0-ffffffff810c80c5: __do_sys_reboot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __do_sys_reboot(int magic1, int magic2, unsigned int cmd, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810d03b0)
Location: kernel/reboot.c:310
Inline: False
Direct callers:
  - kernel/reboot.c:__ia32_sys_reboot
  - kernel/reboot.c:__x64_sys_reboot
```
**Symbols:**

```
ffffffff810d03b0-ffffffff810d05b5: __do_sys_reboot (STB_LOCAL)
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
