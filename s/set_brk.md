# Function: <code>set_brk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate ⚠️</summary>

```c
int set_brk(long unsigned int start, long unsigned int end);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81321b44)
Location: fs/binfmt_elf.c:94
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff81269a40)
Location: fs/binfmt_elf.c:94
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff81321b44-ffffffff81321be2: set_brk (STB_LOCAL)
ffffffff81269a40-ffffffff81269ae1: set_brk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate ⚠️</summary>

```c
int set_brk(long unsigned int start, long unsigned int end);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81356f11)
Location: fs/binfmt_elf.c:94
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff81295d40)
Location: fs/binfmt_elf.c:94
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff81356f11-ffffffff81356f70: set_brk (STB_LOCAL)
ffffffff81295d40-ffffffff81295da0: set_brk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate ⚠️</summary>

```c
int set_brk(long unsigned int start, long unsigned int end);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff8136d388)
Location: fs/binfmt_elf.c:94
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff8136d918)
Location: fs/binfmt_elf.c:94
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff8136d388-ffffffff8136d3e7: set_brk (STB_LOCAL)
ffffffff8136d918-ffffffff8136d977: set_brk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate ⚠️</summary>

```c
int set_brk(long unsigned int start, long unsigned int end, int prot);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff812b70a1)
Location: fs/binfmt_elf.c:98
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff812b7a70)
Location: fs/binfmt_elf.c:98
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff812b70a1-ffffffff812b710d: set_brk (STB_LOCAL)
ffffffff812b7a70-ffffffff812b7add: set_brk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate ⚠️</summary>

```c
int set_brk(long unsigned int start, long unsigned int end, int prot);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff812da98f)
Location: fs/binfmt_elf.c:103
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff812db2b0)
Location: fs/binfmt_elf.c:103
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff812da98f-ffffffff812da9fb: set_brk (STB_LOCAL)
ffffffff812db2b0-ffffffff812db31d: set_brk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate ⚠️</summary>

```c
int set_brk(long unsigned int start, long unsigned int end, int prot);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81303550)
Location: fs/binfmt_elf.c:103
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff81306c30)
Location: fs/binfmt_elf.c:103
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff81303550-ffffffff813035bd: set_brk (STB_LOCAL)
ffffffff81306c30-ffffffff81306c9d: set_brk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate ⚠️</summary>

```c
int set_brk(long unsigned int start, long unsigned int end, int prot);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81318c50)
Location: fs/binfmt_elf.c:103
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff8131c3a0)
Location: fs/binfmt_elf.c:103
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff81318c50-ffffffff81318cbd: set_brk (STB_LOCAL)
ffffffff8131c3a0-ffffffff8131c40d: set_brk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate ⚠️</summary>

```c
int set_brk(long unsigned int start, long unsigned int end, int prot);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81340580)
Location: fs/binfmt_elf.c:102
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff81343c50)
Location: fs/binfmt_elf.c:102
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff81340580-ffffffff813405ed: set_brk (STB_LOCAL)
ffffffff81343c50-ffffffff81343cbd: set_brk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate ⚠️</summary>

```c
int set_brk(long unsigned int start, long unsigned int end, int prot);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81358ad0)
Location: fs/binfmt_elf.c:102
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff8135c040)
Location: fs/binfmt_elf.c:102
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff81358ad0-ffffffff81358b3d: set_brk (STB_LOCAL)
ffffffff8135c040-ffffffff8135c0ad: set_brk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate ⚠️</summary>

```c
int set_brk(long unsigned int start, long unsigned int end, int prot);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff8139efe0)
Location: fs/binfmt_elf.c:109
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff813a20f0)
Location: fs/binfmt_elf.c:109
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff8139efe0-ffffffff8139f050: set_brk (STB_LOCAL)
ffffffff813a20f0-ffffffff813a2160: set_brk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate ⚠️</summary>

```c
int set_brk(long unsigned int start, long unsigned int end, int prot);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff813b0610)
Location: fs/binfmt_elf.c:110
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff813b3120)
Location: fs/binfmt_elf.c:110
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff813b0610-ffffffff813b0680: set_brk (STB_LOCAL)
ffffffff813b3120-ffffffff813b3190: set_brk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate ⚠️</summary>

```c
int set_brk(long unsigned int start, long unsigned int end, int prot);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff813b7750)
Location: fs/binfmt_elf.c:110
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff813ba100)
Location: fs/binfmt_elf.c:110
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff813b7750-ffffffff813b77c0: set_brk (STB_LOCAL)
ffffffff813ba100-ffffffff813ba170: set_brk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate ⚠️</summary>

```c
int set_brk(long unsigned int start, long unsigned int end, int prot);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81407430)
Location: fs/binfmt_elf.c:110
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff81409df0)
Location: fs/binfmt_elf.c:110
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff81407430-ffffffff814074a0: set_brk (STB_LOCAL)
ffffffff81409df0-ffffffff81409e60: set_brk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate ⚠️</summary>

```c
int set_brk(long unsigned int start, long unsigned int end, int prot);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff8147c120)
Location: fs/binfmt_elf.c:112
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff8147ead0)
Location: fs/binfmt_elf.c:112
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff8147c120-ffffffff8147c1a4: set_brk (STB_LOCAL)
ffffffff8147ead0-ffffffff8147eb54: set_brk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate ⚠️</summary>

```c
int set_brk(long unsigned int start, long unsigned int end, int prot);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff8150ea70)
Location: fs/binfmt_elf.c:112
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff81511750)
Location: fs/binfmt_elf.c:112
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff8150ea70-ffffffff8150eaf4: set_brk (STB_LOCAL)
ffffffff81511750-ffffffff815117d4: set_brk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate ⚠️</summary>

```c
int set_brk(long unsigned int start, long unsigned int end, int prot);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81546230)
Location: fs/binfmt_elf.c:113
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff81549030)
Location: fs/binfmt_elf.c:113
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff81546230-ffffffff815462b4: set_brk (STB_LOCAL)
ffffffff81549030-ffffffff815490b4: set_brk (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate ⚠️</summary>

```c
int set_brk(long unsigned int start, long unsigned int end, int prot);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffff80001041dfe8)
Location: fs/binfmt_elf.c:102
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffff800010421778)
Location: fs/binfmt_elf.c:102
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffff80001041dfe8-ffff80001041e06c: set_brk (STB_LOCAL)
ffff800010421778-ffff8000104217fc: set_brk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int set_brk(long unsigned int start, long unsigned int end, int prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (c05e68a0)
Location: fs/binfmt_elf.c:102
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
c05e68a0-c05e691c: set_brk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate ⚠️</summary>

```c
int set_brk(long unsigned int start, long unsigned int end, int prot);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (c00000000052c9b0)
Location: fs/binfmt_elf.c:102
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (c000000000530680)
Location: fs/binfmt_elf.c:102
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
c00000000052c9b0-c00000000052ca48: set_brk (STB_LOCAL)
c000000000530680-c000000000530718: set_brk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int set_brk(long unsigned int start, long unsigned int end, int prot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffe0002c0760)
Location: fs/binfmt_elf.c:102
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffe0002c0760-ffffffe0002c07d2: set_brk (STB_LOCAL)
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
int set_brk(long unsigned int start, long unsigned int end, int prot);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff813510b0)
Location: fs/binfmt_elf.c:102
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff81354620)
Location: fs/binfmt_elf.c:102
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff813510b0-ffffffff8135111d: set_brk (STB_LOCAL)
ffffffff81354620-ffffffff8135468d: set_brk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate ⚠️</summary>

```c
int set_brk(long unsigned int start, long unsigned int end, int prot);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81341d90)
Location: fs/binfmt_elf.c:102
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff813452e0)
Location: fs/binfmt_elf.c:102
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff81341d90-ffffffff81341dfd: set_brk (STB_LOCAL)
ffffffff813452e0-ffffffff8134534d: set_brk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate ⚠️</summary>

```c
int set_brk(long unsigned int start, long unsigned int end, int prot);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff8134eb80)
Location: fs/binfmt_elf.c:102
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff813520f0)
Location: fs/binfmt_elf.c:102
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff8134eb80-ffffffff8134ebed: set_brk (STB_LOCAL)
ffffffff813520f0-ffffffff8135215d: set_brk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate ⚠️</summary>

```c
int set_brk(long unsigned int start, long unsigned int end, int prot);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81362100)
Location: fs/binfmt_elf.c:102
Inline: False
Direct callers:
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff813658b0)
Location: fs/binfmt_elf.c:102
Inline: False
Direct callers:
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
  - fs/compat_binfmt_elf.c:load_elf_binary
```
**Symbols:**

```
ffffffff81362100-ffffffff8136216d: set_brk (STB_LOCAL)
ffffffff813658b0-ffffffff8136591d: set_brk (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int prot</code>
</li>
</ul>
</details>
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
