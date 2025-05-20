# Function: <code>prctl_set_mm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int prctl_set_mm(int opt, long unsigned int addr, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff81093340)
Location: kernel/sys.c:1949
Inline: False
Direct callers:
  - kernel/sys.c:SyS_prctl
```
**Symbols:**

```
ffffffff81093340-ffffffff810936a0: prctl_set_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int prctl_set_mm(int opt, long unsigned int addr, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff81096520)
Location: kernel/sys.c:1949
Inline: False
Direct callers:
  - kernel/sys.c:SyS_prctl
```
**Symbols:**

```
ffffffff81096520-ffffffff81096886: prctl_set_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int prctl_set_mm(int opt, long unsigned int addr, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff8109b4e0)
Location: kernel/sys.c:1940
Inline: False
Direct callers:
  - kernel/sys.c:SyS_prctl
```
**Symbols:**

```
ffffffff8109b4e0-ffffffff8109b839: prctl_set_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int prctl_set_mm(int opt, long unsigned int addr, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810982f0)
Location: kernel/sys.c:2046
Inline: False
Direct callers:
  - kernel/sys.c:SyS_prctl
```
**Symbols:**

```
ffffffff810982f0-ffffffff8109864e: prctl_set_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int prctl_set_mm(int opt, long unsigned int addr, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff8109efc0)
Location: kernel/sys.c:2049
Inline: False
Direct callers:
  - kernel/sys.c:SyS_prctl
```
**Symbols:**

```
ffffffff8109efc0-ffffffff8109f324: prctl_set_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int prctl_set_mm(int opt, long unsigned int addr, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810a5270)
Location: kernel/sys.c:2109
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
**Symbols:**

```
ffffffff810a5270-ffffffff810a55e8: prctl_set_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int prctl_set_mm(int opt, long unsigned int addr, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810adf20)
Location: kernel/sys.c:2110
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
**Symbols:**

```
ffffffff810adf20-ffffffff810ae2ea: prctl_set_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int prctl_set_mm(int opt, long unsigned int addr, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b41d0)
Location: kernel/sys.c:2109
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
**Symbols:**

```
ffffffff810b41d0-ffffffff810b45f2: prctl_set_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int prctl_set_mm(int opt, long unsigned int addr, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810ba7c0)
Location: kernel/sys.c:2099
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
**Symbols:**

```
ffffffff810ba7c0-ffffffff810babe2: prctl_set_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int prctl_set_mm(int opt, long unsigned int addr, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810c2950)
Location: kernel/sys.c:2115
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
```
**Symbols:**

```
ffffffff810c2950-ffffffff810c2d82: prctl_set_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int prctl_set_mm(int opt, long unsigned int addr, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810bdd40)
Location: kernel/sys.c:2119
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
```
**Symbols:**

```
ffffffff810bdd40-ffffffff810be197: prctl_set_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int prctl_set_mm(int opt, long unsigned int addr, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810bf5e0)
Location: kernel/sys.c:2136
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
```
**Symbols:**

```
ffffffff810bf5e0-ffffffff810bfad1: prctl_set_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int prctl_set_mm(int opt, long unsigned int addr, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810d2060)
Location: kernel/sys.c:2107
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
```
**Symbols:**

```
ffffffff810d2060-ffffffff810d254b: prctl_set_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int prctl_set_mm(int opt, long unsigned int addr, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810ea3c0)
Location: kernel/sys.c:2119
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
```
**Symbols:**

```
ffffffff810ea3c0-ffffffff810eaa63: prctl_set_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int prctl_set_mm(int opt, long unsigned int addr, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff8110aec0)
Location: kernel/sys.c:2124
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
```
**Symbols:**

```
ffffffff8110aec0-ffffffff8110b563: prctl_set_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int prctl_set_mm(int opt, long unsigned int addr, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff81117080)
Location: kernel/sys.c:2142
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
```
**Symbols:**

```
ffffffff81117080-ffffffff81117725: prctl_set_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int prctl_set_mm(int opt, long unsigned int addr, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff81120a70)
Location: kernel/sys.c:2155
Inline: False
Direct callers:
  - kernel/sys.c:__do_sys_prctl
```
**Symbols:**

```
ffffffff81120a70-ffffffff81121115: prctl_set_mm (STB_LOCAL)
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
int prctl_set_mm(int opt, long unsigned int addr, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffff800010115da8)
Location: kernel/sys.c:2099
Inline: False
Direct callers:
  - kernel/sys.c:__arm64_sys_prctl
```
**Symbols:**

```
ffff800010115da8-ffff800010116104: prctl_set_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int prctl_set_mm(int opt, long unsigned int addr, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (c036b61c)
Location: kernel/sys.c:2099
Inline: False
Direct callers:
  - kernel/sys.c:__se_sys_prctl
```
**Symbols:**

```
c036b61c-c036b9a0: prctl_set_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int prctl_set_mm(int opt, long unsigned int addr, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (c00000000015f210)
Location: kernel/sys.c:2099
Inline: False
Direct callers:
  - kernel/sys.c:__se_sys_prctl
```
**Symbols:**

```
c00000000015f210-c00000000015f658: prctl_set_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int prctl_set_mm(int opt, long unsigned int addr, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffe0000d2852)
Location: kernel/sys.c:2099
Inline: False
Direct callers:
  - kernel/sys.c:__se_sys_prctl
```
**Symbols:**

```
ffffffe0000d2852-ffffffe0000d2b08: prctl_set_mm (STB_LOCAL)
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
int prctl_set_mm(int opt, long unsigned int addr, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b4b30)
Location: kernel/sys.c:2099
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
**Symbols:**

```
ffffffff810b4b30-ffffffff810b4f52: prctl_set_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int prctl_set_mm(int opt, long unsigned int addr, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810a3460)
Location: kernel/sys.c:2099
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
**Symbols:**

```
ffffffff810a3460-ffffffff810a3882: prctl_set_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int prctl_set_mm(int opt, long unsigned int addr, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810b4090)
Location: kernel/sys.c:2099
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
**Symbols:**

```
ffffffff810b4090-ffffffff810b44b2: prctl_set_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int prctl_set_mm(int opt, long unsigned int addr, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810bb3d0)
Location: kernel/sys.c:2099
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_prctl
  - kernel/sys.c:__x64_sys_prctl
```
**Symbols:**

```
ffffffff810bb3d0-ffffffff810bb7f0: prctl_set_mm (STB_LOCAL)
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
