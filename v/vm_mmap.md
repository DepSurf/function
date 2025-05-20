# Function: <code>vm_mmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int vm_mmap(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flag, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811ac030)
Location: mm/util.c:281
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:elf_map
  - fs/binfmt_elf.c:elf_map
  - fs/binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff811ac030-ffffffff811ac068: vm_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int vm_mmap(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flag, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811c4ca0)
Location: mm/util.c:311
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:elf_map
  - fs/binfmt_elf.c:elf_map
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff811c4ca0-ffffffff811c4cd8: vm_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int vm_mmap(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flag, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811d4db0)
Location: mm/util.c:314
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:elf_map
  - fs/binfmt_elf.c:elf_map
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff811d4db0-ffffffff811d4de8: vm_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int vm_mmap(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flag, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811ddc00)
Location: mm/util.c:343
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:elf_map
  - fs/binfmt_elf.c:elf_map
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff811ddc00-ffffffff811ddc39: vm_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int vm_mmap(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flag, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff811f3680)
Location: mm/util.c:343
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:elf_map
  - fs/binfmt_elf.c:elf_map
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff811f3680-ffffffff811f36b9: vm_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int vm_mmap(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flag, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81214940)
Location: mm/util.c:367
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:elf_map
  - fs/binfmt_elf.c:elf_map
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:elf_map
  - fs/compat_binfmt_elf.c:elf_map
```
**Symbols:**

```
ffffffff81214940-ffffffff81214978: vm_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int vm_mmap(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flag, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81227820)
Location: mm/util.c:360
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:elf_map
  - fs/binfmt_elf.c:elf_map
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:elf_map
  - fs/compat_binfmt_elf.c:elf_map
```
**Symbols:**

```
ffffffff81227820-ffffffff81227858: vm_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int vm_mmap(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flag, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff812375c0)
Location: mm/util.c:401
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:elf_map
  - fs/binfmt_elf.c:elf_map
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:elf_map
  - fs/compat_binfmt_elf.c:elf_map
```
**Symbols:**

```
ffffffff812375c0-ffffffff812375f7: vm_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int vm_mmap(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flag, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81245810)
Location: mm/util.c:506
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:elf_map
  - fs/binfmt_elf.c:elf_map
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:elf_map
  - fs/compat_binfmt_elf.c:elf_map
```
**Symbols:**

```
ffffffff81245810-ffffffff81245847: vm_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int vm_mmap(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flag, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81273540)
Location: mm/util.c:516
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:elf_map
  - fs/binfmt_elf.c:elf_map
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff81273540-ffffffff81273577: vm_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int vm_mmap(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flag, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8127dd00)
Location: mm/util.c:529
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:elf_map
  - fs/binfmt_elf.c:elf_map
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff8127dd00-ffffffff8127dd37: vm_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int vm_mmap(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flag, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81282ec0)
Location: mm/util.c:529
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:elf_map
  - fs/binfmt_elf.c:elf_map
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff81282ec0-ffffffff81282ef7: vm_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int vm_mmap(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flag, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff812c0fb0)
Location: mm/util.c:529
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:elf_map
  - fs/binfmt_elf.c:elf_map
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff812c0fb0-ffffffff812c0fe7: vm_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int vm_mmap(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flag, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8131de10)
Location: mm/util.c:562
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:elf_map
  - fs/binfmt_elf.c:elf_map
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff8131de10-ffffffff8131de6b: vm_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int vm_mmap(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flag, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81391920)
Location: mm/util.c:530
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:elf_map
  - fs/binfmt_elf.c:elf_map
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff81391920-ffffffff8139197b: vm_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int vm_mmap(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flag, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff813c4300)
Location: mm/util.c:553
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:elf_map
  - fs/binfmt_elf.c:elf_map
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff813c4300-ffffffff813c435b: vm_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int vm_mmap(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flag, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff813eeeb0)
Location: mm/util.c:566
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:elf_load
  - fs/binfmt_elf.c:elf_load
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:elf_load
  - fs/compat_binfmt_elf.c:elf_load
```
**Symbols:**

```
ffffffff813eeeb0-ffffffff813eef0b: vm_mmap (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
long unsigned int vm_mmap(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flag, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffff8000102d8d50)
Location: mm/util.c:506
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:elf_map
  - fs/binfmt_elf.c:elf_map
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:elf_map
  - fs/compat_binfmt_elf.c:elf_map
```
**Symbols:**

```
ffff8000102d8d50-ffff8000102d8de4: vm_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int vm_mmap(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flag, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (c04fff98)
Location: mm/util.c:506
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:elf_map
  - fs/binfmt_elf.c:elf_map
  - fs/binfmt_elf_fdpic.c:elf_fdpic_map_file
  - fs/binfmt_elf_fdpic.c:elf_fdpic_map_file
  - fs/binfmt_elf_fdpic.c:elf_fdpic_map_file
  - fs/binfmt_flat.c:load_flat_file
```
**Symbols:**

```
c04fff98-c04ffffc: vm_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int vm_mmap(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flag, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (c0000000003988c0)
Location: mm/util.c:506
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:elf_map
  - fs/binfmt_elf.c:elf_map
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:elf_map
  - fs/compat_binfmt_elf.c:elf_map
```
**Symbols:**

```
c0000000003988c0-c000000000398908: vm_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int vm_mmap(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flag, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffe0001f3208)
Location: mm/util.c:506
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:elf_map
  - fs/binfmt_elf.c:elf_map
  - fs/binfmt_flat.c:load_flat_file
```
**Symbols:**

```
ffffffe0001f3208-ffffffe0001f3278: vm_mmap (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
long unsigned int vm_mmap(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flag, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8123de60)
Location: mm/util.c:506
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:elf_map
  - fs/binfmt_elf.c:elf_map
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:elf_map
  - fs/compat_binfmt_elf.c:elf_map
```
**Symbols:**

```
ffffffff8123de60-ffffffff8123de97: vm_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int vm_mmap(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flag, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81230e60)
Location: mm/util.c:506
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:elf_map
  - fs/binfmt_elf.c:elf_map
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:elf_map
  - fs/compat_binfmt_elf.c:elf_map
```
**Symbols:**

```
ffffffff81230e60-ffffffff81230e97: vm_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int vm_mmap(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flag, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8123bc00)
Location: mm/util.c:506
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:elf_map
  - fs/binfmt_elf.c:elf_map
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:elf_map
  - fs/compat_binfmt_elf.c:elf_map
```
**Symbols:**

```
ffffffff8123bc00-ffffffff8123bc37: vm_mmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int vm_mmap(struct file *file, long unsigned int addr, long unsigned int len, long unsigned int prot, long unsigned int flag, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8124b310)
Location: mm/util.c:506
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_library
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:elf_map
  - fs/binfmt_elf.c:elf_map
  - fs/compat_binfmt_elf.c:load_elf_library
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:elf_map
  - fs/compat_binfmt_elf.c:elf_map
```
**Symbols:**

```
ffffffff8124b310-ffffffff8124b347: vm_mmap (STB_GLOBAL)
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
