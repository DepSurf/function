# Function: <code>elf_map</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int elf_map(struct file *filep, long unsigned int addr, struct elf64_phdr *eppnt, int prot, int type, long unsigned int total_size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81267010)
Location: fs/binfmt_elf.c:337
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff8126a0c0)
Location: fs/binfmt_elf.c:337
Inline: True
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff81267010-ffffffff812670f1: elf_map (STB_LOCAL)
ffffffff8126a0c0-ffffffff8126a1a2: elf_map.isra.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int elf_map(struct file *filep, long unsigned int addr, struct elf64_phdr *eppnt, int prot, int type, long unsigned int total_size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/binfmt_elf.c (ffffffff812933c0)
Location: fs/binfmt_elf.c:336
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff81296090)
Location: fs/binfmt_elf.c:336
Inline: True
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff812933c0-ffffffff812934a5: elf_map (STB_LOCAL)
ffffffff81296090-ffffffff81296178: elf_map.isra.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int elf_map(struct file *filep, long unsigned int addr, struct elf64_phdr *eppnt, int prot, int type, long unsigned int total_size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/binfmt_elf.c (ffffffff812a8140)
Location: fs/binfmt_elf.c:336
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff812aac80)
Location: fs/binfmt_elf.c:336
Inline: True
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff812a8140-ffffffff812a8218: elf_map (STB_LOCAL)
ffffffff812aac80-ffffffff812aad5b: elf_map.isra.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int elf_map(struct file *filep, long unsigned int addr, struct elf64_phdr *eppnt, int prot, int type, long unsigned int total_size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/binfmt_elf.c (ffffffff812b4ae0)
Location: fs/binfmt_elf.c:344
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff812b7b10)
Location: fs/binfmt_elf.c:344
Inline: True
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff812b4ae0-ffffffff812b4bb2: elf_map (STB_LOCAL)
ffffffff812b7b10-ffffffff812b7be4: elf_map.isra.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int elf_map(struct file *filep, long unsigned int addr, struct elf64_phdr *eppnt, int prot, int type, long unsigned int total_size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/binfmt_elf.c (ffffffff812d8360)
Location: fs/binfmt_elf.c:349
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff812db400)
Location: fs/binfmt_elf.c:349
Inline: True
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff812d8360-ffffffff812d8432: elf_map (STB_LOCAL)
ffffffff812db400-ffffffff812db4d4: elf_map.isra.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate ⚠️</summary>

```c
long unsigned int elf_map(struct file *filep, long unsigned int addr, struct elf64_phdr *eppnt, int prot, int type, long unsigned int total_size);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81303430)
Location: fs/binfmt_elf.c:349
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff81306b10)
Location: fs/binfmt_elf.c:349
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff81303430-ffffffff81303545: elf_map (STB_LOCAL)
ffffffff81306b10-ffffffff81306c24: elf_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate ⚠️</summary>

```c
long unsigned int elf_map(struct file *filep, long unsigned int addr, struct elf64_phdr *eppnt, int prot, int type, long unsigned int total_size);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81318b30)
Location: fs/binfmt_elf.c:349
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff8131c280)
Location: fs/binfmt_elf.c:349
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff81318b30-ffffffff81318c45: elf_map (STB_LOCAL)
ffffffff8131c280-ffffffff8131c394: elf_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Transformation ⚠️</summary>

```c
long unsigned int elf_map(struct file *filep, long unsigned int addr, const struct elf64_phdr *eppnt, int prot, int type, long unsigned int total_size);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/binfmt_elf.c (0)
Location: fs/binfmt_elf.c:348
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (0)
Location: fs/binfmt_elf.c:348
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff81340480-ffffffff81340571: elf_map (STB_LOCAL)
ffffffff813436a8-ffffffff813436d2: elf_map.cold (STB_LOCAL)
ffffffff81343b60-ffffffff81343c50: elf_map (STB_LOCAL)
ffffffff81347027-ffffffff81347051: elf_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Transformation ⚠️</summary>

```c
long unsigned int elf_map(struct file *filep, long unsigned int addr, const struct elf64_phdr *eppnt, int prot, int type, long unsigned int total_size);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/binfmt_elf.c (0)
Location: fs/binfmt_elf.c:348
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (0)
Location: fs/binfmt_elf.c:348
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff813589d0-ffffffff81358ac1: elf_map (STB_LOCAL)
ffffffff8135bae6-ffffffff8135bb10: elf_map.cold (STB_LOCAL)
ffffffff8135bf50-ffffffff8135c040: elf_map (STB_LOCAL)
ffffffff8135f335-ffffffff8135f35f: elf_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int elf_map(struct file *filep, long unsigned int addr, const struct elf64_phdr *eppnt, int prot, int type, long unsigned int total_size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/binfmt_elf.c (0)
Location: fs/binfmt_elf.c:356
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (0)
Location: fs/binfmt_elf.c:356
Inline: True
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff8139f570-ffffffff8139f6a2: elf_map (STB_LOCAL)
ffffffff813a1a9a-ffffffff813a1ac4: elf_map.cold (STB_LOCAL)
ffffffff813a2160-ffffffff813a2277: elf_map.isra.0 (STB_LOCAL)
ffffffff813a4d87-ffffffff813a4db1: elf_map.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int elf_map(struct file *filep, long unsigned int addr, const struct elf64_phdr *eppnt, int prot, int type, long unsigned int total_size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/binfmt_elf.c (0)
Location: fs/binfmt_elf.c:360
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (0)
Location: fs/binfmt_elf.c:360
Inline: True
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff813b0bd0-ffffffff813b0d02: elf_map (STB_LOCAL)
ffffffff81beba4d-ffffffff81beba77: elf_map.cold (STB_LOCAL)
ffffffff813b3710-ffffffff813b3827: elf_map.isra.0 (STB_LOCAL)
ffffffff81beba77-ffffffff81bebaa1: elf_map.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int elf_map(struct file *filep, long unsigned int addr, const struct elf64_phdr *eppnt, int prot, int type, long unsigned int total_size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/binfmt_elf.c (0)
Location: fs/binfmt_elf.c:363
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (0)
Location: fs/binfmt_elf.c:363
Inline: True
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff813b7d10-ffffffff813b7dfe: elf_map (STB_LOCAL)
ffffffff81bddaaf-ffffffff81bddad9: elf_map.cold (STB_LOCAL)
ffffffff813ba700-ffffffff813ba7e7: elf_map.isra.0 (STB_LOCAL)
ffffffff81bddad9-ffffffff81bddb03: elf_map.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int elf_map(struct file *filep, long unsigned int addr, const struct elf64_phdr *eppnt, int prot, int type, long unsigned int total_size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81408490)
Location: fs/binfmt_elf.c:363
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff8140a600)
Location: fs/binfmt_elf.c:363
Inline: True
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff81408490-ffffffff81408567: elf_map (STB_LOCAL)
ffffffff8140a600-ffffffff8140a6d1: elf_map.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int elf_map(struct file *filep, long unsigned int addr, const struct elf64_phdr *eppnt, int prot, int type, long unsigned int total_size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/binfmt_elf.c (0)
Location: fs/binfmt_elf.c:365
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (0)
Location: fs/binfmt_elf.c:365
Inline: True
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff8147c010-ffffffff8147c116: elf_map (STB_LOCAL)
ffffffff81e79a7b-ffffffff81e79aa5: elf_map.cold (STB_LOCAL)
ffffffff8147f340-ffffffff8147f43e: elf_map.isra.0 (STB_LOCAL)
ffffffff81e79aa5-ffffffff81e79acf: elf_map.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int elf_map(struct file *filep, long unsigned int addr, const struct elf64_phdr *eppnt, int prot, int type, long unsigned int total_size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81510180)
Location: fs/binfmt_elf.c:365
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff815131f0)
Location: fs/binfmt_elf.c:365
Inline: True
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff81510180-ffffffff815102b0: elf_map (STB_LOCAL)
ffffffff815131f0-ffffffff81513318: elf_map.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int elf_map(struct file *filep, long unsigned int addr, const struct elf64_phdr *eppnt, int prot, int type, long unsigned int total_size);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81547ab0)
Location: fs/binfmt_elf.c:370
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff8154ac40)
Location: fs/binfmt_elf.c:370
Inline: True
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff81547ab0-ffffffff81547bde: elf_map (STB_LOCAL)
ffffffff8154ac40-ffffffff8154ad66: elf_map.isra.0 (STB_LOCAL)
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
In fs/binfmt_elf.c (ffffffff8157cd26)
Location: fs/binfmt_elf.c:356
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_load
```
```
In fs/compat_binfmt_elf.c (ffffffff8157fd6c)
Location: fs/binfmt_elf.c:356
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_load
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
long unsigned int elf_map(struct file *filep, long unsigned int addr, const struct elf64_phdr *eppnt, int prot, int type, long unsigned int total_size);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffff80001041dea8)
Location: fs/binfmt_elf.c:348
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffff800010421638)
Location: fs/binfmt_elf.c:348
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffff80001041dea8-ffff80001041dfe8: elf_map (STB_LOCAL)
ffff800010421638-ffff800010421778: elf_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int elf_map(struct file *filep, long unsigned int addr, const struct elf32_phdr *eppnt, int prot, int type, long unsigned int total_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (c05e679c)
Location: fs/binfmt_elf.c:348
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
c05e679c-c05e68a0: elf_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate ⚠️</summary>

```c
long unsigned int elf_map(struct file *filep, long unsigned int addr, const struct elf64_phdr *eppnt, int prot, int type, long unsigned int total_size);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (c00000000052c830)
Location: fs/binfmt_elf.c:348
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (c000000000530500)
Location: fs/binfmt_elf.c:348
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
c00000000052c830-c00000000052c9a8: elf_map (STB_LOCAL)
c000000000530500-c000000000530678: elf_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int elf_map(struct file *filep, long unsigned int addr, const struct elf64_phdr *eppnt, int prot, int type, long unsigned int total_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffe0002c0680)
Location: fs/binfmt_elf.c:348
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffe0002c0680-ffffffe0002c0760: elf_map (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Transformation ⚠️</summary>

```c
long unsigned int elf_map(struct file *filep, long unsigned int addr, const struct elf64_phdr *eppnt, int prot, int type, long unsigned int total_size);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/binfmt_elf.c (0)
Location: fs/binfmt_elf.c:348
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (0)
Location: fs/binfmt_elf.c:348
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff81350fb0-ffffffff813510a1: elf_map (STB_LOCAL)
ffffffff813540c6-ffffffff813540f0: elf_map.cold (STB_LOCAL)
ffffffff81354530-ffffffff81354620: elf_map (STB_LOCAL)
ffffffff81357915-ffffffff8135793f: elf_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Transformation ⚠️</summary>

```c
long unsigned int elf_map(struct file *filep, long unsigned int addr, const struct elf64_phdr *eppnt, int prot, int type, long unsigned int total_size);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/binfmt_elf.c (0)
Location: fs/binfmt_elf.c:348
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (0)
Location: fs/binfmt_elf.c:348
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff81341c90-ffffffff81341d81: elf_map (STB_LOCAL)
ffffffff81344d86-ffffffff81344db0: elf_map.cold (STB_LOCAL)
ffffffff813451f0-ffffffff813452e0: elf_map (STB_LOCAL)
ffffffff813485c5-ffffffff813485ef: elf_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Transformation ⚠️</summary>

```c
long unsigned int elf_map(struct file *filep, long unsigned int addr, const struct elf64_phdr *eppnt, int prot, int type, long unsigned int total_size);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/binfmt_elf.c (0)
Location: fs/binfmt_elf.c:348
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (0)
Location: fs/binfmt_elf.c:348
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff8134ea80-ffffffff8134eb71: elf_map (STB_LOCAL)
ffffffff81351b96-ffffffff81351bc0: elf_map.cold (STB_LOCAL)
ffffffff81352000-ffffffff813520f0: elf_map (STB_LOCAL)
ffffffff813553e5-ffffffff8135540f: elf_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Transformation ⚠️</summary>

```c
long unsigned int elf_map(struct file *filep, long unsigned int addr, const struct elf64_phdr *eppnt, int prot, int type, long unsigned int total_size);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/binfmt_elf.c (0)
Location: fs/binfmt_elf.c:348
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (0)
Location: fs/binfmt_elf.c:348
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff81362000-ffffffff813620f1: elf_map (STB_LOCAL)
ffffffff81365131-ffffffff8136515b: elf_map.cold (STB_LOCAL)
ffffffff813657c0-ffffffff813658b0: elf_map (STB_LOCAL)
ffffffff813689c0-ffffffff813689ea: elf_map.cold (STB_LOCAL)
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
<code>struct elf64_phdr *eppnt</code> ➡️ <code>const struct elf64_phdr *eppnt</code>
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
<code>const struct elf64_phdr *eppnt</code> ➡️ <code>const struct elf32_phdr *eppnt</code>
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
