# Function: <code>load_elf_phdrs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate ⚠️</summary>

```c
struct elf64_phdr *load_elf_phdrs(struct elf64_hdr *elf_ex, struct file *elf_file);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81266d70)
Location: fs/binfmt_elf.c:400
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff812699b0)
Location: fs/binfmt_elf.c:400
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff81266d70-ffffffff81266df6: load_elf_phdrs (STB_LOCAL)
ffffffff812699b0-ffffffff81269a3a: load_elf_phdrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate ⚠️</summary>

```c
struct elf64_phdr *load_elf_phdrs(struct elf64_hdr *elf_ex, struct file *elf_file);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81293110)
Location: fs/binfmt_elf.c:399
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff81295cb0)
Location: fs/binfmt_elf.c:399
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff81293110-ffffffff81293195: load_elf_phdrs (STB_LOCAL)
ffffffff81295cb0-ffffffff81295d38: load_elf_phdrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate ⚠️</summary>

```c
struct elf64_phdr *load_elf_phdrs(struct elf64_hdr *elf_ex, struct file *elf_file);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff812a7e90)
Location: fs/binfmt_elf.c:399
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff812aa900)
Location: fs/binfmt_elf.c:399
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff812a7e90-ffffffff812a7f15: load_elf_phdrs (STB_LOCAL)
ffffffff812aa900-ffffffff812aa988: load_elf_phdrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate ⚠️</summary>

```c
struct elf64_phdr *load_elf_phdrs(struct elf64_hdr *elf_ex, struct file *elf_file);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff812b4820)
Location: fs/binfmt_elf.c:407
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff812b77c0)
Location: fs/binfmt_elf.c:407
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff812b4820-ffffffff812b48a3: load_elf_phdrs (STB_LOCAL)
ffffffff812b77c0-ffffffff812b7843: load_elf_phdrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
struct elf64_phdr *load_elf_phdrs(struct elf64_hdr *elf_ex, struct file *elf_file);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/binfmt_elf.c (ffffffff812d8060)
Location: fs/binfmt_elf.c:412
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff812db350)
Location: fs/binfmt_elf.c:412
Inline: True
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff812d8060-ffffffff812d810f: load_elf_phdrs (STB_LOCAL)
ffffffff812db350-ffffffff812db3fb: load_elf_phdrs.isra.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate ⚠️</summary>

```c
struct elf64_phdr *load_elf_phdrs(struct elf64_hdr *elf_ex, struct file *elf_file);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81303130)
Location: fs/binfmt_elf.c:417
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff81306810)
Location: fs/binfmt_elf.c:417
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff81303130-ffffffff813031df: load_elf_phdrs (STB_LOCAL)
ffffffff81306810-ffffffff813068be: load_elf_phdrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate ⚠️</summary>

```c
struct elf64_phdr *load_elf_phdrs(struct elf64_hdr *elf_ex, struct file *elf_file);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81318830)
Location: fs/binfmt_elf.c:417
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff8131bf80)
Location: fs/binfmt_elf.c:417
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff81318830-ffffffff813188df: load_elf_phdrs (STB_LOCAL)
ffffffff8131bf80-ffffffff8131c02e: load_elf_phdrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate ⚠️</summary>

```c
struct elf64_phdr *load_elf_phdrs(const struct elf64_hdr *elf_ex, struct file *elf_file);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81340180)
Location: fs/binfmt_elf.c:416
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff81343860)
Location: fs/binfmt_elf.c:416
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff81340180-ffffffff81340228: load_elf_phdrs (STB_LOCAL)
ffffffff81343860-ffffffff81343907: load_elf_phdrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate ⚠️</summary>

```c
struct elf64_phdr *load_elf_phdrs(const struct elf64_hdr *elf_ex, struct file *elf_file);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff813586d0)
Location: fs/binfmt_elf.c:416
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff8135bc50)
Location: fs/binfmt_elf.c:416
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff813586d0-ffffffff81358778: load_elf_phdrs (STB_LOCAL)
ffffffff8135bc50-ffffffff8135bcf7: load_elf_phdrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate ⚠️</summary>

```c
struct elf64_phdr *load_elf_phdrs(const struct elf64_hdr *elf_ex, struct file *elf_file);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff8139f930)
Location: fs/binfmt_elf.c:433
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff813a27c0)
Location: fs/binfmt_elf.c:433
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff8139f930-ffffffff8139f9e4: load_elf_phdrs (STB_LOCAL)
ffffffff813a27c0-ffffffff813a2874: load_elf_phdrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate ⚠️</summary>

```c
struct elf64_phdr *load_elf_phdrs(const struct elf64_hdr *elf_ex, struct file *elf_file);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff813b0d10)
Location: fs/binfmt_elf.c:457
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff813b3830)
Location: fs/binfmt_elf.c:457
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff813b0d10-ffffffff813b0dc4: load_elf_phdrs (STB_LOCAL)
ffffffff813b3830-ffffffff813b38e4: load_elf_phdrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate ⚠️</summary>

```c
struct elf64_phdr *load_elf_phdrs(const struct elf64_hdr *elf_ex, struct file *elf_file);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff813b7e00)
Location: fs/binfmt_elf.c:460
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff813ba7f0)
Location: fs/binfmt_elf.c:460
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff813b7e00-ffffffff813b7eb4: load_elf_phdrs (STB_LOCAL)
ffffffff813ba7f0-ffffffff813ba8a4: load_elf_phdrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate ⚠️</summary>

```c
struct elf64_phdr *load_elf_phdrs(const struct elf64_hdr *elf_ex, struct file *elf_file);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81408570)
Location: fs/binfmt_elf.c:460
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff8140a6e0)
Location: fs/binfmt_elf.c:460
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff81408570-ffffffff81408624: load_elf_phdrs (STB_LOCAL)
ffffffff8140a6e0-ffffffff8140a794: load_elf_phdrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate ⚠️</summary>

```c
struct elf64_phdr *load_elf_phdrs(const struct elf64_hdr *elf_ex, struct file *elf_file);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff8147d1b0)
Location: fs/binfmt_elf.c:461
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff8147f440)
Location: fs/binfmt_elf.c:461
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff8147d1b0-ffffffff8147d270: load_elf_phdrs (STB_LOCAL)
ffffffff8147f440-ffffffff8147f500: load_elf_phdrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate ⚠️</summary>

```c
struct elf64_phdr *load_elf_phdrs(const struct elf64_hdr *elf_ex, struct file *elf_file);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff8150f610)
Location: fs/binfmt_elf.c:461
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff81512310)
Location: fs/binfmt_elf.c:461
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff8150f610-ffffffff8150f6d0: load_elf_phdrs (STB_LOCAL)
ffffffff81512310-ffffffff815123d0: load_elf_phdrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate ⚠️</summary>

```c
struct elf64_phdr *load_elf_phdrs(const struct elf64_hdr *elf_ex, struct file *elf_file);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81546f40)
Location: fs/binfmt_elf.c:466
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff81549d50)
Location: fs/binfmt_elf.c:466
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff81546f40-ffffffff81547000: load_elf_phdrs (STB_LOCAL)
ffffffff81549d50-ffffffff81549e10: load_elf_phdrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate ⚠️</summary>

```c
struct elf64_phdr *load_elf_phdrs(const struct elf64_hdr *elf_ex, struct file *elf_file);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff8157c360)
Location: fs/binfmt_elf.c:506
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff8157efd0)
Location: fs/binfmt_elf.c:506
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff8157c360-ffffffff8157c420: load_elf_phdrs (STB_LOCAL)
ffffffff8157efd0-ffffffff8157f090: load_elf_phdrs (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate ⚠️</summary>

```c
struct elf64_phdr *load_elf_phdrs(const struct elf64_hdr *elf_ex, struct file *elf_file);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffff80001041ddc0)
Location: fs/binfmt_elf.c:416
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffff800010421558)
Location: fs/binfmt_elf.c:416
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffff80001041ddc0-ffff80001041dea4: load_elf_phdrs (STB_LOCAL)
ffff800010421558-ffff800010421634: load_elf_phdrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct elf32_phdr *load_elf_phdrs(const struct elf32_hdr *elf_ex, struct file *elf_file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (c05e6664)
Location: fs/binfmt_elf.c:416
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
c05e6664-c05e6730: load_elf_phdrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate ⚠️</summary>

```c
struct elf64_phdr *load_elf_phdrs(const struct elf64_hdr *elf_ex, struct file *elf_file);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (c00000000052c720)
Location: fs/binfmt_elf.c:416
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (c0000000005303e0)
Location: fs/binfmt_elf.c:416
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
c00000000052c720-c00000000052c82c: load_elf_phdrs (STB_LOCAL)
c0000000005303e0-c0000000005304fc: load_elf_phdrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct elf64_phdr *load_elf_phdrs(const struct elf64_hdr *elf_ex, struct file *elf_file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffe0002c05aa)
Location: fs/binfmt_elf.c:416
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffe0002c05aa-ffffffe0002c0654: load_elf_phdrs (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate ⚠️</summary>

```c
struct elf64_phdr *load_elf_phdrs(const struct elf64_hdr *elf_ex, struct file *elf_file);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81350cb0)
Location: fs/binfmt_elf.c:416
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff81354230)
Location: fs/binfmt_elf.c:416
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff81350cb0-ffffffff81350d58: load_elf_phdrs (STB_LOCAL)
ffffffff81354230-ffffffff813542d7: load_elf_phdrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate ⚠️</summary>

```c
struct elf64_phdr *load_elf_phdrs(const struct elf64_hdr *elf_ex, struct file *elf_file);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81341990)
Location: fs/binfmt_elf.c:416
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff81344ef0)
Location: fs/binfmt_elf.c:416
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff81341990-ffffffff81341a38: load_elf_phdrs (STB_LOCAL)
ffffffff81344ef0-ffffffff81344f97: load_elf_phdrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate ⚠️</summary>

```c
struct elf64_phdr *load_elf_phdrs(const struct elf64_hdr *elf_ex, struct file *elf_file);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff8134e780)
Location: fs/binfmt_elf.c:416
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff81351d00)
Location: fs/binfmt_elf.c:416
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff8134e780-ffffffff8134e828: load_elf_phdrs (STB_LOCAL)
ffffffff81351d00-ffffffff81351da7: load_elf_phdrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate ⚠️</summary>

```c
struct elf64_phdr *load_elf_phdrs(const struct elf64_hdr *elf_ex, struct file *elf_file);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81361d00)
Location: fs/binfmt_elf.c:416
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff813654c0)
Location: fs/binfmt_elf.c:416
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff81361d00-ffffffff81361da8: load_elf_phdrs (STB_LOCAL)
ffffffff813654c0-ffffffff81365567: load_elf_phdrs (STB_LOCAL)
```
</details>
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
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct elf64_hdr *elf_ex</code> ➡️ <code>const struct elf64_hdr *elf_ex</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>armhf</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const struct elf64_hdr *elf_ex</code> ➡️ <code>const struct elf32_hdr *elf_ex</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct elf64_phdr *</code> ➡️ <code>struct elf32_phdr *</code>
</li>
</ul>
</details>
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
