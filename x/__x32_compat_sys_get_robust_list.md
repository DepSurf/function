# Function: <code>__x32_compat_sys_get_robust_list</code>

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
long int __x32_compat_sys_get_robust_list(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex_compat.c (ffffffff8112bda0)
Location: kernel/futex_compat.c:136
Inline: False
```
**Symbols:**

```
ffffffff8112bda0-ffffffff8112be3e: __x32_compat_sys_get_robust_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int __x32_compat_sys_get_robust_list(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81133870)
Location: kernel/futex.c:3789
Inline: False
```
**Symbols:**

```
ffffffff81133870-ffffffff8113390e: __x32_compat_sys_get_robust_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int __x32_compat_sys_get_robust_list(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8113e8d0)
Location: kernel/futex.c:3827
Inline: False
```
**Symbols:**

```
ffffffff8113e8d0-ffffffff8113e973: __x32_compat_sys_get_robust_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __x32_compat_sys_get_robust_list(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8114a440)
Location: kernel/futex.c:4080
Inline: False
```
**Symbols:**

```
ffffffff8114a440-ffffffff8114a4e3: __x32_compat_sys_get_robust_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __x32_compat_sys_get_robust_list(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff8115af60)
Location: kernel/sys_ni.c:149
Inline: False
```
**Symbols:**

```
ffffffff8115af60-ffffffff8115b003: __x32_compat_sys_get_robust_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __x32_compat_sys_get_robust_list(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff81157070)
Location: kernel/sys_ni.c:151
Inline: False
```
**Symbols:**

```
ffffffff81157070-ffffffff8115712f: __x32_compat_sys_get_robust_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __x32_compat_sys_get_robust_list(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff81158490)
Location: kernel/sys_ni.c:152
Inline: False
```
**Symbols:**

```
ffffffff81158490-ffffffff81158551: __x32_compat_sys_get_robust_list (STB_GLOBAL)
```
</details>
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
<summary>In <code>aws</code>: ✅</summary>

```c
long int __x32_compat_sys_get_robust_list(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81142a60)
Location: kernel/futex.c:4080
Inline: False
```
**Symbols:**

```
ffffffff81142a60-ffffffff81142b03: __x32_compat_sys_get_robust_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __x32_compat_sys_get_robust_list(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81135dc0)
Location: kernel/futex.c:4080
Inline: False
```
**Symbols:**

```
ffffffff81135dc0-ffffffff81135e63: __x32_compat_sys_get_robust_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __x32_compat_sys_get_robust_list(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81140910)
Location: kernel/futex.c:4080
Inline: False
```
**Symbols:**

```
ffffffff81140910-ffffffff811409b3: __x32_compat_sys_get_robust_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __x32_compat_sys_get_robust_list(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8114db50)
Location: kernel/futex.c:4080
Inline: False
```
**Symbols:**

```
ffffffff8114db50-ffffffff8114dc16: __x32_compat_sys_get_robust_list (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct pt_regs *__unused</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct pt_regs *regs</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
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
