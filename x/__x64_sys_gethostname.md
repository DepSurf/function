# Function: <code>__x64_sys_gethostname</code>

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
long int __x64_sys_gethostname(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810a5ea0)
Location: kernel/sys.c:1346
Inline: False
```
**Symbols:**

```
ffffffff810a5ea0-ffffffff810a5fff: __x64_sys_gethostname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int __x64_sys_gethostname(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810aea40)
Location: kernel/sys.c:1347
Inline: False
```
**Symbols:**

```
ffffffff810aea40-ffffffff810aeb9f: __x64_sys_gethostname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
long int __x64_sys_gethostname(const struct pt_regs *regs);
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
ffffffff810b79a9-ffffffff810b79b5: __x64_sys_gethostname.cold (STB_LOCAL)
ffffffff810b3c70-ffffffff810b3d58: __x64_sys_gethostname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
long int __x64_sys_gethostname(const struct pt_regs *regs);
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
ffffffff810bdeb0-ffffffff810bdebc: __x64_sys_gethostname.cold (STB_LOCAL)
ffffffff810ba260-ffffffff810ba348: __x64_sys_gethostname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
long int __x64_sys_gethostname(const struct pt_regs *regs);
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
ffffffff810c50f0-ffffffff810c50fc: __x64_sys_gethostname.cold (STB_LOCAL)
ffffffff810c2130-ffffffff810c2218: __x64_sys_gethostname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
long int __x64_sys_gethostname(const struct pt_regs *regs);
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
ffffffff81bdbaa6-ffffffff81bdbabe: __x64_sys_gethostname.cold (STB_LOCAL)
ffffffff810bd420-ffffffff810bd596: __x64_sys_gethostname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
long int __x64_sys_gethostname(const struct pt_regs *regs);
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
ffffffff81bcdb5e-ffffffff81bcdb76: __x64_sys_gethostname.cold (STB_LOCAL)
ffffffff810befd0-ffffffff810bf142: __x64_sys_gethostname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long int __x64_sys_gethostname(const struct pt_regs *regs);
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
ffffffff81ca4bf1-ffffffff81ca4c09: __x64_sys_gethostname.cold (STB_LOCAL)
ffffffff810d1970-ffffffff810d1ae2: __x64_sys_gethostname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long int __x64_sys_gethostname(const struct pt_regs *regs);
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
ffffffff81e544b7-ffffffff81e544cf: __x64_sys_gethostname.cold (STB_LOCAL)
ffffffff810eb1b0-ffffffff810eb352: __x64_sys_gethostname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __x64_sys_gethostname(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff8110c350)
Location: kernel/sys.c:1399
Inline: False
```
**Symbols:**

```
ffffffff8110c350-ffffffff8110c50a: __x64_sys_gethostname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __x64_sys_gethostname(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff81115960)
Location: kernel/sys.c:1417
Inline: False
```
**Symbols:**

```
ffffffff81115960-ffffffff81115982: __x64_sys_gethostname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __x64_sys_gethostname(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff8111f350)
Location: kernel/sys.c:1417
Inline: False
```
**Symbols:**

```
ffffffff8111f350-ffffffff8111f372: __x64_sys_gethostname (STB_GLOBAL)
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
long int __x64_sys_gethostname(const struct pt_regs *regs);
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
ffffffff810b8220-ffffffff810b822c: __x64_sys_gethostname.cold (STB_LOCAL)
ffffffff810b45d0-ffffffff810b46b8: __x64_sys_gethostname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
long int __x64_sys_gethostname(const struct pt_regs *regs);
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
ffffffff810a6b60-ffffffff810a6b6c: __x64_sys_gethostname.cold (STB_LOCAL)
ffffffff810a2f00-ffffffff810a2fe8: __x64_sys_gethostname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
long int __x64_sys_gethostname(const struct pt_regs *regs);
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
ffffffff810b7780-ffffffff810b778c: __x64_sys_gethostname.cold (STB_LOCAL)
ffffffff810b3b30-ffffffff810b3c18: __x64_sys_gethostname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
long int __x64_sys_gethostname(const struct pt_regs *regs);
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
ffffffff810bfb00-ffffffff810bfb0c: __x64_sys_gethostname.cold (STB_LOCAL)
ffffffff810bc2b0-ffffffff810bc398: __x64_sys_gethostname (STB_GLOBAL)
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
