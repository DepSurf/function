# Function: <code>__set_selection_kernel</code>

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
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int __set_selection_kernel(struct tiocl_selection *v, struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/selection.c (0)
Location: drivers/tty/vt/selection.c:189
Inline: False
Direct callers:
  - drivers/tty/vt/selection.c:set_selection_kernel
```
**Symbols:**

```
ffffffff816949c0-ffffffff81694fea: __set_selection_kernel (STB_LOCAL)
ffffffff81695146-ffffffff81695161: __set_selection_kernel.cold (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int __set_selection_kernel(struct tiocl_selection *v, struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/selection.c (ffff800010868cc8)
Location: drivers/tty/vt/selection.c:189
Inline: False
Direct callers:
  - drivers/tty/vt/selection.c:set_selection_kernel
```
**Symbols:**

```
ffff800010868cc8-ffff80001086935c: __set_selection_kernel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __set_selection_kernel(struct tiocl_selection *v, struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/selection.c (c096dfa8)
Location: drivers/tty/vt/selection.c:189
Inline: False
Direct callers:
  - drivers/tty/vt/selection.c:set_selection_kernel
```
**Symbols:**

```
c096dfa8-c096e654: __set_selection_kernel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __set_selection_kernel(struct tiocl_selection *v, struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/selection.c (c000000000908850)
Location: drivers/tty/vt/selection.c:189
Inline: False
Direct callers:
  - drivers/tty/vt/selection.c:set_selection_kernel
```
**Symbols:**

```
c000000000908850-c000000000909160: __set_selection_kernel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __set_selection_kernel(struct tiocl_selection *v, struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/selection.c (ffffffe00053db06)
Location: drivers/tty/vt/selection.c:189
Inline: False
Direct callers:
  - drivers/tty/vt/selection.c:set_selection_kernel
```
**Symbols:**

```
ffffffe00053db06-ffffffe00053e17c: __set_selection_kernel (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int __set_selection_kernel(struct tiocl_selection *v, struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/selection.c (0)
Location: drivers/tty/vt/selection.c:189
Inline: False
Direct callers:
  - drivers/tty/vt/selection.c:set_selection_kernel
```
**Symbols:**

```
ffffffff8165a440-ffffffff8165aa6a: __set_selection_kernel (STB_LOCAL)
ffffffff8165abc6-ffffffff8165abe1: __set_selection_kernel.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int __set_selection_kernel(struct tiocl_selection *v, struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/selection.c (0)
Location: drivers/tty/vt/selection.c:189
Inline: False
Direct callers:
  - drivers/tty/vt/selection.c:set_selection_kernel
```
**Symbols:**

```
ffffffff8163a7c0-ffffffff8163adea: __set_selection_kernel (STB_LOCAL)
ffffffff8163af46-ffffffff8163af61: __set_selection_kernel.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int __set_selection_kernel(struct tiocl_selection *v, struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/selection.c (0)
Location: drivers/tty/vt/selection.c:189
Inline: False
Direct callers:
  - drivers/tty/vt/selection.c:set_selection_kernel
```
**Symbols:**

```
ffffffff81688800-ffffffff81688e2a: __set_selection_kernel (STB_LOCAL)
ffffffff81688f86-ffffffff81688fa1: __set_selection_kernel.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int __set_selection_kernel(struct tiocl_selection *v, struct tty_struct *tty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/selection.c (0)
Location: drivers/tty/vt/selection.c:189
Inline: False
Direct callers:
  - drivers/tty/vt/selection.c:set_selection_kernel
```
**Symbols:**

```
ffffffff816a2df0-ffffffff816a341a: __set_selection_kernel (STB_LOCAL)
ffffffff816a3576-ffffffff816a3591: __set_selection_kernel.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
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
