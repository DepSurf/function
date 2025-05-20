# Function: <code>__do_sys_getegid16</code>

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
long int __do_sys_getegid16(const struct pt_regs *__unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff81160640)
Location: kernel/uid16.c:218
Inline: True
```
**Symbols:**

```
ffffffff81160640-ffffffff8116069c: __do_sys_getegid16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long int __do_sys_getegid16(const struct pt_regs *__unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff8115c5d0)
Location: kernel/uid16.c:218
Inline: True
```
**Symbols:**

```
ffffffff8115c5d0-ffffffff8115c62c: __do_sys_getegid16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long int __do_sys_getegid16(const struct pt_regs *__unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff8115d7f0)
Location: kernel/uid16.c:218
Inline: True
```
**Symbols:**

```
ffffffff8115d7f0-ffffffff8115d84c: __do_sys_getegid16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long int __do_sys_getegid16(const struct pt_regs *__unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff81182af0)
Location: kernel/uid16.c:218
Inline: True
```
**Symbols:**

```
ffffffff81182af0-ffffffff81182b4c: __do_sys_getegid16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long int __do_sys_getegid16(const struct pt_regs *__unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff811b9410)
Location: kernel/uid16.c:218
Inline: True
```
**Symbols:**

```
ffffffff811b9410-ffffffff811b947c: __do_sys_getegid16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long int __do_sys_getegid16(const struct pt_regs *__unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff811fa990)
Location: kernel/uid16.c:218
Inline: True
```
**Symbols:**

```
ffffffff811fa990-ffffffff811fa9fc: __do_sys_getegid16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long int __do_sys_getegid16(const struct pt_regs *__unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff8120fd30)
Location: kernel/uid16.c:218
Inline: True
```
**Symbols:**

```
ffffffff8120fd30-ffffffff8120fd9c: __do_sys_getegid16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long int __do_sys_getegid16(const struct pt_regs *__unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/uid16.c (ffffffff81227300)
Location: kernel/uid16.c:218
Inline: True
```
**Symbols:**

```
ffffffff81227300-ffffffff8122736c: __do_sys_getegid16 (STB_LOCAL)
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
