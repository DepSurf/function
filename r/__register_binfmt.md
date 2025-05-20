# Function: <code>__register_binfmt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void __register_binfmt(struct linux_binfmt *fmt, int insert);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff81212930)
Location: fs/exec.c:76
Inline: True
Direct callers:
  - fs/binfmt_script.c:init_script_binfmt
  - fs/binfmt_elf.c:init_elf_binfmt
  - fs/compat_binfmt_elf.c:init_compat_elf_binfmt
```
**Symbols:**

```
ffffffff81212930-ffffffff812129bb: __register_binfmt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void __register_binfmt(struct linux_binfmt *fmt, int insert);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff81239410)
Location: fs/exec.c:77
Inline: True
Direct callers:
  - fs/binfmt_script.c:init_script_binfmt
  - fs/binfmt_elf.c:init_elf_binfmt
  - fs/compat_binfmt_elf.c:init_compat_elf_binfmt
```
**Symbols:**

```
ffffffff81239410-ffffffff8123949b: __register_binfmt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __register_binfmt(struct linux_binfmt *fmt, int insert);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8124c150)
Location: fs/exec.c:77
Inline: True
Direct callers:
  - fs/binfmt_script.c:init_script_binfmt
  - fs/binfmt_elf.c:init_elf_binfmt
  - fs/compat_binfmt_elf.c:init_compat_elf_binfmt
```
**Symbols:**

```
ffffffff8124c150-ffffffff8124c1db: __register_binfmt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __register_binfmt(struct linux_binfmt *fmt, int insert);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff81258260)
Location: fs/exec.c:82
Inline: True
Direct callers:
  - fs/binfmt_script.c:init_script_binfmt
  - fs/binfmt_elf.c:init_elf_binfmt
  - fs/compat_binfmt_elf.c:init_compat_elf_binfmt
```
**Symbols:**

```
ffffffff81258260-ffffffff812582e5: __register_binfmt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __register_binfmt(struct linux_binfmt *fmt, int insert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff81279b20)
Location: fs/exec.c:82
Inline: False
Direct callers:
  - fs/binfmt_script.c:init_script_binfmt
  - fs/binfmt_elf.c:init_elf_binfmt
  - fs/compat_binfmt_elf.c:init_compat_elf_binfmt
```
**Symbols:**

```
ffffffff81279b20-ffffffff81279b9c: __register_binfmt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __register_binfmt(struct linux_binfmt *fmt, int insert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812a0700)
Location: fs/exec.c:82
Inline: False
Direct callers:
  - fs/binfmt_script.c:init_script_binfmt
  - fs/binfmt_elf.c:init_elf_binfmt
  - fs/compat_binfmt_elf.c:init_compat_elf_binfmt
```
**Symbols:**

```
ffffffff812a0700-ffffffff812a077c: __register_binfmt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __register_binfmt(struct linux_binfmt *fmt, int insert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812b56e0)
Location: fs/exec.c:82
Inline: False
Direct callers:
  - fs/binfmt_script.c:init_script_binfmt
  - fs/binfmt_elf.c:init_elf_binfmt
  - fs/compat_binfmt_elf.c:init_compat_elf_binfmt
```
**Symbols:**

```
ffffffff812b56e0-ffffffff812b575c: __register_binfmt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __register_binfmt(struct linux_binfmt *fmt, int insert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/exec.c (0)
Location: fs/exec.c:83
Inline: False
Direct callers:
  - fs/binfmt_script.c:init_script_binfmt
  - fs/binfmt_elf.c:init_elf_binfmt
  - fs/compat_binfmt_elf.c:init_compat_elf_binfmt
```
**Symbols:**

```
ffffffff812d52f8-ffffffff812d530b: __register_binfmt.cold (STB_LOCAL)
ffffffff812d2490-ffffffff812d250c: __register_binfmt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __register_binfmt(struct linux_binfmt *fmt, int insert);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812e4a80)
Location: fs/exec.c:83
Inline: True
Direct callers:
  - fs/binfmt_script.c:init_script_binfmt
  - fs/binfmt_elf.c:init_elf_binfmt
  - fs/compat_binfmt_elf.c:init_compat_elf_binfmt
```
**Symbols:**

```
ffffffff812e4a80-ffffffff812e4afc: __register_binfmt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __register_binfmt(struct linux_binfmt *fmt, int insert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8131b3d0)
Location: fs/exec.c:82
Inline: False
Direct callers:
  - fs/binfmt_script.c:init_script_binfmt
  - fs/binfmt_elf.c:init_elf_binfmt
  - fs/compat_binfmt_elf.c:init_compat_elf_binfmt
```
**Symbols:**

```
ffffffff8131b3d0-ffffffff8131b44c: __register_binfmt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __register_binfmt(struct linux_binfmt *fmt, int insert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff81326a00)
Location: fs/exec.c:85
Inline: False
Direct callers:
  - fs/binfmt_script.c:init_script_binfmt
  - fs/binfmt_elf.c:init_elf_binfmt
  - fs/compat_binfmt_elf.c:init_compat_elf_binfmt
```
**Symbols:**

```
ffffffff81326a00-ffffffff81326a7c: __register_binfmt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __register_binfmt(struct linux_binfmt *fmt, int insert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8132cae0)
Location: fs/exec.c:85
Inline: False
Direct callers:
  - fs/binfmt_script.c:init_script_binfmt
  - fs/binfmt_elf.c:init_elf_binfmt
  - fs/compat_binfmt_elf.c:init_compat_elf_binfmt
```
**Symbols:**

```
ffffffff8132cae0-ffffffff8132cb5c: __register_binfmt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __register_binfmt(struct linux_binfmt *fmt, int insert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8137a200)
Location: fs/exec.c:85
Inline: False
Direct callers:
  - fs/binfmt_script.c:init_script_binfmt
  - fs/binfmt_elf.c:init_elf_binfmt
  - fs/compat_binfmt_elf.c:init_compat_elf_binfmt
```
**Symbols:**

```
ffffffff8137a200-ffffffff8137a274: __register_binfmt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __register_binfmt(struct linux_binfmt *fmt, int insert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff813f99b0)
Location: fs/exec.c:85
Inline: False
Direct callers:
  - fs/binfmt_script.c:init_script_binfmt
  - fs/binfmt_elf.c:init_elf_binfmt
  - fs/compat_binfmt_elf.c:init_compat_elf_binfmt
```
**Symbols:**

```
ffffffff813f99b0-ffffffff813f9a29: __register_binfmt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __register_binfmt(struct linux_binfmt *fmt, int insert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff81483210)
Location: fs/exec.c:85
Inline: False
Direct callers:
  - fs/binfmt_script.c:init_script_binfmt
  - fs/binfmt_elf.c:init_elf_binfmt
  - fs/compat_binfmt_elf.c:init_compat_elf_binfmt
```
**Symbols:**

```
ffffffff81483210-ffffffff81483289: __register_binfmt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __register_binfmt(struct linux_binfmt *fmt, int insert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff814b7e30)
Location: fs/exec.c:86
Inline: False
Direct callers:
  - fs/binfmt_script.c:init_script_binfmt
  - fs/binfmt_elf.c:init_elf_binfmt
  - fs/compat_binfmt_elf.c:init_compat_elf_binfmt
```
**Symbols:**

```
ffffffff814b7e30-ffffffff814b7ea9: __register_binfmt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __register_binfmt(struct linux_binfmt *fmt, int insert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff814ea330)
Location: fs/exec.c:87
Inline: False
Direct callers:
  - fs/binfmt_script.c:init_script_binfmt
  - fs/binfmt_elf.c:init_elf_binfmt
  - fs/compat_binfmt_elf.c:init_compat_elf_binfmt
```
**Symbols:**

```
ffffffff814ea330-ffffffff814ea3a9: __register_binfmt (STB_GLOBAL)
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
void __register_binfmt(struct linux_binfmt *fmt, int insert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffff80001038c678)
Location: fs/exec.c:83
Inline: False
Direct callers:
  - fs/binfmt_script.c:init_script_binfmt
  - fs/binfmt_elf.c:init_elf_binfmt
  - fs/compat_binfmt_elf.c:init_compat_elf_binfmt
```
**Symbols:**

```
ffff80001038c678-ffff80001038c74c: __register_binfmt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __register_binfmt(struct linux_binfmt *fmt, int insert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (c0573718)
Location: fs/exec.c:83
Inline: False
Direct callers:
  - fs/binfmt_script.c:init_script_binfmt
  - fs/binfmt_elf.c:init_elf_binfmt
  - fs/binfmt_elf_fdpic.c:init_elf_fdpic_binfmt
  - fs/binfmt_flat.c:init_flat_binfmt
```
**Symbols:**

```
c0573718-c05737cc: __register_binfmt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __register_binfmt(struct linux_binfmt *fmt, int insert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (c000000000482fe0)
Location: fs/exec.c:83
Inline: False
Direct callers:
  - fs/binfmt_script.c:init_script_binfmt
  - fs/binfmt_elf.c:init_elf_binfmt
  - fs/compat_binfmt_elf.c:init_compat_elf_binfmt
```
**Symbols:**

```
c000000000482fe0-c0000000004830d8: __register_binfmt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __register_binfmt(struct linux_binfmt *fmt, int insert);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffe00025cf5c)
Location: fs/exec.c:83
Inline: False
Direct callers:
  - fs/binfmt_script.c:init_script_binfmt
  - fs/binfmt_elf.c:init_elf_binfmt
  - fs/binfmt_flat.c:init_flat_binfmt
```
**Symbols:**

```
ffffffe00025cf5c-ffffffe00025cfcc: __register_binfmt (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void __register_binfmt(struct linux_binfmt *fmt, int insert);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812dd060)
Location: fs/exec.c:83
Inline: True
Direct callers:
  - fs/binfmt_script.c:init_script_binfmt
  - fs/binfmt_elf.c:init_elf_binfmt
  - fs/compat_binfmt_elf.c:init_compat_elf_binfmt
```
**Symbols:**

```
ffffffff812dd060-ffffffff812dd0dc: __register_binfmt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __register_binfmt(struct linux_binfmt *fmt, int insert);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812cdce0)
Location: fs/exec.c:83
Inline: True
Direct callers:
  - fs/binfmt_script.c:init_script_binfmt
  - fs/binfmt_elf.c:init_elf_binfmt
  - fs/compat_binfmt_elf.c:init_compat_elf_binfmt
```
**Symbols:**

```
ffffffff812cdce0-ffffffff812cdd5c: __register_binfmt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __register_binfmt(struct linux_binfmt *fmt, int insert);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812dae70)
Location: fs/exec.c:83
Inline: True
Direct callers:
  - fs/binfmt_script.c:init_script_binfmt
  - fs/binfmt_elf.c:init_elf_binfmt
  - fs/compat_binfmt_elf.c:init_compat_elf_binfmt
```
**Symbols:**

```
ffffffff812dae70-ffffffff812daeec: __register_binfmt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __register_binfmt(struct linux_binfmt *fmt, int insert);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812ebd70)
Location: fs/exec.c:83
Inline: True
Direct callers:
  - fs/binfmt_script.c:init_script_binfmt
  - fs/binfmt_elf.c:init_elf_binfmt
  - fs/compat_binfmt_elf.c:init_compat_elf_binfmt
```
**Symbols:**

```
ffffffff812ebd70-ffffffff812ebdf1: __register_binfmt (STB_GLOBAL)
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
