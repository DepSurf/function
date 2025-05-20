# Function: <code>__x32_compat_sys_set_robust_list</code>

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
long int __x32_compat_sys_set_robust_list(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex_compat.c (ffffffff8112bb30)
Location: kernel/futex_compat.c:121
Inline: False
```
**Symbols:**

```
ffffffff8112bb30-ffffffff8112bb74: __x32_compat_sys_set_robust_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int __x32_compat_sys_set_robust_list(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81133440)
Location: kernel/futex.c:3774
Inline: False
```
**Symbols:**

```
ffffffff81133440-ffffffff81133484: __x32_compat_sys_set_robust_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int __x32_compat_sys_set_robust_list(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8113e300)
Location: kernel/futex.c:3812
Inline: False
```
**Symbols:**

```
ffffffff8113e300-ffffffff8113e346: __x32_compat_sys_set_robust_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __x32_compat_sys_set_robust_list(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81149e90)
Location: kernel/futex.c:4065
Inline: False
```
**Symbols:**

```
ffffffff81149e90-ffffffff81149ed6: __x32_compat_sys_set_robust_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __x32_compat_sys_set_robust_list(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff8115a700)
Location: kernel/sys_ni.c:147
Inline: False
```
**Symbols:**

```
ffffffff8115a700-ffffffff8115a746: __x32_compat_sys_set_robust_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __x32_compat_sys_set_robust_list(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff81156750)
Location: kernel/sys_ni.c:149
Inline: False
```
**Symbols:**

```
ffffffff81156750-ffffffff81156796: __x32_compat_sys_set_robust_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __x32_compat_sys_set_robust_list(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff81157b50)
Location: kernel/sys_ni.c:150
Inline: False
```
**Symbols:**

```
ffffffff81157b50-ffffffff81157b96: __x32_compat_sys_set_robust_list (STB_GLOBAL)
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
long int __x32_compat_sys_set_robust_list(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff811424b0)
Location: kernel/futex.c:4065
Inline: False
```
**Symbols:**

```
ffffffff811424b0-ffffffff811424f6: __x32_compat_sys_set_robust_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __x32_compat_sys_set_robust_list(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81135810)
Location: kernel/futex.c:4065
Inline: False
```
**Symbols:**

```
ffffffff81135810-ffffffff81135856: __x32_compat_sys_set_robust_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __x32_compat_sys_set_robust_list(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81140360)
Location: kernel/futex.c:4065
Inline: False
```
**Symbols:**

```
ffffffff81140360-ffffffff811403a6: __x32_compat_sys_set_robust_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __x32_compat_sys_set_robust_list(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8114ce90)
Location: kernel/futex.c:4065
Inline: False
```
**Symbols:**

```
ffffffff8114ce90-ffffffff8114ced6: __x32_compat_sys_set_robust_list (STB_GLOBAL)
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
