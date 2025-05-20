# Function: <code>__do_sys_getegid</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __do_sys_getegid(const struct pt_regs *__unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810bfab0)
Location: kernel/sys.c:951
Inline: False
```
**Symbols:**

```
ffffffff810bfab0-ffffffff810bfadc: __do_sys_getegid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_sys_getegid(const struct pt_regs *__unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810bac70)
Location: kernel/sys.c:952
Inline: False
```
**Symbols:**

```
ffffffff810bac70-ffffffff810bac9c: __do_sys_getegid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_sys_getegid(const struct pt_regs *__unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810bc5a0)
Location: kernel/sys.c:969
Inline: False
```
**Symbols:**

```
ffffffff810bc5a0-ffffffff810bc5cc: __do_sys_getegid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __do_sys_getegid(const struct pt_regs *__unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810cef80)
Location: kernel/sys.c:978
Inline: False
```
**Symbols:**

```
ffffffff810cef80-ffffffff810cefac: __do_sys_getegid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __do_sys_getegid(const struct pt_regs *__unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810e7950)
Location: kernel/sys.c:985
Inline: False
```
**Symbols:**

```
ffffffff810e7950-ffffffff810e7984: __do_sys_getegid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_sys_getegid(const struct pt_regs *__unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff81108610)
Location: kernel/sys.c:986
Inline: False
```
**Symbols:**

```
ffffffff81108610-ffffffff81108644: __do_sys_getegid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __do_sys_getegid(const struct pt_regs *__unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff81114920)
Location: kernel/sys.c:1004
Inline: False
```
**Symbols:**

```
ffffffff81114920-ffffffff81114954: __do_sys_getegid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __do_sys_getegid(const struct pt_regs *__unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff8111e310)
Location: kernel/sys.c:1004
Inline: False
```
**Symbols:**

```
ffffffff8111e310-ffffffff8111e344: __do_sys_getegid (STB_LOCAL)
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
