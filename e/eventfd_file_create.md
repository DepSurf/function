# Function: <code>eventfd_file_create</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct file *eventfd_file_create(unsigned int count, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/eventfd.c (ffffffff812591b0)
Location: fs/eventfd.c:391
Inline: True
Inline callers:
  - fs/eventfd.c:SyS_eventfd
Direct callers:
  - fs/eventfd.c:SyS_eventfd
```
**Symbols:**

```
ffffffff812591b0-ffffffff8125925c: eventfd_file_create.part.3 (STB_LOCAL)
ffffffff812598e0-ffffffff81259900: eventfd_file_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct file *eventfd_file_create(unsigned int count, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/eventfd.c (ffffffff812823a0)
Location: fs/eventfd.c:429
Inline: True
Inline callers:
  - fs/eventfd.c:SyS_eventfd
Direct callers:
  - fs/eventfd.c:SyS_eventfd
```
**Symbols:**

```
ffffffff81281b90-ffffffff81281c3c: eventfd_file_create.part.4 (STB_LOCAL)
ffffffff812822d0-ffffffff812822f0: eventfd_file_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct file *eventfd_file_create(unsigned int count, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/eventfd.c (ffffffff81295ec0)
Location: fs/eventfd.c:429
Inline: True
Inline callers:
  - fs/eventfd.c:SyS_eventfd
Direct callers:
  - fs/eventfd.c:SyS_eventfd
```
**Symbols:**

```
ffffffff812956c0-ffffffff8129576c: eventfd_file_create.part.6 (STB_LOCAL)
ffffffff81295df0-ffffffff81295e10: eventfd_file_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct file *eventfd_file_create(unsigned int count, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/eventfd.c (ffffffff812a3060)
Location: fs/eventfd.c:429
Inline: True
Inline callers:
  - fs/eventfd.c:SyS_eventfd
Direct callers:
  - fs/eventfd.c:SyS_eventfd
```
**Symbols:**

```
ffffffff812a2990-ffffffff812a2a3c: eventfd_file_create.part.6 (STB_LOCAL)
ffffffff812a2fa0-ffffffff812a2fc0: eventfd_file_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct file *eventfd_file_create(unsigned int count, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/eventfd.c (ffffffff812c63f0)
Location: fs/eventfd.c:429
Inline: True
Inline callers:
  - fs/eventfd.c:SyS_eventfd
Direct callers:
  - fs/eventfd.c:SyS_eventfd
```
**Symbols:**

```
ffffffff812c5c40-ffffffff812c5cec: eventfd_file_create.part.5 (STB_LOCAL)
ffffffff812c6330-ffffffff812c6350: eventfd_file_create (STB_GLOBAL)
```
</details>
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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
