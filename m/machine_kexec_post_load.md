# Function: <code>machine_kexec_post_load</code>

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
int machine_kexec_post_load(struct kimage *image);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8116aeb0)
Location: kernel/kexec_core.c:593
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__do_sys_kexec_file_load
```
**Symbols:**

```
ffffffff8116aeb0-ffffffff8116aebd: machine_kexec_post_load (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int machine_kexec_post_load(struct kimage *image);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff811675f0)
Location: kernel/kexec_core.c:592
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__do_sys_kexec_file_load
```
**Symbols:**

```
ffffffff811675f0-ffffffff811675fd: machine_kexec_post_load (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int machine_kexec_post_load(struct kimage *image);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff81168380)
Location: kernel/kexec_core.c:593
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__do_sys_kexec_file_load
```
**Symbols:**

```
ffffffff81168380-ffffffff8116838d: machine_kexec_post_load (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int machine_kexec_post_load(struct kimage *image);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8118e0c0)
Location: kernel/kexec_core.c:594
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__do_sys_kexec_file_load
```
**Symbols:**

```
ffffffff8118e0c0-ffffffff8118e0cd: machine_kexec_post_load (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int machine_kexec_post_load(struct kimage *image);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff811bd610)
Location: kernel/kexec_core.c:594
Inline: False
Direct callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec_file.c:__do_sys_kexec_file_load
```
**Symbols:**

```
ffffffff811bd610-ffffffff811bd621: machine_kexec_post_load (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec.c (0)
Location: include/linux/kexec.h:394
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: include/linux/kexec.h:394
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec.c (0)
Location: include/linux/kexec.h:386
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: include/linux/kexec.h:386
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec.c (0)
Location: include/linux/kexec.h:378
Inline: True
```
```
In kernel/kexec_file.c (0)
Location: include/linux/kexec.h:378
Inline: True
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
</ul>
