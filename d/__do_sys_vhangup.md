# Function: <code>__do_sys_vhangup</code>

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
long int __do_sys_vhangup(const struct pt_regs *__unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8130d950)
Location: fs/open.c:1318
Inline: False
```
**Symbols:**

```
ffffffff8130d950-ffffffff8130d979: __do_sys_vhangup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_sys_vhangup(const struct pt_regs *__unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81319d80)
Location: fs/open.c:1333
Inline: False
```
**Symbols:**

```
ffffffff81319d80-ffffffff81319da9: __do_sys_vhangup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_sys_vhangup(const struct pt_regs *__unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8131fb90)
Location: fs/open.c:1355
Inline: False
```
**Symbols:**

```
ffffffff8131fb90-ffffffff8131fbb9: __do_sys_vhangup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __do_sys_vhangup(const struct pt_regs *__unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8136d130)
Location: fs/open.c:1373
Inline: False
```
**Symbols:**

```
ffffffff8136d130-ffffffff8136d159: __do_sys_vhangup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __do_sys_vhangup(const struct pt_regs *__unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff813eb4c0)
Location: fs/open.c:1440
Inline: False
```
**Symbols:**

```
ffffffff813eb4c0-ffffffff813eb4f5: __do_sys_vhangup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_sys_vhangup(const struct pt_regs *__unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff81473800)
Location: fs/open.c:1473
Inline: False
```
**Symbols:**

```
ffffffff81473800-ffffffff81473835: __do_sys_vhangup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __do_sys_vhangup(const struct pt_regs *__unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814a8000)
Location: fs/open.c:1569
Inline: False
```
**Symbols:**

```
ffffffff814a8000-ffffffff814a8035: __do_sys_vhangup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __do_sys_vhangup(const struct pt_regs *__unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff814d8c10)
Location: fs/open.c:1587
Inline: False
```
**Symbols:**

```
ffffffff814d8c10-ffffffff814d8c45: __do_sys_vhangup (STB_LOCAL)
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
