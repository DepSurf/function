# Function: <code>__do_sys_getuid16</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long int __do_sys_getuid16(const struct pt_regs *__unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff81160520)
Location: kernel/uid16.c:203
Inline: True
```
**Symbols:**

```
ffffffff81160520-ffffffff8116057c: __do_sys_getuid16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long int __do_sys_getuid16(const struct pt_regs *__unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff8115c4b0)
Location: kernel/uid16.c:203
Inline: True
```
**Symbols:**

```
ffffffff8115c4b0-ffffffff8115c50c: __do_sys_getuid16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long int __do_sys_getuid16(const struct pt_regs *__unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff8115d6d0)
Location: kernel/uid16.c:203
Inline: True
```
**Symbols:**

```
ffffffff8115d6d0-ffffffff8115d72c: __do_sys_getuid16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long int __do_sys_getuid16(const struct pt_regs *__unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff811829d0)
Location: kernel/uid16.c:203
Inline: True
```
**Symbols:**

```
ffffffff811829d0-ffffffff81182a2c: __do_sys_getuid16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long int __do_sys_getuid16(const struct pt_regs *__unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff811b92c0)
Location: kernel/uid16.c:203
Inline: True
```
**Symbols:**

```
ffffffff811b92c0-ffffffff811b932c: __do_sys_getuid16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long int __do_sys_getuid16(const struct pt_regs *__unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff811fa810)
Location: kernel/uid16.c:203
Inline: True
```
**Symbols:**

```
ffffffff811fa810-ffffffff811fa87c: __do_sys_getuid16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long int __do_sys_getuid16(const struct pt_regs *__unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff8120fbb0)
Location: kernel/uid16.c:203
Inline: True
```
**Symbols:**

```
ffffffff8120fbb0-ffffffff8120fc1c: __do_sys_getuid16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long int __do_sys_getuid16(const struct pt_regs *__unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff81227180)
Location: kernel/uid16.c:203
Inline: True
```
**Symbols:**

```
ffffffff81227180-ffffffff812271ec: __do_sys_getuid16 (STB_LOCAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
