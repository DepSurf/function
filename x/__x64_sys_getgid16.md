# Function: <code>__x64_sys_getgid16</code>

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
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
long int __x64_sys_getgid16();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff8112d840)
Location: kernel/uid16.c:213
Inline: True
```
**Symbols:**

```
ffffffff8112d840-ffffffff8112d896: __x64_sys_getgid16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
long int __x64_sys_getgid16();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff81139130)
Location: kernel/uid16.c:213
Inline: True
```
**Symbols:**

```
ffffffff81139130-ffffffff81139186: __x64_sys_getgid16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
long int __x64_sys_getgid16();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff81144320)
Location: kernel/uid16.c:213
Inline: True
```
**Symbols:**

```
ffffffff81144320-ffffffff81144376: __x64_sys_getgid16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
long int __x64_sys_getgid16(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810cc120)
Location: kernel/sys_ni.c:434
Inline: True
```
**Symbols:**

```
ffffffff8114fe00-ffffffff8114fe56: __x64_sys_getgid16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __x64_sys_getgid16(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (0)
Location: kernel/sys_ni.c:457
Inline: False
```
**Symbols:**

```
ffffffff811605e0-ffffffff8116063c: __x64_sys_getgid16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __x64_sys_getgid16(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (0)
Location: kernel/sys_ni.c:458
Inline: False
```
**Symbols:**

```
ffffffff8115c570-ffffffff8115c5cc: __x64_sys_getgid16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __x64_sys_getgid16(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (0)
Location: kernel/sys_ni.c:464
Inline: False
```
**Symbols:**

```
ffffffff8115d790-ffffffff8115d7ec: __x64_sys_getgid16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __x64_sys_getgid16(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (0)
Location: kernel/sys_ni.c:461
Inline: False
```
**Symbols:**

```
ffffffff81182a90-ffffffff81182aec: __x64_sys_getgid16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __x64_sys_getgid16(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (0)
Location: kernel/sys_ni.c:464
Inline: False
```
**Symbols:**

```
ffffffff811b93a0-ffffffff811b940c: __x64_sys_getgid16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __x64_sys_getgid16(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (0)
Location: kernel/sys_ni.c:464
Inline: False
```
**Symbols:**

```
ffffffff811fa910-ffffffff811fa97c: __x64_sys_getgid16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __x64_sys_getgid16(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (0)
Location: kernel/sys_ni.c:357
Inline: False
```
**Symbols:**

```
ffffffff8120fcb0-ffffffff8120fd1c: __x64_sys_getgid16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __x64_sys_getgid16(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (0)
Location: kernel/sys_ni.c:376
Inline: False
```
**Symbols:**

```
ffffffff81227280-ffffffff812272ec: __x64_sys_getgid16 (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
long int __x64_sys_getgid16(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810c64a0)
Location: kernel/sys_ni.c:434
Inline: True
```
**Symbols:**

```
ffffffff81148420-ffffffff81148476: __x64_sys_getgid16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
long int __x64_sys_getgid16(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810b4cc0)
Location: kernel/sys_ni.c:434
Inline: True
```
**Symbols:**

```
ffffffff8113b6d0-ffffffff8113b726: __x64_sys_getgid16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
long int __x64_sys_getgid16(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810c59f0)
Location: kernel/sys_ni.c:434
Inline: True
```
**Symbols:**

```
ffffffff811462d0-ffffffff81146326: __x64_sys_getgid16 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
long int __x64_sys_getgid16(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff810cde30)
Location: kernel/sys_ni.c:434
Inline: True
```
**Symbols:**

```
ffffffff81152ee0-ffffffff81152f36: __x64_sys_getgid16 (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct pt_regs *__unused</code>
</li>
</ul>
</details>
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
