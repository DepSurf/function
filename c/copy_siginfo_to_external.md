# Function: <code>copy_siginfo_to_external</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff8139fdbf)
Location: include/linux/signal.h:27
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff813b11bd)
Location: include/linux/signal.h:27
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff813b82ad)
Location: include/linux/signal.h:27
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81407e1d)
Location: include/linux/signal.h:27
Inline: True
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
In fs/binfmt_elf.c (ffffffff8147cb72)
Location: include/linux/signal.h:27
Inline: True
Inline callers:
  - fs/binfmt_elf.c:fill_note_info
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void copy_siginfo_to_external(siginfo_t *to, const kernel_siginfo_t *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff8150ebc0)
Location: include/linux/signal.h:27
Inline: False
Direct callers:
  - fs/binfmt_elf.c:fill_note_info
```
**Symbols:**

```
ffffffff8150ebc0-ffffffff8150ec0e: copy_siginfo_to_external (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void copy_siginfo_to_external(siginfo_t *to, const kernel_siginfo_t *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81546380)
Location: include/linux/signal.h:27
Inline: False
Direct callers:
  - fs/binfmt_elf.c:fill_note_info
```
**Symbols:**

```
ffffffff81546380-ffffffff815463ce: copy_siginfo_to_external (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void copy_siginfo_to_external(siginfo_t *to, const kernel_siginfo_t *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff8157b7d0)
Location: include/linux/signal.h:28
Inline: False
Direct callers:
  - fs/binfmt_elf.c:fill_note_info
```
**Symbols:**

```
ffffffff8157b7d0-ffffffff8157b81e: copy_siginfo_to_external (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
