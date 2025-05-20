# Function: <code>arch_kexec_locate_mem_hole</code>

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
int arch_kexec_locate_mem_hole(struct kexec_buf *kbuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81169150)
Location: kernel/kexec_file.c:652
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_add_buffer
```
**Symbols:**

```
ffffffff81169150-ffffffff811691c2: arch_kexec_locate_mem_hole (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int arch_kexec_locate_mem_hole(struct kexec_buf *kbuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81169e20)
Location: kernel/kexec_file.c:652
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_add_buffer
```
**Symbols:**

```
ffffffff81169e20-ffffffff81169e92: arch_kexec_locate_mem_hole (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int arch_kexec_locate_mem_hole(struct kexec_buf *kbuf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8118f9b0)
Location: kernel/kexec_file.c:652
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_add_buffer
```
**Symbols:**

```
ffffffff8118f9b0-ffffffff8118fa22: arch_kexec_locate_mem_hole (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff811bf21c)
Location: include/linux/kexec.h:234
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_add_buffer
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff812014bc)
Location: include/linux/kexec.h:235
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_add_buffer
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8121688c)
Location: include/linux/kexec.h:227
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_add_buffer
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8122e76c)
Location: include/linux/kexec.h:224
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_add_buffer
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
</ul>
