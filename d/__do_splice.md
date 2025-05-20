# Function: <code>__do_splice</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_splice(struct file *in, loff_t *off_in, struct file *out, loff_t *off_out, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8135eec0)
Location: fs/splice.c:1111
Inline: False
Direct callers:
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__x64_sys_splice
```
**Symbols:**

```
ffffffff8135eec0-ffffffff8135f01e: __do_splice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_splice(struct file *in, loff_t *off_in, struct file *out, loff_t *off_out, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff813657c0)
Location: fs/splice.c:1116
Inline: False
Direct callers:
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__x64_sys_splice
```
**Symbols:**

```
ffffffff813657c0-ffffffff8136591e: __do_splice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __do_splice(struct file *in, loff_t *off_in, struct file *out, loff_t *off_out, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff813b40b0)
Location: fs/splice.c:1118
Inline: False
Direct callers:
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__x64_sys_splice
```
**Symbols:**

```
ffffffff813b40b0-ffffffff813b420e: __do_splice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __do_splice(struct file *in, loff_t *off_in, struct file *out, loff_t *off_out, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81439400)
Location: fs/splice.c:1114
Inline: False
Direct callers:
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__x64_sys_splice
```
**Symbols:**

```
ffffffff81439400-ffffffff8143957e: __do_splice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_splice(struct file *in, loff_t *off_in, struct file *out, loff_t *off_out, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff814c7700)
Location: fs/splice.c:1113
Inline: False
Direct callers:
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__x64_sys_splice
```
**Symbols:**

```
ffffffff814c7700-ffffffff814c787e: __do_splice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __do_splice(struct file *in, loff_t *off_in, struct file *out, loff_t *off_out, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff814fd6a0)
Location: fs/splice.c:1339
Inline: False
Direct callers:
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__x64_sys_splice
```
**Symbols:**

```
ffffffff814fd6a0-ffffffff814fd8c1: __do_splice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t __do_splice(struct file *in, loff_t *off_in, struct file *out, loff_t *off_out, size_t len, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff815322a0)
Location: fs/splice.c:1402
Inline: False
Direct callers:
  - fs/splice.c:__ia32_sys_splice
  - fs/splice.c:__x64_sys_splice
```
**Symbols:**

```
ffffffff815322a0-ffffffff815324c1: __do_splice (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>long int</code> ➡️ <code>ssize_t</code>
</li>
</ul>
</details>
</li>
</ul>
