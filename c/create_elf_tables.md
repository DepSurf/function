# Function: <code>create_elf_tables</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate ⚠️</summary>

```c
int create_elf_tables(struct linux_binprm *bprm, struct elf64_hdr *exec, long unsigned int load_addr, long unsigned int interp_load_addr);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81321be2)
Location: fs/binfmt_elf.c:151
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff8132210c)
Location: fs/binfmt_elf.c:151
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff81321be2-ffffffff8132210c: create_elf_tables (STB_LOCAL)
ffffffff8132210c-ffffffff81322631: create_elf_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate ⚠️</summary>

```c
int create_elf_tables(struct linux_binprm *bprm, struct elf64_hdr *exec, long unsigned int load_addr, long unsigned int interp_load_addr);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81356f70)
Location: fs/binfmt_elf.c:150
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff81357487)
Location: fs/binfmt_elf.c:150
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff81356f70-ffffffff81357487: create_elf_tables (STB_LOCAL)
ffffffff81357487-ffffffff813579b6: create_elf_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate ⚠️</summary>

```c
int create_elf_tables(struct linux_binprm *bprm, struct elf64_hdr *exec, long unsigned int load_addr, long unsigned int interp_load_addr);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff8136d3e7)
Location: fs/binfmt_elf.c:150
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff8136d977)
Location: fs/binfmt_elf.c:150
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff8136d3e7-ffffffff8136d918: create_elf_tables (STB_LOCAL)
ffffffff8136d977-ffffffff8136deb3: create_elf_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate ⚠️</summary>

```c
int create_elf_tables(struct linux_binprm *bprm, struct elf64_hdr *exec, long unsigned int load_addr, long unsigned int interp_load_addr);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff812b710d)
Location: fs/binfmt_elf.c:160
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff812ba114)
Location: fs/binfmt_elf.c:160
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff812b710d-ffffffff812b7663: create_elf_tables (STB_LOCAL)
ffffffff812ba114-ffffffff812ba6ab: create_elf_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate ⚠️</summary>

```c
int create_elf_tables(struct linux_binprm *bprm, struct elf64_hdr *exec, long unsigned int load_addr, long unsigned int interp_load_addr);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff812da9fb)
Location: fs/binfmt_elf.c:165
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff812dda43)
Location: fs/binfmt_elf.c:165
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff812da9fb-ffffffff812daf16: create_elf_tables (STB_LOCAL)
ffffffff812dda43-ffffffff812ddf8c: create_elf_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate ⚠️</summary>

```c
int create_elf_tables(struct linux_binprm *bprm, struct elf64_hdr *exec, long unsigned int load_addr, long unsigned int interp_load_addr);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff813035c0)
Location: fs/binfmt_elf.c:165
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff81306ca0)
Location: fs/binfmt_elf.c:165
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff813035c0-ffffffff81303f23: create_elf_tables (STB_LOCAL)
ffffffff81306ca0-ffffffff81307838: create_elf_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate ⚠️</summary>

```c
int create_elf_tables(struct linux_binprm *bprm, struct elf64_hdr *exec, long unsigned int load_addr, long unsigned int interp_load_addr);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81318cc0)
Location: fs/binfmt_elf.c:165
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff8131c410)
Location: fs/binfmt_elf.c:165
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff81318cc0-ffffffff81319680: create_elf_tables (STB_LOCAL)
ffffffff8131c410-ffffffff8131d043: create_elf_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate ⚠️</summary>

```c
int create_elf_tables(struct linux_binprm *bprm, struct elf64_hdr *exec, long unsigned int load_addr, long unsigned int interp_load_addr);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff813405f0)
Location: fs/binfmt_elf.c:164
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff81343cc0)
Location: fs/binfmt_elf.c:164
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff813405f0-ffffffff81340f94: create_elf_tables (STB_LOCAL)
ffffffff81343cc0-ffffffff813448a4: create_elf_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate ⚠️</summary>

```c
int create_elf_tables(struct linux_binprm *bprm, struct elf64_hdr *exec, long unsigned int load_addr, long unsigned int interp_load_addr);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81358b40)
Location: fs/binfmt_elf.c:164
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff8135c0b0)
Location: fs/binfmt_elf.c:164
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff81358b40-ffffffff8135943f: create_elf_tables (STB_LOCAL)
ffffffff8135c0b0-ffffffff8135cbd3: create_elf_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate ⚠️</summary>

```c
int create_elf_tables(struct linux_binprm *bprm, const struct elf64_hdr *exec, long unsigned int load_addr, long unsigned int interp_load_addr, long unsigned int e_entry);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff8139f050)
Location: fs/binfmt_elf.c:171
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff813a2280)
Location: fs/binfmt_elf.c:171
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff8139f050-ffffffff8139f570: create_elf_tables (STB_LOCAL)
ffffffff813a2280-ffffffff813a27b5: create_elf_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate ⚠️</summary>

```c
int create_elf_tables(struct linux_binprm *bprm, const struct elf64_hdr *exec, long unsigned int load_addr, long unsigned int interp_load_addr, long unsigned int e_entry);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff813b0680)
Location: fs/binfmt_elf.c:172
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff813b3190)
Location: fs/binfmt_elf.c:172
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff813b0680-ffffffff813b0bce: create_elf_tables (STB_LOCAL)
ffffffff813b3190-ffffffff813b3709: create_elf_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate ⚠️</summary>

```c
int create_elf_tables(struct linux_binprm *bprm, const struct elf64_hdr *exec, long unsigned int load_addr, long unsigned int interp_load_addr, long unsigned int e_entry);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff813b77c0)
Location: fs/binfmt_elf.c:172
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff813ba170)
Location: fs/binfmt_elf.c:172
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff813b77c0-ffffffff813b7d0d: create_elf_tables (STB_LOCAL)
ffffffff813ba170-ffffffff813ba6f3: create_elf_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate ⚠️</summary>

```c
int create_elf_tables(struct linux_binprm *bprm, const struct elf64_hdr *exec, long unsigned int load_addr, long unsigned int interp_load_addr, long unsigned int e_entry);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff814074a0)
Location: fs/binfmt_elf.c:172
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff81409e60)
Location: fs/binfmt_elf.c:172
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff814074a0-ffffffff81407a04: create_elf_tables (STB_LOCAL)
ffffffff81409e60-ffffffff8140a3f0: create_elf_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate ⚠️</summary>

```c
int create_elf_tables(struct linux_binprm *bprm, const struct elf64_hdr *exec, long unsigned int interp_load_addr, long unsigned int e_entry, long unsigned int phdr_addr);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff8147c1b0)
Location: fs/binfmt_elf.c:174
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff8147eb60)
Location: fs/binfmt_elf.c:174
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff8147c1b0-ffffffff8147c727: create_elf_tables (STB_LOCAL)
ffffffff8147eb60-ffffffff8147f10a: create_elf_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate ⚠️</summary>

```c
int create_elf_tables(struct linux_binprm *bprm, const struct elf64_hdr *exec, long unsigned int interp_load_addr, long unsigned int e_entry, long unsigned int phdr_addr);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff8150ee60)
Location: fs/binfmt_elf.c:174
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff81511ae0)
Location: fs/binfmt_elf.c:174
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff8150ee60-ffffffff8150f3d4: create_elf_tables (STB_LOCAL)
ffffffff81511ae0-ffffffff81512090: create_elf_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate ⚠️</summary>

```c
int create_elf_tables(struct linux_binprm *bprm, const struct elf64_hdr *exec, long unsigned int interp_load_addr, long unsigned int e_entry, long unsigned int phdr_addr);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81546700)
Location: fs/binfmt_elf.c:175
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff815494a0)
Location: fs/binfmt_elf.c:175
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff81546700-ffffffff81546cae: create_elf_tables (STB_LOCAL)
ffffffff815494a0-ffffffff81549a68: create_elf_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate ⚠️</summary>

```c
int create_elf_tables(struct linux_binprm *bprm, const struct elf64_hdr *exec, long unsigned int interp_load_addr, long unsigned int e_entry, long unsigned int phdr_addr);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff8157bb50)
Location: fs/binfmt_elf.c:156
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff8157e720)
Location: fs/binfmt_elf.c:156
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff8157bb50-ffffffff8157c0fe: create_elf_tables (STB_LOCAL)
ffffffff8157e720-ffffffff8157ece8: create_elf_tables (STB_LOCAL)
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
int create_elf_tables(struct linux_binprm *bprm, struct elf64_hdr *exec, long unsigned int load_addr, long unsigned int interp_load_addr);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffff80001041e308)
Location: fs/binfmt_elf.c:164
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffff800010421de8)
Location: fs/binfmt_elf.c:164
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffff80001041e308-ffff80001041ee00: create_elf_tables (STB_LOCAL)
ffff800010421de8-ffff8000104228b4: create_elf_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int create_elf_tables(struct linux_binprm *bprm, struct elf32_hdr *exec, long unsigned int load_addr, long unsigned int interp_load_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (c05e691c)
Location: fs/binfmt_elf.c:164
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
c05e691c-c05e6f84: create_elf_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate ⚠️</summary>

```c
int create_elf_tables(struct linux_binprm *bprm, struct elf64_hdr *exec, long unsigned int load_addr, long unsigned int interp_load_addr);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (c00000000052ceb0)
Location: fs/binfmt_elf.c:164
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (c000000000530ba0)
Location: fs/binfmt_elf.c:164
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
c00000000052ceb0-c00000000052d87c: create_elf_tables (STB_LOCAL)
c000000000530ba0-c000000000531560: create_elf_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int create_elf_tables(struct linux_binprm *bprm, struct elf64_hdr *exec, long unsigned int load_addr, long unsigned int interp_load_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffe0002c08d2)
Location: fs/binfmt_elf.c:164
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffe0002c08d2-ffffffe0002c0c20: create_elf_tables (STB_LOCAL)
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
int create_elf_tables(struct linux_binprm *bprm, struct elf64_hdr *exec, long unsigned int load_addr, long unsigned int interp_load_addr);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81351120)
Location: fs/binfmt_elf.c:164
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff81354690)
Location: fs/binfmt_elf.c:164
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff81351120-ffffffff81351a1f: create_elf_tables (STB_LOCAL)
ffffffff81354690-ffffffff813551b3: create_elf_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate ⚠️</summary>

```c
int create_elf_tables(struct linux_binprm *bprm, struct elf64_hdr *exec, long unsigned int load_addr, long unsigned int interp_load_addr);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81341e00)
Location: fs/binfmt_elf.c:164
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff81345350)
Location: fs/binfmt_elf.c:164
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff81341e00-ffffffff813426ff: create_elf_tables (STB_LOCAL)
ffffffff81345350-ffffffff81345e73: create_elf_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate ⚠️</summary>

```c
int create_elf_tables(struct linux_binprm *bprm, struct elf64_hdr *exec, long unsigned int load_addr, long unsigned int interp_load_addr);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff8134ebf0)
Location: fs/binfmt_elf.c:164
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff81352160)
Location: fs/binfmt_elf.c:164
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff8134ebf0-ffffffff8134f4ef: create_elf_tables (STB_LOCAL)
ffffffff81352160-ffffffff81352c83: create_elf_tables (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate ⚠️</summary>

```c
int create_elf_tables(struct linux_binprm *bprm, struct elf64_hdr *exec, long unsigned int load_addr, long unsigned int interp_load_addr);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81362170)
Location: fs/binfmt_elf.c:164
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff81365920)
Location: fs/binfmt_elf.c:164
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff81362170-ffffffff81362a6f: create_elf_tables (STB_LOCAL)
ffffffff81365920-ffffffff81366443: create_elf_tables (STB_LOCAL)
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
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int e_entry</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct elf64_hdr *exec</code> ➡️ <code>const struct elf64_hdr *exec</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int phdr_addr</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int load_addr</code>
</li>
<li>
<b>Param reordered. </b>
<code>bprm, exec, load_addr, interp_load_addr, e_entry</code> ➡️ <code>bprm, exec, interp_load_addr, e_entry, phdr_addr</code>
</li>
</ul>
</details>
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
<code>struct elf64_hdr *exec</code> ➡️ <code>struct elf32_hdr *exec</code>
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
