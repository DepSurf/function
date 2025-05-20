# Function: <code>arch_get_kallsym</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int arch_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81140b60)
Location: kernel/kallsyms.c:447
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter
```
**Symbols:**

```
ffffffff81140b60-ffffffff81140b70: arch_get_kallsym (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int arch_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff8114bf50)
Location: kernel/kallsyms.c:450
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter
```
**Symbols:**

```
ffffffff8114bf50-ffffffff8114bf60: arch_get_kallsym (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int arch_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81157c20)
Location: kernel/kallsyms.c:450
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter
```
**Symbols:**

```
ffffffff81157c20-ffffffff81157c30: arch_get_kallsym (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int arch_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff811687d0)
Location: kernel/kallsyms.c:449
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter_mod
```
**Symbols:**

```
ffffffff811687d0-ffffffff811687e0: arch_get_kallsym (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int arch_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81164dc0)
Location: kernel/kallsyms.c:451
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter_mod
```
**Symbols:**

```
ffffffff81164dc0-ffffffff81164dd0: arch_get_kallsym (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int arch_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81165b90)
Location: kernel/kallsyms.c:502
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter_mod
```
**Symbols:**

```
ffffffff81165b90-ffffffff81165ba0: arch_get_kallsym (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int arch_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff8118b350)
Location: kernel/kallsyms.c:566
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter_mod
```
**Symbols:**

```
ffffffff8118b350-ffffffff8118b360: arch_get_kallsym (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int arch_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff811ba650)
Location: kernel/kallsyms.c:590
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter_mod
```
**Symbols:**

```
ffffffff811ba650-ffffffff811ba664: arch_get_kallsym (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int arch_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff811fc310)
Location: kernel/kallsyms.c:663
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter_mod
```
**Symbols:**

```
ffffffff811fc310-ffffffff811fc324: arch_get_kallsym (STB_WEAK)
```
</details>
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
int arch_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffff8000101c7100)
Location: kernel/kallsyms.c:450
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter
```
**Symbols:**

```
ffff8000101c7100-ffff8000101c711c: arch_get_kallsym (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int arch_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (c040e048)
Location: kernel/kallsyms.c:450
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter
```
**Symbols:**

```
c040e048-c040e064: arch_get_kallsym (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int arch_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (c00000000022f2d0)
Location: kernel/kallsyms.c:450
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter
```
**Symbols:**

```
c00000000022f2d0-c00000000022f2e0: arch_get_kallsym (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int arch_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffe000147448)
Location: kernel/kallsyms.c:450
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter
```
**Symbols:**

```
ffffffe000147448-ffffffe000147464: arch_get_kallsym (STB_WEAK)
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
int arch_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff81150240)
Location: kernel/kallsyms.c:450
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter
```
**Symbols:**

```
ffffffff81150240-ffffffff81150250: arch_get_kallsym (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int arch_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff811434f0)
Location: kernel/kallsyms.c:450
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter
```
**Symbols:**

```
ffffffff811434f0-ffffffff81143500: arch_get_kallsym (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int arch_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff8114e0f0)
Location: kernel/kallsyms.c:450
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter
```
**Symbols:**

```
ffffffff8114e0f0-ffffffff8114e100: arch_get_kallsym (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int arch_get_kallsym(unsigned int symnum, long unsigned int *value, char *type, char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffff8115aed0)
Location: kernel/kallsyms.c:450
Inline: False
Direct callers:
  - kernel/kallsyms.c:update_iter
```
**Symbols:**

```
ffffffff8115aed0-ffffffff8115aee0: arch_get_kallsym (STB_WEAK)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
