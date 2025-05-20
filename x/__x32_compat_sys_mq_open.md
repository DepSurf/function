# Function: <code>__x32_compat_sys_mq_open</code>

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
long int __x32_compat_sys_mq_open(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff813e0d70)
Location: ipc/mqueue.c:1410
Inline: False
```
**Symbols:**

```
ffffffff813e0d70-ffffffff813e0e41: __x32_compat_sys_mq_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int __x32_compat_sys_mq_open(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff813fb560)
Location: ipc/mqueue.c:1410
Inline: False
```
**Symbols:**

```
ffffffff813fb560-ffffffff813fb631: __x32_compat_sys_mq_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int __x32_compat_sys_mq_open(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff814278d0)
Location: ipc/mqueue.c:1465
Inline: False
```
**Symbols:**

```
ffffffff814278d0-ffffffff814279a1: __x32_compat_sys_mq_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int __x32_compat_sys_mq_open(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff81441600)
Location: ipc/mqueue.c:1460
Inline: False
```
**Symbols:**

```
ffffffff81441600-ffffffff814416d1: __x32_compat_sys_mq_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __x32_compat_sys_mq_open(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff81492250)
Location: kernel/sys_ni.c:192
Inline: False
```
**Symbols:**

```
ffffffff81492250-ffffffff81492321: __x32_compat_sys_mq_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __x32_compat_sys_mq_open(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff814afaa0)
Location: kernel/sys_ni.c:194
Inline: False
```
**Symbols:**

```
ffffffff814afaa0-ffffffff814afb71: __x32_compat_sys_mq_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __x32_compat_sys_mq_open(const struct pt_regs *__unused);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys_ni.c (ffffffff814b58e0)
Location: kernel/sys_ni.c:195
Inline: False
```
**Symbols:**

```
ffffffff814b58e0-ffffffff814b59b6: __x32_compat_sys_mq_open (STB_GLOBAL)
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
long int __x32_compat_sys_mq_open(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff81439be0)
Location: ipc/mqueue.c:1460
Inline: False
```
**Symbols:**

```
ffffffff81439be0-ffffffff81439cb1: __x32_compat_sys_mq_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int __x32_compat_sys_mq_open(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8142a650)
Location: ipc/mqueue.c:1460
Inline: False
```
**Symbols:**

```
ffffffff8142a650-ffffffff8142a721: __x32_compat_sys_mq_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int __x32_compat_sys_mq_open(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff81435d80)
Location: ipc/mqueue.c:1460
Inline: False
```
**Symbols:**

```
ffffffff81435d80-ffffffff81435e51: __x32_compat_sys_mq_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int __x32_compat_sys_mq_open(const struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8144e850)
Location: ipc/mqueue.c:1460
Inline: False
```
**Symbols:**

```
ffffffff8144e850-ffffffff8144e921: __x32_compat_sys_mq_open (STB_GLOBAL)
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
