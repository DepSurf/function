# Function: <code>__ia32_sys_gethostname</code>

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
long int __ia32_sys_gethostname(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810a5d40)
Location: kernel/sys.c:1346
Inline: False
```
**Symbols:**

```
ffffffff810a5d40-ffffffff810a5e9f: __ia32_sys_gethostname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int __ia32_sys_gethostname(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810aeba0)
Location: kernel/sys.c:1347
Inline: False
```
**Symbols:**

```
ffffffff810aeba0-ffffffff810aecff: __ia32_sys_gethostname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
long int __ia32_sys_gethostname(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sys.c (0)
Location: kernel/sys.c:1347
Inline: False
```
**Symbols:**

```
ffffffff810b799d-ffffffff810b79a9: __ia32_sys_gethostname.cold (STB_LOCAL)
ffffffff810b2440-ffffffff810b2528: __ia32_sys_gethostname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
long int __ia32_sys_gethostname(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sys.c (0)
Location: kernel/sys.c:1347
Inline: False
```
**Symbols:**

```
ffffffff810bdea4-ffffffff810bdeb0: __ia32_sys_gethostname.cold (STB_LOCAL)
ffffffff810b8b10-ffffffff810b8bf8: __ia32_sys_gethostname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
long int __ia32_sys_gethostname(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sys.c (0)
Location: kernel/sys.c:1363
Inline: False
```
**Symbols:**

```
ffffffff810c50e4-ffffffff810c50f0: __ia32_sys_gethostname.cold (STB_LOCAL)
ffffffff810c04b0-ffffffff810c0598: __ia32_sys_gethostname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
long int __ia32_sys_gethostname(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sys.c (0)
Location: kernel/sys.c:1364
Inline: False
```
**Symbols:**

```
ffffffff81bdba8e-ffffffff81bdbaa6: __ia32_sys_gethostname.cold (STB_LOCAL)
ffffffff810bb6d0-ffffffff810bb846: __ia32_sys_gethostname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
long int __ia32_sys_gethostname(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sys.c (0)
Location: kernel/sys.c:1381
Inline: False
```
**Symbols:**

```
ffffffff81bcdb46-ffffffff81bcdb5e: __ia32_sys_gethostname.cold (STB_LOCAL)
ffffffff810bd020-ffffffff810bd192: __ia32_sys_gethostname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long int __ia32_sys_gethostname(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sys.c (0)
Location: kernel/sys.c:1390
Inline: False
```
**Symbols:**

```
ffffffff81ca4998-ffffffff81ca49b0: __ia32_sys_gethostname.cold (STB_LOCAL)
ffffffff810cfa00-ffffffff810cfb72: __ia32_sys_gethostname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long int __ia32_sys_gethostname(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sys.c (0)
Location: kernel/sys.c:1397
Inline: False
```
**Symbols:**

```
ffffffff81e5426c-ffffffff81e54284: __ia32_sys_gethostname.cold (STB_LOCAL)
ffffffff810e8c20-ffffffff810e8dc2: __ia32_sys_gethostname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __ia32_sys_gethostname(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff81109480)
Location: kernel/sys.c:1399
Inline: False
```
**Symbols:**

```
ffffffff81109480-ffffffff8110963a: __ia32_sys_gethostname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __ia32_sys_gethostname(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff811159a0)
Location: kernel/sys.c:1417
Inline: False
```
**Symbols:**

```
ffffffff811159a0-ffffffff811159c1: __ia32_sys_gethostname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __ia32_sys_gethostname(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff8111f390)
Location: kernel/sys.c:1417
Inline: False
```
**Symbols:**

```
ffffffff8111f390-ffffffff8111f3b1: __ia32_sys_gethostname (STB_GLOBAL)
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
long int __ia32_sys_gethostname(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sys.c (0)
Location: kernel/sys.c:1347
Inline: False
```
**Symbols:**

```
ffffffff810b8214-ffffffff810b8220: __ia32_sys_gethostname.cold (STB_LOCAL)
ffffffff810b2e80-ffffffff810b2f68: __ia32_sys_gethostname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
long int __ia32_sys_gethostname(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sys.c (0)
Location: kernel/sys.c:1347
Inline: False
```
**Symbols:**

```
ffffffff810a6b54-ffffffff810a6b60: __ia32_sys_gethostname.cold (STB_LOCAL)
ffffffff810a17b0-ffffffff810a1898: __ia32_sys_gethostname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
long int __ia32_sys_gethostname(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sys.c (0)
Location: kernel/sys.c:1347
Inline: False
```
**Symbols:**

```
ffffffff810b7774-ffffffff810b7780: __ia32_sys_gethostname.cold (STB_LOCAL)
ffffffff810b23e0-ffffffff810b24c8: __ia32_sys_gethostname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
long int __ia32_sys_gethostname(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sys.c (0)
Location: kernel/sys.c:1347
Inline: False
```
**Symbols:**

```
ffffffff810bfaf4-ffffffff810bfb00: __ia32_sys_gethostname.cold (STB_LOCAL)
ffffffff810ba9e0-ffffffff810baac8: __ia32_sys_gethostname (STB_GLOBAL)
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
